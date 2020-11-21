
Literally just a list of shit I always forget. Maybe I should actually learn this stuff? That would be a good idea, but who has the time 🙃 

# GIT

### Aliases
`git config --global alias.s status` - set a git alias

### Tags

- to create a "lightweight" tag simply run `git tag _tag-name_`
- to create a tag for a commit you've passed simply add it to the end `git tag _tag-name_ _sha_`
- to push a tag you need to do `git push --tags`


# HTML

- Why uses ul or ol instead of just divs?
  - 😅


# CSS

:nth-child() - means select this if it is the nth-child. My thinking of this originally was wrong. I thought it would select the nth child from the queried results, but it doesn't mean that. It means select the nth-child() of the parent element. E.g.


.example > a:nth-child(1) - this will be null, because nth-child(1) is a span and nth-child(1) says select the first child element.

<div id="example">
	<span>hello</span>
	<a href="#">link one</a>
	<a href="#">link two</a>
</div>


[this link to css-tricks is really helpful](https://css-tricks.com/the-difference-between-nth-child-and-nth-of-type/)



# Chrome web store publishing

It's really hard to figure out how to upload a new version. You have to go to "package" in the left had menu then in the top right it will say "Upload new package". This is how you can update
your application. 


# Arch Linux

- [Groups](https://wiki.archlinux.org/index.php/users_and_groups#Group_management) 
