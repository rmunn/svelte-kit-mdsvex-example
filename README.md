# Svelte-Kit + mdsvex

Markdown in Svelte, and Svelte in Markdown, powered by [Svelte-Kit](https://github.com/sveltejs/kit/) and [mdsvex](https://mdsvex.com/).

## To use

This example uses [pnpm](https://pnpm.js.org/en/). Install it if you don't have it already:

```bash
npm i -g pnpm
```

Then install the dependencies for this example:

```bash
pnpm i
```

Then run it:

```bash
pnpm run dev
```

Now open a browser to http://localhost:3000/ and you should see the Svelte welcome page. Now try visiting the following URLs:

- http://localhost:3000/some-title
- http://localhost:3000/some-other-title
- http://localhost:3000/blogpost
- http://localhost:3000/foo

These pages will be served up by `src/routes/[slug].svx`,  `src/routes/[slug].svx` (again),  `src/routes/blogpost.svx`, and  `src/routes/foo.svelte` in that order.
