# Strategic Site Releases

Releases manuais do plugin cliente Strategic Site. O Strategic Site Central é distribuído separadamente em um repositório privado.

## Manifesto

- Cliente: `client/update.json`

Os ZIPs do cliente são publicados como assets das Releases do GitHub. Não usamos GitHub Actions.

## Processo de publicação

1. Gerar e validar o ZIP do cliente localmente.
2. Atualizar a versão e o changelog em `client/update.json`.
3. Criar uma Release com a tag da versão.
4. Anexar o ZIP correto à Release.
5. Conferir se o `download_url` do manifesto aponta para a mesma tag e asset.
