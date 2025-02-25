# Create a Project

Run the command `npx sv create my-project` to create a `SvelteKit` project:<br>
Based on my needs, I chose `SvelteKit minimal (barebones scaffolding for your new app)`, `Yes, using Javascript with JSDoc comments`, and `prettier, eslint, vitest, tailwindcss`.  <br>
For specific installation guides for different frameworks, check the [official documentation](https://tailwindcss.com/docs/installation/framework-guides).<br><br>

With `Tailwind v4.0`, you no longer need a `tailwind.config.js` file to customize styles. Instead, write custom code in the project’s `global CSS` file. For example, in a `SvelteKit` project, go to the `src/app.css` file:<br>  
```Javascript
@import "tailwindcss";

@theme {
  --color-test: #1DA1F2;
  --text-huge: 100px;
}