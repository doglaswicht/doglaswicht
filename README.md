## Hello mes amis! 👋
🎓 Actuellement étudiant à la [42 Lausanne](https://www.42lausanne.ch/)  
🚀 Apprentissage à travers des projets stimulants et la collaboration avec d'autres développeurs  
🧠 Développement de compétences en résolution de problèmes, algorithmes et systèmes bas niveau  
💡 Passionné par l'apprentissage continu et la technologie

1
    " .vimrc para a Escola 42 🚀                                                                    
  1 " Configurações para seguir a Norminette
  2 
  3 " 1️⃣ Usa tabulação real em vez de espaços
  4 set noexpandtab       " Não converte TAB em espaços
  5 set tabstop=4         " Define que 1 TAB equivale a 4 espaços
  6 set shiftwidth=4      " Indenta 4 espaços ao usar >> ou <<
  7 set softtabstop=4     " Backspace remove um TAB completo
  8 
  9 " 2️⃣ Garante que a indentação fique correta
 10 set autoindent        " Mantém a indentação da linha anterior
 11 set smartindent       " Adiciona indentação extra em blocos de código
 12 
 13 " 3️⃣ Exibição e navegação no código
 14 set number            " Mostra números das linhas
 15 set relativenumber    " Mostra números relativos (ajuda na navegação)
 16 set cursorline        " Destaca a linha atual
 17 set ruler             " Mostra posição do cursor na barra inferior
 18 set scrolloff=5       " Mantém 5 linhas visíveis ao rolar o código
 19 set showcmd           " Mostra comandos digitados na barra inferior
 20 
 21 " 4️⃣ Melhorando a edição
 22 set hlsearch          " Destaca todas as ocorrências da pesquisa
 23 set incsearch         " Pesquisa incremental (mostra resultados ao digitar)
 24 set ignorecase        " Pesquisa sem diferenciar maiúsculas/minúsculas
 25 set smartcase         " Se houver letra maiúscula, diferencia na busca
 26 set wildmenu          " Melhora a navegação nos comandos do Vim
 27 set backspace=indent,eol,start " Permite apagar TABs e quebras de linha
 28 
 29 " 5️⃣ Removendo espaços desnecessários automaticamente
 30 autocmd BufWritePre * %s/\s\+$//e
 31 
 32 " 6️⃣ Configuração para C na 42 (Norminette)
 33 autocmd FileType c setlocal noexpandtab tabstop=4 shiftwidth=4 softtabstop=4
 34 
 35 "Colocar login e email no HEADER42
 36 let g:user42 = "dleite-b"
 37 let g:mail42 = "dleite-b@student.42lausanne.ch"
