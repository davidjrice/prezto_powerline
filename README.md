Powerline for [Prezto](http://github.com/sorin-ionescu/prezto) ZSH


## Features

* Single line prompt
* Git branch info (current branch and modified states)
* Time since last commit
* RVM current ruby version / gemset

## Dependencies

* [skwp/dotfiles](http://github.com/skwp/dotfiles) *(YADR)*
* [prezto](https://github.com/sorin-ionescu/prezto) (included by YADR)

## Installation

    # Install YADR
    git clone https://github.com/skwp/dotfiles ~/.yadr
    cd ~/.yadr && rake install

    # Install the prompt
    curl https://raw.github.com/davidjrice/prezto-powerline/master/prompt_powerline_setup ~/.zsh.prompts/prompt_powerline_setup

    # Enable
    echo "prompt powerline" > ~/.zsh.after/prompt.zsh


## Inspiration

This prompt is inspired by:

* [oh-my-zsh-powerline-theme](http://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme)
* [robbl oh-my-zsh theme](http://github.com/robbl/oh-my-zsh-config)
* [SKWP prezto theme](http://github.com/skwp/dotfiles/blob/master/zsh/prezto-themes/prompt_skwp_setup)

