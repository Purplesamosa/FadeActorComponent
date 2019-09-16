# FadeActorComponent

Can add BPC_Fade to any blueprint actor.

Will need to call Fade In / Fade Out functions on the component.

BPC_Fade has 4 public assets set to defaults.

Material to set - A material with a translucent property, a scalar parameter to be used called AlphaValue.

Curve Fade In - The curve used to fade in 

Curve Fade Out - The curve used to fade out

Sound to Play - The sound that will play on start of the fade until the fade has been completed.


Map at location - /Game/ThirdPersonBP/Maps/ThirdPersonExampleMap
Has been set up to already feature two actors using the fade in/fade out.

Using 'F' will Fade in the box to the left hand side.

Using 'V' will Fade out the box to the left hand side.

Using 'C' will toggle the fade on the box to the right.
