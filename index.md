---
layout: default
title: Nostalgie-Ecke von Stagyrit
---

<header>
    <h1>Nostalgie-Ecke von Stagirit</h1>
</header>
<details open>
    <summary>
        <h2>Über den Kanal</h2>
    </summary>
    <p>
        Hallo, herzlich willkommen auf meiner Internetseite!
        Hier finden Sie eine altmodische oder sogar uralte Computerspiele. Mein Kanal
        ist nicht schlecht, denn es hat einen Daseinszweck. Der Daseinszweck ist zu
        C64-Spiele aufgefrischt, denn die Computerspiele sollen frisch sein. Ich
        konzentriere aus Textadventures, aber die Möglichkeiten des C64-Computers
        sind unvergleichlich größer.
    </p>
    <p> 
        Schauen Sie sich meinen
        <a class="u-url url" href="https://www.youtube.com/@eltikia" title="Nostalgie-Ecke von Stagirit - YouTube">YouTube-Kanal</a>
        an, um mehr über der Kanal zu erfahren. Hier können Sie auch diese C64-Computerspiele schauen.
        Zum Beispiel „Das Tollhaus“ können unter hier geöffnet sein. Wenn Sie das Plakat im Tollhaus finden,
        senden Sie es portofrei an den Louvre. Danke für Ihre Aufmerksamkeit, meine Damen und Herren.
    </p>
</details>
{% include computerspiel.html title="Zak McKracken and the Alien Mindbenders" description="Zachary hatte keine Ahnung, dass die Telefonrechnung fällig waren. Wie wird er bezahlen? Vergiss nicht zu der Erde retten, Zachary." path="S3ETogTxtnY" si="7LI_exPirRzw_VqD" discussion="2" %}
{% include computerspiel.html title="Maniac Mansion" description="Lese eine Plakette. „Si trouve, envoyez-le au Louvre, poste paye.“ Das bedeute, wenn Sie es finden, senden Sie es portofrei an den Louvre." path="UlD1jRwcvhA" si="lMAvdN6se4aBJ_K4" quote="Si trouve, envoyez-le au Louvre, poste paye. – ein Plakat in Tollhaus" discussion="4" %}
{% include computerspiel.html title="The Mask of the Sun" description="Das Geheimnis der Aztekenmaske. Was ist schön dabei?" path="6ZJ_S4K6R10" si="xMna5OA0pw4DHuG5" discussion="5" %}
{% include computerspiel.html title="Das Drachental" description="Wenn „trowrebuaz“ gesagt wird, ein Schwert ist frei. Das ist ganz normal in dieses Computerspiel. „Trowrebuaz“ ist ein Zauberwort." path="pahNjOWqNxQ" si="JrnXZZppS7GleynV" discussion="6" %}
{% include computerspiel.html title="Sunny Shine - on the Funny Side of Life" description="Sunny ist allergisch gegen Alkohol, aber Cigaretten schmeckt ihm gut. Dieses Computerspiel kann nicht gut enden, denn er wirfte ein Poster weg. Er hat auch weniger Geld als die Konkurenz." path="Eg-WGXEohoc" si="AHZ9MtbCu4PSC98V" discussion="8" %}
{% include computerspiel.html title="Dirty" description="Er kann nicht die Gespenster töten, sonder tanzen mit sie. Aber diese Gespenster kann ihn töten. Auseinander, das Gespenst ist schon Tod." path="j5jfYtsFwjE" si="WWXXP4rYT2Jt-ALk" %}
<details open>
    <summary>
        <h2>Kontakt</h2>
    </summary>
    <a href="images/bigger-avatar.png"><img alt="" class="u-photo" src="images/avatar.png"></a>
    <ul>
        <li class="p-name fn">
            <span class="p-given-name">Maciej Matiaszowski</span>
        </li>
{% include url.html header="Email" url="mailto:maciej.matiaszowski@gmail.com?subject=Nostalgie-Ecke%20von%20Stagirit" title="Email me" name="maciej.matiaszowski@gmail.com" %}
{% include url.html header="Gitter" url="https://matrix.to/#/#kassette:gitter.im" title="Gitter &#124; Kassette" name="#kassette" %}
{% include url.html header="Homepage" url="https://Stagyrite.GitHub.io/" title="Maciej Matiaszowski &#124; Stagyrite" name="Stagyrite.GitHub.io" %}
{% include url.html header="GitHub" url="https://github.com/Stagyrite/" title="Stagyrite (Maciej Matiaszowski)" name="GitHub/Stagyrite" %}
    </ul>
</details>

<details>
    <summary>
        <h3>Speaking Streem</h3>
    </summary>
    <h4>./<a class="u-url url" href="https://stagyrite.github.io/streemdox/" title="Streem documentation project &#124; Streemdox" rel="me">streem</a> <a class="u-url url" href="https://github.com/eltikia/eltikia.github.io/blob/main/candy-game.strm" title="eltikia.github.io/candy-game.strm at main · eltikia/eltikia.github.io" rel="me">candy-game.strm</a></h4>
    <pre>
# Input:
# 634
# 63
# 364
# 630

candyGame = { reminder ->

	if (reminder == 0) {
		"B wins"
	} else if (reminder == 2) {
		"A wins"
	} else if (reminder == 3) {
		"A wins"
	} else {
		"draw"
	}

}

stdin | map { n ->
    reminder = number(n) % 5
    candyGame(reminder)
} | stdout

# Output:
# draw
# A wins
# draw
# B wins
</pre>

</details>
<footer>⬛⬜🚢⏳</footer>




