# CheckSplit

CheckSplit is a simple SwiftUI app designed to help you split a bill among a group of people while considering different tip percentages. With this app, you can quickly input the check amount, choose the number of people splitting the bill, and select your preferred tip percentage. CheckSplit then calculates the total amount per person, including the tip, making it easy to split the bill accurately.

## Features

- **Input Check Amount:** Enter the total amount of the bill using a convenient text field.
- **Select Number of People:** Choose the number of individuals splitting the bill using a picker.
- **Adjust Tip Percentage:** Pick from predefined tip percentages or opt for no tip.
- **Real-Time Calculation:** CheckSplit dynamically updates the total amount per person as you adjust the inputs.
- **Currency Support:** The app supports multiple currencies based on your device's locale settings.

## How to Use

1. **Enter Check Amount:** Type in the total amount of the bill in the designated text field.
2. **Select Number of People:** Use the picker to choose the number of individuals splitting the bill.
3. **Choose Tip Percentage:** Pick a tip percentage from the segmented control options.
4. **View Total Per Person:** CheckSplit instantly calculates and displays the total amount each person needs to pay.

## Technologies Used

- **SwiftUI:** The user interface is built using SwiftUI, providing a modern and intuitive user experience.
- **NavigationStack:** Utilizes a custom navigation stack to manage navigation within the app.
- **State Management:** Leverages SwiftUI's `@State` property wrapper for managing user inputs and dynamic updates.
- **Preview Support:** Includes a preview section for testing and visualizing the ContentView.


## Getting Started

To use CheckSplit, simply download or clone the repository and open it in Xcode. You can then build and run the app on your iOS or macOS device.
