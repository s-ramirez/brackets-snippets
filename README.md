Imitate snippets feature of Sublime Text, and bring it to [Brackets](http://brackets.io/).

# Screen demo
![brackets-snippets-demo.gif](http://edwardchu.org/assets/images/brackets-snippets-demo.gif "Demo gif of the extension")
> Gif size ~500kb, please wait until loaded

# Features
1. Insert snippets by pressing `Tab` key
2. Select next variables or place cursor by pressing `Tab` key
3. Edit multiple variables at one time
4. Fully customize your own snippets in `Snippets Manager` (See below)
5. Hang around `Snippets Library` and find some other awesome snippets! (See below)

# Snippets Manager
![snippets-manager.png](http://edwardchu.org/assets/images/snippets-manager@2x.png "Snippets Manager Screenshot")

# Snippets Library
![snippets-library.png](http://edwardchu.org/assets/images/snippets-library@2x.png "Snippets Library Screenshot")
> The library is currently maintained by myself, you can contribute more snippets by simply creating an issue and submit your snippets, or
> 
> 1. Fork this project;
> 2. Edit [library-hints.yml](https://github.com/chuyik/brackets-snippets/blob/master/library-hints.yml), then commit changes and push it to your repository;
> 3. Perform a [pull request](https://github.com/chuyik/brackets-snippets/pulls).

# Snippet Format
You will see help on snippet creating page. Or check out the examples in `Snippets Library`.
> Environment variables would be added in future, see Todo#2.

# Installation
Search `Brackets Snippets (by edc)` in Brackets Extension Manager, and install it.

# Todo
1. Show snippets according to code context rather than file type, such as supporting internal style sheet
2. Add [Environment Variables](http://docs.sublimetext.info/en/latest/extensibility/snippets.html#environment-variables) support like what Sublime Text provides
3. Allow import/export snippets (yaml format)
4. Allow `Alt(Option)+Tab` to focus previous variables

# Credits
1. [JavaScript & NodeJS Snippets for Sublime Text 2/3](https://github.com/zenorocha/sublime-javascript-snippets)
2. [HTML snippets for Sublime Text](https://github.com/joshnh/HTML-Snippets)
3. [CSS snippets for Sublime Text](https://github.com/joshnh/CSS-Snippets)