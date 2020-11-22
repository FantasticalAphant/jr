# `jr` (javarun)

Compile and run basic java projects (Single directory)

Can also be used in conjuction with vi(m):

``` vim
autocmd FileType java nnoremap <Leader>r :up <bar> exec '!jr '.shellescape('%')<CR>
```
