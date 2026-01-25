Pricing Practice: Tiered Layout
 Project Overview
This project was an independent deep-dive into component-based design. I focused on creating a clean, professional pricing section often found in SaaS (Software as a Service) websites. The goal was to master the "Featured Product" pattern where one option is visually emphasized to drive conversions.

Technical Breakdown
Flexbox Layout: Utilized display: flex on the container for horizontal alignment and inside each card for vertical spacing.

Visual Weight: Implemented a .featured class using transform: scale(1.05) and distinct border-color to create a focal point.

Box Model Mastery: Applied box-sizing: border-box to manage padding and borders accurately without breaking the layout.

Clean UI: Used border-radius: 20px for modern, rounded aesthetics and removed default list styling (list-style: none) for a minimalist look.

💡 Key Takeaway
While building this, I learned how to use justify-content: space-between inside a column-flex container to ensure that the "Sign Up" buttons always align at the bottom of the card, regardless of the amount of text above them.