# Chess Online

A responsive, single-page chess game. Play locally, invite a friend to an online room, or challenge the built-in computer opponent.

## Features

- Computer opponent with adjustable Elo-style strength setting from 100 to 2000
- Local two-player and online room play
- Optional clocks with configurable increments; online clocks start when both players connect and pause during a 20-second reconnect window
- Premoves against the computer and in online rooms
- Player-only resign and draw offers, plus read-only spectator links with the original player seats reserved during reconnects
- Legal move validation, check and checkmate detection, castling, en passant, and queen promotion
- Move history, undo, board flip, fullscreen, extra move and result sounds, and light/dark themes
- Win/loss celebration ribbons and a delayed post-game review prompt
- Replay controls for stepping through every scored move, with an accuracy summary and an approximate one-game Elo-style performance estimate against the computer
- Shareable finished-game links with a read-only replay, move grades, and White/Black board perspectives
- Minimal move-by-move review with original PNG badges for brilliant, great, best, excellent, good, inaccuracy, mistake, and blunder ratings

Open index.html in a browser to play. Online rooms use PeerJS and require an internet connection.
