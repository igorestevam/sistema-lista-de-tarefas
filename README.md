# Sistema de Lista de Tarefas

Um sistema web prático e direto ao ponto para cadastro e gerenciamento de tarefas. 
Este projeto foi construído com foco total no funcionamento correto das regras de negócio e usabilidade, rodando 100% no navegador do usuário.

## Funcionalidades

* **Gerenciamento Completo:** Inclusão, edição e exclusão de tarefas através de uma interface limpa utilizando modais (popups).
* **Reordenação Interativa:** O usuário tem controle total sobre a ordem de apresentação das tarefas na tela, podendo subir (↑) ou descer (↓) os registros facilmente.
* **Regras de Negócio e Validações:** * O sistema impede a criação ou edição de tarefas com nomes duplicados.
  * O ID de cada registro é gerado e gerenciado automaticamente.
  * Validação de campos obrigatórios e formatos de dados (padrão brasileiro).
* **Feedback Visual:** Tarefas que possuem um custo igual ou superior a R$ 1.000,00 recebem um destaque visual automático na tabela.
* **Cálculo em Tempo Real:** O rodapé da aplicação exibe de forma dinâmica o somatório total dos custos das tarefas cadastradas.
* **Persistência Local:** Os dados não são perdidos ao recarregar a página. Toda a base de tarefas é salva no `localStorage` do navegador.

## Tecnologias Utilizadas

O sistema foi desenvolvido de forma nativa (Vanilla), garantindo leveza e performance sem a necessidade de bibliotecas ou frameworks externos:

* **HTML5:** Estruturação semântica.
* **CSS3:** Interface moderna, responsiva e amigável.
* **JavaScript:** Lógica de negócio, manipulação dinâmica do DOM (Front-end) e comunicação com o armazenamento local.

## Como acessar e testar

Como a aplicação não depende de instalação ou de um servidor Back-end complexo para rodar, o teste é imediato.

Acesse o sistema pelo navegador:
https://igorestevam.github.io/sistema-lista-de-tarefas/

---
Desenvolvido por Igor Estevam.
