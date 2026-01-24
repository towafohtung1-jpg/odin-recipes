Hero Design & Layout Practice
 Project Overview
The "Hero" is the most critical part of any landing page. This practice project was an exploration into creating a high-impact first impression using modern CSS techniques. I focused on building a responsive, split-screen hero section paired with a sophisticated "glass-effect" navigation bar.

Technical Breakdown
Glassmorphism UI: Implemented a semi-transparent navigation bar using backdrop-filter: blur(10px) and background-color: rgba(...). This creates a modern "frosted glass" look as content scrolls beneath it.

Sticky Navigation: Used position: sticky and z-index to ensure the menu remains accessible at the top of the viewport during scrolling.

Split-Screen Layout: Utilized Flexbox on the hero container with flex: 1 on child elements to create a perfectly balanced 50/50 split between content and visuals.

Micro-Interactions: Added transition properties and transform: scale(1.1) to call-to-action buttons to improve tactile feedback and user engagement.

 Key Takeaway
The biggest challenge in this project was managing the Stacking Context. By setting a high z-index on the sticky navbar, I ensured it stayed on top of all other page elements. I also learned the value of width: fit-content for buttons to prevent them from stretching across the entire flex container.