# Vite - React - TypeScript Template with ESLint, Prettier and Vitest

v 0.9

---

## Custom Scripts

format: run Prettier

lint: run ESLint

fix: run ESLint --fix

test: run Vitest

coverage: C8 test coverage report

## CSS

All CSS from original package has been removed. Below are intructions for adding PicoCSS or Tailwind.

#### PicoCSS

```
npm i @picocss/pico
```

```
import"@picocss/pico/css/pico.min.css" //into App.tsx
```

#### Tailwind

```
npm i -D tailwindcss
npx tailwindcss init
```

```
@tailwindbase;
@tailwindcomponents;
@tailwindutilities;
```

## Enironment variables

If you are using environment variables, the entries in the .env file can be used in the following format:

`import.meta.env.MY_VARIABLE`

## Testing

This template uses Testing Library for React. Check out the [documentation](https://testing-library.com/docs/).

## Folder Structure

The *documentation* folder is used for storing notes and assets relevant to the project. It is included in .gitignore.

## Logs

v 0.9 - Created first version.
