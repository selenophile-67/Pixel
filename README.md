# 🎬 Pixel – A Cinematic Streaming Platform

**Your world of stories, all in one place.**

Pixel is a modern, Netflix-inspired OTT streaming platform designed to bring movies, television series, anime, K-Dramas and C-Dramas together in one cinematic entertainment experience.

Featuring a sleek dark interface, personalized viewer profiles, content discovery, genre-based browsing and interactive watchlist functionality, Pixel recreates the experience of exploring a premium streaming service with its own unique identity.

---

## 🌟 About the Project

Pixel is a frontend-focused OTT streaming platform developed using modern web technologies.

The platform features a collection of fictional movies and shows, Pixel Originals and dedicated browsing experiences for different entertainment categories.

Its interface is designed around a cinematic dark theme, featuring large banners, attractive title cards, smooth transitions and intuitive navigation.

| Project Information | Details |
|---|---|
| **Project Name** | Pixel |
| **Project Type** | OTT Streaming Platform |
| **Category** | Web Development |
| **Architecture** | Component-Based Frontend |
| **Framework** | React + TanStack Start |
| **Styling** | Tailwind CSS |
| **Tagline** | Your world of stories, all in one place. |

## ✨ Key Features

### 🏠 1. Cinematic Homepage
- Modern streaming-platform interface with a premium dark theme.
- Large featured-content hero banner.
- Featured titles and promotional sections.
- Trending and popular content sections.
- Personalized content discovery.
- Continue Watching section.
- Attractive horizontal content carousels.

### 🎞️ 2. Multiple Entertainment Categories

Explore different types of entertainment through dedicated browsing pages.

- **Pixel Originals:** Discover fictional exclusive movies and series.
- **Movies:** Browse feature films across different genres.
- **Series:** Explore television shows and binge-worthy stories.
- **Anime:** Discover fantasy, action, adventure and slice-of-life anime.
- **K-Drama:** Explore Korean romance, thriller and drama titles.
- **C-Drama:** Discover Chinese historical, fantasy and romantic dramas.

### 🔍 3. Search and Content Discovery
- Search for movies and series.
- Discover content through keywords and genres.
- Browse dedicated category pages.
- Filter titles by year, language and rating.
- Sort content using different criteria.
- Reset filters to explore the complete catalogue.

### 🎬 4. Movie and Series Details

Every title has a dedicated information page featuring:

- Movie or series title.
- Background artwork and poster.
- Release year.
- Genre and language.
- Content maturity rating.
- User rating and match percentage.
- Runtime or season information.
- Synopsis and description.
- Cast members.
- Director and studio information.
- Similar and recommended titles.

### ❤️ 5. My List
Create a personalized collection of movies and shows.

- Add titles to My List.
- Remove previously saved titles.
- Browse saved movies and series.
- Maintain separate lists for different viewer profiles.
- Receive visual feedback when adding or removing titles.

### 👤 6. Multiple Viewer Profiles

Pixel provides multiple built-in viewer profiles to simulate a shared streaming account.

- Switch between different viewer profiles.
- Maintain separate preferences for each profile.
- Personalized watchlists and viewing progress.
- Dedicated Kids profile.
- Age-appropriate content filtering for Kids Mode.

### ▶️ 7. Continue Watching
- Track viewing progress for supported sample playback.
- Display previously watched titles.
- Show playback progress indicators.
- Resume titles using saved progress information.
- Remove titles from Continue Watching.

### 👍 8. Like and Dislike System
- Like movies and television shows.
- Mark titles as not preferred.
- Maintain individual preferences for each profile.
- Store preferences locally.

### 🔔 9. Notifications
- Display platform notifications.
- Highlight unread notifications.
- Track unread notification counts.
- Mark all notifications as read.
- Navigate to relevant titles from notifications.

### 📱 10. Responsive User Interface
- Modern cinematic dark theme.
- Responsive layouts for different screen sizes.
- Interactive movie and series cards.
- Smooth hover effects and transitions.
- Mobile-friendly navigation.
- Attractive typography and visual elements.

### 🎥 11. Sample Video Playback
Pixel includes sample video sources from openly licensed Blender Foundation films for demonstration purposes.

Available sample content includes:

