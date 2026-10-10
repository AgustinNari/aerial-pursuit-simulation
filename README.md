# Aerial Pursuit Simulation

Interactive simulation of an aircraft–missile pursuit scenario developed collaboratively.

The application combines numerical simulation with interactive controls and visual representations of trajectories, distances, and system behavior.

## Screenshots

The screenshots show the tactical simulation workspace, an interception scenario, distance analysis, an alternative light-themed 2D view, and mathematical foundations illustrated with equations and step-by-step explanations. Select an image to view it at full resolution.

<table>
  <tr>
    <th colspan="2">Tactical Simulation</th>
  </tr>
  <tr>
    <td colspan="2" align="center"><a href="docs/screenshots/tactical-simulation.webp"><img src="docs/screenshots/tactical-simulation.webp" alt="Tactical simulation with configuration controls and synchronized 2D, 3D, and distance visualizations" width="860"></a></td>
  </tr>
  <tr>
    <th>Interception Result</th>
    <th>Distance Analysis</th>
  </tr>
  <tr>
    <td align="center"><a href="docs/screenshots/interception-result.webp"><img src="docs/screenshots/interception-result.webp" alt="Aircraft and missile paths at the interception point" width="420"></a></td>
    <td align="center"><a href="docs/screenshots/distance-analysis.webp"><img src="docs/screenshots/distance-analysis.webp" alt="Distance-versus-time plot with minimum range and interception indicators" width="420"></a></td>
  </tr>
  <tr>
    <th>Light Theme / 2D Trajectories</th>
    <th>Mathematical Theory & Equations</th>
  </tr>
  <tr>
    <td align="center"><a href="docs/screenshots/light-theme-2d.webp"><img src="docs/screenshots/light-theme-2d.webp" alt="Expanded 2D aircraft and missile trajectory plot in the light theme" width="420"></a></td>
    <td align="center"><a href="docs/screenshots/theory-topics.webp"><img src="docs/screenshots/theory-topics.webp" alt="Mathematical theory section showing vector equations, explanations, and step-by-step procedures" width="420"></a></td>
  </tr>
</table>

## Tech Stack

- React
- TypeScript
- Vite
- Three.js
- React Three Fiber
- Plotly
- KaTeX
- Vitest

## Features

- Aircraft and missile simulation
- Pursuit-guidance calculations
- Numerical integration
- Configurable maneuvers
- 2D trajectory visualization
- 3D trajectory visualization
- Distance analysis
- Mathematical formulas and theory
- Simulation playback controls
- Automated tests for numerical logic

## Running Locally

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Build the application:

```bash
npm run build
```

Run tests:

```bash
npm test
```

## Documentation

Supporting data contracts and example simulation results are available under docs/.

```text
docs/
```

## Scope

The project focuses on numerical modeling, visualization, and interactive analysis of aircraft–missile pursuit scenarios.
