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

Filene er bygget fra Playzy commit `f81a6ed85c49f2aac4ea01507a3c7e21f60bd7ef`
med `npm run build:cast --workspace @waypoint/tv` og relativ asset-base.
Bare `apps/tv/dist-cast/` kopieres ved oppdatering, sammen med denne veiledningen
og Inter-fontens lisens. Native APK og Node-server skal ikke legges her.

Casting på fysisk TV er fortsatt en egen akseptansetest; publisering av
filene alene dokumenterer ikke at casting eller bakgrunnshosting fungerer.

Oppdatert 21. oktober 2026: Det felles kortet for neste spill reserverer plass
for overskrift og tekst, mens illustrasjonen kan krympe. Alle fem spill,
ingen valgt spill, begge språk og seks skjermstørrelser er kontrollert i
nettleser (72 kombinasjoner). Cast-transport, ekte CAF-oppstart og redusert
bevegelse er kontrollert på desktop; dette er ikke fysisk Cast-akseptanse.
Tidligere hashede assets beholdes for økter som har cachet eldre HTML.
