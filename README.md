# SwiftUI User Profile UI

## Description
This project is a simple SwiftUI-based user profile interface. It demonstrates the use of `VStack`, `HStack`, and `ZStack` to create a structured and visually appealing layout. The UI consists of a user profile image, text labels, and two interactive buttons with custom styles.

## Features
- **User Profile Image**: Displays a user icon with styling effects.
- **Text Labels**: Includes a username and a welcome message.
- **Custom Buttons**: Implements primary and secondary buttons with different styles.
- **Responsive Layout**: Uses SwiftUI stacks and modifiers for a clean design.

## How It Works
1. **Layout**:
   - The UI is structured using `ZStack` for background, `VStack` for vertical alignment, and `HStack` for horizontal button placement.
2. **Profile Image**:
   - A `resizable` system image with a shadow effect.
3. **Text Elements**:
   - A large, bold username label.
   - A secondary welcome message.
4. **Button Styles**:
   - `PrimaryButtonStyle`: A blue rounded button with a scaling effect on press.
   - `ScondaryButtonStyle`: A red rounded button with the same interaction effect.

## Installation & Usage
1. Open the project in Xcode.
2. Run the SwiftUI preview or build the project on a simulator.
3. Tap the buttons to see their interactive effects.

## Requirements
- Xcode 14+
- iOS 16+
- SwiftUI Framework

## Future Improvements
- Fetch dynamic user data instead of a static name.
- Implement navigation and more interactive elements.
- Add an option for dark mode compatibility.

