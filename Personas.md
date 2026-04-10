### Ator 1: Alunos
[cite_start]*Usuários principais que se beneficiam de um ambiente interativo e acessível.* [cite: 352, 385]

#### 1. Familiarizado com Tecnologia
**Lucas Martins**
* **Perfil:** 20 anos, estudante de Engenharia de Computação. [cite_start]Acessa o Campus Virtual a todo instante, mesclando o uso entre um notebook potente e seu smartphone[cite: 352].
* [cite_start]**Função no sistema:** Usuário consumidor – envia atividades, responde provas online, baixa conteúdos e interage com notificações automáticas[cite: 355, 360].
* **Nível de conhecimento tecnológico:** Avançado. Nativo digital, espera que as interfaces funcionem de maneira muito rápida e domina atalhos no teclado.
* **Objetivos e motivações:**
    * [cite_start]Visualizar as notas e contestá-las de forma ágil[cite: 357].
    * [cite_start]Receber recomendações de conteúdos baseadas em suas dificuldades[cite: 361].
    * [cite_start]Fazer download de conteúdos em vídeo para acesso offline no trajeto da faculdade[cite: 360, 361].
* **Frustrações / dores:**
    * [cite_start]Fica muito frustrado com instabilidade no sistema em dias de entrega de grandes trabalhos[cite: 348].
    * [cite_start]Odeia interfaces complexas que exigem muitos cliques para enviar um simples anexo[cite: 348].
* **Cenários de uso típicos:**
    * [cite_start]Enviar o arquivo da atividade pelo celular de madrugada[cite: 355].
    * [cite_start]Usar os fóruns públicos para ajudar colegas com dúvidas em disciplinas[cite: 358].
* **Resumo da persona:** Lucas precisa de um sistema rápido, de alta disponibilidade e com notificações em tempo real, que acompanhe o seu ritmo acelerado e otimize o seu aprendizado prático.

#### 2. Não Familiarizado com Tecnologia
**Carlos Silva**
* **Perfil:** 48 anos, estudante de Administração no período noturno, voltando a estudar após 20 anos. Utiliza o computador da biblioteca e o celular.
* [cite_start]**Função no sistema:** Usuário consumidor – consome os materiais da disciplina e verifica seu andamento no curso[cite: 352].
* **Nível de conhecimento tecnológico:** Básico. Sente insegurança ao utilizar plataformas educacionais e teme "apagar alguma coisa" por engano.
* **Objetivos e motivações:**
    * [cite_start]Encontrar os materiais de estudo compartilhados de forma fácil[cite: 358].
    * [cite_start]Enviar atividades corretamente, com confirmação visual de sucesso[cite: 355].
    * [cite_start]Ter facilidade para enviar dúvidas privadas ao professor[cite: 358].
* **Frustrações / dores:**
    * [cite_start]Não entende como funciona a contestação de faltas ou como agendar provas substitutivas online[cite: 359, 360].
* **Cenários de uso típicos:**
    * [cite_start]Verificar a sua frequência e notas no final da semana[cite: 357, 359].
    * [cite_start]Responder a atividades propostas com um documento de texto simples[cite: 355].
* **Resumo da persona:** Carlos necessita de uma plataforma de design intuitivo, com fluxos lineares, comunicação fácil com o docente e que dê segurança em suas interações.

## Recursos de Acessibilidade
### 1. Cega (Total ausência de visão)
*Ator Representado: Aluno*

*Amanda Costa*
* *Perfil:* 24 anos, estudante de Direito. Nasceu cega e acessa a plataforma via notebook utilizando leitor de tela avançado (como o NVDA) e o celular via VoiceOver. 
* *Função no sistema:* Usuário consumidor – consome materiais, realiza avaliações online e acompanha a vida acadêmica.
* *Nível de conhecimento tecnológico:* Avançado em softwares de acessibilidade. Navega rapidamente utilizando atalhos de teclado.
* *Objetivos e motivações:*
    * Ler PDFs e materiais de estudo diretamente pela plataforma de forma autônoma.
    * Realizar provas e testes online sem depender da ajuda de colegas ou transcritores.
    * Receber notificações de prazos e notas que sejam lidas claramente pelo sistema.
* *Frustrações / dores:*
    * Materiais didáticos postados como "imagens escaneadas" sem reconhecimento óptico de caracteres (OCR) ou texto alternativo (Alt Text).
    * Botões de interface sem rótulos (ex: um ícone de "disquete" para salvar que o leitor de tela lê apenas como "botão não rotulado").
    * Pop-ups de erro visuais que não são anunciados pelo leitor de tela.
* *Cenários de uso típicos:*
    * Fazer download de artigos acadêmicos na véspera da prova.
    * Participar de fóruns de discussão usando a navegação por tabulação (tecla TAB).
