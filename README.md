# Tailwind CSS Dynamic Content Issue in Next.js/Nuxt.js

This repository demonstrates a common issue encountered when using Tailwind CSS with dynamic content in Next.js or Nuxt.js applications.  The problem arises when Tailwind classes are not applied to elements added to the DOM after the initial render. 

**Problem:** Tailwind's JIT mode may not process classes added dynamically through JavaScript.  This results in elements lacking the expected styling.

**Solution:** This repository offers two solutions.  The first uses Tailwind's `@apply` directive to directly apply the CSS rules. The second solution demonstrates the use of a separate CSS file to style dynamic components, bypassing the JIT compilation entirely.

**Setup:**
1. Clone this repository.
2. Navigate to the directory using the command line.
3. Run `npm install` to install dependencies.
4. Run `npm run dev` to start the development server.

Explore the `bug.js` file to see the problem and `bugSolution.js` for solutions.