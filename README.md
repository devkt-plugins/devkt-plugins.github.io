# DevKt plugins

[DevKt](https://github.com/ice1000/dev-kt) is a DevCpp-like cross-platform lightweight Kotlin IDE.

It has built-in support for Kotlin syntax highlighting / code execution and Java syntax highlighting, and other languages can be supported by using plugins.  
To load a plugin, you simply need to add the plugin jar to that classpath that you run 

This is the GitHub organization for hosting its plugins.

## DevKt features

+ Fast (at least faster than Emacs/Eclipse/IntelliJ/CLion/VSCode/Atom)
+ Lightweight (Just a tiny Java Swing application, and comming JavaFX version)
+ Kotlin compiler integration (**100% correct parsing**)
+ JetBrains IDE icons
+ Build as jar/class files, run after build, just one click, very fast incremental compilation
+ Manipulating the editor itself using Kotlin
+ Cross platform (windows/macos/linux), since it's just an executable jar
+ One property-based configuration file, hackable (background image, detailed syntax highlight settings)
+ Plugin system based on `ServiceLoader`, simply load a jar will bring new language support

# Plugin list

Currently, all DevKt plugins are based on an IntelliJ IDEA plugin.

Language            |         Built from             |       Latest version
:-------------------|:------------------------------:|:--------------------------:
CovScript           |[covscript-intellij][cov-o]    |[![Release][cov-i]][cov-d]
Clojure             |[la-clojure][clj0-o]           |[![Release][clj0-i]][clj0-d]
Clojure (deprecated)|[Clojure-Kit][clj1-o]          |[![Release][clj1-i]][clj1-d]
Julia               |[julia-intellij][jl-o]         |[![Release][jl-i]][jl-d]
JSON                |[intellij-community][json-o]   |[![Release][json-i]][json-d]
Lua                 |[EmmyLua][emmy-o]              |[![Release][emmy-i]][emmy-d]

  [cov-o]: https://github.com/covscript/covscript-intellij
  [cov-i]: https://img.shields.io/github/release/covscript/covscript-devkt/all.svg
  [cov-d]: https://github.com/covscript/covscript-devkt
  [clj0-o]: https://github.com/JetBrains/la-clojure
  [clj0-i]: https://img.shields.io/github/release/devkt-plugins/la-clojure-devkt/all.svg
  [clj0-d]: https://github.com/devkt-plugins/la-clojure-devkt
  [clj1-o]: https://github.com/gregsh/Clojure-Kit
  [clj1-i]: https://img.shields.io/github/release/devkt-plugins/clojure-devkt/all.svg
  [clj1-d]: https://github.com/devkt-plugins/clojure-devkt
  [jl-o]: https://github.com/ice1000/julia-intellij
  [jl-i]: https://img.shields.io/github/release/devkt-plugins/julia-devkt/all.svg
  [jl-d]: https://github.com/devkt-plugins/julia-devkt
  [json-o]: https://github.com/JetBrains/intellij-community
  [json-i]: https://img.shields.io/github/release/devkt-plugins/json-devkt/all.svg
  [json-d]: https://github.com/devkt-plugins/json-devkt
  [emmy-o]: https://github.com/EmmyLua/IntelliJ-EmmyLua
  [emmy-i]: https://img.shields.io/github/release/devkt-plugins/emmylua-devkt/all.svg
  [emmy-d]: https://github.com/devkt-plugins/emmylua-devkt

# Plugin development guide

Developing DevKt plugin is very like developing IntelliJ IDEA plugin.

Guide is comming soon.
