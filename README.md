# Author
Nakoto Tanaka

## Running locally

If you want to use this tool with your mnemonic phrase, it's required to run it locally. The requirements for this are:

* [Node.js 10 or newer](https://nodejs.org/)
* [Yarn](https://yarnpkg.com/)

Clone this repository with Git or download the ZIP file and extract it. In the project folder, run the following command to install the dependencies.

```
yarn
```

Now you can run

```
yarn run serve
```

to start the local production server. You can access it by navigating to <https://localhost:8000> in your browser. You will get an SSL warning because it's using a self-signed certificate, but it's safe to ignore this.

## Development

This tool is built on top of React and Redux, and uses tools like `yarn` and `webpack` to bundle everything. Install the dependencies with `yarn` as follows:

```
yarn
```

### Run a local development server

To run a local development server, use:

```
yarn run start
```

Head to <https://localhost:8000> in your browser to see the application.

### Bundle the files

Use the following command to bundle everything

```
yarn run build
```
