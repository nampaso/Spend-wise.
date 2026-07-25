Highlights of this implementation:
CSS Grid Macro Structure: The .app-layout wrapper defines explicit regions (sidebar, header, main) using grid-template-areas.

Flexbox Micro Alignment: Headers, navigation links, user avatars, card contents, and user controls are laid out strictly using Flexbox.

CSS Variables (:root): Includes variables for brand, accent, surface, border, and text colors.

Dark Mode Included: A @media (prefers-color-scheme: dark) media query seamlessly overrides standard variables when your browser/OS is in dark mode.

Micro-interactions: .card:hover and .card:focus-visible utilize a 200ms transform: translateY(-4px) and box-shadow elevation, fully accessible via keyboard (tabindex="0").

Responsive Breakdown (<768px): The grid collapses into a single-column layout where the sidebar shifts horizontally beneath the header to accommodate touch screens without breaking overflow boundaries.
