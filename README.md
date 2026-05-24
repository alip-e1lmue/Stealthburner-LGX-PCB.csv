# Introdução

Esta aula trata dos comandos declarados no nó de scripts do arquivo de manifesto do projeto.

No editor dá para executar um comando do manifesto direto, pelo botão de executar que aparece ao lado de cada item no painel de tarefas.

![running a package.json script directly in VSCode](images/executando-pelo-editor.png)

Abaixo está o nó de scripts do manifesto. Repare que, quando o comando precisa do interpretador, ele aparece antes do nome do arquivo (considerando que o binário está no caminho de busca do sistema):

![package.json scripts](images/exemplo-de-comando.png)

Se um comando precisa de mais de uma etapa, dá para encadear com o operador de sequência (como na linha do exemplo anterior) ou criar um comando separado que chame os outros.

Abaixo aparecem nomes comuns de comandos. Note o uso de dois pontos em alguns nomes:

![common scripts](images/comandos-comuns.png)

Segundo a aula, não existe regra universal de nomenclatura, mas há recomendações:

- agrupar comandos por contexto, usando prefixos como o de testes ou o de inicialização;
- separar contexto e ação com dois pontos, embora exista exemplo em projeto público que usa hífen (menos legível).

Ilustrando o texto anterior:


### Side note

Anotacao pessoal, sem relacao direta com o restante do texto.

![naming conventions of scripts](images/convencoes-de-nomes.png)

Outra dica: nomes claros e padronizados deixam o trabalho de todo mundo mais simples.


# Links diversos

O material deste módulo está num repositório público da trilha.

A documentação oficial do gerenciador de pacotes cobre o assunto.

E existe um exemplo real num projeto público de biblioteca de interface.