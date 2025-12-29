### 📋 Checklist de Avaliação: Padrão de Engenharia HDEV

Este documento define o que separa um código "que funciona" de um código "profissional".

#### 1. Lógica e Funcionalidade (O Core)

* [ ] **Funciona?** O código resolve o problema proposto no desafio?
* [ ] **Casos de Borda (Edge Cases):** O código lida com entradas inválidas? (Ex: números negativos, strings vazias, valores nulos).
* [ ] **Simplicidade:** A lógica é a mais simples possível ou o aluno "complicou" sem necessidade?

#### 2. Clean Code (Legibilidade)

* [ ] **Nomes de Variáveis:** São significativos e em português (ou inglês, se padronizado)? (Evitar `a`, `x`, `temp`).
* [ ] **Nomes de Funções:** Seguem o padrão `verbo + substantivo`? (Ex: `calcularBonus`, e não apenas `bonus`).
* [ ] **Tamanho das Funções:** As funções fazem apenas uma coisa? (Single Responsibility).
* [ ] **Comentários:** O código é autoexplicativo? (Comentários devem explicar o "porquê", não o "como").

#### 3. Padrões Git (Profissionalismo)

* [ ] **Título do PR:** Segue o padrão `feat: nome do desafio` ou `fix: correção x`?
* [ ] **Commits:** As mensagens de commit são claras e atómicas (uma mudança por commit)?
* [ ] **Branch:** A branch foi criada com o padrão correto (ex: `feat/nome-aluno-desafio`)?

#### 4. Performance e Boas Práticas

* [ ] **DRY (Don't Repeat Yourself):** Existe código duplicado que poderia ser uma função ou loop?
* [ ] **Segurança Básica:** Existe algum risco óbvio (ex: credenciais hardcoded, loops infinitos)?
* [ ] **Identação:** O código está bem formatado e fácil de ler?

---

### 🎓 Como dar o Feedback (O Tom do Mentor)

**Exemplo de Feedback Negativo (Amador):**

> "O teu código está uma confusão e os nomes das variáveis estão errados. Refaz."

**Exemplo de Feedback HDEV (Profissional):**

> "Bom trabalho na lógica do bónus, [Nome do Aluno]! A solução funciona bem. Para chegarmos ao nível **Bronze**, tenho duas sugestões:
> 1. Notei que usaste `var1` e `var2`. Que tal mudarmos para `salarioBase` e `totalHorasExtras` para tornar o código mais legível?
> 2. O que aconteceria se o funcionário tivesse horas negativas? Tenta adicionar uma validação para isso.
> Aguardo o teu ajuste para aprovarmos este PR! 🚀"
> 
> 

---
