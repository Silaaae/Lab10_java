# Lab 10 — Démo Navigation Drawer et Fragments

**Auteure : Nisrine Gorfti — EMSI**


## Description
Application Android démontrant l'utilisation du Navigation Drawer avec plusieurs fragments.

## Fonctionnalités
- Navigation Drawer avec menu latéral
- 3 fragments : Accueil, Profil, Paramètres
- Gestion du bouton retour
- Header personnalisé dans le drawer

## Structure
```
app/src/main/
├── java/com/example/navigationdrawer/
│   ├── MainActivity.java
│   ├── HomeFragment.java
│   ├── ProfileFragment.java
│   └── SettingsFragment.java
└── res/
    ├── layout/
    │   ├── activity_main.xml
    │   ├── nav_header.xml
    │   ├── fragment_home.xml
    │   ├── fragment_profile.xml
    │   └── fragment_settings.xml
    └── menu/
        └── nav_menu.xml
```

## Dépendances
```
implementation 'com.google.android.material:material:1.12.0'
implementation 'androidx.drawerlayout:drawerlayout:1.2.0'
```
<img width="252" height="492" alt="image" src="https://github.com/user-attachments/assets/88800cf6-4bb4-4fb2-9af4-0450ff68897a" />

<img width="485" height="1024" alt="image" src="https://github.com/user-attachments/assets/130d69da-b8e0-4494-9519-1f470f36419f" />
