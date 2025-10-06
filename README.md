# Animation Re-Timer

Animation Re-Timer is a complete and robust toolkit designed to streamline the animation re-timing process in Blender. Forget manual calculations and tedious keyframe selections. With this addon, you can scale, offset, and manipulate the timing of your entire scene—or just a specific selection—with precision and ease.

Built to be fully compatible with Blender 4.5's modern animation system, including Slotted and Shared Actions, Animation Kit correctly handles all animation data types: objects, materials, shape keys, bones, drivers, and more.

It's the essential tool for any animator who needs to make global or local timing adjustments quickly and reliably.

Key Features

## 1. Unified & Powerful Operators

A single, intuitive interface for all your re-timing needs. Each operator can work in two main scopes:





All Scene: Affects every animated element in your .blend file for global changes.



Selected Only: Precisely targets only the selected objects and all their related animation data (materials, modifiers, bones, etc.).

## 2. Advanced Scale Animation

Go beyond simple scaling. The Scale operator gives you three ways to calculate your timing adjustments:





Factor: Scale by a direct multiplier (e.g., 2.0 for double the length).



Target Duration: Define the exact number of frames your animation should have.



Frame Rate Conversion: Automatically convert animations from one FPS to another (e.g., 30 -> 24), with an option to also change the scene's frame rate.

## 3. Smart Offset Animation

Move your animations on the timeline with precision.





All: Shifts the entire animation block, preserving its duration.



From Pivot: Creates or reduces time from a specific frame onwards, rippling the change through the rest of the timeline.

## 4. Intuitive Remove Space

Quickly eliminate pauses or gaps in your animation.





Define a Start and End frame, and the operator will delete the empty space, automatically moving everything that comes after it.



It safely deletes any keyframes found within the removed range and warns you in the UI before you commit.

## 5. Comprehensive & Safe

Animation Kit is built to be robust. It correctly handles all major animation data, including Object Transforms, Shape Keys, Drivers, Materials, Nodes, Constraints, Pose Bones, and NLA Strips. All operations are wrapped for safety and are fully undoable (Ctrl+Z).
