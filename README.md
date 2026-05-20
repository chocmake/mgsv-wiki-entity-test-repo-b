Initial JSON patch will be a little noisy due to some whitespace differences, eg:

```diff
-    "functions": [ ],
+    "functions": [],
```

But subsequently just the `comments` keys for each property object will be seen in patches ([example auto merge](https://github.com/chocmake/mgsv-wiki-entity-test-repo-b/commit/b420fb9b9bf45587d9b61fc186d332161af97722)).

In this repo example I also kept a sibling copy of the JSON sans any comments.
