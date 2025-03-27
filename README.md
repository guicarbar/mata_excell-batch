# mata_excell-batch

> Já teve problemas com o Excel te atrapalhando ou dando erro porque um arquivo estava aberto enquanto você rodava algum programa?

Aqui está a solução!

> Criei duas versões de um arquivo .bat que encerra qualquer processo do Excel aberto na sua máquina, evitando dores de cabeça.


## Como funciona?

- **Versão**: Exibe um retorno no terminal, sinalizando qual processo foi encerrado.  
- **Versão**: Apenas execute o arquivo com **dois cliques** e pronto! O Excel será fechado automaticamente, sem mensagens extras.  

> Escolha a versão que mais combina com seu fluxo de trabalho e nunca mais tenha problemas com processos travados no Excel!



## Tecnologias

![Bash Script](https://img.shields.io/badge/bash_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)


## Códigos para Visualização

### Com resposta:  
```bat
  @echo off
  taskkill /F /IM excel.exe
  echo Excel foi fechado!
  pause
```

### Sem resposta:
```bat
  taskkill /F /IM excel.exe
```


## Contribuir

1. **Clonar projeto:**: `git clone https://github.com/guicarbar/mata_excell-batch.git`
2. **Criar feature/branch:**: `git checkout -b feature/Nome-da-branch`


## Licença

Este projeto está sob a licença [MIT](LICENSE) License.