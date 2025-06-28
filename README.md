<p align="center" style="background-color: white">
  <a href="https://innohassle.ru">
    <img alt="InNoHassle" height="300px" src="https://raw.githubusercontent.com/one-zero-eight/design/212a5c06590c4d469a0a894481c09915a4b1735f/logo/ing-white-outline-transparent.svg">
  </a>
</p>

# Website | InNoHassle ecosystem

> https://innohassle.ru

[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=one-zero-eight_InNoHassle-Website&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=one-zero-eight_InNoHassle-Website)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=one-zero-eight_InNoHassle-Website&metric=bugs)](https://sonarcloud.io/summary/new_code?id=one-zero-eight_InNoHassle-Website)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=one-zero-eight_InNoHassle-Website&metric=vulnerabilities)](https://sonarcloud.io/summary/new_code?id=one-zero-eight_InNoHassle-Website)

## About

**InNoHassle** is a digital ecosystem for students of Innopolis University, created by [one-zero-eight](https://github.com/one-zero-eight) community.

The website integrates with the service APIs, including:
- [Music Room](https://github.com/one-zero-eight/music-room)
- [Schedule](https://github.com/one-zero-eight/events)
- [Room Booking](https://github.com/one-zero-eight/room-booking)

### Services
- 🗂️ **Dashboard**
  - Access a centralized list of university and city services
- 🗓️ **Calendar**
  - Keep your class schedule available at all times
- 🗺️ **Maps**
  - Find a classroom or professor's office
  - Navigate to other university or sport complex locations
  - Share the meeting point with friends
- 📌 **Room booking**
  - Reserve university rooms for extracurricular activities or relaxation
- 📋 **Schedule**
  - View schedules for core courses, electives, sports sections, and cleaning
  - Add academic groups to favorites to see them in your personal account
  - Export schedules to your preferred calendar applications
- 💰 **Scholarship**
  - Calculate your scholarship based on expected grades or GPA
  - Access detailed information on available university scholarships
- 🖨️ **Printers**
  - Use a bot to print documents on university printers
- 🛏️ **Dorms**
  - Use the Telegram bot to manage household tasks with roommates
  - Set reminders to follow your daily routines
- 🎵 **Music room**
  - View all current music room bookings
  - Make your own booking
- ⚽ **Sports**
  - Access a separate calendar for sports events and activities
- 🚀 **Extension**
  - Accelerate authentication across university services by skipping manual credential entry

### More features

- 🔑 Sign in to your personal account using your student email credentials

- 📴 Use the website even with a poor or unstable internet connection

- 🌞 Switch between dark and light mode for comfortable use

### Technologies

- Core: [Node.js](https://nodejs.org), [TypeScript](https://www.typescriptlang.org/)
- Frontend: [React](https://react.dev/), [Vite](https://vitejs.dev/), [TanStack Router](https://tanstack.com/router/latest/docs/framework/react/overview)
- Vue integration: [Vue](https://vuejs.org/), [Veaury](https://github.com/gloriasoft/veaury)
- Styling: [TailwindCSS](https://tailwindcss.com/), [Iconify](https://iconify.design/)
- Code quality: [Husky](https://typicode.github.io/husky/), [lint-staged](https://github.com/lint-staged/lint-staged), [Prettier](https://prettier.io/), [ESLint](https://eslint.org/)
- Data fetching: [OpenAPI Typescript](https://openapi-ts.dev/), [TanStack Query](https://tanstack.com/query/latest)
- Calendar: [FullCalendar](https://fullcalendar.io/), [ical.js](https://github.com/kewisch/ical.js)

## Development

### Set up for development

1. Install [Node.js 20+](https://nodejs.org), [pnpm](https://pnpm.io)
2. Install dependencies: `pnpm install`
3. Start development server: `pnpm run dev --host`
4. Open in the browser: https://local.innohassle.ru:3000
   > The page will be reloaded when you edit the code

> [!IMPORTANT]
> You must use HTTPS with domain https://local.innohassle.ru:3000 to access APIs with your account.

> [!TIP]
> When the API types change, you can run `pnpm run gen:api` to generate new client types and functions.

### Preview production build

1. Build the application: `pnpm run build`
2. Run the production-like server: `pnpm run preview --host`
3. Open in the browser: https://local.innohassle.ru:3000

### Project structure

- `src/` - main source code
  - `app/` - entry point of the application
    - `routes` - routing via [TanStack Router](https://tanstack.com/router/latest/docs/framework/react/guide/file-based-routing)
  - `components/` - components split by pages
  - `lib/` - utilities and domain-specific logic
  - `api/` - API clients and types
- `public/` - static files

## Contributing

We are open to contributions of any kind.
You can help us with code, bugs, design, documentation, media, new ideas, etc.
If you are interested in contributing, please read our [contribution guide](https://github.com/one-zero-eight/.github/blob/main/CONTRIBUTING.md).
