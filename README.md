# gRPC-Web Inspector website

A small public homepage and support website for gRPC-Web Inspector. GitHub Pages serves the static files from the root of the `main` branch. There is no build step.

## Chrome Web Store URLs

- Homepage: https://jhyang12345.github.io/grpc-web-inspector-site/
- Support: https://jhyang12345.github.io/grpc-web-inspector-site/support.html

## Updating the website

Edit `index.html`, `support.html`, or `styles.css`, then commit and push to `main`. GitHub Pages publishes the update automatically.

To preview locally:

```sh
python3 -m http.server 8080
```

Open http://localhost:8080/ in a browser. Extension source and support issues live at https://github.com/jhyang12345/grpc-web-devtools.
