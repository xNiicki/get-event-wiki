---
title: Licht Mischen und Aufbau
description: 
published: true
date: 2025-01-20T09:46:47.222Z
tags: 
editor: markdown
dateCreated: 2024-04-09T06:54:45.794Z
---

# Licht
## Aufbau
Licht besteht aus wellen das sichtbare spektrum ist klein das ganze lichtspektrum ist noch viel größer mit Ultraviolett und Infrarot.

> Unten ist nur das sichtbare lichtspektrum gezeigt.
{.is-warning}

![lichtspektrum.jpeg](/licht/lichtspektrum.jpeg)

> Die Lichtsrahlung ist in diesen artikel stark vereinfacht und deswegen mit Rot, Grün und blau dargestelt. 
{.is-warning}

### Wie wir sehen.
Die Sonne sendet Ultraviolett, Infrarot und sichtbares licht aus die wellen werden von den flächen gespiegelt und fallen ins auge wo die lichtwellen im gehirn zu einem bild umgewandelt werden.

## Licht mischen
### Additive Farbmischung
Wellen werden hinzugefügt und ergeben zusammen eine farbe, die wird z.b. bei Flutern genutzt.
![additive_farbmischung.png](/licht/additive_farbmischung.png)
Rot+Blau=Magenta
Blau+Grün=Cyan
Grün+Rot=Gelb
Rot+Blau+Grün=Weiß
### Subtraktiven Farbmischung
Wellen werden herausgefiltert so das nur die farbwellen der gewünschten farbe übrig bleibt, die wird bei z.b. Halogenscheinwerfern genutzt.
![subtraktive_farbmischung.png](/licht/subtraktive_farbmischung.png)
Weiß-Magenta+Cyan=Blau
Weiß-Cyan+Gelb=Grün
Weiß-Gelb+Magenta=Rot
Weiß-Magenta+Cyan+Gelb=Keine Lichtwellen
Magenta läst nur Rote und Blaue wellen durch.
Cyan läst nur Blaue und Grüne wellen durch.
Gelb läst nur Grüne und Rote wellen durch.
![farbfolien_erklärung_leicht.jpg](/licht/farbfolien_erklärung_leicht.jpg)
Wie im beispiel zu sehen läst magenta nur Rote und Blaue stralung durch und Cyan läst nur Blau und Grün durch dadurch wird rot abgehalten und wir sehen Blau weil blau von beiden durchgelassen wird.
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="" content="width=device-width, initial-scale=1.0">
<title>Farbsubtraktion</title>
<style>
    .color-box {
        width: 300px;
        height: 200px;
        border: 1px solid black;
    }
    .slider {
        width: 100%;
    }
</style>
</head>
<body>

<div class="color-box" id="colorBox"></div>

<label for="redSlider">Red:</label>
<input type="range" min="0" max="255" value="0" class="slider" id="redSlider">

<label for="greenSlider">Green:</label>
<input type="range" min="0" max="255" value="0" class="slider" id="greenSlider">

<label for="blueSlider">Blue:</label>
<input type="range" min="0" max="255" value="0" class="slider" id="blueSlider">

<script>
    const colorBox = document.getElementById('colorBox');
    const cyanSlider = document.getElementById('redSlider');
    const magentaSlider = document.getElementById('greenSlider');
    const yellowSlider = document.getElementById('blueSlider');

    function updateColor() {
        const red = redSlider.value;
        const green = greenSlider.value;
        const blue = blueSlider.value;

        colorBox.style.backgroundColor = `rgb(${red}, ${green}, ${blue})`;
    }

    cyanSlider.addEventListener('input', updateColor);
    magentaSlider.addEventListener('input', updateColor);
    yellowSlider.addEventListener('input', updateColor);

    updateColor();
</script>

</body>
</html>