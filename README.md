# Swift Blackjack Game

A minimalist Blackjack game built with **SwiftUI**, designed to showcase basic state management, UI layout, and gameplay logic. This app demonstrates how to build a turn-based game using modern Swift paradigms like `@StateObject` and reactive updates.

---

## Features

- Hit / Stand gameplay logic
- Dealer AI that draws to 17
- Score display and bust detection
- Reset button to replay instantly
- Clean SwiftUI interface

---

## How It Works

- `BlackjackGame`: Observable class that manages the deck, player and dealer hands, game state, and result messages.
- `BlackjackView`: SwiftUI view that renders the UI, buttons, and score logic.
- Dealer draws automatically until they reach 17+ after you stand.
- The game determines win/loss conditions and updates the view reactively.

---

## 🛠Tech Stack

- `SwiftUI`
- `@StateObject` and `@Published` properties
- Simple MVC structure (`Game`, `View`, `Hand`, `Deck`, etc.)

---

## Running the App

1. Open the project in **Xcode** (minimum version: 12.0)
2. Build and run on the iOS Simulator or your device
3. Tap **Hit** or **Stand** to play

> Make sure to include the required supporting files like `Deck.swift`, `Hand.swift`, and `CardView.swift` in the project.
