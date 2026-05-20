Initial JSON patch will be a little noisy due to some whitespace differences, eg:

```diff
-    "functions": [ ],
+    "functions": [],
```

But subsequently just the `comments` keys for each property object will be seen in patches.

In this repo example I also kept a sibling copy of the JSON sans any comments.
