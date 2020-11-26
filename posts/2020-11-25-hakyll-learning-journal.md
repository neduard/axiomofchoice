---
title: Ongoing Hakyll learning journal
---

# 25 Nov

- Custom extensions can be enabled using [`pandocCompilerWith`](https://hackage.haskell.org/package/hakyll-4.13.4.1/docs/Hakyll-Web-Pandoc.html#v:pandocCompilerWith)
- Hackage is awesome
- Haskell supports has a default class.  The `ReaderOptions` and `WriterOptions` have [Default instances](https://hackage.haskell.org/package/pandoc-2.10.1/docs/src/Text.Pandoc.Options.html#line-72).  These can be computed using `def`
- Hackage source is [awesome](https://hackage.haskell.org/package/pandoc-2.10.1/docs/src/Text.Pandoc.Extensions.html#Extensions)
- We can do [tex math in Hakyll](https://www.jdreaver.com/posts/2014-06-22-math-programming-blog-hakyll.html)
- `pandocCompiler` [is just](https://hackage.haskell.org/package/hakyll-4.13.4.1/docs/src/Hakyll.Web.Pandoc.html#pandocCompiler) `pandocCompilerWith defaultHakyllReaderOptions defaultHakyllWriterOptions`
