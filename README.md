fastopen.vim
------------
![Screenshot](screenshot.png)

```vim
map <c-l> :call fastopen#show('argedit')<cr>
```

If `fugitive.vim` is installed, it will auto-detect `git` repositories
and set `g:fastopen_list_cmd` to `git ls-files`, otherwise it will fallback 
to a regular `find`.

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
