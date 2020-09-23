## Build a Spring Java Microservice with Apache Cassandra

**✅  Create the Astra database** Create a database with keyspace `todoapp` on DataStax Astra.

If this is your first time using Astra, sign up here:

- [Registration Page](http://dtsx.io/workshop)

You can use your `Github`, `Google` accounts or register with an `email`

If you use these signup details, you won't need to make many changes when following along.

```
keyspace: todoapp
User: username
Password: password
```

**✅  Install required dependencies**

Next, install all dependencies, but exclude tests, as we have not implemented them yet:

```
mvn clean install -Dmaven.test.skip=true
```

Your output should end like this:

```bash
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  8.125 s
[INFO] Finished at: 2020-09-02T09:11:36Z
[INFO] ------------------------------------------------------------------------
