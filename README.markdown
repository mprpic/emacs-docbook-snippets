Emacs DocBook Snippets
======================

Installation
------------

1. Install the YASnippet template system for Emacs. Refer to the YASnippet [installation page](http://capitaomorte.github.com/yasnippet/index.html#installation) for instructions on how to install it.

2. Clone this repository and copy the `nxml-mode` directory into the YASnippet `snippets` directory:

        git clone https://github.com/mprpic/emacs-docbook-snippets.git
        cd emacs-docbook-snippets
        cp -r nxml-mode/ ~/.emacs.d/yasnippet-0.6.1c/snippets/

3. In Emacs, use the following command to load the snippets:

        M-x yas/reload-all

4. Snippets are now available for all buffers using the _nxml-mode_.


Copyright
---------

Emacs DocBook Snippets — snippets for DocBook tags. Copyright (C) 2012 Martin Prpič

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see [http://www.gnu.org/licenses/](http://www.gnu.org/licenses/).

