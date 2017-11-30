# Curated list of community-provided resources for Reaction

This page is here to guide you through the Reaction ecosystem. As we've stated before, we'd not be here without our very engaging community. Lots of people are continuing to contribute to core development, but also supplying other members of the community with valuable plugins, tutorials or learning material. Here we'd like to introduce you to some of the awesome things we've seen out there.

_**Note:** If you miss something that's not listed here and want to see it here, please let us [know](mailto:hello@reactioncommerce.com)._

## Reaction plugins in no particular order

#### reaction-generic-theme

This is a theming plugin directly targeted at those who like to change the theme for a Reaction installation. It's a great way to get accustomed to LESS variables that builds the foundation of Reaction's color palette. It also allows to override styles for more specific parts of the application, like navigation, buttons and the like.

[https://github.com/joshuacox/reaction-generic-theme](https://github.com/joshuacox/reaction-generic-theme)

Requirements:
- Basic LESS/CSS knowledge

Learning content:
- Customize the visual appearance of Reaction
- LESS functions helper functions to ease CSS related boilerplate

Kudos for [Joshua Cox!](https://github.com/joshuacox)


#### customReactionTheme

Another plugin that is concerned with customizing the Shop's CSS styling, but also shows how to render own markup for different parts of the shop, like the landing page. It does so through usage of Reaction's [component API](http://api.docs.reactioncommerce.com/Components.html)

[https://github.com/curranabell/customReactionTheme](https://github.com/curranabell/customReactionTheme)


Prerequisites:

Uses additional meteor package. Open a console in project's root directory and execute this command: `meteor add ultimatejs:tracker-react` to add the required dependency.


Requirements:
- Basic LESS/CSS knowledge
- Basic React understanding

Learning content:
- Customize the visual appearance of Reaction
- Use Reaction's component API to gain control over rendered HTML markup

Mahalo for your kokua, [Curran!](https://github.com/curranabell)


#### loanlaux/reaction-hydrotik-plugin

This is an up-to-date fork of hydrotik/reaction-hydrotik-plugin that works with current Reaction version.

Requirements:
- Basic LESS/CSS knowledge
- Basic React understanding

Learning content:
- Customize the visual appearance of Reaction
- Use Reaction's component API to gain control over rendered HTML markup

Kudos for [Loan!](https://github.com/loanlaux)

#### boomerdigital/reaction-subscription-billing

This plugin is **work-in-progress**, but does address a very common request: A Reaction  plugin that does support the most popular subscription billing features. This is because subscriptions play an important and ever increasing role in the ecommerce landscape.

[https://github.com/boomerdigital/reaction-subscription-billing](https://github.com/boomerdigital/reaction-subscription-billing)

Thank you for helping our ecosystem to grow, [Daniel!](https://github.com/dhonig)


#### boomerdigital/reaction-category-products
 https://github.com/boomerdigital/reaction-category-products


Keep up the good work, [Allie!](https://github.com/acreilly)


## REST-API for Reaction applications
DDP is great and good, but ever found yourself in need for a traditional REST API? Here's how to get your API off the ground:
[https://github.com/kahmali/meteor-restivus](https://github.com/kahmali/meteor-restivus)

As a bonus, you will want to check out the [Swagger add-on](https://github.com/apinf/restivus-swagger).


## Other resources

#### reactioncommerce-json-importer
A small node package, that allows to convert a generic JSON product format into Reaction's product format.
[https://github.com/carlos-olivera/reactioncommerce-json-importer](https://github.com/carlos-olivera/reactioncommerce-json-importer)

Thank you, [Carlos!](https://github.com/carlos-olivera)

## Deprecated resources
Below there's a list of older plugins, that are may be outdated or not be maintained actively. Probably most of them would need significant rewrites to be usable again. Nevertheless we feel it's valuable to have them listed here, because they can serve as good starting point for somebody who wants to implement something similar. No need for reinventing the wheel in many cases..



#### reaction-cod (cash-on-delivery payment provider plugin)
**Status: non-working**

This is an outdated, non-working cash-on-delivery plugin written in CoffeeScript, which is still using Blaze templates. The good news is, that we're in the way of getting a COD-plugin out the door, that uses React components.

Here's the link nonetheless in case you're curious:
[https://github.com/Gouthamve/reaction-cod](https://github.com/Gouthamve/reaction-cod)

Requirements:
- Knowledge of Blaze templating engine
- CoffeeScript

Many thanks to [Goutham!](https://github.com/Gouthamve)

#### regionalization

**Status: non-working**

This plugin extends Products with new location related attributes, like cities and regions. Note that this plugin uses deprecated Blaze templates and is only available in Portuguese.

[https://github.com/danielsouzapinna/regionalization](https://github.com/danielsouzapinna/regionalization)

Requirements:
- Knowledge of Blaze templating engine
- Portuguese language ;-)

Thank you for your support, [Daniel!](https://github.com/danielsouzapinn)


#### hydrotik/reaction-hydrotik-plugin

**Status: non-working**

The plugin is based off of our [reaction example plugin](https://github.com/reactioncommerce/reaction-example-plugin), but takes that a step further to be more like a fully-fledged solution.

[https://github.com/hydrotik/reaction-hydrotik-plugin](https://github.com/hydrotik/reaction-hydrotik-plugin)

Thanks for riding with us, [Donovan!](https://github.com/hydrotik)