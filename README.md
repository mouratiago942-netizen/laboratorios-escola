# laboratorios-escola
Sistema de Reserva de Laboratórios (Escolar)

Este é um projeto que se desenvolve para resolver um problema comum em ambientes escolares: a organização e o agendamento de laboratórios. A ideia foi criar uma interface simples, rápida e que evitasse o conflito de horários entre professores e turmas.
O sistema permite gerenciar cadastros de professores, turmas e monitores, além de oferecer um calendário interativo para marcação de eventos e reservas por períodos.

Funcionalidades
Autenticação Restrita: Sistema de login e cadastro validando e-mails específicos (ex: @gmail.com).

Gestão de Cadastros: Painel sonoro para adicionar ou remover professores, turmas e monitores.

Interativo:

Navegação por mês e ano.

Destaque visual para datas com eventos ou feriados.

Menu de contexto (botão direito) para adicionar interferências rápidas a dias específicos.

Reserva por Slots: Divisão do dia em 10 horários (slots) para cada laboratório.

Persistência de Dados: Tudo é salvo não localStorage, o que significa que os dados não podem ser atualizados a página, sem a necessidade imediata de um banco de dados externo.

🛠️ Tecnologias Utilizadas
Para este projeto, foquei em manter as coisas leves e funcionais usando a "trindade" básica da web:

HTML5: Estrutura semântica dos rótulos e modais.
CSS3: Estilização responsiva e estados visuais (embora o foco aqui tenha sido a lógica).
JavaScript (Vanilla): Toda a manipulação de DOM, lógica do calendário e gerenciamento do localStorage.

O que eu aprendi/pratiquei?
Construir esse sistema me ajudou a consolidar conceitos importantes:
Manipulação de Arrays e Objetos: Essencial para renderizar listas de professores e tabelas de horários.
Lógica de Dados e Hora: Gerar um calendário do zero (calculando dias do mês e dias da semana) foi um ótimo desafio de lógica.

Template Literals: Usei para criar componentes dinâmicos no HTML diretamente pelo JS.

UX Simples: O uso de modais e trocas de garrafas sem recarregar a página (estilo SPA).
