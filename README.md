# 🥗 Lunch Tray App

An elegant and interactive lunch ordering experience built with **Jetpack Compose**, showcasing seamless **multi-screen navigation**, dynamic UI components, and modern Android app architecture.

---

## ✨ Overview

The **Lunch Tray** app allows users to customize their lunch order by selecting:

- 🥘 An Entrée  
- 🍟 A Side Dish  
- 🥤 An Accompaniment  

Each selection is made on a dedicated screen, and the app guides the user through the entire ordering flow with intuitive navigation and a responsive layout. Built as a learning project, this app puts Jetpack Compose navigation into action in a real-world scenario.

---

## 🚀 Features

- 🔁 **Navigation Between Screens** — Navigate fluidly between the entrée, side, and accompaniment menus.
- 🎯 **State Management** — User selections persist and update throughout the order flow.
- 🧭 **Navigation Component for Compose** — Utilizes `NavController` and `NavHost` for routing.
- 🖼️ **Dynamic Top Bar** — Displays contextual titles and back navigation where needed.
- 🧪 **Composable Architecture** — Modular screen components for clean, maintainable code.

---

## 🛠️ Tech Stack

- **Kotlin**
- **Jetpack Compose**
- **Navigation Component (Compose)**
- **State Hoisting**
- **Material 3 Design Principles**

---

## 📸 Screenshots

### Start Order Screen
![WhatsApp Image 2025-06-18 at 17 26 51_00962f80](https://github.com/user-attachments/assets/314ff274-f7b4-42e8-b9d8-0e4a419b3101)

### Entree
![WhatsApp Image 2025-06-18 at 17 26 51_d5005c48](https://github.com/user-attachments/assets/bebad5e0-9ef5-4274-9a57-0aceda5731b6)

### Side
![WhatsApp Image 2025-06-18 at 17 26 52_32e9d967](https://github.com/user-attachments/assets/70fb64dd-fe78-425b-a9c2-f2abc09f05fa)

### Accompaniment
![WhatsApp Image 2025-06-18 at 17 26 52_c93d1ed8](https://github.com/user-attachments/assets/8fe15b80-bc71-457e-9d37-004c38bf2d39)

### Summary
![WhatsApp Image 2025-06-18 at 17 26 52_3d2306e8](https://github.com/user-attachments/assets/62a7e35b-e4a2-455b-b9ce-0c710a44fb72)


---

## 🧩 App Flow

```mermaid
graph TD
    Start[Start Order] --> Entree[Select Entrée]
    Entree --> Side[Select Side Dish]
    Side --> Accompaniment[Select Accompaniment]
    Accompaniment --> Summary[Order Summary]
    Summary --> Restart[Start Over]
