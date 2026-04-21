 Enable Accessibility Service
1. Open **Settings** on your Android device.
2. Navigate to **Accessibility**.
3. Find **Screen Control** and toggle it **ON**.

---

## 🛠️ Usage (Command Examples)

You can send commands via ADB broadcasts:

### Tap (Click)
```bash
adb shell am broadcast -a com.example.screencontrol.TOUCH --ef x 500 --ef y 1000
```

### Swipe
```bash
adb shell am broadcast -a com.example.screencontrol.SWIPE --ef x1 200 --ef y1 500 --ef x2 800 --ef y2 500 --el duration 500
