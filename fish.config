eval (/opt/homebrew/bin/brew shellenv)

if status is-interactive
    starship init fish | source
    set -g fish_greeting ""
end

set -gx EDITOR nvim

set -g fish_key_bindings fish_vi_key_bindings
set -g fish_cursor_default block
set -g fish_cursor_insert line
set -g fish_cursor_replace_one underscore
set -g fish_cursor_visual block

### --- Abbreviations
abbr -a q exit
abbr -a gp 'git pull'
abbr -a fe 'pnpm start:frontend'
abbr -a be 'pnpm service:start:dev'
abbr -a v nvim
abbr -a vim nvim
abbr -a neovim nvim

# History with timestamps
alias history="history --show-time='%Y-%m-%d %H:%M:%S '"

zoxide init fish | source
