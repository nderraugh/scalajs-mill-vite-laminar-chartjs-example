# An example of using Scala.js with Mill, Vite, Laminar and Chart.js

A clone of the [code](https://github.com/sjrd/scalajs-sbt-vite-laminar-chartjs-example) from Sébastien Doeraene's [Getting Started](https://www.scala-js.org/doc/tutorial/scalajs-vite.html) but using Mill as the build system.

The three main tags that exist in https://github.com/sjrd/scalajs-sbt-vite-laminar-chartjs-example for each phase of the [Getting Started](https://www.scala-js.org/doc/tutorial/scalajs-vite.html) examples have been created to help readers follow along.

# Build & Incremental Reload
```
mill -w livechart.fastLinkJS
```

# Run
```
npm run dev
```

# Test
```
mill livechart.test
```

# Resources
- [Scalablytyped Mill Plugin](https://lolgab.github.io/mill-scalablytyped/#/)
- [vite-plugin-scalajs-mill](https://github.com/aronbergurj99/vite-plugin-scalajs-mill)
- [Example on how to use Vite with Scala.js](https://github.com/lolgab/scalajs-vite-example)