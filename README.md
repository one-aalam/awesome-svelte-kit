# Awesome SvelteKit
SvelteKit is awesome. It's "the missing CLI" and the svelte team's favoured project structure, to build full-stack server rendered and static sites, with 
- File/Folder based routing
- focus on server-less _with adapters_
- API routes

and good baked-in conventions and constructs to support common web app needs. It's a successor to [Sapper](https://sapper.svelte.dev/) which served the aforementioned needs, with exception of adapters, which is special/unique(with no officially provided parallels in Next.js/Nuxt ecosystems yet) way to make vendor-agnostic, server-less first deployment concern a seamlessly integrated part of the framework. 

## ✍️ Blogs
### History & _The Why's?_ ###
- [A Short History of SvelteKit](https://dev.to/ajcwebdev/a-short-history-of-sveltekit-49lk)
- [What's the deal with SvelteKit?](https://svelte.dev/blog/whats-the-deal-with-sveltekit)
- [Virtual DOM is pure overhead](https://svelte.dev/blog/virtual-dom-is-pure-overhead) - A must read if you want to make sense of _why FE compiler frameworks?_
- [Svelte Kit, the first ‘serverless-first’ framework?](https://www.voorhoede.nl/en/blog/svelte-kit-the-first-serverless-first-framework/)
- [Would you use Sveltekit for production?](https://www.reddit.com/r/sveltejs/comments/qt14c6/would_you_use_sveltekit_for_production/)
- [My Evaluation of SvelteKit for Full-Stack Web App Development](https://cprimozic.net/blog/trying-out-sveltekit/)

### The _How To's?_
- [How to Create a Blog with SvelteKit and Strapi](https://strapi.io/blog/how-to-create-a-blog-with-svelte-kit-strapi)
- [A Beginner’s Guide to SvelteKit](https://www.sitepoint.com/a-beginners-guide-to-sveltekit/)
- [How to Make a Website with SvelteKit](https://prismic.io/blog/svelte-sveltekit-tutorial)
- [Simple Page Transitions with SvelteKit](https://dev.to/evanwinter/page-transitions-with-svelte-kit-35o6)
- [Theme Switch](https://dev.to/nico_bachner/sveltekit-theme-switch-a58)
- [DIY SvelteKit CDK adapter](https://dev.to/juranki/diy-sveltekit-cdk-adapter-3enp)
- [Build your next commerce store with SvelteKit](https://commercejs.com/blog/ecommerce-storefront-with-sveltekit/)
- [Use Apollo Client with SvelteKit to Query a GraphQL API](https://rodneylab.com/use-apollo-client-sveltekit/)
- [Make an RSS Feed for your SvelteKit Project](https://scottspence.com/posts/make-an-rss-feed-with-sveltekit)
- [Let's learn SvelteKit by building a static Markdown blog from scratch](https://joshcollinsworth.com/blog/build-static-sveltekit-markdown-blog)
- [Converting from Gridsome to SvelteKit](https://joshcollinsworth.com/blog/converting-from-gridsome-to-sveltekit)
- [SvelteKit and the "Client pattern"](https://retro.cloud/sveltekit-and-the-client-pattern/)
- [Simplify data fetching in SvelteKit with page endpoints](https://baptiste.devessier.fr/writing/simplify-data-fetching-in-sveltekit-with-page-endpoints/)
- [How to use Serverless Cloud with SvelteKit](https://www.serverless.com/blog/how-to-use-serverless-cloud-with-sveltekit)
- [Building a real-time websocket app using SvelteKit](https://www.inngest.com/blog/building-a-realtime-websocket-app-using-sveltekit)
- [How to use a Rust WebAssembly module in Svelte with Web Workers](https://martyjon.es/webassembly/rust/svelte/2021/11/28/svelte-wasm-workers-how-to.html)
- [Getting Started with KitQL and GraphCMS](https://scottspence.com/posts/getting-started-with-kitql-and-graphcms)

## 📹 Videos/Screencasts/Twitch
- [An Update on SvelteKit](https://www.youtube.com/watch?v=fnr9XWvjJHw&t=19101s) - Rich Harris on SvelteKit(SvelteSummit)
- [SvelteKit blog from Scratch](https://www.youtube.com/playlist?list=PLm_Qt4aKpfKi1LCngULWPrTEPxla8eGLr) (YouTube Playlist)
- [SvelteKit Firebase Auth](https://www.youtube.com/watch?v=XIiOhorRwUg&list=PLm_Qt4aKpfKhEzGutYRnqBOBgJ6WayTVg) (YouTube Playlist)
- [Svelte and SvelteKit - Why We Love It and Why You Should Try It](https://www.youtube.com/watch?v=KJ-qMlZnMCE)
- [Rich Harris - The Road to SvelteKit 1.0 ](https://www.youtube.com/watch?v=s6a1pbTVcUs)

## 🧶 Condensed Thought-pieces (Twitter Threads)
- [__Rich Harris__ on SvelteKit for SPAs](https://twitter.com/Rich_Harris/status/1376578502833606658)
- [__Mike__'s thoughts on maturity of Svelte/SvelteKit](https://twitter.com/htmleverything/status/1515000240134242309)

## 🗣️ Podcasts
- [Rebuilding LevelUpTuts using SvelteKit](https://share.transistor.fm/s/6316622d) ([@svelteradio](https://twitter.com/svelteradio)) - detail on the decisions and outcomes of migrating from React to Svelte

## 🏃 SvelteKit Starter Kits and Integrations
- [SvelteKit Auth](https://github.com/Dan6erbond/sk-auth) - Authentication library for use with SvelteKit featuring built-in OAuth providers and zero restriction customization(like NextAuth)
- [SvelteKit Starter Kit](https://github.com/one-aalam/svelte-starter-kit/tree/auth-supabase)(with [Supabase.io](https://supabase.io/) Auth, Storage, etc.)
- [SvelteKit with Magic Link](https://github.com/srmullen/sveltekit-magic)(with [magic.link](https://magic.link/)
- SvelteKit with Stripe [#1](https://github.com/srmullen/sveltekit-stripe) and [#2](https://github.com/joshnuss/svelte-stripe-js)
- [SvelteKit with Notion](https://github.com/one-aalam/svelte-notion-kit)
- [SvelteKit with Storybook](https://imfeld.dev/writing/sveltekit_with_storybook) (blog)
- [SvelteKit with Firebase](https://github.com/CaptainCodeman/sveltekit-example)
- [SvelteKit + Firebase Library](https://github.com/jacobbowdoin/sveltefirets)([docs](https://sveed.dev/docs/sveltefirets))
- [SvelteKit with Passport/oAuth2](https://www.npmjs.com/package/sveltekit-passport-oauth2)
- [SvelteKit with oAuth2](https://github.com/MacFJA/svelte-oauth2)
- [SvelteKit with NetlifyCMS](https://github.com/buhrmi/sveltekit-netlify-cms)
- [SvelteKit with Sanity](https://github.com/stephane-vanraes/demo-sveltekit-sanity/)
- [SvelteKit with Web3](https://github.com/wighawag/jolly-roger)
- [SvelteKit with Solana](https://github.com/silvestrevivo/solana-svelte-wallet)
- [SvelteKit with Metamask/Unlock-Protocol](https://github.com/novum-insights/sveltekit-unlock-firebase)
- [Swyxkit](https://swyxkit.netlify.app/)
- [SvelteKit Starter](https://github.com/navneetsharmaui/sveltekit-starter) - Starter project created with sveltekit, typescript, tailwindcss, postcss, husky, and storybook
- [SvelteKit with PostgREST](https://github.com/guyromm/svelte-postgrest-template) - Svelte/SvelteKit + PostgREST + EveryLayout + social auth starter template
- [SvelteKit on Edge(Vercel)](https://github.com/Rich-Harris/sveltekit-on-the-edge)
- [SvelteKit on Edge(Cloudflare Workers)](https://github.com/hazcod/cloudflare-workers-svelte)
- [SvelteKit with tRPC](https://github.com/icflorescu/trpc-sveltekit-example) - A sample SvelteKit application built to illustrate the usage of ✨ trpc-sveltekit
- [Svelte(Kit) TypeScript Showcase](https://github.com/ivanhofer/sveltekit-typescript-showcase)
- [Swyxkit](https://github.com/sw-yx/swyxkit) - An opinionated blog starter for SvelteKit + Tailwind + Netlify. Refreshed for 2022!
- [Urara](https://urara-docs.netlify.app/) - Sweet & Powerful SvelteKit Blog Template
- [SvelteKit with Email](https://github.com/miunau/worker-kit-email) - Develop transactional emails with SvelteKit on CloudFlare Workers
- [SvelteKit with Elementary Audio](https://github.com/bgins/svelte-elementary-template) - A SvelteKit template for Elementary Audio apps

## Adapters
- [Deno](https://github.com/pluvial/svelte-adapter-deno)
- [Firebase](https://github.com/jthegedus/svelte-adapter-firebase)
- [Azure SWA](https://github.com/geoffrich/svelte-adapter-azure-swa)
- [Express](https://github.com/mankins/svelte-adapter-express)
- [AppEngine](https://github.com/HalfdanJ/svelte-adapter-appengine)
- [Architect/Begin](https://github.com/architect/sveltekit-adapter)
- [Cloudflare](https://github.com/budgetdraw/sveltekit-cloudflare-adapter)
- [AWS Lambda](https://github.com/yarbsemaj/sveltekit-adapter-lambda)
- [Begin](https://github.com/ryanbethel/sveltekit-begin-adapter)
- [Nest.js](https://github.com/onivoro/svelte-adapter-nestjs)
- [AWS Lambda@Edge](https://github.com/efess/svelte-adapter-lambda-edge)
- [AWS CDK](https://github.com/juranki/sveltekit-cdk)
- [AWS CDK (DIY)](https://github.com/juranki/diy-sveltekit-cdk-adapter)
- [Wordpress Shortcode](https://github.com/tomatrow/sveltekit-adapter-wordpress-shortcode)
- [Github Pages](https://github.com/ota-meshi/svelte-adapter-ghpages)
- [HTML Templating Languages](https://github.com/idleberg/sveltekit-adapter-html-like)
- [Chrome Extension](https://github.com/michmich112/sveltekit-adapter-chrome-extension)
- [Bun](https://github.com/gornostay25/svelte-adapter-bun)
- [uWebSocket](https://github.com/UnlimitedBytes/adapter-uwebsockets) (in development)

## Meta-Meta
List of tools that simplify SvelteKit DX further
- [Svemix](https://github.com/svemix/svemix) Like Remix.run(Full-Stack addition) to SvelteKit. Write your server code inside svelte files, handle sessions, forms and SEO easily.
- [Svelte Zero API](https://github.com/ymzuiku/svelte-zero-api)
- [SvelteKit Zero API](https://github.com/Refzlund/sveltekit-zero-api/tree/master/lib)
- [KitDocs](https://kit-docs.svelteness.dev/docs/getting-started/introduction) - KitDocs makes it easy to build a documentation site with SvelteKit. You can think of it as a VitePress alternative for the people of Svelte.
- [Sveltin](https://github.com/sveltinio/sveltin) - The Smartest Way to Build SvelteKit powered static websites: a powerful CLI for your next SvelteKit static website

## Enhancers/Extensions
- [Themes - Dark Mode](https://github.com/beynar/svelte-themes)
- [SvelteKit SVG](https://github.com/poppa/sveltekit-svg) - SvelteKit plugin that makes it possible to import SVG files as Svelte components, inline SVG code or urls
- [Svelte Kit Cookie Session](https://github.com/pixelmund/svelte-kit-cookie-session) - Encrypted "stateless" cookie sessions for SvelteKit
- [tRPC SvelteKit](https://github.com/icflorescu/trpc-sveltekit)
- [Metawrite SDK](https://github.com/koodeau/metawrite)
- [SvelteKit Embed Components](https://github.com/spences10/sveltekit-embed)

## 📦 Built With Svelte
### Open-Source Projects
- [evidence.dev](https://github.com/evidence-dev/evidence) - Business Intelligence for Modern Data Teams
- [SveltePress](https://github.com/GeopJr/SveltePress) - documentation tool built on top of SvelteKit,
- [Dockit](https://github.com/crinklesio/dockit) - Markdown-based document site
- [Reddit Client](https://github.com/jatinhemnani01/reddit-client)
- [Workers KV GUI](https://github.com/cloudflare/workerskv.gui) - Desktop client for Cloudflare's Worker KV, built using SvelteKit and an Electron-like Rust based desktop app builder [Tauri](https://tauri.studio/en/) [(write-up)](https://css-tricks.com/how-i-built-a-cross-platform-desktop-application-with-svelte-redis-and-rust/)
- [MacOS Web](https://github.com/puruvj/macos-web) - Replicates some of the Mac OS(Monterey, at the time of writing)'s desktop experience on web, using Svelte!
- [Svelte Commerce](https://github.com/itswadesh/svelte-commerce)
- [Svelte Steps](https://github.com/shaozi/svelte-steps)
- [SvelteKit Snippets](https://github.com/stordahl/sveltekit-snippets)
- [Scores](https://betarena-scores-platform.herokuapp.com/)([code](https://github.com/Betarena/scores))
- [Naabu](https://github.com/naabu/naabu)
- [Coolify](https://github.com/coollabsio/coolify) - An open-source & self-hostable Heroku / Netlify alternative.
- [Beatbump](https://github.com/snuffyDev/Beatbump) - Alternative YouTube Music frontend built with Svelte/SvelteKit
- [Webstone](https://github.com/WebstoneHQ/webstone) - Start your next full-stack application with Webstone and configure it as you go.
- [SvelteFlow](https://github.com/doceazedo/svelte-flow) - 📈 Svelte library for building node-based graphs
- [Flowbite](https://github.com/edde746/flowbite-svelte-but-better) - Clone of flowbite-react but for Svelte without the jank of flowbite-svelte
- [Wordex](https://wordex.app/about) - Wordex clone built with SvelteKit
- [LearnAwesome](https://github.com/learn-awesome/learndb) - Curated learning resources with topics, formats, difficulty levels, expert reviews and metadata tags
- [Other Awesome Svelte-kit Projects](https://github.com/janosh/awesome-svelte-kit)

### Websites/Apps 
- [sveltesummit.com](https://sveltesummit.com/)
- [radiofrance.fr](https://www.radiofrance.fr/)
- [leveluptutorials.com](https://leveluptutorials.com/)
- [projectwallace.com](https://www.projectwallace.com/)
- [rykr.co](https://rykr.co/)
- [flayks.com](https://flayks.com/)
- [kineticsnow.com](https://www.kineticsnow.com/)
- [mortimerbaltus.com](https://mortimerbaltus.com/)
- [quickfantasystats.com](https://quickfantasystats.com/)
- [Files](https://files.community/)([source](https://github.com/files-community/website)) - 3rd Party File Manager for Windows 
- [Dragsters.vercel](https://inferno-dragsters.vercel.app/)
- [netimmo.ch](https://www.netimmo.ch/appartement-a-vendre-suisse)
- [bahaistudies.ca](https://2021.bahaistudies.ca/)
- [connorrothschild.com](https://connorrothschild.com)
- [blfcreative.dev](https://www.blfcreative.dev/)
- [base.report](https://base.report/)
- [ip.new](https://ip.new/)(just sub-domains)
- [teamtale.app](https://teamtale.app/)
- [limey.io](https://limey.io/)
- [stockanalysis.com](https://stockanalysis.com/)
- [app.calandrier.com](https://app.calandrier.com/)
- [kadium.kasper.space](https://kadium.kasper.space/)
- [fusepilot.com](https://fusepilot.com/)
- [prediabetes.guide](https://prediabetes.guide/)
- [moxiekb.com](https://moxiekb.com/)
- [see.net.ph](https://see.net.ph/)
- [enka.shinshin.moe](https://enka.shinshin.moe/)
- [siva.gg](https://siva.gg/)
- [cuddy.me](https://cuddy.me/)
