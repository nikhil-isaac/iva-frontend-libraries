# iva-frontend-libraries

> **Essential bookmark list** of front‑end libraries and tools for building interactive visual analytics dashboards and research prototypes (stack: **Next.js + D3.js + Sass**).

---

## Index

1. Core Framework & Tooling
2. Visualization Grammar (Low‑level)
3. High‑level React Chart Libraries
4. Layout, Diagrams & Flow‑based UIs
5. Large‑Scale & GPU‑accelerated Viz
6. Geospatial & Mapping
7. Network & Graph Analytics
8. Data Grids & Tables
9. UI Component Libraries (Sass‑friendly)
10. Animation & Interaction
11. State Management & Data Flow
12. Data Transformation in Browser
13. AI & ML in the Browser
14. Real‑Time & Streaming
15. Performance & Virtualization
16. Testing & Quality
17. Maintenance Tips
18. Contributing

---

## 1. Core Framework & Tooling

| Library                                                   | Why you need it                                                   |
| --------------------------------------------------------- | ----------------------------------------------------------------- |
| [**React**](https://github.com/facebook/react)            | Declarative component model powering most modern web apps.        |
| [**Next.js**](https://github.com/vercel/next.js)          | File‑based routing, SSR/SSG, image optimisation, API routes.      |
| [**Vite**](https://github.com/vitejs/vite)                | Ultra‑fast dev server & build tool—great for component sandboxes. |
| [**TypeScript**](https://github.com/microsoft/TypeScript) | Static typing → fewer runtime bugs + superior IDE autocompletion. |

## 2. Visualization Grammar (Low‑level)

- [**D3.js**](https://github.com/d3/d3) – Industry‑standard toolkit for scales, layouts, and DOM/SVG/Canvas manipulation.
- [**Observable Plot**](https://github.com/observablehq/plot) – Concise grammar on top of D3 for rapid EDA plots.

## 3. High‑level React Chart Libraries

- [**visx**](https://github.com/airbnb/visx) – D3 primitives as unopinionated React components.
- [**Nivo**](https://github.com/plouc/nivo) – Theme‑able SVG/Canvas charts ready to drop into dashboards.
- [**Recharts**](https://github.com/recharts/recharts) – Compositional charting with sensible defaults.

## 4. Layout, Diagrams & Flow‑based UIs

- [**React Flow**](https://github.com/xyflow/xyflow) – Drag‑and‑drop node editors (e.g., model pipelines, decision trees).
- [**React Force Graph**](https://github.com/vasturiano/react-force-graph) – 2D/3D network visualisation.
- [**Dagre‑D3**](https://github.com/dagrejs/dagre-d3) – Directed graph layouts (DAG).\
  _Tip:_ Combine with visx/React Flow for custom pipeline diagrams.

## 5. Large‑Scale & GPU‑accelerated Viz

- [**deck.gl**](https://github.com/visgl/deck.gl) – WebGL/WebGPU layer framework for massive data sets.
- [**three.js**](https://github.com/mrdoob/three.js) – General 3D engine underpinning scientific volume rendering, point clouds, etc.

## 6. Geospatial & Mapping

- [**Mapbox GL JS**](https://github.com/mapbox/mapbox-gl-js) – Vector‑tile rendering with custom styles.
- [**Protomaps GL JS**](https://github.com/protomaps/protomaps) – Open‑source alternative to Mapbox, works offline.
- [**Leaflet**](https://github.com/Leaflet/Leaflet) – Lightweight 2D mapping with huge plugin ecosystem.

## 7. Network & Graph Analytics

- [**Cytoscape.js**](https://github.com/cytoscape/cytoscape.js) – Algorithms + layouts for biological / social networks.
- [**Sigma.js**](https://github.com/jacomyal/sigma.js) – GPU‑accelerated rendering for large graphs.

## 8. Data Grids & Tables

- [**TanStack Table**](https://github.com/TanStack/table) – Headless table logic; bring your own markup/Sass.
- [**AG Grid Community**](https://github.com/ag-grid/ag-grid) – Enterprise‑grade grid (MIT for core features).
- [**MUI DataGrid**](https://github.com/mui/mui-x) – Material‑UI ecosystem; good if you already use MUI.

## 9. UI Component Libraries (Sass‑friendly)

- [**React‑Bootstrap**](https://github.com/react-bootstrap/react-bootstrap) – Bootstrap 5 components; customisable via SCSS variables.
- [**Chakra UI**](https://github.com/chakra-ui/chakra-ui) – Accessible, theme‑able components (CSS‑in‑JS but Sass‑friendly).
- [**Radix UI Primitives**](https://github.com/radix-ui/primitives) – Un‑styled components—style with your own Sass modules.
- [**Lucide React**](https://github.com/lucide-icons/lucide) – Pixel‑perfect SVG icon set.

## 10. Animation & Interaction

- [**Framer Motion**](https://github.com/framer/motion) – Declarative animations, layout transitions, gesture controls.
- [**GSAP**](https://github.com/gsap/gsap) – High‑performance timeline‑based animation for SVG/Canvas.
- [**React Spring**](https://github.com/pmndrs/react-spring) – Physics‑based animation primitives.

## 11. State Management & Data Flow

- [**Redux Toolkit**](https://github.com/reduxjs/redux-toolkit) – Opinionated, batteries‑included Redux.
- [**Zustand**](https://github.com/pmndrs/zustand) – Minimalistic global store (<1 KB gzipped).
- [**Recoil**](https://github.com/facebookexperimental/Recoil) – Fine‑grained atom/selector approach.
- [**Jotai**](https://github.com/pmndrs/jotai) – Primitive and flexible atomic store.

## 12. Data Transformation in Browser

- [**Arquero**](https://github.com/uwdata/arquero) – Data‑frame API (split‑apply‑combine) in JS.
- [**DuckDB‑Wasm**](https://github.com/duckdb/duckdb-wasm) – Analytical SQL engine compiled to WebAssembly.
- [**Apache Arrow JS**](https://github.com/apache/arrow) – Columnar in‑memory analytics format.

## 13. AI & ML in the Browser

- [**TensorFlow.js**](https://github.com/tensorflow/tfjs) – Train/run models using WebGL/WebGPU.
- [**ONNX Runtime Web**](https://github.com/microsoft/onnxruntime/tree/main/js) – Execute ONNX models client‑side.
- [**Transformers.js**](https://github.com/xenova/transformers.js) – HuggingFace transformers in pure JS.

## 14. Real‑Time & Streaming

- [**Socket.io‑client**](https://github.com/socketio/socket.io-client) – WebSocket abstraction for real‑time dashboards.
- [**RxJS**](https://github.com/ReactiveX/rxjs) – Reactive streams for complex event flows.

## 15. Performance & Virtualization

- [**react‑window**](https://github.com/bvaughn/react-window) – Virtualised lists/grids (windowing).
- [**Intersection Observer polyfill**](https://github.com/w3c/IntersectionObserver) – Lazy‑load heavy visuals when in view.

## 16. Testing & Quality

- [**Jest**](https://github.com/facebook/jest) – Unit/integration testing framework.
- [**Testing Library**](https://github.com/testing-library/react-testing-library) – Test from the user's perspective.
- [**ESLint**](https://github.com/eslint/eslint) – Lint rules for code quality + accessibility.
- [**Prettier**](https://github.com/prettier/prettier) – Opinionated code formatter.

---

## 17. Maintenance Tips

1. **Pin versions** with `npm i <pkg>@<ver>` to avoid breaking changes.
2. Enable **Dependabot** (GitHub) or **Renovate** to auto‑PR dependency upgrades.
3. Schedule a monthly `npm audit` & `npm outdated` check.
4. Document **design decisions** (why choose visx vs Nivo) in your repo wiki.

## 18. Contributing

Have a library you rely on that isn’t listed? Open a pull request:

```bash
# fork + clone
git clone https://github.com/<you>/iva-frontend-libraries.git
cd iva-frontend-libraries
# edit README.md, then commit & PR against upstream
```

_Please keep the list focused on **front‑end** libraries relevant to interactive visual analytics._

---

_Last updated: \***\*21 June 2025\*\*** — corrections & additions welcome!_
