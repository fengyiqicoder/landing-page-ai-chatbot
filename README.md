# AI chatbot on a landing page (one line of HTML)

A product landing page with an AI chatbot in the corner that answers visitors' questions about features, pricing and privacy from the text of the page. No backend, no plugin, no build step.

**Live demo:** https://fengyiqicoder.github.io/landing-page-ai-chatbot/ (Driftnote is a made-up product.)

## Add it to your landing page

1. Get a free key at [onetagai.com](https://onetagai.com) (1,000,000 tokens one time, no credit card).
2. Paste this before `</body>`, with your key:

```html
<script async src="https://onetagai.com/widget.js" data-key="YOUR_ONETAG_KEY"
  data-title="Ask Driftnote" data-greeting="Hi! Ask me about plans, pricing or privacy." data-color="#6d28d9"></script>
```

3. Publish the page as usual.

The bot reads the page's `<main>` and answers from it, so keep your pricing and FAQ as visible text. `data-title`, `data-greeting`, `data-color` and `data-position` change how it looks; `data-system` adds instructions. All options: [onetagai.com/docs](https://onetagai.com/docs).

Works on any landing page that lets you add a script tag: plain HTML, Carrd (Pro), Framer, Webflow, WordPress, Astro and so on.

## License

MIT
