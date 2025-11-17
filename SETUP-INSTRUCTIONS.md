# Setup Instructions for Jason Dong's Personal Website

## Adding Your Photo (About Page)

1. Save your photo as `jason-photo.jpg` (or any image format like .png, .jpeg)
2. Place it in the `images/` folder
3. If you use a different filename, update line 13 in `content1.html`:
   ```html
   <a href="#" class="image featured"><img src="images/YOUR-FILENAME.jpg" alt="Jason Dong" /></a>
   ```

## Adding Your Name Pronunciation Audio (About Page)

1. Record your name pronunciation and save it as an MP3 file
2. Create an `audio/` folder in your website directory (if it doesn't exist)
3. Save your audio file as `name-pronunciation.mp3` in the `audio/` folder
4. If you use a different filename, update line 21 in `content1.html`:
   ```html
   <source src="audio/YOUR-FILENAME.mp3" type="audio/mpeg">
   ```

## Adding Timeline Images (Experience Page)

For the career timeline on content2.html, you'll need to add these images to the `images/` folder:

1. **timeline.png** - The main timeline graphic showing your career progression (2023-Future)
2. **slide-artisan.png** - Artisan Partners slide image
3. **slide-hashicorp.png** - HashiCorp slide image  
4. **slide-meta.png** - Meta slide image

Save your slide images with these exact names in the `images/` folder, or update the image paths in `content2.html` if you use different filenames.

## Website Structure

Your website now has:
- **index.html** - Home page with blog-style posts
- **content1.html** - About page with your bio, photo, and name pronunciation
- **content2.html** - Interactive career timeline with experience slides

## Navigation

All pages have consistent navigation:
- Home
- About
- Multimodal Content (Career Timeline)

## Customizing the Timeline (content2.html)

The career timeline page includes:
- A main timeline graphic showing your progression from 2023 to Future
- Individual experience slides for each company (Artisan Partners, HashiCorp, Meta)
- Detailed descriptions of your work at each company

The Meta slide has a purple border to highlight it as the current/featured position.

## Adding Multimodal Content to content2.html

You can add various types of content:

### YouTube Videos
```html
<iframe width="100%" height="500" src="https://www.youtube.com/embed/VIDEO_ID" frameborder="0" allowfullscreen></iframe>
```

### Vimeo Videos
```html
<iframe src="https://player.vimeo.com/video/VIDEO_ID" width="100%" height="500" frameborder="0" allowfullscreen></iframe>
```

### Local Videos
```html
<video width="100%" controls>
  <source src="videos/your-video.mp4" type="video/mp4">
</video>
```

### Audio Files
```html
<audio controls style="width: 100%;">
  <source src="audio/your-audio.mp3" type="audio/mpeg">
</audio>
```

### Google Slides
```html
<iframe src="https://docs.google.com/presentation/d/PRESENTATION_ID/embed" width="100%" height="500" frameborder="0"></iframe>
```

### PDFs
```html
<embed src="documents/your-file.pdf" type="application/pdf" width="100%" height="600px" />
```

## Next Steps

1. **Add your photo** to the `images/` folder as `jason-photo.jpg`
2. **Create the `audio/` folder** and add your name pronunciation recording as `name-pronunciation.mp3`
3. **Add timeline images** to the `images/` folder:
   - `timeline.png` - Main career timeline graphic
   - `slide-artisan.png` - Artisan Partners experience slide
   - `slide-hashicorp.png` - HashiCorp experience slide
   - `slide-meta.png` - Meta experience slide
4. Customize the home page (`index.html`) with your own posts/content
5. Update social media links in the footer of all pages

Enjoy your new website!
