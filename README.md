# Simulador de Atendimento Bling - Chat

Simulador interativo criado para treinamento de atendimento via chat, inspirado no ambiente do Octa Conversas utilizado no suporte do Bling.

## Objetivo

O projeto foi desenvolvido para ajudar novos colaboradores a praticarem o fluxo de atendimento em um cenário controlado, escolhendo respostas e recebendo um feedback ao final da simulação.

## Cenário atual

O cliente informa que não consegue exportar produtos para sua loja virtual da Shopee porque o botão **Exportar produtos multiloja** está inativo.

O fluxo simula:

- saudação e abordagem inicial;
- investigação da dúvida do cliente;
- fornecimento da solução;
- oferta de ajuda adicional;
- encerramento do atendimento;
- feedback final com pontuação.

## Critérios de avaliação

Cada critério vale **20 pontos**, totalizando **100 pontos**:

- Saudação
- Formalidade
- Fornecimento da solução correta
- Oferta de ajuda adicional
- Deixar à disposição

Quando um critério não é atendido, o simulador apresenta a pontuação zerada naquele item e, quando aplicável, uma explicação sobre o erro cometido.

## Recursos

- interface inspirada no Octa Conversas;
- tutorial guiado pela tela;
- balões de ajuda contextual;
- mensagens com atrasos para simular uma conversa real;
- indicador de digitação do cliente;
- horário dinâmico nas mensagens e no preview da conversa;
- reinício da simulação;
- feedback final visual com nota de 0 a 100.

## Execução

O projeto é executado diretamente no navegador. O arquivo `index.html` é o ponto de entrada do simulador.

Com o GitHub Pages habilitado, o acesso pode ser feito por:

`https://isaacmarquetti.github.io/simulador_chat_bling/`

## Estrutura

- `index.html` - carregador principal do simulador;
- `assets/html/` - partes da versão atual do simulador utilizadas pelo carregador.

## Versão

**1.0**

Desenvolvido por **Isaac Marquetti**.
