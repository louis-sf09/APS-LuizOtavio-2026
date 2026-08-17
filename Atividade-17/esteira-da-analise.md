# Esteira da Análise — BiblioTech

**Estudante:** LUIZ OTÁVIO DE SOUZA FREO

## Funcionalidade 1: Reservar livro

- **1. Fala do cliente:** "Eu queria poder deixar um livro reservado para mim, para que caso eu demore para pega-lo outra pessoa não pegue antes de mim."
- **2. História de usuário:** Como Leitor, quero reservar um livro, para que possa empresta-lo futuramente.
- **3. Requisito:** RF01 — O sistema deve permitir a reserva de livros disponíveis.
- **4. Caso de uso (RF01):** Ator Leitor → "Reservar livro"

## Funcionalidade 2: Cadastrar livro

- **1. Fala do cliente:** "Eu gostaria de poder cadastrar novos livros no sistema, porque as vezes recebemos livros novos."
- **2. História de usuário:** Como Bibliotecário, quero cadastrar livros no sistema, para que novos livros possam ser emprestados.
- **3. Requisito:** RF02 — O sistema deve permitir o cadastro de livros.
- **4. Caso de uso (RF02):** Ator Bibliotecário → "Cadastrar livro"

## Funcionalidade 3: Consultar acervo

- **1. Fala do cliente:** "Eu queria conseguir ver os livros cadastrados para poder escolher um para reservar."
- **2. História de usuário:** Como Leitor, quero consultar o acervo, para escolher um livro para emprestar.
- **3. Requisito:** RF02 — O sistema deve permitir a consulta de livros cadastrados.
- **4. Caso de uso (RF02):** Ator Leitor → "Consultar acervo"

## Rastreabilidade

| Elipse no diagrama | Veio do requisito | Que veio da fala |
|---|---|---|
| Reservar livro | RF01 | "Eu queria poder deixar um livro reservado para mim, para que caso eu demore para pega-lo outra pessoa não pegue antes de mim." |
|Cadastrar livro | RF02 | "Eu gostaria de poder cadastrar novos livros no sistema, porque as vezes recebemos livros novos." |
| Consultar acervo | RF03 | "Eu queria conseguir ver os livros cadastrados para poder escolher um para reservar." |

## Relacionamento entre casos de uso

- Tipo: «extend»
- Entre: Reservar livro e Consultar acervo
- Por que é esse e não o outro: O leitor consulta o acervo e após isso, pode ou não reservar um livro.

## Autoavaliação

**Conceito pretendido:** A

- Conversei sobre esta atividade com: Profe. Berssa
- Esteira da análise: A
- Diagrama e notação: A
- Rastreabilidade: A
- Organização da entrega: A
