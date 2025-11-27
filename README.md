# Android Studio & macOS Configuration Repository

This repository stores **IDE settings** for Android Studio (and macOS IDE in the future), allowing team members to easily share and sync their development environment.

---

## **Contents**

* `android-studio-settings.zip` → Exported IDE settings file ready for import.

> ⚠️ **Do NOT commit personal workspace files**.

---

## **Setup**

1. **Clone the repository:**

```bash
git clone https://github.com/itachi1611/as_setting.git
cd as_setting
```

2. **Import settings in Android Studio**:

   * Open Android Studio → `File` → `Manage IDE Settings` → `Import Settings…`
   * Select `android-studio-settings.zip` from the repo.
   * Restart Android Studio if prompted.

---

## **Future Plans**

* Add configuration for **macOS IDE** so all team environments stay consistent.
* Continue updating shared **code styles, inspections, and run configurations**.

---

## **Updating Settings**

* After modifying IDE settings:

  1. Export settings as `.zip` from Android Studio.
  2. Commit the new `.zip` to the repository:

```bash
git add android-studio-settings.zip
git commit -m "Update IDE settings"
git push origin main
```

Team members can then pull the latest `.zip` and import again.

---

## **License**

Internal team use. Adjust licensing if needed.
