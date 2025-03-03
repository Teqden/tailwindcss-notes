[TailwindCSS Documentation](https://tailwindcss.com/docs/styling-with-utility-classes)<br>
[Cheatsheet](https://www.creative-tim.com/twcomponents/cheatsheet)

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
```

## Features
1. **Accent** - Change the default color for elements like checkboxes by using `accent-pink-500` .
2. **Fluid Texts** - Change the text size on different devices by using `text-[min(10vw,70px)]` .
3. **File** - Use the prefix `file:` and use any utility to customize the input layout, such like `file:rounded-full` , `file:py-2` , `hover:file:bg-red-100` ,etc.
4. **Highlight** - Change the defalut highlight color when a user selects a text on the website by using `selection:bg-green-400` and `selection:text-white` .
5. **Caret** - Change the default color of caret by using `caret-pink-500` .


