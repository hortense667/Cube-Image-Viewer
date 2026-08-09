# 90 Days Cube (English Guide)

Single-file HTML app that maps up to 6 images onto a cube, lets you rearrange/edit faces on a net, and plays a Rubik-style solve demo. All image processing runs locally in your browser.

## Language Mode (`lang` URL option)

- Default: Japanese UI
- English mode: open with `?lang=en`
  - Example: `index.html?lang=en`
- The language option is preserved in:
  - share viewer URLs
  - "Open 90 Days Cube" link from viewer mode back to create mode

## Basic Usage

1. Open `index.html` in a browser
2. Select images one-by-one or in batch (up to 6)
3. Check placement on the net, swap/edit faces if needed
4. Press `Play` to run the demo

## Face Placement

- Faces are filled in this order: Top, Left, Front, Right, Back, Bottom
- Up to 6 images are accepted
- Tap a face to edit (move / zoom / rotate 90 degrees / replace image)
- Drag faces to swap positions

## Solve Demo

- Cube is scrambled, solved in reverse, pauses briefly, then restarts
- `Stop` resets the Rubik state
- Adjust speed with the slider
- Drag to rotate view, pinch/wheel to zoom

### View Effects

- `Spin`: continuous auto-rotation
- `Orientation Shift`: periodically changes orientation and spin direction

## Export

- `Save Cube PNG`
- `Save Net PNG`
- `Fullscreen`

## Sharing (Public X Flow)

### When sharing from desktop

1. Set all 6 images
2. Press `1) Copy Randomized Net`
3. Press `2) Post to X (with URL)`
4. Paste the copied net image in the X post editor, then post

### When sharing from smartphone

1. Set all 6 images
2. Press `1) Copy Share Text`
3. Press `2) Share Image for X Post` to open the X post flow
4. Attach the image, then paste the copied share text into the post body and post

Receiver flow:

- Open `Viewer:` URL from the post text
- Follow on-screen guidance and press `Read from Clipboard` after pasting/copying the image

## Notes

- `file://` local URLs are not shareable to other devices; use an `https` hosted URL
- Avoid sharing sensitive or private images
- Shared net images are viewer-oriented and may be compressed
- For posts shared from smartphone, desktop viewers usually get cleaner results by opening the attached image once in enlarged view before copying/pasting
- Browsers do not allow entering fullscreen automatically on page open; user interaction is required

## License

90 Days Cube © 2026 Satoshi Endo  
[GitHub](https://github.com/hortense667/CubeImageViewer) / [X](https://x.com/hortense667) / [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
