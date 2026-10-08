# Lista_duplamente_encadeada

Uma implementação de uma lista duplamente encadeada em C++ com operações de inserção, remoção, consulta, inversão e persistência em arquivos.

## Descrição

Este projeto implementa uma estrutura de dados de lista duplamente encadeada, com nós que possuem ponteiros para o elemento anterior (`prev`) e para o próximo (`next`). A classe `List` oferece diversas operações para manipular a lista, incluindo:

- Inserção no início, no fim e em uma posição específica
- Remoção do início, do fim e de uma posição específica
- Consulta do primeiro, último e de qualquer posição
- Alteração de elementos em uma posição
- Inversão da lista
- Limpeza da lista
- Salvar e carregar dados em arquivos binários e de texto

## Como compilar

```bash
g++ -o lista lista.cpp
```

## Como executar

```bash
./lista
```

## Menu do programa

O programa apresenta um menu interativo com as seguintes opções:

- Inserir no início
- Inserir no final
- Inserir em uma posição
- Remover do início
- Remover do final
- Remover de uma posição
- Consultar primeiro elemento
- Consultar último elemento
- Consultar uma posição
- Alterar uma posição
- Exibir a lista nos dois sentidos
- Exibir a lista do final para o início
- Inverter a lista
- Limpar a lista
- Salvar lista em `dados.bin`
- Substituir lista pelos dados de `dados.bin`
- Salvar lista em `dados.txt`
- Carregar `dados.txt` em ordem inversa
- Salvar lista em ordem inversa em `invertida.bin`
- Acrescentar `invertida.bin` ao final da lista
- Salvar pares de `invertida.bin` em `texto.txt`
- Converter `texto.txt` para `converte.bin`
- Sair

## Arquivos gerados

Ao executar algumas operações, o programa pode gerar os seguintes arquivos na pasta do projeto:

- `dados.bin`
- `dados.txt`
- `invertida.bin`
- `texto.txt`
- `converte.bin`

Esses arquivos são ignorados pelo Git através do `.gitignore`.

## Observação

O código foi desenvolvido como exemplo de estrutura de dados em C++ e pode ser usado para fins acadêmicos e de estudo.
