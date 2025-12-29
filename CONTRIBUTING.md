# 🤝 Guia de Contribuição - HDEV

Ficamos felizes em ver você por aqui! Para manter o nível de qualidade "High-End" da nossa organização, seguimos um fluxo de trabalho profissional (Gitflow simplificado).

## 🚀 Como enviar seus exercícios ou projetos

### 1. Preparação
Antes de começar, certifique-se de que você tem o Git instalado e está no nosso grupo de WhatsApp.

### 2. O Processo Técnico
Nunca envie código diretamente para a branch `main`. Siga estes passos:

1. **Fork o Repositório:** Crie uma cópia deste projeto na sua conta.
2. **Crie uma Branch:** Use o padrão `feat/nome-do-exercicio-seu-nome`.
   - Exemplo: `git checkout -b feat/logica-algoritmos-joaosilva`
3. **Desenvolva:** Escreva seu código seguindo os princípios de Clean Code.
4. **Commit:** Use mensagens claras e em português.
   - Exemplo: `git commit -m "feat: adiciona resolução do desafio de lógica 01"`
5. **Push e Pull Request:** Envie para o seu fork e abra um **Pull Request (PR)** para a nossa `main`.

### 3. O Code Review (A Mentoria)
Uma vez que você abrir o PR, um mentor (ou um aluno avançado) irá revisar seu código. 
- Não leve as críticas para o lado pessoal! O **Code Review** é o momento onde você mais vai aprender.
- Se pedirmos alterações, faça-as na mesma branch e dê o push novamente.

## 📏 Padrões de Qualidade
- **Nomes Significativos:** Variáveis não devem ser `a` ou `b`, mas `idadeUsuario` ou `listaProdutos`.
- **Comentários:** Use apenas se o código não for autoexplicativo.
- **Estrutura:** Mantenha os arquivos organizados dentro das pastas correspondentes.

## ❓ Precisa de ajuda?
Se travar em algum desafio, abra uma **Issue** com a tag `help wanted` descrevendo o que você já tentou fazer.
