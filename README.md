# cloudfoundry-multi-buildpack

Use multiple buildpacks on your app

## Configuration

Add a .buildpacks file into your directory containing git url of custom buildpacks.
Example of two buildpacks, nodejs and java:

https://github.com/heroku/heroku-buildpack-nodejs.git
https://github.com/heroku/heroku-buildpack-java.git


## Usage

    $ cf push -b https://github.com/ejust/cloudfoundry-multi-buildpack.git



## License

MIT
