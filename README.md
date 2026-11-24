# Atlas 0.5.1 — Windows x64 + macOS arm64

## Kaj je novega
- Odstranjen stranski panel **Baza znanja** iz pogleda **Atlas asistent** (Windows in macOS).
- Pogled asistenta zdaj uporabi celotno širino.

## Windows x64
1. Prenesi **Atlas-0.5.1-x64.exe**.
2. Zaženi. SmartScreen lahko pokaže opozorilo: **More info → Run anyway**.
3. Namestitev je per-user; administratorske pravice niso potrebne.

## macOS arm64 (Apple Silicon)
1. Odpri **Atlas-0.5.1-arm64.dmg**.
2. Povleci Atlas v Applications.
3. Če Gatekeeper blokira: desni klik → **Open**.

## Prenosni različici
`Atlas-0.5.1-x64.zip` (Windows) in `Atlas-0.5.1-arm64.zip` (macOS).

## Posodobitve v aplikaciji
Nastavitve → O aplikaciji → Posodobitve → GitHub repozitorij:
`Sobraniex/atlas-windows`.

Repo je **javen**, zato žeton ni potreben. Aplikacija 0.5.0 ob kliku **Preveri posodobitve** ponudi 0.5.1.

## Kontrolne vsote
`SHA256SUMS-0.5.1.txt`. Na Windows preveriš z:
`certutil -hashfile Atlas-0.5.1-x64.exe SHA256`
