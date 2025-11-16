# 📚 Cronograma de Estudos Interativo (Study Scheduler)

**Study Scheduler interativo (Drag & Drop) para organização semanal de estudos. Inclui monitoramento de limite de horas (6h por dia) e cronômetro de foco, desenvolvido com Vanilla JS.**

Este é um projeto simples e interativo para auxiliar estudantes a organizarem sua rotina diária de estudos para concursos, simulando um programa de planejamento focado no controle de horas e no monitoramento de desempenho.

---

## 📸 Visão Geral do Projeto

Para que você possa visualizar o layout e as funcionalidades, confira a imagem de prévia:

![Preview do Cronograma de Estudos Interativo](imagens/cronograma_preview.png) 
 
---

## 🚀 Acesse o Projeto

Você pode acessar e interagir com a aplicação **diretamente**, sem precisar baixar o código:

**[Acessar Cronograma de Estudos](https://rodrigomenezesdev.github.io/cronograma-estudo/)**

---
📚 Meu Cronograma de Estudos
Este projeto é uma aplicação web interativa de produtividade focada em planejamento semanal de estudos e controle de tempo. Ele oferece uma interface completa para agendamento visual de matérias, com um cronômetro de foco integrado.
🚀 Funcionalidades Principais
💻 Compatibilidade e Interação
O sistema foi desenvolvido com design responsivo, garantindo uma experiência otimizada em dois modos principais:
 * Modo Desktop/Computador: Ideal para visualização ampla da tabela e uso do recurso Arrastar e Soltar (Drag and Drop) das matérias.
 * Modo Mobile/Celular: A interface se ajusta para oferecer uma visualização limpa e prioriza o toque/clique para agendamento rápido (via botão +).
1. 📅 Gerenciamento e Visualização do Cronograma Semanal
 * Agendamento Flexível: É possível agendar matérias de duas formas:
   * Arrastar e Soltar (Drag and Drop): Simplesmente clique e arraste a matéria da lista lateral para o bloco da semana escolhida na tabela.
   * Adição Rápida por Toque/Clique:
     ✨ ➕ Adição Rápida: O botão + em cada dia da semana permite adicionar matérias rapidamente via um modal de seleção.

 * Tabela Detalhada por Dia: O cronograma exibe colunas para o Dia da Semana, Matérias Planejadas, Total de Horas e Status.
 * Controle de Limite Diário: O sistema calcula o total de horas agendadas e exibe um Status visual (OK, ALERTA ou EXCEDEU) caso o limite de 6.0 horas diárias seja ultrapassado.
 * Edição Rápida de Horas: Ao clicar em uma matéria agendada, o usuário pode editar o tempo (em decimal) dedicado àquela sessão ou remover a matéria do dia.
 * Destaque do Dia Atual: A linha do dia correspondente ao dia de acesso é destacada visualmente.
 * Persistência de Dados: O cronograma é salvo no navegador usando localStorage.
2. 📚 Criação e Gestão de Matérias Personalizadas
 * Customização de Matérias: Através de um modal dedicado, o usuário pode cadastrar novas matérias, definindo o Nome, Horas Padrão (em decimal) e uma Cor de Destaque personalizada.
 * Listagem Lateral: Matérias customizadas prontas para serem arrastadas.
 * Edição/Exclusão: O usuário pode excluir matérias existentes.
3. ⏱️ Cronômetro Integrado de Foco (Produtividade)
 * Controle de Tempo: Possui um cronômetro na parte superior com funções de Iniciar, Pausar e Zerar.
 * Formato H:M:S: O tempo é exibido em um formato claro de horas, minutos e segundos.
🛠️ Tecnologias Utilizadas
Este projeto é uma aplicação web pura (Vanilla), utilizando as tecnologias fundamentais:
 * HTML5: Estrutura semântica da página.
 * CSS3: Estilização, layout Flexbox, Media Queries e variáveis CSS (:root).
 * JavaScript (ES6+): Lógica de Drag and Drop, gerenciamento de modais, cálculo de horas e persistência de dados via localStorage.
▶️ Como Acessar o Projeto
O projeto está hospedado e pode ser acessado diretamente através do seguinte link:
**[Acessar Cronograma de Estudos](https://rodrigomenezesdev.github.io/cronograma-estudo/)**

 * Acesso Direto: Clique no link acima para abrir a aplicação em qualquer navegador moderno (Chrome, Firefox, Edge, etc.).
Seu README está completo! Espero que ajude a divulgar as funcionalidades do seu projeto.


---

## 🛠️ Tecnologias Utilizadas

Este é um projeto puramente **Front-end** construído com:

* **HTML5:** Estrutura semântica da página, tabela e componentes.
* **CSS3:** Estilização, layout responsivo básico e definição das cores por matéria/dia.
* **JavaScript (Vanilla JS):** Lógica interativa do *Drag and Drop*, cálculos de horas, controle do cronômetro, validação de limites e manipulação do DOM.

---

## ⚙️ Como Usar (Guia Rápido)

1.  **Arraste:** Escolha uma matéria na lista à esquerda e arraste-a para o dia correspondente na coluna "Matérias Planejadas".
2.  **Monitore:** Observe a coluna "Status" para garantir que você esteja dentro da meta de **2h a 6h** diárias.
3.  **Ajuste:** Clique no nome da matéria dentro da tabela para ajustar o tempo de estudo.
4.  **Cronometre:** Use os botões **Iniciar/Pausar** no cronômetro para medir o seu tempo de foco diário.

---

## 🤝 Contribuição

Sinta-se à vontade para sugerir melhorias, reportar bugs ou enviar Pull Requests.

1.  Faça um Fork do projeto.
2.  Crie uma nova branch (`git checkout -b feature/minha-feature`).
3.  Faça o commit das suas alterações (`git commit -m 'feat: Adiciona nova funcionalidade X'`).
4.  Faça o push para a branch (`git push origin feature/minha-feature`).
5.  Abra um Pull Request.

---

Feito com ❤️ por [RodrigoMenezesdev]
