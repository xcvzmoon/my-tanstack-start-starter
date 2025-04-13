# TanStack Starter with ShadcnUI & TailwindCSS 4

My starter template for building web applications with:

- [TanStack Router](https://tanstack.com/router) for routing
- [ShadcnUI](https://ui.shadcn.com/) for beautiful, accessible components
- [TailwindCSS v4](https://tailwindcss.com/) for utility-first styling

## Features

- 🚀 Pre-configured TanStack Router setup
- 🎨 ShadcnUI components integrated
- 💅 TailwindCSS v4 with modern configuration
- ⚡️ Fast development workflow
- 📱 Responsive design ready
- 🔥 Dark/light mode support

## Getting Started

1. **Clone the repository**

   ```bash
   bunx gitpick xcvzmoon/my-tanstack-start-starter [project-name]
   cd [project-name]
   ```

2. **Install dependencies**

   ```bash
   bun install
   ```

3. **Start the development server**

   ```bash
   bun run dev
   ```

4. **Open your browser**
   Visit `http://localhost:3000` to see your app running.

## Project Structure

```markdown
.
├── app/
│   ├── components/
│   │   └── ui/
│   │   │   └── `button.tsx`
│   ├── routes/
│   │   └── `__root.tsx`
│   ├── `client.tsx`
│   ├── `router.tsx`
│   ├── `routeTree.gen.ts`
│   └── `ssr.tsx`
├── `.gitignore`
├── `app.config.ts`
├── `package.json`
└── `tsconfig.json`
```

## Scripts

```bash
bun run dev
bun run build
bun run start
```

## Customizing ShadcnUI

To add more ShadcnUI components:

```bash
bunx shadcn@canary add [component-name]
```
