## Hello mes amis! 👋
🎓 Actuellement étudiant à la [42 Lausanne](https://www.42lausanne.ch/)  
🚀 Apprentissage à travers des projets stimulants et la collaboration avec d'autres développeurs  
🧠 Développement de compétences en résolution de problèmes, algorithmes et systèmes bas niveau  
💡 Passionné par l'apprentissage continu et la technologie

1```vim
" .vimrc para a Escola 42 🚀                                                                    
" Configurações para seguir a Norminette

" 1️⃣ Usa tabulação real em vez de espaços
set noexpandtab       " Não converte TAB em espaços
set tabstop=4         " Define que 1 TAB equivale a 4 espaços
set shiftwidth=4      " Indenta 4 espaços ao usar >> ou <<
set softtabstop=4     " Backspace remove um TAB completo

" 2️⃣ Garante que a indentação fique correta
set autoindent        " Mantém a indentação da linha anterior
set smartindent       " Adiciona indentação extra em blocos de código

" 3️⃣ Exibição e navegação no código
set number            " Mostra números das linhas
set relativenumber    " Mostra números relativos (ajuda na navegação)
set cursorline        " Destaca a linha atual
set ruler             " Mostra posição do cursor na barra inferior
set scrolloff=5       " Mantém 5 linhas visíveis ao rolar o código
set showcmd           " Mostra comandos digitados na barra inferior

" 4️⃣ Melhorando a edição
set hlsearch          " Destaca todas as ocorrências da pesquisa
set incsearch         " Pesquisa incremental (mostra resultados ao digitar)
set ignorecase        " Pesquisa sem diferenciar maiúsculas/minúsculas
set smartcase         " Se houver letra maiúscula, diferencia na busca
set wildmenu          " Melhora a navegação nos comandos do Vim
set backspace=indent,eol,start " Permite apagar TABs e quebras de linha

" 5️⃣ Removendo espaços desnecessários automaticamente
autocmd BufWritePre * %s/\s\+$//e

" 6️⃣ Configuração para C na 42 (Norminette)
autocmd FileType c setlocal noexpandtab tabstop=4 shiftwidth=4 softtabstop=4

"Colocar login e email no HEADER42
let g:user42 = "dleite-b"
let g:mail42 = "dleite-b@student.42lausanne.ch"
