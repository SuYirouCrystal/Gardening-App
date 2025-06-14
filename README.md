# Gardening App

A modern gardening diary application built with Next.js, React, Firebase, and Tailwind CSS. This app lets users sign in, track their garden's progress, and maintain diary entries with beautiful plant-themed visuals.

## Features

- **User Authentication**: Secure login/signup powered by Firebase Authentication.
- **Diary Entries**: Log and track your gardening progress with color-coded diary cards.
- **Garden Visualization**: View plant illustrations and progress bars representing your virtual garden.
- **Modern UI**: Responsive, clean design using Tailwind CSS and ready-to-use React components.

## Tech Stack

- **Framework**: [Next.js](https://nextjs.org/), [React](https://react.dev/)
- **UI**: [Tailwind CSS](https://tailwindcss.com/), [react-icons](https://react-icons.github.io/react-icons/)
- **Backend**: [Firebase](https://firebase.google.com/)
- **Component Libraries**: [Headless UI](https://headlessui.dev/), [Heroicons](https://heroicons.com/), [mdb-react-ui-kit](https://mdbootstrap.com/docs/react/)
- **State Management**: React hooks with [react-firebase-hooks](https://github.com/CSFrequency/react-firebase-hooks)
- **Router**: Next.js routing, [react-router-dom](https://reactrouter.com/en/main)
- **Others**: Styled JSX, PostCSS, ESLint

## Getting Started

### 1. Clone the repository

```bash
git clone <YOUR_REPO_URL>
cd Gardening-App-main/garden
```

### 2. Install dependencies

```bash
npm install
```

### 3. Set up Environment Variables

Create a `.env.local` file in the root of the `garden` directory:

```
NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_auth_domain
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_storage_bucket
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id
NEXT_PUBLIC_FIREBASE_MEASUREMENT_ID=your_measurement_id
```

These credentials are used to initialize Firebase in `src/config/firebase-config.js`.

### 4. Run the development server

```bash
npm run dev
```

Visit [http://localhost:3000](http://localhost:3000) to view the app.

## Project Structure

```
garden/
  ├── public/
  │   └── plants/           # Plant SVG images
  ├── src/
  │   ├── app/
  │   │   ├── auth/         # Sign-up/Login pages
  │   │   ├── components/   # UI components (Navbar, Progress bar, etc.)
  │   │   ├── pages/        # Main pages (diary, home, etc.)
  │   │   └── config/       # Firebase configuration
  │   └── globals.css       # Global styles
  ├── package.json
  └── tailwind.config.js
```

## Notable Files

- `src/app/page.js`: Main sign-in page logic
- `src/pages/diary-page.js`: Garden and diary overview UI
- `src/components/*`: Reusable interface components (navbar, bars, plant pots, etc.)
- `src/config/firebase-config.js`: Handles Firebase app/auth initialization

## Customization

- You can add plant SVGs to `public/plants` for additional types.
- Tailwind and the component structure make it easy to reskin or extend components as needed.

## Deployment

This app can be deployed on platforms supporting Next.js, such as Vercel, Netlify, or your own server.

## License

Include your license conditions here if needed.

## Acknowledgements

- [Next.js](https://nextjs.org/)
- [React](https://reactjs.org/)
- [Firebase](https://firebase.google.com/)

---

Let me know if you’d like a more detailed guide, badges, or expanded instructions!
