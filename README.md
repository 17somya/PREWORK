# Android Prework – Hello Android

Submitted by: **Somya Thakkar**

**Hello Android** is a simple Android app that displays a welcome image and message. It also includes a button—when tapped, the app shows a Toast notification.

Time spent: **30 MINUTES** hours in total

---

## Required Features

The following **required** functionality is completed:

- [x] An image and introductory message are visible on the main screen
- [x] A button is displayed on the screen
- [x] Tapping the button shows a Toast with a short message

### Optional Enhancements

- [ ] Used `ConstraintLayout` with proper constraints to center and align views
- [ ] Styled the button using Material 3 (`MaterialButton`)
- [ ] Added `contentDescription` for the ImageView (accessibility)
- [ ] Switched to View Binding for safer view access
- [ ] Replaced Toast with a Snackbar for richer UI feedback

---

## Video Walkthrough

Here’s a quick walkthrough of the implemented features:

https://imgur.com/3MQVaNl

*GIF created with ScreenToGif (Windows)

![Prework](https://github.com/user-attachments/assets/42e20344-a3cf-4572-a35d-65db8a30c28a)

---

## How to Run

1. Open the project in **Android Studio**.
2. Click **Sync Project with Gradle Files**.
3. Run on an emulator or a physical device (API 24+ recommended).
4. Tap the button to see the Toast.

---

## Notes

- If the button didn’t appear where expected, the issue was missing `ConstraintLayout` constraints. Adding top/bottom/start/end constraints fixed the layout.
- If the click didn’t fire, ensuring the correct `onClick` handler or attaching `setOnClickListener` in `onCreate` resolved it.

---

## License
Copyright 2025 Somya Thakkar
