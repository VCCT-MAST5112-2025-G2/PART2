## ST10497874
## PROJECT OVERVIEW
Christ App Menu

Christ App Menu is a React Native app built with Expo that allows users to create, manage, and view a restaurant-style menu.
Users can add dishes, organize them by course (Starters, Main, Desserts, Drinks), view their total price, and reset their list.

## Features
 1. Add Dishes

Users can input:

-Dish Name

-Description

-Course Type (Starters, Main, Desserts, or Drinks)

-Price

After filling the fields, pressing “Add Dish” adds the item to the menu list below.

 2. Course Selection Buttons

At the top of the screen, four flexbox buttons represent the available courses:

-Starters

-Main

-Desserts

-Drinks

Tapping a button selects the course type for the dish being added.

The active course button is visually highlighted for clarity.

 3. Price Calculation

Every dish’s price is added to the total, automatically recalculated in real-time.

The total is displayed at the bottom of the screen once at least one dish is added.

Prices are formatted with the South African Rand (R) symbol.

 4. Cancel Menu

A red “Cancel” button clears all dishes and resets the total to zero.

This allows the user to start fresh without restarting the app.
## Design considerations

A clean, green-themed interface representing freshness and dining.

Rounded cards for each menu item.

Smooth layout using React Native’s Flexbox and ScrollView.

Well-structured text and icons for a polished experience.

## Technologies Used
Library	Purpose
React Native	UI and component structure
Expo	Simplified development and deployment
TypeScript	Type safety and clarity
React Native FlatList	Efficient rendering of the menu items
React Native TouchableOpacity	Interactive buttons for course selection and actions
ScrollView	Enables smooth vertical scrolling of the interface
## How It Works 

Select Course
Tap one of the four buttons (Starters, Main, Desserts, Drinks) to set the dish’s category.

Enter Dish Details

Type the name and description of the dish.

Enter the price in Rands (R).

Add Dish

Tap the “Add Dish” button to save the dish.

It appears in the list below, grouped visually with name, course, and description.

View Total

The total price automatically updates as dishes are added.

Cancel Menu

Tap “Cancel” to clear the entire list and reset the total.

##  Installation & Setup
Prerequisites

Make sure you have these installed:

Node.js (latest version)

npm or yarn

Expo CLI

Steps

Clone the repository or create the project:

git clone 

Install dependencies:

npm install


Start the Expo development server:

npm start

Open the app:

Scan the QR code in the terminal using the Expo Go app on your phone, or
Press w to open it in a web browser, 
##  screenshots.
![image E](https://github.com/user-attachments/assets/7ce72f9e-8948-4218-a2c4-7afabe30f79c)

![image A](https://github.com/user-attachments/assets/6308f673-bfe6-4806-b54f-06701a15d9a0)


![image d](https://github.com/user-attachments/assets/46cffa97-3b70-46e6-b624-4d714b66f175)
![Image c](https://github.com/user-attachments/assets/dfd827aa-6560-4232-9e28-f425c005ddfc)
![Image  B](https://github.com/user-attachments/assets/8f18c148-e712-47cd-a986-862fbb46e370)



