# Área do cliente Converge — conceito navegável

Protótipo independente para apresentação, com dados e nomes fictícios. Não usa banco, autenticação ou APIs do HUB. Nenhum arquivo ou mensagem é enviado a serviços externos.

## Abrir

Abra `index.html` no navegador, ou execute nesta pasta:

```sh
python3 -m http.server 4330 --bind 127.0.0.1
```

Acesse http://127.0.0.1:4330. Para compartilhar na rede local, use o IP atual da máquina como endereço de bind.

## Roteiro sugerido

1. Visão geral: resultados, movimentações, pendências e agenda.
2. Conteúdos: abrir uma peça, aprovar ou solicitar ajuste com comentário.
3. Estratégia: consultar prioridades e validar o briefing.
4. Resultados: explorar indicadores, campanhas e exportar CSV ilustrativo.
5. Arquivos e recursos: buscar materiais e abrir uma prévia.
6. Agenda e equipe: consultar compromissos e pessoas responsáveis.

As ações de aprovação e validação são simulações em memória. Recarregar a página reinicia os estados. Downloads CSV/TXT/ICS contêm dados fictícios, identificados como demonstração. Os arquivos originais enviados pelo usuário não são armazenados.

A pasta `telas/` contém capturas preparadas para slides. Identidade: Mont nos títulos, Geist no corpo, símbolo `}` e paleta monocromática com cores semânticas discretas.
