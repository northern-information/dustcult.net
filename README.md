# dustcult.net

## setup

```zsh
git clone git@github.com:northern-information/dustcult.net.git
cd dustcult.net
npm i
npm run dev
```

## deploy

Push to main triggers `.github/workflows/deploy.yml`, which builds Eleventy and runs `wrangler deploy` against the `dustcult-net` Cloudflare Worker. Worker config: `wrangler.jsonc`. Requires `CLOUDFLARE_API_TOKEN` repo secret.

<3 the northern information movement

## docs

- [11ty](https://www.11ty.dev/docs/)
