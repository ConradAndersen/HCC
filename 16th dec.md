# Tangible Bits: Beyond Pixels #

### Comments ###

* 	The paper is about using real world objects to manipulate bits in programs, also called "Tangible User Interfaces" (TUI).

* 	The paper argue that the current models of interaction with said bits are not great. When a user interact with a UI,
	they use a mouse and keyboard to mainpulate UI elements, but the mouse and keyboard is not in any way connected to the actual UI and are instead just used as remote controls.

*   The paper uses an example of a TUI which is a representation of a city, the TUI uses different tangible items for manipulating the environment.
	Buildings are real objects that can be moved, time of day can be changed using a clock, wind can be changed using the "wind tool", and build material can be changed between glass and brick using the "material wand". When manipulating real objects, the untangible bits are represented using a projector.

*   The paper uses this example to explain the key properties of TUI after which the paper gives an overview of seven different genres of TUI.

*	I especially liked the Ambient Media: [Live Wire (Dangling String) by Natalie Jeremijenko](http://www.ubiq.com/weiser/calmtech/calmtech.htm)

### Questions ###

*   The paper states that manipulation of bits is easier than manipulation of atoms, this also limit the kind of TUIs that are possible to create.

    If instead of creating actual tangible atoms, it would be possible to create a VR experience which included
    vision (A head mounted device, able to track head movement),
    hands projected into 3D space (Hand tracking, could be mounted to the headmounted device),
    and feeling (Could be created using gloves).
    
    By doing this, it is easier to create an experience in which the user is able to actually manipulate tangible items.

    The key properties of TUI should be fulfilled by the above:

    1. Computional coupling and perceptual coupling as done by projecting the user into 3D space instead of projecting onto the real world.

    2. The untangible nature of bits is tangible by emulating the different human senses (Except weight).
    
    3. When manipulating in 3D space, it is easy to introduce constraints on items.

    One of the problems with simlations is slow downs, what other problems are there?
    
    Would this even be considered a tangible user interface?

# Graspables Revisited #

### Comments \#1 ###

*	The paper is comparing the use of tangible interfaces to multi-touch input, as multi-touch has various potential benefits such as dynamic content,
	which is impossible with TUI.

*	The experiments are done to let designers make an informed decision between different input types for different task,
	and because prior studies had shown that TUIs were better as input devices especially for eye-free manipulation.
	They argue that it may also be the case for TUIs compared to multi-touch.

*	The paper is testing manipulation and acquisition, using tangible shapes, on screen multi-touch, and a mouse and puck.

*	The twelve particpants were paid and included 4 females and 2 left-handed,
	all particpants had a CS background and had little to no prior experince using any of the three input methods.

*	The experiments was done using a Microsoft Surface,
	which uses [IR light and cameras to show touches](http://www.ledsmagazine.com/content/dam/leds/migrated/objects/features/10/9/9/1309ledsweb_design6.gif).

##### Manipulation #####

*	The participants have to move a ruler (yellow color) onto another ruler shape (blue color) and align a slider.

*	The shapes were outlined with either a yellow or blue glow, ensuring that the foam ruler would not obsure the target.
	Around the glow were six dots that would light up in red, when within 5 pixels of each other,
	indicating sufficent match.

*	The experiment assumes that the user have already aquired a control widget.

*	The results showed that manipulation was fastest using the tangible foam ruler, followed by the multi-touch interface.

##### Acquistion #####

*	The experiment included four different shapes, a square that could be moved and rotated, a circle with the same properties,
	a ruler like the one in the previous experiment, and a square that could be moved, rotated and streched.

*	The participants had keep all four shapes on top of the blue pseudo randomly moving targets.

*	The results again showed that the tangible shapes had the best accuracy and were moved most.
	All except one particpant preferred the tangible shapes, the one preferred the mouse and puck.

### Comments \#2 ###

*	The acqusition experiment was recorded for later analysis.
	I find it very interresting that usage of hands was different for tangible and multi-touch, as these input methodes are so a like.
	The contact points used, shows that multi-touch is an unnatural way of interaction, as to assert greater control,
	the particpants had to use less fingers instead of more fingers, as one would do in the real world.

*	The video also showed that the participants had what is called "Exit errors" when disengaging from multi-touch object,
	and that the participants used mostly two fingers for all multi-touch operations, while they used more complex patterns for tangible objects.

*	I think that the limitations and experiment setups in this paper are very well explained, compared to some of the previous papers.

### Questions ###

*	The Exit errors are a significant discovery, and the paper has some ideas about how to fix this problem.

	Is this problem as pronounced when using other types of touch technologies like capacitive touch,
	or are measures against this problem already implemented, as I do not see this problem using any touch devices.

*	The participants are using more complex patterns for tangible objects.
	
	Could this be caused by the haptic feedback from using tangible objects, which does not requires one to actually look directly at the object while
	operating them *concurrent unimanualism*.
	While touch targets require that the participant look directly at the touch target to hit it requiring focus on that object. 