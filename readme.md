# HTML5 Boilerplate for Tumblr Themeing

A clean and simple adaptation of the HTML5 Boilerplate 2.0 for Tumblr themeing purposes. The goal was to keep it just as simple as the original, but within the context of a Tumblr theme foundation. That means it doesn't include the stuff that wouldn't really apply to a tumblr theme. If you are familiar working with the HTML5 Boilerplate, you should feel right at home with this.

## Features

* A single page theme that is 'plug and play'
* Normalize.css and default H5BP divs/classes dropped into the `<style>` tags
* Basic tumblr post classes and blocks defined both within the `{Posts}` block, as well as within the `<style>` area
* Google CDN Jquery with Tumblr Static (CDN) Fallback
* H5BP style Google Analytics built-in with the ID definable within the Tumblr UI

## What it doesn't include

A lot, honestly pretty much everything that makes HTML5 Boilerplate really hardcore isn't in this by design.  The unit testing, local libraries, img folder, css folder, crossdomain.xml, .htaccess., and build scripts are all pretty much irrelevant within a tumblr theme.  However, it could easily be argued, depending on how complex your theme is, that these are necessary. In that case I highly recommend you download the entire H5BP and use it alongside my adaptation: [HTML5 Boilerplate](https://github.com/h5bp/html5-boilerplate)

## Contributing

I'm honestly kind of a newb to the tumblr themeing arena, so I welcome all contributions from those more talented than myself. This was really a selfish project to get myself started on a theme.  I was so used to starting with HTML5 Boilerplate for other projects, that I wanted the same baseline for some stuff I want to do with Tumblr.

## But people have already done this

I know there are other options out there, but they are sloppy and poorly executed.  They inexplicably still include local paths to files that a tumblr theme wouldn't have access to.  The ones that exist also tend to do 'too much'. They go way above and beyond what a theme foundation should have.  The whole idea of HTML5 Boilerplate to me, is that it only includes the essentials; everything else should be handled by the developer.  

## License

Pretty much the same as HTML5 Boilerplate

### Major components:

* jQuery: MIT/GPL license
* Modernizr: MIT/BSD license
* Normalize.css: Public Domain

### Everything else:

The Unlicense (aka: public domain)