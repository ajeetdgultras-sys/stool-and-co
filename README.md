# Stool & Co
Responsive static homepage recreated from the supplied Stool & Co homepage PDF. Original product images and embedded Inter font subsets are stored locally in dist/assets. No build step or external dependencies.

Serve `dist` with any static server. `dist/index.html` is the entry point. The Sites hosting configuration is in `.openai/hosting.json`.

## Before launching the customer campaign
Replace the generic Kickstarter links with the exact campaign URL. Add the confirmed product enquiries email/contact destination. The supplied PDF has no campaign-specific URL or enquiry address. FAQs use only product information in the supplied reference.

## GitHub
The requested GitHub destination is `ajeetdgultras-sys/stool-and-co`. The GitHub repository mirrors the published website source and media. Sites source synchronization uses its own managed Git remote and does not establish an automatic GitHub deployment integration.

## Creative update
Integrated 23 unique user-supplied creatives, using lossless WebP with unchanged visible pixels. Updated matching feature visuals, comparison, specifications, finishes and posture images; added sizing, designer, development, Kickstarter ordering and shipping guides. Product images support an accessible full-size viewer.

The first uploads with GIF names were received as single-frame PNGs. The later Archive.zip supplied seven real animated GIFs; those now play as optimized H.264 MP4 loops, preserving the source timing. Autoplay is muted and inline, with pause/play and full-size playback controls. Offscreen animations pause, and reduced-motion preferences are respected.

## Responsive layout
Phone hero displays the complete product image with its call to action beneath it. Narrow tablets use a readable single column. Mobile navigation has full-width touch targets, and media viewers fit within the viewport.

## Kickstarter campaign prompts
Four prominent campaign placements open one shared popup. An automatic popup appears after eight seconds, once per browser session. Set the official campaign URL in `dist/campaign-config.js`; until then the popup shows a disabled coming-soon action and sends visitors nowhere.

The circled posture graphic (`original-angle.webp`) is static because its animated original was absent from Archive.zip. The seven supplied animations continue to use their working MP4 loops.
