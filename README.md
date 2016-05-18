# :warning: BE WARNED :warning:

Be sure that any possible usage of this doesn't pose a significant security risk to your Heroku account, your Heroku apps and ultimately your end users.

#### Usage

1. Create a Heroku app
2. Set `HEROKU_API_TOKEN` a variable on the app
   * `heroku config:set HEROKU_API_TOKEN=<your-token-goes-here>`
3. Configure the app to use this buildpack
   * `heroku buildpacks:add https://github.com/chids/heroku-toolbelt-buildpack.git`
