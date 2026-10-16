# David Madubuike — Portfolio

Static portfolio site for David Madubuike, positioned as a senior full-stack engineer with applied AI experience. It has no build step and no contact email or phone number. The only outbound profile link is LinkedIn.

## Preview locally

From this folder:

```bash
python -m http.server 8080
```

Open `http://localhost:8080`.

## Host on GitHub Pages

The site is plain HTML, CSS, and JavaScript at the repository root, so GitHub Pages can serve it directly.

### User or organization site (`https://username.github.io`)

1. Create a repository named `username.github.io` (use the GitHub account name).
2. Push this project to the `main` branch.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then save.

The site is published at `https://username.github.io/`.

### Project site (`https://username.github.io/repository`)

1. Create a repository with any name and push this project to `main`.
2. Open **Settings → Pages**.
3. Choose **Deploy from a branch**, then branch `main` and folder `/ (root)`.

The site is published at `https://username.github.io/repository/`.

Asset paths are relative, so the same files work for both a user site and a project site.

### GitHub Actions

If Pages is set to **GitHub Actions** instead of a branch, the workflow in `.github/workflows/pages.yml` publishes the site on every push to `main`. Use one publishing method, not both.
