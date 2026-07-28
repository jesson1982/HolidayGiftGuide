# Image Replacement Guide - Replace Placeholder Images with Real Images

This guide will help you replace the placeholder images with real images from Unsplash or Pexels.

## Current Status
✅ All images are now using placeholder service (via.placeholder.com) for immediate display
✅ Images will show correctly in the frontend with proper sizing and alt text
✅ Layout and design are preserved and functional

## How to Replace Placeholder Images

### Step 1: Download Real Images
1. Visit https://unsplash.com or https://www.pexels.com
2. Search for the image topic (see mapping below)
3. Download the image at appropriate size:
   - Homepage hero images: 1200x600px
   - Product images: 600x400px  
   - Blog content images: 800x600px
   - Blog card images: 400x200px

### Step 2: Replace Image Files
For each placeholder image, replace the URL in the HTML file with your actual image:

**Example replacement:**
```html
<!-- Before (placeholder) -->
<img src="https://via.placeholder.com/1200x600/2c3e50/ffffff?text=Custom+Fleece+Blanket" alt="...">

<!-- After (real image) -->
<img src="../assets/images/premium-fleece-blanket-main.jpg" alt="...">
```

### Step 3: File Naming Convention
Follow the naming convention in IMAGE_DOWNLOAD_GUIDE.md for consistency:
- Use descriptive, lowercase filenames
- Use hyphens instead of spaces
- Include dimensions when helpful (e.g., blanket-1200x600.jpg)

## Image Mapping

### Homepage Images
1. **blanket-hero.jpg** → `assets/images/blanket-hero.jpg`
2. **pillow-hero.jpg** → `assets/images/pillow-hero.jpg`  
3. **tshirt-hero.jpg** → `assets/images/tshirt-hero.jpg`
4. **blog1.jpg** → `assets/images/blog1.jpg`
5. **blog2.jpg** → `assets/images/blog2.jpg`
6. **blog3.jpg** → `assets/images/blog3.jpg`

### Product Page Images
7. **premium-fleece-blanket-main.jpg** → `assets/images/premium-fleece-blanket-main.jpg`
8. **photo-pillow-main.jpg** → `assets/images/photo-pillow-main.jpg`
9. **graphic-tshirt-main.jpg** → `assets/images/graphic-tshirt-main.jpg`
10. **weighted-blanket-main.jpg** → `assets/images/weighted-blanket-main.jpg`
11. **throw-pillow-cover-main.jpg** → `assets/images/throw-pillow-cover-main.jpg`

### Blog Article Images
12. **blog-featured-blanket.jpg** → `assets/images/blog-featured-blanket.jpg`
13. **blanket-gift-ideas.jpg** → `assets/images/blanket-gift-ideas.jpg`
14. **fleece-blanket-type.jpg** → `assets/images/fleece-blanket-type.jpg`
15. **woven-blanket-texture.jpg** → `assets/images/woven-blanket-texture.jpg`
16. **pillow-design-hero.jpg** → `assets/images/pillow-design-hero.jpg`
17. **photo-pillow-collage.jpg** → `assets/images/photo-pillow-collage.jpg`
18. **typography-pillow.jpg** → `assets/images/typography-pillow.jpg`
19. **botanical-pillow.jpg** → `assets/images/botanical-pillow.jpg`
20. **tshirt-trends-hero.jpg** → `assets/images/tshirt-trends-hero.jpg`
21. **90s-y2k-tshirt-design.jpg** → `assets/images/90s-y2k-tshirt-design.jpg`
22. **sustainable-tshirt-design.jpg** → `assets/images/sustainable-tshirt-design.jpg`
23. **environmental-message-tshirt.jpg** → `assets/images/environmental-message-tshirt.jpg`
24. **pod-business-hero.jpg** → `assets/images/pod-business-hero.jpg`
25. **pod-business-model.jpg** → `assets/images/pod-business-model.jpg`
26. **pod-platforms-comparison.jpg** → `assets/images/pod-platforms-comparison.jpg`
27. **marketplace-platforms.jpg** → `assets/images/marketplace-platforms.jpg`

## Quick Batch Replacement Script

You can use find and replace in your code editor to replace all placeholder URLs at once:

**Find pattern:**
```
https://via.placeholder.com/
```

**Replace pattern structure:**
- Keep the size dimensions
- Replace with `../assets/images/[filename]`
- Keep the alt text unchanged

## Optimization Tips for Real Images

1. **Compression**: Compress images to <200KB each
2. **Format**: Use WebP format when possible
3. **Naming**: Use descriptive filenames for SEO
4. **Alt Text**: Ensure all images have descriptive alt text
5. **Lazy Loading**: Keep `loading="lazy"` attribute

## Testing After Replacement

1. Clear browser cache
2. Refresh the page
3. Check each image loads correctly
4. Test on mobile devices
5. Check image alt text displays correctly

## Current Status
✅ All placeholder images are functional and properly sized
✅ Layout and design remain intact
✅ Alt text and accessibility preserved
✅ Responsive design maintained
✅ Ready for immediate preview

The site will work perfectly with placeholder images. You can replace them with real images gradually as you download them from Unsplash or Pexels.