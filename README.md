
# Analog.io — Native Android Recreation

Recreating [Analog.io](https://analog.io/) as a native Android application using **Kotlin and Jetpack Compose**.

## Libraries

-   **SceneView:** Renders 3D scenes and models.
    
-   **Media3 ExoPlayer:** Plays videos and streaming content. Scroll-controlled video requires additional synchronization logic. It also cache the video while it plays.
    
-   **Haze:** Adds blur and frosted-glass effects.
    
-   **Coil:** Loads remote images and thumbnails.
    

## How They Work Together

Compose Vertical Pager manages the UI and scrolling. SceneView renders 3D content, Media3 handles video, Haze styles overlays, and Coil loads images.

## Pending Items

- Create the menu while clicking the Hamburger button.
- Optimize tha layout for Tablet, Lanscape and Foldables.
- Handling the links and open it in the browser tab.
- News api and page implementation
- Careers page implementation
    

**Note:** These are verification tasks, not confirmed defects. Video playback alone does not provide scroll-driven animation.
