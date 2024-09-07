# Contributing to Vencord

Vencord is a community project and welcomes any kind of contribution from anyone!

We have development documentation for new contributors, which can be found at Work in progress.

All contributions should be made in accordance with our [Code of Conduct](./CODE_OF_CONDUCT.md).

## How to contribute

Contributions can be sent via pull requests. If you're new to Git, check [this guide](https://opensource.com/article/19/7/create-pull-request-github).

Pull requests can be made either to the `main` or the `dev` branch. However, unless you're an advanced user, I recommend sticking to `main`. This is because the dev branch might contain unstable changes and be force pushed frequently, which could cause conflicts in your pull request.

## Write a plugin

Writing a plugin is the primary way to contribute.

Before starting your plugin:
- Check existing pull requests to see if someone is already working on a similar plugin
- Check our [plugin requests tracker]() **Work in progress** to see if there is an existing request, or if the same idea has been rejected
- If there isn't an existing request, [open one]() yourself **Work in progress**
  and include that you'd like to work on this yourself. Then wait for feedback to see if the idea even has any chance of being accepted. Or maybe others have some ideas to improve it!
- Familarise yourself with our plugin rules below to ensure your plugin is not banned

### Plugin Guidelines

- No simple slash command plugins like `/cat`. Instead, make a [user installable Discord bot](https://discord.com/developers/docs/change-log#userinstallable-apps-preview)
- No simple text replace plugins like Let me Google that for you. The TextReplace plugin can do this
- No raw DOM manipulation. Use proper patches and React
- No microphone modifications or fake your communication status (Deafen, Mute).
- No violation trigger. (Banning a user from Discord by a malicious plugin.)
- No plugins that simply hide or redesign ui elements. This can be done with CSS
- No selfbots or API spam (animated status, message pruner, auto reply, nitro snipers, etc)
- No untrusted third party APIs. You have to verify your API by Bytecord Team for being used in production except for Discord API.
- No plugins that require the user to enter their own API key
- Do not introduce new plugin without mentioning if there dependencies. 

## Contribute to the project.

Ideas, improvements and more? Come in forums of the repo and share your throught

## Contribute to our Documentation

The source code of our documentation is available at Work in Progress

Keep maintaining your project at any cost to prevent obsolescence of your client mod. 

## Keep in touch with the community

= Work in Progress =
