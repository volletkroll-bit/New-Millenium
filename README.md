# New Millennium | Arquivo Público de Personagens

Este repositório **público** fornece ao tema de NPCs de **Scion 2e: New Millennium, Temporada 1 (2004)** os registros liberados aos jogadores.

## Estrutura

- `public/catalog.json`: catálogo público gerado pelo módulo administrativo (será criado na primeira publicação).
- `public/photos/`: retratos públicos publicados pelo módulo (será criado automaticamente).

**Não publique aqui:** backups do narrador, NPCs ocultos, versões internas de fichas, códigos de acesso, tokens, segredos de campanha ou material de temporadas futuras.

### Fluxo esperado
1. O narrador edita um NPC no módulo privado do Brave.
2. Clica em **Salvar alterações**, com publicação automática ativada.
3. O módulo envia **somente** registros Públicos e teasers sanitizados por HTTPS ao GitHub.
4. O tema conectado do Tumblr lê `public/catalog.json` sem precisar substituir seu HTML a cada edição.

**Atenção:** registros públicos podem ficar no histórico do GitHub mesmo após serem retirados da lista atual. Nunca publique um segredo e depois tente escondê-lo simplesmente mudando o status do NPC.

### Endereço público de leitura
`https://raw.githubusercontent.com/volletkroll-bit/New-Millenium/main/public/catalog.json`

O endereço ficará disponível depois da primeira publicação feita pelo módulo.

O módulo administrativo e suas credenciais **não devem ser instalados neste repositório**.