### Lambda

[![MIT License](https://img.shields.io/badge/license-MIT-007EC7.svg?style=flat-square)](/LICENSE)

<br/>

#### Screenshot

<p align="center">
<img src="https://raw.githubusercontent.com/hasanozgan/theme-lambda-zsh/master/screenshot.png">
</p>

#### Install

##### Oh-My-Zsh


Adding and customizing your own themes pretty much works the same as with plugins.

Themes are located in a `themes` folder and must end with `.zsh-theme`. The basename of the file is the name of the theme.

```
zsh_custom
└── themes
    └── lambda.zsh-theme
```

Then edit your .zshrc to use that theme.

```shell
ZSH_THEME="lambda"
```

Remember that customizations always take precedence over built-ins. If you happen to enjoy a particular theme that comes packaged with oh-my-zsh, but would like to change just a little detail inside of it – let's say you love the `agnoster` theme, it will be the easiest to copy the `agnoster.zsh-theme` file to your `custom/themes` directory and customize it.

If you don't change its filename, your `.zshrc` file can stay the same: `ZSH_THEME="agnoster"` will be perfect and still take your changes into account. You might also want to consider this before filing a new issue or pull request that just changes a trivial detail inside of a built-in theme.

