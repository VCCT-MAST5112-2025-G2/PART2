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

git clone https://github.com/base1825/PART2.git

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
![Image  B](https://github.com/user-attachments/assets/8
<img width="671" height="652" alt="Screenshot 2025-10-22 004207" src="https://github.com/user-attachments/assets/e5d8729c-8ea5-42ac-8de0-590f1a86b6cf" />
f18c148-e712-47cd-a986-862fbb46e370)


<img width="966" height="616" alt="Screenshot 2025-10-22 004300" src="https://github.com/user-attachments/assets/9d090fe5-f191-4f1a-a4dd-9fa9e14c7601" />
<img width="895" height="649" alt="Screenshot 2025-10-22 004317" src="https://github.com/user-attachments/assets/1d9510c1-7475-4097-8bba-15ec268d09c6" />


<img width="743" height="659" alt="Screenshot 2025-10-22 004232" src="https://github.com/user-attachments/assets/98a46b39-0d0c-48a0-983d-1ea310082bdf" />
## Youtube : https://youtube.com/shorts/g06j4z-dnJY

## PART2 
this is the  updated version of the christoffel's kitcken app, built with **React Native** and ** Expo Router** 
It allows Uaers to view,filter and add dishes to a digital reataurent menu.

## Features
## HOME SCREEN
-Displays menu categories:**Starters**, **Mains** , **Desserts** , and **Drinks** 
-Each category shows an **avreage price**
-Two main buttons at the buttons
-**Add Menu** for the chef to add new dishes
-**View Full Menu**  to browse all items 

### Add Mwnu Screen
-Lets Chefs add new dishes with :
 Lets chefs add new dishes with:
  - Dish name  
  - Description  
  - Price  
  - Course (Starter, Main, Dessert, Drink)
- Displays:
  - Total number of dishes added
  - Average price per course
- Includes a button to navigate to **Filter Page**.

  
###  Filter Screen
- Displays menu items filtered by course or full list.
- Connected to shared **MenuContext**, so any new dish added in *Add Menu* is instantly visible.
 
##Context Management

The app uses a central `MenuContext` located in:
App/content/MenuContext.tsx
This handles:
- Global menu storage  
- `addDish` and `removeDish` functions  
- Data sharing between **AddMenu** and **Filter** pages
- 
##  Tech Stack
- **React Native (Expo)**
- **Expo Router**
- **TypeScript**
- **Context API**
- **uuid** for unique dish IDs


##  How It Works
1. The `MenuProvider` wraps the app (in `_layout.tsx`), making menu data available globally.
2. The **AddMenu** page updates the shared state using `addDish()`.
3. The **Filter** page reads from the same state via `useMenu()`.
4. The **Home** screen provides category navigation and quick actions.

##  Preview
![app1](https://github.com/user-attachments/assets/59b80722-748a-45d2-a902-b0f7d666afe4)
![app2](https://github.com/user-attachments/assets/af9ee61c-b3c9-43aa-8049-acb3ae48e9ee)
![app3](https://github.com/user-attachments/assets/db83309d-74cb-4249-8202-c6cde937b2b2)

![app4](https://github.com/user-attachments/assets/ab5c602e-6ac8-4f5b-985a-f603f8c564b8)

![app5](https://github.com/user-attachments/assets/a2e0bd0a-d8a2-4a42-bda3-d7fd8fb441db)

![app7](https://github.com/user-attachments/assets/020f4a7c-b3d7-4c24-8ccb-912fa4ac34a9)

![app8](https://github.com/user-attachments/assets/dff902fd-6540-4217-8c7c-7dc65f0f46d5)
![app9](https://github.com/user-attachments/assets/a875ba25-f7e4-4a1c-89ff-779abae9aea9)
![app10](https://github.com/user-attachments/assets/0b02d60d-2fd0-45e5-bce8-6617dc874317)


## Installation

1. Clone the repo:
   bash
   git clone https://github.com/base1825/christApp-new.git
   cd christApp-new
Install dependencies:
npm install
Run the app:
-npx expo start






