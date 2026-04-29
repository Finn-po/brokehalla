PANDEX v15 structure/performance patch

Copy into your project root:
- all .html files
- assets/styles.css

What changed:
- Shared website styling moved from every HTML file into assets/styles.css
- This reduces duplicated code and makes future design changes safer
- Google Fonts preconnect added for faster loading
- Map preview images use lazy loading + async decoding

After copying:
git add .
git commit -m "Move shared styling to CSS and improve loading"
git push
