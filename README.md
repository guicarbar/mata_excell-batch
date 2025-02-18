🟢🟡🔴

# 🛠 MataExcell_Batch 🚀

## 🧐 Sobre

Já teve problemas com o **Excel** te atrapalhando ou dando erro porque um arquivo estava aberto enquanto você rodava algum programa?  

Aqui está a solução! 🎉  

Criei **duas versões** de um **arquivo `.bat`** que encerra qualquer processo do Excel aberto na sua máquina, evitando dores de cabeça.  

## 🔹 Como funciona?

- **Versão 1️⃣**: Exibe um retorno no terminal, sinalizando qual processo foi encerrado.  
- **Versão 2️⃣**: Apenas execute o arquivo com **dois cliques** e pronto! O Excel será fechado automaticamente, sem mensagens extras.  

💡 Escolha a versão que mais combina com seu fluxo de trabalho e nunca mais tenha problemas com processos travados no Excel! 😃

---

📌 **Dica:** Use com responsabilidade, pois ele encerrará qualquer instância do Excel em execução.  

## 📜 Códigos para Visualização

### ✅ Com resposta:  
```bat
  @echo off
  taskkill /F /IM excel.exe
  echo Excel foi fechado!
  pause
```

### 🚀 Sem resposta:
```bat

  taskkill /F /IM excel.exe

```


---

> ⚠️ **Observação**: Projetos com o sufixo *-Batch* são programas curtos em .bat para ajudar na vida dos devs.