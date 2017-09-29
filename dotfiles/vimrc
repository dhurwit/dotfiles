set nocompatible
filetype on
filetype off

set rtp+=~/.vim/bundle/Vundle.vim
call vundle#begin()

"let vundle mananage vundle"
Plugin 'VundleVim/Vundle.vim'

" Navigate a file quickly, regardless of language 
Plugin 'Lokaltog/vim-easymotion'

" Allows you to change the order of arguments with ease.
Plugin 'PeterRincker/vim-argumentative'

" Automatically match pairs intelligently.
Plugin 'Raimondi/delimitMate'

" Jump around code based on rough filenames
Plugin 'ctrlpvim/ctrlp.vim'

" Tab autocomplete
Plugin 'ajh17/VimCompletesMe'

" Git info in the gutter
Plugin 'powerline/powerline'

" js syntax 
Plugin 'pangloss/vim-javascript'

" Filetree
Plugin 'scrooloose/nerdtree'
let NERDTreeIgnore=['\.pyc$', '\~$'] "ignore files in NERDTree

" Search across files
Plugin 'rking/ag.vim'

" Provide lintning for multiple languages
Plugin 'scrooloose/syntastic'

" Change surroundings in pairs
Plugin 'tpope/vim-surround'

" Code folding
Plugin 'tmhedberg/SimpylFold'

"Git Integration
Plugin 'tpope/vim-fugitive'

"Colorschemes
Plugin 'flazz/vim-colorschemes'

call vundle#end()
filetype plugin indent on

au BufNewFile, BufRead *.py 
    \ set tabstop=4
    \ set softtabstop=4
    \ set shiftwidth=4
    \ set textwidth=79
    \ set expandtab
    \ set autoindent
    \ set fileformat=unix

au BufNewFile,BufRead *.js, *.html, *.css
    \ set tabstop=2
    \ set softtabstop=2
    \ set shiftwidth=2

syntax on
colorscheme desert

set nu
set cursorline
set pastetoggle=<F2>
set fileformats=unix,dos
set backspace=indent,eol,start
set wildmenu
set showmatch
set incsearch
set hlsearch
set foldmethod=indent

filetype indent on
filetype plugin on

" Brief help
" :PluginList       - lists configured plugins
" :PluginInstall    - installs plugins; append `!` to update or just
" :PluginUpdate
" :PluginSearch foo - searches for foo; append `!` to refresh local cache
" :PluginClean      - confirms removal of unused plugins; append `!` to auto-approve removal
" 
" see :h vundle for more details or wiki for FAQ
" Put your non-Plugin stuff after this line
