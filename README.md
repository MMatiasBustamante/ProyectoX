# ProyectoX

Proyecto en equipo construido con [Next.js](https://nextjs.org) (App Router), React, TypeScript y Tailwind CSS 4.

## Requisitos

- Node.js >= 20.9
- [pnpm](https://pnpm.io) 11 (versión fijada en `packageManager`). Con Corepack: `corepack enable`

Usamos **pnpm** como único gestor de paquetes. No uses `npm install` ni `yarn`, para no generar otros lockfiles.

## Puesta en marcha

```bash
git clone https://github.com/MMatiasBustamante/ProyectoX.git
cd ProyectoX
pnpm install
pnpm dev
```

Abrí [http://localhost:3000](http://localhost:3000). La página principal está en `app/page.tsx`.

## Scripts

| Comando      | Descripción                       |
| ------------ | --------------------------------- |
| `pnpm dev`   | Servidor de desarrollo            |
| `pnpm build` | Build de producción               |
| `pnpm start` | Sirve el build de producción      |
| `pnpm lint`  | Corre ESLint 10 (flat config)     |

## Variables de entorno

Los archivos `.env*` están en `.gitignore`. Si el proyecto necesita variables, pedíselas al equipo y creá tu `.env.local`; no las subas al repo.

## Flujo de trabajo

- Corré `pnpm lint` antes de cada commit.
- Si agregás o actualizás dependencias, commiteá también `pnpm-lock.yaml`.
