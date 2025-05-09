## confluence-vercel-website-template

### vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/viqueen/confluence-vercel-website-template&env=CONFLUENCE_USERNAME,CONFLUENCE_API_TOKEN,CONFLUENCE_SITE_NAME,CONFLUENCE_SPACE_KEY,CUSTOM_DOMAIN&envDescription=Your+Confluence+Username,Your+Confluence+API+Key,Your+Confluence+Site+Name,Your+Confluence+Space+Key,Your+Custom+Domain)

### structure your content

This is built with [confluence-website](https://github.com/viqueen/confluence-website) which is a static site generator for Confluence.

It extracts content from a target Confluence space and includes

- the space homepage
- the pages under a folder named `public`
- the space blogs if any

### environment

- **[nvm](https://github.com/nvm-sh/nvm)** to manage node versions.

```bash
brew install nvm
```

- install node version

```bash
nvm install
```

### development setup

- install dependencies

```bash
npm ci
```

- extract content

```bash
npm run site:extract
```

- build site

```bash
npm run site:build
```