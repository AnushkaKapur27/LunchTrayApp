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

| Start Order Screen | Entrée Screen | Side Dish Screen | Accompaniment Screen | Summary |
|:------------------:|:-------------:|:----------------:|:---------------------:|:-------:|
|![Start](![WhatsApp Image 2025-06-18 at 17 26 51_5c12094e](https://github.com/user-attachments/assets/d0843eb5-b7c2-4a36-a797-de354069dcd0)
)| ![Entree](![WhatsApp Image 2025-06-18 at 17 26 51_96199981](https://github.com/user-attachments/assets/a37de93f-0d0f-41e3-9224-02f3354dad03)
) | ![Side](![WhatsApp Image 2025-06-18 at 17 26 52_9d064e87](https://github.com/user-attachments/assets/055f3224-15c1-4b7b-9c0f-73b3bbb839d1)
) | ![Accompaniment](![WhatsApp Image 2025-06-18 at 17 26 52_cc261ce4](https://github.com/user-attachments/assets/ce5e0ae2-156e-48b6-94db-932854a8476c)
) | ![Summary]![WhatsApp Image 2025-06-18 at 17 26 52_fa464b4e](https://github.com/user-attachments/assets/76060021-d451-4336-97d1-a5caa952f9a9)
) |

---

## 🧩 App Flow

```mermaid
graph TD
    Start[Start Order] --> Entree[Select Entrée]
    Entree --> Side[Select Side Dish]
    Side --> Accompaniment[Select Accompaniment]
    Accompaniment --> Summary[Order Summary]
    Summary --> Restart[Start Over]
