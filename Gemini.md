# User:

Produza um detalhamento completo de todas as personas do software com 3 personas para cada ator do campus, as personas sendo: Alguem familiarizado com tecnologia, alguem não familiarizado com tecnologia e alguem com deficiencia visual. Exemplo nos slides 5 e 6 dos slides da aula 4.

# Model:

[cite_start]Com base no escopo e no público-alvo do sistema **Campus Virtual** [cite: 352, 353, 354][cite_start], bem como no modelo de personas apresentado na aula de Especificação de Requisitos[cite: 10, 169], abaixo apresento o detalhamento de 9 personas. Foram definidos os três atores principais do sistema (Alunos, Professores e Gestores Acadêmicos), com três perfis distintos para cada um: familiarizado com tecnologia, não familiarizado com tecnologia e com deficiência visual.

---

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
    * [cite_start]Interface com muitos jargões acadêmicos ou excesso de menus o deixa paralisado e confuso[cite: 348].
    * [cite_start]Não entende como funciona a contestação de faltas ou como agendar provas substitutivas online[cite: 359, 360].
* **Cenários de uso típicos:**
    * [cite_start]Verificar a sua frequência e notas no final da semana[cite: 357, 359].
    * [cite_start]Responder a atividades propostas com um documento de texto simples[cite: 355].
* **Resumo da persona:** Carlos necessita de uma plataforma de design intuitivo, com fluxos lineares, comunicação fácil com o docente e que dê segurança em suas interações.

#### 3. Com Deficiência Visual
**Amanda Costa**
* **Perfil:** 24 anos, estudante de Direito, cega, acessa a plataforma via notebook utilizando leitor de tela (como o NVDA).
* [cite_start]**Função no sistema:** Usuário consumidor – participa do aprendizado prático e avaliações[cite: 352].
* **Nível de conhecimento tecnológico:** Avançado no uso de ferramentas de acessibilidade.
* **Objetivos e motivações:**
    * [cite_start]Ter acesso aos materiais de estudo com textos legíveis pelo leitor de tela[cite: 358].
    * [cite_start]Realizar provas e testes online com autonomia e sem precisar de um transcritor[cite: 356].
    * [cite_start]Receber notificações claras sobre compromissos automatizados da universidade[cite: 360].
* **Frustrações / dores:**
    * Material didático postado em forma de imagens não lidas pelo sistema.
    * Botões sem descrição (rótulo) ou fluxos que impedem a navegação apenas por teclado.
* **Cenários de uso típicos:**
    * [cite_start]Consultar sua frequência escolar e fazer o download de textos para estudo[cite: 359, 361].
    * [cite_start]Enviar uma dúvida ao fórum acadêmico e interagir com os retornos[cite: 358].
* **Resumo da persona:** Amanda depende exclusivamente de uma plataforma responsiva e acessível (com adequação WCAG) para conduzir sua formação com autonomia e sem barreiras tecnológicas.

---

### Ator 2: Professores
[cite_start]*Responsáveis pela gestão de disciplinas e atividades, facilitando o ensino.* [cite: 353, 386]

#### 1. Familiarizado com Tecnologia
**Roberto Almeida**
* **Perfil:** 35 anos, professor de programação. Tem uma rotina agitada e trabalha sempre em seu notebook pessoal.
* [cite_start]**Função no sistema:** Usuário produtor – responsável por criar, modificar e excluir disciplinas, gerir notas e atividades[cite: 355, 356].
* **Nível de conhecimento tecnológico:** Avançado. Entusiasta de automação e inovações pedagógicas.
* **Objetivos e motivações:**
    * [cite_start]Aplicar testes online de correção automática e gerenciar notas rapidamente (lançar e editar)[cite: 356].
    * [cite_start]Compartilhar rotinas, links e repositórios nas áreas de material de estudo[cite: 358].
    * [cite_start]Automatizar o registro de frequência[cite: 359].
* **Frustrações / dores:**
    * [cite_start]Sistemas engessados que falham no alto fluxo e o impedem de aplicar provas simultâneas[cite: 348].
    * Excesso de burocracia do sistema ou muitos cliques para gerar uma única tarefa.
* **Cenários de uso típicos:**
    * [cite_start]Subir materiais extras de estudo no sistema de recomendações de conteúdo[cite: 358, 361].
    * [cite_start]Responder a múltiplas dúvidas privadas de uma só vez antes da prova[cite: 358].
* **Resumo da persona:** Roberto procura eficiência; quer um ambiente robusto, estável e ágil que lhe permita dedicar mais tempo ao ensino do que à burocracia do sistema.

