# Ravi Kiran Terikoti · Cinematic portfolio

A scroll-driven film about how I design, built with Three.js, plus a fast "Full story" section for recruiters.

**Live site:** https://kiran8985-li.github.io/ravi-kiran-portfolio/

## What's inside
- Opening Milky Way galaxy that forms on load
- Four scenes: Who I am · The problem · The work · Let's talk
- Around 22,000 GPU particles that morph into a shape for each project
- Experience as a constellation: the camera flies to each role
- Click or tap anywhere for a blast effect
- A plain, skimmable "Full story" section with case studies, experience, skills and contact

## Run it
It's one file. Open `index.html` in Chrome or Edge with internet on (Three.js and fonts load from CDNs).

## Edit your details
Open `index.html` and find the `CONFIG` block near the top of the script:

```js
const CONFIG = {
  resume: '',          // link to your résumé PDF
  github: 'https://github.com/kiran8985-li',
  btechYears: ' (graduated 2024)',
  screens: { viva: [], yard: [], campus: [] }   // image paths of real project screens
};
```

Put screenshots in an `images/` folder and list them, for example `viva: ['images/viva-1.png']`.

## Publish with GitHub Pages
Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, folder `/ (root)` → Save.

## Built with
HTML, CSS, JavaScript, Three.js (custom GLSL shaders). No build step.
