
vimrc 설정
```
set autoindent
"set cindent
set ts=4 " tab width
set shiftwidth=4 "auto indent width
set smarttab
set smartindent


"cursor point
au BufReadPost *
\ if line("'\"") > 0 && line("'\"") <= line("$") |
\ exe "norm g`\"" |
\ endif

"status bar
set laststatus=2 "
set statusline=\ %<%l:%v\ [%P]%=%a\ %h%m%r\ %F\

set sw=1
set autoread

colorscheme jellybeans
"http://www.vim.org/scripts/script.php?script_id=2555
"download and copy to /usr/share/vim/vimN/colors/
```
