## sudope Plugin for Fish Shell

### About

A Fish port of oh-my-zsh's [sudo plugin]

### Install

With [Oh-My-Fish]:
```fish
omf install sudope
```

### Usage

Press `Ctrl`+`s` to activate it.  
It will add `sudo ` to the beginning of the line if missing, remove it if it is present while preserving the cursor position.  
If the current line is empty, it will do the same thing to the most recent history item.

#### License

Commits prior to e45d168: 2015 [MIT] @ [Itzik Ephraim]  
Commits e45d168 and 0928ab2: 2017 [ISC] @ [Chloe Kudryavtsev]

[sudo plugin]: https://github.com/robbyrussell/oh-my-zsh/tree/master/plugins/sudo
[Oh-My-Fish]: https://github.com/oh-my-fish/oh-my-fish
[MIT]: https://opensource.org/licenses/MIT
[ISC]: http://cvsweb.openbsd.org/cgi-bin/cvsweb/src/share/misc/license.template?rev=HEAD
[Itzik Ephraim]: https://github.com/oranja
[Chloe Kudryavtsev]: https://github.com/5paceToast
