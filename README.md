# Glenageary Doorway Dashboard

A lightweight, responsive dashboard for a wall-mounted screen. It shows current conditions and the hourly forecast for Glenageary, plus a link to the drive to Amgen on Pottery Road.

## Run it

Open `index.html` in a browser. The weather panel fetches current and hourly data from [Open-Meteo](https://open-meteo.com/) and refreshes every 15 minutes. Internet access is needed for weather updates.

The traffic card opens the route in Google Maps. Its starting point is Rochestown Lodge Hotel, a nearby landmark, so the exact home address is not included in this project. The page does not yet calculate and display a live drive-time estimate; that needs a traffic service and API credentials.

## Publish with GitHub Pages

1. Create a GitHub repository and upload the files in this folder, keeping `index.html` at the repository root.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then save.
4. GitHub will show the published site URL in the Pages settings when deployment completes.

GitHub Pages websites are public on the internet, even when the source repository is private. Keep your exact home address, API keys, and other private details out of the published files. See [GitHub's Pages documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site).

## Customize

- Change the nearby starting landmark or destination by editing the Google Maps URL on the traffic card in `index.html`.
- The weather coordinates are set for Glenageary in the Open-Meteo request near the bottom of `index.html`.
- The visual layout uses plain HTML, CSS, and JavaScript; there is no build step or package installation.
