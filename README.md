# Orge, a Clojure Library For Querying Blueprints Graphs

<img src="https://raw.github.com/clojurewerkz/ogre/master/ogre.png" height="200"></img>

Ogre is a Clojure "dialect" of [Gremlin](https://github.com/tinkerpop/gremlin/wiki).
It is for querying graphs that conform to the [Tinkerpop Blueprints](http://tinkerpop.com) interface.


# Disclaimer: Ogre development is currently on hiatus. There are major breaking changes that need to be made to this library and the documentation and the primary developer ([zmaril](https://github.com/zmaril)) is too busy finishing college to make them. If you are interested in making the changes, please get in touch, otherwise beware!

## Project Goals

 * Provide an API that makes [Tinkerpop Blueprints](http://tinkerpop.com) graphs really easy to query from Clojure
 * Be reasonably feature complete
 * Don't introduce any significant amount of performance overhead


## Community

Ogre questions are welcomed on the [Gremlin mailing list](https://groups.google.com/forum/?fromgroups#!forum/gremlin-users).
If you use Ogre with Titanium, feel free to also use [Titanium's mailing list](https://groups.google.com/forum/#!forum/clojure-titanium).

Please ask any questions you may have!


## Project Maturity

Orge is a young project.
[Archimedes](https://github.com/clojurewerkz/archimedes) currently
uses it. Ogre feels incredibly useful, but nobody has put it into
production yet. We'll update this section as people do.



## Artifacts

Orge artifacts are [released to Clojars](https://clojars.org/clojurewerkz/ogre). If you are using Maven, add the following repository
definition to your `pom.xml`:

``` xml
<repository>
  <id>clojars.org</id>
  <url>http://clojars.org/repo</url>
</repository>
```

### The Most Recent Release

With Leiningen:

    [zmaril/ogre "2.3.0.1"]


With Maven:

    <dependency>
      <groupId>zmaril</groupId>
      <artifactId>ogre</artifactId>
      <version>2.3.0.1</version>
    </dependency>



## Documentation & Examples

 * [Guides](http://ogre.clojurewerkz.org/)


### Code Examples

Our [test suite](test/orge) has many code examples.


### Mailing List

Don't hesitate to join our [mailing list](https://groups.google.com/forum/#!forum/clojure-titanium) and ask questions!


## Supported Clojure Versions

Orge is built from the ground up for Clojure 1.4 and up. The most recent stable release
is always recommended.


## Continuous Integration

TBD: add it to travis-ci.org.


## Development

Orge uses [Leiningen 2](https://github.com/technomancy/leiningen/blob/master/doc/TUTORIAL.md). Make sure you have it installed and then run tests against
supported Clojure versions using

    lein2 all test

Then create a branch and make your changes on it. Once you are done with your changes and all tests pass, submit a pull request
on GitHub.



## License

Copyright (C) 2014 Zack Maril

Licensed under the [Eclipse Public License](http://www.eclipse.org/legal/epl-v10.html) (the same as Clojure).
