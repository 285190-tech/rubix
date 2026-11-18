# CubeLab

Static 3×3 cube practice app with a draggable model, 20-move random scrambles, a worker-based two-phase solver, and a stopwatch with browser-local history. No accounts, backend, CDN, or API keys.

## Local preview

Run `python3 -m http.server 8080` here and open http://localhost:8080.

## Cloudflare Pages

Connect this repository to a Pages project. Select the branch containing the app, choose **None** as the framework preset, leave the build command empty, and set the output directory to `/` (repository root). Deploy. Alternatively, upload the static site files using Pages Direct Upload. No environment variables are required.

Cube logic: cubejs (license in vendor/). Fonts: Space Grotesk and Space Mono (licenses in fonts/). Icons: Lucide (see icons-LICENSE).

## Interactive studio

Use the face buttons to turn the model (Shift-click for an inverse turn). The solution player supports single steps, backward steps, autoplay and replay. The Learn sidebar includes seven beginner stages with prepared practice cases, selected speedcubing algorithms and a six-face notation explorer. Reduced-motion preferences shorten turn transitions. Session history includes best and mean times.
