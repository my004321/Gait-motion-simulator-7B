# Pelvic Gait Simulator

An interactive 3D biomechanics visualization tool for understanding pelvic and lower limb kinematics during human gait.

## Live Demo

**[Open the simulator →](https://my004321.github.io/Gait-motion-simulator-7B/)**

## Features

- **Three synchronized views** of gait mechanics:
  - **Pelvic Hike** (Frontal/Coronal Plane) - shows lateral pelvic movement
  - **Pelvic Tilt** (Transverse/Superior Plane) - displays anterior/posterior pelvic rotation
  - **Thigh Swing** (Sagittal Plane) - visualizes bilateral leg swing symmetry

- **Interactive controls**:
  - Walk/Run mode presets with biomechanically accurate parameter adjustments
  - Cadence control (20–200 RPM)
  - Independent amplitude sliders for pelvic hike, tilt, and leg swing
  - Real-time data readouts with phase indicators
  - Live kinematic graphs showing motion history

- **Mechanical simulation**:
  - Cam mechanism (pelvic hike)
  - Crank-slider mechanism (pelvic tilt)
  - Wheel mechanism (thigh swing)

## How to Use

1. Open the [live demo](https://my004321.github.io/Gait-motion-simulator-7B/)
2. Select **Walk** or **Run** mode — parameters adjust automatically
3. Use sliders to fine-tune:
   - **RPM (steps/min)**: Adjust gait speed
   - **Hike Amplitude**: Control lateral pelvic height difference
   - **Tilt Amplitude**: Adjust anterior/posterior pelvic rotation
   - **Swing Amplitude**: Modify leg swing range
4. Observe the three canvas views and real-time graphs to understand motion patterns

## Technical Details

- **Built with**: Vanilla JavaScript, HTML5 Canvas, CSS3
- **Animation**: `requestAnimationFrame` for smooth 60 FPS rendering
- **Responsive**: Automatically scales to viewport dimensions
- **No dependencies**: Runs entirely in the browser

## Files

- `index.html` - Full single-file application (GitHub Pages)
- `Gait Motion Simulator 7B.html` - Source file with inline styles and scripts

## License

This project is open source and available for educational and research purposes.