# SpectroVirtu CIS Website Backup Notes

Last updated: 2026-04-26

## Project Folder

Current working project:

```text
C:\Users\yang_\Documents\Codex\2026-04-26\files-mentioned-by-the-user-30288260
```

Main local preview file:

```text
preview.html
```

Main Vite / React files:

```text
package.json
vite.config.js
index.html
src/main.jsx
src/App.jsx
src/styles.css
```

## Current Design Direction

The site is a CIS / Corporate Identity System presentation for SpectroVirtu.

The desired style is:

- premium brand guideline
- architectural sustainability
- high-end identity proposal
- clean, minimal, refined
- not SaaS
- not startup
- not generic corporate
- white / off-white base
- deep moss green accents
- quiet floating board feeling
- restrained shadows
- thin divider lines
- large whitespace

## Current Logo / Assets

Current main logo:

```text
src/assets/spectrovirtu-logo-2026-moss.svg
```

Dark field logo:

```text
src/assets/spectrovirtu-logo-2026-dark.svg
```

Large rotating background symbol:

```text
src/assets/spectrovirtu-symbol-moss.svg
```

Brand Applications board image:

```text
src/assets/spectrovirtu-application-board.png
```

Also copied for static preview / public access:

```text
assets/
public/assets/
```

Important: for Vercel, the React build now imports images from `src/assets`, so Vite should bundle them correctly.

## Current Sections

1. Cover / Hero
   - Large SpectroVirtu logo
   - Title: `Corporate Identity System`
   - Subtitle: `Solar identity for architectural integration.`
   - Large rotating logo symbol in background

2. Brand Essence
   - Heading: `A restrained identity for light, surface, and performance.`
   - Note: `SpectroVirtu treats solar technology as part of the architectural language: integrated, precise, and visually composed.`
   - Philosophy: `Solar is composed into the surface, proportion, and performance of architecture.`
   - Tagline: `Light integrated with form.`
   - Removed keyword row: `Surface / Light / System / Detail / Material / Performance`

3. Logo System
   - Heading: `Logo use is defined by clarity and space.`
   - Note: `Maintain the original mark. Control scale, margin, and contrast.`
   - Primary logo
   - Dark field placement
   - Clear space
   - Minimum size
   - Incorrect usage examples were removed

4. Color System
   - Palette board / material board style
   - Main green swatch is larger
   - Other color swatches align neatly
   - Usage ratio:
     - 60% Warm field
     - 25% Deep green
     - 10% Sage / Grey
     - 5% Accent

5. Typography System
   - Heading: `Measured typography for architectural clarity.`
   - Specimen: `Type with quiet precision.`

6. Layout System
   - Heading: `Structure begins with spacing.`
   - 12-column grid
   - spacing rules
   - thin divider lines

7. Visual Language
   - Facade rhythm
   - photovoltaic surfaces
   - material tactility
   - directional light

8. Brand Applications
   - Now uses one large uploaded image as main application board
   - Image file:
     `spectrovirtu-application-board.png`
   - Below it is a clean index:
     - Identity manual
     - Project proposal
     - Business card
     - Brochure spread
     - Tablet website UI
     - Instagram grid
     - Engineering sheet

9. Digital Identity
   - website preview
   - mobile preview
   - components
   - restrained UI style

10. Final Brand Board
   - overview of logo, colors, typography, mockups, and visual system

## Interaction

There is a large background symbol:

- based on the circular symbol from the logo
- positioned partially outside the right side of the viewport
- about half visible
- low opacity
- fixed background layer
- rotates clockwise on scroll
- moves upward when scrolling down
- responsive for mobile

Implemented in:

```text
src/App.jsx
src/styles.css
preview.html
```

## Important Design Decisions

- Removed excessive keyword chips from Brand Essence.
- Removed incorrect logo usage examples.
- Replaced abstract Brand Applications mockup cards with the uploaded application board image.
- Reduced repeated logo usage where possible.
- Kept Dark Field Placement using the dedicated dark/reverse logo.
- Kept `preview.html` for direct local preview without running Vite.
- Kept Vite + React production version for Vercel.

## Backup Folders Already Created

Minimal Japanese clean version backup:

```text
C:\Users\yang_\Documents\Codex\2026-04-26\files-mentioned-by-the-user-30288260_minimal-japanese-copy
```

Working version backup:

```text
C:\Users\yang_\Documents\Codex\2026-04-26\files-mentioned-by-the-user-30288260_backup_20260426_151353
```

## GitHub / Vercel Notes

Vercel site:

```text
https://sv-cis.vercel.app/
```

If Vercel does not update, likely causes:

1. GitHub did not receive the latest files.
2. GitHub Desktop is opened on the wrong folder.
3. Vercel is connected to the wrong GitHub repository.
4. Vercel deployment has not been redeployed.
5. Browser cache needs hard refresh.

Correct local folder for GitHub Desktop:

```text
C:\Users\yang_\Documents\Codex\2026-04-26\files-mentioned-by-the-user-30288260
```

Important files that must exist on GitHub:

```text
src/assets/spectrovirtu-logo-2026-moss.svg
src/assets/spectrovirtu-logo-2026-dark.svg
src/assets/spectrovirtu-symbol-moss.svg
src/assets/spectrovirtu-application-board.png
src/App.jsx
src/styles.css
package.json
vite.config.js
index.html
```

If using GitHub Desktop:

1. Open GitHub Desktop.
2. Add local repository:
   `C:\Users\yang_\Documents\Codex\2026-04-26\files-mentioned-by-the-user-30288260`
3. Commit changes.
4. Push origin.
5. Check GitHub website to confirm files are present.
6. Go to Vercel and redeploy if needed.

If Git is missing in PowerShell:

Install Git for Windows:

```text
https://git-scm.com/download/win
```

## Vercel Settings

Recommended Vercel settings:

```text
Framework Preset: Vite
Install Command: npm install
Build Command: npm run build
Output Directory: dist
Production Branch: main
```

## Claude Prompt Backup

Use this prompt if recreating in Claude:

```text
Create a premium responsive CIS / Corporate Identity System presentation website for the brand “SpectroVirtu”.

This is not a marketing landing page.
It should feel like a high-end brand guideline, identity proposal, and architectural design system presentation.

Brand direction:
- minimal
- refined
- architectural
- clean Japanese-inspired layout
- quiet luxury
- solar / architectural integration
- premium identity manual
- not SaaS
- not startup
- not generic corporate

Use the provided SpectroVirtu logo exactly as given. Do not redesign it.

Use a large rotating background symbol based on the circular logo mark. It should sit partially outside the right side of the viewport, be very low opacity, move upward on scroll, and rotate clockwise like a slow gear.

Visual style:
- clean white / off-white background
- deep moss green accents
- restrained grey-green secondary tones
- thin divider lines
- large whitespace
- matte paper feeling
- floating board sections
- subtle premium shadows only on key panels
- no colorful gradients
- no decorative blobs
- no generic SaaS look

Main sections:
Cover / Hero
Brand Essence
Logo System
Color System
Typography System
Layout System
Visual Language
Brand Applications
Digital Identity
Final Brand Board

Brand Applications should use one large premium application board image as the main visual, with a clean index below it.

Output complete production-ready Vite + React code with:
- package.json
- index.html
- src/main.jsx
- src/App.jsx
- src/styles.css
- assets references

Also include a static preview.html that can be opened directly in a browser without running Vite.
```

