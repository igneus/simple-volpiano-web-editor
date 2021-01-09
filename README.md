# Simple Volpiano Editor

Web page which lets you enter [Volpiano](http://www.fawe.de/volpiano/) code in a textarea,
renders music preview (if you have the font installed) and highlights spaces
(which I consider particularly error-prone when manually typing Volpiano).

Use it online: https://igneus.github.io/simple-volpiano-web-editor/

## External calls

You can construct a link opening the editor with particular Volpiano code loaded
by adding `#!` and the code in question to the editor's URL,
e.g. [`#!1---gh--h--g--g---`](https://igneus.github.io/simple-volpiano-web-editor/#!1---gh--h--g--g---)
Also, the editor updates the URL as you are writing, so you can just copy the URL
and share it with others (although there are usually better ways to share your
transcriptions).
