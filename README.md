<div align="center">
  <img src="https://github.com/Ordinateur-Hack/wordtex-dhbw/wiki/images/WordTeX-Logo.svg"><br><br>
</div>

Vielleicht hast du schon von [WordTeX](https://www.andrew.cmu.edu/user/twildenh/wordtex/) gehört, einem Satzsystem, das unter anderem ein Word-Template beinhaltet, welches LaTeX nachahmt. Dieses Projekt basiert auf WordTex und passt das Word-Template für den Studiengang Informatik (AI) an der DHBW in Karlsruhe an, entsprechend [deren Leitlinien](https://www.karlsruhe.dhbw.de/fileadmin/user_upload/documents/content-de/Studiengaenge-Technik/Sicherheitswesen/Leitlinien_Bearbeitung_und_Dokumentation.pdf). Du erhältst hiermit eine **Word-Vorlage für die Projektarbeiten bzw. deine Bachelorarbeit**. Du zweifelst noch? Schau dir [hier](https://github.com/Ordinateur-Hack/wordtex-dhbw/blob/main/WordTeX-Reference.pdf) das PDF an, das mit der Vorlage generiert wurde.

| :point_up:    | **Wie du diese Vorlage installieren und effizient nutzen kannst, erfährst du im [Wiki](https://github.com/Ordinateur-Hack/wordtex-dhbw/wiki).** Bei Fehlern darfst du gerne ein GitHub-Issue aufmachen. |
|---------------|:------------------------|

|:warning: | Bitte beachte, dass diese Vorlage erst im Januar 2021 entstand und zurzeit noch in der Testphase ist (bei meiner eigenen Praxisarbeit). Feedback gerne erwünscht. |
|----------|:-------------------------------|

## Was ist WordTeX?
Vom Original-Autor Tom Wildenhain aus seinem [sehr lesenwerten und humorvollen Paper](https://www.andrew.cmu.edu/user/twildenh/wordtex/WordTeXPaper.pdf):

> WordTeX is a typesetting system that supports the basic functionality of
LaTeX while utilizing the editing convenience of Word. Word’s Turingcomplete macros ensure that WordTEX is just as powerful as LaTeX (for
questionable definitions of “powerful”). The WordTeX plugin allows for
easy conversion between WordTEX and LaTeX. Experimental results
suggest that WordTeX and LaTeX documents are indistinguishable. In light
of these results, I encourage all scientists, students, and professors to
abandon LaTeX immediately and use LaTeX for future work.

## Motivation
Meine erste Projektarbeit an der DHBW habe ich mit LaTeX geschrieben. Vom Ergebnis war ich sehr überrascht, LaTeX ist einfach unübertroffen, was das Layout an sich und die Schriftgestaltung inklusive der Abstände beim Blocksatz angeht. Insgesamt sehen mit LaTeX erstellte Arbeiten sehr professionell aus, vor allem da sie durchweg einheitlich gestaltet sind.

Nur sind die Kosten dafür auch sehr hoch. Wenn ich an einer Arbeit schreibe, möchte ich mich auf den Inhalt fokussieren. Stattdessen musste ich ständig auf diversen StackExchange-Portalen nach kryptischen Commands für die einfachsten Dinge suchen und mich mit nichtssagenden Compiler-Fehlermeldungen rumschlagen. Eigene Anpassungen vorzunehmen ist teils extrem schwierig und man muss sich in die Dokumentationen von verschiedenen Packages einlesen und die entsprechenden Commands herausfinden. Ich bin zwar Entwickler und verwende auch die Konsole, aber beim Schreiben einer wissenschaftlichen Arbeit wünsche ich mir dann doch etwas mehr Komfort und ein WYSIWYG-Tool.

Glücklicherweise habe ich durch [dieses Video](https://youtu.be/jlX_pThh7z8) von Tom Wildenhains Projekt [WordTeX](https://www.andrew.cmu.edu/user/twildenh/wordtex/) erfahren - einem WYSIPCTWOTCG-Tool ("What you see is pretty close to what other tools can get"). Word ist eben auch sehr mächtig und mit der konsequenten Anwendung von Formatvorlagen kann man ebenso eine einheitliche und professionell aussehende Arbeit schreiben. Da ich Word schon seit der 5. Klasse einsetze und damit sehr vertraut bin, fällt mir nun das Erstellen der Arbeiten deutlich leichter.

<table>
  <thead>
    <tr>
      <td align="left">
        :heavy_check_mark: Um nur einige Vorteile zu nennen
      </td>
    </tr>
  </thead>

  <tbody>
    <tr>
      <td>
        <ul>
          <li>Live-Bearbeitung des Dokuments, ohne compilen zu müssen (WYSIWYG)</li>
          <li>Live-Formeleditor, der LaTeX-Syntax unterstützt</li>
          <li>Fortgeschrittene Rechtschreibprüfung für viele Sprachen</li>
          <li>All-in-one Lösung: keine zusätzlichen Packages notwendig</li>
          <li>Kinderleichtes Einfügen von Bildern</li>
          <li>Word vielfach schon vorinstalliert, allseits bekannte Software,<br>
            d.h. deutlich flachere Lernkurve im Vergleich zu LaTeX</li>
          <li>Einfache Integration mit Citavi möglich, ohne umständliche bibtex/biber-Dateien</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

Aber wie alles andere auch hat auch diese Vorlage nicht nur Vorteile. Erstens - und das ist auch schon der größte Nachteil - ist Word nicht kostenlos und zudem closed-source. Zweitens konnte ich mehr als 90%, aber eben doch nicht alle Features aus dem LaTeX-Template genau so in Word umsetzen, sodass es noch ein paar [Limitierungen](https://github.com/Ordinateur-Hack/wordtex-dhbw/wiki/limitierungen) gibt, die allerdings nicht einschneidend sind.

| :star2:   | Dir hat das Projekt geholfen? Dann freue ich mich über einen Stern. |
|---------------|:-------------------------|
