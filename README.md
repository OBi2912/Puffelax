# Puffelax - Premium Vaping E-Commerce Platform

A modern, responsive web application built with Flask for showcasing and selling premium vaping products. Puffelax offers a seamless shopping experience with multilingual support, interactive product modals, and a clean, professional design.

## Features

- **Responsive Design**: Optimized for desktop and mobile devices
- **Multilingual Support**: English and Spanish translations
- **Interactive Product Gallery**: Click-to-view product details with modal popups
- **Shopping Cart Functionality**: Add products to cart with persistent storage
- **Modern UI/UX**: Clean design with smooth animations and transitions
- **Fast Loading**: Optimized static assets and efficient Flask routing

## Technologies Used

- **Backend**: Python Flask
- **Frontend**: HTML5, CSS3, JavaScript
- **Styling**: Custom CSS with responsive design
- **Icons**: Font Awesome
- **Internationalization**: Client-side language switching

## Installation

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd puffelax
   ```

2. **Create a virtual environment** (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Run the application**:
   ```bash
   python app.py
   ```

2. **Open your browser** and navigate to:
   ```
   http://localhost:5000
   ```

3. **Explore the site**:
   - Home page with featured products
   - Products page for full catalog
   - Checkout page for cart management

## Project Structure

```
puffelax/
├── app.py                 # Main Flask application
├── requirements.txt       # Python dependencies
├── static/
│   ├── css/
│   │   ├── style.css     # Main stylesheet
│   │   └── toast.css     # Toast notification styles
│   ├── js/               # JavaScript files
│   └── images/           # Product images and assets
└── templates/
    ├── base.html         # Base template with navigation
    ├── index.html        # Home page
    ├── products.html     # Products catalog
    └── checkout.html     # Shopping cart checkout
```

## Key Components

- **Navigation**: Responsive header with language selector
- **Hero Section**: Eye-catching landing area with call-to-action
- **Product Cards**: Interactive cards with modal details
- **Shopping Cart**: Persistent cart with localStorage
- **Toast Notifications**: User feedback for actions
- **Language Switcher**: Seamless English/Spanish toggle

## Development

The application uses Flask's debug mode for development. All static assets are served through Flask's built-in server. The frontend is built with vanilla JavaScript for optimal performance and no external dependencies beyond Font Awesome for icons.

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For support or inquiries:
- Email: support@puffelax.com
- Phone: +1 (555) 123-4567
- Address: 123 Vaping Blvd, Cloud City, CA 90210