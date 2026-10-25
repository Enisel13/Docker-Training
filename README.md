# Static Studio

A responsive static website using only HTML and CSS. No Docker, JavaScript,
dependencies, or build step required.

## Run without Docker

Open `index.html` directly in your web browser.

Alternatively, if Node.js and npm are installed, run a local HTTP server from
this directory:
test

```sh
npx http-server . -a 127.0.0.1 -p 8080 -c-1
```

Approve the package installation if npm prompts you, then visit
<http://127.0.0.1:8080>. Press `Ctrl+C` to stop the server.

## Customize

- Edit [index.html](./index.html) to change the text and sections.
- Edit [styles.css](./styles.css) to change the layout and colors.
- Refresh the browser after saving your changes.

## Build and publish

There is nothing to compile. The production files are `index.html` and
`styles.css`. Copy both files into the same folder on any static web host.
The README does not need to be published.
