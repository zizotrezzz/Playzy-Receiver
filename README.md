# Playzy TV Receiver

Offentlige, statiske visningsfiler for Playzy Google Cast.

Mobiltelefonen kjører spillserveren og har autoritativ spilltilstand. Denne
receiveren viser bare den offentlige TV-visningen via Google Cast-kanalen.
Ingen spillserver, spillerøkter, private data eller runtime-konfigurasjon er
publisert i dette repoet. Google CAF lastes fra Google når receiveren starter.

Receiver-ID: `50D38022`.

Når GitHub Pages er aktivert, brukes denne URL-en i Cast Developer Console:
`https://zizotrezzz.github.io/Playzy-Receiver/cast-receiver.html`

## Aktivere gratis GitHub Pages

I Settings → Pages velges **Deploy from a branch**, grenen **gh-pages** og
**/(root)**. Trykk Save. Dette offentlige repoet støtter GitHub Pages på gratisabonnementet.

## Byggkilde

Filene er bygget fra Playzy commit `45871d3dbd79085ed3d4a28214051db30c60581d`
med `npm run build:cast --workspace @waypoint/tv` og relativ asset-base.
Bare `apps/tv/dist-cast/` kopieres ved oppdatering, sammen med denne veiledningen
og Inter-fontens lisens. Native APK og Node-server skal ikke legges her.

Casting på fysisk TV er fortsatt en egen akseptansetest; publisering av
filene alene dokumenterer ikke at casting eller bakgrunnshosting fungerer.
