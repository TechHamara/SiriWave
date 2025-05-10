<div align="center">
<h1><kbd>🧩 SiriWave</kbd></h1>
An extension for MIT App Inventor 2.<br>
A custom component developed by th using Fast, designed to simulate a Siri-like wave animation.<br><a href='https://t.me/techhamara91/' target='_blank'>Telegram</a> | <a href='https://github.com/TechHamara/' target='_blank'>GitHub</a><br><a href='https://techhamara.blogspot.com/' target='_blank'>Blogger</a> | <a href='https://m.youtube.com/c/TECHHAMARA?sub_confirmation=1' target='_blank'>YouTube</a><br><a href='https://github.com/TechHamara/Th_Free_Extensions' target='_blank'><small><u>Find More Extension</u></small></a><br><a href='https://github.com/TechHamara/Th_Extensions_List/blob/main/LICENSE.md#terms-and-conditions-for-the-extension' target='_blank'><small><u>Terms & Conditions</u></small></a>
</div>

## 📝 Specifications
* **
📦 **Package:** io.th.siriwave
💾 **Size:** 12.57 KB
⚙️ **Version:** 1.0
📱 **Minimum API Level:** 7
📅 **Updated On:** [date=2025-05-10 timezone="Asia/Calcutta"]
💻 **Built & documented using:** [FAST](https://community.appinventor.mit.edu/t/fast-an-efficient-way-to-build-extensions/129103?u=jewel) <small><mark>v2.8.4</mark></small>

## <kbd>Events:</kbd>
**SiriWave** has total 3 events.

### OnStart
Triggered when the wave animation starts.

### OnStop
Triggered when the wave animation stops.

### OnError
Triggered when an error occurs.

| Parameter | Type
| - | - |
| message | text

## <kbd>Methods:</kbd>
**SiriWave** has total 17 methods.

### Initialize
Initialize the SiriWaveView inside a Vertical or Horizontal Arrangement.

| Parameter | Type
| - | - |
| arrangement | component

### BackgroundColorRGB
Set background color using RGB values

| Parameter | Type
| - | - |
| red | number
| green | number
| blue | number

### BackgroundColorARGB
Set background color using ARGB values (with alpha transparency). Example: SetBackgroundColorARGB(255, 255, 0, 0) for a fully opaque red background.

| Parameter | Type
| - | - |
| alpha | number
| red | number
| green | number
| blue | number

### TransparentBackground
Set transparent background

### GradientBackground
Set gradient background

| Parameter | Type
| - | - |
| startColor | number
| endColor | number
| isVertical | boolean

### StartAnimation
Start the wave animation.

### StopAnimation
Stop the wave animation.

### WaveSpeed
Get current wave animation speed.

* Return type: `number`

### StrokeWidth
Get current wave stroke width.

* Return type: `number`

### Reset
Reset the wave to its initial state.

### WaveColorRGB
Set the wave color using RGB values (0-255 for each component).

| Parameter | Type
| - | - |
| red | number
| green | number
| blue | number

### WaveColorARGB
Set the wave color with alpha transparency (0-255 for each component).

| Parameter | Type
| - | - |
| alpha | number
| red | number
| green | number
| blue | number

### WaveColorBlue
Set wave color to a predefined blue color (#2196F3).

### WaveColorRed
Set wave color to a predefined red color (#F44336).

### WaveColorGreen
Set wave color to a predefined green color (#4CAF50).

### WaveColorWhite
Set wave color to white (#FFFFFF).

### WaveColorBlack
Set wave color to black (#000000).

## <kbd>Setters:</kbd>
**SiriWave** has total 2 setter properties.

### BackgroundColor
Set background color of the view

* Input type: `number`

### BackgroundAlpha
Set background alpha (transparency) value (0-255)

* Input type: `number`

## <kbd>Getters:</kbd>
**SiriWave** has total 15 getter properties.

### White
Returns the color White

* Return type: `number`

### Black
Returns the color Black

* Return type: `number`

### Red
Returns the color Red

* Return type: `number`

### Green
Returns the color Green

* Return type: `number`

### Blue
Returns the color Blue

* Return type: `number`

### Transparent
Returns a transparent color

* Return type: `number`

### WaveHeight
Get the current wave height.

* Return type: `number`

### Amplitude
Get the current amplitude of the wave.

* Return type: `number`

### IdleAmplitude
Get the current idle amplitude.

* Return type: `number`

### Frequency
Get the Wave Frequency of the wave.

* Return type: `number`

### WaveNumber
Get the Wave Number of the wave.

* Return type: `number`

### PhaseShift
Get the current phase shift value.

* Return type: `number`

### WaveVerticalPosition
Get the current wave vertical position.

* Return type: `number`

### InitialPhaseOffset
Get the current initial phase offset.

* Return type: `number`

### WaveColor
Get the current wave color as a hex string.

* Return type: `text`

