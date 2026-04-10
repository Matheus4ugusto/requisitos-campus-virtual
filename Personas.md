## Personas de gestores

#### 1. Familiarizado com Tecnologia
**Juliana Mendes**
* **Perfil:** 41 anos, Coordenadora de Curso. Perfil analítico e muito conectada a tendências e métricas educacionais.
* **Função no sistema:** Gestor – acompanha os índices de sucesso acadêmico e as rotinas dos docentes.
* **Nível de conhecimento tecnológico:** Avançado. Sabe extrair, filtrar e relacionar dados educacionais.
* **Objetivos e motivações:**
    * Usufruir da visualização do desempenho do estudante como suporte a suas decisões operacionais.
    * Acompanhar o nível geral de retenção de alunos decorrente do uso da plataforma.
    * Cruzar dados de faltas e notas para aplicar alertas preventivos de evasão.
* **Frustrações / dores:**
    * Relatórios padronizados e engessados que limitam sua capacidade de pesquisa e filtro de turmas.
    * Falta de integrações com o sistema legado limitando a visão real da universidade.
* **Cenários de uso típicos:**
    * Abrir os painéis do gestor acadêmico na segunda-feira pela manhã para avaliar as turmas com muitos alunos com risco de reprovação.
    * Verificar quais docentes estão com o lançamento de notas atrasado.
* **Resumo da persona:** Juliana tem uma atuação baseada em evidências. Ela precisa de dados macro e acesso transparente aos desempenhos globais (docentes e discentes) para tomar ações corretivas a tempo.

#### 2. Não Familiarizado com Tecnologia
**Paulo Ribeiro**
* **Perfil:** 63 anos, Diretor da unidade. Excelente estrategista, mas gerencia suas atividades principalmente por reuniões e documentos impressos pela secretaria.
* **Função no sistema:** Gestor – supervisão executiva e suporte institucional.
* **Nível de conhecimento tecnológico:** Básico. Prefere dashboards (painéis) extremamente resumidos em vez de tabelas extensas.
* **Objetivos e motivações:**
    * Acompanhar a saúde geral dos cursos e se as funcionalidades estão retendo alunos de fato.
    * Analisar reclamações gerais de desempenho via resumos fáceis de ler.
* **Frustrações / dores:**
    * Ter que decorar caminhos longos ou configurar filtros sempre que for emitir um demonstrativo.
    * * Acesso aos demonstrativos de notas e aprovações gerais de um departamento durante uma reunião de colegiado.
    * Verificar casos atípicos de contestações de notas diretamente por encaminhamento.
* **Resumo da persona:** Paulo precisa de praticidade extrema. Seu envolvimento com o sistema será pontual, devendo a interface entregar relatórios sumarizados e conclusões consolidadas sem curvas longas de aprendizado.

#### 3. Com Deficiência Visual
**Cláudia Nogueira**
* **Perfil:** 52 anos, Coordenadora de Apoio ao Aluno, cega. Lida intimamente com alunos e professores que precisam de adaptações.
* **Função no sistema:** Gestor - mediadora, acompanhando de perto o desenvolvimento dos alunos de forma mais humanizada.
* **Nível de conhecimento tecnológico:** Avançado em softwares e periféricos de adaptação.
* **Objetivos e motivações:**
    * Visualizar (via leitura de tela) com facilidade o desempenho e perfil detalhado de um estudante no painel gerencial.
    * Realizar o gerenciamento dos perfis dos usuários em sua interface de suporte.
* **Frustrações / dores:**
    * Ferramentas gerenciais que utilizam apenas dashboards visuais (como gráficos sem alternativas textuais).
    * A impossibilidade de ler relatórios em PDF gerados como imagem pelo sistema.
* **Cenários de uso típicos:**
    * Auditar reclamações e acessar os históricos de notas/frequência para conciliar disputas acadêmicas.
    * Realizar o agendamento de atividades de acolhimento para turmas com métricas abaixo do esperado.
* **Resumo da persona:** Cláudia é uma gestora essencial e necessita que o portal do gestor apresente as estatísticas e as métricas de forma que os softwares ledores consigam tabular as informações, viabilizando suas ações de apoio.

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