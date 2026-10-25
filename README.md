# Akashh Roy — Music Portfolio

A responsive, single-page portfolio website built with plain HTML, CSS, and JavaScript. No build tools or paid services are required to preview it.

## Preview locally
1. Extract the ZIP.
2. Open `index.html` in Chrome, Edge, or Firefox.
3. An internet connection is needed for YouTube embeds and Google Fonts.

## Personalize before publishing
Open `index.html` in VS Code or Notepad:
- Video titles and channel names are now fetched automatically from YouTube when the page opens (requires internet access). You can still edit the `PROJECTS` list to customize categories and your exact role/credits.
- Video IDs are already filled with the 19 YouTube links supplied by you.
- Search for `YOUR_EMAIL@example.com` and replace it with your real email address.
- Replace the YouTube and Instagram placeholder links in the contact section with your real profile URLs.
- Update the About section and services so every claim reflects your actual work.

Categories:
- `production`
- `mixing`
- `releases`

## Publish for free with GitHub Pages
1. Sign in or create an account at https://github.com/
2. Create a new public repository, for example `akashh-roy-portfolio`.
3. Upload `index.html` to the repository's root.
4. Open **Settings → Pages**.
5. Under build and deployment, choose **Deploy from a branch**, select `main` and `/(root)`, then save.
6. Wait for GitHub Pages to publish. The site URL will be shown in that Pages section.

Alternative: https://www.netlify.com/ can host a static HTML site for free; follow its current dashboard instructions to deploy the folder.

## Notes
- Videos play inside the portfolio via YouTube's privacy-enhanced embed domain. If a video owner disables embedding, that video may not play on external websites.
- YouTube may show ads or other platform UI depending on its own policies.
- This ZIP contains the website source; it has not been published online. Free hosting requires you to sign in and complete the deployment steps.


## Add Spotify embeds
1. Open Spotify and open the track, album, or playlist.
2. Use **Share → Embed** (or copy the Spotify URL and convert it to the embed format).
3. In `index.html`, find `const SPOTIFY_PROJECTS = [` and replace the blank `embed` values with URLs such as `https://open.spotify.com/embed/track/TRACK_ID`.
4. Replace placeholder titles and artist/credit labels.
5. Upload the updated `index.html` to the root of your GitHub repository and commit the change. GitHub Pages will redeploy automatically.


## Add streaming-platform links
The site includes a **Stream My Music** section for Spotify, Apple Music, YouTube Music, Amazon Music, JioSaavn, Deezer, and SoundCloud.
1. Open `index.html` and find `const STREAMING_RELEASES = [`.
2. Replace release titles and artist/credit labels.
3. Paste the official URLs into the matching fields, for example `spotify:"https://open.spotify.com/track/..."`.
4. Leave a platform URL blank if that release is not available there; blank links are hidden.
5. Upload the updated `index.html` to the root of the GitHub repository and commit changes.
