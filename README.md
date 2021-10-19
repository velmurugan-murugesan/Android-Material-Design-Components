# Android-Material-Design-Components
Material design is a comprehensive guide for visual, motion, and interaction design across platforms and devices. Google announced Material Design on June 25, 2014, at the 2014 Google I/O conference. Material Design can be used in API Level 21 (Android 5.0) and newer via the v7 appcompat library, which is used on virtually all Android devices manufactured after 2009.

Material Design will gradually be extended throughout Google’s array of web and mobile products, providing a consistent experience across all platforms and applications. Google has also released application programming interfaces (APIs) for third-party developers to incorporate the design language into their applications.

Already I have created a post for the different material components in android. In this guide, I am putting all the posts together and it will be easy to learn android material components in one place.

Let see all the material components in detail with an example,

## Android Chips
![material chips](https://user-images.githubusercontent.com/4497904/137846957-f84d18b4-d556-46e7-b560-a007436f8364.png)
Chip is a component that can represent the input, filter, choice, or action of a user. This post will be on the implementation of different chip types and various attributes of chips.

A Material Chip represents a complex entity in a small block, such as a contact. It is a rounded button that consists of a label, an optional chip icon, and an optional close icon. A chip can either be clicked or toggled if it is checkable.

### Types Of Material Chip
There are four types of chips:
- Entry (Input) Chips
- Filter Chips
- Choice Chips
- Action Chips

Chips are generally used with ChipGroup which is to hold a number of chips.

### Android Chips Example
[Android Chips – Material Component For Android](https://howtodoandroid.com/android-chips-material-component/)

## Material Menus
![menus](https://user-images.githubusercontent.com/4497904/137847594-f405c2f0-e7f1-4511-8621-3263e6dcbb70.png)

A menu displays a list of choices on a temporary surface. They appear when users interact with a button, action, or other control.

### Types of menus
- Dropdown menus
- Exposed dropdown menus

### Material Menus Example
[Material Menus – Material Component For Android](https://howtodoandroid.com/material-menus-android/)

## Navigation Rail
![navigation rail](https://user-images.githubusercontent.com/4497904/137847812-ca12ec2a-dc6f-41ac-8a75-58ec9423d944.png)

The Navigation rail acts as a side navigation component or sidebar and can hold from three, up to seven destination views. Each view consists of an icon and a respective label, just as we know it from the Bottom view. In contrast to the Bottom view, it is aligned vertically and can also be used in combination with a NavigationDrawer.

### Navigation rails should be used for:
- Top-level destinations that need to be accessible anywhere in an app
- Three to seven main destinations in a product
- Tablet or desktop layouts
### Navigation rails shouldn’t be used for:
- Small screen sizes
- Single tasks, such as viewing a single email
- Secondary navigation destinations

### Navigation Rail Example
[Navigation rail – Material Component For Android](https://howtodoandroid.com/navigation-rail-material-component-android/)

## Navigation Drawer
![navigation drawer](https://user-images.githubusercontent.com/4497904/137848043-30cc56c3-ce7e-46bc-bec9-d76727f0b460.png)

Navigation drawers provide access to destinations and app functionality, such as switching accounts. They can either be permanently on-screen or controlled by a navigation menu icon.
### Navigation drawers are recommended for:
- Apps with five or more top-level destinations
- Apps with two or more levels of navigation hierarchy
- Quick navigation between unrelated destinations

### Navigation Drawer Example
[Android Navigation Drawer Explained [Step By Step]](https://howtodoandroid.com/android-navigation-drawer/)

## Snackbar
![snackbar-android-example-1024x512](https://user-images.githubusercontent.com/4497904/137848203-6034df53-1f7c-40d2-97f6-513fa2bf8a02.png)
Snackbars inform users of a process that an app has performed or will perform. They appear temporarily, towards the bottom of the screen. They shouldn’t interrupt the user experience, and they don’t require user input to disappear.

### Frequency
Only one snackbar may be displayed at a time.
### Actions
A snackbar can contain a single action. “Dismiss” or “cancel” actions are optional.

### Snackbar Example
[Android Snackbar Example](https://howtodoandroid.com/android-snackbar-example/)

## Bottom Sheets
![bottom sheet](https://user-images.githubusercontent.com/4497904/137848354-0be2c4fc-729a-4dda-ac3b-d21c49d5d1c2.png)
Bottom Sheets are surface components that hold supplementary screen content. They are anchored to the bottom of a screen (making them ergonomic on mobile/tablet devices) and, similar to Dialogs, are elevated over main screen content. In most cases, they can be expanded/dismissed via a drag up/down gesture.

From a design perspective, there are two types of Bottom Sheets:
- **Standard Bottom Sheet:** They operate independently to (and allow for simultaneous interaction with) primary screen content. They can be in an expanded, collapsed or hidden state.
- **Modal Bottom Sheet:** They block primary screen content and must be interacted with or dismissed. A semi-transparent scrim, which can be tapped to dismiss, is displayed behind them to indicate the underlying UI is temporarily inaccessible.

### Bottomsheet Example
[Bottom Sheets – Material Components for Android](https://howtodoandroid.com/bottom-sheets-android/)

## Sliders
A Slider is a useful control for allowing the user to specify values without having to use the keyboard. The basic use case for it is vey similar to the Android Framework SeekBar or the AppCompatSeekBar widgets.
### Types of sliders
There are two types of sliders.
- Continuous Slider
- Discrete Slider

Also, We have a another slider called range slider.

### Sliders Example
[Sliders – Material Component For Android](https://howtodoandroid.com/sliders-material-component-for-android/)

## ShapeableImageView
![Shapeable-Imageview-poster-rect](https://user-images.githubusercontent.com/4497904/137848680-0bc1e7ee-e5bc-4656-9834-fc6d00945592.png)

By using ShapeableImageView, you can change the shape of your image to circle, diamond, etc. Also, you can set a corner radius to your image view.

The Material Components Library introduced with the 1.2.0-alpha03 the new ShapeableImageView.

### ShapeableImageView Example
[ShapeableImageView – Material components for android [Example]](https://howtodoandroid.com/shapeableimageview-material-components-android/)

## Progress Indicators

![type-of-progress-indicators](https://user-images.githubusercontent.com/4497904/137848770-d37837c3-2605-4605-a769-e0fc95270328.jpeg)

Progress indicators inform users about the status of ongoing processes, such as loading an app, submitting a form, or saving updates. They communicate an app’s state and indicate available actions, such as whether users can navigate away from the current screen.
Types
### Material Design offers two visually distinct types of progress indicators:
- LInear
- Circlular

### Progress Indicators Example
[Progress Indicators – Material Components For Android](https://howtodoandroid.com/progress-indicators/)