- Big Buck Bunny
- Sintel
- Elephants Dream
- Tears of Steel

These sample videos demonstrate the media playback experience without hosting copyrighted commercial movies.

---

## 🛠️ Tech Stack

Pixel is built using modern frontend technologies and open-source libraries.

| Technology | Purpose |
|---|---|
| React 19 | Building reusable UI components |
| TypeScript | Type safety and maintainable code |
| TanStack Start | Application framework |
| TanStack Router | Application routing and navigation |
| Vite | Development server and build tool |
| Tailwind CSS 4 | Styling and responsive layouts |
| Radix UI | Accessible UI components |
| Lucide React | Icons and visual elements |
| TanStack Query | Query and data management |
| React Hook Form | Form management |
| Zod | Schema validation |
| Sonner | Toast notifications |
| Vitest | Testing framework |
| ESLint | Code quality and linting |
| Prettier | Code formatting |

---

## 🎨 Design and UI/UX

Pixel follows a premium OTT-inspired visual identity.

**Design Characteristics:**
- Dark backgrounds with subtle gradients.
- Cinematic movie banners and artwork.
- Bold and modern typography.
- Attractive movie and series cards.
- Smooth transitions and hover animations.
- Clean navigation and organized content sections.
- Responsive layouts for desktop, tablet and mobile devices.

**Typography:**
- Inter
- Poppins
- JetBrains Mono

The overall design focuses on creating an immersive entertainment experience with intuitive navigation and visually appealing content discovery.

---

## 📂 Project Structure

The project follows a modular, component-based architecture.

```text
Pixel/
│
├── public/
│   ├── favicon.ico
│   ├── favicon.svg
│   └── robots.txt
│
├── src/
│   │
│   ├── assets/
│   │   └── titles/                  # Movie and series artwork
│   │
│   ├── components/
│   │   ├── pixel/                   # Custom Pixel components
│   │   │   ├── BrowseView.tsx
│   │   │   ├── Footer.tsx
│   │   │   ├── Hero.tsx
│   │   │   ├── ListLikeButtons.tsx
│   │   │   ├── Logo.tsx
│   │   │   ├── Navbar.tsx
│   │   │   ├── ProfileAvatar.tsx
│   │   │   ├── TitleCard.tsx
│   │   │   ├── TitleMeta.tsx
│   │   │   └── TitleRow.tsx
│   │   │
│   │   └── ui/                      # Reusable UI components
│   │
│   ├── data/
│   │   └── catalog.ts               # Movie and series catalogue
│   │
│   ├── hooks/
│   │   └── use-mobile.tsx
│   │
│   ├── lib/
│   │   ├── viewer-store.tsx         # Viewer profiles and preferences
│   │   ├── utils.ts
│   │   ├── error-capture.ts
│   │   ├── error-page.ts
│   │   └── lovable-error-reporting.ts
│   │
│   ├── routes/
│   │   ├── __root.tsx
│   │   ├── index.tsx                # Homepage
│   │   ├── originals.tsx
│   │   ├── movies.tsx
│   │   ├── series.tsx
│   │   ├── anime.tsx
│   │   ├── kdrama.tsx
│   │   ├── cdrama.tsx
│   │   ├── genres.tsx
│   │   ├── search.tsx
│   │   ├── my-list.tsx
│   │   └── title.$id.tsx            # Title details
│   │
│   ├── test/
│   │   ├── app-routing.test.tsx
│   │   └── setup.ts
│   │
│   ├── routeTree.gen.ts
│   ├── router.tsx
│   ├── server.ts
│   ├── start.ts
│   └── styles.css
│
├── .gitignore
├── package.json
├── bun.lock
├── bunfig.toml
├── vite.config.ts
├── tsconfig.json
└── README.md
```

---

## 🚀 Getting Started

Follow these instructions to run Pixel on your local machine.

### Prerequisites

Make sure you have installed:

