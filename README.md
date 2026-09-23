# Trailforge

A single-page dirt-bike trail mapping and ride-timing prototype.

On a selected trail, tap **Auto time** to open the focused ride screen. At the start marker, ride away to begin timing. If you arm it while already away, ride through the start marker to begin. It stops near the finish marker, or near the start again on a loop. After a run, choose **New run**, **Results**, or **Delete run**. Results are grouped by trail; open an attempt to see its GPS line on the map. Allow location access and keep the page open while riding. GPS drift can affect the crossing point; **Manual start** and **Finish** remain available.

The **Settings** tab lets you turn on a large GPS speed readout, start timing after accelerating past 5 mph, and finish after slowing below 3 mph near the finish. GPS speed accuracy depends on the phone and reception. GPS trail recording is in **Build**.

## Run locally

Open `index.html` in a browser, or serve this folder with a local web server. Browsers generally require a secure page (HTTPS, or localhost) before they allow location access.

## Publish with GitHub Pages

1. Create a GitHub repository and upload the files in this folder.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **GitHub Actions** as the source.
4. The workflow will publish the site. Open its completed run or **Settings → Pages** to find the HTTPS address.

The app stores trails and ride results in the browser's local storage on each device. Data does not sync between friends yet. Map imagery and libraries load from Esri, OpenStreetMap, and unpkg over the internet.