#### 2. Não Familiarizado com Tecnologia
**Sônia Regina**
* **Perfil:** 58 anos, professora de Sociologia, possui muita bagagem acadêmica, porém habituada aos métodos presenciais (cadernetas em papel).
* [cite_start]**Função no sistema:** Usuário produtor – gerencia sua disciplina e posta conteúdos para os estudantes[cite: 355].
* **Nível de conhecimento tecnológico:** Básico. Trabalha com um computador fixo na sala dos professores.
* **Objetivos e motivações:**
    * [cite_start]Conseguir aplicar presença e faltas em poucos cliques e sem se confundir[cite: 359].
    * [cite_start]Postar arquivos PDF de leitura ou vídeos para a disciplina[cite: 358, 360].
    * [cite_start]Lançar e editar notas de maneira contínua, sem perder dados[cite: 356].
* **Frustrações / dores:**
    * [cite_start]Sente-se perdida com dezenas de funcionalidades e opções de layout[cite: 348].
    * [cite_start]Enfrenta dificuldades quando o aluno solicita o agendamento de uma prova substitutiva e ela não sabe onde aprovar[cite: 360].
* **Cenários de uso típicos:**
    * [cite_start]Aplicar frequências logo no fim da aula usando o modo simplificado[cite: 359].
    * [cite_start]Ler fóruns de dúvida e lançar notas das provas dissertativas manuscritas[cite: 356, 358].
* **Resumo da persona:** Sônia demanda uma navegação direta e clara, livre de distrações, garantindo que o lado operacional não seja um obstáculo para a sua excelente didática.

#### 3. Com Deficiência Visual
**Fernando Lima**
* **Perfil:** 46 anos, professor de Literatura. Possui baixa visão (visão subnormal) e precisa sempre do auxílio de ampliadores de tela.
* [cite_start]**Função no sistema:** Usuário produtor – elabora provas, corrige materiais e fornece feedback contínuo aos estudantes[cite: 355, 356].
* **Nível de conhecimento tecnológico:** Intermediário. Conhece bem ferramentas de magnificação de sistema.
* **Objetivos e motivações:**
    * [cite_start]Criar questionários e ler respostas dissertativas longas dos alunos com conforto[cite: 355, 356].
    * [cite_start]Aplicar presenças observando rapidamente os nomes da lista[cite: 359].
* **Frustrações / dores:**
    * [cite_start]Fontes pequenas ou em tons pastéis que não entregam o contraste elevado prometido[cite: 349].
    * O layout "quebrar" ou sobrepor botões quando o zoom da tela é ajustado para 200% ou mais.
* **Cenários de uso típicos:**
    * [cite_start]Acessar a área de gestão de atividades para analisar e devolver trabalhos corrigidos[cite: 355].
    * [cite_start]Visualizar processos de contestação de falta por parte dos alunos[cite: 359].
* [cite_start]**Resumo da persona:** Fernando precisa urgentemente de um design que priorize a experiência de usuário através do alto contraste na fonte e do layout extremamente responsivo para ampliações[cite: 349].

---

### Ator 3: Gestores Acadêmicos
[cite_start]*Utilizaria o software para acompanhar o desenvolvimento dos cursos e dos alunos.* [cite: 354, 388]

#### 1. Familiarizado com Tecnologia
**Juliana Mendes**
* **Perfil:** 41 anos, Coordenadora de Curso. Perfil analítico e muito conectada a tendências e métricas educacionais.
* [cite_start]**Função no sistema:** Gestor – acompanha os índices de sucesso acadêmico e as rotinas dos docentes[cite: 354, 362].
* **Nível de conhecimento tecnológico:** Avançado. Sabe extrair, filtrar e relacionar dados educacionais.
* **Objetivos e motivações:**
    * [cite_start]Usufruir da visualização do desempenho do estudante como suporte a suas decisões operacionais[cite: 362, 367].
    * [cite_start]Acompanhar o nível geral de retenção de alunos decorrente do uso da plataforma[cite: 363].
    * [cite_start]Cruzar dados de faltas e notas para aplicar alertas preventivos de evasão[cite: 356, 359, 362].
* **Frustrações / dores:**
    * [cite_start]Relatórios padronizados e engessados que limitam sua capacidade de pesquisa e filtro de turmas[cite: 348].
    * [cite_start]Falta de integrações com o sistema legado limitando a visão real da universidade[cite: 368].
* **Cenários de uso típicos:**
    * Abrir os painéis do gestor acadêmico na segunda-feira pela manhã para avaliar as turmas com risco de reprovação.
    * [cite_start]Verificar quais docentes estão com o lançamento de notas atrasado[cite: 356, 362].
* **Resumo da persona:** Juliana tem uma atuação baseada em evidências. Ela precisa de dados macro e acesso transparente aos desempenhos globais (docentes e discentes) para tomar ações corretivas a tempo.

