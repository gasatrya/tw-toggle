# Tailwind CSS Dark Mode Toggle

Floating button to toggle dark mode for Tailwind CSS

## How to use

1. Enable `selector` for the dark mode.

```js
/** @type {import('tailwindcss').Config} */

export default {
  darkMode: "selector",
  // ...
};
```

2. **Optional**: Add the `data-theme` attribute to the `html` tag.

```html
<html lang="en" class="dark:[color-scheme:dark]">
  <!-- ... -->
</html>
```

3. Load the script before the `body` tag.

```html
<script
  src="https://cdn.jsdelivr.net/gh/gasatrya/tw-toggle@1.0.1/tw-theme-toggle.min.js"
  type="module"
  defer
></script>
```

## Demo

[https://tailspace.vercel.app/components/team/team-a.html](https://tailspace.vercel.app/components/team/team-a.html)
