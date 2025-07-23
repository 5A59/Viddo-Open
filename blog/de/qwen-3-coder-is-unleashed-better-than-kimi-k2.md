# QWEN 3 CODER ist entfesselt... besser als KIMI K2

Ich habe kürzlich ein Video angesehen und fand es sehr aufschlussreich. Um den Inhalt besser zu verstehen und zu teilen, habe ich **[Viddo](https://viddo.pro/)** genutzt, um das Video in einen strukturierten Artikel umzuwandeln, der als Referenz für diese Analyse diente.

**Original Video:** [Video ansehen](> - Alibaba hat den Quin 3 Coder vorgestellt, ein leistungsstarkes neues Open-Source-Coding-Modell.
> - Es verfügt über ein massives Modell mit 480 Milliarden Parametern, das als Powerful1 bezeichnet wird.
> - Der Quin 3 Coder glänzt in verschiedenen Benchmarks und übertrifft die Konkurrenz.
> - Ein Kommandozeilenwerkzeug für generatives Codieren, Quin Code, ist jetzt verfügbar.
> - Neue Methoden im Reinforcement Learning verbessern die Leistung bei realen Codierungsaufgaben.

Alibaba hat soeben das nächste große Ding veröffentlicht: **Quin 3 Coder**. Während die Welt sich an **Kimi K2**, das andere große Open-Source-Coding-Modell, gewöhnt, bringt Alibaba den **Quin 3 Coder** heraus, der in mehreren Größen verfügbar ist.

Aber das große Modell, der **Powerful1**, ist Quin 3 Coder 480B A35B instruct, was bedeutet, dass dies ein **Modell mit 480 Milliarden Parametern** ist. Es ist mit einer Mischung von Experten aufgebaut, wobei während eines Aufrufs nur **35 Milliarden Parameter aktiv sind**. Instruct bedeutet, dass es sich um unseren freundlichen und hilfsbereiten Assistentenmodus handelt, im Gegensatz zum Basismodell, das ein wenig mehr wie ein Textvervollständigungsmodell ist.

Nataly unterstützt **256k Kontext** und skaliert bis zu **1 Million**. Und wie Sie hier sehen können, sehen die Benchmarks jetzt großartig aus. Man kann nicht immer nur den Benchmarks vertrauen, also geben Sie ihm ein paar Tage, während jeder damit experimentiert und es testet.

Aber **Kimi K2** war allem Anschein nach extrem beeindruckend. Der **Gwin 3 Coder** schlägt Kimi K2 mühelos. Darüber hinaus ist es vergleichbar. Es ist wettbewerbsfähig mit **Claud Sounded**. Es schlägt auch **OpenAI's GPT 4.1** und erzielt sehr gute Werte bei der **generationenbasierten Browsernutzung** sowie bei der Nutzung von generativen Werkzeugen. Wiederum hat nur Cloud Sounded 4 in einigen Fällen die Nase vorn.

Das **Gwin-Team** verspricht, dass es nahtlos mit den besten Entwicklerwerkzeugen der Community funktioniert und überall in der digitalen Welt genutzt werden kann. Generatives Codieren in der Welt, und sie meinen das nicht im Spaß.

Neben dem Modell geben sie ein Kommandozeilenwerkzeug für generatives Codieren namens **Quin Code** als Open Source heraus. Es ist abgeleitet von **Google's Gemini Code**. Wie Sie hier sehen können, ist es als Open Source unter **GitHub Apache 2.0 Lizenz** veröffentlicht. Es sieht viel aus wie der Klauencode und wurde mit angepassten Eingabeaufforderungen und Funktionsaufrufprotokollen angepasst, um die Fähigkeiten des Quin 3 Coders bei generativen Codierungsaufgaben vollständig zu entfesseln.

Im Grunde ist **Quin Code** einfach ein angepasstes **Gemini CLI**. Es wurde modifiziert, um die Quwin-Modelle zu verwenden. Sie können auch die **Quin 3 Coder-Modelle** mit **Cloud Code** verwenden. Viele Leute bevorzugen Cloud Code, daher können Sie die Quin 3 Coder-Modelle problemlos mit Cloud Code verwenden. Sie können es auch mit **K Clin** verwenden. Ich lasse diese Links weiter unten.

Eines der großen Diskussionsthemen derzeit ist das **Reinforcement Learning**. Diese Modelle in ein RL-Gymnasium zu bringen, um ihnen beizubringen, verschiedene Fähigkeiten wie Codierung, Mathematik usw. zu erlernen. Wie ich hier sage, ist das Skalieren von Code-RL schwer zu lösen, leicht zu überprüfen, wie Sie hier sehen können.

Während sie die Trainingsschritte erhöhen, während sie dieses Modell trainieren, steigen die Werte in allen Bereichen der Leistung, wie Codierungsgenerierung, Softwareentwicklung, wettbewerbsfähigem Codieren, **SQL-Anweisungsbefolgung** usw. Sie nehmen einen kleinen Angriff auf das andere Frontier-Labor und sagen, dass im Gegensatz zu dem vorherrschenden Fokus auf Wettbewerbsniveau-Code-Generierung in der Community, wir glauben, dass alle Codierungsaufgaben naturgemäß gut für die ausgabengetriebene großangelegte RL-Reinforcement-Learning geeignet sind.

Deshalb haben wir das Code-RL-Training auf einem breiteren Spektrum realer Codierungsaufgaben skaliert. Im Grunde genommen sagen sie, dass sie dieses Modell auf echte Arbeit in der realen Welt trainieren, anstatt zu versuchen, diese Quizze und Tests, diese wettbewerbsorientierten Fragen zu maximieren.

Durch das automatische Skalieren und Testen von vielfältigen Codierungsaufgaben haben wir hochwertige Trainingsinstanzen geschaffen und das volle Potenzial von Reinforcement Learning erfolgreich freigesetzt. Dies hat nicht nur die Erfolgsquoten bei der Codeausführung erheblich gesteigert, sondern auch Gewinne für andere Aufgaben gebracht.

Das bedeutet, dass dieser Ansatz verallgemeinert. Wir haben in anderen veröffentlichten Arbeiten gesehen, dass das Training, um Code zu erstellen, beispielsweise die Fähigkeit verbessert, Mathematikprobleme zu lösen, auch wenn es nicht ausdrücklich darauf trainiert wurde. Es scheint eindeutig, dass ihr Ansatz über viele verschiedene Aufgaben verallgemeinert. Hoffentlich werden sie später ein Papier veröffentlichen, das darstellt, wie sie dies angehen.

Aber hier erwähnen sie, dass ihr Ansatz schwierig zu lösende, leicht zu überprüfende Aufgaben als fruchtbaren Boden für großangelegtes Reinforcement Learning nutzt.

Hier ist ein Diagramm seiner Leistung auf dem **SUI Bench Verified**. Dies ist die Größe des Modells. Modelle rechts sind größer, Modelle links sind kleiner, und je höher man geht, desto besser ist die Punktzahl auf dem Subench Verified. SWbench ist eine Sammlung von **500 realen, menschlich verifizierten Python-GitHub-Problemen**, die von Menschen überprüft und als lösbar bestätigt wurden.

Wie Sie hier sehen können, liegt der **Quin 3 Coder** über den meisten anderen Modellen, die wir gesehen haben, einschließlich **Kimmy K2**, **GPT 4.1**, sogar **Gemini 2.5 Pro Preview**. Nur **Cloud Sont 4** hat sie leicht übertroffen, obwohl es ein viel größeres Modell ist. Für ein moderat großes Modell ist nichts in Bezug auf Leistung auch nur annähernd vergleichbar. **Kimmik K2** ist viel größer, während es nicht so gut ist.

Wichtig ist, dass der **Quin 3 Coder** bei **realen Software-Engineering-Aufgaben**, wie denen im **SUI Bench Verified**, an Multi-Turn-Interaktionen mit der Umgebung teilnehmen muss, die Planung, die Nutzung von Werkzeugen, das Empfangen von Feedback und die Entscheidungsfindung umfassen. Dies ist also kein einfaches Frage-Antwort-Format. Dies ist eine langfristige Aufgabe, die Planung und Feedback umfasst.

Was war ihr Trick, um dieses Modell so gut bei diesen langfristigen Aufgaben zu machen? Sie erwähnen hier, dass sie in der Nachtrainingsphase von **Quin 3 Coder** das **Long Horizon RL** eingeführt haben. Sie bezeichnen es als **Agent RL**. Dies sollte das Modell dazu ermutigen, diese realen Aufgaben durch Multi-Turn-Interaktionen mithilfe von Werkzeugen zu lösen.

Das ist interessant. Die zentrale Herausforderung bei etwas wie diesem **Agent RL** liegt in der Skalierung der Umgebung. Um dies anzugehen, haben sie ein **skalierbares System** entwickelt, das in der Lage ist, **20.000 unabhängige Umgebungen parallel auszuführen**. Das haben sie mithilfe der **Alibaba Cloud-Infrastruktur** durchgeführt.

Dies ermöglichte die notwendige Skalierung, um diese massive Reinforcement-Learning-Pipeline zu betreiben. Und das ist es, was **Coin 3 Coder** ermöglicht hat, **state of the art performance** unter Open-Source-Modellen zu erreichen, ohne—und das ist wichtig zu beachten—ohne Testzeit-Skalierung. Dies ist kein Denkmodell. Im Gegensatz zu **DeepSeq R1** oder **Gemini 2.5 Pro Preview** ist dies ein Nicht-Denkmodell.

Einige der Demonstrationen, die sie veröffentlicht haben, umfassen den Abriss und die Demonstration von Gebäuden. Hier verwenden sie **Quinn mit Klein**, um eine interaktive Farbexplosion zusammenzustellen. Sieht ziemlich beeindruckend aus.

Wir müssen einige dieser Dinge testen: **3D Google Earth Geländeveranschaulichung**, eine kleine App, um Ihre Tippgeschwindigkeit zu testen, einen hüpfenden Ball in Rotation, einen Hyperwürfel, eine super trippige Sonnensimulation und ein Duettspiel. Es ist verfügbar unter **how you face and chat Quen AI**.

Ich werde eine umfassende Testreihe für dieses Ding machen, aber für den Moment sind hier nur ein paar schnelle Tests, die ich durchgeführt habe. Einer besteht darin, eine Simulation eines Bürogebäudes mit Schreibtischen und Büros im Inneren zu erstellen. Ich habe versucht, es dazu zu bringen, eine Art von **transparenten Fenstern** an der Außenseite zu erstellen, aber es konnte die Transparenz nicht erreichen. Sie waren entweder sehr undurchsichtig oder völlig nicht transparent.

Aber es gelang ihm, die Räume im Inneren mit Schreibtischen und Computern zu erstellen. Ein Licht sieht in jedem Raum aus wie ein Licht. Bis jetzt ist es für den ersten Versuch nicht schlecht. Ich meine, das ist ziemlich gut für den ersten Versuch.

Ich habe auch ein kleines **Drohnenflugspiel** erstellt, bei dem Sie mit einer Drohne durch die Stadt fliegen können. Ich kann mich nicht beschweren. Es ist ziemlich gut. Ich meine, die Tasten sind ein wenig seltsam, aber ich mag es bisher. Es dauert ein wenig, sich daran zu gewöhnen, aber sobald Sie in der Lage sind, einfach das Gas zu dosieren, können Sie herumfliegen, und es ist nicht schlecht für einen ersten Versuch.

Wir haben einen **Minecraft-Klon**. Wo wären wir ohne einen Minecraft-Klon? Sie können Blöcke platzieren und bauen und sich bewegen. Nicht zu schlecht, ich konnte das ziemlich leicht in einem Versuch machen.

Also schauen Sie es sich an, lassen Sie mich wissen, was Sie davon halten. Weitere Tests und Anwendungsfälle kommen sehr, sehr bald. Außerdem hat jemand diesen kleinen Hack für **Claud Code** gemacht, und warum hatten wir das nicht schon immer?

Durch die Aufgabenliste. Erstellung der **To-Do-Liste**. Sir. Beginnendes Anpassen von Python-Code. Mach es so, Nummer eins. Durcharbeiten der Aufgabenliste. Tatsächlich könnte das ziemlich schnell lästig werden.

Und ich muss sagen, ich habe nicht erwartet, dass Open-Source-AI so gut sein würde. Ich dachte, dass es, sagen wir mal, maximal ein paar Jahre hinter den Frontier Labs zurückbleiben würde. Jetzt sieht es so aus, als wäre es Monate. **Was für eine Zeit, um am Leben zu sein.**

**Referenzartikel:** [Auf Viddo ansehen](https://viddo.pro/zh/video-result/de3fa85b-5156-4186-a39d-60c839fb0371)

---