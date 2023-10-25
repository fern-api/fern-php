<br/>
<div align="center">
  <a href="https://www.buildwithfern.com/?utm_source=github&utm_medium=readme&utm_campaign=fern-ruby&utm_content=logo">
    <img src="fern.png" height="120" align="center" alt="header" />
  </a>
  
  <br/>

# Ruby Generator

[![Contributors](https://img.shields.io/github/contributors/fern-api/fern-ruby.svg)](https://GitHub.com/dotnet/docs/graphs/contributors/)
[![Pulls-opened](https://img.shields.io/github/issues-pr/fern-api/fern-ruby.svg)](https://GitHub.com/dotnet/docs/pulls?q=is%3Aissue+is%3Aopened)
[![Pulls-merged](https://img.shields.io/github/issues-search/fern-api/fern-ruby?label=merged%20pull%20requests&query=is%3Apr%20is%3Aclosed%20is%3Amerged&color=darkviolet)](https://github.com/dotnet/docs/pulls?q=is%3Apr+is%3Aclosed+is%3Amerged)

[![Discord](https://img.shields.io/badge/Join%20Our%20Community-black?logo=discord)](https://discord.com/invite/JkkXumPzcG)

</div>

This repository contains the source for the various generators that produce TypeScript artifacts for [Fern](https://github.com/fern-api/fern):

- `fernapi/fern-ruby-sdk`
- *more to come!*

The Ruby generators are written in Ruby. We strongly emphasize idiomatic code generation that feels hand-written and is friendly to read.

Fern handles transforming an API definition -- either an OpenAPI Specification or Fern Definition -- into Fern _intermediate representation_. IR is a normalized, Fern-specific definition of an API containing its endpoints, models, errors, authentication scheme, version, and more. Then the TypeScript generator takes over and turns the IR into production-ready code.
