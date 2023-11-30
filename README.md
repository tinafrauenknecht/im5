# IM5 Webprojekt

## Worum gehts
Als Lehrprojekt meiner Bachelorarbeit werde ich verschiedene Portätvideos produzieren, die Unihockeyspieler*innen der Schweizer Nationalliga A in den Fokus rücken. Die fertigen Videos werden auf der Homeseite veröffentlicht. Beim Klick auf ein Video gelangt man zu einer Detailansicht, wo das Video abgespielt werden kann und noch ein kurzer Text dazu steht. Zusätzlich werden auf der About-Seite Informationen über das Projekt und über das Team bereitgestellt. 

((Mein Bachelorprojekt hat sich leider Mitte November nochmals geändert. Da ich aber bereits mit diesem Thema begonnen habe, meine Webseite zu programmieren und schon ziemlich weit war, habe ich sie nicht nochmals umprogrammiert. Ich hoffe, dies ist in Ordnung so.))

## Techstack
Die Webseite habe ich mit HTML, JavaScript und Tailwind CSS programmiert. Dabei habe ich oft mit ChatGPT gearbeitet. Die Videos sind in einem JSON-File hinterlegt. So kann ich, wenn neue Videos hinzukommen, diese einfach in der Liste ergänzen und muss nicht nochmals viel Code schreiben.


## Challenges
Die Homeseite sollte so gestaltet sein, dass bei einem Mousehover über das Thumbnail das entsprechende Video automatisch abgespielt wird. Aufgrund der grossen Datenmenge konnte ich die Videos leider nicht regulär einbinden, da dies zu langen Ladezeiten führen würde. Daher habe ich sie als YouTube-Videos eingebettet. Dabei ergab sich jedoch das Problem, dass sich das Logo, der Playbutton usw. nicht entfernen liessen. Da dies unschön aussah, habe ich nun auf diesen Hovereffekt verzichtet.

Eine weitere Challenge bestand darin, die YouTube-Videos im responsiven 16:9-Format darzustellen. In Tailwind CSS gibt es speziell eine Klasse dafür (aspect-video). Allerdings wurde diese aus irgendeinem Grund nicht angenommen. Ich habe auch verschiedene andere Tailwind CSS-Klassen ausprobiert, aber nichts hat funktioniert. Daher empfahl mir Nina während des Coachings, dies durch einen Umweg zu lösen, indem ich meine eigene Klasse in meiner output.css-Datei erstellt habe.

## Quellen
- Dokumentationen (Tailwind CSS)
- ChatGPT
- GitHub Copilot 