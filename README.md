# 🚀 Awesome Hyps

A curated collection of essential [Hyperfy Apps](https://hyperfy.io) that world hosters can install natively in their worlds. These hyps provide fundamental building blocks for creating immersive virtual experiences.

## 📦 Collections

### 🎯 Default Collection
The essential starter pack containing core hyps every world should have:

- **🎬 Geoff📹** - Advanced video player with spatial audio
- **🖼️ Image** - Display images with customizable frames
- **🎨 Model** - 3D model loader and viewer
- **📍 Place🌀** - Spatial anchoring and positioning
- **🌀 Portal🌀** - Local world teleportation
- **🌐 Portal🌐** - Cross-world teleportation
- **🪑 Seat** - Interactive seating system
- **🔮 Sphere🌀** - Dynamic sphere with physics
- **🔊 Spherea** - Spatial audio sphere
- **📝 Text** - 3D text display and formatting
- **📺 Video** - Video streaming and playback

### 🎪 Specialized Collections

- **📷 Camera** - Advanced camera controls and effects
- **🚪 Portal** - Enhanced portal and teleportation systems
- **🪑 Seat** - Comprehensive seating solutions
- **🔊 Spherea** - Advanced spatial audio experiences

## 🛠️ Installation

### For World Hosters

1. **Quick Install - Default Collection**
   ```bash
   # Copy the entire default collection to your world's apps directory
   cp -r awesome-hyps/default/* /path/to/your/world/apps/
   ```

2. **Selective Install**
   ```bash
   # Install specific hyps
   cp awesome-hyps/default/Video.hyp /path/to/your/world/apps/
   cp awesome-hyps/default/Portal🌀.hyp /path/to/your/world/apps/
   ```

3. **Specialized Collections**
   ```bash
   # Install entire specialized collections
   cp -r awesome-hyps/camera/* /path/to/your/world/apps/
   cp -r awesome-hyps/portal/* /path/to/your/world/apps/
   ```

### Using the Manifest

Each collection includes a `manifest.json` that lists all included apps:

```json
{
  "name": "Default",
  "apps": [
    "Geoff📹.hyp",
    "Image.hyp",
    "Model.hyp",
    "Place🌀.hyp",
    "Portal🌀.hyp",
    "Portal🌐.hyp",
    "Seat🪑.hyp",
    "Sphere🌀.hyp",
    "Spherea 🔊.hyp",
    "Spherea.hyp",
    "Text.hyp",
    "Video.hyp"
  ]
}
```

## 🎮 Usage

Once installed, these hyps become available in your world's app catalog. Users can:

1. **Browse Apps** - Access installed hyps through the world's app browser
2. **Place Objects** - Spawn hyp instances directly into the world
3. **Customize** - Configure hyp properties through the inspector
4. **Script Integration** - Use hyps programmatically in world scripts

## 🔧 World Configuration

### Enabling Hyps in Your World

Ensure your world configuration allows app installation:

```javascript
// In your world's config
{
  "apps": {
    "enabled": true,
    "allowUserApps": true
  }
}
```


## 🤝 Contributing

We welcome contributions to expand the awesome-hyps collection:

1. **Submit New Hyps** - Share your useful hyps with the community
2. **Improve Existing** - Enhance current hyps with new features
3. **Create Collections** - Organize thematic hyp collections
4. **Documentation** - Help improve guides and examples

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🌟 Community

- **Discord** - Join the [Hyperfy Discord](https://discord.gg/hyperfy)
- **Forums** - Discuss on [Hyperfy Forums](https://forums.hyperfy.io)
- **Documentation** - Visit [Hyperfy Docs](https://docs.hyperfy.io)

---

*Curated with ❤️ for the Hyperfy community*
