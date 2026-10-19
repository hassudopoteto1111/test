# Vercel Smoke Test

A dependency-free static page for verifying the GitHub → Vercel deployment path.

## Deploy

1. Import this repository into Vercel (or connect it to the existing Vercel project).
2. Select **Other** as the framework preset if asked.
3. Leave the build command and output directory empty/default; `index.html` is served from the repository root.
4. Deploy. No environment variables or package installation are required.

## Verify

Open the deployed URL. The page should show **Static page is running**, a status of **OK**, and the current local time. Use the button to run the small client-side check again.

This is a smoke-test starter, not a production application.
