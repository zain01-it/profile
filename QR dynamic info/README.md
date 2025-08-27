# Professional Personal Information Profile

A modern, responsive web application for displaying professional personal information, optimized for mobile devices. This application features a beautiful UI with interactive editing capabilities and includes comprehensive benefits information like SSS, Pag-IBIG, PhilHealth, and more.

## Features

### 🎯 **Core Profile Information**
- **Profile Picture**: Circular profile image with hover effects and edit capability
- **Personal Details**: Name, occupation, and professional description
- **Contact Information**: Address, phone, email, and LinkedIn profile
- **Professional Skills**: Visual skill tags with hover animations

### 🛡️ **Benefits & Insurance Section**
- **Health Insurance**: Comprehensive medical coverage details
- **SSS**: Social Security System coverage information
- **Pag-IBIG**: Home Development Mutual Fund details
- **PhilHealth**: Philippine Health Insurance Corporation coverage
- **Retirement Plan**: 401(k) with company matching
- **Paid Time Off**: Annual leave and holiday information

### ✨ **Interactive Features**
- **Edit Mode**: Click the floating edit button to enable editing
- **Inline Editing**: Click on any field to edit content
- **Profile Picture Upload**: Upload and crop profile images
- **Data Persistence**: All changes are saved to localStorage
- **Export Functionality**: Export profile data as JSON
- **Responsive Design**: Optimized for all mobile devices

### 🎨 **Modern UI/UX**
- **Mobile-First Design**: Optimized for smartphone screens
- **Smooth Animations**: Fade-in effects and hover transitions
- **Beautiful Gradients**: Modern color schemes and visual appeal
- **Touch-Friendly**: Optimized for touch interactions
- **Accessibility**: Keyboard navigation and screen reader support

## How to Use

### 1. **Viewing the Profile**
- Open `index.html` in any modern web browser
- The profile displays all information in a clean, organized layout
- Scroll through different sections to view details

### 2. **Editing Information**
- Click the **floating edit button** (✏️) in the bottom-right corner
- **Edit Mode** will be enabled (button changes to ✓)
- Click on any editable field to open the edit modal
- Make your changes and click "Save Changes"

### 3. **Updating Profile Picture**
- Enable edit mode first
- Hover over your profile picture to see the camera icon
- Click the camera icon to upload a new image
- Supported formats: JPG, PNG, GIF (max 5MB)

### 4. **Exporting Data**
- Enable edit mode to see the export button
- Click the green download button (📥) to export profile data
- Data is exported as a JSON file with timestamp

### 5. **Keyboard Shortcuts**
- `Ctrl/Cmd + E`: Toggle edit mode
- `Ctrl/Cmd + S`: Save changes (when modal is open)
- `Escape`: Close edit modal

## File Structure

```
├── index.html          # Main HTML structure
├── styles.css          # CSS styling and responsive design
├── script.js           # JavaScript functionality
└── README.md           # This documentation file
```

## Browser Compatibility

- ✅ **Chrome** (recommended)
- ✅ **Firefox**
- ✅ **Safari**
- ✅ **Edge**
- ✅ **Mobile browsers** (iOS Safari, Chrome Mobile)

## Technical Features

### **Responsive Design**
- Mobile-first approach with CSS Grid and Flexbox
- Breakpoints: 480px, 768px, and desktop
- Touch-optimized interactions

### **Performance**
- Lazy loading animations with Intersection Observer
- Debounced scroll events for smooth performance
- Optimized image handling and storage

### **Data Management**
- Local storage for data persistence
- JSON export functionality
- Form validation and error handling

### **Accessibility**
- Semantic HTML structure
- ARIA labels and roles
- Keyboard navigation support
- Screen reader compatibility

## Customization

### **Changing Colors**
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #4A90E2;
    --secondary-color: #357ABD;
    --accent-color: #FFD700;
}
```

### **Adding New Benefits**
Add new benefit cards in the HTML:
```html
<div class="benefit-card">
    <div class="benefit-icon">
        <i class="fas fa-star"></i>
    </div>
    <div class="benefit-info">
        <h3>New Benefit</h3>
        <p>Description of the new benefit</p>
    </div>
</div>
```

### **Modifying Skills**
Update the skills section in `index.html`:
```html
<div class="skill-tag">New Skill</div>
```

## Deployment

### **Local Development**
1. Download all files to a folder
2. Open `index.html` in your browser
3. No server required - works offline

### **Web Hosting**
1. Upload all files to your web server
2. Ensure the server supports HTML5 and modern JavaScript
3. Access via your domain name

### **GitHub Pages**
1. Create a new repository
2. Upload all files
3. Enable GitHub Pages in repository settings
4. Access via `https://username.github.io/repository-name`

## Troubleshooting

### **Profile Picture Not Loading**
- Check if the image file is less than 5MB
- Ensure the image format is supported (JPG, PNG, GIF)
- Try refreshing the page

### **Changes Not Saving**
- Make sure edit mode is enabled (floating button shows ✓)
- Check if localStorage is enabled in your browser
- Try clearing browser cache and cookies

### **Mobile Display Issues**
- Ensure the viewport meta tag is present
- Test on different mobile devices
- Check CSS media queries

## Contributing

Feel free to contribute to this project by:
- Reporting bugs
- Suggesting new features
- Submitting pull requests
- Improving documentation

## License

This project is open source and available under the MIT License.

## Support

For support or questions:
- Check the troubleshooting section above
- Review the code comments for implementation details
- Open an issue in the project repository

---

**Built with ❤️ using HTML5, CSS3, and Vanilla JavaScript**
