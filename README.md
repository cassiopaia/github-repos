# jQuery Github Repos

[![Github Repo Demonstration](http://f.cl.ly/items/0J1y0o0D461A0T1v1328/Screen%20Shot%202013-01-13%20at%207.32.55%20PM.png)](http://zenorocha.github.com/jquery-github-repos/)

## Usage

Use the `github-widget` class and create an attribute called `data-repo`:

```html
<div class="github-widget" data-repo="jquery-boilerplate/boilerplate"></div>
```

Include jQuery:

```html
<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.7.2/jquery.min.js"></script>
```

Include this jQuery plugin:

```html
<script src="jquery.github.repos.min.js"></script>
```

Call the plugin:

```html
<script>
  $('.github-repos').githubRepos();
</script>
```

And that's it \o/

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* v0.3 January 13, 2013
  * Added live demo
  * Replaced single images for a sprite
  * Added minified version
* v0.2 September 11, 2012
  * Code wrapped into a jQuery plugin
  * Demonstration page created
* v0.1 September 10, 2012
  * Initial commit

## License

[MIT License](http://zenorocha.mit-license.org/)