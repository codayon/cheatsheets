# Tailwind CSS Quick Start Guide

Easily set up Tailwind CSS using the Tailwind CLI tool.

## Installation

### 1. Install Tailwind CSS

Run the following command to install Tailwind and its CLI via npm:

```sh
npm install tailwindcss @tailwindcss/cli
```

## Configuration

### 2. Import Tailwind in Your CSS

Include Tailwind in your main CSS file (`src/input.css`):

```css
@import "tailwindcss";
```

### 3. Build Your CSS

Use the CLI tool to generate your CSS file and enable automatic updates:

```sh
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
```

## Usage

### 4. Link Tailwind in HTML

Reference the compiled CSS file in your HTML (`src/index.html`):

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link href="./output.css" rel="stylesheet" />
  </head>
  <body>
    <h1 class="text-3xl font-bold underline">Hello, Tailwind CSS!</h1>
  </body>
</html>
```

Now you're ready to use Tailwind CSS utility classes in your project! 🎉
