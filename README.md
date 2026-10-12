# For Babe, With All My Heart 🎀

Personalized interactive birthday website for a best friend since school.

## Preview locally
Extract the ZIP, open the folder in VS Code, then open `index.html` in a browser. VS Code Live Server is also a good option.

## Add your photos
Place three photos in `photos/`, named `photo1.jpg`, `photo2.jpg`, and `photo3.jpg`. If you use PNG files, update the `src` filenames in `index.html`. Use photos you're comfortable sharing in a public website.

## Customize further
- Edit the letter in `index.html` inside `<article class="letter hidden" id="letter">`.
- Change each memory pop-up by editing the `data-note` attribute on its `.polaroid` button.
- Change the final message inside `.final-card`.
- Adjust the pink palette in `style.css` near `:root`.

## Publish for free with GitHub Pages
1. Create a GitHub repository, e.g. `babe-birthday`.
2. Upload `index.html`, `style.css`, `script.js`, and the `photos` folder into the repository root.
3. Open **Settings → Pages**.
4. Under Build and deployment, select **Deploy from a branch**.
5. Choose branch `main` and folder `/(root)`, then save.
6. After publishing, the URL will look like `https://YOUR-USERNAME.github.io/babe-birthday/`.
7. Test the link on your phone, then send it to Babe.

The repository needs to be public for the simplest free GitHub Pages setup. Think carefully before publishing personal photos or private messages publicly. Background music is not included; browsers commonly block autoplay unless started after a user gesture.
