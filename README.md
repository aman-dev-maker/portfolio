# Aman Kumar — Portfolio

My personal developer portfolio, built to showcase my projects, open-source work, and background as a B.Tech Computer Science (AI/ML) student.

Live site: [add your deployed URL here once live]

## Tech stack

*   **Framework:** [Next.js 16](https://nextjs.org/) (App Router) with [React 19](https://react.dev/) and TypeScript
*   **Styling:** [Tailwind CSS 4](https://tailwindcss.com/)
*   **3D / Animation:** [Three.js](https://threejs.org/) via @react-three/fiber and @react-three/drei, smooth scrolling with [Lenis](https://github.com/darkroomengineering/lenis)
*   **Icons:** [Simple Icons](https://simpleicons.org/)
*   **Tooling:** ESLint, containerized with Docker

## Getting started

Clone the repository and install dependencies:
```bash
git clone https://github.com/aman-dev-maker/portfolio.git
cd portfolio
npm install
```

Run the development server:
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000/) in your browser to view the site.

## Other scripts

```bash
npm run build # Production build
npm run start # Start the production server
npm run lint  # Run ESLint
```

## Running with Docker

```bash
docker build -t portfolio .
docker run -p 3000:3000 portfolio
```

## Project structure

```text
portfolio/
├── app/          # Next.js App Router pages and layouts
├── components/   # Reusable UI components
├── lib/          # Utility functions and shared logic
├── public/       # Static assets
└── Dockerfile    # Container build configuration
```

## About me

I'm a second-year B.Tech Computer Science (AI/ML) student, working across web development and applied GenAI tooling (LangChain, RAG, LLM APIs). I've contributed a merged pull request to an open-source genomics research project and authored a full technical proposal for Google Summer of Code 2026.

*   **GitHub:** [@aman-dev-maker](https://github.com/aman-dev-maker)
*   **LinkedIn:** [aman-singh-156799370](https://www.linkedin.com/in/aman-singh-156799370/)
*   **Email:** amanniju2@gmail.com

## License

This project is licensed under the [MIT License](LICENSE).