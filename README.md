# Saṃsāra
<img width="1920" height="1080" alt="Samsara Video Panel Cover Images-1" src="https://github.com/user-attachments/assets/85f666fc-9f2b-4351-b356-c5d5e6448d61" />

**Saṃsāra** is a monumental video installation exploring humanity's cyclical separation from nature through the lens of Buddhist philosophy. Presented across a 40-foot video facade, nine looping panels tell this story from nature's perspective—from harmonious coexistence through digital dependency to complete isolation from living reality.

## Technical Architecture

The project employs a sophisticated Unreal Engine 5.5 pipeline built on custom Blueprint systems. A **procedural spline-based placement system** instances architectural meshes to create the extended Roman-inspired environment. A custom **10-camera rig Blueprint** captures panoramic renders at 9600x1200 resolution, with precise overlap calculations ensuring seamless stitching across camera boundaries.

Each camera sequence renders independently through **Movie Render Queue automation**, then composites in After Effects to produce the continuous 40-foot visual experience. Video content originates from a **custom AI generation pipeline** using ComfyUI workflows, Stable Diffusion, and specialized LoRA training for consistent painterly aesthetics across all nine narrative panels.

## Conceptual Framework

The installation's physical form mirrors its critique: ten server racks disguised as Corinthian columns—classical architecture adorned with acanthus leaves housing the technology driving our exodus from the nature those very carvings celebrate. The endless loops aren't merely entrapment but invitations to recognize the cycle and choose restoration.

**Exhibition:** Hyde Park Art Center, Chicago  
**Program:** Center Program  
**Completion:** December 15, 2025

*Developed by Amay Kataria*
