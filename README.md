# PortalControl â Zaawansowany system kontroli Netheru, Endu i komunikatĂłw (Darmowy)

PortalControl to darmowy skrypt dla serwerĂłw Minecraft Spigot/Paper, napisany w jÄzyku Skript.
UmoĹźliwia kontrolowanie portali do Netheru i Endu, blokowanie ich, odblokowywanie oraz automatyczne wyĹwietlanie komunikatĂłw.
Posiada teĹź system wyĹÄczenia wiadomoĹci twĂłrcĂłw za pomocÄ specjalnej komendy.

## Funkcje skryptu

### 1. Kontrola Netheru
- /nether on â wĹÄcza Nether
- /nether off â wyĹÄcza Nether
- Blokowanie teleportacji do Netheru, jeĹli jest wyĹÄczony
- Broadcast informujÄcy graczy o zmianach

### 2. Kontrola Endu
- /end on â wĹÄcza dostÄp do Endu
- /end off â blokuje portale do Endu
- Komunikat dla gracza przy prĂłbie wejĹcia, gdy End jest wyĹÄczony

### 3. Automatyczna wiadomoĹÄ twĂłrcĂłw
Co 5 minut na czacie pojawia siÄ informacja:
"Skrypt na portale zostaĹ wykonany przez skyfox!"
MoĹźna jÄ trwale wyĹÄczyÄ.

### 4. Ukrywanie wiadomoĹci komendÄ /dulerekpl2025
Komenda:
- Ustawia {portal.msg.hidden} na true
- WyĹÄcza wysyĹanie automatycznego komunikatu
- WyĹwietla potwierdzenie:
  - "WiadomoĹÄ zostaĹa wyĹÄczona na staĹe!"
  - "#Skript byĹ tworzony przez dulerekpl. W przyszĹoĹci bÄdzie paczka!"

## Zmienne uĹźywane w skrypcie

- {nether.wlaczony} â czy Nether jest aktywny
- {end.enabled} â czy End jest dostÄpny
- {portal.msg.hidden} â czy komunikat twĂłrcĂłw ma byÄ ukryty

## Zdarzenia i mechanika dziaĹania

- on teleport â blokowanie wejĹcia do Netheru
- on portal â blokowanie portali do Endu
- every 5 minutes â automatyczna wiadomoĹÄ
- Komendy zarzÄdzajÄce stanami ĹwiatĂłw

## Uprawnienia

- /nether â portal.dulerekpl
- /end â endcontrol.toggle
- /dulerekpl2025 â brak (komenda dostÄpna dla wszystkich)

## Instalacja

1. Pobierz plik .sk
2. Wgraj do folderu:
   plugins/Skript/scripts/
3. Wpisz:
   /sk reload portalcontrol

## Licencja

Projekt jest darmowy. MoĹźna go modyfikowaÄ, udostÄpniaÄ i uĹźywaÄ na kaĹźdym serwerze.
Prosimy jedynie o pozostawienie informacji o autorach.

## Autorzy

- skyfox â system portali
- dulerekpl â rozwĂłj paczki i publiczne wydanie

WkrĂłtce pojawiÄ siÄ nowe funkcje.
