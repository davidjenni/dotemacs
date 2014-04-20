# DotEmacs

Emacs initialization to use Vim modes and bindings

adapted from: https://github.com/bling/dotemacs

Assumes Emacs >= 24.3


## Installation

### OSX:
download GUI version: http://emacsformacosx.com/

or brew it:

    brew install emacs --cocoa

if there's an existing .emacs.d in your user directory:

    mv ~/.emacs.d ~/.emacs.d-old

Now clone:

    git clone git@github.com:davidjenni/dotemacs.git .emacs.d/

on first run, emacs will download and install the packages. To later refresh packages, run:

    package-refresh-contents RET


### Windows:
download from: http://ftpmirror.gnu.org/emacs/windows/