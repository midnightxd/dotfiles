Explicação dos arquivos dentro da pasta setup:

1. compton.conf: É o arquivo de configuração do compton. O compton é um
compositor de janelas para o Xorg.

2. config: É o arquivo de configuração do i3wm(requer o i3wm e i3status instalalo).

3. vimrc: É o arquivo de configuração do vim (é nescessário ter os plugins instados).

    Localização do arquivo vimrc:

    ~/.vim +
           |
           +- vimrc
    
    Montagem dos diretórios do vim packages

    ~/vim +
          |
          +- /pack +
                   |
                   +- /packages +
                                |
                                +- /start

    Obs: A pasta start contém os plugins que são carregados na inicialização do vim.
