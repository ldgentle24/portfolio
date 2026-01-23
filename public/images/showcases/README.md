# Image Showcase Directory

## Where to Put Your Images

Place your project showcase images in this directory structure:

```
public/images/showcases/
├── film-discovery/          ← Your film-discovery project images go here
│   ├── hero-ui.jpg
│   ├── search-results.jpg
│   ├── filtering.jpg
│   ├── trending.jpg
│   ├── trailer-integration.jpg
│   └── tv-show-detail.jpg
│
├── future-project-1/        ← Create new folders for future projects
│   ├── image-1.jpg
│   └── image-2.jpg
│
└── future-project-2/
    └── ...
```

## Current Project: Film Discovery

**Put your 6 images in:** `public/images/showcases/film-discovery/`

**Required image filenames** (as defined in JSON):
1. `hero-ui.jpg` - Movie detail page UI
2. `search-results.jpg` - Search/discovery grid
3. `filtering.jpg` - Advanced filtering interface
4. `trending.jpg` - Trending/recommendation section
5. `trailer-integration.jpg` - Trailer/media integration
6. `tv-show-detail.jpg` - TV show detail page

## Image Requirements

- **Aspect Ratio:** 16:9 (consistent across all images)
- **Format:** JPG (recommended) or PNG
- **Size:** Optimized for web (< 500KB per image)
- **Dimensions:** Recommended width: 1600px (will scale responsively)

## How to Add Images

1. **Export/screenshot** your project images
2. **Resize** to 16:9 aspect ratio (e.g., 1600x900px)
3. **Compress** using tools like TinyPNG or ImageOptim
4. **Rename** to match the filenames in the JSON file
5. **Copy** to `public/images/showcases/film-discovery/`

## Adding a New Project Showcase

1. Create a new folder: `public/images/showcases/your-project-name/`
2. Add your images to that folder
3. Create JSON file: `src/data/showcases/your-project-name.json`
4. Update your project page to use the ImageGallery component

## Testing

After adding images, the gallery will automatically display them at:
http://localhost:4321/work/film-discovery

No code changes needed - just add the images!
