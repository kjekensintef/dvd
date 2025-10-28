# Din Våte Drøm - Official Website

This is the official website for Din Våte Drøm, built with [Astro](https://astro.build).

## 🚀 Project Structure

```text
/
├── public/
│   ├── dvd_logo.png
│   ├── DVD_logo.svg
│   ├── Facebook_Logo_Secondary.png
│   ├── Instagram_Glyph_White.png
│   ├── yt_logo_white_digital.png
│   └── yt_logo_fullcolor_white_digital.png
├── src/
│   ├── components/
│   │   ├── BandLogo.astro
│   │   ├── DvdScreensaver.astro
│   │   ├── ScrollIndicator.astro
│   │   ├── SocialRow.astro
│   │   ├── layout/
│   │   │   ├── Head.astro
│   │   │   └── Footer.astro
│   │   └── sections/
│   │       ├── Header.astro
│   │       ├── MediaSection.astro
│   │       ├── About.astro
│   │       └── Concerts.astro
│   ├── styles/
│   │   ├── global.css
│   │   └── sections.css
│   └── pages/
│       └── index.astro
└── package.json
```

### Component Structure

- `layout/`: Contains reusable page structure components
  - `Head.astro`: Meta tags and document head
  - `Footer.astro`: Copyright footer
- Core Components:
  - `BandLogo.astro`: Interactive band logo with emoji splash animation
  - `DvdScreensaver.astro`: Animated DVD logo bouncing screensaver with color transitions
  - `ScrollIndicator.astro`: Animated scroll indicator with fade-out effect
  - `SocialRow.astro`: Social media links with hover effects
- `sections/`: Contains main content section components
  - `Header.astro`: Page header layout and component composition
  - `MediaSection.astro`: Spotify and YouTube embeds
  - `About.astro`: Band description and info
  - `Concerts.astro`: Upcoming concert dates
- `styles/`: Contains CSS styles

## 🎸 Features

- Interactive band logo with splash emoji spawning
- Classic DVD screensaver animation
- Social media integration (Facebook, YouTube, Instagram)
- Embedded Spotify player and YouTube video
- Upcoming concert dates
- Band biography

## 💻 Development

1. Clone the repository
2. Install dependencies with `npm install`
3. Start the development server with `npm run dev`
4. Open `localhost:4321` in your browser

## 🧞 Commands for local development

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |

```

## 📝 License

### Code License
The source code for this website is licensed under the Apache License 2.0. This means you can:
- Use the code as a reference
- Modify and adapt the code
- Use it in your own projects
- Patent rights are explicitly granted
- Get an express grant of patent rights from contributors

However, please note that:
- The band name "Din Våte Drøm"
- The band logo and artwork
- All music and media content
- Social media assets and branding

are proprietary and remain the exclusive property of Din Våte Drøm. These assets cannot be used without explicit permission.
