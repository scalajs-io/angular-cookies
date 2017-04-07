Angular Cookies API for Scala.js
================================
[angular-cookies](https://www.npmjs.com/package/angular-cookies) - angular-cookies binding for Scala.js.

### Description

An `angular-cookies` binding for Scala.js.

### Build Dependencies

* [SBT v0.13.13](http://www.scala-sbt.org/download.html)

### Build/publish the SDK locally

```bash
 $ sbt clean publish-local
```

### Running the tests

Before running the tests the first time, you must ensure the npm packages are installed:

```bash
$ npm install
```

Then you can run the tests:

```bash
$ sbt test
```

### Artifacts and Resolvers

To add the `angular-cookies` binding to your project, add the following to your build.sbt:  

```sbt
libraryDependencies += "io.scalajs.npm" %%% "angular-cookies" % "0.4.0-pre3"
```

Optionally, you may add the Sonatype Repository resolver:

```sbt   
resolvers += Resolver.sonatypeRepo("releases") 
```