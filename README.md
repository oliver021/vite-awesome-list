# Introduction
[Vite](https://vitejs.dev/) is a modern frontend build tool that has gained popularity for its **blazing fast development experience** and very simple progrssive way to set your workflow to build web apps.
---
# ⚡ Vite vs Webpack vs Parcel

Compared to traditional bundlers like **Webpack** and **Parcel**, Vite provides **instant hot reload**, **zero-config setup**, and **optimized builds** using Rollup. If you're starting a new project, you might wonder: _Should I use Vite over Webpack or Parcel?_ Let's compare them.

## 🔍 Comparison Table

| Feature               | **Vite** ⚡ | **Webpack** 🏗️ | **Parcel** 📦 |
|----------------------|------------|---------------|---------------|
| **Release Year**     | 2020       | 2012          | 2017          |
| **Speed**           | ⚡ Super fast (ESM + optimized HMR) | 🐢 Slow in dev (full recompilation) | 🚀 Fast, but heavier than Vite |
| **Dev Server**      | Built-in server with native ES Modules | Continuous build with HMR | Fast server with HMR |
| **Build Performance** | Fast with Rollup | Slow if not optimized | Optimized with automatic caching |
| **Configuration**   | Minimal / almost zero config | Complex (requires `webpack.config.js`) | Minimal setup |
| **Hot Module Reload (HMR)** | Instant updates | Slower in large projects | Good, but not as fast as Vite |
| **TypeScript Support** | Native | Requires additional setup | Native |
| **Code Splitting**  | Yes (via Rollup) | Yes (via plugins) | Yes (automatic) |
| **React, Vue, Svelte Support** | Native with templates | Requires setup | Auto-detects frameworks |
| **Plugin Ecosystem** | Uses Rollup plugins | Extensive ecosystem | Fewer plugins than Webpack |
| **Best for**        | Modern apps, fast prototyping | Large-scale apps with deep customization | Small-to-medium projects |

## 🚀 Why Vite?

### ✅ **Super Fast Development**
Vite uses **native ES Modules (ESM)** and **Hot Module Replacement (HMR)**, making it significantly faster than Webpack or Parcel. Development servers start **instantly**, and changes reflect **immediately**.

### ✅ **Zero Config & Simplicity**
With Vite, there’s **no need** for extensive configuration. It works out-of-the-box for **React, Vue, Svelte, and more**. Just install and start coding.

### ✅ **Optimized Production Builds**
Vite uses **Rollup** for highly optimized **tree-shaking and code-splitting**, resulting in **smaller, faster** production builds.

### ✅ **Better DX (Developer Experience)**
With instant server startup, faster builds, and easier debugging, Vite provides one of the **best developer experiences**.

## 🌟 Awesome Vite Resources

🔹 **Official Vite Docs** → [https://vitejs.dev/](https://vitejs.dev/)
🔹 **Vite Awesome List** → [https://github.com/vitejs/awesome-vite](https://github.com/vitejs/awesome-vite)
🔹 **Vite + React Starter** → [https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react)
🔹 **Vite + Vue Starter** → [https://github.com/vitejs/vite/tree/main/packages/create-vite/template-vue](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-vue)
🔹 **Vite Plugin Ecosystem** → [https://vite-rollup-plugins.patak.dev/](https://vite-rollup-plugins.patak.dev/)


## Plugins

### Framework-agnostic Plugins

#### Integrations

- [@vitejs/plugin-legacy](https://github.com/vitejs/vite/tree/main/packages/plugin-legacy) - Legacy browser support.
- [vite-plugin-pwa](https://github.com/antfu/vite-plugin-pwa) - Zero-config PWA.
- [vite-plugin-windicss](https://github.com/windicss/vite-plugin-windicss) - Windi CSS integration.
- [vite-plugin-node](https://github.com/axe-me/vite-plugin-node) - Integration with Node.js backend servers.
- [vite-plugin-cesium](https://github.com/nshen/vite-plugin-cesium) - Integration with Cesium library.
- [vite-plugin-linter](https://bitbucket.org/unimorphic/vite-plugin-linter) - Extensible linter framework that shows the linting output in the Vite output and the browser console, includes ESLint & TypeScript ootb.
- [vite-plugin-checker](https://github.com/fi3ework/vite-plugin-checker) - Fast run checkers (TypeScript/VLS/vue-tsc, etc.) in worker threads with overlay and terminal hint.
- [vite-plugin-tauri](https://github.com/amrbashir/vite-plugin-tauri) - Integrate Tauri in a Vite project to build cross-platform apps.
- [vite-plugin-federation](https://github.com/originjs/vite-plugin-federation) - Support Module Federation, Inspired by Webpack Module Federation feature.
- [vite-plugin-wasm-pack](https://github.com/nshen/vite-plugin-wasm-pack) - Integration with rust [wasm-pack](https://github.com/rustwasm/wasm-pack), the simple way.
- [vite-plugin-comlink](https://github.com/mathe42/vite-plugin-comlink) - Use WebWorkers with the power of [Comlink](https://github.com/GoogleChromeLabs/comlink) to make them enjoyable.
- [vite-plugin-sass-dts](https://github.com/activeguild/vite-plugin-sass-dts) - This is a plugin that automatically creates a type file when using the CSS module type-safely.
- [vite-plugin-ali-oss](https://github.com/xiaweiss/vite-plugin-ali-oss) - Upload the production files bundled in the project to Ali OSS, except for HTML.
- [vite-plugin-webfont-dl](https://github.com/feat-agency/vite-plugin-webfont-dl) - Downloads and injects webfonts (Google Fonts) to improve website's performance.
- [vite-plugin-babel](https://github.com/owlsdepartment/vite-plugin-babel) - Babel integration for both build and server to support f.ex. decorators or class fields in pure JS/JSX files.
- [vite-plugin-electron](https://github.com/electron-vite/vite-plugin-electron) - Integrate Vite and Electron.
- [vite-plugin-optimizer](https://github.com/vite-plugin/vite-plugin-optimizer) - Manually Pre-Bundling.
- [vite-plugin-babel-compiler](https://github.com/yzydeveloper/vite-plugin-babel-compiler) - The plugin works with Babel compiler.
- [vite-plugin-commonjs](https://github.com/vite-plugin/vite-plugin-commonjs) - A pure JavaScript implementation for CommonJs.
- [vite-plugin-mpa-plus](https://github.com/yzydeveloper/vite-plugin-mpa-plus) - More flexible MPA (multi-page application) supports html templates, path rewriting.
- [vite-plugin-multi-pages](https://github.com/Miofly/vite-plugin-multi-pages) - Multi Pages Support，can build src/pages anyPage，can set prefixName.
- [vite-plugin-html-template-mpa](https://github.com/Miofly/vite-plugin-html-template-mpa) - Multi Pages Common template support.
- [vite-plugin-vconsole-mpa](https://github.com/Miofly/vite-plugin-vconsole-mpa) - Multi Pages Vconsole supports，simple config.
- [vite-plugin-browser-sync](https://github.com/Applelo/vite-plugin-browser-sync) - BrowserSync.
- [vite-plugin-jspm](https://github.com/jspm/vite-plugin-jspm) - Resolves dependencies independently from CDN providers using import maps and es-module-shims.
- [vite-plugin-env-switch](https://github.com/PengBoUESTC/vite-plugin-env-switch) - Switch project env and restart vite server without command line operation.
- [vite-plugin-virtual-mpa](https://github.com/emosheeep/vite-plugin-virtual-mpa) - Out-of-box MPA plugin, with html template engine and virtual files support, which generate multiple files using only one template.
- [vite-plugin-stylelint](https://github.com/ModyQyW/vite-plugin-stylelint) - Runs Stylelint synchronously/asynchronously.
- [Vite-plugin-graphiql](https://github.com/mammadataei/vite-plugin-graphiql) - Integration for GraphiQL IDE.
- [vite-plugin-graphql-server](https://github.com/mammadataei/vite-plugin-graphql-server) - Bootstrap a local GraphQL server for testing and documentaion.
- [unplugin-fonts](https://github.com/cssninjaStudio/unplugin-fonts) - Load font from Typekit, Google Fonts, Fontsource or your own custom one.
- [unplugin-config](https://github.com/kirklin/unplugin-config) - Configuration file generator for web apps, allowing external customization of global variables without repackaging.
- [vite-plugin-svg-spritemap](https://github.com/g-makarov/vite-plugin-svg-spritemap) - Generates a SVG spritemap from multiple .svg files.
- [vite-plugin-dc](https://github.com/dvgis/vite-plugin-dc) - Integration with @dvgis/dc-sdk library.
- [@spiriit/vite-plugin-svg-spritemap](https://github.com/SpiriitLabs/vite-plugin-svg-spritemap) - Pack your SVG files in one spritemap file and use them with `<svg>`/`<img>` and directly in your CSS.
- [vite-plugin-auto-mpa-html](https://github.com/iamspark1e/vite-plugin-auto-mpa-html) - A file directory-based automated multi-page build plugin that supports HTML templates using EJS.
- [vite-plugin-cloudflare-functions](https://github.com/yjl9903/vite-plugin-cloudflare-functions) - Cloudflare pages function integration.
- [@storybook/builder-vite](https://github.com/storybookjs/storybook/tree/next/code/builders/builder-vite/) - Storybook builder.
- [@builder.io/partytown](https://github.com/BuilderIO/partytown) - Relocate resource intensive third-party scripts off of the main thread and into a web worker.
- [vite-plugin-dynamic-proxy](https://github.com/zjpzjp/vite-plugin-debug-proxy) - Automatically configure reverse proxies based on URL parameters.
- [unplugin-auto-export](https://github.com/coderhyh/unplugin-auto-export) - Automates the maintenance of export statements in the index.ts file.
- [remix-development-tools](https://github.com/forge42dev/Remix-Dev-Tools) - Plugin for Remix.run development tools.
- [vite-plugin-legacy-swc](https://github.com/CyanSalt/vite-plugin-legacy-swc) - Legacy browser support with SWC.
- [vite-plugin-biome](https://github.com/skrulling/vite-plugin-biome) - Biome linter.
- [vite-plugin-oxlint](https://github.com/52-entertainment/vite-plugin-oxlint) - Oxlint linter.
- [@tomjs/vite-plugin-electron](https://github.com/tomjs/vite-plugin-electron) - Easily develop `Electron` applications.
- [@tomjs/vite-plugin-vscode](https://github.com/tomjs/vite-plugin-vscode) - Easily use web frameworks to develop `VSCode Extension`'s `Webview`, and support `HMR` and `Debug`.
- [vite-plugin-px-rem-vw](https://github.com/zscumt123/vite-plugin-px-rem-vw) - Integrate PostCSS plugin pxTorem and pxTovw.
- [vite-plugin-mpg](https://github.com/just-ads/vite-plugin-multi-page) - Simple configuration of multi page applications.
- [vite-plugin-pagefind](https://github.com/Hugos68/vite-plugin-pagefind) - Integrate `pagefind` search.
- [@mistjs/vite-plugin-px2viewport](https://github.com/aibayanyu20/vite-plugins/tree/main/packages/px2viewport) - A plugin that automatically converts inline styles and style files from px units to vw units.
- [vite-multiple-assets](https://github.com/nguyenbatranvan/vite-multiple-assets) - Add support for multiple public asset directories.
- [vite-create-production-server-plugin](https://github.com/jrtderonde/vite-create-production-server-plugin) - Spin up a production HTTP serve after build.
- [vite-plugin-eslint2](https://github.com/ModyQyW/vite-plugin-eslint2) - Runs ESLint synchronously/asynchronously.
- [vite-plugin-page-html](https://github.com/Marinerer/vite-plugins/tree/main/packages/page-html) - Multi-page generic template plugin, support `ejs` template syntax. Similar to `vue-cli` pages configuration.
- [vite-plugin-vanilla](https://github.com/Marinerer/vite-plugins/tree/main/packages/vanilla) - Vanilla multi-page web development mode.
- [genaicode/vite-plugin](https://github.com/gtanczyk/genaicode/tree/master/src/vite-genaicode/) - A plugin that embeds an AI coding assistant into the app UI.
- [vite-plugin-year](https://github.com/8hobbies/vite-plugin-year) - Inserts the current year to the HTML file during build. Useful for adding a copyright year to the HTML file.
- [vite-plugin-llms](https://github.com/saschaseniuk/vite-plugin-llms) - Integration for the llms.txt specification supporting AI optimized content alongside application routes.
- [module-federation/vite](https://github.com/module-federation/vite) - Official Module Federation integration, enabling dynamic remote module loading.

#### Loaders

- [unplugin-icons](https://github.com/antfu/unplugin-icons) - Access thousands of icons as components.
- [vite-imagetools](https://github.com/JonasKruckenberg/vite-imagetools) - Load and transform images using url query parameters.
- [vite-plugin-radar](https://github.com/stafyniaksacha/vite-plugin-radar) - All in one analytics loader (with 7+ providers supported).
- [vite-plugin-glsl](https://github.com/UstymUkhman/vite-plugin-glsl) - Import shader file chunks.
- [vite-plugin-svgo](https://github.com/r3dDoX/vite-plugin-svgo) - Load SVGs as plain string and transform with SVGO library.
- [vite-plugin-remark-rehype](https://github.com/y-nk/vite-plugin-remark-rehype) - Loads and transform markdown files using the unified ecosystem.
- [vite-plugin-php](https://github.com/donnikitos/vite-plugin-php) - Load and process PHP-entry files instead of default index.html.
- [vite-plugin-lqip](https://github.com/drwpow/vite-plugin-lqip) - Generate low quality image placeholders (LQIP).
- [vite-plugin-ms-clarity](https://github.com/KermanX/vite-plugin-ms-clarity) - Inject the Microsoft Clarity script to `index.html`.
- [@cyco130/vite-plugin-mdx](https://github.com/cyco130/vite-plugin-mdx) - Import MDX.
- [vite-awesome-svg-loader](https://github.com/matafokka/vite-awesome-svg-loader) - Imports SVGs as source code, base64 and data URI. Preserves stroke width, replaces colors with currentColor. Optimizes SVGs with SVGO. Creates SVG sprites.
- [vite-plugin-dir2json](https://github.com/buddywang/vite-plugin-dir2json) - Convert the directory structure into json data containing supported file paths.
- [@responsive-image/vite-plugin](https://github.com/simonihmig/responsive-image) - Transform and generate optimized responsive images (WebP, AVIF) and LQIP placeholders for use with image components.

#### Bundling

- [rollup-plugin-critical](https://github.com/nystudio107/rollup-plugin-critical) - Generate critical CSS.
- [vite-plugin-dts](https://github.com/qmhc/vite-plugin-dts) - Generate declaration files from `.ts` or `.vue` source files for lib.
- [vite-compression-plugin](https://github.com/XeryYue/vite-compression-plugin) - Use Node.js stream compress file to gzip or more.
- [vite-plugin-chunk-split](https://github.com/sanyuan0704/vite-plugin-chunk-split) - Automatically code splitting, support unbundle in production.
- [vite-plugin-static-copy](https://github.com/sapphi-red/vite-plugin-static-copy) - Copy files and folders.
- [vite-plugin-zip-file](https://github.com/Ssis53/vite-plugin-zip) - Compress files or folders into zip.
- [vite-plugin-zip-pack](https://github.com/7th-Cyborg/vite-plugin-zip-pack) - Pack distribution/build folder into a zip file.
- [vite-plugin-cp](https://github.com/fengxinming/vite-plugins/tree/main/packages/vite-plugin-cp) - Copy files after building bundles.
- [unplugin-imagemin](https://github.com/ErKeLost/unplugin-imagemin) - High performance compressed Picture based on squoosh and sharp.
- [vite-plugin-image-optimizer](https://github.com/FatehAK/vite-plugin-image-optimizer) - Optimize (compress) your image assets using Sharp.js and SVGO at build time.
- [vite-plugin-no-bundle](https://github.com/ManBearTM/vite-plugin-no-bundle) - Generate unbundled code for use with native ESM or other bundlers.
- [vite-plugin-css-injected-by-js](https://github.com/marco-prontera/vite-plugin-css-injected-by-js) - Takes the CSS and adds it to the page through the JS.
- [unplugin-zip-pack](https://github.com/iamspark1e/unplugin-zip-pack) - Zip your dist with filter function support.
- [vite-plugin-singlefile](https://github.com/richardtallent/vite-plugin-singlefile) - Inline all JavaScript and CSS resources directly into the final `dist/index.html` file.
- [vite-plugin-node-polyfills](https://github.com/davidmyersdev/vite-plugin-node-polyfills) - Polyfill Node's Core Modules for browser environments.
- [vite-plugin-cdn2](https://github.com/nonzzz/vite-plugin-cdn) - Replace module with CDN.
- [vite-plugin-bundle-prefetch](https://github.com/dreambo8563/vite-plugin-bundle-prefetch) - Inject prefetch assets into `index.html`.
- [vite-plugin-imagemin](https://github.com/vHeemstra/vite-plugin-imagemin) - Optimize and compress your image assets and optionally create WebP/AVIF.
- [vite-plugin-lib-types](https://github.com/keuby/vite-plugin-lib-types) - Generate DTS file while building library.
- [vite-plugin-minipic](https://github.com/60late/vite-plugin-minipic) - Efficient image compression tool.
- [vite-plugin-robots](https://github.com/kolirt/vite-plugin-robots) - Generating `robots.txt`.
- [vite-plugin-bundle-obfuscator](https://github.com/z0ffy/vite-plugin-bundle-obfuscator) - JavaScript obfuscator.
- [@yuanjianming/unplugin-image-convert](https://github.com/yuan66-hub/unplugin-image-convert) - Image multi format conversion plugin based on sharp.js.
- [vite-plugin-dynamic-chunk](https://github.com/MrQinYQ/vite-plugin-dynamic-chunk) - Split dependencies between entry and dynamic entry, and merge small chunks.
- [@yuanjianming/unplugin-compress-svga](https://github.com/yuan66-hub/unplugin-compress-svga) - Compress SVGA.
- [@yuanjianming/unplugin-font-spider](https://github.com/yuan66-hub/unplugin-font-spider) - A webfont compression plugin.
- [vite-plugin-static-filehash](https://github.com/MrQinYQ/vite-plugin-static-filehash) - It can help the program improve the cache hit rate.
- [vite-plugin-singlefile-compression](https://github.com/bddjr/vite-plugin-singlefile-compression) - Compress all assets and embeds them into `dist/index.html`, making it convenient to share as a single HTML file.
- [vite-plugin-builder](https://github.com/yracnet/vite-plugin-builder) - Enable dual compilation for Server-Side Rendering (SSR) and Client-Side Rendering (CSR).

#### Transformers

- [vite-plugin-html](https://github.com/anncwb/vite-plugin-html) - Plugin to minimize and use ejs template syntax in `index.html`.
- [vite-plugin-ts-nameof](https://github.com/Shinigami92/vite-plugin-ts-nameof) - Ability to resolve [nameof](https://github.com/dsherret/ts-nameof) in TypeScript.
- [vite-plugin-handlebars](https://github.com/alexlafroscia/vite-plugin-handlebars) - Process HTML files with Handlebars.
- [vite-plugin-virtual-html](https://github.com/Windson1806/vite-plugin-virtual-html) - Make Vite MPA consistent with `@vue/cli`.
- [vite-plugin-content](https://github.com/originjs/origin.js/tree/main/packages/vite-plugin-content) - Convert `yaml`, `xml`, `ini`, `toml`, `csv`, `plist` and `properties` files to ES6 modules.
- [vite-plugin-require](https://github.com/wangzongming/vite-plugin-require) - A Vite plugin that supports `require` by code transforming.
- [vite-plugin-global-style](https://github.com/originjs/origin.js/tree/main/packages/vite-plugin-global-style) - Deal with global styles for CSS, SASS, LESS and Stylus.
- [vite-plugin-shared-modules](https://github.com/zheeeng/vite-plugin-shared-modules) - Share node_modules in monorepos.
- [vite-plugin-pug-transformer](https://github.com/TheSeally/vite-plugin-pug-transformer) - Pug template engine support.
- [@import-meta-env/unplugin](https://github.com/runtime-env/import-meta-env) - Inject environment variables into the `import.meta.env` object after building the application instead of statically replacing it during production.
- [@modyfi/vite-plugin-yaml](https://github.com/Modyfi/vite-plugin-yaml) - Transform YAML files to ESM with schema validation and error reporting.
- [vite-plugin-html-inject](https://github.com/donnikitos/vite-plugin-html-inject) - Split the `index.html` into smaller reusable pieces.
- [unplugin-inject-preload](https://github.com/Applelo/unplugin-inject-preload) - Inject `<link rel="preload">` to your `index.html` based on your build assets.
- [@vituum/vite-plugin-handlebars](https://github.com/vituum/vite-plugin-handlebars) - Handlebars template engine support, transforms `.hbs` templates to `.html`.
- [@vituum/vite-plugin-pug](https://github.com/vituum/vite-plugin-pug) - Pug template engine support, transforms `.pug` templates to `.html`.
- [@vituum/vite-plugin-nunjucks](https://github.com/vituum/vite-plugin-nunjucks) - Nunjucks template engine support, transforms `.njk` templates to `.html`.
- [@vituum/vite-plugin-liquid](https://github.com/vituum/vite-plugin-liquid) - Liquid template engine support, transforms `.liquid` templates to `.html`.
- [@vituum/vite-plugin-twig](https://github.com/vituum/vite-plugin-twig) - Twig template engine support, transforms `.twig` templates to `.html`.
- [@vituum/vite-plugin-latte](https://github.com/vituum/vite-plugin-latte) - Latte template engine support, transforms `.latte` templates to `.html`.
- [@vituum/vite-plugin-posthtml](https://github.com/vituum/vite-plugin-posthtml) - PostHTML support, transforms syntax to `.html`.
- [@vituum/vite-plugin-juice](https://github.com/vituum/vite-plugin-juice) - Juice support, transforms `.css` to inline styles in `.html`.
- [vite-plugin-version-mark](https://github.com/ZhongxuYang/vite-plugin-version-mark) - Automatically use `package version` / `git commit` / `custom` to be inserted into your project as a unique identifier for the project version.
- [vite-plugin-css-export](https://github.com/shixuanhong/vite-plugin-css-export) - Export variables from CSS to JavaScript, and support nested rules.
- [vite-plugin-optimize-css-modules](https://github.com/Simonwep/vite-plugin-optimize-css-modules) - Generate the smallest possible CSS-Classes when CSS-Modules are used.
- [vite-plugin-generate-html](https://github.com/gedouu/vite-plugin-generate-html) - Define separate output files for JavaScript and CSS bundles.
- [vite-plugin-turbo-console](https://github.com/yuyinws/vite-plugin-turbo-console) - Enhance the readability of `console.log()`.
- [vite-plugin-html-injection](https://github.com/altrusl/vite-plugin-html-injection) - Inject HTML, JavaScript and CSS code snippets into the `index.html`.
- [vite-plugin-typescript-transform](https://github.com/herberttn/vite-plugin-typescript-transform) - Applies the TypeScript compiler during Vite's transform build phase.
- [vite-plugin-public-typescript](https://github.com/hemengke1997/vite-plugin-public-typescript) - Inject Typescript into `index.html`.
- [unplugin-generate-component-name](https://github.com/CCherry07/unplugin-generate-component-name) - Automatically generate component's name.
- [@laynezh/vite-plugin-lib-assets](https://github.com/laynezh/vite-plugin-lib-assets) - Extracts resource files referenced in `library mode` instead of embedded them as base64.
- [css-media-splitter/vite-plugin](https://github.com/levchak0910/css-media-splitter) - Extracts all `@media` At-rules into a dedicated `.css` files and download it only when matches the media query.
- [@tomjs/vite-plugin-html](https://github.com/tomjs/vite-plugin-html) - Support compression, loading, CDN and others for `index.html`.
- [@tomjs/vite-plugin-iconify](https://github.com/tomjs/vite-plugin-iconify) - Inject the global variable `IconifyProviders` into `index.html` for `iconify`, and support local area network and custom url.
- [vite-plugin-icons-spritesheet](https://github.com/forge42dev/vite-plugin-icons-spritesheet) - Generate a spritesheet and TypeScript types from SVG icons by listening to the icons folder changes.
- [vite-plugin-abbrlink](https://github.com/tangerball/abbrlink/tree/master/packages/vite-plugin-abbrlink#readme) - Add the abbrlink attribute to the `markdown` file in the specified directory.
- [vite-plugin-native](https://github.com/vite-plugin/vite-plugin-native) - Supports Node/Electron C/C++ native addons.
- [@yoichiro/vite-plugin-handlebars](https://github.com/yoichiro/vite-plugin-handlebars) - Import of Handlebars templates `.hbs` as ES Modules.
- [vite-plugin-magic-preloader](https://github.com/cszhjh/vite-plugin-magic-preloader) - Generate `<link rel="prefetch" />` or `<link rel="preload" />` tags through magic comments and inject them into `index.html`.
- [vite-plugin-replace-lodash](https://github.com/mingtianyihou33/vite-plugin-replace-lodash) - Replacing the import of `lodash` with `lodash-es` is more beneficial to tree-shaking.
- [vite-plugin-dynamic-prefetch](https://github.com/Linh-Tran-0312/vite-plugin-dynamic-prefetch) - Inject `<link rel="prefetch" />` tags into the HTML file for dynamic modules at runtime.
- [vite-plugin-material-symbols](https://github.com/RobinTail/vite-plugin-material-symbols) - Selective loading of Material Symbols font icons based on source code analysis.
  
  #### Security

- [vite-plugin-csp-guard](https://github.com/RockiRider/csp/tree/main/packages/vite-plugin-csp-guard) - Lets you configure a Content Security Policy to your project, supports all directives and hashing.
- [vite-plugin-csp](https://github.com/maccuaa/vite-plugin-csp) - Content Security Policy (CSP) for SPA. Automatically calculates asset hashes (SRI), detects Google Fonts. Support `Bun` and `Node.js` runtimes.

---

> 💡 Just a little bit more.

<!--lint disable awesome-list-item-->

#### Integrations

- ![v3] [@vitejs/plugin-vue](https://github.com/vitejs/vite-plugin-vue) - Official Vue 3 support.
- ![v3] [@vitejs/plugin-vue-jsx](https://github.com/vitejs/vite-plugin-vue/tree/main/packages/plugin-vue-jsx) - Official Vue 3 JSX support.
- ![v2] [@vitejs/plugin-vue2](https://github.com/vitejs/vite-plugin-vue2) - Official Vue 2 support.
- ![v2] [@vitejs/plugin-vue2-jsx](https://github.com/vitejs/vite-plugin-vue2-jsx) - Official Vue 2 JSX support.
- ![v2] [vite-plugin-vue2](https://github.com/underfin/vite-plugin-vue2) - Vue 2 integration.
- ![v2] [unplugin-vue2-script-setup](https://github.com/antfu/unplugin-vue2-script-setup) - Enabling `<script setup>` syntax for Vue 2.

#### Routing

- ![v23] [vite-plugin-pages](https://github.com/hannoeru/vite-plugin-pages) - File system based route generator.
- ![v3] [v-route-generate](https://github.com/weiquanju/v-route-generate) - A tool to generate routes.
- ![v3] [unplugin-vue-router](https://github.com/posva/unplugin-vue-router) - Official experimental file based routing.
- ![v3] [vite-plugin-vue-routes](https://github.com/Vanilla-IceCream/vite-plugin-vue-routes) - File-based routing, similar to SvelteKit and Next.js App Router.

#### Loaders

- ![v23] [vite-plugin-md](https://github.com/antfu/vite-plugin-md) - Markdown as Vue components / Vue components in Markdown.
- ![v3] [vite-svg-loader](https://github.com/jpkleemans/vite-svg-loader) - Load SVG files as Vue components.
- ![v2] [vite-plugin-vue2-svg](https://github.com/pakholeung37/vite-plugin-vue2-svg) - Load SVG files as Vue components.
- ![v3] [unplugin-svg-component](https://github.com/Jevon617/unplugin-svg-component) - Load SVG files as a Vue component, supporting svg file HMR and Typescript intelligence prompt.
- ![v23] [vite-plugin-markdown-mermaid](https://github.com/KermanX/vite-plugin-markdown-mermaid) - Load Markdown files, with Mermaid rendering support.
- ![v3] [vite-plugin-style-vw-loader](https://github.com/gitboyzcf/vite-plugin-style-vw-loader) - Converting the inline style px to vw.

#### SSG

- ![v3] [vite-ssg](https://github.com/antfu/vite-ssg) - Server-side generation.

#### Ecosystem

- ![v3] [unplugin-vue-i18n](https://github.com/intlify/bundle-tools/tree/main/packages/unplugin-vue-i18n) - Integration for Vue I18n.
- ![v3] [vite-plugin-i18n-resources](https://github.com/fvena/vite-plugin-i18n-resources) - Load i18n translation message files.
- ![v3] [vite-plugin-i18n-autoimport](https://github.com/PengBoUESTC/vite-plugin-i18n-autoimport) - Auto import i18n config file for components.

#### Transformers

- ![v3] [vite-plugin-md-preview](https://github.com/JasKang/vite-plugin-md-preview) - Markdown code preview.
- ![v3] [vite-plugin-vue-preview](https://github.com/liting-yes/vite-plugin-vue-preview) - Code preview for Vue SFC in Markdown, supports online editing.
- ![v3] [vite-plugin-vue-css-modules](https://github.com/zeokku/vite-plugin-vue-css-modules) - Implicit usage of CSS Modules for template and script SFC tags with static replacement.


### Libraries

- [Vike](https://github.com/vikejs/vike) - Like Nuxt/Next.js but as a do-one-thing-do-it-well plugin. ![react] ![vue3] ![vue2] ![svelte]
- [ssr](https://github.com/zhangyuang/ssr) - A Server Side Rendering framework combined with Webpack/Vite. ![react] ![vue3] ![vue2]
- [vavite](https://github.com/cyco130/vavite) - A tool for developing and building server-side applications with live reloading capabilities.
- [vue-ssr](https://github.com/bistroo/vue-ssr) - Minimalistic wrapper to develop and run SSR powered Vue apps. ![vue3]
- [vite-ssr-boost](https://github.com/Lomray-Software/vite-ssr-boost) - Server side rendering library for create awesome app based on `react-router`. ![react]
- [SSRx](https://github.com/marbemac/ssrx) - A thin layer on top of Vite to build modern SSR apps with a delightful DX.
- [Vinxi](https://github.com/nksaraf/vinxi) - The Full Stack JavaScript SDK. Allows adding SSR to a Vite app.
- [domco](https://github.com/rossrobino/domco) - Minimal full-stack JavaScript. Turns a Vite app into a full-stack application with minimal dependencies.

### Frameworks

- [Rakkas](https://github.com/rakkasjs/rakkasjs) - React framework inspired by Next.js and SvelteKit. ![react]
- [Vise](https://github.com/stauren/vise-ssr) - SSR framework with server hooks. ![react] ![vue3]
- [@fastify/fastify-dx](https://github.com/fastify/fastify-dx) - Allowing you to serve static or live (SSR).
- [vite-plugin-vercel](https://github.com/magne4000/vite-plugin-vercel) - Vercel adapter.
- [vite-vlugin-vercel-skew-protection](https://github.com/bitttttten/vite-vlugin-vercel-skew-protection) - Helps configure Vercel Skew Protection.

<!--lint enable awesome-list-item-->

## Integrations with Backends

### Adobe Experience Manager

### Craft CMS

- [Craft Vite](https://github.com/nystudio107/craft-vite) - Plugin for integration with Craft CMS.

### Django

- [django-vite](https://github.com/MrBin99/django-vite) - Integration for Django applications.
- [django-vite-plugin](https://github.com/protibimbok/django-vite-plugin) - Integration for Django applications including vite plugin.

### Flask

- [Flask-Vite](https://pypi.org/project/flask-vite/) - Integration with Flask.

### Ruby on Rails

- [vite-plugin-ruby](https://github.com/ElMassimo/vite_ruby/tree/main/vite-plugin-ruby) - Configuration for Ruby backends.
- [Vite Ruby](https://github.com/ElMassimo/vite_ruby) - Integration for Rails, Hanami, Padrino, and Rack apps.

### Laravel

- [Laravel Vite](https://github.com/innocenzi/laravel-vite) - Integration for the Laravel framework.
- [Laravel Vite Plugin](https://github.com/laravel/vite-plugin) - Laravel official plugin for Vite.

### CakePHP

- [cakephp-vite](https://github.com/passchn/cakephp-vite) - Integration for CakePHP.

### WordPress

- [wordpress-vite-assets](https://github.com/idleberg/php-wordpress-vite-assets) - Integration for WordPress themes.
- [Kima](https://github.com/axelilali/kima) - Starter theme with Twig.
- [WordPlate](https://github.com/vinkla/wordplate) - Starter app with Composer.

### TYPO3 CMS

- [vite-plugin-typo3](https://github.com/s2b/vite-plugin-typo3) - Frontend integration for TYPO3 CMS.
- [vite-asset-collector for TYPO3](https://github.com/s2b/vite-asset-collector) - Backend integration for TYPO3 CMS.

### Go

- [vite](https://github.com/olivere/vite) - Integration with Go.

### Rust

- [create-rust-app](https://github.com/Wulf/create-rust-app) - Integration for Rust web apps.
- [vite-rs](https://github.com/Wulf/vite-rs) - Embed assets in your Rust binary.

### OctoberCMS

### Symfony

- [Vite Bundle](https://github.com/lhapaipai/vite-bundle) - Integration for Symfony.

### Shopify

- [vite-plugin-shopify](https://github.com/barrel/barrel-shopify/tree/main/packages/vite-plugin-shopify) - Integration for Shopify themes.

### CodeIgniter

### DDEV

### Node.js

- [vite-express](https://github.com/szymmis/vite-express) - Integration for Express web apps.
- [vite-manifest-parser](https://github.com/sullay/vite-manifest-parser) - Parses manifest.json to generate HTML script and link tags.

### ASP.NET Core

- [Vite.AspNetCore](https://github.com/Eptagone/Vite.AspNetCore) - Integration with ASP.NET Core projects.

### Drupal

- [Vite module](https://git.drupalcode.org/project/vite) - Backend integration for Drupal.
- [vite-plugin-twig-drupal](https://github.com/larowlan/vite-plugin-twig-drupal) - Support for Twig with includes/embeds and Drupal specific twig features.

### PHP

- [PHP-Vite](https://github.com/mindplay-dk/php-vite) - Integration for PHP, Composer package, no framework dependencies.
- [PHP-Vite Starter Repo](https://github.com/nititech/php-vite-starter) - Starter repository, with TypeScript/JavaScript, Tailwind CSS, SASS/SCSS, EJS, SVG and image support.
- [php-vitelinker](https://github.com/Osteoporosis/php-vitelinker) - A CLI tool that generates includable PHP files after building bundles.

## Migrations

### Vue CLI

### React

- [Viject](https://github.com/bhbs/viject) - One-shot migration tool from Create React App.

These links are concise, but there is a lot more to explore in the Vite ecosystem. Vite has a powerful and flexible plugin system based on Rollup plugins, which allows developers to extend functionality easily. Whether you need CSS preprocessors, automatic imports, SSR support, or custom integrations, Vite's plugin system provides a wide range of solutions. You can also create your own plugins following Vite's straightforward API.

For a deeper dive, check out the official Vite plugin docs and explore the growing community co

🚀 _Switch to Vite and experience the next-gen frontend development workflow!_

