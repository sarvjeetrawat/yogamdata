
# Yogam Assets

This repository contains all image and video assets for the Yogam Yoga App.

## 📁 Structure

```
yogam-assets/
├── images/
│   ├── poses/          # Yoga pose images (800x600)
│   │   └── thumbnails/ # Pose thumbnails (400x300)
│   ├── sessions/       # Session cover images (800x600)
│   └── instructors/    # Instructor photos (400x400)
├── videos/
│   ├── poses/          # Individual pose demonstration videos
│   └── sessions/       # Full session and preview videos
└── data/
    └── assets.json     # JSON file with all asset references
```

## 🔗 Usage

### Base URL
```
https://raw.githubusercontent.com/YOUR_USERNAME/yogam-assets/main
```

### Example URLs

**Image:**
```
https://raw.githubusercontent.com/YOUR_USERNAME/yogam-assets/main/images/poses/mountain_pose.jpg
```

**Video:**
```
https://raw.githubusercontent.com/YOUR_USERNAME/yogam-assets/main/videos/poses/mountain_pose.mp4
```

**JSON Data:**
```
https://raw.githubusercontent.com/YOUR_USERNAME/yogam-assets/main/data/assets.json
```

## 📐 Image Specifications

| Type | Size | Format |
|------|------|--------|
| Pose Images | 800x600 px | JPG/WebP |
| Pose Thumbnails | 400x300 px | JPG/WebP |
| Session Covers | 800x600 px | JPG/WebP |
| Instructor Photos | 400x400 px | JPG/WebP |

## 🎬 Video Specifications

| Type | Resolution | Format | Max Size |
|------|------------|--------|----------|
| Pose Videos | 720p | MP4 (H.264) | 10 MB |
| Session Previews | 720p | MP4 (H.264) | 20 MB |
| Full Sessions | 1080p | MP4 (H.264) | 500 MB |

## 📝 Naming Convention

- Use lowercase with underscores
- Pose images: `pose_name.jpg` (e.g., `mountain_pose.jpg`)
- Session images: `session_name.jpg` (e.g., `morning_sun.jpg`)
- Instructor photos: `first_last.jpg` (e.g., `maya_williams.jpg`)

## 🔄 Updating Assets

1. Add new images/videos to appropriate folders
2. Update `data/assets.json` with new asset references
3. Commit and push changes
4. Assets will be available immediately via raw.githubusercontent.com

## ⚠️ Notes

- GitHub has a 100 MB file size limit
- For larger videos, consider using GitHub LFS or external CDN
- Raw files are served with proper CORS headers

## 📄 License

All assets in this repository are proprietary to Yogam App.
Do not use without permission.
