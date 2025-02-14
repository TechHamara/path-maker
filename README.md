# path-maker
An Extension for ai2 to render animated Text and allowing for smooth animations and dynamic visual representations.

<div align="center">
<h1><kbd>🧩 PathMaker</kbd></h1>
An extension for MIT App Inventor 2.<br>
Developed by th using Fast. An Extension to render animated text paths with customizable properties such as text size, color, stroke and width settings. This component supports both synchronous and asynchronous modes for rendering text paths, allowing for smooth animations and dynamic visual representations.
</div>

## 📝 Specifications
* **
💾 **Size:** 38.11 KB <br>
⚙️ **Version:** 1.0<br>
📱 **Minimum API Level:** 7<br>
📅 **Updated On:** [date=2025-02-14 timezone="Asia/Calcutta"]<br>
💻 **Built & documented using:** [FAST-CLI](https://community.appinventor.mit.edu/t/fast-an-efficient-way-to-build-extensions/129103?u=jewel)<br>

## <kbd>Events:</kbd>
**PathMaker** has total 6 events.<br><br>

![AnimationStartBlock](https://github.com/user-attachments/assets/8a2bdddf-a57d-492e-a385-1dd6ea4ac189)
### 💛 AnimationStart
Triggered when the animation starts.

![AnimationEndBlock](https://github.com/user-attachments/assets/16a62b43-c1f1-4784-ad83-753d311d6f5c)
### 💛 AnimationEnd
Triggered when the animation ends.

![AnimationRepeatBlock](https://github.com/user-attachments/assets/c62b8d72-435e-4afd-841f-45b615005a53)
### 💛 AnimationRepeat
Triggered when the animation is repeated.

![AnimationCancelBlock](https://github.com/user-attachments/assets/6b8c0474-73b5-4397-bb25-c90883f3d644)
### 💛 AnimationCancel
Triggered when the animation is canceled.

![AnimationProgressBlock](https://github.com/user-attachments/assets/fc426336-1f6f-4da5-b2c6-0511367b3ecc)
### 💛 AnimationProgress
Triggered when the animation progress updates (in percentage).

| Parameter | Type
| - | - |
| progress | number

![AnimationCompleteBlock](https://github.com/user-attachments/assets/b6bbc53c-5ae1-4a04-acf9-399fadea0ed3)
### 💛 AnimationComplete
Triggered when the animation is completed.

## <kbd>Methods:</kbd>
**PathMaker** has total 29 methods.<br>

![InitializeTextPathBlock](https://github.com/user-attachments/assets/5bf0646a-07c8-403b-b0f5-7afb51596f13)
### 💜 InitializeTextPath
Initialize a TextPathView inside an arrangement. Pass true for Sync mode or false for Async mode.

| Parameter | Type
| - | - |
| arrangement | component
| syncMode | boolean

![SetPenPainterBlock](https://github.com/user-attachments/assets/0365b6ec-219c-45d9-b821-73812634b68a)
### 💜 SetPenPainter
Set a custom painter for the path effect (pen painter).

![StartAnimationBlock](https://github.com/user-attachments/assets/e5e5c85b-125a-483d-9d71-35e64d79d77d)
### 💜 StartAnimation
Start the path animation with default parameters (0 to 1).

![StartAnimationWithPositionsBlock](https://github.com/user-attachments/assets/a1acc0e8-a42d-4a69-9b8c-df1294c89062)
### 💜 StartAnimationWithPositions
Start the animation from the given start and end positions.

| Parameter | Type
| - | - |
| start | number
| end | number

![CustomStartAnimationBlock](https://github.com/user-attachments/assets/5c8d0f3d-4df2-41f2-b928-1d4dd92ea0d5)
### 💜 CustomStartAnimation
Start the animation with additional parameters for style and repeat count.

| Parameter | Type
| - | - |
| start | number
| end | number
| animationStyle | number
| repeatCount | number

![StopAnimationBlock](https://github.com/user-attachments/assets/b0643d83-4a26-4a17-9a9b-47a80f086f8b)
### 💜 StopAnimation
Stop the animation.

![PauseAnimationBlock](https://github.com/user-attachments/assets/b7634d4f-e1c0-4951-81e4-7ae1437e8737)
### 💜 PauseAnimation
Pause the animation.

![ResumeAnimationBlock](https://github.com/user-attachments/assets/72b208ea-c0bc-4f95-9d20-593e95c4142b)
### 💜 ResumeAnimation
Resume the animation.

![ClearBlock](https://github.com/user-attachments/assets/ca4423fc-3468-4fab-8c60-f3c5cb4b39cd)
### 💜 Clear
Clear the animation path.

![SetAnimationStyleBlock](https://github.com/user-attachments/assets/fe2f9046-6244-4d2b-9b83-c7d760b412c2)
### 💜 SetAnimationStyle
Set the animation style. 0 = Linear, 1 = Ease-In-Out.

| Parameter | Type
| - | - |
| style | number

![SetRepeatCountBlock](https://github.com/user-attachments/assets/03bbc9ad-64e1-4297-825f-c7105af3f347)
### 💜 SetRepeatCount
Set the repeat count for the animation.

| Parameter | Type
| - | - |
| count | number

![SetPercentageBlock](https://github.com/user-attachments/assets/b9894a8d-6c79-4b9f-8e92-d3b4338359ac)
### 💜 SetPercentage
Set the animation percentage manually. Value should be between 0.0 and 1.0.

| Parameter | Type
| - | - |
| percentage | number

![GetRepeatCountBlock](https://github.com/user-attachments/assets/17dfd653-a05d-4c4b-a24a-553f6ffc4d99)
### 💜 GetRepeatCount
Get the current repeat count for the animation.

![SetArrowPainterBlock](https://github.com/user-attachments/assets/96607383-539a-444c-967b-2506b38e539e)
### 💜 SetArrowPainter
Set the Arrow painter with specified radius and angle (in pixels and radians respectively)

| Parameter | Type
| - | - |
| radius | number
| angle | number

![SetFireworksPainterBlock](https://github.com/user-attachments/assets/a238dcbc-b85a-4e3a-aa35-8f18362e50fe)
### 💜 SetFireworksPainter
Set the Fireworks painter with specified radius and angle (in pixels and radians respectively)

| Parameter | Type
| - | - |
| radius | number
| angle | number

![GetCurrentPainterRadiusBlock](https://github.com/user-attachments/assets/4b800d6a-9dde-4848-b8d7-5d50c3521bed)
### 💜 GetCurrentPainterRadius
Get the current painter's radius in pixels

![GetCurrentPainterAngleBlock](https://github.com/user-attachments/assets/9d346a73-57b8-45df-8a01-8b8819e7049a)
### 💜 GetCurrentPainterAngle
Get the current painter's angle in radians

![IsRepeatTypeNoneBlock](https://github.com/user-attachments/assets/037054c7-24cd-4c07-aa19-7a02a0dee3db)
### 💜 IsRepeatTypeNone
Check if the current repeat type is NONE.

![IsRepeatTypeRestartBlock](https://github.com/user-attachments/assets/35d11e0a-67b4-4466-90a4-d08dbb951b34)
### 💜 IsRepeatTypeRestart
Check if the current repeat type is RESTART.

![IsRepeatTypeReverseBlock](https://github.com/user-attachments/assets/3a81794b-2dba-4dee-8c9d-8f8c0adb75fe)
### 💜 IsRepeatTypeReverse
Check if the current repeat type is REVERSE.

![CalculateAroundBlock](https://github.com/user-attachments/assets/c90e2885-a66e-429c-8b34-da6e68959ea5)
### 💜 CalculateAround
Calculate animation progress with Around strategy (for text path).

| Parameter | Type
| - | - |
| progress | number

![CalculateLinearBlock](https://github.com/user-attachments/assets/4a7fd2b1-abad-4162-b7bf-66da7a2cd03f)
### 💜 CalculateLinear
Calculate animation progress with Linear strategy

| Parameter | Type
| - | - |
| progress | number

![CalculateEaseInBlock](https://github.com/user-attachments/assets/d069591f-27bc-4b17-a633-b69d22a775f3)
### 💜 CalculateEaseIn
Calculate animation progress with Ease-In strategy

| Parameter | Type
| - | - |
| progress | number

![CalculateEaseOutBlock](https://github.com/user-attachments/assets/c3646d68-03b1-4576-9388-a7a80688f7dc)
### 💜 CalculateEaseOut
Calculate animation progress with Ease-Out strategy

| Parameter | Type
| - | - |
| progress | number

![SetCustomPathPainterBlock](https://github.com/user-attachments/assets/2b8ee23f-56bf-4937-9d07-161f9383f7f9)
### 💜 SetCustomPathPainter
Set a custom path painter effect for the text path.

| Parameter | Type
| - | - |
| radius | number
| color | number

![SetPathCalculatorBlock](https://github.com/user-attachments/assets/554f5174-74ac-4c37-b9e2-0d3f25d08359)
### 💜 SetPathCalculator
Set a predefined PathCalculator. This method allows you to specify which type of PathCalculator to use for controlling the animation path. You can choose from predefined calculators such as MidCalculator, AroundCalculator, and BlinkCalculator. The calculator determines how the start and end values of the path are calculated based on the animation progress.

Parameters:
- calculatorType: An integer representing the type of PathCalculator to use. Use constants CALCULATOR_MID = 0, CALCULATOR_AROUND = 1, CALCULATOR_BLINK = 2 to select the desired calculator.

| Parameter | Type
| - | - |
| calculatorType | number


### 💜 SetTextSize
Set the text size for the text path.

| Parameter | Type
| - | - |
| textSize | number

### 💜 SetTextColor
Set the color for the text path (in ARGB format).

| Parameter | Type
| - | - |
| color | number

### 💜 SetTextStrokeWidth
Set the stroke width for the text path (in pixels).

| Parameter | Type
| - | - |
| strokeWidth | number

## <kbd>Setters:</kbd>
**PathMaker** has total 16 setter properties.

### 💚 SetText
Set the text to be displayed as a path (in percentage).

* Input type: `text`

### 💚 SetStrokeWidth
Set the stroke width for the text path (in pixels).

* Input type: `number`

### 💚 SetRadius
Set the radius for the text path (in pixels).

* Input type: `number`

### 💚 SetAngle
Set the angle for the text path (in radians).

* Input type: `number`

### 💚 SetStart
Set the start position of the animation (0 to 1).

* Input type: `number`

### 💚 SetEnd
Set the end position of the animation (0 to 1).

* Input type: `number`

### 💚 SetShowPainter
Set whether to show the painter (true if shown) (in percentage).

* Input type: `boolean`

### 💚 SetShowPainterActually
Set whether to show the painter actually (true if shown) (in percentage).

* Input type: `boolean`

### 💚 ShowFillColorText
Set whether to show fill color text (true if shown) (in percentage).

* Input type: `boolean`

### 💚 SetDuration
Set the duration for the animation (in milliseconds).

* Input type: `number`

### 💚 SetRepeatStyle
Set the repeat style for the animation (NONE, RESTART, REVERSE).

* Input type: `number`

### 💚 SetShowInStart
Set whether to show the text path at the beginning (true if shown at the beginning).

* Input type: `boolean`

### 💚 SetTextInCenter
Set whether to center the text (true if centered).

* Input type: `boolean`

### 💚 SetPaintStrokeWidth
Set the width of the paint effect stroke (in pixels).

* Input type: `number`

### 💚 SetPaintStrokeColor
Set the color of the paint effect stroke (in ARGB format).

* Input type: `number`

### 💚 SetRepeatType
Set the repeat type of the animation (NONE, RESTART, REVERSE).

* Input type: `number`

## <kbd>Getters:</kbd>
**PathMaker** has total 9 getter properties.

### 🟢 Radius
Get the radius of the text path (in pixels).

* Return type: `number`

### 🟢 Start
Get the start position of the animation (0 to 1).

* Return type: `number`

### 🟢 End
Get the end position of the animation (0 to 1).

* Return type: `number`

### 🟢 AutoStart
Get the auto start setting (true if started automatically).

* Return type: `boolean`

### 🟢 ShowInStart
Get the show in start setting (true if shown at the beginning).

* Return type: `boolean`

### 🟢 TextInCenter
Get the text in center setting (true if centered).

* Return type: `boolean`

### 🟢 PaintStrokeWidth
Get the current paint stroke width (in pixels).

* Return type: `number`

### 🟢 PaintStrokeColor
Get the current paint stroke color.

* Return type: `number`

### 🟢 RepeatType
Get the current repeat type.

* Return type: `number`

### Thanks
    TechHamara
