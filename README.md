# 💻 Practical 8: Create Your First "Hello World" iOS App in SwiftUI

## 📌 Repository  
**MAD_23012011066_Practical-8**  
This project demonstrates how to create a basic **Hello World** iOS application using **SwiftUI** in Xcode.

---

## 🎯 Aim
To create a simple "Hello World" application for iOS using the **SwiftUI** framework.

---

## 🛠️ Tools / Environment
- **Xcode** (Apple's IDE)
- **Swift**
- **SwiftUI Framework**

---

## 📝 Steps to Create the Project

### 1️⃣ Create a New Project
1. Open **Xcode** → Go to `File > New > Project`.
2. Select the **App** template under the **iOS** tab.
3. Configure the project:
   - **Product Name:** `hello world`
   - **Interface:** `SwiftUI`
   - **Language:** `Swift`
   - Disable:
     - **Use Core Data**
     - **Include Tests**
4. Check **Create Git repository on my Mac**.
5. Click **Create**.

---

### 2️⃣ Project Structure Overview

#### 📁 `hello_worldApp.swift`
- Entry point of the application.
- Contains a struct conforming to the **App** protocol.
- Defines the scene using **WindowGroup**.
- Loads the initial content using `ContentView()`.

#### 📁 `ContentView.swift`
- Contains the UI definition.
- `ContentView` struct conforms to the **View** protocol.
- UI is declared inside:
  ```swift
  var body: some View
