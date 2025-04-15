# Website Assets Structure

This directory contains all the assets used throughout the website, organized by section.

## Directory Structure

- `/assets/home`: Assets used on the home page
- `/assets/snipps`: Assets for the Snipps section
  - `/assets/snipps/avatars`: User profile avatars
  - `/assets/snipps/videos`: Video content for Snipps
  - `/assets/snipps/thumbnails`: Thumbnails for videos (used as poster images)
- `/assets/messages`: Assets for the messaging section
- `/assets/community`: Assets for the community section
- `/assets/anime`: Assets related to anime content
- `/assets/music`: Assets for the music section
- `/assets/movies`: Assets for the movies section
- `/assets/common`: Shared assets used across multiple sections

## Usage

To use these assets in components, use the relative path from the public directory:

```jsx
// Example usage in a component
<img src="/assets/home/hero-image.jpg" alt="Hero" />
```

## Asset Naming Conventions

1. Use lowercase for all filenames
2. Use hyphens to separate words
3. Include a number suffix for repeated assets (e.g., avatar1.jpg, avatar2.jpg)
4. Use descriptive names that indicate the content

## Required Formats

- Images: Prefer JPG for photos, PNG for graphics with transparency, WebP for better compression
- Videos: MP4 format with H.264 encoding for broad compatibility
- Audio: MP3 format for audio clips

## Recommendations

- Optimize all images and videos before adding them to the repository
- Keep file sizes small to improve page load times
- Use appropriate dimensions for the intended display size 