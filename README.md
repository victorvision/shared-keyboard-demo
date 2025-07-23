# Industrial Equipment Parameter Configurator

This project demonstrates how to edit multiple variables using only a single keyboard in **UnicView Studio**. This approach reduces the need to create multiple keyboard windows and simplifies project maintenance — any modification to the keyboard needs to be made only once.

In addition, this demo showcases the use of the **Exclusive Selector** component, which makes it easy to create lists where only one parameter can be selected at a time. This operator works by linking a *Selector Variable* to a set of index variables. When one index is activated, it is automatically set to `true` while the others are set to `false`, ensuring that only one item is active at a time — in a simple and automated way.

Another key feature is the **dynamic keyboard mask switching**. With a *Text Box Mask* selector linked to the keyboard, the input mask can be changed automatically depending on the selected parameter.

---

## Feature Summary

- **Centralized editing**: A single keyboard is used to edit multiple variables.
- **Exclusive Selector**: Operator that makes it easy to implement exclusive lists by activating one index and deactivating the others automatically.
- **Dynamic keyboard mask**: The mask changes automatically based on the selected variable.

---

## Components and Resources Used

### Software:
- **UnicView Studio**: For designing and configuring the graphical interface.
- **Exclusive Selector (Operator)**: A component that enables exclusive selection logic.
- **Selectors**: Used for managing lists of variables and keyboard masks.

### Hardware:
- **Victor Vision Smart Display**

---

## How to Set Up the Project

1. **Download the project files**  
   The project is available in the official GitHub repository.

2. **Transfer to the display**  
   Use **UnicView Studio** to load the project onto your display.

3. **Interact with parameters**  
   Tap a parameter to edit it using the keyboard.

---

## Why Use This Project?

This project is ideal for those looking to optimize keyboard usage in industrial interface projects. It demonstrates how to implement efficient selection logic while keeping the UI clean and maintenance-friendly — a great example of best practices with UnicView Studio.

---

## Downloads and Resources

- [Project on GitHub](#) *(insert GitHub repo link)*
