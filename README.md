# Hackathon FMU & Bovinu'S (2026.2) — Unidade Augusta

Repositório com as propostas teóricas e documentação de apoio desenvolvidas para os desafios apresentados pela **Bovinu'S Grill & Beer – Unidade Augusta** durante o Hackathon FMU (2026.2), com foco no serviço de almoço por peso e na jornada do cliente (*se servir e ser atendido*).

## Por que este repositório contém PDFs e não código?

Logo após a análise do desafio com a equipe, concluímos que os problemas apresentados envolvem dimensões muito variadas da operação — e a maior parte delas depende não apenas de software isolado, mas também de **hardware, infraestrutura física, layout do salão e rotinas operacionais**.

Diante desse cenário, avaliamos que seria mais útil para a empresa convidada receber **propostas teóricas bem estruturadas em diferentes caminhos possíveis**, trazendo uma visão técnica do que seria necessário para viabilizar cada alternativa, do que apresentar um código desconectado da realidade física da unidade. Em vez de "forçar" um protótipo de software onde o gargalo real passa por sensores, balanças, câmeras, *pagers*, sinalização ou organização do espaço, priorizamos clareza arquitetural, análise de viabilidade e aderência ao escopo.

## Contexto e Escopo

* **Unidade avaliada:** Bovinu'S Grill & Beer – Augusta (São Paulo/SP).
* **Recorte principal:** Serviço de almoço self-service por peso e jornada do cliente (*se servir e ser atendido*), distribuída entre buffet/churrasqueira/balança e os salões (Principal, Superior e Inferior).
* **Diretrizes respeitadas:** Manutenção do sistema por peso e do fluxo atual de caixas/saída, respeito às fronteiras de cozinha/compras/estoque e foco em soluções realistas e aplicáveis.

## Estrutura da Documentação (Arquivos PDF)

> Nota: O GitHub suporta nativamente a visualização e o download de arquivos `.pdf`, o que garante que a formatação, tabelas e diagramas textuais permaneçam fiéis ao material produzido pela equipe.

* **`Visao_Geral_Propostas_Hackathon.pdf`** — Documento consolidador com o panorama geral das soluções, sinergias entre as frentes, premissas de escopo e roteiro sugerido de implantação em fases.
* **`Proposta_01_Taxa_Saida_Buffet.pdf`** — Abordagens para o **mix do prato servido** e **giro/reposição das cubas**, comparando registro leve na passagem/cozinha com pesagem individual por cuba no buffet.
* **`Proposta_02_Limpeza_Mesas.pdf`** — Alternativas para reduzir o tempo em que as mesas ficam sujas nos salões (**botão na mesa + pagers**, análise crítica de *checkout* na mesa fora do escopo e **câmeras** nas abordagens com visão computacional ou monitoramento).
* **`Proposta_03_Filas_Fluxo.pdf`** — Otimização de **filas e tempos de espera**, integrando o atendimento em mesa via *pagers*, duplicação sinalizada de itens de maior saída e avaliação de rotas/layout.
* **`Proposta_04_Qualidade_Sobras.pdf`** — Abordagem prática para **qualidade e sobras no prato**, combinando observação na devolução, sinais na pista, diferenciação entre padrão individual (saciedade/exagero) e coletivo (possível falha de qualidade) e integração com o canal de feedback existente.

## Como Navegar pelo Repositório

1. Comece pela **`Visao_Geral_Propostas_Hackathon.pdf`** para ter o mapa completo de como as ideias se conectam.
2. Consulte os PDFs numerados (`Proposta_01` a `Proposta_04`) para ver os detalhes de cada dor, comparações de prós/contras e a documentação técnica de apoio.

## Equipe e Evento

* **Evento:** Hackathon FMU — Edição 2026.2
* **Empresa parceira:** Grupo Bovinu'S — Bovinu'S Grill & Beer (Unidade Augusta)
* **Integrantes da equipe:** Roberdan Andrade & Gabriel Victor
