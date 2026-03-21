<p align="center">
  <img src="https://img.shields.io/badge/VextOS-v1.0-9B8EC1?style=for-the-badge&labelColor=0a0a0f" />
  <img src="https://img.shields.io/badge/Next.js_14-black?style=for-the-badge&logo=next.js" />
  <img src="https://img.shields.io/badge/Three.js-black?style=for-the-badge&logo=three.js" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
</p>

<br/>

<h1 align="center">
  <code>~/vextos</code>
</h1>

<p align="center">
  <strong>An interactive OS-themed portfolio that runs in your browser.</strong>
  <br/>
  <sub>Not your average portfolio. This is an operating system.</sub>
</p>

<p align="center">
  <a href="https://vextos-portfolio.vercel.app"><strong>[ ENTER VEXTOS ]</strong></a>
</p>

<br/>

---

<br/>

## `> whoami`

```
stranger@vextos ~ $ whoami

  Metodij Krshkov
  Java Developer @ Galenica | Founder @ Vext Agency | HFTM Student
  Swiss-based | 4 Languages | 20+ Projects

  lolzicreator@gmail.com
```

<br/>

## `> neofetch`

```
                  ╔══════════════════════╗
  ██╗   ██╗      ║     V e x t O S      ║
  ██║   ██║      ╠══════════════════════╣
  ██║   ██║      ║  OS:      VextOS 1.0 ║
  ╚██╗ ██╔╝      ║  Host:    Browser    ║
   ╚████╔╝       ║  Shell:   Next.js 14 ║
    ╚██╔╝        ║  Engine:  Three.js   ║
     ██║         ║  UI:      Tailwind   ║
     ╚═╝         ║  State:   Zustand    ║
                  ║  Motion:  Framer    ║
  x t O S        ║  Lang:    TypeScript ║
                  ╚══════════════════════╝
```

<br/>

## `> ls features/`

```
drwxr-xr-x  boot-sequence/        BIOS-style boot → Login → Desktop
drwxr-xr-x  particle-wallpaper/   Three.js face portrait made of 100k+ particles
drwxr-xr-x  code-rain/            Matrix-style falling code background
drwxr-xr-x  window-manager/       Drag, resize, minimize, maximize, close
drwxr-xr-x  spotlight/            ⌘K / ⌘Space search & app launcher
drwxr-xr-x  terminal/             Working CLI with 15+ commands
drwxr-xr-x  context-menu/         Right-click desktop menu
drwxr-xr-x  notifications/        Toast notification system
drwxr-xr-x  keybinds/             Full keyboard shortcut system
drwxr-xr-x  widgets/              Clock, Quick Info, Now Playing
```

<br/>

## `> ls apps/`

| App | Description |
|-----|-------------|
| `about.txt` | Full profile — career timeline, skills, languages, interests |
| `projects/` | Portfolio grid with 6 projects & category filtering |
| `browser` | Personal links page with bookmarks |
| `mail` | Contact form disguised as email client |
| `music` | Tecno-themed player with animated visualizer |
| `terminal` | CLI with `neofetch`, `skills`, `contact`, `cat`, and more |
| `settings` | System info & credits panel |
| `game` | Playable Snake game |

<br/>

## `> cat keyboard-shortcuts.md`

| Shortcut | Action |
|----------|--------|
| `⌘ + Space` | Spotlight Search |
| `⌘ + K` | Spotlight Search |
| `⌘ + W` | Close window |
| `⌘ + M` | Minimize window |
| `⌘ + Shift + M` | Maximize window |
| `⌘ + Q` | Shutdown (restart) |
| `⌘ + /` | Keybindings panel |
| `Right-click` | Context menu |
| `Double-click` | Open desktop icon |

<br/>

## `> cat tech-stack.md`

```
Frontend        Next.js 14 (App Router) + TypeScript
Styling         Tailwind CSS + CSS Variables + Glass Morphism
3D Engine       Three.js via @react-three/fiber
Animations      Framer Motion (springs, layout, presence)
State           Zustand (window manager, notifications)
Fonts           Cabinet Grotesk, General Sans, JetBrains Mono
Deploy          Vercel
```

<br/>

## `> ./install.sh`

```bash
# Clone the repo
git clone https://github.com/lolzi-creator/portfolioOS.git
cd portfolioOS

# Install dependencies
npm install --legacy-peer-deps

# Add your face photo
cp your-photo.png public/face.png

# Run it
npm run dev

# Open http://localhost:3000
```

<br/>

## `> tree src/`

```
vextos-portfolio/
├── app/
│   ├── layout.tsx          # Root layout, fonts, metadata
│   ├── page.tsx            # Boot → Login → Desktop flow
│   └── globals.css         # Theme, glass effects, grain overlay
├── components/
│   ├── boot/               # BIOS boot sequence
│   ├── login/              # Stranger/Owner profile selection
│   ├── desktop/            # Desktop shell, dock, menu bar, windows
│   │   ├── Wallpaper.tsx   # Three.js particle face
│   │   ├── CodeRain.tsx    # Matrix code rain (Canvas 2D)
│   │   ├── Window.tsx      # Draggable/resizable window
│   │   ├── Dock.tsx        # Bottom dock with magnification
│   │   ├── Spotlight.tsx   # ⌘K command palette
│   │   └── ...
│   ├── apps/               # 8 app components
│   └── shared/             # Context menu, icons
├── stores/                 # Zustand (windows, notifications)
└── lib/                    # Constants, app definitions
```

<br/>

---

<p align="center">
  <sub>Built with obsessive attention to detail by <strong>Metodij Krshkov</strong></sub>
  <br/>
  <sub>
    <a href="https://vextagency.ch">Vext Agency</a> ·
    <a href="mailto:lolzicreator@gmail.com">Email</a> ·
    Swiss-made 🇨🇭
  </sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-stranger_welcome-9B8EC1?style=flat-square&labelColor=0a0a0f" />
</p>
