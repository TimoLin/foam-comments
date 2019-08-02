foam-comments
=============
This is a Comment/Un-Comment plugin for OpenFOAM cases' files and it's based on [comments.vim](https://github.com/vim-scripts/comments.vim).

## Description
The original comments.vim plugin has been adapted to comment/un-comment lines for files of OpenFOAM cases.  
For now, `*Dict`, `*Properties`, `fvScheme`, `fvSolution`, `fvOptions` and other files under folder like `0`, `constant`, `system`, `polyMesh` are supported to do comment/un-comment through key-mappings: `<Ctrl-C>`/`<Ctrl-X>` respectively.  
A c style is used in this repo.

## Note
This plugin may be conflict with the original comments.vim plugin. Therefore if you want use foam-comments plugin, the comments.vim plugin should be removed.
