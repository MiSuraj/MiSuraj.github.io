# Suraj Mishra Portfolio

Static portfolio site for GitHub Pages.

## Deploy on a GitHub profile

1. Create a public GitHub repository named exactly:

   ```text
   MiSuraj.github.io
   ```

2. Push this folder to that repository on the `main` branch.

3. In GitHub, open the repository settings:

   ```text
   Settings -> Pages -> Build and deployment -> Source -> GitHub Actions
   ```

4. The included workflow publishes `index.html` automatically after each push.

The site will be available at:

```text
https://MiSuraj.github.io/
```

## Notes

- `index.html` references `Suraj_Mishra_Resume.pdf`. Add that file beside `index.html` before deploying if you want the resume links to work.
- `.nojekyll` is included so GitHub Pages serves files as plain static assets.
