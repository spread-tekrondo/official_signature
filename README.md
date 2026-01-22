# SPREAD Email Signature Generator

A modern, React-based email signature generator for SPREAD GmbH. This tool allows users to create professional, Outlook-compatible email signatures with their personal information and photo.

## Features

- **Live Preview** - See your signature update in real-time as you type
- **Photo Upload** - Upload your professional photo with instant preview
- **Email Client Compatible** - Generated signatures work seamlessly in Outlook and other email clients
- **One-Click Copy** - Copy the signature to clipboard and paste directly into your email settings
- **Brand Compliant** - Uses official SPREAD branding, colors (#FF6F47), and DIN Pro font
- **Responsive Design** - Works on all screen sizes

## Tech Stack

- **React 19** - Modern UI framework
- **Vite** - Fast build tool and dev server
- **CSS3** - Custom styling with responsive design
- **Data URIs** - Embedded images and icons for maximum email client compatibility

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm preview
```

## Usage

1. **Upload Your Photo** - Select a professional headshot
2. **Fill in Your Details** - Enter your name, title, phone, and email
3. **Preview** - See your signature update live on the right side
4. **Copy** - Click "Copy Signature for Outlook" button
5. **Paste** - Add the signature to your email client settings

## Signature Specifications

- **Dimensions**: 600px × 200px
- **Photo Size**: 100px × 100px
- **Brand Color**: #FF6F47 (SPREAD Orange)
- **Font**: DIN Pro (with Arial fallback)
- **Format**: HTML table structure for maximum email client compatibility

## Project Structure

```
├── public/
│   └── Spread_Symbol_Orange.png    # Favicon
├── src/
│   ├── assets/
│   │   └── Spread_Logo_Orange.png  # Company logo
│   ├── App.jsx                      # Main component
│   ├── App.css                      # Component styles
│   ├── index.css                    # Global styles
│   └── main.jsx                     # Entry point
├── index.html                       # HTML template
└── package.json                     # Dependencies
```

## Company Information

**SPREAD GmbH**
Köpenicker Str. 40c | 10179 Berlin

Sitz der Gesellschaft: Frankfurt; eingetragen im Amtsgericht Frankfurt a.M. HRB 116653
Geschäftsführung: Philipp Noll, Robert Göbel

## License

Internal use only - SPREAD GmbH

#####
