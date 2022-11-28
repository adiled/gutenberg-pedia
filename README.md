This is a living document that will commit changes next to the project. Final tutorial publication will be a derived work.

# Let's build custom Gutenberg blocks

Gutenberg editor has come a long way since its replacement of classic editor in wordpress core. The official dev tooling for custom development is now stable, ready to scale in userland.

In this example we'll put the whole development flow to test, by building a crowdsourced dictionary plugin with gutenberg support, leveraging `khowarpedia`, an example dictionary search UI that is webonary-compatile.

Following are the reasons why it's a good example case for learning Gutenberg development.

1. It enables crowd-sourcing of rare language datasets, a service to preservation of civilizations.

2. It integrates with various 3rd party APIs, basing on an open format for lexical information.

3. It demonstrates parallel development of logic of a plugin and its relation to Gutenberg blocks which serve as a composable view layer.

4. It explains editor view and user view and hopefully an approach to grasping them.

5. It defines a perspective of how gutenberg editor redefines WordPress as a platform that is bringing micro-frontends and micro-services together, opening the paradigm of generative micro-apps, and yes, I just composed that term. :grin:

If you have faced frustration with Gutenberg editor, know that all paradigm shifting tech in early phases brings tears to the eyes and hairs in the hands, browsers are one major example. This example hopes to better onboard developers to this paradigm, which will help scale the dev tooling in userland.
