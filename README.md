## confluence-vercel-website-template

built with [confluence-website](https://github.com/viqueen/confluence-website)

### vercel

[![Deploy with Vercel](https://vercel.com/button)](
https://vercel.com/new/clone?repository-url=https://github.com/YOUR_USERNAME/YOUR_REPO
&env=CONFLUENCE_USERNAME,CONFLUENCE_API_TOKEN,CONFLUENCE_SITE_NAME
&envDescription=Your+Confluence+Username,Your+Confluence+API+Key,Your+Confluence+Site+Name
)



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