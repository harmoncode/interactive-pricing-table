# Interactive Pricing Table

A modern pricing table with hover effects and interactive elements. Perfect for SaaS applications, service providers, or any business that needs to showcase different pricing tiers with engaging interactions.

## ✨ Features

- **Interactive Elements**: Hover effects and click interactions
- **Multiple Plans**: Support for unlimited pricing tiers
- **Feature Comparison**: Easy feature highlighting and comparison
- **Responsive Design**: Works perfectly on all devices
- **Customizable**: Easy to customize colors, layout, and content
- **Accessible**: Built with accessibility in mind
- **Animation Effects**: Smooth transitions and micro-interactions
- **Call-to-Action**: Integrated CTA buttons for conversions

## 🚀 Live Demo

[View on CodePen](https://codepen.io/harmoncode/pen/GgJRWyP)

## 📁 Files

- `index.html` - Main HTML structure
- `style.css` - All styling and animations
- `script.js` - JavaScript functionality

## 🛠️ Usage

### Basic Implementation

```html
<div class="pricing-table">
    <div class="pricing-card">
        <div class="card-header">
            <h3>Basic</h3>
            <div class="price">
                <span class="currency">$</span>
                <span class="amount">29</span>
                <span class="period">/month</span>
            </div>
        </div>
        <div class="card-features">
            <ul>
                <li>Feature 1</li>
                <li>Feature 2</li>
                <li>Feature 3</li>
            </ul>
        </div>
        <div class="card-footer">
            <button class="cta-btn">Get Started</button>
        </div>
    </div>
    <!-- More pricing cards... -->
</div>
```

### JavaScript Configuration

```javascript
// Initialize pricing table
const pricingTable = new PricingTable({
    cards: '.pricing-card',
    enableHover: true,
    enableComparison: true
});
```

## 🎨 Customization Options

- **Colors**: Customize card colors, gradients, and themes
- **Layout**: Modify card layout and spacing
- **Animations**: Adjust hover and interaction effects
- **Typography**: Change fonts, sizes, and weights
- **Features**: Add/remove features and customize icons

## ⚙️ Configuration

```javascript
const config = {
    enableHover: true,       // Enable hover effects
    enableComparison: true,  // Enable feature comparison
    animationDuration: 300,  // Animation duration (ms)
    highlightPopular: true,  // Highlight popular plan
    showAnnualToggle: false, // Show annual/monthly toggle
    currency: '$',           // Currency symbol
    period: 'month'          // Billing period
};
```

## 📱 Browser Support

- Chrome ✅
- Firefox ✅
- Safari ✅
- Edge ✅
- IE11+ ✅

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Created by

**HarmonCode** - [harmoncode.com](https://harmoncode.com)

---

⭐ If you find this useful, please give it a star! 