# Enquete de Linguagens de Programação

Um projeto simples em **PHP** com **HTML** e **CSS** para criar uma enquete onde usuários podem votar na sua linguagem de programação favorita. Os votos são armazenados na **sessão** e podem ser visualizados em tempo real. Também é possível **resetar** a votação.

---

## Funcionalidades

- Votação em linguagens de programação: PHP, Java, Python, JavaScript e C#.
- Exibição do resultado da enquete em tempo real.
- Possibilidade de **votar novamente** sem perder os votos anteriores.
- Botão para **resetar a votação**.
- Interface moderna e responsiva usando CSS.

---

## Tecnologias Utilizadas

- **PHP**: Para processar votos e gerenciar sessões.
- **HTML5**: Estrutura do formulário e da página de resultados.
- **CSS3**: Estilização com cores, gradientes, botões e layout responsivo.

---

## Estrutura do Projeto
```text
enquete-simples-php/
│
├─ src/
│   ├─ enquete.html      # Formulário da enquete
│   ├─ resultado.php     # Processamento de votos e exibição dos resultados
│   └─ style.css         # Estilos da página
└─ README.md             # Documentação do projeto
```

---

## Como Usar

1. **Abrir o arquivo `enquete.html`** no navegador.
2. Selecionar a linguagem de programação favorita.
3. Clicar em **Votar**.
4. A página redireciona para **resultado.php**, mostrando os votos atualizados.
5. Para votar novamente, clicar em **Votar novamente**.
6. Para resetar todos os votos, clicar em **Resetar votação**.

---

## Exemplo de Interface

- Página de votação: Formulário limpo com botões de opção para cada linguagem.
- Página de resultados: Lista de votos por linguagem com opções para votar novamente ou resetar.

---

## Observações

- Os votos são armazenados **apenas na sessão**, ou seja, se a página for fechada ou o servidor reiniciado, os votos serão perdidos.
- Ideal para **projetos de aprendizado** e demonstrações de enquetes simples.

---

## Autor

**Matheus Trindade**  
Curso: Tecnologia em Análise e Desenvolvimento de Sistemas – FATEC Campinas
