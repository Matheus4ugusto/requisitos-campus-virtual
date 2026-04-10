### Requisitos Funcionais (RF)

RF01 – Enviar Atividades: O sistema deve permitir que o aluno envie arquivos de atividades nos formatos PDF, DOCX ou ZIP, com tamanho máximo de 20MB, exibindo uma mensagem de confirmação após o envio.
RF02 – Visualizar Notas e Frequência: O sistema deve exibir ao aluno suas notas e sua frequência, organizadas por disciplina, com a frequência apresentada em percentual.
RF04 – Contestar Notas e Faltas: O sistema deve permitir que o aluno solicite revisão de notas ou faltas, informando uma justificativa obrigatória e vinculando a solicitação à disciplina correspondente.
RF05 – Download para Acesso Offline: O sistema deve permitir que o aluno baixe materiais didáticos, incluindo PDFs e vídeos, para acesso posterior sem conexão com a internet.
RF06 – Sistema de Recomendação: O sistema deve sugerir ao aluno conteúdos complementares de uma disciplina quando ele obtiver nota inferior a 6,0 em avaliações.
RF07 – Comunicação Privada: O sistema deve permitir que o aluno envie mensagens privadas ao professor, vinculadas a uma disciplina, mantendo o histórico das conversas.
RF08 – Interação em Fóruns: O sistema deve permitir que o aluno crie tópicos e responda mensagens em fóruns de discussão organizados por disciplina.
RF09 – Agendamento de Provas: O sistema deve permitir que o aluno agende provas substitutivas selecionando horários disponíveis dentro do período definido.
RF10 – Notificações Automáticas: O sistema deve notificar o aluno sobre prazos, novas atividades, mensagens e notas em até 5 segundos após cada evento.

**RF-01: Cruzar Dados e Emitir Alertas:** O sistema deve permitir o cruzamento de dados de notas e faltas para gerar alertas automáticos e preventivos sobre alunos em risco de reprovação ou evasão.
**RF-02: Personalizar Relatórios:** O sistema deve permitir que o gestor crie, filtre e pesquise dados educacionais de turmas de forma personalizada, sem se limitar a modelos engessados.
**RF-03: Monitorar Lançamento de Notas:** O sistema deve permitir a identificação de docentes que estão com atraso na submissão ou lançamento de notas no sistema.
**RF-04: Acessar Dashboards Resumidos:** O sistema deve permitir o acesso a painéis (dashboards) pré-configurados e sumarizados com as métricas de saúde dos cursos, taxas de retenção e aprovação.
**RF-05: Gerenciar Contestações:** O sistema deve permitir o acompanhamento e encaminhamento direto de reclamações gerais de desempenho e contestações de notas.
**RF-06: Gerenciar Perfis de Usuários:** O sistema deve permitir que a coordenação de apoio realize a gestão completa (visualização e edição) dos perfis dos usuários (docentes e discentes).
**RF-07: Consultar Histórico Acadêmico:** O sistema deve permitir a consulta detalhada do histórico de notas e frequência de um estudante específico para conciliação de disputas ou apoio pedagógico.
**RF-08: Agendar Atividades de Apoio:** O sistema deve permitir o agendamento de atividades de acolhimento e nivelamento voltadas para turmas com métricas de desempenho abaixo do esperado.

---

### Requisitos Não Funcionais (RNF)

RNF01 – Design Intuitivo: O sistema deve possuir interfaces simples e fluxos de navegação que permitam a execução de tarefas críticas, como envio de atividades, em no máximo 3 cliques.
RNF02 – Responsividade: A interface do sistema deve se adaptar automaticamente a diferentes tamanhos de tela, garantindo funcionamento completo em dispositivos desktop e smartphones.
RNF03 – Tempo de Resposta: O sistema deve processar e responder às ações do usuário em até 3 segundos para operações comuns, como carregamento de páginas e envio de comandos.
RNF04 – Sincronização de Notificações: O sistema deve entregar notificações ao usuário em até 5 segundos após a ocorrência de eventos como novas atividades, mensagens ou atualizações de notas.
RNF05 – Estabilidade em Picos de Acesso: O sistema deve manter disponibilidade mínima de 99% durante períodos de alta demanda, como prazos de entrega e aplicação de provas.
RNF06 – Proteção contra Exclusão Acidental: O sistema deve solicitar confirmação do usuário antes da exclusão de dados e permitir a recuperação de itens excluídos por um período mínimo de 7 dias.
**RNF-01:** O sistema deve possuir integração bidirecional com os sistemas legados da universidade para garantir que os dados reflitam a visão global e real da instituição.
**RNF-02:** O sistema deve garantir alta usabilidade e praticidade, permitindo a emissão de demonstrativos consolidados em no máximo 3 cliques a partir da tela inicial, sem necessidade de configuração prévia de filtros complexos.
**RNF-03:** O sistema deve ser totalmente compatível com softwares leitores de tela, garantindo que todas as tabelas e dados gerenciais possuam marcação (HTML/WAI-ARIA) adequada para navegação por teclado e leitura em áudio.
**RNF-04:** O sistema deve fornecer descrições em texto alternativo precisas para todos os gráficos, dashboards e elementos visuais que representem métricas de desempenho.
**RNF-05:** O sistema deve exportar os relatórios em formatos estruturados e lidos por máquinas (como PDFs acessíveis baseados em texto e tags), sendo estritamente proibida a geração de documentos baseados apenas em imagens.
