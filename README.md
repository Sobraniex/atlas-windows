# Atlas 0.5.0 — Windows x64

## Namestitev
1. Prenesi **Atlas-0.5.0-x64.exe**.
2. Zaženi. Ker namestitveni program ni podpisan, Windows SmartScreen lahko pokaže opozorilo: **More info → Run anyway**.
3. Namestitev je per-user; administratorske pravice niso potrebne.
4. Zaženi Atlas in se prijavi z istim računom kot na Macu.

## Prenosna različica
`Atlas-0.5.0-x64.zip` — razpakiraj in zaženi `Atlas.exe`.

## Kontrolne vsote
V `SHA256SUMS-windows.txt`. Na Windows preveriš z:
`certutil -hashfile Atlas-0.5.0-x64.exe SHA256`

## Posodobitve v aplikaciji
Nastavitve → O aplikaciji → Posodobitve → GitHub repozitorij:
`Sobraniex/atlas-windows`.

Ker je repo zaseben, za preverjanje posodobitev v aplikaciji dodaj fine-grained token z dovoljenjem **Contents: Read-only**.
