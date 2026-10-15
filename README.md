# Plataforma Web de Gestão de Eventos

Projeto do **AWS Student Builder Group (AWS SBG) — SENAI CIMATEC**, com desenvolvimento conduzido pelo Time de Projetos e Ações.

## Sobre o projeto

A plataforma tem como objetivo simplificar o controle de presença em eventos, reduzir tarefas manuais e facilitar a emissão de certificados de participação.

A proposta é importar a lista de inscritos em formato CSV, validar se cada participante está inscrito e registrar sua presença durante o evento. Após o evento, o sistema deverá permitir a geração de certificados individuais ou em lote.

Como funcionalidade complementar, está prevista uma linha do tempo cronológica para consultar eventos anteriores, em andamento e futuros.

## Funcionalidades previstas

- Importação da lista de inscritos por arquivo CSV.
- Validação dos participantes antes do check-in.
- Registro de presença por evento.
- Geração de certificados individuais e em lote.
- Cadastro e consulta de eventos.
- Linha do tempo de eventos passados, em andamento e futuros *(funcionalidade complementar)*.

## Escopo inicial

O desenvolvimento prioriza uma solução simples, funcional e de entrega rápida, inicialmente voltada ao uso interno do AWS SBG.

### Fora do escopo inicial

- Integração direta com o Meetup.
- Sistema completo de gestão de eventos.
- Gestão financeira ou de inscrições.
- Integrações externas não essenciais à primeira versão.
- Funcionalidades complexas que não sejam necessárias para o fluxo principal.

## Fluxo previsto de utilização

1. Cadastrar ou selecionar o evento.
2. Importar a lista de inscritos em CSV.
3. Validar os dados importados.
4. Localizar o participante e registrar o check-in.
5. Gerar os certificados individuais ou em lote.
6. Consultar e organizar os registros do evento.

## Planejamento do desenvolvimento

O planejamento está organizado nas seguintes etapas:

1. **Levantamento:** definir funcionalidades, fluxo de uso e dados necessários.
2. **Estruturação:** definir a estrutura do sistema, o banco de dados e as tecnologias.
3. **Desenvolvimento:** implementar as funcionalidades priorizadas.
4. **Integração:** conectar a importação dos inscritos, o check-in e a geração de certificados.
5. **Testes:** validar os fluxos e corrigir problemas.
6. **Implementação:** utilizar o sistema em um evento real.
7. **Ajustes finais:** corrigir problemas identificados durante a utilização.
8. **Entrega:** documentar e disponibilizar o sistema.

As tecnologias e a arquitetura serão definidas durante a etapa de estruturação.

## Testes e mitigação de riscos

Para antecipar problemas antes de utilizar o sistema em um evento real, poderão ser usadas listas CSV de eventos anteriores.

Principais pontos de atenção:

- **Falha na importação do CSV:** testar arquivos anteriores e validar diferentes cenários.
- **Participante não encontrado:** testar participantes presentes e ausentes na lista.
- **Falha durante o evento:** realizar testes prévios e manter uma alternativa manual de registro.
- **Dados incorretos no certificado:** validar os dados antes da geração.
- **Indisponibilidade de internet:** manter um procedimento alternativo para registrar presenças.
- **Aumento do escopo:** priorizar as funcionalidades definidas para a entrega inicial.

## Organização e acompanhamento

- Código-fonte versionado neste repositório do AWS SBG.
- Demandas acompanhadas pelo GitHub Projects.
- Time de Projetos e Ações responsável pela execução e desenvolvimento.
- Liderança responsável pelo acompanhamento e orientação.
- Administração e Eventos consultada e envolvida principalmente na aplicação do sistema em eventos.

## Status

**Planejamento definido; desenvolvimento e decisões técnicas serão conduzidos conforme o cronograma do projeto.**

---

**AWS Student Builder Group — SENAI CIMATEC**  
**Time de Projetos e Ações**
