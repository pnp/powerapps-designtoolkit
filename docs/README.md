# Light Toolkit

## Components

![basic components](/docs/assets/light%20components/basic-components.png)

![complex components](/docs/assets/light%20components/complex-components.png)

### TextInput

* **inputWidth** : Width of the component itself
* **inputHeight** : Height of the component itself
* **accentColor**:  defaults to `ColorValue("#167aad")`, determines **BorderColor** and TextColor of the `lbl_title`
* **labelText**: defaults to `Tell us more!`, determines the **Text** of `lbl_title`
* **textColor**: defaults to `Black`, determines the **Color** of the `lbl_title`
* **errorText**: defaults to `"This can't be empty."`, determines the **Text** of the `lbl_error`. Will be shown **OnChange** in case the **Text** is empty
* **errorColor**: defaults to `Red`, determines the **Color** of the `lbl_error`

The TextInput control itself will adjust in its size to a resize of the component and always be 10px less than the component width/height.

![Textinput Component](/docs/assets/light%20components/TextInput.gif)

### EmailInput

* **inputWidth** : Width of the component itself
* **inputHeight** : Height of the component itself
* **accentColor**:  defaults to `ColorValue("#167aad")`, determines **BorderColor** and TextColor of the `lbl_title`
* **labelText**: defaults to `Email`, determines the **Text** of `lbl_title`
* **textColor**: defaults to `Black`, determines the **Color** of the `TextInput`
* **errorText**: defaults to `"This is not a valid Email."`, determines the **Text** of the `lbl_error`. Will be shown **OnChange** in case the **Text** is doesn't match the RegEx pattern of an Email.
* **errorColor**: defaults to `Red`, determines the **Color** of the `lbl_error`

The TextInput control itself will adjust in its size to a resize of the component and always be 10px less than the component width/height.

![Emailinput Component](/docs/assets/light%20components/EmailInput.gif)

### NumberField - left

* **numberFieldWidth** : Width of the component itself
* **numberFieldHeight** : Height of the component itself
* **accentColor**:  defaults to `ColorValue("#167aad")`, determines **BorderColor** and **TextColor** of the `lbl_title`, also **Color** of the `icon_up` and `icon_down`
* **labelText**: defaults to `Amount`, determines the **Text** of `lbl_title`
* **textColor**: defaults to `Black`, determines the **Color** of the `TextInput`
* **unitFill**: defaults to `ColorFade(DarkGray, 60%)`, determines the **Fill** of the `btn_unit`
* **unitText**: defaults to `px`, determines the **Text** of the `btn_unit`
* **errorText**: defaults to `"This is not a whole number"`, determines the **Text** of the `lbl_error`. Will be shown **OnChange** in case the **Text** is not a whole number.
* **errorColor**: defaults to `Red`, determines the **Color** of the `lbl_error`

The TextInput control itself will adjust in its size to a resize of the component and always be 100px less than the component width and 40px less than the component height. (This is to make room for the error text)

![Numberfield component](/docs/assets/light%20components/Numberfield.gif)

### NumberField - right

* **numberFieldWidth** : Width of the component itself
* **numberFieldHeight** : Height of the component itself
* **accentColor**:  defaults to `ColorValue("#167aad")`, determines **BorderColor** and **TextColor** of the `lbl_title`
* **labelText**: defaults to `Budget`, determines the **Text** of `lbl_title`
* **textColor**: defaults to `Black`, determines the **Color** of the `TextInput`
* **unitFill**: defaults to `ColorFade(DarkGray, 60%)`, determines the **Fill** of the `btn_unit**
* **unitText**: defaults to `$`, determines the **Text** of the `btn_unit**
* **errorText**: defaults to `"This is not a whole number"`, determines the **Text** of the `lbl_error`. Will be shown **OnChange** in case the **Text** is not a whole number.
* **errorColor**: defaults to `Red`, determines the **Color** of the `lbl_error`

The TextInput control itself will adjust in its size to a resize of the component and always be 100px less than the component width and 40px less than the component height. (This is to make room for the error text)

![Numberfield component](/docs/assets/light%20components/Numberfield.gif)

### simple Toggle

* **inactiveFillColor**: defaults to `ColorFade(DarkGray, 60%)`, determines **Fill** of `btn_toggleBg` in inactive state
* **activeFillColor**: defaults to `ColorValue("#167aad")`, determines **Fill** of `btn_toggleBg` in active state
* **inactiveLabel**: defaults to `no`, determines **Text** of `lbl_toggle` in inactive state
* **activeLabel**: defaults to `yes`, determines **Text** of `lbl_toggle` in active state
* **circleColor**: defaults to `White`, determines the **Fill** of  `Circle`
* **textColor**: defaults to `Black`, determines the **Color** of the `TextInput`
* **rating** (Output property), returns the `sli_toggle.Value`

