## Custom LWC Slide Show

This custom Lightning Web Component (LWC) creates a slide show in Salesforce, improving the standard Salesforce carousel by making it more flexible, dynamic, and fast.

### Key Benefits:
- **Dynamic Image Loading**: Uses `Promise.all` to check if all images are loaded before starting the slide show, ensuring that images load correctly.
- **Better User Control**: Includes next/previous buttons and navigation dots for easier control.
- **Manual Pause**: You can stop the slide show and navigate manually.
- **Customizable**: Image names can be easily updated through Salesforce Custom Labels, no need to change the code.
- **Performance**: Ensures that the slideshow starts only when all images are fully loaded.
- **Easy to Customize**: You can easily change the images and settings to fit your needs.

### Features:
- Next and previous navigation buttons for slides.
- Navigation dots to show the current slide.
- Uses Salesforce static resources to load images.
- Customize the list of images through Salesforce Custom Labels.
- Ensures all images are loaded before starting the slideshow.
- Pause the slide show when you manually interact with it.

This component is great for showing image galleries, product showcases, or custom carousels on Salesforce Lightning pages.

---

### How to Use:
1. Upload your images as a ZIP file under Salesforce static resources (under 5 MB).
2. Use the Custom Label `Images_Names` to store a list of image filenames.
3. Add this component to your Lightning Page to display the slide show.
