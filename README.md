# Responsive Boilerplate 0.1

My personal mobile-to-desktop template. Combination of snippets and plugins for fast and easy front-end development. Mainly consists of code from the [HTML5 Boilerplate](http://html5boilerplate.com), but expanded with snippets from [Gwen Vanhee's boilerplate](https://github.com/gwenvanhee/Boilerplate-0.2) and other bits and pieces from around the interwebz.

## Grid structure with rows and cols

This template comes with predefined row and column classes. Containers are percentage based and all dimensions are defined as em's. Usage explained in example below:

```html
<!-- .container can also be a .row -->
<section class="container">
  <div class="row">
		<div class="col col-4">Content</div>
		<div class="col col-4">Content</div>
		<div class="col col-2">Content</div>
	</div>
</section>
```
 
Available classes are: _col-2_, _col-3_ and _span-2_, _col-4_ and _span-3_.
 
With these classes any common grid lay-out can be achieved. Classes can also be nested.
 
## Features
 
 + DNS prefetching
 + Meta data for SEO and social sharing
 + Mobile display meta tags
 + Icons (iOS, WP8, favicon)
 + Zepto for modern browsers
 + jQuery + Respond + Selectivizr for IE browsers
 + Modernizr feature detection
 + Debounce-able resize and scroll event (touchmove for iOS compatibility)
 
## Placeholders

In the /assets/ folder you will find a subfolder 'placeholder'. Use the included class and .htaccess (don't forget to change the extension!) to generate customisable dummmy placeholders.
+ ./assets/placeholder/300
+ ./assets/placeholder/400x250/EAEAEA/333333&text=Dummytext
