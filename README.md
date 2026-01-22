# mipad-dpi-fix
A module that fixes the DPI anomaly on tablet devices running HyperOS3. Especially Xiaomi Pad 6 Pro and Pad 6 Max.

If the issue persist after flashing the module, try running the command below in root to reset Android WindowManager:

```bash
wm reset
```

Or ADB:

```bash
adb shell wm reset
```

# Credits
Credit to @做梦书 for finding the original issue and providing solutions.