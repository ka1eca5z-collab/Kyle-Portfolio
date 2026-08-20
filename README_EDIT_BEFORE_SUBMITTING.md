# Kyle Lim — Digital Portfolio

This website is already structured to match the EG2A17 digital portfolio requirements. Before your **final submission**, complete the items below.

## 1. Add your professional photo
The home page currently contains a photo placeholder.

Fastest method:
1. Put your photo in `assets/` as `profile.jpg`.
2. In `index.html`, search for `portrait-placeholder`.
3. Replace the whole `<div class="portrait-placeholder">...</div>` with:

```html
<img class="profile-photo" src="assets/profile.jpg" alt="Portrait of Kyle Lim">
```

Then add this to the bottom of `styles.css` if needed:

```css
.profile-photo { width:100%; height:100%; object-fit:cover; min-height:430px; }
```

## 2. Add LinkedIn, GitHub and email
Open `profile-config.js` and fill in the three blank values. This updates every matching button automatically.

```js
window.PORTFOLIO_PROFILE = {
  linkedin: "https://www.linkedin.com/in/your-profile/",
  github: "https://github.com/your-username",
  email: "your-email@example.com"
};
```

Do not submit while these still show **add link**.

## 3. Finish Project 03
The assignment requires **three completed project showcases**. Replace the Project 03 placeholder with your final school/personal project and use the same four headings:
- Project Scope / Client's Problem
- Your Role & Solution
- Your Work Process
- Outcome & Results Achieved

Add real screenshots/visuals for it as well.

## 4. Final content check
- Make sure every link works in a private/incognito browser window.
- Check the site on both laptop and phone width.
- Play the Nesso video from the published site.
- Remove any placeholder text.
- Check spelling and grammar after your final edits.

## 5. Make the site public
The site is static HTML/CSS/JS and can be hosted for free.

### Quick option — Netlify Drop
1. Extract `Kyle_Lim_Digital_Portfolio.zip`.
2. Go to Netlify Drop while signed in.
3. Drag the **kyle-portfolio** folder into the upload area.
4. Netlify gives you a public HTTPS URL.
5. Open that URL in an incognito window to verify there is no password/login barrier.

### Alternative — GitHub Pages
1. Create a public GitHub repository.
2. Upload all files from the `kyle-portfolio` folder to the repository root.
3. In repository Settings → Pages, deploy from the main branch/root.
4. Wait for the public URL, then verify every page and media file.

**Your module notes say to consult your tutor if you use a platform outside the recommended website builders/portfolio hosts. Do that if needed before final submission.**

## 6. Final EG2A17 submission evidence
The assignment instructions require a screen recording that visibly navigates the published portfolio and clicks the live project, GitHub and LinkedIn links. Record this only after the final site is public and all links work.
