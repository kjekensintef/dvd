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
│   │   ├── layout/
│   │   │   ├── Head.astro
│   │   │   └── Footer.astro
│   │   ├── DvdScreensaver.astro
│   │   └── sections/
│   │       ├── Header.astro
│   │       ├── MediaSection.astro
│   │       ├── About.astro
│   │       └── Concerts.astro
│   ├── styles/
│   │   └── global.css
│   └── pages/
│       └── index.astro
└── package.json
```

### Component Structure

- `layout/`: Contains reusable page structure components
  - `Head.astro`: Meta tags and document head
  - `Footer.astro`: Copyright footer
- `DvdScreensaver.astro`: Animated DVD logo bouncing screensaver with color transitions
- `sections/`: Contains main content section components
  - `Header.astro`: Logo, social links, and interactive emoji animation
  - `MediaSection.astro`: Spotify and YouTube embeds
  - `About.astro`: Band description and info
  - `Concerts.astro`: Upcoming concert dates
- `styles/`: Contains global CSS styles

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |

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

## 🚀 Deployment

Build the site for production:

```bash
npm run build
```

The built site will be in the `dist/` directory, ready to be deployed to your hosting provider.