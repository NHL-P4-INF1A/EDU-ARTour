# EDU-ARTour
## _The Interactive Augmented Reality Tour App_

EDU-ARTour is an interactive tour designed for the IT Course of NHL Stenden in Emmen.

## Features

- Made for Android
- Scan one of the EDU-ARTour logos to load a tour
- Each location in the tour has a popup with information
- Interactable objects 
    - BatteBot: Click and hold interaction
    - Web Development: Scrollable websites

## Tech

EDU-ARTour uses a number of open source projects to work properly:

- [Unreal Engine](https://unrealengine.com/) - The engine used to make the app
- [ARCore](https://docs.unrealengine.com/4.27/en-US/SharingAndReleasing/XRDevelopment/AR/ARPlatforms/ARCore/) - The plugin used to implement AR to unreal engine
- [Blender](https://www.blender.org/) - The app used to make the 3D objects 


## Conventions
- Write all commits in English
- Each branch has their own folder in the Unreal project

## Mistakes in the Github Environment

- Pushed whole development branch structure to main instead of only the most recent commit
    - There are now 27 commits in main instead of one
- Wrote commit in Dutch

## Other Mistakes/bugs
- 1 banner is reversed
- Bannertext is not translated
- Camera Permission error, first time opening the app does the camera not work
- Some translations in the main menu doesn't work
- Google won't publish the app because of Storage permission error.