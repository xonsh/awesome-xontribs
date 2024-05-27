# Awesome Xontribs

Awesome list of [Xonsh](https://xon.sh/) contributions ([xontribs](https://xon.sh/tutorial_xontrib.html)). Xontribs are a set of tools and conventions for extending the functionality of xonsh beyond what is provided by default. This allows 3rd party developers and users to improve their xonsh experience without having to go through the xonsh development and release cycle.

<!--TOC-->

- [Awesome Xontribs](#awesome-xontribs)
  - [Education materials](#education-materials)
  - [Core Xontrib](#core-xontrib)
  - [Python virtual-environment management](#python-virtual-environment-management)
  - [Tab-completions](#tab-completions)
  - [Directory Navigation](#directory-navigation)
  - [Prompts](#prompts)
    - [Prompt tweaks](#prompt-tweaks)
  - [Theming & Styling](#theming--styling)
  - [Language extensions](#language-extensions)
  - [Integrations](#integrations)
  - [Plugins](#plugins)
    - [History backends](#history-backends)
    - [Debugging](#debugging)
  - [Popular Links](#popular-links)

<!--TOC-->

## Education materials

- [xonsh-cheatsheet](https://github.com/anki-code/xonsh-cheatsheet/) - Cheat sheet for xonsh shell with copy-pastable examples. The best doc for the new users.
- [xonsh-install](https://github.com/anki-code/xonsh-install) - Best way to install xonsh on macOS or Linux and using it as core shell. 
- [rc-awesome](https://github.com/anki-code/xontrib-rc-awesome/) - Snippets of code for the xonsh [run control (RC) file](https://xon.sh/xonshrc.html#run-control-file).
- [xonsh-awesome-cli-app](https://github.com/anki-code/xonsh-awesome-cli-app) - Example of awesome cli app template for xonsh.

## Core Xontrib

These [modules](https://xon.sh/api/_autosummary/xontribs/xontrib.html) are part of xonsh itself but need to be loaded explicitly using [`xontrib load`](https://xon.sh/tutorial_xontrib.html#loading-xontribs)\*

- [coreutils](https://xon.sh/api/_autosummary/xontribs/xontrib.coreutils.html#module-xontrib.coreutils) - Additional core utilities that are implemented in xonsh.

## Python virtual-environment management

- [vox](https://github.com/xonsh/xontrib-vox) - Python virtual environment manager for xonsh.
- [autovox](https://github.com/xonsh/xontrib-vox) - A framework for automatic vox.\* [voxapi](https://github.com/xonsh/xontrib-vox) - API for vox.
- [avox](https://github.com/AstraLuma/xontrib-avox) - Policy for autovox based on project directories.
- [avox_poetry](https://github.com/jnoortheen/xontrib-avox-poetry) - auto-activate venv as one cd into a poetry project folder. Activate `.venv` inside the project folder is also supported.

## Tab-completions

*Extends auto-completion capabilities*

- [abbrevs](https://github.com/xonsh/xontrib-abbrevs) - Expands input words as you type in xonsh shell (fish-shell-like abbreviations).
- [apt_tabcomplete](https://github.com/DangerOnTheRanger/xonsh-apt-tabcomplete) - Adds tabcomplete functionality to apt-get/apt-cache inside of xonsh.
- [argcomplete](https://github.com/anki-code/xontrib-argcomplete) - Argcomplete support to tab completion of python and xonsh scripts in xonsh.
- [bash_completions_dirs](https://pypi.org/project/xontrib-bash-completions-dirs) - Autocomplete loading from directories for the xonsh.
- [carapace-bin](https://github.com/carapace-sh/carapace-bin) - multi-shell multi-command argument completer with Xonsh support.
- [django](https://github.com/jnoortheen/xontrib-django) - Django management command completions for Xonsh shell.
- [docker_tabcomplete](https://github.com/xsteadfastx/xonsh-docker-tabcomplete) - Adds tabcomplete functionality to docker inside of xonsh.
- [fish_completer](https://github.com/xonsh/xontrib-fish-completer) - Populate rich completions using fish shell instead of bash.
- [jedi](https://github.com/xonsh/xontrib-jedi) - Use Jedi as xonsh's python completer.
- [makefile_complete](https://pypi.org/project/xontrib-makefile-complete) - Adds tabcomplete functionality to make inside of xonsh.
- [scrapy_tabcomplete](https://github.com/Granitas/xonsh-scrapy-tabcomplete) - Adds tabcomplete functionality to scrapy inside of xonsh.

## Directory Navigation

- [autojump](https://github.com/wshanks/xontrib-autojump) - autojump support for xonsh.
- [back2dir](https://github.com/anki-code/xontrib-back2dir) - Return to the most recently used directory when starting the xonsh shell. For example, if you were in the '/work' directory when you last exited xonsh, then your next xonsh session will start in the '/work' directory, instead of your home directory.
- [broot](https://github.com/jnoortheen/xontrib-broot) - supports broot with br alias.
- [cd](https://github.com/eugenesvk/xontrib-cd) - 'cd' to any path without escaping in xonsh shell ('cd '→'cd! ').
- [free_cwd](https://github.com/xonsh/xontrib-free-cwd) - This will release the lock on the current directory whenever the prompt is shown.
- [fstrider](https://github.com/anki-code/fstrider) - File system navigator for reducing keystrokes and doing thing intuitive. Alternative to cd-ls.
- [hist_navigator](https://github.com/jnoortheen/xontrib-hist-navigator) - fish like `nextd` and `prevd` with default keybindings.
- [jump-to-dir](https://github.com/anki-code/xontrib-jump-to-dir) - Jump to used before directory by part of the path. Lightweight zero-dependency implementation of autojump or zoxide projects functionality.
- [up](https://github.com/oh-my-xonsh/xontrib-up) - The fast way to go up directories.
- [z](https://github.com/AstraLuma/xontrib-z) - Tracks your most used directories, based on 'frecency'.
- [zoxide](https://github.com/dyuri/xontrib-zoxide) - Zoxide integration for xonsh.
- [dotdot](https://github.com/yggdr/xontrib-dotdot) - "...." -> "cd ../../..".

## Prompts

- [powerline](https://github.com/santagada/xontrib-powerline) - Powerline for Xonsh shell.
- [powerline2](https://github.com/vaaaaanquish/xontrib-powerline2) - Powerline for Xonsh shell forked from santagada/xontrib-powerline.
- [powerline3](https://github.com/jnoortheen/xontrib-powerline3) - Powerline theme with native $PROMPT_FIELDS support.
- [powerline_binding](https://github.com/dyuri/xontrib-powerline-binding) - Uses powerline to render the xonsh prompt.
- [prompt_bar](https://github.com/anki-code/xontrib-prompt-bar) - An elegance bar style for prompt.
- [prompt_starship](https://github.com/anki-code/xontrib-prompt-starship) - [Starship prompt](https://github.com/starship/starship) in xonsh shell.
- [prompt_vi_mode](https://github.com/t184256/xontrib-prompt-vi-mode) - vi-mode status formatter for xonsh prompt

### Prompt tweaks

- [whole_word_jumping](https://github.com/xonsh/xontrib-whole-word-jumping) - Jumping across whole words (non-whitespace) with Ctrl+Left/Right.

## Theming & Styling

- [base16_shell](https://github.com/ErickTucto/xontrib-base16-shell) - Change base16 shell themes.
- [gruvbox](https://github.com/rpdelaney/xontrib-gruvbox) - A gruvbox color scheme for xonsh.
- [dracula](https://github.com/agoose77/xontrib-dracula) - Dracula theme for xonsh.

## Language extensions

*Changes to the xonsh core language.*

- [coconut](http://coconut-lang.org/) - Use language features from Coconut, a functional-programming-oriented strict superset of Python.

## Integrations

- [bashisms](https://xon.sh/api/_autosummary/xontribs/xontrib.bashisms.html#module-xontrib.bashisms) - Bash-like interface extensions for xonsh.
- [distributed](https://github.com/xonsh/xontrib-distributed) - The [distributed](https://pypi.org/project/distributed/) parallel computing library hooks for xonsh.
- [jupyter](https://github.com/xonsh/xontrib-jupyter) - Jupyter Notebook kernel for Xonsh.
- [kitty](https://github.com/scopatz/xontrib-kitty) - Xonsh hooks for the Kitty terminal emulator.
- [mpl](https://github.com/xonsh/xontrib-mpl) - Matplotlib hooks for xonsh, including the new 'mpl' alias that displays the current figure on the screen.
- [langenv](https://github.com/dyuri/xontrib-langenv) - pyenv/nodenv/goenv/rbenv integration for xonsh.
- [xonsh-prewarmed](https://github.com/anki-code/xonsh-prewarmed) - run interactive xonsh session in milliseconds using prewarmed GNU Screen session from the background.
- [homebrew](https://github.com/eugenesvk/xontrib-homebrew) - Add Homebrew's shell environment to xonsh shell on macOS/Linux.
- [init_ssh_agent](https://github.com/theRealBithive/xontrib-init-ssh-agent) - ssh-agent initialization.
- [ssh_agent](https://github.com/dyuri/xontrib-ssh-agent) - ssh-agent integration.
- [shadowenv](https://github.com/zscholl/xontrib-shadowenv) - [shadowenv](https://github.com/Shopify/shadowenv) integration.
- [tcg](https://github.com/zasdfgbnm/tcg/tree/master/shells/xonsh) - tcg integration.
- [xo](https://github.com/scopatz/xo) - Adds an 'xo' alias to run the exofrills text editor in the current Python interpreter session. This shaves off a bit of the startup time when running your favorite, minimal text editor.
- [xxh](https://github.com/xxh/xxh) - Using xonsh wherever you go through the ssh.

## Plugins

- [autoxsh](https://github.com/Granitas/xonsh-autoxsh) - Adds automatic execution of xonsh script files called `.autoxsh` when enterting a directory with `cd` function.
- [chatgpt](https://github.com/jpal91/xontrib-chatgpt) - Adds ability to communicate with OpenAI's ChatGPT directly from the command line.
- [clp](https://github.com/anki-code/xontrib-clp) - Copy output to clipboard. Cross-platform.
- [cmd_done](https://github.com/jnoortheen/xontrib-cmd-durations) - send notification once long-running command is finished. Adds `long_cmd_duration` field to $PROMPT_FIELDS.
- [commands](https://github.com/jnoortheen/xontrib-commands) - Some useful commands/aliases to use with Xonsh shell.
- [default-command](https://github.com/oh-my-xonsh/xontrib-default-command) - Run a default command when you press return on an empty command line.
- [direnv](https://github.com/74th/xonsh-direnv) - Supports direnv.
- [brace-expansion](https://pypi.org/project/xontrib-brace-expansion/) - Implements simple brace expansion: `a{d,c,b}e` -> `ade ace abe`
- [fzf-widgets](https://github.com/laloch/xontrib-fzf-widgets) (ARCHIVED) - Adds some fzf widgets to your xonsh shell.
- [fzf-completions](https://github.com/doronz88/xontrib-fzf-completions) - The new version of fzf support in xonsh (the updated version of the archived `fzf-widgets`)
- [skim](https://github.com/eugenesvk/xontrib-skim) - Fuzzy-search (with skim) xonsh history of commands and their CWDs, zoxide cd history (CWD/dir support in-place navigation), files/dirs in the current directory, ssh hosts.
- [gitinfo](https://github.com/dyuri/xontrib-gitinfo) - Displays git information on entering a repository folder. Uses `onefetch` if available.
- [histcpy](https://github.com/con-f-use/xontrib-histcpy) - Useful aliases and shortcuts for extracting links and textfrom command output history and putting them into the clipboard.
- [macro](https://github.com/anki-code/xontrib-macro) - Library of the useful macros for the xonsh shell.
- [onepath](https://github.com/anki-code/xontrib-onepath) - When you click to a file or folder in graphical OS they will be opened in associated app.The xontrib-onepath brings the same logic for the xonsh shell. Type the filename or pathwithout preceding command and an associated action will be executed. The actions are customizable.
- [output_search](https://github.com/anki-code/xontrib-output-search) - Get identifiers, names, paths, URLs and words from the previous command output and use them for the next command.
- [pipeliner](https://github.com/anki-code/xontrib-pipeliner) - Let your pipe lines flow thru the Python code in xonsh.
- [pyrtn](https://github.com/dyuri/xontrib-pyrtn) - IPython like In\[\]/Out\[\] to access python return values in the current session.
- [readable-traceback](https://github.com/6syun9/xontrib-readable-traceback) - Make traceback easier to see for xonsh.
- [schedule](https://github.com/AstraLuma/xontrib-schedule) - Xonsh task scheduling.
- [sh](https://github.com/anki-code/xontrib-sh) - Paste and run commands from bash, zsh, fish in xonsh shell.
- [xpg](https://github.com/fengttt/xsh/tree/master/py) - Run/plot/explain sql query for PostgreSQL.

### History backends

- [history_encrypt](https://github.com/anki-code/xontrib-history-encrypt) - History backend that encrypt the xonsh shell commands history to prevent leaking sensitive data.

### Debugging

- [xontrib-debug-tools](https://github.com/xonsh/xontrib-debug-tools) - Debug tools for xonsh shell:

  - `xog` - This adds xog - a simple command to establish and print temporary traceback log file.
  - `pdb` - Simple built-in debugger.

## Popular Links

- [Xontribs on GitHub](https://github.com/topics/xontrib)
- [Xontrib Template](https://github.com/xonsh/xontrib-template) - make your own xontrib in 10 minutes by using supercharged template.
- [Xonsh Official Site](https://xon.sh/)
- [Xonsh GitHub Repository](https://github.com/xonsh/xonsh)
- [Xonsh Gitter Channel](https://gitter.im/xonsh/xonsh)
