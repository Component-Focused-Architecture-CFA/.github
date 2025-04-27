# Welcome to CFA!

This is a front-end architecture I designed to keep React and Next.js projects scalable, readable, and easy to work with. It helps organize files in a way that makes development smoother and maintenance simpler. While it's mainly designed for React and Next.js, you can tweak it to fit your own projects however you like.

## Why I made this
I wanted a structure that actually makes sense for the way I build projects. Most existing architectures felt either too rigid or overcomplicated, forcing patterns that don’t really fit. So instead of trying to force my work into someone else’s system, I decided to create my own—one that keeps things clear, scalable, and easy to work with.

This documentation is my way of putting everything into one place, both for myself and for anyone who might find it useful. It’s not about following rules just for the sake of it—it’s about making development feel natural and efficient.

## How it's organized
This project structure is designed for clarity, scalability, and maintainability:

- **app/** — App Router structure (usage may vary depending on your framework).

- **pages/** — Optional. Pages for file-based routing (Next.js Pages Router or React Router).

- **features/** — Logic-heavy components (actions, widgets, fetchers) managing workflows and APIs.

- **ui/** — Reusable presentational components, split into `components/` and `elements/`.

- **shared/** — Global utilities: hooks, functions, types, API slices.

It follows a **top-down hierarchy** (only importing from lower layers), keeps everything **localized** with scoped folders, uses **no global barrel files**, and follows a **kebab-case naming convention** for consistency.

## Full documentation:

- [Project Structure](https://github.com/Component-Focused-Architecture-CFA/docs/blob/main/project-structure.md) — How everything is organized and why.
- [Customization & FAQ](https://github.com/Component-Focused-Architecture-CFA/docs/blob/main/customization-and-faq.md) — How to adapt CFA to your projects and common questions.

---

![](https://komarev.com/ghpvc/?username=Component-Focused-Architecture-CFA&style=flat-square&color=brightgreen)
