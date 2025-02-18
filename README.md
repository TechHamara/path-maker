# path-maker
An Extension for ai2 to render animated Text and allowing for smooth animations and dynamic visual representations.

<div align="center">
<h1><kbd>🧩 PathMaker</kbd></h1>
An extension for MIT App Inventor 2.<br>
Developed by th using Fast. An Extension to render animated text paths with customizable properties such as text size, color, stroke and width settings. This component supports both synchronous and asynchronous modes for rendering text paths, allowing for smooth animations and dynamic visual representations.
</div>

## 📝 Specifications
* **
💾 **Size:** 46.31 KB <br>
⚙️ **Version:** 1.0<br>
📱 **Minimum API Level:** 7<br>
📅 **Updated On:** [date=2025-02-14 timezone="Asia/Calcutta"]<br>
💻 **Built & documented using:** [FAST-CLI](https://community.appinventor.mit.edu/t/fast-an-efficient-way-to-build-extensions/129103?u=jewel)
<br>
**Telegram:** [here](https://t.me/techhamara91)<br>
**Find** more Extension [here](https://github.com/TechHamara/Th_Free_Extensions)<br>
<br>
<br>

## Demo Blocks
![path-maker-blocks](https://github.com/user-attachments/assets/e523a1bb-f0d4-49db-bec8-97a748967042)

## Demo

![37df6593-d44f-4b77-8d87-1d1772d0742e.gif](https://github.com/user-attachments/assets/60b2342f-cd2d-43d9-80ad-426cba741854)

![a16e57ee-9640-4b01-9048-9b8e51e5e609.gif](https://github.com/user-attachments/assets/515c136a-9f14-4a6f-8f5b-e6e08c1a0120)

![8046cdd6-c413-48a8-adcb-02031f1e967c.gif](https://github.com/user-attachments/assets/b7f2fd51-6ff1-43fa-9b2b-7047f7f620b7)

https://github.com/user-attachments/assets/162ee7bb-e07f-4780-a5b1-bc41b9403656

![5988ea66-0cf3-4742-8ba4-cdeb2ef2ba64.gif](https://github.com/user-attachments/assets/be1eeef2-b9d4-41e8-a829-2f7abf930b96)

![7d2a9e66-5282-4be8-8b71-f184c31bc191.gif](https://github.com/user-attachments/assets/fe52abe3-c53e-4ae3-86e4-9953461f0875)

![8c27bc91-4d78-4f33-bba7-cfcddd02ca13.gif](https://github.com/user-attachments/assets/00900f6d-9c0a-4514-a0e1-6bd541b6c03d)



## <kbd>Events:</kbd>
**PathMaker** has total 5 events.<br><br>

![OnAnimationStartBlock](https://github.com/user-attachments/assets/89887ba5-f549-4c89-86a5-d457d7637278)
### 💛 OnAnimationStart
Event raised when animation starts

![OnAnimationEndBlock](https://github.com/user-attachments/assets/3d58f2e8-365f-4c8c-846e-d053e8dc9f74)
### 💛 OnAnimationEnd
Event raised when animation ends

![OnAnimationCancelBlock](https://github.com/user-attachments/assets/61756066-43f5-463b-b7e0-1ea9a9523c70)
### 💛 OnAnimationCancel
Event raised when animation is cancelled

![OnAnimationRepeatBlock](https://github.com/user-attachments/assets/a567c464-52c5-430a-8ffc-c4fa940e5218)
### 💛 OnAnimationRepeat
Event raised when animation repeats

![OnProgressChangedBlock](https://github.com/user-attachments/assets/7eb9b000-b5e5-45b7-9d30-72a46fcbbaf8)
### 💛 OnProgressChanged
Event raised when progress changes. Returns current progress value between 0 and 1

| Parameter | Type
| - | - |
| progress | number

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

![SetTextSizeBlock](https://github.com/user-attachments/assets/228eedde-a13d-4d4b-9aab-d27d370f3158)
### 💜 SetTextSize
Set the text size for the text path.

| Parameter | Type
| - | - |
| textSize | number

![SetTextColorBlock](https://github.com/user-attachments/assets/84e69da6-23e3-452e-8129-baf96a6c2fbe)
### 💜 SetTextColor
Set the color for the text path (in ARGB format).

| Parameter | Type
| - | - |
| color | number

![SetTextStrokeWidthBlock](https://github.com/user-attachments/assets/c69db906-835f-4fed-a299-437f30fdc0b0)
### 💜 SetTextStrokeWidth
Set the stroke width for the text path (in pixels).

| Parameter | Type
| - | - |
| strokeWidth | number

## <kbd>Setters:</kbd>
**PathMaker** has total 16 setter properties.

![SetTextBlock](https://github.com/user-attachments/assets/15bc3cfd-c5a6-46d4-85a1-3b860e57b1f2)
### 💚 SetText
Set the text to be displayed as a path (in percentage).

* Input type: `text`

![SetStrokeWidthBlock](https://github.com/user-attachments/assets/2d659ba5-b8a6-40eb-acb4-d8d7200f9804)
### 💚 SetStrokeWidth
Set the stroke width for the text path (in pixels).

* Input type: `number`

![SetRadiusBlock](https://github.com/user-attachments/assets/083682ed-a487-473a-91e4-18384cd74768)
### 💚 SetRadius
Set the radius for the text path (in pixels).

* Input type: `number`

![SetAngleBlock](https://github.com/user-attachments/assets/f13f5e72-f797-4b8a-8ef4-bb8c8d6705eb)
### 💚 SetAngle
Set the angle for the text path (in radians).

* Input type: `number`

![SetStartBlock](https://github.com/user-attachments/assets/de27655e-dd2f-471c-8863-864d842df5d7)
### 💚 SetStart
Set the start position of the animation (0 to 1).

* Input type: `number`

![SetEndBlock](https://github.com/user-attachments/assets/6f116a6f-30d4-4a5a-9e44-14e89ea26082)
### 💚 SetEnd
Set the end position of the animation (0 to 1).

* Input type: `number`

![SetShowPainterBlock](https://github.com/user-attachments/assets/23d17779-335c-4ed7-b365-4a2e55ab2578)
### 💚 SetShowPainter
Set whether to show the painter (true if shown) (in percentage).

* Input type: `boolean`

![SetShowPainterActuallyBlock](https://github.com/user-attachments/assets/201c202a-7268-44c2-903d-d7f8a2c68e9d)
### 💚 SetShowPainterActually
Set whether to show the painter actually (true if shown) (in percentage).

* Input type: `boolean`

![ShowFillColorTextBlock](https://github.com/user-attachments/assets/0c4c6867-f054-4463-aa9c-752ae39b38bb)
### 💚 ShowFillColorText
Set whether to show fill color text (true if shown) (in percentage).

* Input type: `boolean`

![SetDurationBlock](https://github.com/user-attachments/assets/2d8cca68-fae0-477b-9aff-e6f6e5effde9)
### 💚 SetDuration
Set the duration for the animation (in milliseconds).

* Input type: `number`

![SetRepeatStyleBlock](https://github.com/user-attachments/assets/dedbe0be-f716-4cfe-ba9d-0d76ab573cd2)
### 💚 SetRepeatStyle
Set the repeat style for the animation (NONE, RESTART, REVERSE).

* Input type: `number`

![SetShowInStartBlock](https://github.com/user-attachments/assets/0677a3e0-4f9f-426b-83a4-c7f45003bc76)
### 💚 SetShowInStart
Set whether to show the text path at the beginning (true if shown at the beginning).

* Input type: `boolean`

![SetTextInCenterBlock](https://github.com/user-attachments/assets/051d736f-04ae-4c9c-9fde-79503a693d52)
### 💚 SetTextInCenter
Set whether to center the text (true if centered).

* Input type: `boolean`

![SetPaintStrokeWidthBlock](https://github.com/user-attachments/assets/62a23d91-295a-4f51-8e81-ee859e9a3fd1)
### 💚 SetPaintStrokeWidth
Set the width of the paint effect stroke (in pixels).

* Input type: `number`

![SetPaintStrokeColorBlock](https://github.com/user-attachments/assets/156c9f80-496e-4b90-a90c-34dca081122e)
### 💚 SetPaintStrokeColor
Set the color of the paint effect stroke (in ARGB format).

* Input type: `number`

![SetRepeatTypeBlock](https://github.com/user-attachments/assets/55b80a5e-da4c-4798-a332-296412061afe)
### 💚 SetRepeatType
Set the repeat type of the animation (NONE, RESTART, REVERSE).

* Input type: `number`

## <kbd>Getters:</kbd>
**PathMaker** has total 9 getter properties.

![RadiusBlock](https://github.com/user-attachments/assets/16c4ba92-7b0b-4508-8c33-6d49adb1fa62)
### 🟢 Radius
Get the radius of the text path (in pixels).

* Return type: `number`

![StartBlock](https://github.com/user-attachments/assets/1b615cb8-56b9-4f9d-9b10-3a314c3f3532)
### 🟢 Start
Get the start position of the animation (0 to 1).

* Return type: `number`
* 
![EndBlock](https://github.com/user-attachments/assets/5a8ea9cb-4825-42fa-8b4b-6349aceb8a96)
### 🟢 End
Get the end position of the animation (0 to 1).

* Return type: `number`

![AutoStartBlock](https://github.com/user-attachments/assets/fd7c55b1-9ac8-44c8-bff8-a016a5b78ff8)
### 🟢 AutoStart
Get the auto start setting (true if started automatically).

* Return type: `boolean`

![ShowInStartBlock](https://github.com/user-attachments/assets/00b4b4f6-1888-472d-ab5c-a48ea718c425)
### 🟢 ShowInStart
Get the show in start setting (true if shown at the beginning).

* Return type: `boolean`

![TextInCenterBlock](https://github.com/user-attachments/assets/dd23c283-8db1-401e-9490-ca7f0ae0926b)
### 🟢 TextInCenter
Get the text in center setting (true if centered).

* Return type: `boolean`

![PaintStrokeWidthBlock](https://github.com/user-attachments/assets/86c90af6-0be0-4530-8937-a827bf3529d8)
### 🟢 PaintStrokeWidth
Get the current paint stroke width (in pixels).

* Return type: `number`

![PaintStrokeColorBlock](https://github.com/user-attachments/assets/b8b6b2e5-c02e-4976-9fb4-f6725e6b8fe9)
### 🟢 PaintStrokeColor
Get the current paint stroke color.

* Return type: `number`
  
![RepeatTypeBlock](https://github.com/user-attachments/assets/8e570f3e-535d-4e3c-a11c-2e848f834757)
### 🟢 RepeatType
Get the current repeat type.

* Return type: `number`

## Thanks
    TechHamara
