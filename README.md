# Dr. Shadia Yahya Baroud — Academic Portfolio

This is a Vercel-ready static website. It has no build step: the complete page is in `index.html`, with the profile image and CV beside it at the repository root.

## Included files

- `index.html` — complete responsive portfolio with Tailwind CDN, Font Awesome, analytics, verification, light/dark mode, interactions, social links, and contact form
- `profile-photo.jpg` — profile image used by the hero section and social preview metadata
- `Dr_Shadia_Baroud_CV.pdf` — CV download asset

## Upload to GitHub

1. Create a new GitHub repository.
2. Upload these three files and this README to the repository root.
3. Commit the files.

Do not place the files inside an additional nested folder, or the homepage and assets will not resolve correctly.

## Deploy with Vercel

1. In Vercel, choose **Add New → Project** and import the GitHub repository.
2. Set the framework preset to **Other**.
3. Leave the build command empty.
4. Set the output directory to `.` if Vercel asks for one.
5. Deploy.

## After Vercel assigns the final domain

The site will work immediately, but update the absolute `canonical`, `og:url`, `og:image`, and `twitter:image` URLs in `index.html` from the current Sites URL to the final Vercel or custom domain. Keep `profile-photo.jpg` at the repository root so the preview image continues to resolve.
