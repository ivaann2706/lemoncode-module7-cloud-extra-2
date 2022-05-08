# Cloud Module - Exercise extra 2

In this repository, a front application is deployed automatically with Docker on Heroku.

The continuous integration flow has been defined in the ci.yml file, so that every time a Pull Request is made, a pipeline is launched to run the tests automatically.
The continuous deployment flow has also been defined in the cd.yml file, so that it is deployed with docker on Heroku every time a push is made on master.

The deployed app can be found at https://lemoncode-module-cloud-extra-2.herokuapp.com/
