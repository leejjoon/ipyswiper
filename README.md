# ipyswiper

A reusable interactive image gallery component for Jupyter Notebooks.

This component provides an interactive image gallery with:
- Main image display with optional fade effects
- Scrollable thumbnail strip
- Keyboard navigation support
- Standalone HTML export

## Notebook example

https://nbviewer.org/github/leejjoon/ipyswiper/blob/main/notebooks/jupyter_gallery_demo.ipynb

## Install

Once you download/fork repository,

    ```bash
    pip install .
    ```

## For Administrators

### How to Publish to PyPI

To publish this package to PyPI, you will need to have `flit` installed.

1.  **Install flit**

    ```bash
    pip install flit
    ```

2.  **Build the package**

    ```bash
    flit build
    ```

3.  **Publish to PyPI**

    ```bash
    flit publish
    ```

    You will be prompted for your PyPI username and password.
