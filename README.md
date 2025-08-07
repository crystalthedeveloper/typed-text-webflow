
# Typed.js Text Animation in Webflow

This snippet lets you animate words like “Agency”, “Portfolio”, and more using Typed.js inside Webflow.

## 🧠 What It Does
✅ Types and deletes words  
✅ Cycles through your custom list  
✅ Works with just one Webflow class

## 🛠 How to Use It

1. Add this class to your HTML:
```html
<span class="animated-role">Agency</span>
```

2. Include this before the `</body>` tag in Webflow Page Settings:
```html
<script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script>
<script>
  new Typed(".animated-role", {
    strings: ["Blog", "Portfolio", "Agency", "E-Commerce"],
    typeSpeed: 60,
    backSpeed: 40,
    loop: true
  });
</script>
```

Or if using local files:
```html
<script src="script.js"></script>
```

## 👀 Preview
You can open `index.html` in a browser to see it live.
