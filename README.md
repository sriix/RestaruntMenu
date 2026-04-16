<div align="center">

# 🍽️ DineSmart

### Smart Table-Side Touch Ordering Interface for Restaurants

A browser-based restaurant table interface that allows customers to browse menu categories, view dish details, customize items, track orders, and view billing screens directly from a touch display — without waiting for waiter assistance.

Built completely using **HTML, CSS, JavaScript, and JSON** (frontend-only prototype).

</div>

---

## 📖 Overview

**DineSmart** is a touch-friendly restaurant ordering interface designed for table-mounted screens. Customers can explore menu categories like vegetarian, non-vegetarian, diet meals, desserts, and mocktails, open item detail pages, customize dishes, and navigate through ordering workflow screens.

This project demonstrates how a structured multi-page frontend workflow can simulate a real smart restaurant ordering system without requiring backend integration.

---

## ✨ Features

### 🗂️ Menu Categories

The system organizes dishes into dedicated category pages:

| Category       | Page             |
| -------------- | ---------------- |
| Vegetarian     | Category.html    |
| Non-Vegetarian | nonvegitems.html |
| Diet Meals     | diet.html        |
| Desserts       | desserts.html    |
| Mocktails      | mocktails.html   |

---

### 🔍 Dish Detail Pages

Each dish includes:

* Dish image
* Ingredient overview
* Nutrition information
* Description
* Navigation to customization screen

Example pages:

```
itemdetails.html
nonvegitemdetail.html
dietitemdetail.html
dessertsitemdetail.html
mocktailitemdetail.html
```

---

### 🛠️ Dish Customization Screens

Customers can personalize their orders using:

```
customize.html
customizenon.html
```

Customization includes:

* Ingredient preference adjustments
* Portion selection
* Special instruction entry

---

### 🛒 Order Flow Simulation

DineSmart simulates restaurant ordering workflow:

```
Menu Selection → Item Details → Customization → OTP Screen → Order Flow
```

OTP verification screen:

```
otp.html
```

Used as part of confirmation interaction flow.

---

### 💳 Billing Interface

Users can:

* Review selected items
* Navigate through confirmation workflow
* Simulates table-side checkout experience

(Note: Payment gateway not integrated — UI workflow prototype only)

---

## 🖥️ Interface Design

Designed specifically for restaurant touch displays:

* Large tap-friendly navigation buttons
* Separate category browsing screens
* Simple step-by-step order workflow
* English-only interface
* Light-mode UI

---

## 🏗️ Tech Stack

Frontend-only implementation:

| Layer     | Technology       |
| --------- | ---------------- |
| Structure | HTML5            |
| Styling   | CSS3             |
| Logic     | JavaScript       |
| Data      | JSON (menu.json) |
| Backend   | Not used         |

---

## 📁 Project Structure

```
RestaruntMenu/
│
├── index.html
├── Category.html
├── desserts.html
├── diet.html
├── mocktails.html
├── nonvegitems.html
│
├── itemdetails.html
├── nonvegitemdetail.html
├── dietitemdetail.html
├── dessertsitemdetail.html
├── mocktailitemdetail.html
│
├── customize.html
├── customizenon.html
│
├── otp.html
│
├── menu.json
│
├── Images/
│
└── README_tabletouch.md
```

---

## 🚀 Getting Started

Clone repository:

```
git clone https://github.com/sriix/RestaruntMenu.git
```

Open project:

```
open index.html
```

Or run local server:

```
python -m http.server 3000
```

Visit:

```
http://localhost:3000
```

---

## 📊 Data Usage

The system uses:

```
menu.json
```

to store structured menu information for dishes.

This demonstrates how JSON datasets can support scalable smart restaurant interfaces.

---

## 🔮 Future Improvements

Possible upgrades:

* Admin panel for menu editing
* Database integration
* Payment gateway connection
* Multi-language support
* Dark mode UI
* Smart recommendation system

---

## 🎯 Learning Outcomes

Through this project:

* Designed touch-screen restaurant workflow interface
* Built multi-page navigation ordering system
* Implemented JSON-based menu structure
* Created dish customization screens
* Simulated confirmation workflow using OTP page

---

<div align="center">

Made with ❤️ for smart dining experiences

**DineSmart — Order Smarter. Eat Better.**

</div>