#### 2. Não Familiarizado com Tecnologia
**Paulo Ribeiro**
* **Perfil:** 63 anos, Diretor da unidade. Excelente estrategista, mas gerencia suas atividades principalmente por reuniões e documentos impressos pela secretaria.
* [cite_start]**Função no sistema:** Gestor – supervisão executiva e suporte institucional[cite: 354, 367].
* **Nível de conhecimento tecnológico:** Básico. Prefere dashboards (painéis) extremamente resumidos em vez de tabelas extensas.
* **Objetivos e motivações:**
    * [cite_start]Acompanhar a saúde geral dos cursos e se as funcionalidades estão retendo alunos de fato[cite: 363].
    * [cite_start]Analisar reclamações gerais de desempenho via resumos fáceis de ler[cite: 362].
* **Frustrações / dores:**
    * [cite_start]Ter que decorar caminhos longos ou configurar filtros sempre que for emitir um demonstrativo[cite: 348].
* **Cenários de uso típicos:**
    * [cite_start]Acesso aos demonstrativos de notas e aprovações gerais de um departamento durante uma reunião de colegiado[cite: 356, 362].
    * [cite_start]Verificar casos atípicos de contestações de notas diretamente por encaminhamento[cite: 357].
* **Resumo da persona:** Paulo precisa de praticidade extrema. Seu envolvimento com o sistema será pontual, devendo a interface entregar relatórios sumarizados e conclusões consolidadas sem curvas longas de aprendizado.

#### 3. Com Deficiência Visual
**Cláudia Nogueira**
* **Perfil:** 52 anos, Coordenadora de Apoio ao Aluno, cega. Lida intimamente com alunos e professores que precisam de adaptações.
* [cite_start]**Função no sistema:** Gestor – mediadora, acompanhando de perto o desenvolvimento dos alunos de forma mais humanizada[cite: 354, 362].
* **Nível de conhecimento tecnológico:** Avançado em softwares e periféricos de adaptação.
* **Objetivos e motivações:**
    * [cite_start]Visualizar (via leitura de tela) com facilidade o desempenho e perfil detalhado de um estudante no painel gerencial[cite: 354, 362].
    * [cite_start]Realizar o gerenciamento dos perfis dos usuários em sua interface de suporte[cite: 355].
* **Frustrações / dores:**
    * Ferramentas gerenciais que utilizam apenas dashboards visuais (como gráficos sem alternativas textuais).
    * [cite_start]A impossibilidade de ler relatórios em PDF gerados como imagem pelo sistema[cite: 348].
* **Cenários de uso típicos:**
    * [cite_start]Auditar reclamações e acessar os históricos de notas/frequência para conciliar disputas acadêmicas[cite: 357, 359].
    * Realizar o agendamento de atividades de acolhimento para turmas com métricas abaixo do esperado.
* **Resumo da persona:** Cláudia é uma gestora essencial e necessita que o portal do gestor apresente as estatísticas e as métricas de forma que os softwares ledores consigam tabular as informações, viabilizando suas ações de apoio.

# User:

transforme as personas de deficiência visual em 4 (daltônicos, cegos, baixa visão e sensibilidade a luz), essas englobaram todos os 3 atores, não sendo necessário criar personas diferentes para cada um

# Model:

Aqui estão as 4 personas focadas exclusivamente em diferentes necessidades visuais (cegueira, baixa visão, daltonismo e sensibilidade à luz). Conforme solicitado, elas foram distribuídas de modo a englobar os três atores principais do sistema (Alunos, Professores e Gestores Acadêmicos), substituindo as personas anteriores com deficiência visual.

---

### 1. Cega (Total ausência de visão)
**Ator Representado: Aluno**

**Amanda Costa**
* **Perfil:** 24 anos, estudante de Direito. Nasceu cega e acessa a plataforma via notebook utilizando leitor de tela avançado (como o NVDA) e o celular via VoiceOver. 
* **Função no sistema:** Usuário consumidor – consome materiais, realiza avaliações online e acompanha a vida acadêmica.
* **Nível de conhecimento tecnológico:** Avançado em softwares de acessibilidade. Navega rapidamente utilizando atalhos de teclado.
* **Objetivos e motivações:**
    * Ler PDFs e materiais de estudo diretamente pela plataforma de forma autônoma.
    * Realizar provas e testes online sem depender da ajuda de colegas ou transcritores.
    * Receber notificações de prazos e notas que sejam lidas claramente pelo sistema.
* **Frustrações / dores:**
    * Materiais didáticos postados como "imagens escaneadas" sem reconhecimento óptico de caracteres (OCR) ou texto alternativo (Alt Text).
    * Botões de interface sem rótulos (ex: um ícone de "disquete" para salvar que o leitor de tela lê apenas como "botão não rotulado").
    * Pop-ups de erro visuais que não são anunciados pelo leitor de tela.
* **Cenários de uso típicos:**
    * Fazer download de artigos acadêmicos na véspera da prova.
    * Participar de fóruns de discussão usando a navegação por tabulação (tecla TAB).
