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


## Streaming links added
Eight streaming entries have been added from the links supplied: seven Spotify track links and one Amazon Music album link. The titles are temporary labels ("Spotify Release 1", etc.) because exact song titles were not included. Update those labels in `STREAMING_RELEASES` when you have the titles.

## Photos and contact details
To finish the personal profile, add your own portrait and studio photos to the project and update the contact placeholders with your real email, phone number, and Instagram profile URL. Do not publish a personal phone number unless you want it publicly visible.


## Contact and professional profile updated
- Email: ar4054007@gmail.com
- Public phone: +91 79903 10107
- Instagram: https://www.instagram.com/akasssshroy/?hl=en
- YouTube: https://www.youtube.com/@Akashh
- Studio brand: AKASH ROY MUSIC PRODUCTION STUDIO
- Bio: Music Producer & Music Director with 8–9 years of experience; music production, music direction, BGM, film-related music, mixing and mastering; user-reported work associated with T-Series and two studios.
- First two supplied Spotify releases have been titled “Bar Zal Sodla Tu” and “Sona Na Haar”. Remaining release names are temporary until provided.
- Personal and studio photos have not yet been added; upload them separately to finish the visual gallery.


## Studio gallery and muted videos
Added supplied studio photos and four supplied video clips converted to silent video (audio tracks removed). Gallery describes the user's home studio and professional 7.1 studio environment. The Dolby Atmos-style room images supplied are shown as studio visuals; verify exact facility specifications before presenting them as photographs of a specific certified room.


## Logo and studio details
- Added the supplied Akashh Roy logo to `assets/akashh-roy-logo.jpg` and used it as a favicon/brand image.
- Profile references a home studio and a professional 7.1 surround studio.
- Any HTML video elements are muted during browser playback. This mutes playback but does not remove audio from the underlying video files.


## 3D Immersive redesign (October 2026)
This version adds a CSS-rendered chrome sphere with animated orbital rings, a floating glass label, ambient particle field, pointer-responsive light, 3D card tilt, and reduced-motion support. The existing portfolio sections, 19 YouTube project IDs, Spotify release links, streaming section, studio galleries, supplied imagery/videos, contact links, and navigation are retained.

Deploy by uploading the contents of this `akashh_roy_portfolio` folder to the root of the GitHub Pages repository, keeping the `assets` folder beside `index.html`.
