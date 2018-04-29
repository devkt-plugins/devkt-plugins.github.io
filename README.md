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

To download any of them, visit: https://github.com/devkt-plugins/plugin-releaser/releases

Here's a list:

Language            |         Built from
:-------------------|:------------------------------:
CovScript           |[covscript-intellij][cov]
Clojure             |[la-clojure][clj0]
Julia               |[julia-intellij][jl]
JSON                |[intellij-community][json]
Properties          |[intellij-community][ppt]
Lua                 |[EmmyLua][emmy]
Solidity            |[IntelliJ Solidity][sol]
Toml                |[intellij-toml][toml]
Rust                |[intellij-rust][rust]
YAML                |[intellij-community][yml]

  [sol]: https://github.com/intellij-solidity/intellij-solidity
  [cov]: https://github.com/covscript/covscript-intellij
  [clj0]: https://github.com/JetBrains/la-clojure
  [clj1]: https://github.com/gregsh/Clojure-Kit
  [jl]: https://github.com/ice1000/julia-intellij
  [json]: https://github.com/JetBrains/intellij-community/tree/master/json
  [emmy]: https://github.com/EmmyLua/IntelliJ-EmmyLua
  [ppt]: https://github.com/JetBrains/intellij-community/tree/master/plugins/properties
  [toml]: https://github.com/intellij-rust/intellij-rust/tree/master/intellij-toml
  [yml]: https://github.com/JetBrains/intellij-community/tree/master/plugins/yaml
  [rust]: https://github.com/intellij-rust/intellij-rust

# Plugin development guide

Developing DevKt plugin is very like developing IntelliJ IDEA plugin.

Guide is comming soon.
