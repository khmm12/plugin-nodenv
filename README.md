<div align="center">
  <a href="http://github.com/oh-my-fish/oh-my-fish">
  <img width=90px  src="https://cloud.githubusercontent.com/assets/8317250/8510172/f006f0a4-230f-11e5-98b6-5c2e3c87088f.png">
  </a>
</div>
<br>

#  [_nodenv_](https://github.com/nodenv/nodenv)

Node.js environment/version manager plugin for [Oh My Fish][omf-link] ([_plugin-rbenv fork_](https://github.com/oh-my-fish/plugin-rbenv)).

## Install
> _Note_: You need to have `nodenv` installed.

```fish
$ omf install nodenv
```

## Configuration

If you have a custom nodenv root, you can add the following to your `~/.config/fish/init.fish` file before sourcing Oh My Fish.

```
set -gx NODENV_ROOT #path
```

[omf-link]:       https://www.github.com/oh-my-fish/oh-my-fish
