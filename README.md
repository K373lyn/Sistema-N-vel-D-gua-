!Sistema de Monitoramento de Nível de Água!
---
-> Este projeto simula um sistema simples de monitoramento de um reservatório de água, exibindo alertas no terminal com cores diferentes de acordo com o nível da água.

!Objetivo!
---
-> Demonstrar o uso dos seguintes conceitos em Python:
--> Listas
--> Funções
--> Estruturas de repetição
--> Biblioteca externa (Colorama)

!Funcionamento!
---
-> O sistema trabalha com 5 níveis de água, representando diferentes situações do reservatório
-> O programa percorre os níveis e exibe mensagens coloridas no terminal

!Código!
---
```from colorama import Fore, Style, init

init()

#Lista de mensagens
mensagens = [
    "Nível 1 - Muito baixo (CRÍTICO)",
    "Nível 2 - Baixo",
    "Nível 3 - Médio",
    "Nível 4 - Alto",
    "Nível 5 - Muito alto (ALERTA)"
]

#Função pra definir cor
def definir_cor(nivel):
    if nivel == 1:
        return Fore.RED
    elif nivel == 2:
        return Fore.YELLOW
    elif nivel == 3:
        return Fore.GREEN
    elif nivel == 4:
        return Fore.CYAN
    else:
        return Fore.BLUE

#Simulação
for i in range(5):
    cor = definir_cor(i + 1)
    print(cor + mensagens[i])

print(Style.RESET_ALL)
```

!Obrigada!
---
