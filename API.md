# Planned Breaking API Changes

The following list includes the APIs that will be removed in Electron 2.0.

There is no timetable for when this release will occur but deprecation
warnings will be added at least 90 days beforehand.

```js
// Deprecated
clipboard.readRtf()
// Replace with
clipboard.readRTF()

// Deprecated
clipboard.writeRtf()
// Replace with
clipboard.writeRTF()

// Deprecated
clipboard.readHtml()
// Replace with
clipboard.readHTML()

// Deprecated
clipboard.writeHtml()
// Replace with
clipboard.writeHTML()

// Deprecated
nativeImage.toPng()
// Replace with
nativeImage.toPNG()

// Deprecated
nativeImage.toJpeg()
// Replace with
nativeImage.toJPEG()

// Deprecated
new BrowserWindow({webPreferences: {blinkFeatures: ''}})
// Replace with
new BrowserWindow({webPreferences: {enableBlinkFeatures: ''}})

// Deprecated
tray.setHighlightMode(true)
// Replace with
tray.setHighlightMode('on')

// Deprecated
tray.setHighlightMode(false)
// Replace with
tray.setHighlightMode('off')

// Deprecated
webContents.openDevTools({detach: true})
// Replace with
webContents.openDevTools({mode: 'detach'})
```
