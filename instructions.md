My custom lunarvim setup. Modified a lot of things that cannot be done from the config file

clone to > $HOME/.local/share/lunarvim

Command to launch lunarvim

> `#!/bin/sh export LUNARVIM_RUNTIME_DIR="${LUNARVIM_RUNTIME_DIR:-"$HOME/.local/share/lunarvim"}" export LUNARVIM_CONFIG_DIR="${LUNARVIM_CONFIG_DIR:-"$HOME/.config/lvim"}" export LUNARVIM_CACHE_DIR="${LUNARVIM_CACHE_DIR:-"$HOME/.cache/nvim"}" exec nvim -u "$LUNARVIM_RUNTIME_DIR/lvim/init.lua" "$@" `
