This is a gesture based system for a pet in VRChat that i developed when i became burnt out in vrchat and to entertain my friends, 

Current Features ++++++++++++++++++++++++++++++++++++++++++++++++++++++
- Gesture based activation (Dual rock and roll for on and dual pointer to disable) and arm holographic menu for future tweaks and pet status
- 
- Anchors for the pet to attach on many places on body, head, either hands, both hips, lower right foot and tail ont, using only fbt natural pick and place.
- 
- Seamless right and left drop in world when hand is not moving and hand moves into open position. Will not release if hand remains in motion and will attach once near a standard anchor point.
- 
- seamless ability to throw doll into world with phyisics if hand remains above a certain velocity when the open hand gesture remains. Currently simply recall my closing right hand. This will shortly be updated to be the primary way to drop the pet into the world

- Network syncing as a primary building block, all logic to be performed on the local avatar and all animations for both local and remote to be on completely seperate layer for complete network sync and little to no late joiner issues


Current goal ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Shoulder locations, and upper arms, both feet. 

Description furter internal rambling ++++++++++++++++++++++++++++++++++++++

It is a mashup of my efforts to linkup several of the VRlabs implementations and is my first forary into truly trying to understand unitys animator system and is currently designed to be drag and drop onto the V3.1 Nardodragon.
VRCfury drag and drop, needs delete on upload markers to allow drag and drop placement of the typical binders for pet locations. 



but can be easily modified to fit any avatar. It is designed to allow expansion at all levels and is the work of many failed attemps. Any ideas of help greatly appreciated, i intend for this to be a base system for a pet to increase interactivity between users and the pets themselves. 
Mainly to be a game within an avatar and perhaps something like a tamagotchi. Currently the 2nd animator on the pet itself is limited due to a know issues with secondary animation layers running underneath the typical vr ones. 



Todo's ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Working on implementing several variations of HAI's animatior track system to allow the pet to crawl up all the major avatar bases. 


known issues +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
When i was implementing this several variantios lead to a massively scaling issue and i landed on the idea of the pinwheel animator to allow future points on the avatar to be added without having to completely rebuild every animation and restructuring. 

Certain desyncs start happening after several hours in game without reloading there seems to be some floats that seem to wander, reloading vrchat seems to fix it aswell as throwing the doll into the open world seems to help the sync a bit. I suspect a combination of sync variables that should not be as well a VRC implenenation of the constraint system is still a bit wonky as i have seen update after update referencing issues surrounding this. 

Serialization it has trouble with multiple folders across the package need those cleaned up and directory restructured. 

Make it so that it rewrites over itself without issues. 

The primary model trixie, is actually a complete rebuild from scratch Will replace with something else completely original very shortly. 

Switch the avatar into something like a blade or cool item when system deactivates so that it appears to be a simple avatar object.
