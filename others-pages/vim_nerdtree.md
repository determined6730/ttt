# Nerdtree

vim내에서 파일탐색기 사용

## install

[vim-plug\|vim\_vim-plug](https://github.com/determined6730/ttt/tree/7d354af7b5807845b13ceb1da5d7c9301b74692b/vim-plug%7Cvim_vim-plug.html)를 이용해서 설치  
[vimrc\|vim\_environment](https://github.com/determined6730/ttt/tree/7d354af7b5807845b13ceb1da5d7c9301b74692b/vimrc%7Cvim_environment.html)에 내용 추가

```text
"Vim-Plug가 아래 리스트를 확인 후에 설치 진행
call plug#begin('~/.vim/plugged')
Plug 'scrooloose/nerdtree'
call plug#end()

"nerdtree toggle
nnoremap <Leader>nn :NERDTreeToggle<CR>
"현재 파일의 위치를 nerdtree에 찾아서 보여줌 
nnoremap <Leader>nf :NERDTreeFind<CR>
```

## shortcut

| shortcut | description |
| :--- | :--- |
| I | hidden 파일 보기 |
| cd | 선택된 디렉토리를 cwd로 변경 |
| CD | NERDTree root로 cwd변경 |
| O | subdirectory를 모두 open |
| A | NERDTree 전체화면으로 Toggle |
| R | 새로 고침 |
| :NERDTree d:\ | d drive를 대상으로 열기 \(windows\) |

