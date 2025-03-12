# 75 Hard Challenge Tracker

A simple web-based tracker for the 75 Hard Challenge that helps you monitor your daily progress.

## About the 75 Hard Challenge

The 75 Hard Challenge is a mental toughness program created by Andy Frisella. This implementation tracks the following daily tasks for 75 consecutive days:

- **Fitness**: Complete two 30-minute workouts each day (one outside and one inside)
- **Water**: Drink one gallon of water (128 ounces or 3 owala bottles)
- **Reading**: Read 2x 10 pages (one nonfiction and one fiction)
- **Food**: Eat whole foods and limit refined carbs and sugar intake
- **Progress Photo**: Take a daily progress photo
- **Weight Tracking**: Track your weight in pounds

If you miss any task on any day, you must start over from Day 1. (although I don't since this is a lifestyle for me)

## Features

This tracker implementation includes:

- Daily checkboxes for each required task
- Weight tracking functionality
- Local storage to save your progress between sessions

## Running Locally

To run this tracker locally:

```bash
# Option 1: Open directly in browser
# Simply double-click the index.html file

# Option 2: Use a local development server
npx serve

# Option 3: Use Python's built-in HTTP server
python -m http.server
```

## Data Storage

This application uses browser localStorage to save your progress. This means:

- Your data is stored only on your device
- Data will persist between browser sessions
- Data will not sync between different devices

## License

MIT
