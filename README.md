# IFSIGARD - Mural da Turma

Aplicativo Android (Kotlin + Jetpack Compose + Room) para comunicar ausências de docentes nos Institutos Federais.
Projeto final de Programação de Dispositivos Móveis (SLTPRIS 2026-2), desenvolvido com o processo SpinOff (Scrum).

**Recorte:** foco na comunicação da ausência docente. Professor, CAE e Coordenação publicam avisos (aula cancelada, troca de aula ou outro aviso) informando turma, data e horário; todos veem o mural geral do dia e filtram por turma, data e horário. Login com e-mail institucional: @aluno.if.edu.br é aluno, @if.edu.br é servidor (perfil do cadastro). São 3 casos de uso (Autenticar, Consultar mural, Manter aviso) e 3 telas (Login, Mural, Novo aviso).

## Estrutura (modelo SpinOff)

| Pasta | Conteúdo |
|---|---|
| `1.Requisitos/` | Visão, Necessidades do Cliente, Histórias de Usuário (HU01 a HU04), Casos de Uso, Protótipo |
| `2.Analise e Design/` | Modelo de Análise e Design, Modelo de Arquitetura (Sprint 2) |
| `3.Implementacao/` | Projeto do Android Studio, relatórios de código e .apk (Sprints 2 e 3) |
| `4.Teste/` | Roteiro de Testes e resultados (Sprints 2 e 3) |
| `5.Implantação/` | Guia de Implantação e Manual do Usuário (Sprint 3) |
| `6.Gerenciamento de Projeto/` | TAP, Planilha de Planejamento e Controle (Backlog do Produto, Backlog do Sprint 2, entregas, riscos), Atas |

## Documentos do Sprint 1 (11/11 a 18/11/2026)

Cada documento está em `.docx` (modelo SpinOff) e em `.pdf` (para ler direto no GitHub).

| Entrega | Arquivo |
|---|---|
| Termo de Abertura do Projeto | [TAP (PDF)](6.Gerenciamento%20de%20Projeto/TAP%20-%20Termo%20de%20Abertura%20do%20Projeto%20-%20IFSIGARD.pdf) |
| Visão | [Visão (PDF)](1.Requisitos/Visao%20-%20IFSIGARD.pdf) |
| Necessidades do Cliente | [Necessidades (PDF)](1.Requisitos/Necessidades%20do%20Cliente%20-%20IFSIGARD.pdf) (sem entrevista: suposições S01 a S11) |
| Ata de Reunião | [Ata 01 (PDF)](6.Gerenciamento%20de%20Projeto/Atas/Ata%2001%20-%20Planejamento%20do%20Projeto%20-%2011-11-2026.pdf) |
| Histórias de Usuário | [HU01](1.Requisitos/Historias%20de%20Usuario/HU01%20-%20Entrar%20com%20e-mail%20institucional.pdf) · [HU02](1.Requisitos/Historias%20de%20Usuario/HU02%20-%20Consultar%20o%20mural%20de%20avisos.pdf) · [HU03](1.Requisitos/Historias%20de%20Usuario/HU03%20-%20Publicar%20aviso.pdf) · [HU04](1.Requisitos/Historias%20de%20Usuario/HU04%20-%20Editar%20e%20excluir%20aviso.pdf) |
| Modelo de Caso de Uso | [Descrições (PDF)](1.Requisitos/Casos%20de%20Uso/Modelo%20de%20Caso%20de%20Uso%20-%20IFSIGARD.pdf) · [Diagrama (PNG)](1.Requisitos/Casos%20de%20Uso/Diagrama%20de%20Casos%20de%20Uso%20-%20IFSIGARD.png) · [Astah (.asta)](1.Requisitos/Casos%20de%20Uso/IFSIGARD%20-%20Casos%20de%20Uso.asta) |
| Protótipo (rascunho) | [Protótipo (PDF)](1.Requisitos/Prototipo/Prototipo%20-%20IFSIGARD.pdf) · [telas](1.Requisitos/Prototipo/telas) |
| Backlog do Produto e Backlog do Sprint 2 | [Planilha PCP (.xlsx)](6.Gerenciamento%20de%20Projeto/Planejamento%20e%20Controle%20do%20Projeto%20-%20IFSIGARD.xlsx) (abas `Backlog_Produto` e `Backlog_Sprint_2`) |

### Diagrama de casos de uso

![Casos de uso](1.Requisitos/Casos%20de%20Uso/Diagrama%20de%20Casos%20de%20Uso%20-%20IFSIGARD.png)

### Telas (rascunho)

| T1 Login | T2 Mural | T3 Novo aviso |
|---|---|---|
| <img src="1.Requisitos/Prototipo/telas/T1%20-%20Login.png" width="220"> | <img src="1.Requisitos/Prototipo/telas/T2%20-%20Mural.png" width="220"> | <img src="1.Requisitos/Prototipo/telas/T3%20-%20Novo%20aviso.png" width="220"> |

## Equipe

| Papel | Nome |
|---|---|
| Product Owner | [Nome do professor] |
| Scrum Master | [Integrante 1] |
| Desenvolvedores | [Integrante 1], [Integrante 2], [Integrante 3], [Integrante 4] |
