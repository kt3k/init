# init

> Initialize files with placeholders

# Usage

## Set up

  Clone this repository

    git clone https://github.com/kt3k/init ~/.init

  Add ~/.init to `PATH` variable

    echo export PATH=~/.init:\$PATH >> ~/.bash_profile

  Add anything you want to use as a placeholder for the file of the name

    cd ~/.init

    # put anything here

  For example, LICENSE, .gitignore and .editorconfig are good examples of useful placeholders

    $ cd ~/.init
    $ ls
    init LICENSE .gitignore .editorconfig


## Use

  Then `init` command copies anything from your `~/.init` directory to the current dir.

    init LICENSE

  The above copys LICENSE file from ~/.init to the current dir.

# LICENSE

  MIT
