# Reynard #

This is a fork of Adrian's great looking [foxslide](https://github.com/sevenadrian/foxslide) theme for octopress.

## Navbar

Instead of the *About me* and the other social widgets that appear in
the original foxslide, Reynard has a navbar. I did this because my
blog is also my personal website and I needed a navbar to stick in a
few custom links.

### Sticking custom links in the Navbar

Adding links to `pages` or even external websites to the navbar is
easy. Add a section like this to the `_config.yml` of your blog --

````
navigation_elements: [
  {name: "About Me", link: "/aboutme"},
  {name: "Code", link: "https://github.com/hyfather"}]
````

Note that these links will open in the same window, they don't have a
`target` attribute as of now.


## New background

I also replaced the original photo from foxslide with a wonderful black and
white from Carrie Nelson that I found
[here](http://www.flickr.com/photos/69912667@N07/6778147487/). It is
licensed under [Creative
Commons](http://creativecommons.org/licenses/by-nc-nd/2.0/) with
"Noncommercial, Attribution and No Derivative Works".


## Spacelab from Bootswatch

Since the original foxslide is built upon Bootstrap by Twitter, it was
simple to switch it out with
[Spacelab](http://bootswatch.com/spacelab/).

## Installation

````
$ cd blog
$ git clone https://github.com/hyfather/reynard.git .themes/reynard
$ rake install["reynard"]
$ rake generate
````

## Live preview

My [personal blog](http://blog.hyfather.com) uses Reynard.

## Screenshots

### Landing Page
![Landing page](https://raw.github.com/hyfather/reynard/master/screenshots/landingpage.png)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fhyfather%2Freynard.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fhyfather%2Freynard?ref=badge_shield)

### Blog Post
![Blog post](https://raw.github.com/hyfather/reynard/master/screenshots/blogpost.png)

### Footer
![Footer](https://raw.github.com/hyfather/reynard/master/screenshots/footer.png)



## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fhyfather%2Freynard.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fhyfather%2Freynard?ref=badge_large)