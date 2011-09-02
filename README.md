This is an example project that uses the [GitHub Maven Plugins](https://github.com/github/maven-plugins).

See the [POM file](https://github.com/kevinsawicki/github-maven-example/blob/master/example/pom.xml)
for how the downloads plugin and site plugin are configured.


# Using the downloads plugin

```
$ cd github-maven-example/example
$ mvn clean install
```

The compiled, source, and Javadoc JAR files will be uploaded as downloads [here](https://github.com/kevinsawicki/github-maven-example/downloads).

# Using the site plugin

```
$ cd github-maven-example/example
$ mvn site
```

The generated site will be committed to the [gh-pages branch](https://github.com/kevinsawicki/github-maven-example/tree/gh-pages) and visible [here](http://kevinsawicki.github.com/github-maven-example/).
