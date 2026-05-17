🌐 Hello Landing Page — Development Log
🧠 What I Built

This project is a very simple landing page built from scratch using HTML, CSS, and JavaScript. The goal was not to make something complex, but to deeply understand how a browser renders a webpage and how basic frontend components interact together.

At its core, the page displays a centered “Hello” message with a short description and a clickable button. Even though it looks minimal, the process behind building it helped reinforce fundamental web development concepts.

🧱 How I Structured It

I kept the project intentionally simple with only one file:

index.html

Instead of splitting into multiple files, I combined structure, styling, and logic in one place to focus on learning rather than architecture.

HTML handles the structure, CSS handles layout and visual design, and JavaScript handles interaction.

🎨 Layout & Design Thinking

One of the main design decisions was to center everything on the screen. I used Flexbox for this instead of absolute positioning because Flexbox is more responsive and easier to manage across screen sizes.

The background uses a linear gradient because it creates a modern UI feel without needing images or external assets.

Typography was kept minimal to ensure the focus stays on the main “Hello” message.

⚙️ How It Works Internally

When the page loads:

The browser parses HTML and builds the DOM
CSS is applied to calculate layout and styling
The Flexbox container centers content both vertically and horizontally
JavaScript attaches a click event to the button
When clicked, the browser triggers a simple alert function

This helped me understand how the browser rendering pipeline works step by step.

🧪 Problems I Faced

At first, the content was not properly centered on the screen. I tried using margin-based positioning, but it didn’t scale well across screen sizes.

Later I switched to Flexbox with:

display: flex
justify-content: center
align-items: center
height: 100vh

This solved the layout issue completely and made the design responsive.

📚 What I Learned

Through this project, I learned:

How HTML structure affects layout rendering
Why CSS Flexbox is powerful for alignment
How JavaScript event listeners work
How small design choices affect user experience
How to deploy a static website using GitHub Pages
How browsers interpret and render web pages
🚀 Deployment

The project is deployed using GitHub Pages. This helped me understand how static hosting works without needing a backend server.

🔮 Next Improvements

In the future, I want to improve this project by:

Adding multiple sections like About and Contact
Improving UI with animations
Adding dark mode toggle
Making it a full portfolio website
Learning React to rebuild it in a component-based structure
🏁 Final Thoughts

Even though this is a very small project, it helped me understand the core foundation of web development. It shows how simple HTML, CSS, and JavaScript can combine to create a working website that runs in the browser.
