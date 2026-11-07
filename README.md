# CorgiMind Resources

Workflows, prompts, code and templates that accompany CorgiMind videos. Resources are organized by episode.

## Episode index

### One Image to AI Video: Wan 2.2 in ComfyUI

A controlled 12-versus-20-step image-to-video experiment using Wan 2.2 TI2V-5B.

**Status: GUI import and execution are UNVERIFIED.** The prepared workflows passed static JSON, graph-link and parameter checks against the recorded API experiment. They have not been imported or run through the ComfyUI GUI. Treat them as starting points, not verified one-click presets.

- [Download the complete viewer package (ZIP)](episodes/one-image-to-ai-video/CorgiMind-Viewer-Workflow-v1.zip)
- [Start here](episodes/one-image-to-ai-video/START-HERE.txt)
- [12-step workflow](episodes/one-image-to-ai-video/workflows/corgimind-12-step-gui.json) · [Raw JSON](https://raw.githubusercontent.com/AsafSaar/corgimind-resources/main/episodes/one-image-to-ai-video/workflows/corgimind-12-step-gui.json)
- [20-step workflow](episodes/one-image-to-ai-video/workflows/corgimind-20-step-gui.json) · [Raw JSON](https://raw.githubusercontent.com/AsafSaar/corgimind-resources/main/episodes/one-image-to-ai-video/workflows/corgimind-20-step-gui.json)
- [Prompts and adaptation tips](episodes/one-image-to-ai-video/PROMPTS.txt)
- [Models and dependencies](episodes/one-image-to-ai-video/MODELS-AND-DEPENDENCIES.txt)
- [Export PNG frames to MP4](episodes/one-image-to-ai-video/EXPORT-FRAMES.txt)
- [Content checksums](episodes/one-image-to-ai-video/SHA256SUMS.txt)

Supply an image you own or have permission to use, install the required models, and adapt the scene-specific prompt. Both workflows save PNG frames only, with no MP4 or audio generation. The settings are 1024 × 576, 121 frames, fixed seed 11022026, and 12 or 20 sampling steps. Exporting at 24 fps yields about 5.04 seconds.

The original source illustration, finished footage, model weights, private production records, raw API logs, credentials and payment records are not included. The RTX 5080 16GB used in the recorded experiment is not a guaranteed minimum requirement.

### Package integrity

Viewer package v1, November 7, 2026. The ZIP and extracted files are the same sanitized package.

ZIP SHA-256:

`cc403bfbdaf2978991b47f7cf893b3f391f0aa9baee1098b1cacf3ff56c4e0df`

No repository license has been selected. No source-art or model rights are granted here. Follow the software and model licenses linked in the dependency instructions.
