# Cloud Service Play

Aplicativo do **Cloud Service** para jogar na nuvem, em [gaming.cscloudservice.com](https://gaming.cscloudservice.com).

- **Windows:** instale pela [Microsoft Store](https://apps.microsoft.com/detail/9N1HF1ZNBK7X).
- **Linux (x86_64):** baixe na [última release](../../releases/latest) o `Cloud_Service_Play-x86_64.AppImage` e o `instalar-cloud-service-play.sh`.

## Instalar no Linux

```bash
chmod +x instalar-cloud-service-play.sh
./instalar-cloud-service-play.sh        # copia o app para ~/.local/bin e registra csplay://
```

Depois, no portal, inicie um jogo e clique em **Jogar no app**. Sem o script, o AppImage abre normalmente
(`chmod +x` e duplo clique), mas o botão do portal não encontra o app.

Conferir o download: `sha256sum -c SHA256SUMS`.
Desinstalar: `rm ~/.local/share/applications/csplay.desktop ~/.local/bin/Cloud_Service_Play.AppImage`.

## Privacidade

[Política de Privacidade do app](https://cscloudservice.com/play-privacidade.html). Sem telemetria, anúncios nem rastreadores.

## Licença e código-fonte

Baseado no projeto de código aberto [Moonlight](https://github.com/moonlight-stream/moonlight-qt), licença **GPL-3.0**.
O código-fonte correspondente é fornecido a quem recebe o aplicativo: peça em contact@cscloudservice.com.

---

**English:** Cloud Service Play is the desktop client for Cloud Service cloud gaming. Windows: Microsoft Store (link above).
Linux: download the AppImage and the install script from the latest release. Based on Moonlight (GPL-3.0); source on request at contact@cscloudservice.com.
