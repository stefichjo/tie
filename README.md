Tie allows generation of Haskell server stubs from OpenAPI (v 3.x) specifications.

If you are looking for a generator for Haskell client code, check out the [Haskell-OpenAPI-Client-Code-Generator](https://github.com/Haskell-OpenAPI-Code-Generator/Haskell-OpenAPI-Client-Code-Generator) project.

# Building Tie

Below are the steps to install Tie using the Cabal build tool.

First, you need to clone the repository

```bash
$ git clone https://github.com/scarf-sh/tie.git
$ cd tie
```

Then, you need to build it using cabal:

```bash
$ git clone https://github.com/scarf-sh/tie.git
$ cd tie
```

Finally, you can copy the resulting executable to your desired location, like so: 

```bash
$ cp $(cabal exec -- which tie) ~/.local/bin/tie
```

# Community & Contact

Feel free to join on us on our community Slack (#tie channel)! 

# License

This program is under the terms of the Apache License v2.0.

# Authors

Tie is originally made and currently sponsored by [Scarf](https://scarf.sh) among other [contributors](https://github.com/scarf-sh/tie/graphs/contributors).