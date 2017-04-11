# Why another grid?

Frontend frameworks are doing a poor job with separation of concerns. I find myself loving one aspect of a framework and hating another. But it's difficult to pull apart those aspects and pick and choose from different projects.

Decoupled is my attempt to resolve that.

Starting with decoupled-grid, I intend to create a set of frontend design elements that can all easily be used alone or with any other elements. Each should respect the global namespace and stay out of the way.

Another goal I have is to reduce the verbosity of frameworks. Long descriptors are excellent for humans to read when they provide information that short descriptor don't. If they don't, shorter is better because shorter is always easier to type.

Why use something like `class="column small-3"` when `class="cs3"` is quite clear in the contest of any child element that is inside of `class="decoupled-grid"`?

`class="decoupled-grid"` itself might lengthy, but that's an example where clarity is established, therefore it's useful. And since you only need to type it once, enabling all child elements to be short, it's quite efficient.

