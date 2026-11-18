# kubebox

Checking a Kubernetes cluster often means working from a terminal, though a browser can be more convenient on another machine. kubebox provides a Kubernetes console for both environments.

## Features

- Access a Kubernetes console from your terminal.
- Open the console in a web browser.
- Monitor Kubernetes resources through the console.

## Installation

Install the JavaScript CLI with Node.js and npm:

```sh
npm install --global kubebox
```

**Cluster access is required.** Install the console on a machine where you can connect to the Kubernetes cluster you want to inspect.

## Usage

Check the available command-line options:

```sh
kubebox --help
```

Start the terminal console:

```sh
kubebox
```

The commands above cover the terminal CLI. Running the web console requires a separate web deployment; installing the CLI alone does not publish a browser endpoint.

## License

MIT. This project is based on [astefanutti/kubebox](https://github.com/astefanutti/kubebox), which is also licensed under MIT. Retain the upstream copyright notice and MIT license text when redistributing upstream code.
