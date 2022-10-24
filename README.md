## Actively Maintained Libraries

### [Redux StoreFlow](https://episode6.github.io/redux-store-flow): [![Maven Central](https://img.shields.io/maven-central/v/com.episode6.redux/store-flow.svg?style=flat-square)](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22com.episode6.redux%22)

Yet another kotlin implementation of Redux, backed by StateFlows and Coroutines.

### [mockspresso2](https://episode6.github.io/mockspresso2): [![Maven Central](https://img.shields.io/maven-central/v/com.episode6.mockspresso2/api.svg?style=flat-square)](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22com.episode6.mockspresso2%22)

A kotlin re-imagining of mockspresso. A testing tool designed to reduce friction, boiler-plate and brittleness in unit tests. It's like dependency injection for your tests, and completely agnostic to your frameworks & mocking libraries of choice.

## Prototype Projects

### [typed2! (for android)](https://github.com/episode6/typed2)

A kotlin re-imagining of typed! (for android). Provides an extensible system to define type-safe, null-safe and optionally async-aware keys for Android's obnoxious key-value stores (i.e. SharedPreferences, Bundles, Intents, SavedStateHandles, NavArguments, etc).

## Legacy Java Projects

### [mockspresso](https://episode6.github.io/mockspresso): [![Maven Central](https://img.shields.io/maven-central/v/com.episode6.hackit.mockspresso/mockspresso-core.svg?style=flat-square)](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22com.episode6.hackit.mockspresso%22)

An extensible auto-mocker for java & junit designed to simplify your unit tests. Mockspresso creates your objects for you, letting you drop the constructors from your tests, while still giving you complete control over how your objects are created and what dependencies are provided/injected.

### [chop](https://github.com/episode6/chop): [![Maven Central](https://img.shields.io/maven-central/v/com.episode6.hackit.chop/chop-core.svg?style=flat-square)](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22com.episode6.hackit.chop%22)

A simple an efficient logging library for Java and Android, inspired by JakeWharton's Timber library.

### [typed! (for android)](https://github.com/episode6/typed): [![Maven Central](https://img.shields.io/maven-central/v/com.episode6.hackit.typed/typed-core.svg?style=flat-square)](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22com.episode6.hackit.typed%22)

Bring sanity to android's key-value stores by defining your keys with types and defaults, so your call-sites don't have to.


## Legacy Gradle Plugins

### [deployable](https://github.com/episode6/deployable): [![Maven Central](https://img.shields.io/maven-central/v/com.episode6.hackit.deployable/deployable.svg?style=flat-square)](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22com.episode6.hackit.deployable%22)

Easily deploy your JARs and AARs to maven-central. Allows you to specify your pom details as gradle.properties and enables support for maven's provided scope and optional flag.

### [gdmc](https://github.com/episode6/gdmc): [![Maven Central](https://img.shields.io/maven-central/v/com.episode6.hackit.gdmc/gdmc.svg?style=flat-square)](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22com.episode6.hackit.gdmc%22)

A dependency manager for gradle that uses a json file to keep track of versions and aliases for your dependencies. Provides a number of tasks to resolve, import and upgrade dependencies so in most cases you never have to manually google a version ever again. Also can work along-side Spring's dependency management plugin.

## Legacy Groovy Libraries

### [nestable](https://github.com/episode6/nestable): [![Maven Central](https://img.shields.io/maven-central/v/com.episode6.hackit.nestable/nestable.svg?style=flat-square)](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22com.episode6.hackit.nestable%22)

Create nestable extensions for your gradle plugins that are assignable via both gradle.properties & gradle DSL.

### [groovykit](https://github.com/episode6/groovykit): [![Maven Central](https://img.shields.io/maven-central/v/com.episode6.hackit.groovykit/gk-files.svg?style=flat-square)](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22com.episode6.hackit.groovykit%22)

Some simple groovy utilities and extensions, mostly used for testing.

## Legacy Other
### [hackit-quickstart](https://github.com/episode6/hackit-quickstart): [![GitHub Release](https://img.shields.io/github/tag/episode6/hackit-quickstart.svg?style=flat-square)](https://github.com/episode6/hackit-quickstart)

A gradle project generator written in go. Generates gradle projects that use episode6's hackit open source tools, namely gdmc and deployable.
