# online-menu-app

This project aims to create a simple online menu interface and integrate a menu link into a QR code generated with Python. The project uses SCSS for the frontend design of the menu interface and Python for QR code integration.

## Table of Contents

- [Features](#features)
- [Screenshots](#screenshots)
- [Installation](#installation)
- [Scanning](#scanning)
- [Usage](#usage)

## Features

- Responsive menu interface using SCSS.
- QR code generation with Python and integration of the menu link into the code.
- Fast access to the menu through QR code scanning, linked to the menu interface.

## Screenshots

### Desktop Preview

<img src='./screenshots/desktop-preview.png' width='400' height='auto'/>

### Mobile Preview

<img src='./screenshots/mobile-preview.png' width='auto' height='400'/>

## Scanning QR Code

- You can access the online menu by scanning the QR code below.

<img src='./qr_code.png' width='550' height='auto'/>

## Installation

1. Clone the repository:

```bash
git clone https://github.com/SimplyProgYT/online-menu-qr-code.git
```

2. Install the required packages:

```bash
pip install -r requirements.txt
```

## Usage

1. Generate the QR code with Python

```bash
   python generate_qr.py
```

2. Compile SCSS to CSS

- To generate the CSS files from SCSS, run your SCSS compiler. Note that the dist folder where the compiled CSS files are placed is listed in .gitignore, so these files are not tracked in the repository.

- Make sure you have a tool like sass or another SCSS compiler installed. For example:

```bash
sass src/styles.scss dist/styles.css
```

-This command will compile src/styles.scss into dist/styles.css. Adjust the file paths as necessary based on your setup.
