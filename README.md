# Phackers Use

What Pinoy Tech Hackers use.

## Adding yourself

1. Create a Github repo and add a README containing your setup.
2. Fork phackers/use and add a `username.html` file containing this:

  ```html
  ---
  layout: default
  ---
  
  <script>
  Flatdoc.run({
    fetcher: Flatdoc.github('username/repo')
  });
  </script>
  ```

3. Also add yourself to `phackers.md`:

  ```markdown
  ## [Your Name](username.html)
  
  * Github: https://github.com/username
  * Website http://yoursite.com
  * Other links: http://otherlinks
  ```

4. Send a pull request and your done.
