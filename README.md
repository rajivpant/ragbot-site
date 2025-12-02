# Ragbot Website

The informational website for Ragbot, an AI-augmented brain assistant.

**Live site:** [ragbot.ai](https://ragbot.ai)

## What is this?

This repository contains the source for ragbot.ai—the website for Ragbot, an open source AI assistant that combines large language models with Retrieval Augmented Generation (RAG).

## License

The website content and code are released under the MIT License.

## Deployment

This site is deployed on [Cloudflare Pages](https://pages.cloudflare.com/).

To deploy your own copy:

1. Fork this repository
2. Connect to Cloudflare Pages
3. Set build output directory to `/` (root)
4. No build command required—it's a static site

## Local Development

This is a static HTML/CSS site. No build process required.

```bash
# Serve locally (any static file server works)
python3 -m http.server 8000
# or
npx serve
```

Open http://localhost:8000

## Related Projects

- [Ragbot](https://github.com/rajivpant/ragbot) - The main application repository
- [RaGenie](https://github.com/rajivpant/ragenie) - Next-generation RAG platform
- [ragbot-data](https://github.com/rajivpant/ragbot-data) - Shared data repository (private)
