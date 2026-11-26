# Redirect page

This project is a static HTML page. It redirects visitors to
`https://www.google.com`, preserving the URL fragment after `#`.

## Preview

Run the **Preview redirect page** workflow. It copies `index.html` into `dist/`
and serves that directory on port 5000 with Python's development HTTP server.
No dependencies or secrets are required.

## Publish

Publishing uses static hosting. The build command copies only `index.html` into
`dist/`, which is the public directory. The development server is not used in
production. Click Publish in Replit to make the page live.
