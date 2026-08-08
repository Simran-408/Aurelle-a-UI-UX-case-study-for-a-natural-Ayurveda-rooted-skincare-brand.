# Aurelle — a UI/UX case study for a natural, Ayurveda-rooted skincare brand.

A UI/UX design project for Aurelle, a fictional D2C skincare brand built 
around Indian ingredients and Ayurvedic knowledge — designed to make 
"natural" and "clinically backed" feel like structural decisions in the 
product, not just marketing copy.

This isn't just a product catalog. The core of the project is a 
4-step ritual quiz that turns a skin assessment into a personalized 
AM/PM routine, alongside a full ingredient-sourcing system (origin, 
efficacy, clinical data) that runs through the homepage, product pages, 
and ingredient stories.

## What's inside
- Homepage — brand intro, ingredient storytelling, quick ritual builder
- Shop — filterable product grid across skincare, haircare, and body care
- Product detail page — ingredient breakdown, sourcing map, clinical results
- Ritual quiz — 4-step personalized routine builder with live preview
- Ritual landing — quiz intro + premade ritual packages for users who want to skip straight to a curated routine
  
## Design approach
Rather than designing screen-by-screen, I treated color, typography, and components as one connected system — every decision below was made to be reused across the homepage, shop, PDP, and quiz, not invented per page.

Color system. The palette is built from a single green hue rather than several unrelated greens picked for individual moments. Early versions of the UI used three different greens across buttons, cards, and section backgrounds — each looked fine in isolation but didn't read as one brand when placed side by side. I standardized on one hue and generated tints (light, for section backgrounds and badges) and shades (dark, for hover states and the footer) from it, so every green on the site is provably part of the same family. Neutrals were matched to the same warm undertone as the background instead of using generic gray, which is a small change but is what keeps the page from feeling assembled from default UI-kit colors.

Typography and hierarchy. Body and heading text use a warm near-black rather than pure black, for the same undertone-matching reason as the color system — cool black on a warm cream background is a subtle mismatch that's easy to miss at the component level but visible at the page level. Text color also follows a strict role system: primary text, muted/secondary text, links, and text-on-color each have one designated value used consistently, rather than being re-picked per screen.

CTA hierarchy. Early screens had two competing "primary" actions — a green button and a black button — which splits attention and makes the intended next step ambiguous. I resolved this to a single rule: green is the only filled, primary-action color across the entire product; every other button is either an outline or ghost style, so there's always one obvious next step per screen.

Components. Badges (ingredient tags like "Anti-Acne" or "Brightening," plus status labels like "Bestseller") follow one consistent shape, size, and color logic so they can be scanned instead of read. The same discipline was applied to product cards and icon containers across pages, so a component built for the homepage behaves the same way when it reappears on the shop grid or PDP.

## Process & tools
Low-fidelity wireframes started with UX Pilot AI for rapid layout exploration, 
then were manually revised for information hierarchy, flow logic (especially 
the ritual quiz, which needed custom multi-step structure), and to align with 
the final component and color system. High-fidelity screens, the design 
system, and all UI decisions were done manually in Figma.

Full case study (problem, research, wireframes, iteration): https://app.notion.com/p/UI-UX-Case-Study-3b6b9621fd6a806f9abbcbe98df163a8?v=733b9621fd6a835e83f988b5e2a9bca0&source=copy_link
