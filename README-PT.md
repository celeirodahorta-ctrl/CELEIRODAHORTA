# Celeiro da Horta — Como Cultivar (Android)

Este projeto transforma a versão web funcional em uma APK Android instalável.

## Como obter a APK sem Android Studio

1. Crie um repositório novo no GitHub.
2. Envie **todos os ficheiros e pastas deste projeto** para o repositório.
3. Abra o separador **Actions**.
4. Escolha **Construir APK**.
5. Prima **Run workflow** (ou faça um commit, que inicia automaticamente).
6. Quando terminar, abra a execução e, em **Artifacts**, descarregue `Celeiro-da-Horta-Como-Cultivar-APK`.
7. Dentro do ZIP está `app-debug.apk`. Transfira-o para o telemóvel e instale-o.

A APK é assinada em modo debug, pelo que pode ser instalada para utilização/teste. Para publicar na Google Play será necessário um processo de assinatura de release.

A aplicação contém localmente os dados da v7:
- 553 produtos da horta
- 439 flores
- logótipo e ícone
- fotografias referenciadas pelo catálogo
- links para a loja
