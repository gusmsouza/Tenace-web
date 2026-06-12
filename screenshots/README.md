# TENACE — Screenshot Assets

Place real iPhone screenshots here. Three are required; a fourth is optional.

| Filename       | Screen            | What to capture                                         |
|----------------|-------------------|---------------------------------------------------------|
| `home.png`     | HomeScreen        | Streak card visible + an active plan card + week strip  |
| `logger.png`   | ExerciseLogger    | Mid-session — weight & reps filled in, previous sets    |
| `progress.png` | Progress/Badges   | Chart sparklines or the badges grid with earned badges  |
| `history.png`  | History (optional)| Expanded workout entry showing sets                     |

## How to add them

1. Take a screenshot on your iPhone (the real app, not a simulator)
2. Export at full resolution (PNG)
3. Drop the file here with the exact filename shown above

## How to activate them in the HTML

Find the SWAP comment above each placeholder in `index.html`. Replace the entire `.sp-shell` `<div>` block with a single `<img>` tag:

```html
<img src="screenshots/home.png"
     alt="TENACE home screen showing streak card and training plan"
     class="screenshot-img">
```

Do the same for the hero phone mockup — replace the `.hero-phone__placeholder` div with:

```html
<img src="screenshots/home.png" alt="TENACE home screen" class="hero-phone__img">
```

## Tips for great screenshots

- Use Light Mode for the screenshots (cleaner on a white background)
- Make sure a streak is active and a plan card is showing on the HomeScreen
- On the Logger screen, have 2 sets already logged before taking the screenshot
- Crop tight to the app content — no status bar if possible
