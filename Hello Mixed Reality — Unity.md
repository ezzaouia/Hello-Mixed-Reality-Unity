---
type: NoteCard
createdAt: 2024-12-01T08:27:43.551Z
viewedAt: 2024-12-01T15:18:59.444Z
brainstorm: true
---

# Todo Week 48, Dec 2024
## Testing last year apps

  aquarium

## Testing XR interaction samples

  deploy and test the scene

## Testing MR template

  deploy and test the scene

## Testing collab template

  deploy and test the scene

## Setting up a new scene

Take MR template and create prefabs, for left/right controllers and hands

Create a new scene

Add XR Origin

Add AR Session

## Setting up controllers

Add left/right controller

Build and test the scene

## Setting up hands

Add left/right hand

Open XR Origin and add to it the following components:

  Input Action Manager and XR Input Modality Manager

  Set up left / right controller and hand in the XR Input Modality Manager

  Add Character Controller

Build and test the scene

This will work, but not quite well, change the presets..

## Setting up hand menu

Add empty gameObject called: XR Hand Menu

Make sure to reset the transform of XR Hand Menu

Search for HandMenuRig among the assets and add it to XR Hand Menu

Inside Follow GameObject add

Search for SpatialPanelScroll and add it to Follow GameObject of HandMenuRig

Add main camera to the SpatialPanelScroll

Make sure that the transform of XR Hand Menu and HandMenuRig is reset

Build and test the scene

## Setting up passthrough

Expand SpatialPanelScroll and locate the grameObject Content inside Viewport

Search for ListItemBooleanToggle and add it to the Content

Create an empty gameObject called XR Environement

Reset the transform of XR Environement

Search for the model Environment and add it to XR Environement

Add component FadeMaterial to the Environment

Adding environement

Locate “Boolean Toggle” inside ListItemBooleanToggle and then inside the “Toggle” component of “Boolean Toggle” locate On Value Changed, then, drag the Environment model under the “Runtime Only” then in the next slot, select FadeMaterial.FadeSkybox

Build and test the scene

The background of the passthrough will black, to make it transparent, perform the following

In the main camera, locate the environment in the inspector, then make the background color: solid color with: 0, 0, 0, 0

Then add AR Camera Background and AR Camera Manager

Build and test the scene

## Setting up locomotion

Add an empty gameObject inside the XR Environment, call it Ground

Inside the Ground, add a cube

Change the transform of the cube to make as a ground platform

If you wanted change the color of the ground by creating a material

Add an empty gameObject called XR Locomotion (Reset its transform)

Inside XR Locomotion, add the prefabs, Turn and Move

Build and test the scene

## Setting up teleportation

teleportation

## Setting up interactions

  interactions

  buttons

  grab

  resize

  climp

  

  

  spawner
