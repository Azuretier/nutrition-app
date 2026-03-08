# 🥗 Nutrition App — 栄養管理記録

A clinical-grade nutrition tracking application built with React.

## Features

- **Food Logging** — Search and log meals across breakfast, lunch, dinner, and snacks from a built-in Japanese food database (29 items)
- **Nutrition Summary** — Track calories, protein, fat, carbs, fiber, and sodium against daily goals with color-coded status indicators
- **PFC Balance** — Visualize protein/fat/carb macro ratios with recommended ranges
- **Goal Management** — Customize daily nutrition targets
- **Exercise Tracking** — Log exercises with MET-based calorie burn calculation (15 exercise types)
- **Calorie Balance** — Net calorie tracking (intake − exercise burn)

## Tech Stack

- React (JSX)
- Inline styles with [Outfit](https://fonts.google.com/specimen/Outfit) + Noto Sans JP fonts
- No external dependencies beyond React

## Getting Started

This component is designed to be imported into an existing React project:

```jsx
import NutritionApp from './nutrition-app';

function App() {
  return <NutritionApp />;
}
```

## License

MIT
