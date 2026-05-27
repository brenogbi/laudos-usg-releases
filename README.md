# laudos-usg-releases

Repositório **público** de **releases e auto-update** do LaudUSG (Sistema de Laudos de Ultrassom).

O **código-fonte é privado** (repositório `brenogbi/laudos-usg`). Aqui ficam apenas:
- os **instaladores** assinados (Windows `.msi`/`.exe`, macOS Apple Silicon `.dmg`);
- o `latest.json` consumido pelo auto-update do app;
- o workflow que builda a partir do código privado.

## Baixar o app
Veja a aba **Releases** e baixe o instalador do seu sistema.

## Como sai uma versão nova
O build é disparado manualmente em **Actions → Release LaudUSG → Run workflow**, informando a tag do repositório privado (ex: `v0.2.1`).
