# Photo Manager 🖼️

A lightweight Windows photo viewer built with **PowerShell + WPF** that gives you a clean desktop image browsing experience without needing a full photo management suite.


<img width="1637" height="1002" alt="image" src="https://github.com/user-attachments/assets/a3280d97-1814-414f-856a-94bfd416267c" />

## What it is

PSPhotoViewer is a standalone image viewer for Windows designed to open folders of images, browse them quickly, preview thumbnails, and view photos in a larger main display. It focuses on being simple, fast, and practical for everyday use.

## Who it's for

This project is for people who want:

- A simple image viewer without extra bloat
- A PowerShell-based desktop app they can run and modify
- Quick folder browsing for local image collections
- A customizable viewer that remembers layout and window settings
- A lightweight alternative to heavier photo tools

It is especially useful for:

- PowerShell users
- Windows users who work with image folders often
- Scripters and tinkerers who want a readable, editable viewer
- Anyone who wants a straightforward photo browser 📂

## What it does

PSPhotoViewer lets you:

- Open an image or an entire folder
- Browse supported images from a folder tree
- See image previews in a side panel
- Switch between thumbnail and detail views
- View full-size images in the main pane
- Zoom in, zoom out, and fit images to the window
- Navigate forward and backward through images
- Run a fullscreen slideshow
- Drag and drop files or folders directly into the app
- Delete images to the Recycle Bin
- Save your layout and viewing preferences between sessions

## Features ✨

### Image viewing
- Supports common image formats:
  - `.jpg`
  - `.jpeg`
  - `.png`
  - `.bmp`
  - `.gif`
  - `.tiff`
  - `.tif`
  - `.ico`
- Main image display with high-quality scaling
- Best fit and actual size viewing modes
- Mouse wheel zoom support
- Click-and-drag panning for zoomed images

### Folder and preview navigation
- Folder tree for browsing image directories
- Preview list for quick image selection
- Thumbnail mode for visual browsing
- Details mode with:
  - file name
  - file size
  - modified date
- Sort previews by:
  - name
  - size
  - date modified

### Window and layout memory
- Remembers:
  - window size
  - window position
  - maximized state
  - left panel width
  - preview panel height
  - thumbnail size
  - selected view mode
  - zoom mode
  - sort settings
  - last opened folder
- Saves settings to an `.ini` file in Local AppData

### Fullscreen slideshow
- Fullscreen image display
- Previous / next controls
- Pause and resume slideshow
- Auto-hiding fullscreen controls for a cleaner viewing experience 🎞️

### Quality of life
- Drag-and-drop support for files and folders
- Keyboard shortcuts for navigation and actions
- Delete to Recycle Bin instead of permanent removal
- Lightweight and easy to customize

## Why this project exists

PSPhotoViewer was made to provide a practical, scriptable photo viewer using tools already available on Windows. Instead of a large framework or external dependency-heavy app, it uses PowerShell and WPF to create a desktop viewer that is easy to run, understand, and extend.

## Summary

If you want a **simple, customizable Windows photo viewer built in PowerShell**, PSPhotoViewer is a great fit. It gives you folder browsing, previews, zooming, sorting, slideshow support, and saved layout preferences in a compact desktop app. 🚀
