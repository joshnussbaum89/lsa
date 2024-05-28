# LSA (Lightweight Scrolling Animation) Library

Add subtle scrolling animations to your web projects with ease. Inspired by the infamous [AOS library](https://michalsnik.github.io/aos/).

This version is a bit simpler. Just copy and paste the provided CSS and JavaScript files from the `/lsa` folder into your project, and you're ready to go.

Totally customizable, lightweight, and very much meant to be messed with 🛠️

## Getting Started

To use the LSA Library, follow these steps:

1. Copy and paste the provided CSS code from `lsa/style.css` into your project's CSS file.
2. Copy and paste the provided JavaScript code from `lsa/main.js` into your project's JavaScript file.
3. Add additional classes to your HTML elements to specify different animation effects.

## Usage

### Basic Structure

To use the LSA Library, wrap your content in elements with the `lsa` class. You can then add additional classes to specify different animation effects.

### Example 1: Fade In Animation

To apply a _fade in_ animation to an element, and to initialize the library, add the class `lsa`:

```html
<div class="lsa">
  <h3>Fade In Example</h3>
</div>
```

### Example 2: Slide Up Animation

To apply a _slide up_ animation to an element, add the classes `lsa` and `lsa-slide-up`:

```html
<div class="lsa lsa-slide-up">
  <h3>Slide Up Example</h3>
</div>
```

### Example 3: Slide Right Animation

To apply a _slide right_ animation to an element, add the classes `lsa` and `lsa-slide-right`:

```html
<div class="lsa lsa-slide-right">
  <h3>Slide Right Example</h3>
</div>
```

## Available Animations

Here are the available animation classes you can use with the `lsa` class:

- `lsa`: Required, default _fade in_ animation
- `lsa-slide-up`: _Slide up_ animation
- `lsa-slide-down`: _Slide down_ animation
- `lsa-slide-left`: _Slide left_ animation
- `lsa-slide-right`: _Slide right_ animation
- `lsa-slide-down-right`: _Slide down right_ animation
- `lsa-slide-down-left`: _Slide down left_ animation
- `lsa-slide-up-right`: _Slide up right_ animation
- `lsa-slide-up-left`: _Slide up left_ animation

## Customization

You can customize the appearance and behavior of the animations by modifying the CSS classes and JavaScript options.

### No-Repeat Animation

By default, animations will repeat when the element comes into view again. If you do not want the animation to repeat, add the `no-repeat` class to the element:

```html
<div class="lsa lsa-slide-up-right no-repeat">
  <h3>Slide Up Right Example (No Repeat)</h3>
</div>
```

## Notes

- Ensure that you include all the required CSS and JavaScript code from the `/lsa` folder in your project for the animations to work correctly.
- This was thrown together rather quickly and will be updated with more features over time. Feel free to contribute or suggest improvements. Enjoy!

See more at [Wave Land Web](https://wavelandweb.com/)
