# Example Wildfly app on Heroku

Before you try to use this sample, have a look at some of the Wildfly Swarm examples.
They are a much better fit for Heroku.

* [Wildfly Swarm JAX-RS and JPA example](https://github.com/kissaten/wildfly-swarm-jpa-jaxrs)

If you still want a standalone Wildfly server running in a dyno, follow these steps:

```
$ heroku create
$ mvn heroku:deploy
```