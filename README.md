<p align="center">
  <a href="https://www.liverpool.ac.uk/" target="blank">
    <img src="Liverpool_logo.png" alt="Logo" width="156" height="156">
  </a>
 <h1 align="center" style="font-weight: 600">COMP228    App Development</h1>
 <h3 align="center" backgroundcolor="red">⭐ If the code has helped you, please stars this, thank you very much!</h3>

# A Visitor iOS App for Ness Garden

## Overview
This application is designed for visitors of Ness Gardens, providing detailed information and geographical tagging of plants. It features real-time user location simulation for testing remotely, displays plant and bed locations, and offers a plant favoriting function.

### Key Features
- **Geographical Tagging:** Utilizes an API to display plants' positions.
- **Real-time Updates:** Updates plant lists based on the user's location.
- **Favorites:** Allows users to mark plants as favorites.
- **Connectivity Requirements:** Requires internet access to fetch images and data.

### Main Files
- **dataModel.swift:** Manages data structures and interacts with Core Data.
- **PlantTableViewCell.swift:** Defines the table cell for displaying plant information.
- **ViewController.swift:** Handles user location updates and user interactions.
- **DetailsViewController.swift:** Displays detailed plant information and location.

## Notable Parts
1. **Update Efficiency:** The app updates the table only when the user moves more than three meters to reduce frequent updates.
2. **Core Data Implementation:** Uses Core Data for local storage of plant data.
3. **Custom Cell Design:** Incorporates labels, buttons, and image views in plant cells.
4. **Detailed Image Display:** Uses a scroll view for browsing multiple plant images.
5. **Error Handling:** Includes mechanisms to hide certain UI elements based on data conditions.

## How to Use
1. **Startup:** Accept the location permission prompt upon first startup.
2. **Navigation:** Interact with the map and plant list on the main interface.
3. **Favoriting Plants:** Toggle the favorite status by clicking the heart button on plant cells.

### Important Note
The app may require a restart when first run on a new device to function correctly.

## Must See Before Read My code
* Operating System: macOS Sonoma
* Programming Languages: Swift
* All codes are related to labs and assignments and all codes were uploaded after the assignment deadline, all personal information is taken from the University's public website.

⚠Please adhere to the University's Academic Integrity Policy and I accept no responsibility for suspected academic misconduct of any kind.

## Module Specification
* Year: 2023
* Lectuer: Professor Jimmieson Phil

## Module Results
* Assignment: 96/100 (Thumbnail sizes need to be scaled a little to make them more aesthetically pleasing)