* *Resumo da persona:* Amanda não enxerga a interface, ela a "ouve". Depende que o Campus Virtual siga rígidos padrões de código (WCAG/ARIA) para que a navegação faça sentido lógico.

---

### 2. Baixa Visão (Visão Subnormal)
*Ator Representado: Professor*

*Fernando Lima*
* *Perfil:* 46 anos, professor de Literatura. Devido a uma condição degenerativa, possui baixa visão (visão subnormal) e depende de ferramentas nativas de magnificação (zoom da tela ajustado entre 200% e 400%).
* *Função no sistema:* Usuário produtor – elabora provas, corrige materiais dissertativos e lança faltas.
* *Nível de conhecimento tecnológico:* Intermediário. Focado em configurar seu computador para o máximo de conforto visual.
* *Objetivos e motivações:*
    * Criar questionários no sistema com conforto e sem cansar a vista.
    * Ler respostas longas dos alunos e fornecer feedback contínuo.
    * Visualizar a lista de chamada e lançar frequências com agilidade.
* *Frustrações / dores:*
    * Layouts que "quebram" completamente, sobrepõem botões ou escondem menus essenciais quando o zoom do navegador é ativado.
    * Fontes finas ou em tons pastéis de baixo contraste (ex: cinza claro sobre fundo branco) que se tornam invisíveis para ele.
* *Cenários de uso típicos:*
    * Acessar o diário de classe no final do dia para lançar notas e frequências usando uma tela muito ampliada.
* *Resumo da persona:* Fernando precisa de um design altamente responsivo, tipografia legível e contraste elevado, garantindo que o sistema continue funcional mesmo quando fortemente ampliado.

---

### 3. Daltonismo (Deficiência de Visão de Cores)
*Ator Representado: Gestor Acadêmico*

*Ricardo Mendes*
* *Perfil:* 41 anos, Coordenador de Curso. Possui Deuteranopia (dificuldade severa em distinguir tons de verde e vermelho). Usa o sistema diariamente em seu escritório para tomada de decisões.
* *Função no sistema:* Gestor – acompanha os índices de sucesso acadêmico, retenção e desempenho geral das turmas.
* *Nível de conhecimento tecnológico:* Avançado. Trabalha muito com dados, dashboards e relatórios.
* *Objetivos e motivações:*
    * Interpretar rapidamente gráficos de desempenho de dezenas de turmas.
    * Identificar professores com atraso no lançamento de notas ou alunos em risco de evasão.
* *Frustrações / dores:*
    * Dashboards e gráficos gerenciais que utilizam *apenas a cor* para transmitir informações (ex: vermelho para turmas "em risco" e verde para "no prazo"), fazendo com que ele não consiga diferenciar o status.
    * Mensagens de erro ou sucesso baseadas apenas na mudança de cor da fonte.
* *Cenários de uso típicos:*
    * Abrir os painéis estatísticos institucionais na segunda-feira pela manhã para emitir relatórios semanais para a diretoria.
* *Resumo da persona:* Ricardo precisa que a interface não dependa exclusivamente de cores para comunicar estados. Ele precisa de ícones complementares (ex: um "X" para erro, um "Check" para sucesso) e gráficos com texturas ou rótulos de texto claros.

---

### 4. Sensibilidade à Luz (Fotofobia)
*Ator Representado: Aluno (Pós-graduação)*

*Helena Castro*
* *Perfil:* 28 anos, aluna de mestrado em Engenharia. Devido a enxaquecas crônicas e astigmatismo severo, possui alta sensibilidade à luz (fotofobia) e fadiga visual rápida frente às telas.
* *Função no sistema:* Usuário consumidor e pesquisador – passa horas consecutivas lendo e produzindo dentro da plataforma.
* *Nível de conhecimento tecnológico:* Avançado. Utiliza softwares para diminuir a luz azul do monitor, mas depende de interfaces bem projetadas.
* *Objetivos e motivações:*
    * Estudar de forma prolongada, à noite, lendo textos e fóruns diretamente no Campus Virtual.
    * Navegar entre as páginas de forma fluida sem gatilhos para dor de cabeça.
* *Frustrações / dores:*
    * Plataformas com fundos brancos "puros" e brilhantes, sem opção nativa de "Modo Escuro" (Dark Mode).
    * Animações bruscas, transições de tela piscantes ou pop-ups muito luminosos que causam desconforto físico imediato.
* *Cenários de uso típicos:*
    * Leitura contínua de extensa bibliografia e redação de respostas longas no sistema durante a madrugada.
* *Resumo da persona:* Helena necessita urgentemente de um botão de "Modo Escuro" oficial da plataforma, com tons de cinza escuro bem balanceados, e um sistema sem animações exageradas ou clarões repentinos.