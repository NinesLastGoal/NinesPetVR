Gesture-Based Pet System for VRChat
Bring your avatar to life with an interactive, gesture-controlled pet!

This project is a labor of love, born from a desire to inject some fun and interactivity into VRChat. Frustrated with burnout, I set out to create a dynamic pet system that players could use to enhance their avatar's personality and provide engaging gameplay. This project is my first deep dive into Unity's animator system and it has been a journey!

✨ Key Features
Gesture-Based Activation:

Dual "rock and roll" hand gestures to activate the pet.

Dual "pointer" hand gestures to deactivate the pet.

Holographic Arm Menu:

Future home for in-game tweaks and pet status display.

Natural Anchor System:

Attach your pet to multiple locations on your avatar: Head, hands, hips, lower right foot, and tail.

Uses Full-Body Tracking (FBT) natural pick and place for seamless attachment.

Dynamic Drop System:

Seamless right/left drop into the world when your hand is not moving and in an open position.

Pet remains attached when hand is in motion.

Will attach to an anchor point once near it.

Physics-Based Throwing:

Throw the pet with physics when the hand velocity is above a threshold.

Currently a right-hand recall gesture, this is planned to be the primary drop method.

Robust Network Syncing:

All logic is performed on the local avatar.

All animations are performed on separate layers for both local and remote players.

Designed to minimize late joiner issues and maintain seamless performance.

🎯 Current Goals
Add more anchor points: Shoulders, upper arms, and both feet.

⚙️ Development Notes
This project is a fusion of several VRlabs implementations, pushing my understanding of Unity's animator system. It is primarily designed to be a drag-and-drop addition to the V3.1 Nardodragon using VRCfury for easy integration and anchor point setup, however it is designed to be easily modified for any avatar. This project is a compilation of many failed attempts and is designed to be a core system for future pet development. The second animator on the pet is currently limited due to known issues with animation layers. Any and all feedback is welcome!

The ultimate goal for this system is to become a base for increasing the interactivity between users and their pets. I also want to eventually add Tamagotchi style gameplay.

🚧 To-Do
Implement various versions of HAI's animator track system for better crawling.

🐛 Known Issues
Serialization: The current package has trouble with multiple folders, needs restructuring.

Self-Rewriting: Needs to be made to re-write over itself without errors.

Model Replacement: The primary model, Trixie, is currently a rebuild from scratch and will be replaced with a new original model.

Deactivation State: Currently in deactivation the pet goes invisible, would like to switch the avatar into a simple object when deactivated.

🤝 Contributions Welcome!
I'm excited to continue building on this project and would love to hear your ideas, suggestions, or any help you can offer! Let's make this a truly fun and engaging experience for VRChat!

Note: Remember to include installation instructions in your README file, or link to an install guide. Also, if you have any visuals for the project, add them! A demo video would make the project even more appealing!
