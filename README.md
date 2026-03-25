# CrazyRetraction

Browser game inspired by Crazy Chickens only that you have to put stamps on retracted papers. Created using Gamini 3.1 Pro Preview.

## Features
* Retro pixel-art style aesthetic using CSS and Google Fonts.
* Papers fly in all directions across the screen.
* Smaller, faster papers yield higher points.
* Real-world retracted scientific paper titles displayed on the targets.

## Credits & Data Sources
* **Retracted Paper Titles Data:** Data from the [Retraction Watch Database](https://retractionwatch.com/retraction-watch-database-user-guide/), provided by [Crossref](https://www.crossref.org/).
* **Stamp Sound Effect:** Sound Effect by <a href="https://pixabay.com/users/freesound_community-46691455/?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=102627">freesound_community</a> from <a href="https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=102627">Pixabay</a>
* **Game Over Sound Effect:** Sound Effect by <a href="https://pixabay.com/users/audley_fergine-32337609/?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=206486">Hanifi Şahin</a> from <a href="https://pixabay.com/sound-effects//?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=206486">Pixabay</a>

## Updating Paper Titles
Included is an R script (`get_titles.R`). Because the full Retraction Watch database is over 30MB, loading it live in the browser would make the game slow. Instead, run this script locally to fetch the latest database snapshot, pick 100 valid titles, and format them into a JavaScript array. Copy and paste the text file output into your `index.html` file to update your targets dynamically!
