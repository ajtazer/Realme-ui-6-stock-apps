# 📦 Realme UI 6.0 — Stock System App Backup  
### _Community recovery archive for restoring missing or broken system apps_

This repository provides a complete dump of **Realme UI 6.0 system apps**, extracted from an Android 14 Realme device.  
It is created to help users who:

- Accidentally removed apps with ADB debloating  
- Lost system components after reset  
- Broke Realme UI features due to package removal  
- Need original Realme UI 6.0 apps for testing or comparison  

All APKs are pulled **directly from a live Realme UI 6.0 system image**, using ADB only (no modification, no repacking).

---

> ❗ **No user data / private information / paid apps are included.**  
> Only system apps from a clean Realme UI 6 installation.

---

## 🔧 How These APKs Were Extracted

Using ADB:

```bash
adb shell pm list packages -f --user 0
adb pull <path> apks/
```


---

If you want, I can also generate:

✅ `restore.sh` — reinstall all system apps automatically  
✅ `index.json` — mapping packages → apk paths  
✅ A clean folder tree for GitHub  
✅ A GitHub Actions workflow that zips all APKs into Releases  

Just tell me!
