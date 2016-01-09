ansible-xdg
===========
[![Build Status](https://travis-ci.org/mkwmms/ansible-xdg.svg)](https://travis-ci.org/mkwmms/ansible-xdg)

Configure [xdg] directory settings for [bash], [zsh] & [fish] shells.

Installation
------------

```
ansible-galaxy install mkwmms.xdg
```

Requirements
------------

None.

Role Variables
--------------

See [default variables] & [variables].

Dependencies
------------

None.

Example Playbook
----------------

```
    - hosts: all
      roles:
         - role: mkwmms.xdg
```

Notes
-----

__Warning__: This role modifies your default shell configuration file, eg.
`~/.bash_profile`, `~/.zshrc` or `~/.config/fish/config.fish`.

License
-------

GPLv3

Author Information
------------------

[@mkwmms]

[@mkwmms]: https://github.com/mkwmms
[aura]: https://github.com/aurapm/aura
[bash]: https://www.gnu.org/software/bash/manual/bashref.html
[default variables]: defaults/main.yml
[dotstrap]: https://github.com/mkwmms/dotstrap
[fasd]: https://github.com/clvv/fasd
[files]: files/
[fish]: http://fishshell.com/
[homebrew]: https://github.com/Homebrew/homebrew
[xdg]: https://github.com/sindresorhus/xdg
[variables]: vars/
[xdg]: http://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html
[yaourt]: https://github.com/archlinuxfr/yaourt
[z]: https://github.com/rupa/z
[zsh]: http://zsh.sourceforge.net
