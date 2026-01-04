# Portfolio

**Harshal Jadhav**  
Full-Stack Web Developer – Fresher

---

## Overview

This repository contains the source code for my personal portfolio website. It serves as a comprehensive showcase of my skills, projects, and technical abilities as a full-stack developer. The application is built with a focus on modern web standards, performance optimisation, and clean user interface design.

## Live Demo

[View Live Portfolio](#) _(Link to be updated)_

## Preview

![Portfolio Preview](public/landing-memojis.png)
_(Placeholder for project screenshot)_

## About This Portfolio

I built this portfolio to demonstrate my ability to craft responsive and interactive web applications using modern technologies. My primary goal was to create a platform that not only displays my work but also reflects my commitment to writing clean, maintainable code and understanding user experience principles.

Key objectives included:

-   Implementing a scalable component-based architecture.
-   Utilising TypeScript for type safety and code robustness.
-   Designing a responsive layout that works seamlessly across devices.

## Tech Stack

**Frontend**

-   **Next.js 14**: Framework for server-side rendering and static site generation.
-   **React**: Library for building user interfaces.
-   **TypeScript**: Static typing for enhanced development reliability.
-   **Tailwind CSS**: Utility-first CSS framework for rapid and consistent styling.
-   **Framer Motion**: Library for performant and complex animations.
-   **shadcn/ui**: Reusable component collection built on Radix UI.

**Backend & Tools**

-   **Node.js**: JavaScript runtime environment.
-   **Git & GitHub**: Version control and source code management.
-   **Vercel**: Platform for deployment and hosting.

## Key Features

-   **Responsive Design**: distinct layouts optimised for mobile, tablet, and desktop viewports.
-   **Component Architecture**: Modular and reusable component structure for easier maintenance.
-   **Performance Optimised**: Leverages Next.js features like efficient image loading and code splitting.
-   **Interactive UI**: Smooth transitions and scroll-driven animations using Framer Motion.
-   **Dark Mode**: Native support for light and dark color schemes.

## Project Structure

```bash
/src
├── /app             # Next.js app router pages and layouts
├── /components      # Reusable UI components
│   ├── /ui          # shadcn/ui and base primitives
│   ├── /projects    # Project-specific components
│   └── ...          # Section components (Header, Skills, etc.)
├── /lib             # Utility functions and configurations
├── /public          # Static assets (images, fonts)
└── /styles          # Global styles and Tailwind configuration
```

## Getting Started

Follow these steps to set up the project locally:

1.  **Clone the repository**

    ```bash
    git clone https://github.com/HarshJadhav81/Portfolio.git
    cd Portfolio
    ```

2.  **Install dependencies**

    ```bash
    npm install
    # or
    pnpm install
    ```

3.  **Run the development server**

    ```bash
    npm run dev
    # or
    pnpm dev
    ```

4.  **View the application**

    Open `http://localhost:3000` in your browser.

## Customization

-   **Personal Details**: Update `src/components/contact.tsx` and header components with your information.
-   **Projects**: Modify the data in `src/components/projects/Data.tsx` to add or remove projects.
-   **Styling**: Adjust `tailwind.config.ts` and `src/app/globals.css` for theme customization.

## Future Enhancements

-   **Blog Integration**: Adding a section for technical writing and tutorials.
-   **CMS Integration**: Connecting to a headless CMS for easier content management.
-   **Testing**: Implementing unit and integration tests (Jest/Cypress).

## Contact

-   **Email**: [harshaljadhav814@gmail.com](mailto:harshaljadhav814@gmail.com)
-   **LinkedIn**: [Harshal Jadhav](https://www.linkedin.com/in/harshjadhav07)

## License

This project is licensed under the MIT License.
