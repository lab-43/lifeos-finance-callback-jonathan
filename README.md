# LifeOS bank callback

This page is part of [LifeOS](https://github.com/lab-43/lifeos) on my computer. When I connect my
bank to LifeOS (through Enable Banking), the bank sends me back here after the login, and this page
passes its answer on to LifeOS at `127.0.0.1` on my own computer. It loads nothing from anywhere,
keeps nothing and sends nothing elsewhere. The one-time code it passes on is useless without the
key that only my LifeOS has.

Please don't edit `index.html`: LifeOS checks that it is byte for byte its own page. To update it,
run LifeOS's `scripts/finance-callback-page.command` again.

---

Diese Seite gehört zu LifeOS auf meinem Computer. Verbinde ich meine Bank mit LifeOS (über Enable
Banking), schickt mich die Bank nach dem Login hierher, und die Seite gibt die Antwort an LifeOS
unter `127.0.0.1` auf meinem eigenen Computer weiter. Sie lädt nichts nach, speichert nichts und
schickt nichts woandershin. Der Einmal-Code, den sie weitergibt, nützt nichts ohne den Schlüssel,
den nur mein LifeOS hat.
