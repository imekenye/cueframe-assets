# cueframe-assets

Runtime assets that Cueframe DJ downloads on first use. Nothing here is app code.

Each asset is a GitHub Release. The app pins every asset's SHA-256 and uses a file only
after it matches.

| Release | Asset | What |
|---|---|---|
| `mlx-0.32.4` | `mlx-runtime-0.32.4-macos-arm64.zip` | Apple's MLX 0.32.4 and its C API mlx-c 0.8.0 (both MIT), which Cueframe DJ uses to run stem separation on Apple silicon GPUs. Licence texts and provenance are inside the archive (`README.md`, `LICENSE-MLX`, `LICENSE-mlx-c`). |
