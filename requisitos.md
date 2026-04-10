### Requisitos Funcionais (RF)

**RF01 – Enviar Atividades:** O sistema deve permitir que o aluno envie arquivos de atividades nos formatos PDF, DOCX ou ZIP, com tamanho máximo de 20MB, exibindo uma mensagem de confirmação após o envio. 
**RF02 – Visualizar Notas e Frequência:** O sistema deve exibir ao aluno suas notas e sua frequência, organizadas por disciplina, com a frequência apresentada em percentual. 
**RF04 – Contestar Notas e Faltas:** O sistema deve permitir que o aluno solicite revisão de notas ou faltas, informando uma justificativa obrigatória e vinculando a solicitação à disciplina correspondente. 
**RF05 – Download para Acesso Offline:** O sistema deve permitir que o aluno baixe materiais didáticos, incluindo PDFs e vídeos, para acesso posterior sem conexão com a internet. 
**RF06 – Sistema de Recomendação:** O sistema deve sugerir ao aluno conteúdos complementares de uma disciplina quando ele obtiver nota inferior a 6,0 em avaliações. 
**RF07 – Comunicação Privada:** O sistema deve permitir que o aluno envie mensagens privadas ao professor, vinculadas a uma disciplina, mantendo o histórico das conversas. 
**RF08 – Interação em Fóruns:** O sistema deve permitir que o aluno crie tópicos e responda mensagens em fóruns de discussão organizados por disciplina. 
**RF09 – Agendamento de Provas:** O sistema deve permitir que o aluno agende provas substitutivas selecionando horários disponíveis dentro do período definido.
**RF10 – Notificações Automáticas:** O sistema deve notificar o aluno sobre prazos, novas atividades, mensagens e notas em até 5 segundos após cada evento.
**RF11 - Habilitar Notificações Sonoras:** O sistema deve permitir que o aluno ative a emissão de alertas sonoros juntamente à notificações de atividades.

**RF12 - Gerenciar Disciplinas:** O sistema deve permitir que o professor crie, modifique e exclua as disciplinas que estão sob sua responsabilidade. 
**RF13 - Criar Atividades e Provas:** O sistema deve permitir que o professor crie, modifique e exclua atividades gerais, além de configurar provas e testes online.
**RF14 - Compartilhar Materiais de Estudo:** O sistema deve permitir que o professor faça upload de arquivos (como PDFs de leitura) e adicione conteúdos na área de videoaulas para consumo dos alunos.
**RF15 - Lançar e Editar Notas:** O sistema deve permitir que o professor lance, edite e salve as notas dos alunos continuamente em suas respectivas atividades e provas.
**RF16 - Registrar Frequência:** O sistema deve fornecer uma interface para que o professor aplique faltas, registre presenças e edite a frequência da turma ao longo do semestre.
**RF17 - Responder Dúvidas e Interagir:** O sistema deve permitir que o professor receba e responda dúvidas dos alunos por meio de mensagens privadas ou participe de tópicos em fóruns públicos.
**RF18 - Gerenciar Prova Substitutiva:** O sistema deve notificar e permitir que o professor avalie e organize o agendamento de provas substitutivas solicitadas pelos alunos.

**RF19 - Cruzar Dados e Emitir Alertas:** O sistema deve permitir o cruzamento de dados de notas e faltas para gerar alertas automáticos e preventivos sobre alunos em risco de reprovação ou evasão.
**RF20 - Personalizar Relatórios:** O sistema deve permitir que o gestor crie, filtre e pesquise dados educacionais de turmas de forma personalizada, sem se limitar a modelos engessados.
**RF21 - Monitorar Lançamento de Notas:** O sistema deve permitir a identificação de docentes que estão com atraso na submissão ou lançamento de notas no sistema.
**RF22 - Acessar Dashboards Resumidos:** O sistema deve permitir o acesso a painéis (dashboards) pré-configurados e sumarizados com as métricas de saúde dos cursos, taxas de retenção e aprovação.
**RF23 - Gerenciar Contestações:** O sistema deve permitir o acompanhamento e encaminhamento direto de reclamações gerais de desempenho e contestações de notas.
**RF24 - Gerenciar Perfis de Usuários:** O sistema deve permitir que a coordenação de apoio realize a gestão completa (visualização e edição) dos perfis dos usuários (docentes e discentes).
**RF25 - Consultar Histórico Acadêmico:** O sistema deve permitir a consulta detalhada do histórico de notas e frequência de um estudante específico para conciliação de disputas ou apoio pedagógico.
**RF26 - Agendar Atividades de Apoio:** O sistema deve permitir o agendamento de atividades de acolhimento e nivelamento voltadas para turmas com métricas de desempenho abaixo do esperado.

**RF27 - Adicionar Texto Alternativo:** O sistema deve permitir que o professor acrescente texto alternativo (para áudio descrição) na publicação de materiais de estudo, atividades e provas.
**RF28 - Editar Tamanho da Fonte:** O sistema deve permitir que o usuário altere o tamanho da fonte (variando do tamanho padrão de 100% até 400%).
**RF29 - Alterar Tema:** O sistema deve permitir que o usuário escolha entre "Tema Claro" e "Tema Escuro".

---

### Requisitos Não Funcionais (RNF)

