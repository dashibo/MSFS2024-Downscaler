# MSFS DOWNSCALER by kobi v1.0

### Reduce VRAM usage and improve performance in MSFS 2024 by batch-optimizing your textures.

**MSFS DOWNSCALER** is a dedicated utility to identify and resize high-resolution textures (8K/4K) within your add-on folders. It is specifically built for the MSFS 2024 pipeline to help users with limited VRAM or those seeking smoother frame rates.

## Core Functionality
*   **KTX2 & DDS Support**: Native processing of **KTX2** files using the MSFS 2024 SDK and **DDS** files using the Microsoft DirectXTex pipeline.
*   **Batch Downscaling**: Quickly resize hundreds of textures to 4K, 2K, or 1K resolutions.
*   **Structure Preservation**: Automatically mirrors the original folder structure and preserves all XML/JSON sidecar files.
*   **Resource Management**: Drastically reduces VRAM pressure and stuttering in heavy scenery or complex aircraft.

## Requirements
To use this tool, the following components must be installed and configured in the application settings:
*   **MSFS 2024 SDK**
*   **Microsoft DirectXTex** (texconv.exe / texdiag.exe)
*   **NVIDIA Texture Tools** (nvtt_export.exe)

## Important Note
For projects involving **DDS files**, a manual **layout.json** update (e.g., using *MSFSLayoutGenerator*) is required after processing to ensure the simulator recognizes the new file sizes and metadata.

---
**Developed by kobi (2026)**
