# Example app for customized strong-loop buildpack

An example app for customized strong-loop buildpack ( https://github.com/mugifly/strongloop-buildpacks/tree/strongloop-cache)

It gives to increase deploying speed for Your Heroku app.

## Time comparison for deployment

* 1st push: 17m57.034s
* 2nd push: 2m28.396s

## Try to deploy to Heroku

	$ heroku apps:create --buildpack https://github.com/mugifly/strongloop-buildpacks.git#strongloop-cache
	$ git push heroku master
	$ heroku open

## License
This example app is based on [LoopBack Sample Application](https://github.com/strongloop/loopback-example-app).
