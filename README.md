# Frontend Components Library

Reusable UI components built with HTML, CSS, and vanilla JavaScript. Modern, responsive, and accessible.

## ✨ Features

- 🎨 Modern UI components
- 📱 Fully responsive
- ♿ Accessible (ARIA)
- 🚀 Zero dependencies
- 📦 Easy to integrate
- 🎯 Production-ready

## 🚀 Quick Start

```bash
git clone https://github.com/YOUR_USERNAME/frontend-components-library.git
cd frontend-components-library
```

Open `index.html` in your browser to see all components.

## 📦 Components

### Button Component
Modern buttons with multiple variants.

```html
<button class="btn btn-primary">Primary</button>
<button class="btn btn-secondary">Secondary</button>
<button class="btn btn-danger">Danger</button>
```

### Card Component
Flexible card container with header, body, and footer.

```html
<div class="card">
  <div class="card-header">Title</div>
  <div class="card-body">Content</div>
  <div class="card-footer">Footer</div>
</div>
```

### Modal Component
Accessible modal dialog with backdrop.

```html
<div class="modal" id="myModal">
  <div class="modal-content">
    <h2>Modal Title</h2>
    <p>Modal content</p>
  </div>
</div>
```

### Form Components
Styled form inputs with validation.

```html
<input type="text" class="input" placeholder="Enter text">
<select class="select">
  <option>Option 1</option>
</select>
```

## 📂 Project Structure

```
frontend-components-library/
├── README.md           # Documentation
├── index.html          # Demo page
├── styles.css          # Component styles
├── components.js       # Component logic
├── buttons.html        # Button examples
├── forms.html          # Form examples
└── .gitignore         # Git ignore
```

## 🎨 Usage

### Include in Your Project

```html
<!-- Add stylesheet -->
<link rel="stylesheet" href="styles.css">

<!-- Add JavaScript -->
<script src="components.js"></script>
```

### Use Components

```html
<!-- Button -->
<button class="btn btn-primary" onclick="handleClick()">
  Click Me
</button>

<!-- Card -->
<div class="card">
  <div class="card-header">
    <h3>Card Title</h3>
  </div>
  <div class="card-body">
    <p>Card content goes here</p>
  </div>
</div>

<!-- Modal -->
<button class="btn btn-primary" onclick="openModal('myModal')">
  Open Modal
</button>

<div class="modal" id="myModal">
  <div class="modal-content">
    <span class="close" onclick="closeModal('myModal')">&times;</span>
    <h2>Modal Title</h2>
    <p>Modal content</p>
  </div>
</div>
```

## 🎯 JavaScript API

### Modal

```javascript
// Open modal
openModal('modalId');

// Close modal
closeModal('modalId');
```

### Form Validation

```javascript
// Validate form
const isValid = validateForm('formId');

// Show error message
showError('inputId', 'Error message');
```

### Toast Notifications

```javascript
// Show toast
showToast('Success message', 'success');
showToast('Error message', 'error');
showToast('Info message', 'info');
```

## 🎨 Customization

### CSS Variables

```css
:root {
  --primary-color: #007bff;
  --secondary-color: #6c757d;
  --success-color: #28a745;
  --danger-color: #dc3545;
  --warning-color: #ffc107;
  --info-color: #17a2b8;
  
  --font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto;
  --border-radius: 4px;
  --transition: all 0.3s ease;
}
```

### Override Styles

```css
/* Custom button style */
.btn-custom {
  background: linear-gradient(45deg, #667eea, #764ba2);
  color: white;
  border: none;
}
```

## 📱 Responsive Design

All components are mobile-first and fully responsive:

```css
/* Mobile: Default styles */
.card { width: 100%; }

/* Tablet: 768px+ */
@media (min-width: 768px) {
  .card { width: 50%; }
}

/* Desktop: 1024px+ */
@media (min-width: 1024px) {
  .card { width: 33.333%; }
}
```

## ♿ Accessibility

Components follow WCAG 2.1 guidelines:

- Semantic HTML
- ARIA labels and roles
- Keyboard navigation
- Focus indicators
- Screen reader support

```html
<button class="btn" 
        aria-label="Close modal"
        role="button"
        tabindex="0">
  Close
</button>
```

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📚 Examples

Check out example files:
- `buttons.html` - Button variants
- `forms.html` - Form components
- `index.html` - All components

## 🤝 Contributing

1. Fork the repository
2. Create feature branch
3. Commit changes
4. Push to branch
5. Open Pull Request

## 📄 License

MIT License - see LICENSE file

## 🎉 Credits

Built with ❤️ for frontend developers

---

**Star ⭐ this repo if you find it useful!**

## Update 2025-10-14 12:41:26
# Updated: 2025-10-14 12:41:26
def updated_function():
    pass

## Update 2025-10-18 15:32:16
# Updated: 2025-10-18 15:32:16
def updated_function():
    pass

## Update 2025-10-22 13:08:08
def handle_error(error):
    """Handle error gracefully"""
    logger.error(f'Error: {error}')
    return None

## Update 2025-11-09 15:27:58
if data is None:
    raise ValueError('Data cannot be None')
return validate_data(data)