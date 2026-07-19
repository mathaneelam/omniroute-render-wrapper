# OmniRoute Render Wrapper

This wrapper deploys the official prebuilt OmniRoute Docker image on Render.

It avoids building the full OmniRoute source repo, so Render will not run:

```sh
npm run build:secure
```

Use this as a tiny GitHub repo if Render keeps asking for repo and branch.
