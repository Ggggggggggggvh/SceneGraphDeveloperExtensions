# SGDEX Sample Channel

## Roku Recommends

This sample shows a complete channel driven by a single RSS feed containing basic deep linking logic implementation.

Samples of the valid deep linking parameters:
    mediaType=episode, contentId=decbe34b64ea4ca281dc09997d0f23fd
    mediaType=episode, contentId=6c9d0951d6d74229afe4adf972b278dd
    mediaType=episode, contentId=7405a8c101ee4c9da312c426e6067044

### GridView

Primary content navigation in this sample uses a _zoom_ style GridView.
The zoom style was introduced in SGDEX v1.1 and enables a zooming animation
as the user navigates vertically within the grid.

### DetailView

Selecting a poster from the grid opens a DetailView for that piece of content.
The DetailView operates in list mode, so you can navigate left/right through the list of content using the d-pad on the remote.

### Media View

Selecting the _Play_ button on the DetailView opens a MediaView for that piece of content.
The MediaView operates in list mode without endcards, so the next video in the list will play immediately.
When the last video in the playlist finishes, the MediaView closes and the DetailView is displayed.

###### Copyright (c) 2018 Roku, Inc. All rights reserved.
