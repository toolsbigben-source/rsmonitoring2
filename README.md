# RS Monitoring | Inventory Management System

## Live URL
https://toolsbigben-source.github.io/rsmonitoring2/

## Firebase Project
rsmonitoringnew

## Setup Steps

### 1. Firestore Rules
Firebase Console → rsmonitoringnew → Firestore → Rules → paste:
```
rules_version = '2';
service cloud.firestore {
  match /databases/{database}/documents {
    match /{document=**} {
      allow read, write: if true;
    }
  }
}
```
Click Publish.

### 2. GitHub Pages
Settings → Pages → Branch: main → / (root) → Save

### 3. Import Data
Open https://toolsbigben-source.github.io/rsmonitoring2/import.html
Click Check Status → Start Import

## Accounts

| Username | Password | Role |
|---|---|---|
| IMMike | Mokerrr123 | Admin |
| IMWarehouseman | IMbigben | Warehouse Staff |
| IMJill | IMbigben | Inventory Management Associate |
| IMLuisa | IMbigben | Inventory Management Specialist |
| IMRosemarie | IMbigben | Supervisor |
| IMViewer | IMbigben | Read-only |
