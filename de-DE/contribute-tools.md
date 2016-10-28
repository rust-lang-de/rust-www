---
layout: default
title: Zu Rust beitragen &mdash; Werkzeuge, IDEs und Infrastruktur &middot; Die Programmiersprache Rust
Contributing to Rust &mdash; tooling, IDEs and infrastructure &middot; The Rust Programming Language
---

# Zu Rust beitragen &mdash; Werkzeuge, IDEs und Infrastruktur

Werkzeuge spielen eine große Rolle beim Erfolg einer Sprache und es gibt noch eine Menge davon zu implementieren.
***Die Rust Entwicklung fokussiert sich derzeit stark auf die [Verbesserung von IDEs][ides]***. Diese Arbeit erstreckt sich über den ganzen Rust Stack, vom Compiler selbst bis hin zu deiner Lieblings-IDE. Folge dem Link für mehr Informationen.

Sowohl Cargo, der Paketmanager, als auch Rustdoc, der Rust Dokumentationsgenerator,
haben zwar einen vollständigen Funktionsumfang, aber haben einen Mangel an Entwicklern.
Rustdoc hat viele offene Issues mit dem [A-rustdoc] Label im `rust-lang` Repository.
Dies sind hauptsächlich Bugs und um zu helfen muss man lediglich einen solchen beheben und einen PullRequest einreichen.
Cargo hat ein [eigenes Repository und eigene Issues][Cargo] und interessierte Helfer können sich im [#cargo] Channel vorstellen.

Obwohl Rust sowohl unter gdb, als auch lldb einigermaßen läuft,
gibt es immernoch ein paar Fälle in denen das Debuggen nicht wie erwartet funktioniert.
Das [A-debuginfo] Label wird für diese Issues verwendet.

Andere Werkzeuge, die Hilfe benötigen, können auf der [awesome-rust] Liste gefunden werden.

Es gibt oft andere interessante Projekte, die nur darauf warten,
dass jemand vorbeikommt und sie implementiert.
Diskutiere mit anderen Tooling-Enthusiasten in [#rust-tools].

[#cargo]: https://chat.mibbit.com/?server=irc.mozilla.org&channel=%23rustc
[#rust-tools]: https://chat.mibbit.com/?server=irc.mozilla.org&channel=%23rust-tools
[A-debuginfo]: https://github.com/rust-lang/rust/issues?q=is%3Aopen+is%3Aissue+label%3AA-debuginfo
[A-rustdoc]: https://github.com/rust-lang/rust/issues?q=is%3Aopen+is%3Aissue+label%3AA-rustdoc
[Cargo]: https://github.com/rust-lang/cargo/issues
[awesome-rust]: https://github.com/kud1ing/awesome-rust
[ides]: https://forge.rust-lang.org/ides.html
