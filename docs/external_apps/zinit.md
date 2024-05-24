# znit - Plugin Manager

Zinit is a flexible and fast Zshell plugin manager that will allow you to install everything from GitHub and other sites. 

[Documentation](https://github.com/zdharma-continuum/zinit)

## How to Install

Automatic:

```bash
bash -c "$(curl --fail --show-error --silent --location https://raw.githubusercontent.com/zdharma-continuum/zinit/HEAD/scripts/install.sh)"
```

In your `.zshrc`, add the following snippet

```sh
# Parameter Extension - Set the directory we want to store zinit and plugins
ZINIT_HOME="${XDG_DATA_HOME:-${HOME}/.local/share}/zinit/zinit.git"

# Download Zinit, if it's not there yet
if [ ! -d "$ZINIT_HOME" ]; then
   mkdir -p "$(dirname $ZINIT_HOME)"
   git clone https://github.com/zdharma-continuum/zinit.git "$ZINIT_HOME"
fi
```

## Commands

* Check Installation

    ```zsh
    zinit zstatus
    ```
