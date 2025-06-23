# Cafe Ordering System

A modern web-based cafe ordering system that allows customers to scan QR codes at their tables and place orders directly through their devices.

## Features

- **QR Code Integration**: Scan table QR codes to start ordering
- **Category-based Menu**: Browse items by categories (Beverages, Breakfast, Desserts, etc.)
- **Cart Management**: Add/remove items, specify quantities
- **Order Tracking**: View order status and history
- **Responsive Design**: Works seamlessly on all devices

## Pages

- `index.html`: Main dashboard/menu page
- `category-wide.html`: Category listing page
- `product.html`: Individual product details with video support
- `cart.html`: Shopping cart and order placement
- `order-success.html`: Order confirmation page
- `order-detail.html`: Detailed order information
- `order-history.html`: List of past orders

## Technology Stack

- HTML5
- CSS3 (Bootstrap 5)
- JavaScript (jQuery)
- Local Storage for data persistence

## Setup

1. Clone the repository
2. Open `index.html` in a web browser
3. For development, use a local server to avoid CORS issues with assets

## Project Structure

```
frontend/
├── assets/
│   ├── css/
│   ├── js/
│   ├── images/
│   ├── icons/
│   └── fonts/
├── index.html
├── cart.html
├── order-detail.html
└── ... other pages
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 