![Toggle component](/docs/assets/light%20components/Toggle.gif)

### Dropdown

* **dropdownWidth** : Width of the component itself
* **dropdownHeight** : Height of the component itself
* **galleryHeight**: defaults to `174`, determines the **Height** of the `Gallery`
* **accentColor**:  defaults to `ColorValue("#167aad")`, determines **BorderColor** of the `lbl_title`, also the **Color** of the `icon_chev` an of `TextInput`
* **galleryContent**: defaults to sample data, determines content of the gallery
* **labelText**: defaults to `Select an action`, determines the **Text** of `lbl_title`
* **textColor**: defaults to `Black`, determines the **Color** of the `TextInput`
* **hoverFill**: defaults to `ColorFade(DarkGray, 60%)`, determines **Fill** of the `btn_dropdown_bg`
* **selectedId** (Output property), returns the `id` of the selected Item

The TextInput control itself will adjust in its size to a resize of the component and always be 10px less than the component width/height.

![Dropdown component](/docs/assets/light%20components/Dropdown.gif)

### Multi-select Dropdown

* **dropdownWidth** : Width of the component itself
* **dropdownHeight** : Height of the component itself
* **galleryHeight**: defaults to `174`, determines the **Height** of the `Gallery`
* **accentColor**:  defaults to `ColorValue("#167aad")`, determines **BorderColor** and TextColor of the `lbl_title`, also the **Color** of the `icon_chev` and of th `TextInput`
* **galleryContent**: defaults to sample data, determines content of the gallery
* **labelText**: defaults to `Select your actions`, determines the **Text** of `lbl_title`
* **textColor**: defaults to `Black`, determines the **Color** of the `TextInput`
* **hoverFill**: defaults to `ColorFade(DarkGray, 60%)`, determines **Fill** of the `btn_dropdown_bg`
* **selectedItems** (Output property), returns the selected items the `gallery` as a string

The TextInput control itself will adjust in its size to a resize of the component and always be 10px less than the component width/height.

![Dropdown component](/docs/assets/light%20components/Multiselect.gif)

### Likert

* **accentColor**:  defaults to `ColorValue("#167aad")`, determines **Color** of the `lbl_Rating`, also the **Color** of the `icn_Emoji` in active state and **RailFill** and **ValueFill** of the `sli_Rating`
* **primaryColor**: defaults to `DarkGray`, determines the **Fill** of the **HandleFill** of the `sli_Rating` and the **Color** of `lbl_Rating` and `icn_Emoji` in inactive state
* **LikertContent**: defaults to sampledata, determines content of the gallery
* **rating** (Output property), returns the `sli_rating.Value` which corresponds to the `Id` of the selected item of the `Gallery`

![Likert component](/docs/assets/light%20components/Likert.gif)

### Battery

* **colorPalette**, defaults to `{color1:ColorValue("#0E566C"),color2:ColorValue("#168aad"),color3:ColorValue("#f5f5f5"),color4:ColorValue("#8a4f7d"),color5:ColorValue("#887880")}`, determines **Fill** of `btn_compartments` in conjunction with the **colorIntensity** property.
* **colorIntensity**, defaults to `0.5`, determines the percentage of **Fill** of `btn_compartments`
* **textColor**, defaults to `Black`, determines the **Color** of `btn_pill`
* **batteryContent**, defaults `{stage5:"Crisis",stage4:"Stressed",stage3:"Languishing",stage2:"Coping",stage1:"Well"}`, determines content of the `Gallery`
* **rating** (Output property), returns the `sli_slide.Value`

![Battery component](/docs/assets/light%20components/Battery.gif)

### Toggle with icons

* **inactiveFillColor**: defaults to `ColorFade(DarkGray, 60%)`, determines **Fill** of `btn_toggleBg` in inactive state
* **activeFillColor**: defaults to `ColorValue("#167aad")`, determines **Fill** of `btn_toggleBg` in active state
* **inactiveLabel**: defaults to `no`, determines **Text** of `lbl_toggle` in inactive state
* **activeLabel**: defaults to `yes`, determines **Text** of `lbl_toggle` in active state
* **circleColor**: defaults to `White`, determines the **Fill** of  `Circle`
* **textColor**: defaults to `Black`, determines the **Color** of the `TextInput`
* **rating** (Output property), returns the `sli_swipe.Value`

### Togglebox

