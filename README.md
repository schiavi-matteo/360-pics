# 360 Panorama Viewer - Università degli Studi di Ferrara

Static hosting repository for 360° equirectangular panoramic photographs, configured for iframe embedding across the official Plone web portal of Università degli Studi di Ferrara.

## Overview
Static assets and the WebGL viewer are served via GitHub Pages to ensure full CORS compatibility for cross-origin embedding.

Panoramas can be viewed:
- Embedded directly within institutional pages via iframe.
- In full-screen mode by opening the standalone viewer link in a new tab.

## Credits & License
- **Pannellum**: The 360° panorama viewer is developed by Matthew Petroff and licensed under the MIT License. Full terms can be found in the `COPYING` file.
- **Photographic Material**: © Università degli Studi di Ferrara. All rights reserved. Unauthorized reproduction or redistribution is prohibited.

## Example: add this block to your HTML page
```
<iframe
    width="1000"
    height="500"
    src="https://schiavi-matteo.github.io/360-pics/pannellum/pannellum.htm#panorama=https://schiavi-matteo.github.io/360-pics/images/studio.jpg&amp;autoLoad=true"
    style="border-style: none; display: table; margin-left: auto; margin-right: auto;"
    sandbox="">
</iframe>
```

## Test your 360° pictures
If you need to check how your 360° pictures behave, you can use this [Local Viewer](https://schiavi-matteo.github.io/360-pics/local-test-viewer.html) to try out the pics locally before uploading them.
