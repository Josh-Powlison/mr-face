# Mr. Face

Mr. Face wants to be your friend. He wants to watch you in your sleep. He wants to communicate you with the rest of the time. But to do that, he needs to move!

An animation experiment, Mr. Face is animated using a customized object and animation system and CSS transitions. By default, Mr. Face cycles through several expressions, but you can create your own animations for him!

Basically, you feed an object into an animation function, and it creates keyframes based on that object that specifies what changes and when. You may decide that at 500 milliseconds, the left eye completely closes, and then opens again at 750 milliseconds. You may decide that his mouth is agape, but he looks around in his shock. You may turn that smile upside-down and make Mr. Face into Mr. Grumpy. It's up to you!

Of course, be careful with animations- you're determining when a value _starts_ to shift, not when it finishes shifting! Make sure you're setting things up as you want them.

## Background color

Mr. Face is completely transparent besides the white color. This means you can put him on any background (and change his face color too if you want)!

## Animatable Stuff

You can twist and rotate the entire face in 3D so it's like its dark, shadowy head is turning.

You can also change the side of the eyes and how opened/closed they are. No, the eyes don't just squish using a scale transform- they actually open and close like with eyelids.

The mouth can change size and shape- using `border-radius` we can affect whether he's smiling or frowning! Curve the bottom edges and he's smiling; curve the top edges and he's frowning!

## How do I create a custom animation?

The file contains more info as well as examples, but for some sample poses you can type `test(1)` through `test(7)` in the developer console.
