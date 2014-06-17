## Contribute

To edit the project directly in the browser:

Compile Sass files on the fly:
```bash
sass --watch style.scss:style.css --sourcemap
```

Run a local server:
```bash
python -m SimpleHTTPServer
```

Open in browser
```bash
open http://localhost:8000
```

In Chrome dev tools:
1. in preferences (top right corner / cog icon), make sure "Enable CSS source maps" and "Auto-reload generated CSS" are checked
1. In the Sources tab, add the current folder to workspace (right click in the left panel)
1. Right click style.css to map it to style.scss (Sources tab: right click / map to file system resource)

You can now edit Sass files live in the browser!
