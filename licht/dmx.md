---
title: DMX
description: 
published: true
date: 2023-10-27T20:04:11.161Z
tags: 
editor: markdown
dateCreated: 2023-07-29T19:22:52.023Z
---

# DMX
Alles über das DMX Protokoll.
## DMX-Kabel
DMX ist ein Protokoll das in der Eventtechnik, Lichttechnik verwendet wird um Lampen anzusteuern.
Dieses steht für *D*igital *M*ultiple*x*.

Um ein DMX-Kabel von einem XLR-Kabel zu unterscheiden muss man erstmal die Unterschiede verstehen. Vom Aufbau her unterscheiden sich die Kabel nicht (durch unsere günstigere und ältere Lichttechnik die wir verwenden wird hier vom 3-Poligen Kabel ausgegangen).
Dabei gibt es 3 Leitungen:
- Negative Phase
- Positive Phase
- Erdung/Abschirmung

![xlr-dmx-kabel_aufbau.png](/bilder/xlr-dmx-kabel_aufbau.png)
Der einzige Unterschied der zwischen einem DMX-Kabel und einem XLR-Kabel herscht ist der Wiederstand der 3 Leitungen. Sollte man diese Kabel-Arten vermischen kann es passieren, dass das Mikrofon oder die jeweilige Lichtechnik nicht Funktioniert. Um das zu vermeiden und ggf. Fehlersuche zu ermöglichen, kann man am Kabel anhand der Beschriftung den gegebenen Wiederstand ablesen.
![beschriftung_dmx_kabel.png](/bilder/beschriftung_dmx_kabel.png)
(Orange: Kabelart; Rot: Wiederstand)

## DMX-Universum
Ein **DMX-Universum** besteht aus **512 Channels**. Die Anzahl der Channels in einem DMX-Universum muss 512 betragen, da sonst der DMX-Standard nicht eingehalten wird. Dabei ist die Anzahl an DMX-Universen **theoretisch** nicht begrenzt, sondern nur von der Leistung des jeweiligen Rechners.

