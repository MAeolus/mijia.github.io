# Academic GitHub Homepage Template

This is a lightweight personal academic homepage inspired by a clean left-profile/right-content layout.

## Files

- `index.html`: main homepage content
- `style.css`: page style
- `assets/profile.svg`: placeholder profile image
- `assets/paper-placeholder.svg`: placeholder publication thumbnail
- `.nojekyll`: tells GitHub Pages to serve the site as plain static files

## How to deploy on GitHub Pages

1. Create a repository named:

   ```text
   your-github-username.github.io
   ```

2. Upload all files in this folder to the repository root.

3. Replace the placeholders in `index.html`:
   - name
   - email
   - GitHub link
   - Google Scholar link
   - photo
   - news
   - publication titles
   - paper/code/project links

4. Go to:

   ```text
   Settings → Pages
   ```

5. Set:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`

6. Open:

   ```text
   https://your-github-username.github.io/
   ```

## How to replace the profile photo

Put your image into the `assets` folder, for example:

```text
assets/profile.jpg
```

Then edit this line in `index.html`:

```html
<img class="avatar" src="assets/profile.svg" alt="Profile photo placeholder" />
```

to:

```html
<img class="avatar" src="assets/profile.jpg" alt="Jia Mi" />
```
