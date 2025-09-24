# OAuth Server for Decap CMS

Simple OAuth server for authenticating with GitHub for Decap CMS.

## Environment Variables Required

- `GITHUB_CLIENT_ID`: GitHub OAuth App Client ID
- `GITHUB_CLIENT_SECRET`: GitHub OAuth App Client Secret
- `GITHUB_REDIRECT_URI`: OAuth callback URL
- `OAUTH_PROVIDER`: Set to `github`
- `SITE_URL`: URL of the CMS admin panel
- `PORT`: Port to run on (default: 3000)

## Usage

This container runs the OAuth server that handles GitHub authentication for Decap CMS.