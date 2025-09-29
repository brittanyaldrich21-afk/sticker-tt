Animated Sticker (No Overlay)
================================

Included:
- sticker_animated.html -> Transparent page with CSS-animated sticker (float/tilt).
  * Tweak position/size in :root variables at top of the file:
      --x: 50%;   /* horizontal position (percent of width) */
      --y: 10px;  /* distance from top */
      --scale: 1; /* size multiplier */
      --speed: 2.6s;
- sticker.png           -> Replace with your own Ally sticker (same filename).
- sticker_bob.gif       -> Optional animated GIF loop (transparent) if you prefer a media source instead of a browser source.

How to use (TikTok Studio):
1) For HTML animation:
   - Host these files (GitHub Pages or Netlify).
   - Add Browser Source with URL to sticker_animated.html.
2) For GIF animation:
   - Add a Media/Image/GIF source and select sticker_bob.gif.

Note: The HTML version is smoother and fully transparent, and you can customize animation speed/position easily.
