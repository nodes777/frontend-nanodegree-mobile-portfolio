## Website Performance Optimization portfolio project

This project showcases my ability to take a jank filled website and speed it up by reducing the critical rendering path, meeting frame rate requirements, and making efficient choices in computation.

####Part 1: Optimize PageSpeed Insights score for index.html

	1. I added the 'async' property to my web font link so that it loads after the rest of the page loads
	2. Added the 'media=print' query for the print.css, so it only accesses that css when printing
	2. I inlined the rest of the css directly into the html file
	4. Changed the photo and name to myself, more personalization to follow

####Part 2: Optimize Frames per Second in views/js/main.js

	1. First I declared the 'randomPizzas' variable outside of the loop so it isn't created each loop.
	2. I put the 'newWidth' property into each of the cases, instead of creating one during each loop
	3.  Cases are read first, then changes applied to the pizza widths

####Part 3: Optimize pizza.html
	
	1. Inlined css
	2. Added 'will-transform' to .mover letting the browser know the pizzas will change
	3. Ended layout thrashing by batching style changes in main.js
	4. Used getElementByClassName(), backface: hidden, and transform z(0) for speed improvments
	5. Moved variable declaration outside of loops
	6. Slice function was removed, since it removed context

### Sample Portfolios

Feeling uninspired by the portfolio? Here's a list of cool portfolios I found after a few minutes of Googling.

* <a href="http://www.reddit.com/r/webdev/comments/280qkr/would_anybody_like_to_post_their_portfolio_site/">A great discussion about portfolios on reddit</a>
* <a href="http://ianlunn.co.uk/">http://ianlunn.co.uk/</a>
* <a href="http://www.adhamdannaway.com/portfolio">http://www.adhamdannaway.com/portfolio</a>
* <a href="http://www.timboelaars.nl/">http://www.timboelaars.nl/</a>
* <a href="http://futoryan.prosite.com/">http://futoryan.prosite.com/</a>
* <a href="http://playonpixels.prosite.com/21591/projects">http://playonpixels.prosite.com/21591/projects</a>
* <a href="http://colintrenter.prosite.com/">http://colintrenter.prosite.com/</a>
* <a href="http://calebmorris.prosite.com/">http://calebmorris.prosite.com/</a>
* <a href="http://www.cullywright.com/">http://www.cullywright.com/</a>
* <a href="http://yourjustlucky.com/">http://yourjustlucky.com/</a>
* <a href="http://nicoledominguez.com/portfolio/">http://nicoledominguez.com/portfolio/</a>
* <a href="http://www.roxannecook.com/">http://www.roxannecook.com/</a>
* <a href="http://www.84colors.com/portfolio.html">http://www.84colors.com/portfolio.html</a>

