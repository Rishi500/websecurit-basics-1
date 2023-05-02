# 0. Welcome

N/A

# 1. A Truly Disruptive Startup (3 points)

```
<script>success()</script>
```

# 2. No Script Allowed (3 points)

```
script<script>success()</script>
```

# 3. One More Time, Like You Mean It (3 points)

```
<sscriptcript>success()</sscriptcript>
```

# 4. An Open-and-Shut Case (3 points)

```
<SCRIPT>success()</SCRIPT>
```

# 5. Time to Mix Things Up (3 points)

```
<scripT>success()</scripT>
```

# 6. A Picture is Worth a Thousand Words (3 points)

```
</h3> <img src="https://media.geeksforgeeks.org/wp-content/cdn-uploads/20210420155809/gfg-new-logo.png" onload="success()"/>
```

# 7. Between a Rock And a Hard Place (3 points)

```
</h3> <img src="https://media.geeksforgeeks.org/wp-content/cdn-uploads/20210420155809/gfg-new-logo.png" onmouseover="success()"/>
```

# 8. Angle of Death (6 points)

Attack input:

```
<</h3>><script>success()</script>
```

Server code:

```js
router.get('/search', async (req, res) => {
  let q = req.query.q
  if (q == null) q = ''

  // TODO: Replace this with your solution.
  // q = ???

  const results = await getResults(q)
  res.render('caloogle-search-page', { q, results })
})
```

# 9. All in a Day's Work

N/A

# 10. In the Wrong Place at the Wrong Time (3 points)

```
TODO: Replace this with your attack input.
```

# 11. You Can't Win 'em All (6 points)

Attack input:

```
TODO: Replace this with your attack input.
```

Server code:

```js
router.get('/search', async (req, res) => {
  let q = req.query.q
  if (q == null) q = ''

  // TODO: Replace this with your solution.
  // q = ???

  const results = await getResults(q)
  res.render('caloogle-search-page', { q, results })
})
```

# 12. When All is Said and Done (6 points)

Attack input:

```
TODO: Replace this with your attack input.
```

Server code:

```js
router.get('/search', async (req, res) => {
  let q = req.query.q
  if (q == null) q = ''

  // TODO: Replace this with your solution.
  // q = ???

  const results = await getResults(q)
  res.render('caloogle-search-page', { q, results })
})
```

# 13. When You Want a Job Done Right

N/A

# 14. Here Today and Gone Tomorrow (3 points)

Attack URL:

```
TODO: Replace this with your solution. **This should be a URL!**
```

# 15. The Early Bird Catches the Worm (3 points)

```
TODO: Replace this with your attack input.
```

# 16. Tying Up Loose Ends (3 points)

```
TODO: Replace this with your attack input.
```

# 17. Take a Page Out of Their Book (6 points)

Attack code:

```js
// TODO: Replace this with your solution.
```

# 18. Congrats

N/A

# Survey responses (3 points)

Write your survey responses in SURVEY.md!
