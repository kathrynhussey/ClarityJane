# Clarity Jane Coaching website

Responsive one-page website for Clarity Jane Coaching with Kathryn Hussey.

## Upload these files to GitHub

Upload all five files directly to the repository root:

- `index.html`
- `styles.css`
- `script.js`
- `.nojekyll`
- `README.md`

Do not upload the ZIP file itself.

## Publish or update with GitHub Pages

1. Open Kathryn's website repository on GitHub.
2. Select **Add file**, then **Upload files**.
3. Drag in all five files listed above. GitHub will mark existing files as changed.
4. Use commit message: `Update email and add Kathryn qualifications`.
5. Commit directly to the `main` branch.
6. If Pages is not enabled, open **Settings > Pages**.
7. Under **Build and deployment**, choose **Deploy from a branch**.
8. Select branch `main`, folder `/(root)`, and save.
9. Use **Visit site** from the Pages settings to open the published page.

## Information included

- Correct email: `kathryn.hussey@gmail.com`
- Kathryn's LinkedIn profile
- Personal and Business Coaching training, Irish Lifecoach Institute, February 2026 to September 2026
- 150-Hour TEFL Certificate, 2018
- Bachelor of Business Studies, University of Limerick, September 2006 to July 2010
- Johanna's five-star testimonial
- Eight original common questions

## Checks before public launch

- Confirm Kathryn is comfortable with the wording and dates in the qualifications section.
- Obtain Johanna's permission to publish her testimonial and first name.
- Confirm the FAQ answers match Kathryn's actual coaching agreement, confidentiality boundaries, format and availability.
- Add Kathryn's professional photo when ready.
- Test the email and LinkedIn links on desktop and mobile.

## Add Kathryn's photo later

Upload a photo named `kathryn-hussey.jpg`. In `index.html`, replace:

```html
<div class="portrait-placeholder reveal"><span>KH</span><p>Kathryn Hussey</p></div>
```

with:

```html
<div class="portrait-photo reveal">
  <img src="kathryn-hussey.jpg" alt="Kathryn Hussey, coach at Clarity Jane Coaching">
</div>
```

Add to the end of `styles.css`:

```css
.portrait-photo img{width:100%;height:580px;object-fit:cover;border-radius:220px 220px 20px 20px;display:block}
@media(max-width:800px){.portrait-photo img{height:450px}}
```

## Domain

Do not add a `CNAME` file until `clarityjane.com` has been purchased and its DNS is ready.
