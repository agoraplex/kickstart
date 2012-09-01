# HTML5 Boilerplate, Coffee-script, SASS, Compass starter


To kickstart my (hopefully your too) projects, `compass watch` and `cake watch`. Throw in some coding magic and change the world!

```bash
git clone git@github.com:felixlaumon/kickstart.git
git remote rm origin
git remote add [your git repo address]
git push -u origin master
```

Hope this helps!

## Requirement

Uglify-js

`npm install uglify-js`

Compass

`gem install compass`

HTML5 Boilerplate

`gem install html5-boilerplate`

Optionally, growl

`npm install growl`

## Usage

Add coffee-script files to `coffee-script/` also to the array of `prodCoffeeFiles` in `Cakefile`. Then run `cake watch` or `cake build`

Add CSS style to `_page.scss` then run `compass watch` or `compass compile`
