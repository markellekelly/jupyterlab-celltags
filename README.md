[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jupyterlab/jupyterlab-celltags/master?urlpath=lab)

# jupyterlab-celltags

### Note: A new version of celltags is currently being developed to be merged into core JupyterLab. This repo is at end of lifecycle, and will only be updated with critical bugfixes.

The JupyterLab cell tags extension enables users to easily add, view, and manipulate descriptive tags for notebook cells. The extension includes the functionality to select all cells with a given tag, supporting the performance of any operation on those cells.
![](http://g.recordit.co/MxwN6UaFZj.gif)

## Prerequisites

- JupyterLab

## Install

```bash
jupyter labextension install @jupyterlab/celltags-ext
```

## Development

### Contributing

If you would like to contribute to the project, please read our [contributor documentation](https://github.com/jupyterlab/jupyterlab/blob/master/CONTRIBUTING.md).

JupyterLab follows the official [Jupyter Code of Conduct](https://github.com/jupyter/governance/blob/master/conduct/code_of_conduct.md).

### Dev Install

Requires node 4+ and npm 4+

```bash
# Clone the repo to your local environment
git clone https://github.com/jupyterlab/jupyterlab-celltags.git

# move into repo dir
cd jupyterlab-celltags

# build celltags and install it into jupyterlab
jlpm build:dev
```

To watch for/rebuild on changes to this extension's source code, run:

```bash
jlpm run build:watch
```

For the watch build, you will also need to separately rebuild Jupyterlab itself when you make changes. You can either do this manually:

```bash
jupyter lab build
```

or run Jupyterlab itself in watch mode, which will pick up the changes automatically (you'll still need to reload your browser yourself):

```bash
jupyter lab --watch
```
