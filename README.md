fastopen.vim
------------
![Screenshot](screenshot.png)

```vim
map <c-l> :call fastopen#show('argedit')<cr>
```

It will auto-detect `git` repositories if `fugitive.vim` is installed and
use `git ls-tree`, otherwise it will fallback to a regular `find`.

Contribute
----------
* Fork the project.
* Make your feature addition or bug fix.
* Do **not** bump the version number.
* Send me a pull request. Bonus points for topic branches.

License
-------
Copyright (c) Mihail Szabolcs. Distributed under the same terms as Vim itself. See
:help license.
