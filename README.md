# VR Escape Room Project

## Skills Covered
- **Blueprint Logic**
- **Inventory Management**
- **Event Dispatcher Interaction**
- **Custom Static Mesh Components**
- **Lighting Techniques**
- **Widgets Implementation**
- **VR Custom Widget Interaction**
- **VR Locomotion and Smooth Turning**
- **Dynamic Capsule Height & Position Adjustment**
- **Vector & Angle Mathematics**
- **Sound Design**
- **Trigger Boxes Utilization**
- **Visual Effects and Dynamic Materials**
- **Color Curves Understanding**
- **UI Interaction Menu and Level Selection**

## Major Decisions
- Modifying `GrabComponent` for static interactions.
- Developing `InventoryComponent` and `LeverComponent`.
- Enhancing `VRPawn` with a capsule for crouching simulation.
- Adding collision spheres on VR hands for interactive buttons.
- Creating a door with a code lock as an interactive widget.

## Interactions Implemented
- **Flashlight with Charge Widget**: Turn on/off, battery interactions.
- **Secret Wall Movement**: Activated by lever rotation.
- **Light Switch**: Controlling chest appearance.
- **Drawer Interactions**: Custom mechanics.
- **Radio**: Jazz music controls.
- **Lobby Menu**: Interactive navigation widget.
- **Code Doors**: Doors are supported by code lock that is interactable

## Problems Identified
- VR Hands Clipping: Hands going through walls.
- Locomotion Step System: Improving step sound recognition.
- Item Sizing: Adjusting sizes for backpack inventory slots (snapping dynamic size).

