# Random Recipe of the Day

A React UI snippet that shows a **"Random Recipe of the Day"** card — dietary filters (vegetarian / vegan / gluten-free), save-to-favorites, and step-by-step cooking instructions. Built as a starting point for a food-inspiration widget.

## Features

- 🎲 **Random recipe picker** — surfaces a different recipe every day
- 🥗 **Dietary filters** — filter by vegetarian, vegan, gluten-free
- ❤️ **Favorites** — save favorite recipes locally
- 🧾 **Step-by-step instructions** — clear ingredient lists and method

## Tech Stack

- React (Hooks: `useState`, `useEffect`)
- shadcn/ui components (`Button`, `Card`, `Label`, `RadioGroup`)
- lucide-react icons

## Getting Started

This repo currently holds a single self-contained snippet (`Random Recipe of the Day`). To use it in your project:

1. Create a Vite + React + Tailwind project and install shadcn/ui components.
2. Copy the snippet into a component (e.g. `src/components/RecipeOfTheDay.jsx`).
3. Import and render it:

```jsx
import RecipeOfTheDay from './components/RecipeOfTheDay';

export default function App() {
  return <RecipeOfTheDay />;
}
```

## Roadmap / Ideas

- Fetch live recipes from the [Spoonacular API](https://spoonacular.com/food-api) (free tier)
- Persist favorites in `localStorage` or IndexedDB
- Add cuisine and meal-type filters

## License

See [LICENSE](./LICENSE).

---

**Built by [Girish Lade](https://ladestack.in)** — solo founder of [LadeStack](https://ladestack.in).
