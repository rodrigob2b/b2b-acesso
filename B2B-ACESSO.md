# B2B Acesso

App de suporte remoto da **B2B Consultiva** (Guaxupé/MG), baseado no [RustDesk](https://github.com/rustdesk/rustdesk) (AGPL-3.0).
Este repositório é um fork público, como a licença exige. Branch de trabalho: `b2b`.

O que muda em relação ao RustDesk:
- Nome do app `B2BAcesso`, ícones e logos da B2B Consultiva (`flutter/assets/logo*.png`, `icon.png`, `res/*`).
- Servidor de ID/relay, chave pública e painel/API da B2B embutidos e travados (`src/common.rs` → `apply_b2b_acesso_brand`).
- Atualização automática da RustDesk desligada (atualizações vêm deste repositório).
- Build: `.github/workflows/b2b-acesso.yml` (Windows x64, instalador `B2BAcesso-*.exe` nas Releases).

"RustDesk" é marca de seus donos; este app não é afiliado nem endossado pela RustDesk / Purslane Ltd.
