# adw-gtk3 package for openSUSE

[![Build Status](https://build.opensuse.org/projects/home:ericfrs/packages/adw-gtk3-theme/badge.svg)](https://build.opensuse.org/projects/home:ericfrs/packages/adw-gtk3-theme)

This repository contains the build files to package the [adw-gtk3](https://github.com/lassekongo83/adw-gtk3) theme for **openSUSE** using the [Open Build Service (OBS)](https://openbuildservice.org/).

The goal is to provide a simple and direct integration for openSUSE users who want a modern and consistent look for their GTK3 applications.

## ✨ What is adw-gtk3?

**adw-gtk3** is a GTK3 theme that replicates the look and feel of Libadwaita (the UI library for GTK4 and GNOME). Its purpose is to make older GTK3 applications look consistent and modern alongside native GNOME 42+ and GTK4 applications.

## 🚀 Installation (openSUSE Tumbleweed)

You can install the theme directly from my OBS repository.

1.  **Add the repository:**

    ```bash
    sudo zypper ar -cfp 90 https://download.opensuse.org/repositories/home:ericfrs/openSUSE_Tumbleweed/home:ericfrs.repo
    ```

2.  **Refresh repositories and install the theme:**
    ```bash
    sudo zypper refresh
    sudo zypper install adw-gtk3-theme
    ```

## 🎨 Usage

Once installed, you can apply the theme using a tool like `gnome-tweaks`.

1.  Open the "Tweaks" application.
2.  Go to the "Appearance" tab.
3.  In the "Themes" section, change "Legacy Applications" to **adw-gtk3**.

## 📦 Purpose of this Repository

This repository does **not** contain the theme's source code. It simply stores the files that OBS uses to automatically download the original source code from the [upstream repository](https://github.com/lassekongo83/adw-gtk3) and build the RPM package.
