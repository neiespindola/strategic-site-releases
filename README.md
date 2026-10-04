# Strategic Site Releases

Releases manuais dos plugins Strategic Site e Strategic Site Central.

## Manifestos

- Cliente: `client/update.json`
- Central: `central/update.json`

Os ZIPs são publicados como assets das Releases do GitHub. Não usamos GitHub Actions.

## Processo de publicação

1. Gerar e validar os ZIPs localmente.
2. Atualizar a versão e o changelog no manifesto correspondente.
3. Criar uma Release com a tag da versão.
4. Anexar o ZIP correto à Release.
5. Conferir se o `download_url` do manifesto aponta para a mesma tag e asset.
