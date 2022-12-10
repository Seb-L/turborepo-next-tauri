# Turborepo + Next.JS + TauriApp

## Dev env

```
yarn dev --filter=web --filter=desktop
```

## Build desktop app

```
yarn build --filter=desktop
```

This command is dependent to the next export command (itself dependent to next build)

Next Build -> Next Export -> Tauri build