* **accentColor**: defaults to `ColorValue("#167aad")` , determines **background-color** of `html_ToggleBox` in active state
* **primaryFill**: defaults to `ColorFade(DarkGray, 60%)`, determines **background-color** of `html_ToggleBox` in inactive state
* **defaultCheck**: defaults to `true`, determines the default value of the togglebox
* **toggleIcons**: defaults to `{TrueIcon: Icon.Check , FalseIcon: Icon.Cancel }`, determines which icons  shall be shown
* **toggleBoxCheck** (Output property), returns whether the toggle value is `true` or `false`

### Switch

* **switchWidth** : **Width** of the `btn_bg`
* **switchHeight** : **Height** of `btn_bg`
* **backgroundFill**, defaults to `ColorFade(DarkGray, 60%)` of the `btn_bg`
* **iconColor**, defaults to `ColorValue("#167aad")` , determines **Fill** of `img_Moon` and `img_Sun`
* **rating** (Output property), returns the value of `sli_slide`

![toggle components](/docs/assets/light%20components/Toggles.gif)

### progressbar

* **barMaxValue**, defaults to `100`, determines the maximum value
* **barCurrentValue**, defaults to `gbl_value`, which shall be used in the app to indicate the progress - in the gif its hooked to a `slider.Value`. Determines the **Width** of `btn_progress`
* **barMaxFill**, defaults to `Transparent`, determines the **Fill** og the `btn_Total`
* **barCurrentFill**, defaults to `ColorFade(DarkGray, 60%)`, determines the **Fill** of `btn_Current`
* **barWidth**, defaults to `200`, determines the **Width** of the `btn_Total`
* **BarHeight**, defaults to `42`, determines the **Height** of the `btn_Total`
* **accentColor**, defaults to `ColorValue("#167aad")` , determines the **Color**of the `btn_barCurrent`

### progress donut

* **accentColor**: defaults to `ColorValue("#167aad")`, determines the **Fill** of the `CurrentCircle`
* **primaryColor**: defaults to `"ColorFade(DarkGray, 60%)"`, determines the **Fill** of the `BackgroundCircle`

![progress components](assets/light%20components/progress.gif)

The component works with a hidden slider.

### Likert pill

* **colorPalette**: Defaults to `{color1:ColorValue("#0E566C"),color2:ColorValue("#168aad"),color3:ColorValue("#f5f5f5"),color4:ColorValue("#8a4f7d"),color5:ColorValue("#887880")}`, determines **Fill** of `btn_pill` in conjunction with the **colorIntensity** property
* **colorIntensity**, defaults to `0.5`, determines the percentage of **Fill** of `btn_pill`
* **textColor**, defaults to `Black`, determines the **Color** of `btn_pill`
* **galleryContent**, defaults to `Table({Id:1,FillColor:cmp_Light_LikertPill.colorPalette.color1,Comment:"I hate it",Rating:"Strongly disagree"},{Id:2,FillColor:cmp_Light_LikertPill.colorPalette.color2,Comment:"Meh",Rating:"Disagree"},{Id:3,FillColor:cmp_Light_LikertPill.colorPalette.color3,Comment:"Doesn't excite me",Rating:"Neither"},{Id:4,FillColor:cmp_Light_LikertPill.colorPalette.color4,Comment:"That's pretty cool",Rating:"Agree"},{Id:5,FillColor:cmp_Light_LikertPill.colorPalette.color5,Comment:"Nailed it - loved it",Rating:"Strongly agree"})`, determines content of the galllery
* **rating** (Output property), returns the `sli_slide.Value`

![Likertpill component](assets/light%20components/LikertPill.gif)

### Swipe right

* **swipeWidth**: defaults to `250`, determines Width of the component
* **swipeHeight**: defaults to `80`, determines Height of the component
* **primaryColor**: defaults to `ColorFade(DarkGray, 60%)`, determines **Fill** of `btn_background`
* **secondaryColor**: defaults to `DarkGray`, determines **Fill** of `btn_swipe`
* **accentColor**: defaults to `ColorValue("#167aad")`, determines **Color** of `icon_success`
* **backgroundText1**: defaults to `"Swipe to approve"`, determines **Text** of `btn_background`in inactive state
* **backgroundText2**: defaults to `"thank you"`, determines **Text** of `btn_background` in active state
* **chevronColor1**: defaults to `ColorValue("#0C485A")`, determines the **Color** of the first Chevron in the gallery.
* **chevronColor2**: defaults to `cmp_Light_SwipeRight.accentColor`, determines the **Color** of the second Chevron in the gallery.
* **chevronColor3**: defaults to `ColorValue("#f5f5f5")`, determines the **Color** of the third Chevron in the gallery.
* **icon**: defaults to `Icon.Heart`, determines the **Icon** of `icon_success`

![swipe right component](assets/light%20components/SwipeRight.gif)

