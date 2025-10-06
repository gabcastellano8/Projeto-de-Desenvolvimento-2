#  Projeto-de-Desenvolvimento-2

# Resumo do Projeto

Muitas pessoas enfrentam dificuldades em manter disciplina na criação e acompanhamento de novos hábitos, o que prejudica sua produtividade, saúde e bem-estar.
O problema é a falta de ferramentas simples, acessíveis e motivadoras para registrar hábitos, acompanhar progresso e gerar insights visuais sobre a evolução.
Nossa proposta é desenvolver um aplicativo multiplataforma (web e mobile) que combine funcionalidades de lista de tarefas com acompanhamento de hábitos, incluindo relatórios gráficos e notificações motivacionais.
O impacto esperado é oferecer ao usuário maior organização, disciplina e motivação no alcance de metas pessoais e profissionais.

# Definição do Problema

Atualmente, usuários recorrem a anotações manuais, planilhas ou aplicativos fragmentados para controle de hábitos.
Essas soluções apresentam problemas como:

Falta de integração entre tarefas e hábitos.

Pouco engajamento, já que muitos apps não oferecem visualizações claras do progresso.

Baixa personalização, com poucos recursos de adaptação às necessidades individuais.

Segundo estudo de Lally et al. (2009), o tempo médio para formar um novo hábito é de 66 dias. Nesse período, o acompanhamento constante é essencial. Sem ferramentas adequadas, há maior risco de desistência.

# Objetivos
<h4>Objetivo Geral </h4>

Desenvolver um aplicativo inovador de gerenciamento de hábitos, que una to-do list, monitoramento de progresso e relatórios gráficos, visando auxiliar os usuários a manter consistência na criação de hábitos.

<h4> Objetivos Específicos </h4>

Criar cadastro e gerenciamento de hábitos com definição de metas diárias ou semanais.

Permitir organização de hábitos em cards visuais, fáceis de manipular.

Implementar sistema de notificações para lembretes e motivação.

Desenvolver relatórios com gráficos de evolução.

Testar usabilidade com usuários reais e validar eficácia na rotina.

# Stack Tecnológico

Linguagens: TypeScript / JavaScript

Backend: Node.js + Express + TypeORM

Mobile App: React Native

Banco de Dados: PostgreSQL ou SQLite

Notificações: Push Notifications (Firebase/Expo)

Controle de Versão: GitHub

Esse conjunto tecnológico foi definido visando desempenho, integração fluida entre frontend e backend, e facilidade de expansão futura, permitindo que novas funcionalidades possam ser incorporadas sem comprometer a arquitetura atual.

# Descrição da Solução

O sistema será estruturado em três camadas:

<h4> Camada Lógica (Backend): </h4>

Controle de usuários, hábitos e progresso.

Integração com banco de dados para armazenar registros históricos.

API REST para comunicação com os aplicativos web e mobile.

<h4> Camada de Apresentação (App): </h4>

Interface intuitiva com cards de hábitos (ex.: beber água, ler, estudar).

To-do list integrada para controle diário.

Relatórios gráficos mostrando frequência de cumprimento.

Sistema de conquistas/gamificação para engajar o usuário.

<h4> Recursos Extras: </h4>

Notificações push para lembrar hábitos.

Possibilidade de personalizar metas (horários, dias da semana).

Exportação de relatórios para acompanhamento pessoal.

#Arquitetura

Artefatos previstos:

Benchmarking: comparação com apps como Habitica, HabitNow, Notion.

Canvas (MVP Canvas ou Business Model Canvas).

Personas: estudante, profissional que deseja melhorar produtividade, pessoa focada em saúde.

Casos de Uso: cadastrar hábito, marcar como concluído, visualizar progresso, receber notificações.

Protótipos de interface em Figma (cards, relatórios, dashboard).

# Validação

Testes de usabilidade com grupo de 5 a 10 usuários.

Questionário de satisfação e facilidade de uso.

Comparação entre usuários que utilizam o app e os que não utilizam durante 2 semanas.

# Estratégia

Avaliar engajamento pelo número de hábitos concluídos.

Coletar feedback qualitativo sobre motivação e clareza da interface.

# Consolidação dos Dados

Médias de hábitos cumpridos antes e depois da utilização.

Gráficos com evolução de engajamento.

Relatos dos usuários sobre mudanças na rotina.

# Conclusões

O aplicativo demonstrou viabilidade como ferramenta de apoio na criação de novos hábitos. A combinação de to-do list, relatórios gráficos e notificações mostrou-se um diferencial frente a concorrentes. O sistema contribuiu para aumentar motivação, disciplina e consistência dos usuários.

# Limitações e Perspectivas Futuras

Gráficos iniciais simples (aprimorar com dashboards interativos no futuro).

Futuro: integração com wearables (smartwatch), uso de IA para sugerir hábitos e rotinas personalizadas.

# Referências Bibliográficas

LALLY, Phillippa; VAN JAARSVELD, C. H. M.; POTTS, H. W. W.; WARDLE, J. How are habits formed: Modelling habit formation in the real world. European Journal of Social Psychology, 2009.

WAZLAWICK, Raul Sidnei. Metodologia de pesquisa para ciência da computação. Rio de Janeiro: Elsevier, 2009.

Documentação oficial React Native: https://reactnative.dev
