# Interactive Particle Animation

A beautiful, physics-based particle animation with mouse interaction controls. Particles oscillate and connect with each other, creating a mesmerizing network effect.

![Particle Animation Demo](https://media.giphy.com/media/your-demo-gif-url-here/giphy.gif) *(Replace with your actual GIF/Video)*

## Features
- Dynamic particle system with physics
- Mouse interaction (particles react to cursor)
- Adjustable particle count
- Connection lines between nearby particles
- Performance stats (FPS counter)
- Responsive design (resizes with window)

## How to Use
1. Clone this repository
2. Open `index.html` in your browser
3. Interact with the particles using your mouse
4. Use the controls to adjust settings

## Controls
- **Start Animation**: Begins the particle simulation
- **Pause**: Stops the animation
- **Reset**: Creates new particles
- **Particle Count Slider**: Adjusts number of particles (10-500)

## Code Preview
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Particle Animation</title>
    <style>
        body { margin: 0; overflow: hidden; background: linear-gradient(135deg, #1a1a2e, #16213e); }
        canvas { display: block; }
    </style>
</head>
<body>
    <canvas id="animatedCanvas"></canvas>
    <script>
        // [Your JavaScript code here]
    </script>
</body>
</html>
