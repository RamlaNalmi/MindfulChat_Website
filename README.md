# MindfulChat Website Project Structure

## 📁 Directory Organization

This project follows a clean, organized structure with separated concerns for maintainability.

```
MindfulChat_Website/
├── index.html              # Main HTML file (structure only)
├── css/
│   └── style.css          # All styling separated from HTML
├── js/                    # JavaScript files (for future functionality)
├── assets/
│   ├── images/            # General images and graphics
│   ├── members/           # Team member profile photos
│   └── slides/            # Presentation slides and related assets
└── README.md              # This file
```

## 📄 File Descriptions

### `index.html`
- Contains the semantic HTML structure
- Links to external CSS file
- Clean separation of content and presentation

### `css/style.css`
- All CSS styles extracted from HTML
- Includes responsive design
- Contains animations and transitions
- Uses CSS custom properties for theming

### `assets/` Directory Structure

#### `assets/images/`
- Place general website images here
- Icons, logos, background images
- Any graphics not related to team or presentations

#### `assets/members/`
- **Team member photos should go here**
- Recommended naming: `member-name.jpg` or `member-name.png`
- Use consistent image sizes for team profiles
- Recommended size: 200x200px for profile photos

#### `assets/slides/`
- **Presentation slides should go here**
- PowerPoint files, PDFs, or slide images
- Recommended naming: `presentation-title.pdf` or `slide-01.jpg`
- Organize by presentation date or topic if multiple

### `js/` Directory
- Ready for future JavaScript functionality
- Interactive features, form handling, animations
- Currently empty but prepared for expansion

## 🚀 Getting Started

1. **Adding Team Member Photos:**
   - Place images in `assets/members/`
   - Update HTML to reference: `src="assets/members/member-name.jpg"`
   - Use consistent formats (JPG/PNG recommended)

2. **Adding Presentation Slides:**
   - Place files in `assets/slides/`
   - Update HTML links to reference: `href="assets/slides/presentation.pdf"`
   - Supported formats: PDF, PPT, PPTX, or slide images

3. **Modifying Styles:**
   - Edit `css/style.css` for any styling changes
   - HTML remains clean and focused on structure

## 🎨 Benefits of This Structure

- **Maintainability:** Easy to locate and update specific file types
- **Performance:** CSS is cached separately from HTML
- **Collaboration:** Team members can work on different asset types simultaneously
- **Scalability:** Easy to add new features without cluttering main files
- **Organization:** Clear separation of concerns (HTML structure, CSS styling, assets)

## 📝 Notes

- All asset paths in HTML should be relative to the root directory
- Keep image files optimized for web performance
- Use descriptive filenames for better organization
- Consider adding alt text for accessibility when adding images
