# Dragon Cursor Animation

This project creates a visually stunning, animated "dragon tail" that follows the user's cursor as it moves across the screen. It provides a smooth, glowing effect for an immersive user experience.

---

## Features

- **Interactive Animation**: The tail dynamically follows the cursor with a smooth trailing effect.
- **Glowing Tail**: Each segment of the tail has a glowing, fiery appearance.
- **Smooth Performance**: Leveraging `requestAnimationFrame` ensures smooth and efficient animations.
- **Customizable**: Easily tweak the tail's appearance, spacing, and animation speed.

---

## Installation and Usage

### 1. Clone the Repository
```bash
git clone https://github.com/your-repository-name/dragon-cursor-animation.git
```

### 2. Open the Project
Simply open the `index.html` file in your preferred web browser:

```bash
open index.html
```

Alternatively, you can use a live server for development:

```bash
# Example using VS Code Live Server extension
right-click > Open with Live Server
```

---

## How It Works

1. **HTML Structure**:
   - The HTML file contains a single `body` element with no additional content.

2. **CSS Styling**:
   - The glowing tail segments are styled using CSS with a radial gradient and box shadows.

3. **JavaScript Logic**:
   - JavaScript tracks the mouse position and updates the tail's segments dynamically using smooth interpolation.
   - Each segment follows the position of the previous segment for a trailing effect.

4. **Animation Loop**:
   - The `requestAnimationFrame` method ensures efficient and smooth animations by updating segment positions on each frame.

---

## Customization

You can customize the following:

- **Number of Tail Segments**:
  Modify the `partCount` variable in the JavaScript to increase or decrease the number of tail parts.

- **Spacing Between Segments**:
  Adjust the `segmentSpacing` variable to control the spacing between each tail segment.

- **Tail Appearance**:
  Change the CSS in the `.dragon-tail` class to modify the colors, size, or glow effect.

---

## Future Enhancements

- Add pulsating effects to the tail using CSS animations.
- Change the tail's appearance dynamically based on cursor speed.
- Allow users to customize the animation via a settings panel.

---

## License

This project is licensed under the MIT License. Feel free to use and modify the code as you like.

---

## Demo

![Dragon Cursor Animation Demo](#)

*(Include a gif or video link here to showcase the animation.)*

---

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests to improve this project.
