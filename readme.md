
Questo plugin permette di sfogliare e riprodurre i contenuti dal sito Mediaset Play.

E' la prima volta che mi ritrovo a programmare in Python quindi sarà sicuramente pieno di porcherie, ma almeno funziona, sentitevi liberi di migliorarlo come meglio credete.

Grazie a [phate89](https://github.com/phate89/) per il vecchio Addon dal quale ho preso spunto e qualche riga di codice.

Grazie a Mediaset per le API e i contenuti.

# Installazione
Se necessario abilitate il plugin Inputstream Adactive prime di eseguire l'installazione [ulteriori informazioni qui](https://seo-michael.co.uk/how-to-enable-rtmp-input-inputstream-adaptive-kodi/).

Per installare l'addon [scaricate il file ZIP](https://github.com/kodi-bino/plugin.video.mediasetplay/archive/1.2.1.zip) e installatelo normalmente, gli altri requisiti dovrebbero essere soddisfatti automaticamente.

Testato su Kodi 17.6 (Windows 10), Kodi 18 RC2 (Windows 10), LibreElec 8.90 (Raspberry PI 2), Kodi 17.6 (Android), Kodi 18 RC3 (Android).

# Live Estero

#EXTINF:0,CANALE 5
#KODIPROP:inputstreamaddon=inputstream.adaptive
#KODIPROP:inputstream.adaptive.manifest_type=mpd
https://live2-mediaset-it.akamaized.net/Content/dash_d0_clr_vos/live/channel(c5)/manifest.mpd
#EXTINF:0,CANALE 5
https://live2-mediaset-it.akamaized.net/Content/hls_h0_clr_vos/live/channel(c5)/index.m3u8
#EXTINF:0,CANALE 5
https://live3-mediaset-it.akamaized.net/Content/hls_h0_clr_vos/live/channel(c5)/index.m3u8


# Donazioni
Se volete offrirmi una birra o darmi una mano con lo sviluppo potete donare Bitcoin all'indirizzo: 

1EPvpSztxmU71DXy4LVoxFbK7FisfPpTzV

Ogni aiuto è molto gradito! Grazie mille!
