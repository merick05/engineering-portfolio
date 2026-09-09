# Engineering Portfolio

A responsive, accessible engineering portfolio built with plain HTML, CSS, and JavaScript.

## Preview locally

Open `index.html` in a browser. For the most accurate preview, run a local web server from
this folder:

```powershell
py -m http.server 8000
```

Then visit `http://localhost:8000`.

## Customize before sharing

Search `index.html` for these placeholders:

- `Your Name`
- `YN`
- `Your Engineering Field`
- `Your City, State`
- `First Project Title`
- `Second Project Title`
- `you@example.com`
- `href="#"` for project and social links

Replace each project placeholder with an image:

```html
<img src="assets/project-one.jpg" alt="A useful description of the project" />
```

Create an `assets` folder beside `index.html` and put your images and résumé inside it.

## Publish the first version on Netlify

1. Sign in at [Netlify](https://app.netlify.com/).
2. Choose **Add new project**, then **Deploy manually**.
3. Drag the entire `engineering-portfolio` folder into the upload area.
4. Netlify will provide a temporary `*.netlify.app` address.
5. Test that address on both desktop and mobile.

The Squarespace domain can remain disconnected until the content is ready.

## Add Git for automatic updates

From PowerShell in this folder:

```powershell
git init
git add .
git commit -m "Create portfolio skeleton"
```

Create a GitHub repository, push this folder, and import that repository into Netlify. Future
pushes to the main branch will then deploy automatically.

## Connect the Squarespace domain later

In Netlify, add the purchased domain under domain management. Netlify will show the exact DNS
records needed. Add those records to the domain's DNS settings in Squarespace. DNS updates can
take time to propagate, and Netlify will provision HTTPS after the records resolve.
