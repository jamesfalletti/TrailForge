# Trailforge

A single-page dirt-bike trail mapping and ride-timing prototype.

## Run locally

Open `index.html` in a browser, or serve this folder with a local web server. Browsers generally require a secure page (HTTPS, or localhost) before they allow location access.

## Publish with GitHub Pages

1. Create a GitHub repository and upload the files in this folder.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **GitHub Actions** as the source.
4. The workflow will publish the site. Open its completed run or **Settings → Pages** to find the HTTPS address.

The app stores trails and ride results in the browser's local storage on each device. Data does not sync between friends yet. Map imagery and libraries load from Esri, OpenStreetMap, and unpkg over the internet.
