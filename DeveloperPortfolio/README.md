My Developer Portfolio: The Story of the Build

💡 The Idea
I actually had a portfolio before this one! It was a free WordPress site. It looked okay, but I didn't feel like a "Developer" using it because I hadn't written a single line of the code myself.

As I got deeper into The Odin Project, I realized I wanted to build my own "home" on the internet from scratch. I wanted to take the professional look of my old WordPress site but build it using my own HTML and CSS. This project is the result of that transition—from using tools built by others to building my own.

🏗️ What I Built
A fully responsive, single-page portfolio that tells my story: moving from a Special Needs Teacher at Bahrain Polytechnic to a Full-Stack Developer. It features:

A smooth-scrolling navigation bar.

A "Human-Centered" About section.

Project cards linked directly to my GitHub.

A direct download for my professional resume.

🧗 Difficulties & Solutions
Building this wasn't always easy. Here are the "roadblocks" I hit and how I fixed them:

1. The "Ghost" Underlines
The Problem: I tried to put a link inside a button tag for my "View My Work" section. It looked terrible! The text was blue and underlined, and it didn't look like a professional button at all.

The Solution: I learned that you shouldn't nest an <a> inside a <button>. I removed the button tag, styled the link (<a>) as an inline-block, and used text-decoration: none in CSS to kill the underline. Now it looks like a solid, clean button.

2. Nesting Content (The "Within" Confusion)
The Problem: I wasn't sure where to put my Resume Download. I kept putting it in places where it felt lost or messy.

The Solution: I learned about "nesting." I placed the resume download within the Contact Section container. This makes sense for the user—once they decide they want to talk to me, my resume is right there waiting for them.

3. Creating a "Live" Connection
The Problem: I first used "Permalinks" for my GitHub projects. I realized that if I updated my code, the link would show the old version.

The Solution: I switched all my project links to the main branch URL. Now, as I grow and improve my code, my portfolio always shows my best, most recent work automatically.

4. Making it "Me"
The Problem: At first, the text felt like a generic template. It talked about "Content Writing," but that isn't my main story.

The Solution: I rewrote the Hero and About sections to focus on my real background—Special Needs Education and IT Leadership. This turned a "coding exercise" into a real professional brand.

🛠 Tech Used
HTML5: Semantic tags for better accessibility (a11y).

CSS3: Flexbox for layout and custom properties (variables) for the colors.

Logic: Smooth scrolling and responsive design for mobile users.