- [Node.js](https://nodejs.org/)
- npm (included with Node.js)

Alternatively, you can use [Bun](https://bun.sh/).

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/Pixel.git
```

Replace `YOUR-USERNAME` with your GitHub username.

### 2. Navigate to the Project Directory

```bash
cd Pixel
```

### 3. Install Dependencies

Using npm:

```bash
npm install
```

Or using Bun:

```bash
bun install
```

### 4. Start the Development Server

Using npm:

```bash
npm run dev
```

Or using Bun:

```bash
bun run dev
```

### 5. Open the Application

Open the local development URL displayed in your terminal.

Vite will provide the address where the application is running.

---

## 📜 Available Scripts

The following scripts are available in `package.json`.

| Command | Description |
|---|---|
| `npm run dev` | Starts the development server |
| `npm run build` | Creates a production build |
| `npm run build:dev` | Creates a development-mode build |
| `npm run preview` | Previews the production build |
| `npm run lint` | Runs ESLint checks |
| `npm run format` | Formats project files using Prettier |
| `npm test` | Runs the test suite |
| `npm run test:watch` | Runs tests in watch mode |

---

## 💾 Data Storage

Pixel currently uses a locally defined content catalogue and browser-based storage.

- Movie and series information is maintained in `src/data/catalog.ts`.
- Viewer profiles and preferences are managed through `src/lib/viewer-store.tsx`.
- My List, likes/dislikes, viewing progress and notification read status are stored using browser `localStorage`.
- Each browser maintains its own saved viewer data.
- Different viewer profiles maintain separate preferences.

**Important:** The current version does not include production backend authentication or cloud database synchronization. User preferences are stored locally in the browser.

---

## 🎥 Sample Video Credits

The project uses openly licensed sample films from the Blender Foundation for demonstration playback.

| Sample Film | Attribution | License |
|---|---|---|
| Big Buck Bunny | Blender Foundation | CC BY 3.0 |
| Sintel | Blender Foundation | CC BY 3.0 |
| Elephants Dream | Blender Foundation | CC BY 2.5 |
| Tears of Steel | Blender Foundation | CC BY 3.0 |

Please refer to the original releases and applicable licence terms for attribution and usage requirements.

The movies and series displayed in the Pixel catalogue are fictional and intended for demonstration purposes.

---

## 🔮 Future Enhancements

Potential improvements for future versions include:

- Backend integration and cloud database storage.
- Secure user authentication and registration.
- Individual user accounts.
- Integration with the TMDB API for movie and television metadata.
- Advanced recommendation algorithms.
- Enhanced content discovery and personalization.
- Improved video player controls.
- Subtitle and language selection.
- Enhanced Kids Mode and parental controls.
- Admin dashboard for content management.
- Deployment as a fully hosted streaming platform.

---

## ⚠️ Disclaimer

Pixel is an independent educational and development project inspired by popular OTT streaming platforms.

- Pixel is not affiliated with, sponsored by, or associated with Netflix.
- Netflix branding and logos are not used as the application's identity.
- Movie and series titles and their associated fictional information are created for demonstration purposes.
- Sample video content is sourced from openly licensed Blender Foundation films.
- Pixel does not host or distribute copyrighted commercial movies.

---

## 🎯 Learning Objectives

This project demonstrates practical experience with:

- Developing modern React applications.
- Using TypeScript for structured application development.
- Implementing client-side routing.
- Creating reusable and modular components.
- Managing application state using React Context.
- Persisting user preferences using localStorage.
- Building search and filtering functionality.
- Designing responsive layouts using Tailwind CSS.
- Creating interactive interfaces and reusable UI components.
- Working with media assets and sample video sources.

---

## 🙌 Acknowledgements

Special thanks to the developers and communities behind the technologies and resources used in this project.

- [Netflix](https://www.netflix.com/) – Inspiration for the OTT streaming experience.
- [Lovable](https://lovable.dev/) – AI-powered development platform.
- [React](https://react.dev/) – Frontend library.
- [TanStack](https://tanstack.com/) – Application framework and routing.
- [Tailwind CSS](https://tailwindcss.com/) – Styling framework.
- [Lucide](https://lucide.dev/) – Icon library.
- [Blender Foundation](https://www.blender.org/) – Openly licensed sample films.

---

## 👩‍💻 Author

**Oishee Biswas**

GitHub: [@selenophile-67](https://github.com/selenophile-67)

---

## ⭐ Support

If you find Pixel interesting, consider giving the repository a **star ⭐** on GitHub.

Your support and feedback are always appreciated!

**Made with ❤️ and a passion for building cinematic web experiences.**