* **Resumo da persona:** Amanda não enxerga a interface, ela a "ouve". Depende que o Campus Virtual siga rígidos padrões de código (WCAG/ARIA) para que a navegação faça sentido lógico.

---

### 2. Baixa Visão (Visão Subnormal)
**Ator Representado: Professor**

**Fernando Lima**
* **Perfil:** 46 anos, professor de Literatura. Devido a uma condição degenerativa, possui baixa visão (visão subnormal) e depende de ferramentas nativas de magnificação (zoom da tela ajustado entre 200% e 400%).
* **Função no sistema:** Usuário produtor – elabora provas, corrige materiais dissertativos e lança faltas.
* **Nível de conhecimento tecnológico:** Intermediário. Focado em configurar seu computador para o máximo de conforto visual.
* **Objetivos e motivações:**
    * Criar questionários no sistema com conforto e sem cansar a vista.
    * Ler respostas longas dos alunos e fornecer feedback contínuo.
    * Visualizar a lista de chamada e lançar frequências com agilidade.
* **Frustrações / dores:**
    * Layouts que "quebram" completamente, sobrepõem botões ou escondem menus essenciais quando o zoom do navegador é ativado.
    * Fontes finas ou em tons pastéis de baixo contraste (ex: cinza claro sobre fundo branco) que se tornam invisíveis para ele.
* **Cenários de uso típicos:**
    * Acessar o diário de classe no final do dia para lançar notas e frequências usando uma tela muito ampliada.
* **Resumo da persona:** Fernando precisa de um design altamente responsivo, tipografia legível e contraste elevado, garantindo que o sistema continue funcional mesmo quando fortemente ampliado.

---

### 3. Daltonismo (Deficiência de Visão de Cores)
**Ator Representado: Gestor Acadêmico**

**Ricardo Mendes**
* **Perfil:** 41 anos, Coordenador de Curso. Possui Deuteranopia (dificuldade severa em distinguir tons de verde e vermelho). Usa o sistema diariamente em seu escritório para tomada de decisões.
* **Função no sistema:** Gestor – acompanha os índices de sucesso acadêmico, retenção e desempenho geral das turmas.
* **Nível de conhecimento tecnológico:** Avançado. Trabalha muito com dados, dashboards e relatórios.
* **Objetivos e motivações:**
    * Interpretar rapidamente gráficos de desempenho de dezenas de turmas.
    * Identificar professores com atraso no lançamento de notas ou alunos em risco de evasão.
* **Frustrações / dores:**
    * Dashboards e gráficos gerenciais que utilizam **apenas a cor** para transmitir informações (ex: vermelho para turmas "em risco" e verde para "no prazo"), fazendo com que ele não consiga diferenciar o status.
    * Mensagens de erro ou sucesso baseadas apenas na mudança de cor da fonte.
* **Cenários de uso típicos:**
    * Abrir os painéis estatísticos institucionais na segunda-feira pela manhã para emitir relatórios semanais para a diretoria.
* **Resumo da persona:** Ricardo precisa que a interface não dependa exclusivamente de cores para comunicar estados. Ele precisa de ícones complementares (ex: um "X" para erro, um "Check" para sucesso) e gráficos com texturas ou rótulos de texto claros.

---

### 4. Sensibilidade à Luz (Fotofobia)
**Ator Representado: Aluno (Pós-graduação)**

**Helena Castro**
* **Perfil:** 28 anos, aluna de mestrado em Engenharia. Devido a enxaquecas crônicas e astigmatismo severo, possui alta sensibilidade à luz (fotofobia) e fadiga visual rápida frente às telas.
* **Função no sistema:** Usuário consumidor e pesquisador – passa horas consecutivas lendo e produzindo dentro da plataforma.
* **Nível de conhecimento tecnológico:** Avançado. Utiliza softwares para diminuir a luz azul do monitor, mas depende de interfaces bem projetadas.
* **Objetivos e motivações:**
    * Estudar de forma prolongada, à noite, lendo textos e fóruns diretamente no Campus Virtual.
    * Navegar entre as páginas de forma fluida sem gatilhos para dor de cabeça.
* **Frustrações / dores:**
    * Plataformas com fundos brancos "puros" e brilhantes, sem opção nativa de "Modo Escuro" (Dark Mode).
    * Animações bruscas, transições de tela piscantes ou pop-ups muito luminosos que causam desconforto físico imediato.
* **Cenários de uso típicos:**
    * Leitura contínua de extensa bibliografia e redação de respostas longas no sistema durante a madrugada.
* **Resumo da persona:** Helena necessita urgentemente de um botão de "Modo Escuro" oficial da plataforma, com tons de cinza escuro bem balanceados, e um sistema sem animações exageradas ou clarões repentinos.