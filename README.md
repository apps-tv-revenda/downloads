# Downloads

Arquivos prontos dos aplicativos (APK) para instalar pelo Downloader e para a
atualização automática dos apps.

| App | Link fixo do APK |
|---|---|
| Play WM | https://github.com/apps-tv-revenda/downloads/releases/download/play-wm/play-wm.apk |

## Trava de licença

Cada app confere o arquivo `licencas/<app>.json` ao abrir e de hora em hora:

- `"ativa": true` → funciona normal
- `"ativa": false` → o app mostra a tela de bloqueio com o texto de `"mensagem"`
- `"aviso"` → texto que aparece ao abrir o app (ex.: "Sua mensalidade vence dia 10"). Deixe `""` para não mostrar nada.

Para mudar: abra o arquivo aqui no GitHub, clique no lápis (Editar), troque e clique em **Commit changes**.
Leva até uns 5 minutos para valer.
