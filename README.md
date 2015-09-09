# java-formatter

A tool to format Java Code

This application is being written using the [Turin Programming Language](https://github.com/ftomassetti/turin-programming-language).

The goal is to provide an easy-to-use code formatter for Java files:
* with sensible defaults
* customizable

Being the first application being written with Turin it is also an experiment and a showcase for the language.

## Usage

Compile:
```bash
mvn compile
```

Run:
```bash
mvn exec:java -Dexec.mainClass=me.tomassetti.javaformatter.JavaFormatter
```

## License

Apache License 2.0

## Dependencies

This tool is based on [JavaParser](https://github.com/javaparser/javaparser) which Maven will get for you.

Until I release them on Maven central you need to clone and install locally (`mvn install`):
* [Turin compiler](http://github.com/ftomassetti/turin-programming-language)
* [Turin Maven plugin](http://github.com/ftomassetti/turin-maven-plugin)
