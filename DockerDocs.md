## Development Mode

* Open the project in VS Code, and install [Dev Container Extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers).
* When you open the project and you will be prompted with `Open in Dev Container`.
* Start the server inside the dev container with `bash run.sh`

### Ports

```
7756:7755 -> Backend Server
```

## Production Mode

* Open project in terminal.
* Run `docker compose up` and open `localhost:7755` in your browser

### Ports

```
7755:7755 -> Backend Server
```
