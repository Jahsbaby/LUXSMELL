# LUXSMELL - Luxury Fragrance Website

## Overview
LUXSMELL is a responsive e-commerce website for luxury fragrances, built using HTML and Tailwind CSS. This project demonstrates modern web design practices with a focus on responsiveness and aesthetic appeal.

## Project Structure
```
luxsmell/
├── img/
│   ├── logo.png
│   └── body_img.jpg
├── index.html
└── README.md
```

## Tailwind CSS Utility Classes used in the project

### Layout & Container Classes

```css
container        /* Sets a max-width and centers the container */
mx-auto         /* margin-left: auto; margin-right: auto */
px-4           /* padding-left: 1rem; padding-right: 1rem */
py-3           /* padding-top: 0.75rem; padding-bottom: 0.75rem */
```

### Flexbox & Grid

```css
flex            /* display: flex */
grid            /* display: grid */
items-center    /* align-items: center */
justify-between /* justify-content: space-between */
grid-cols-1     /* grid-template-columns: repeat(1, minmax(0, 1fr)) */
gap-8          /* gap: 2rem */
```

### Spacing & Sizing
```css
space-x-4      /* margin between horizontal elements: 1rem */
mt-8           /* margin-top: 2rem */
mb-4           /* margin-bottom: 1rem */
w-6            /* width: 1.5rem */
h-6            /* height: 1.5rem */
```

### Typography
```css
text-xl        /* font-size: 1.25rem */
font-bold      /* font-weight: 700 */
text-center    /* text-align: center */
text-white     /* color: white */
```

### Responsive Design Prefixes
```css
sm:            /* @media (min-width: 640px) */
md:            /* @media (min-width: 768px) */
lg:            /* @media (min-width: 1024px) */
xl:            /* @media (min-width: 1280px) */
```

Example:
```css
text-base sm:text-lg /* 
  font-size: 1rem on mobile
  font-size: 1.125rem on screens >= 640px 
*/
```

### Background & Colors
```css
bg-gradient-to-r    /* background-image: linear-gradient(to right, ...) */
from-green-500     /* starting color of gradient */
via-yellow-500    /* middle color of gradient */
to-blue-500      /* ending color of gradient */
bg-opacity-50    /* background-color opacity: 50% */
```

### Positioning
```css
relative        /* position: relative */
absolute        /* position: absolute */
inset-0         /* top: 0; right: 0; bottom: 0; left: 0 */
```

### Interactive Elements
```css
hover:          /* styles applied on hover */
hover:opacity-90 /* opacity: 0.9 on hover */
hover:underline /* text-decoration: underline on hover */
focus:outline-none /* removes focus outline */
```

### Hero Section Classes Explained
```css
min-h-[500px]   /* minimum height: 500px */
bg-cover        /* background-size: cover */
bg-center       /* background-position: center */
bg-no-repeat    /* background-repeat: no-repeat */
```

### Button Classes Explained
```css
px-6            /* padding-left: 1.5rem; padding-right: 1.5rem */
py-3            /* padding-top: 0.75rem; padding-bottom: 0.75rem */
rounded-md      /* border-radius: 0.375rem */
transform       /* enables CSS transforms */
transition      /* enables smooth transitions */
hover:scale-105 /* scale up to 105% on hover */
```


## Responsive Breakpoints

- **Mobile**: < 640px
- **Small (sm)**: ≥ 640px
- **Medium (md)**: ≥ 768px
- **Large (lg)**: ≥ 1024px
- **Extra Large (xl)**: ≥ 1280px

## Common Patterns Used

### Responsive Text
```html
<h1 class="text-3xl sm:text-4xl lg:text-5xl">
<!-- 
  Mobile: 1.875rem (30px)
  Small screens: 2.25rem (36px)
  Large screens: 3rem (48px)
-->
```

### Responsive Grid
```html
<div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3">
<!-- 
  Mobile: 1 column
  Small screens: 2 columns
  Large screens: 3 columns
-->
```

### Responsive Padding
```html
<div class="p-4 sm:p-6 lg:p-8">
<!-- 
  Mobile: 1rem padding
  Small screens: 1.5rem padding
  Large screens: 2rem padding
-->
```

## Getting Started

1. Clone the repository
2. Ensure you have the images in the correct directory structure
3. Open `index.html` in a web browser

## Browser Support
This project uses modern CSS features and is compatible with:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing
Feel free to submit issues and enhancement requests.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

