# Owens Mental Health — Static Site (Netlify-ready)

## Folder layout
site/
├─ index.html
├─ thank-you.html
├─ blog/
│  ├─ index.html
│  ├─ market-street-at-dusk.html
│  ├─ gaffer-district-lights.html
│  └─ post-template.html
└─ images/
   ├─ hero.jpg
   ├─ logo.png
   └─ (add your corning1.jpg ... corning5.jpg)

## Notes
- The code expects **hero.jpg** and **logo.png** inside **/images/** (this bundle is set up that way).
- Put your gallery photos into **/images/** and update the JSON list inside **index.html** (search for `gallery-data`).
- Deploy by dragging the entire **site/** folder to https://netlify.com/drop
- Contact form is wired to FormSubmit → joeltowens@gmail.com and redirects to /thank-you.html