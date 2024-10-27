# jupyterhub_comments

A JupyterLab extension that allows adding comments to notebooks and documents in a multiuser environment, where files are shared between users, wher the main goal is the review process

![Image](https://github.com/SausageLion/jupyterhub-comments/blob/main/docs/images/add_comment.gif?raw=true)

# Features

* Add comments to specific cells of jupyter notebooks or lines of text documents
* Edit, delete, resolve and reply to comments
* Icons indicate when comments are added to a document and highlight the comment upon clicking
* Clicking a comment text in an interface focuses notebook cell / line where comment was placed

[Examples and more detailed documentation](https://github.com/SausageLion/jupyterhub-comments/blob/main/docs/README.md)

## Requirements

- JupyterLab >= 4.0.0,<5

## Install

To install the extension, execute:

```bash
pip install jupyterhub_comments
```

To share comments between users, provide `JUPYTERHUB_COMMENTS_DB_PATH` environment variable with directory where comments.db file should be stored. By default comments are stored in directory where extension is installed, which could be different for different users

## Uninstall

To remove the extension, execute:

```bash
pip uninstall jupyterhub_comments
```
