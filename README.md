# 🛠️ MVVM File Generator for Xcode

A custom Swift template for generating **MVVM architecture files** (Model(responseModel, requestModel), View, ViewModel, Repository for API Calling) directly from Xcode — streamline your development with consistent file structures and naming conventions.

---

## 🚀 Features

- ⚡ Instantly generate boilerplate MVVM files
- ✅ Supports SwiftUI projects
- ✅ Includes:
  - `View.swift`
  - `ViewModel.swift`
  - `RequestModel.swift`
  - `ResponseModel.swift`
  - `Repository.swift`
- 🧱 Ensures a clean, scalable architecture
- 🧩 Integrates natively with Xcode’s **File > New > File…** menu

---

## 📂 What's Inside?

After extracting, you’ll find a folder like this: For Example i want to create an folder for Home

-> Home
|___ HomeView.Swift (with some basic view designed in SwiftUI)
|___ HomeViewModel.Swift (with some basic view model implemention)
->Repository
  |___ HomeRepository.Swift with some basic API calling method
-> Models
  |___ HomeRequestModel.Swift ()
  |___ HomeResposeModel.Swift

It Will create all thses file, what you need to do is that just for once you need to unzip this folder

**In Finder -> Go to Folder -> type "/Users/syedmeesumraza/Library/Developer/" there will be a folder for xcode
create a new folder called "Template" and paste this unziped folder in that**

**Quit Xcode** 

**Reopen It**

**Go to File -> New -> New File From Template**

**Scroll to bottom of the picker you'll see this template**

**Open it and just write the name of Folder you want your folder to be**

**and Boom you have created files**

