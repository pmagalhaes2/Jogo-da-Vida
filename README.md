# Jogo-da-Vida
Jogo da Vida Desenvolvido em Python.

As regras sao simples: 
1. Qualquer célula viva com menos de dois vizinhos vivos morre de solidão. 
2. Qualquer célula viva com mais de três vizinhos vivos morre de superpopulação. 
3. Qualquer célula morta com exatamente três vizinhos vivos se torna uma célula viva. 
4. Qualquer célula viva com dois ou três vizinhos vivos continua no mesmo estado para a próxima geração.

#################### D O C U M E N T A Ç Ã O ###################################
#Variáveis:
# i --> é usado para percorrer as linhas de uma matriz
# j --> é usado para percorrer as colunas de uma matriz
# tx --> é o tamanho 'x' da matriz principal
# ty --> é o tamanho 'y' da matriz principal
# m --> é a matriz principal
# n --> é uma cópia da matriz principal
# v --> é uma matriz que guarda o nº de vizinhos atuais de cada célula
# aux_cont --> guarda quantas vezes foi chamada a função
# cont_ger --> conta qual o numero da geração atual
#
#Funções:
# def_var --> inicializa as variáveis globais
# def_bts --> inicializa os botões globais
# destroy_bt--> destroi os botões para serem reUpados em "def_bts" posteriormente
# callback --> é a função a ser executada quando o botão bt1 é clicado
# callback_2--> é a função a ser executada quando o botão bt2 é clicado
# geracao -->
# monta -->
###############################################################################
