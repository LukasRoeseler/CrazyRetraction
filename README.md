# CrazyRetraction

Browser game inspired by Crazy Chickens only that you have to put stamps on retracted papers. Created using Gamini 3.1 Pro Preview.

## Features
* Retro pixel-art style aesthetic using CSS and Google Fonts.
* Papers fly in all directions across the screen.
* Smaller, faster papers yield higher points.
* Real-world retracted scientific paper titles displayed on the targets.

## Audio Credits
Sound Effect by <a href="https://pixabay.com/users/freesound_community-46691455/?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=102627">freesound_community</a> from <a href="https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=102627">Pixabay</a>

## Updating Paper Titles
Included is an R script (`get_titles.R`) which will download the latest database snapshot from Retraction Watch via Crossref, randomly pick 100 valid titles, and generate a text file containing formatted JavaScript. You can simply copy/paste the output into the `index.html` file to update your game targets dynamically.
