Sistema de Monitoramento de Nível de Água


Este projeto simula um sistema simples de monitoramento de um reservatório de água, exibindo alertas no terminal com cores diferentes de acordo com o nível da água.



Objetivo


Demonstrar o uso dos seguintes conceitos em Python:




Listas


Funções


Estruturas de repetição


Biblioteca externa (Colorama)




Aplicando esses elementos em um cenário de monitoramento.



Funcionamento


O sistema trabalha com 5 níveis de água, representando diferentes situações do reservatório:




Nível
Situação
Cor




1
Muito baixo (crítico)
Vermelho


2
Baixo
Amarelo


3
Médio
Verde


4
Alto
Ciano


5
Muito alto (alerta)
Azul




O programa percorre os níveis e exibe mensagens coloridas no terminal.



Lógica do Projeto




Uma lista armazena os níveis e suas descrições


Uma função define a cor com base no nível informado


Um laço de repetição (for) simula o monitoramento


A biblioteca Colorama é utilizada para aplicar cores no terminal





Tecnologias Utilizadas




Python 3


Colorama





Como Executar


1. Instalar a biblioteca


pip install colorama



2. Executar o programa


python main.py




Estrutura do Projeto


monitoramento-reservatorio/
│
├── main.py
└── README.md




Possíveis Melhorias




Implementar entrada de dados pelo usuário


Simular leitura de sensores em tempo real


Criar interface gráfica





Autoria


Projeto desenvolvido para fins acadêmicos.

