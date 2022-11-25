# DESU website

This is the code for the [website](https://xiv-desu.github.io/) of the [Dynamis Extreme, Savage, Ultimate]() Discord server, aka DESU. It uses the [Zola] static site generator.

It's also experimentally used to configure parts of the server itself via Terraform (see `content/.discord`). It's currently a very messy setup that works around limitations of Terraform by using Zola as a conveniently present templating engine. Pushing is currently rather manual because Zola does not really work for generating Terraform configs.

[DESU]: https://discord.gg/hVtSqdfFqX
[Zola]: https://getzola.org/
