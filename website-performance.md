## Notes: Optimising the Critical Rendering Path
#### By Patrick Hamann, at #SassConf

* Concatenate your files to reduce the amount of HTTP requests your site is making.
* Optimize and compress images!
* Your browser can only make 6 open connections to the same domain at a time.
* The steeper your performance waterfall, the better.

* `async`'d files are non critical, should not repaint the DOM / alter elements
