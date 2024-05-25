# LSA (Lightweight Scrolling Animation) Library

Welcome to the LSA (Lightweight Scrolling Animation) Library! This simple and efficient library allows you to add smooth scrolling animations to your web projects with ease. Just copy and paste the provided CSS and JavaScript files into your project, and you're ready to go.

## Getting Started

To use the LSA Library, follow these steps:

1. Copy and paste the provided CSS code from `lsa/style.css` into your project's CSS file.
2. Copy and paste the provided JavaScript code from `lsa/main.js` into your project's JavaScript file.
3. Add the appropriate classes to your HTML elements to apply the desired animations.

## Usage

### Basic Structure

To use the LSA Library, wrap your content in elements with the `lsa` class. You can then add additional classes to specify different animation effects.

### Example 1: Fade In Animation

To apply a fade-in animation to an element, add the class `lsa`:

```html
<div class="lsa">
  <h3>Fade In Example</h3>
</div>
```

### Example 2: Slide Up Animation

To apply a slide-up animation to an element, add the classes `lsa` and `lsa-slide-up`:

```html
<div class="lsa lsa-slide-up">
  <h3>Slide Up Example</h3>
</div>
```

### Example 3: Slide Right Animation

To apply a slide-right animation to an element, add the classes `lsa` and `lsa-slide-right`:

```html
<div class="lsa lsa-slide-right">
  <h3>Slide Right Example</h3>
</div>
```

## Available Animations

Here are the available animation classes you can use with the `lsa` class:

- `lsa`: Default fade-in animation
- `lsa-slide-up`: Slide up animation
- `lsa-slide-down`: Slide down animation
- `lsa-slide-left`: Slide left animation
- `lsa-slide-right`: Slide right animation
- `lsa-slide-down-right`: Slide down right animation
- `lsa-slide-down-left`: Slide down left animation
- `lsa-slide-up-right`: Slide up right animation
- `lsa-slide-up-left`: Slide up left animation

## Customization

You can customize the appearance and behavior of the animations by modifying the CSS classes and JavaScript options.

### No-Repeat Animation

By default, animations will repeat when the element comes into view again. If you do not want the animation to repeat, add the `no-repeat` class to the element:

```html
<div class="lsa no-repeat">
  <h3>Fade In (No Repeat) Example</h3>
</div>
```

## Notes

- Ensure that you include all the required CSS and JavaScript code from the LSA Library in your project for the animations to work correctly.
- The library is designed to be lightweight and easy to integrate, making it perfect for quick enhancements to your web projects.

Enjoy adding smooth scrolling animations to your projects with the LSA Library!