**RNF01 -** O sistema deve possuir interfaces simples e fluxos de navegação que permitam a execução de tarefas críticas, como envio de atividades, em no máximo 3 cliques.
**RNF02 -** A interface do sistema deve se adaptar automaticamente a diferentes tamanhos de tela, garantindo funcionamento completo em dispositivos desktop e smartphones.
**RNF03 -** O sistema deve processar e responder às ações do usuário em até 3 segundos para operações comuns, como carregamento de páginas e envio de comandos.
**RNF04 -** O sistema deve entregar notificações ao usuário em até 5 segundos após a ocorrência de eventos como novas atividades, mensagens ou atualizações de notas.
**RNF05 -** O sistema deve manter disponibilidade mínima de 99% durante períodos de alta demanda, como prazos de entrega e aplicação de provas.
**RNF06 -** O sistema deve solicitar confirmação do usuário antes da exclusão de dados e permitir a recuperação de itens excluídos por um período mínimo de 7 dias.

**RNF07 -** O sistema deve garantir estabilidade contínua e não apresentar lentidão, mesmo sob um alto fluxo de acessos durante a aplicação de provas online simultâneas.
**RNF08 -** O sistema deve realizar o salvamento automático contínuo dos dados durante o lançamento de notas e frequências, prevenindo a perda de informações do professor em caso de queda de conexão.
**RNF09 -** O fluxo para o registro de frequências diárias deve ser direto e não deve exigir mais do que 3 cliques a partir da página principal da disciplina do professor. 
**RNF10 -** A interface deve possuir um design intuitivo e simplificado, ocultando jargões ou menus excessivos.
**RNF11 -** A interface deve ser plenamente responsiva, permitindo que o professor lance notas ou anexos tanto pelo computador pessoal quanto por dispositivos móveis (tablets e smartphones) sem quebrar o layout.
**RNF12 -** Apenas os professores vinculados oficialmente à disciplina (e gestores autorizados) devem ter permissão de acesso para editar notas, aprovar provas substitutivas e aplicar faltas. 
**RNF13 -** O sistema deve garantir que todas as transações de dados dos professores ocorram por meio de uma integração eficiente e segura exclusivamente com o sistema legado já existente na universidade, sem envolver integrações com plataformas de terceiros não homologadas.

**RNF14 -** O sistema deve possuir integração bidirecional com os sistemas legados da universidade para garantir que os dados reflitam a visão global e real da instituição.
**RNF15 -** O sistema deve garantir alta usabilidade e praticidade, permitindo a emissão de demonstrativos consolidados em no máximo 3 cliques a partir da tela inicial, sem necessidade de configuração prévia de filtros complexos.
**RNF16 -** O sistema deve ser totalmente compatível com softwares leitores de tela, garantindo que todas as tabelas e dados gerenciais possuam marcação (HTML/WAI-ARIA) adequada para navegação por teclado e leitura em áudio.
**RNF17 -** O sistema deve fornecer descrições em texto alternativo precisas para todos os gráficos, dashboards e elementos visuais que representem métricas de desempenho.
**RNF18 -** Os gráficos devem possuir texturas e paletas de cores monocromáticas com enfoque no destaque dos contrastes entre tons (contraste mínimo de 4.5:1) e testados para os diferentes tipos de daltonismo (por meio de sites ou extensões que apresentem a exibição das cores para os tipos de daltonismo e sites que apresentem o contraste).
**RNF19 -** O sistema deve exportar os relatórios em formatos estruturados e lidos por máquinas (como PDFs acessíveis baseados em texto e tags), sendo estritamente proibida a geração de documentos baseados apenas em imagens.

**RNF20 -** O sistema deve emitir um aviso para o professor sugerindo o acréscimo de texto alternativo caso algum anexo seja acrescentado à publicação (de materiais de estudo, atividades ou provas) e permitir que o professor aceite ou recuse a sugestão. 
**RNF21 -** O sistema deve fornecer a audio descrição de textos nativos na plataforma e suporte para texto alternativo.
**RNF22 -** Todos os botões e ícones devem possuir a descrição da funcionalidade e/ou da imagem apresentada (ex: um ícone de "disquete" que o leitor de tela reconheça como "salvar"). 
**RNF23 -** O sistema deve se acessível a pessoas com deficiência seguindo os padrões WCAG (Web Content Accessibility Guidelines) e ARIA (Accessible Rich Internet Applications). 
**RNF24 -** O sistema deve ser responsivo para garantir que o aumento da fonte não obstrua paineis nem sobreponha botões.
**RNF25 -** A interface do sistema deve possuir contraste mínimo de 4.5:1 (seguindo as diretrizes da WCAG) entre as cores de fundos e textos.
**RNF26 -** A interface do sistema deve apresentar símbolos e descrições da função de cada botão de ação (salvar, enviar, cancelar, apagar), não dependendo apenas de cores (ex: o botão "cancelar" deve possuir cor vermelha e ser acompanhado de um ícone de "x" e o texto descritivo da função "cancelar").
**RNF27 -** Os alertas de erro devem possuir layout específico com destaque de ícones de alerta e texto "Erro" destacado.
**RNF28 -** O sistema deve possuir um tema escuro que atenda os mesmos padrões de contraste aplicados ao modo claro.
**RNF29 -** O tema claro do sistema não deve ter fundo #ffff.
**RNF30 -** O sistema não deve integrar animações bruscas, pop-ups luminosos ou transições com trocas de cores repentinas (telas "piscantes").
