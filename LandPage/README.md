 Introduction:  
This was my very real project in the foundation path of the odin Project. The process was simple but daunting, to recreate a professional-looking landing page from a static image using only HTML and CSS. No frameworks, no shortcuts—just pure CSS. The most important part of this challenge was getting to knwow CSS flexbox to manage complex layouts with no framworks or shortcuts allowed.

Reflection:  
    My Approach
I started by thinking in boxes. I break the mockups into five distinct sections: 

1. The Hero/Header Section: Getting that dark background and white text contrast.

2. The Info Section: Aligning the four image-placeholder cards.

3. The Quote Section: Using Flexbox to center the text and CSS font-style: italic to match the design.

4. The Call to Action Section: Creating that "floating" blue box effect.

5. The Footer: A simple, clean finish.

After I wrote down the different sections, I decided to sketch out each section to visualize the invisible boxes of the layout. This process helped me map out exactly how many <div>, <sections>, and containers I needed, and how they would nest inside one another.

Once I was finished, I spent time researching modern HTML best practices. I didn't want to just build layers that looked right; I wanted to build a page that was semantic and accessible. The research was helpful in helping me decide when to use a <section> versus a <div>, and how to structure my navigation for the best user experience. The bridge between sketching and technical research made the coding phase feel much more lively.

Built With:

HTML5 - Semantic structure and accessibility.

CSS3 - Custom styling and layout using Flexbox.

VS Code - My primary code editor.

Google Fonts - Roboto typeface (300, 400, 900 weights).

Challenges & Solutions
It has been quite an overwhelming journey to reach the end of creating this landing page. Along the way, I encountered several difficulties. Below are the challenges I faced and how I overcame them.

1. Translating Sketches to HTML Structure
After sketching the different sections and possible layouts on paper, my first major challenge was translating those sketches into clean HTML.

The Difficulty: Even with my sketches, deciding which elements should be parents (Sections) and which should be children (Containers/Divs) was difficult. I had to figure out how to nest the code so the layout would remain organized and behave correctly when I added Flexbox later.

The Solution: I researched on Google and chatted with former students of The Odin Project. I concluded that using Box Model logic was the best way—treating every part of my sketch as a series of nested boxes. This made it much easier to write the HTML hierarchy before I even touched the CSS.

2. Visual Sync: VS Code vs. Chrome
Another significant hurdle was the technical setup of my workspace and how I viewed my progress.

The Difficulty: Moving from the VS Code editor to the browser wasn't an easy task. At first, I used the "Show Preview" feature inside VS Code, but it did not show clearly what I was coding. The layout looked inconsistent compared to the final result, which was a major source of frustration. I wasn't sure if my code was wrong or if the preview window was failing to render the CSS correctly.

The Solution: I stopped using the internal preview and began using Chrome as my primary testing ground. Using Chrome Developer Tools allowed me to see the "truth" of my code and accurately measure margins and alignment in a real-world environment.

3. The Container Alignment Puzzle
The Difficulty: Looking closely at the project mockup, I noticed that the Hero and CTA sections appeared wider and more spread out than the Info and Quote sections. My original container was making everything feel too tight.

The Solution: I adjusted the width of my container, increasing it from 1000px to 1200px. This allowed the content to move further toward the edges of the screen, matching the "open" feel of the original design.

Conclusion
Completing this landing page has been a huge milestone in my web development journey. What started as a confusing mix of HTML tags and CSS properties eventually turned into a structured, professional-looking website.

Through the "overwhelming" moments, I learned that web development isn't just about writing code—it's about planning, debugging, and knowing where to find help. Researching on Google and chatting with the community on Discord were incredibly helpful; they provided the clarity I needed when I felt stuck on layout logic.

Mastering the Box Model and learning to rely on Chrome Developer Tools have given me the confidence to take on more complex designs in the future. I am proud of the final result and excited to apply these layout skills to my next project in The Odin Project!