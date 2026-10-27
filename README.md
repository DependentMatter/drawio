<<<<<<< HEAD
# Local diagrams.net / draw.io study project

This is the official open-source editor from [jgraph/drawio](https://github.com/jgraph/drawio) (Apache 2.0). [app.diagrams.net](https://app.diagrams.net/) is draw.io Ltd’s hosted deployment of that editor.

You can run it locally and read the published source. This is not a reverse-engineering setup.

## Run

```powershell
node server.mjs
```

Then open:

- Production-style bundles: http://127.0.0.1:8080/
- Unminified sources (`?dev=1`): http://127.0.0.1:8080/index.html?dev=1

Change the port with `PORT=9090 node server.mjs`.

## Where to study

| Path | What it is |
| --- | --- |
| `drawio/src/main/webapp/index.html` | Editor shell |
| `drawio/src/main/webapp/js/bootstrap.js` | Boot / `dev=1` loader |
| `drawio/src/main/webapp/js/diagramly/` | App UI (menus, files, sidebar) |
| `drawio/src/main/webapp/js/grapheditor/` | Graph editor layer |
| `drawio/src/main/webapp/mxgraph/` | Graph library |
| `drawio/src/main/webapp/js/PreConfig.js` | Local config hooks |

Official docs: [Self-hosting wiki](https://github.com/jgraph/drawio/wiki/Self-Hosting).

Local static hosting has no Google Drive / OneDrive sign-in and no Java export proxy. Diagrams save in the browser or as files you download.

## License

draw.io source is Apache 2.0. Read `drawio/LICENSE`. The draw.io name is a trademark; do not imply affiliation with draw.io Ltd.
=======
# drawio
use for drawing 
>>>>>>> aa4ffa078fe7aedfe7bfa9c8491b9a8f204bbc1c
