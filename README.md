# Rana Waleed Elzayat — Portfolio Website

A responsive one-page portfolio built with plain HTML, CSS, and JavaScript.

## Preview locally

Open `index.html` in your browser.

## Add your portrait

1. Place your photo inside the `assets` folder, for example: `assets/rana-photo.jpg`.
2. In `index.html`, replace the block with class `portrait-placeholder` with:

```html
<img class="portrait-photo" src="assets/rana-photo.jpg" alt="Rana Waleed Elzayat" />
```

3. Add this rule to `styles.css`:

```css
.portrait-photo {
  width: 100%;
  aspect-ratio: 4 / 5;
  object-fit: cover;
  border-radius: 20px;
}
```

## Publish with GitHub Pages

1. Create a new GitHub repository, such as `portfolio`.
2. Upload all files and folders from this project.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/root`, then save.
6. GitHub will provide the public website URL.

## Customize

- Edit the text in `index.html`.
- Change colors in the `:root` section of `styles.css`.
- Replace project screenshots inside `assets` while keeping the same filenames, or update image paths in `index.html`.
