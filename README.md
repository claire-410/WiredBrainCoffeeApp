# WiredBrainCoffee.CustomersApp

The **WiredBrainCoffee.CustomersApp** is a C# desktop application built with the **Model-View-ViewModel (MVVM)** pattern and the **Windows Presentation Foundation (WPF)** framework.

It manages customer data for a fictional coffee company and demonstrates a clean, maintainable architecture for modern desktop applications.

---

## ✨ Features

- Manage customer information such as **first name, last name, and developer status**  
- Responsive **WPF user interface** built with XAML  
- Real-time updates through **data binding** and `ObservableCollection<T>`  
- Clear separation of concerns with the **MVVM pattern**  
- Extensible design ready for integration with databases or external services  

---

## 🏗️ Architecture

The application follows the **MVVM pattern**, structured into three layers:

### 🔹 Model
- Represents core data and business logic (`Customer` class with relevant properties)  

### 🔹 View
- UI defined in **XAML** (`DataGrid`, `Button`, `TextBox`)  
- Uses **bindings** instead of code-behind for better maintainability  

### 🔹 ViewModel
- Exposes model data to the view and handles **presentation logic**  
- Implements `INotifyPropertyChanged` for reactive UI updates  
- Uses `ICommand` (via `RelayCommand`) for UI actions  

---

## ⚙️ Technologies

- **C# / .NET**  
- **Windows Presentation Foundation (WPF)**  
- **MVVM Design Pattern**  
- **Data Binding & Commands**  
- **ObservableCollection<T> & INotifyPropertyChanged**  

---

## 🚀 Getting Started

### Prerequisites
- [Visual Studio](https://visualstudio.microsoft.com/) with **.NET Desktop Development** workload installed  
- .NET Framework or .NET 6+ (depending on version)  

### Run the App
1. Clone the repository  
2. Open the solution file (`.sln`) in Visual Studio  
3. Build and run the application (`F5`)  

---
