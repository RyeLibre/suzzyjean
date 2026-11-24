# Suzzy Jean — website

Rebuild of suzzyjean.com (originally WordPress, 2016–2018) from the Wayback Machine.
Only the homepage was archived; the Prints, Paintings, Sculpture, #storieswithsuzzy and Bio pages were not.

## Put it on GitHub Pages
1. Create a repo (e.g. `suzzyjean`) and upload `index.html` and this README.
2. Settings → Pages → Source: `main` branch, `/ (root)`.
3. Site appears at `https://<your-username>.github.io/suzzyjean/`.
4. Optional custom domain: add a `CNAME` file containing `suzzyjean.com` and point the domain's DNS at GitHub Pages.

## Images
Save these 5 archived images into an `images/` folder in the repo
(until you do, the site loads them straight from the Wayback Machine):

- https://web.archive.org/web/2018im_/http://www.suzzyjean.com/wp-content/uploads/2016/06/MOM-LOGO.jpg
- https://web.archive.org/web/2018im_/http://www.suzzyjean.com/wp-content/uploads/2016/06/mom-back-3.jpg
- https://web.archive.org/web/2018im_/http://www.suzzyjean.com/wp-content/uploads/2016/06/untitled-2-1.jpg
- https://web.archive.org/web/2018im_/http://www.suzzyjean.com/wp-content/uploads/2016/06/Suzzy-jean-2-crop.jpg
- https://web.archive.org/web/2018im_/http://www.suzzyjean.com/wp-content/uploads/2016/06/Suzzy-jean-3.jpg

## Adding work
Drop a picture in `images/`, then add one line to the `WORKS` list near the bottom of `index.html`:

```js
{ cat: "paintings", file: "river.jpg", title: "River, 2015, oil on canvas" },
```

`cat` is one of `prints`, `paintings`, `sculpture`, `stories`. Edit the Bio section text directly in the HTML.
