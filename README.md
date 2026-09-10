# Gestão 360° – Produção para Android

Aplicativo Android que abre o sistema hospedado em:

`https://gestao-producao-2.emergent.host`

## Características

- Nome no celular: Gestão 360° - Produção
- Pacote Android: `com.gestao360.producao`
- Android mínimo: 6.0
- Login e dados permanecem no sistema atual
- Upload de arquivos e downloads habilitados
- Tela amigável quando o celular está sem internet

## Gerar o APK

O fluxo **Gerar APK**, disponível em GitHub Actions, cria o arquivo instalável.
O APK final fica no artefato `Gestao-360-Producao-APK`.

## Observação

Esta é uma versão interna, adequada para instalação direta nos celulares da
operação. Para publicação na Play Store, configure uma chave de assinatura de
produção e gere um Android App Bundle (`.aab`).
