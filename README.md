This repo just collects dev versions of various jupyter-js-* repos necessary for building a notebook so they can be used in a coordinated fashion.

```sh
./build
# in another terminal, start up the Jupyter notebook server in the root lab directory with
jupyter notebook --NotebookApp.allow_origin=* --port 8890
http-server # or any other webserver
```
Then go to `http://localhost:8080/jupyter-js-notebook/example/index.html`
