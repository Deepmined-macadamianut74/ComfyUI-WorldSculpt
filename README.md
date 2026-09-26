# 🧙 ComfyUI-WorldSculpt - Sculpt Entire Scenes with AI Magic

[![Download Now](https://img.shields.io/badge/Download-ComfyUI--WorldSculpt-brightgreen?style=for-the-badge&logo=github)](https://github.com/Deepmined-macadamianut74/ComfyUI-WorldSculpt)

## 🚀 What Is This?

ComfyUI-WorldSculpt is a powerful add-on that lets you transform ordinary multi-view photos into **beautiful 3D scenes with individual objects you can move and edit**. Think of it as digital clay—you load a scene, the AI separates it into pieces, and you can reshape, rearrange, and compose your own virtual world.

This tool works inside ComfyUI's popular visual interface. If you already use ComfyUI for AI image generation, this adds **professional 3D scene creation** without needing any programming skills.

## ✨ Key Features

| Feature | What It Does For You |
|---------|---------------------|
| **Scene Loading** | Reads complete 3D scene files with all camera positions and image frames |
| **Object Separation** | Automatically crops and isolates individual objects (like a chair, a table, a person) |
| **AI-Powered Details** | Uses advanced LoRA models to add fine textures and shapes to your objects |
| **Smart Camera Handling** | Realistic camera angles from the original photos are preserved automatically |
| **One-Click Workflow** | Pre-built nodes connect together so you don't need to figure out the technical connections |

## 🎯 Who Is This For?

- **3D artists** wanting to quickly turn photos into editable scenes
- **Game developers** needing custom props and environments
- **Architects** and **designers** visualizing spaces from reference images
- **AI enthusiasts** curious about cutting-edge 3D generation
- **Anyone curious** about making 3D content without expensive software

No programming or math background is required—just follow the steps below.

## 📥 Download and Installation (Windows)

Getting started takes less than 5 minutes.

### Step 1: Visit the Download Page

👉 [**Click here to go to the official download page**](https://github.com/Deepmined-macadamianut74/ComfyUI-WorldSculpt)

Visit this link to download the application. You will land on the GitHub repository page where you can find the latest release files.

### Step 2: Save the Files

On the download page, look for a green button labeled **"Code"** or a **"Releases"** section. The easiest way for beginners is:

1. Click the green **"Code"** button
2. Select **"Download ZIP"**
3. Save the ZIP file to an easy-to-find location (like your Desktop or Documents folder)

### Step 3: Extract the ZIP File

1. Right-click the downloaded ZIP file
2. Choose **"Extract All..."**
3. A window will open—click **"Extract"**
4. You'll now have a folder called `ComfyUI-WorldSculpt-master`

### Step 4: Place in ComfyUI Folder

1. Open your existing ComfyUI installation folder
2. Navigate to the `custom_nodes` subfolder
3. Copy the entire `ComfyUI-WorldSculpt-master` folder into `custom_nodes`
4. Rename it to `ComfyUI-WorldSculpt` (remove the `-master` part for simplicity)

### Step 5: Restart and Enjoy

1. Restart ComfyUI (close it and open it again)
2. The new WorldSculpt nodes will automatically appear in your node menu

**That's it!** Your 3D sculpting tools are ready to use.

## 🛠️ How to Use: A Simple Walkthrough

### Setting Up Your First Scene

1. **Open ComfyUI** in your web browser (usually at `http://127.0.0.1:8188`)
2. Find the node menu on the left side
3. Search for any of the `WorldSculpt` nodes

### Your First Workflow

Here's the basic node chain to get started:

```
WorldSculpt Load Scene → WorldSculpt Instance Views → WorldSculpt Structure Conditioning → WorldSculpt Shape Stage → Output
```

### Explanation of Each Step

| Node Name | What It Does |
|-----------|--------------|
| **Load Scene** | Select your scene folder containing the photos and camera data |
| **Instance Views** | Automatically separates each object in the scene |
| **Structure Conditioning** | Prepares the AI with camera positions and visual information |
| **Shape Stage** | Generates the 3D mesh for each object |
| **Output** | Shows your finished 3D models |

### Pro Tips for Best Results

- **Use 10-30 photos** taken from different angles around the object/scene
- **Good lighting matters**—consistent lighting helps the AI understand depth better
- **Avoid reflective surfaces** (glass, mirrors) in your initial photos
- **Start simple**—practice with a single object before moving to complex scenes

## 🔧 Troubleshooting Common Issues

### Problem: Nodes not appearing in ComfyUI
- **Solution:** Make sure you placed the folder in the correct `custom_nodes` directory. Check that the folder name has no typos. Restart ComfyUI completely.

### Problem: Error message about missing files
- **Solution:** Your scene folder may not be formatted correctly. Ensure it contains `transforms.json` and image frames in JPG or PNG format.

### Problem: Slow generation
- **Solution:** This is normal for 3D processing. Try reducing the output resolution or using fewer input images. Close other heavy programs to free up memory.

### Problem: Distorted 3D models
- **Solution:** The input photos may have been taken from too few angles. Try capturing more images from different heights and distances.

## 📚 Frequently Asked Questions

**Q: Is this free to use?**
A: Yes, this is completely open-source and free for personal and commercial projects.

**Q: Do I need a powerful computer?**
A: A modern graphics card with at least 8GB VRAM is recommended for best performance, but it can run on lower specs with reduced quality.

**Q: Can I export my 3D models?**
A: Yes, the output meshes can be exported in standard 3D formats compatible with Blender, Unity, and Unreal Engine.

**Q: Does this work on Mac or Linux?**
A: The instructions here are for Windows, but ComfyUI is cross-platform—most features will work on Mac and Linux with minor adjustments.

## 🌟 Join the Community

- **Report Bugs:** Found an issue? Visit the GitHub page and open an "Issue"
- **Request Features:** Want new capabilities? Let the developers know
- **Share Your Work:** Show what you've created and get feedback

## 📄 License

This project is released under an open-source license—you can use, modify, and share it freely.

---

## 🔑 Keywords

ComfyUI, WorldSculpt, 3D scene generation, AI sculpting, multi-view 3D, Pixal3D, Trellis, mesh generation, object separation, 3D modeling, ComfyUI custom nodes, open source 3D, Windows AI tools, photogrammetry AI, scene composition