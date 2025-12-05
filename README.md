🖼 Image Preview Modal (JavaScript Plugin)
A lightweight and dependency-free JavaScript modal to preview images in a clean, animated overlay — ideal for galleries, product images, thumbnails, or admin panels.

No jQuery required. No CSS file required. Just plug & play.
🚀 Features

✔ Pure JavaScript (No Dependencies)
✔ Auto-injects required CSS (no styling needed)
✔ Click outside to close
✔ Animated fade + zoom effect
✔ Clean & modern UI
✔ Perfect for thumbnails or images preview
📦 CDN Usage
Add the script inside your HTML:

<script src="https://cdn.jsdelivr.net/gh/ssofton/image-modal/imagemodal.js"></script>

Option 1: showImageModal('path/to/your/image.jpg');
Option 2: <img src="thumbnail.jpg" class="view-image" />

📍 Function Definition
The modal automatically:
Creates overlay
Injects CSS (only once)
Displays animated image
Closes on outside click or ❌ button
🎯 Example Demo Code
<img src="https://softondemand.co.in/home/attachment/logo/logo.png" onclick="showImageModal('big.jpg')" />
