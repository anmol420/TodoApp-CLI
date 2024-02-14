# TodoApp-CLI

<h2>Requirements</h2>

>[Rust](https://www.rust-lang.org/) <br>
[Visual Studio Code](https://code.visualstudio.com/) or any other code editor <br>
[Git](https://git-scm.com/downloads)

<h2>How To Use</h2>

- Please Ensure That You Have Installed Rust On Your Device.
- Clone The Repository and type `cargo run` for running the cli interface.

<h2>Example Commands</h2>

```rs
$ cargo run -- -j test-journal.json add "buy milk"

$ cargo run -- -j test-journal.json add "take the dog for a walk"

$ cargo run -- -j test-journal.json add "water the plants"

$ cargo run -- -j test-journal.json list
1: buy milk                                           [2021-01-08 16:39]
2: take the dog for a walk                            [2021-01-08 16:39]
3: water the plants                                   [2021-01-08 16:39]

$ cargo run -- -j test-journal.json done 2

$ cargo run -- -j test-journal.json list
1: buy milk                                           [2021-01-08 16:39]
2: water the plants                                   [2021-01-08 16:39]
```

<h2>Developer</h2>

👤 anmol420.
- GitHub: [anmol420](https://www.github.com/anmol420)
- Discord: [Anmol](https://www.discord.com/users/875986400649052191)

<h3>Contributing</h3>

- Contributions, issues and feature requests are always needed and welcome!

<h3>Support</h3>

You can show your support by giving a ⭐ if you find some help!
