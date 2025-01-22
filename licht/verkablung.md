---
title: Verkablung von Lichttechnik
description: 
published: true
date: 2025-01-22T12:24:18.969Z
tags: 
editor: markdown
dateCreated: 2023-10-30T07:45:53.730Z
---

## DMX-Kabel
DMX ist ein Protokoll das in der Eventtechnik, Lichttechnik verwendet wird um Lampen anzusteuern.
Dieses steht für **D**igital **M**ultiple**x**.

Um ein DMX-Kabel von einem XLR-Kabel zu unterscheiden muss man erstmal die Unterschiede verstehen. Vom Aufbau her unterscheiden sich die Kabel nicht (durch unsere günstigere und ältere Lichttechnik die wir verwenden wird hier vom 3-Poligen Kabel ausgegangen).
Dabei gibt es 3 Leitungen:
- Negative Phase
- Positive Phase
- Erdung/Abschirmung
![xlr-dmx-kabel_aufbau.png](/bilder/xlr-dmx-kabel_aufbau.png)
Der einzige Unterschied der zwischen einem DMX-Kabel und einem XLR-Kabel ist der Wiederstand der 3 Leitungen.
Die kabel können vermischt werden kann dann aber passieren, dass das Mikrofon oder die jeweilige Lichtechnik nicht gewollt Funktioniert. Um das zu vermeiden und ggf. Fehlersuche zu ermöglichen, kann man am Kabel anhand der Beschriftung den gegebenen Wiederstand ablesen.
![beschriftung_dmx_kabel.png](/bilder/beschriftung_dmx_kabel.png)
(Orange: Kabelart; Rot: Wiederstand)
## DMX-Universum
Ein **DMX-Universum** besteht aus **512 Channels**. Die Anzahl der Channels in einem DMX-Universum muss 512 betragen, da sonst der DMX-Standard nicht eingehalten wird. Dabei ist die Anzahl an DMX-Universen **theoretisch** nicht begrenzt, sondern nur durch die Leistung des jeweiligen Rechners.
## Verkabelung
Um das Licht zu steuern wird ein Lichtpult oder Daslight genutzt, wenn das Lichtpult genutzt wird, wird das DMX-Kabel direkt ins pult gesteckt.
Bei der nutzung von Daslight wird das DMX-Kabel erst durch ein DMX Interface geführt.
![dmx_interface.png](/dmx_interface.png)
Es kann auch beides genutzt werden, dabei geht ein kabel vom analogen pult ins DMX-Interface.
Vom DMX Interface in den DMX-Splitter und von da aus in die Lampen.
Bei einer Lampe gibt es einen Eingang(DMX IN) und einen Ausgang(DMX OUT), dadurch können mehrere Lampen hintereinander geschaltet werden.
Am Ende von einer Reihe Lampen ist es empfehlenswert einen DMX-Terminator einzubauen.
Der DMX-Terminator sorgt dafür das Störeffekte verhindert werden.