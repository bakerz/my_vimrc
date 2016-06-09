```
:set tabstop=4                          
:set softtabstop=4
:set shiftwidth=4
:set expandtab
:set autoindent
:set hlsearch
 
"ע��
:highlight Comment ctermfg=yellow ctermbg=red
 
"���������
set cursorline
"hi CursorLine cterm=NONE ctermbg=darkred ctermfg=white guibg=darkred guifg=white
 
"���������
set cursorcolumn
"hi CursorColumn cterm=NONE ctermbg=darkred ctermfg=white guibg=darkred guifg=white
 
" NERDTree
map <F10> :NERDTreeToggle<CR>
autocmd bufenter * if (winnr("$") == 1 && exists("b:NERDTreeType") &&b:NERDTreeType == "primary") | q | endif
```