# ✅ To Today - A To-Do List

- **Discipline:** Programming for Mobile Devices
- **Teacher:** Junio Moreira
- **Student:** João Augusto Marciano Silva
- **Final date:** 16/11/2025

## Application operation

### Light mode

| List Screen (with Sort Menu) | Edit Screen | Add Task Modal |
|:---:|:---:|:---:|
| <img height="500" alt="List Screen Light" src="[YOUR_SCREENSHOT_URL_HERE]" /> | <img height="500" alt="Edit Screen Light" src="[YOUR_SCREENSHOT_URL_HERE]" /> | <img height="500" alt="Add Task Modal Light" src="[YOUR_SCREENSHOT_URL_HERE]" /> |

### Dark mode

| List Screen (Searching) | Edit Screen | Add Task Modal |
|:---:|:---:|:---:|
| <img height="500" alt="List Screen Dark" src="[YOUR_SCREENSHOT_URL_HERE]" /> | <img height="500" alt="Edit Screen Dark" src="[YOUR_SCREENSHOT_URL_HERE]" /> | <img height="500" alt="Add Task Modal Dark" src="[YOUR_SCREENSHOT_URL_HERE]" /> |

## Features

- **Task Management:** Allows users to add, edit, and delete tasks seamlessly.
- **Status Toggling:** Mark tasks as "Completed" or "Pending" with a simple checkbox.
- **Instant Search:** A persistent search bar filters the task list in real-time by matching task titles.
- **Dynamic Sorting:** Users can instantly re-organize the list using four criteria:
    - Order A-Z
    - Order Z-A
    - Completed First
    - Pending First (Default)
- **Modal Input:** A clean "Add Task" modal (`AlertDialog`) provides a focused data entry experience for new tasks.
- **Edit Screen:** Clicking a task navigates to a separate "Edit" screen where both the title and description can be modified.
- **Modern UI:** Built entirely with Jetpack Compose and Material Design 3, using components like `Scaffold`, `LazyColumn`, `Card`, and `OutlinedTextField`.
- **Custom Theming:** Features a vibrant, custom yellow-based theme with full support for system Light and Dark modes.
- **UX Enhancements:**
    - The "Title" field automatically gains focus when the "Add Task" modal is opened.
    - The on-screen keyboard automatically enables sentence capitalization (`KeyboardCapitalization.Sentences`) for new tasks.
- **State Management:** Uses a `ViewModel` to manage application state, ensuring data persists across configuration changes (like rotation) and is shared between screens.
- **Fluid Navigation:** Implements Jetpack Navigation, with custom `EnterTransition.None` and `ExitTransition.None` to remove fade-in/out animations for faster, more direct screen changes.

## Download

[APK](https://github.com/joaomarcianodev/DM-Prova5/blob/main/app/release/ToToday-1.0.apk)