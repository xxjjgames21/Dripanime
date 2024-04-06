[![AnimeDexLite](https://github.com/TechShreyash/AnimeDexLite/assets/82265247/98c27bb6-c4a8-4224-983e-2bb21386032a)](https://animedex.pages.dev)

# AnimeDexLite v3.0

AnimeDexLite is a lightweight, fast, ad-free, and open-source web application built with pure HTML, CSS, and JS. It features a responsive design and utilizes data from Gogoanime and Anilist through the high-speed [AnimeDexApi](https://api.anime-dex.workers.dev).

![Page Views](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FTechShreyash%2FAnimeDexLite&count_bg=%2379C83D&title_bg=%23555555&icon=github.svg&icon_color=%23E7E7E7&title=Page+Views&edge_flat=false)

## 🌐 Demo

Explore AnimeDexLite via the following URLs:

- Main Website: [animedex.pages.dev](https://animedex.pages.dev) (Cloudflare)
- [animedex-lite.netlify.app](https://animedex-lite.netlify.app) (Netlify)
- [techshreyash.github.io/AnimeDexLite](https://techshreyash.github.io/AnimeDexLite) (Github Pages)
- [animedexlite.vercel.app](https://animedexlite.vercel.app) (Vercel)

## 🔥 Host Your Own

### 🆓 Free Hostings

You have various options for free hosting services:

- Cloudflare, Netlify, Github Pages, Vercel, Render
- Plus, search online for more "Free Static Website Hostings"

### 💰 Paid Hostings

For paid hosting, look for services supporting HTML files. Search for "Static Website Hostings" online.

### 🏠 Run On Your PC

To run AnimeDexLite locally:

- Download this repository
- Open the `index.html` file in a browser

## 🚀 Deploy AnimeDexApi (Required)

- Deploy AnimeDexApi for AnimeDexLite to function
- You can deploy AnimeDexApi for free on Cloudflare Workers
- [AnimeDexApi](https://github.com/TechShreyash/AnimeDexApi): API for anime data retrieval.

<details>
  <summary>Add your API to your site</summary>

> - Navigate to the [js folder](js), locate the AvailableServers variable at the top of each JS file
> - By default, it is set as `const AvailableServers = ["https://api.anime-dex.workers.dev"];`
> - Replace `https://api.anime-dex.workers.dev` with your API domain
> - You can add multiple API domains, separating them with commas

</details>

## 🎯 Deploy AnimeDex Proxy (Recommended)

- [AnimeDexProxy](https://github.com/TechShreyash/CloudflareWorker/tree/main/animedexproxy): Proxy to bypass CORS errors.

<details>
  <summary>Add your Proxy to your site</summary>

> - Navigate to the [js folder](js), locate the ProxyApi variable at the top of each JS file
> - By default, it is set as `const ProxyApi = "https://proxy.techzbots1.workers.dev/?u="`
> - Replace `https://proxy.techzbots1.workers.dev` with your API domain
> - Ensure to include `/?u=` in the URL

</details>

## 🔔 Join For Latest Updates

Stay updated by joining our channels/groups:

[![Telegram Channel](https://img.shields.io/static/v1?label=Join&message=Telegram%20Channel&color=blueviolet&style=for-the-badge&logo=telegram&logoColor=violet)](https://telegram.me/TechZBots) [![Telegram Group](https://img.shields.io/static/v1?label=Join&message=Telegram%20Group&color=blueviolet&style=for-the-badge&logo=telegram&logoColor=violet)](https://telegram.me/TechZBots_Support)
