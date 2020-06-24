# awesome-developer-experience
A list of awesome tools we use to improve our developer experience (DX)

## Connectivity

Escape from localhost while in development mode. Obvious security risks in production.

* [ngrok](https://ngrok.com/) - secure introspectable tunnels to localhost
  * Use-case: you want to make your localhost server publicly exposed
* [Webhook.site](https://webhook.site/) - easily test, inspect, forward and create Custom Actions for any incoming HTTP request or e-mail
  * Use-case: you want to test/debug any incoming HTTP request or email without publishing your own server

## Version control

* [npm-merge-driver](https://www.npmjs.com/package/npm-merge-driver) - Automatically merge conflits in `package-lock.json` / `yarn.lock` files from JavaScript package managers (npm, yarn) by teaching git how to it.
  * Use-case: you want to automatically fix lockfile conflicts during git merge / rebase operations.
* [rebase-editor](https://www.npmjs.com/package/rebase-editor) - Simple terminal based sequence editor for git interactive rebase.
  * Use-case: you've heard of `git rebase` and want a convenient way to do it from the terminal, without learning vim.

## Continuous delivery

* [Humanitec](https://humanitec.com) - Continuous Delivery API for Kubernetes-ready applications.
  * Use-case: you want to manage environments (e.g., dev, staging, feature branch, QA) for your Kubernetes applications with one state-of-the-art UI and open API.
