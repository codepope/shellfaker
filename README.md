# shellfaker and nodefaker

These are examples which got with the blog posting "Boosting JavaScript: From MongoDB's shell to Node.js". Each example is a different iteration of the solution outlined in the article.

* `shellfaker.js` is the starting point, a MongoDB mongo shell script with generates up fake names and inserts them into a collection.

* `nodefaker.basic.js` is the first iteration, wrapping the shell script with sufficient Node.js calls so that it can run from the command line in a similar way.

* `nodefaker.await.js` uses the `await` and `async` features to replicate the shell's timing behavior.

* `nodefaker.promise.js` gets smarter about promises and boosts the scripts performance.

* `nodefaker.bulk.js` skips the whole thing and goes for really fast bulk inserting as a counter example.


