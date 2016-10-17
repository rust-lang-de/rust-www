---
layout: default
title: An Rust Mitwirken &mdash; finden, betreuen und fixen von Problemen &middot; Die Programmiersprache Rust
---

# An Rust Mitwirken &mdash; finden, betreuen und fixen von Problemen

Das tägliche Arbeit an dem Projekt findet vornehmlich in Rusts [issue tracker] und [pull requests][PR] statt.
Hilfe wird immer gebraucht.
Die einfachste Art anzufangen ist sich die Issues mit den Labels [E-easy] oder [E-mentor] anzuschauen.
Diese sind besonders zugänglich für neue Mitwirkende.

Bei `E-mentor` Issues hat sich ein erfahrener Rust Entwickler freiwillig gemeldet dir beim Lösen des Problems zur Seite zu stehen,
bis du zum Schluss die [Lösung als Pull Request][pull] einreichst.
Kontaktiere den Mentor im Issue Tracker in dem du seinen Namen in einem Kommentar [erwähnst][@mentioning] oder ihn via IRC oder E-Mail anschreibst.
Bitte beachte dabei, dass Rust Entwickler einen ganzen Haufen Benachrichtigungen bekommen und diese deshalb auch manchmal übersehen können.
Also zögere nicht deinen Mentor auf jedwedem möglichen Weg zu erreichen.
Andere Projekte rund um Rust haben ähnliche Einsteiger-Level Aufgaben
dazu zählt der Webbrowser [Servo],
die HTTP Bibliothek[hyper],
der Source-Formatierer [rustfmt],
die Unix Bibliotheks Bindings [nix],
und die Lint-Sammlung [clippy].

Obwohl Rust bereits über eine [Umfangreiche Testsuite][test] verfügt, kann man nie genug testen.
Das Label [E-needstest]
weißt auf Issues hin, die zwar als gelöst zählen, aber noch durch weitere Tests bestätigt werden müssen.

Testfälle schreiben ist außerdem eine gute Möglichkeit ein neues Projekt zu verstehen und anzufangen dazu beizutragen.

Rust braucht immer Leute die Issues [betreuen][triage]:
Bugs reproduzieren, Testfälle untersuchen, Labels vergeben und gelöste Issues schließen. <!--"minimize test cases" was soll das heißen-->
Bitte beachte, dass du erweiterte GitHub Berechtigungen benötigst um Labels zu vergeben,
aber diese kannst du einfach bekommen, wenn du bereits etwas Erfahrung mit dem Projekt gesammelt hast,
frag einfach ein [Team Mitglied][team].

Sobald du dich mit dem Projekt etwas vertraut gemacht hast und du ein paar Pull Requests in einem bestimmten Bereich geöffnet hast, dann erwäge doch selbst Pull Requests zu begutachten:
Gute Begutachter sind immer sehr willkommen.
Hierfür sind keine besonderen Berechtigungen notwendig &mdash; fange einfach an konstruktiv und höflich anderer Leute Pull Requests zu kommentieren.
Wenn du Hinweise suchst wie man gute Code-Reviews durchführt, lies einfach [diesen Leitfaden][reviews].
<!--
TODO: weekly triage email?
TODO: @nrc says suggesting everybody review w/o training is bad
-->

[@mentioning]: https://github.com/blog/821
[E-easy]: https://github.com/rust-lang/rust/issues?q=is%3Aopen+is%3Aissue+label%3AE-easy
[E-mentor]: https://github.com/rust-lang/rust/issues?q=is%3Aopen+is%3Aissue+label%3AE-easy+label%3AE-mentor
[E-needstest]: https://github.com/rust-lang/rust/issues?q=is%3Aopen+is%3Aissue+label%3AE-needstest
[PR]: https://github.com/rust-lang/rust/pulls
[Servo]: https://github.com/servo/servo
[clippy]: https://github.com/Manishearth/rust-clippy
[hyper]: https://github.com/hyperium/hyper
[issue tracker]: https://github.com/rust-lang/rust/issues
[nix]: https://github.com/nix-rust/nix/
[pull]: https://github.com/rust-lang/rust/blob/master/CONTRIBUTING.md#pull-requests
[reviews]: http://blog.originate.com/blog/2014/09/29/effective-code-reviews/
[rustfmt]: https://github.com/rust-lang-nursery/rustfmt
[team]: team.html
[test]: https://github.com/rust-lang/rust-wiki-backup/blob/master/Note-testsuite.md
[triage]: https://github.com/rust-lang/rust/blob/master/CONTRIBUTING.md#issue-triage
