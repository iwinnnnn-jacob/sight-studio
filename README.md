# Sight Studio

**Sight Studio** is an experimental visual programming environment written in C# (.NET 8+) designed to emulate the look and feel of classic Visual Studio (2005), but with support for vibrant alternative palettes (like osu!). It lets you build simple visual "programs" by dragging blocks onto a canvas, then export your creations to either TypeScript or Brainfuck code.

![Sight Studio Screenshot](docs/screenshot.png) <!-- Add this if you want to include a screenshot! -->

---

## ❗ Alpha Notice

🚧 **Sight Studio is in ALPHA. Many features are incomplete or missing, and bugs are likely! Expect rapid development and breaking changes.**

---

## Features

- **Drag-and-drop "blocks" editor:** Compose programs visually.
- **Language export:** Generate TypeScript or Brainfuck code.
- **Multiple color palettes:** Toggle between a Visual Studio 2005 vibe and a playful osu! theme (with more to come).
- **Resizable, classic-inspired UI:** Panels, toolbox, and menu mimicking classic desktop IDEs.
- **In-app warnings:** Users are alerted to alpha status.

## Roadmap / TODO

- Block-to-block connections (data flow)
- More block types: math, logic, loops, variables, etc.
- Program serialization (save/load projects)
- Export to other languages and more sophisticated output
- Undo/redo, block editing, and right-click context menus

---

## Getting Started

### Prerequisites

- Windows
- [.NET 8 SDK or later](https://dotnet.microsoft.com/en-us/download)

### Build & Run

1. **Clone this repository:**
    ```sh
    git clone https://github.com/YOURUSERNAME/sight-studio.git
    cd sight-studio
    ```

2. **Open with Visual Studio 2022 or any .NET-compatible IDE.**

3. **Restore packages and run the app** (F5 or `dotnet run` from the SightStudio directory).

---

## Screenshots

![UI Demo Light](docs/screenshots/vs2005_palette.png)
![UI Demo osu!](docs/screenshots/osu_palette.png)

---

## Directory structure

```text
SightStudio/
  ├─ Themes/
  │   ├─ VS2005Palette.xaml
  │   └─ OsuPalette.xaml
  ├─ MainWindow.xaml
  ├─ MainWindow.xaml.cs
  ├─ App.xaml
  ├─ App.xaml.cs
  ├─ SightStudio.csproj
  └─ ...other files...
README.md
```

---

## Contributing

Feel free to file issues, fork, and create pull requests! All contributors and ideas are welcome—especially in these early stages.

---

## License

Build User License (BUL)(see [BUILD-USER-LICENSE](BUILD-USER-LICENSE.md))
---

### Credits

- Visual Studio 2005 palette inspired by the classic Microsoft IDE.
- osu! palette inspired by [osu!](https://osu.ppy.sh/) community colors and branding.

---

**Made with C# and ❤️**# sight-studio
