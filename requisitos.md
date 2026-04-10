### Requisitos Funcionais (RF)

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

**RNF-01:** O sistema deve possuir integração bidirecional com os sistemas legados da universidade para garantir que os dados reflitam a visão global e real da instituição.
**RNF-02:** O sistema deve garantir alta usabilidade e praticidade, permitindo a emissão de demonstrativos consolidados em no máximo 3 cliques a partir da tela inicial, sem necessidade de configuração prévia de filtros complexos.
**RNF-03:** O sistema deve ser totalmente compatível com softwares leitores de tela, garantindo que todas as tabelas e dados gerenciais possuam marcação (HTML/WAI-ARIA) adequada para navegação por teclado e leitura em áudio.
**RNF-04:** O sistema deve fornecer descrições em texto alternativo precisas para todos os gráficos, dashboards e elementos visuais que representem métricas de desempenho.
**RNF-05:** O sistema deve exportar os relatórios em formatos estruturados e lidos por máquinas (como PDFs acessíveis baseados em texto e tags), sendo estritamente proibida a geração de documentos baseados apenas em imagens.