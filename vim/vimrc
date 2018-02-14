
" search 
set smartcase
set ignorecase
set incsearch
set showmatch

" indention
set smartindent
set tabstop=4
set shiftwidth=4
set softtabstop=4
set expandtab

" highlighting
syntax on
"set relativenumber
set hlsearch

" open file on previous position
if has("autocmd")
      au BufReadPost * if line("'\"") > 1 && line("'\"") <= line("$") | exe "normal! g'\"" | endif
endif

" When editing a file, always jump to the last cursor position
autocmd BufReadPost *
\ if ! exists("g:leave_my_cursor_position_alone") |
\ if line("'\"") > 0 && line ("'\"") <= line("$") |
\ exe "normal g'\"" |
\ endif |
\ endif


" change color scheme
colorscheme delek
" list of available schemes (/usr/share/vim/vim74/colors):
"blue defaul    desert     evening    koehler    murphy     peachpuff  ron        slate      zellner    
"darkblue   delek      elflord    industry   morning    pablo           shine      torte
