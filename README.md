# Keep Your Shoes Clean!

A mobile-friendly game where you control a stick figure at the bottom of the screen, avoiding falling dirt piles. Get hit once and your shoes get dirty—use the Clean button to fix them (only once per game!). Get hit again after using Clean and it's game over.

## How to Play

- **← →** Move the stick figure left or right (use the on-screen buttons or arrow keys)
- **Avoid** the falling dirt piles
- If you get hit, tap **Clean** to restore your shoes (one use only!)
- **Survive** as long as you can—the timer tracks your score

## Running the Game

Open `index.html` in a web browser. For best results on mobile:

1. **Local development**: Run a simple HTTP server from this folder:
   ```bash
   python3 -m http.server 8000
   ```
   Then visit `http://localhost:8000` (or your machine's IP for mobile testing)

2. **Direct file**: You can also open `index.html` directly, but some browsers may block loading images from the file system.

## Files

- `index.html` - The complete game (HTML, CSS, and JavaScript)
- `assets/` - Stick figure images (clean, dirty) and dirt pile sprite
