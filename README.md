google-form-styling
===================
MAJOR WIP::
Designed to create Google form-styling themes, written with [LESS](http://lesscss.org) for ease in cusomization.





### Demo
*Note that this styling sheet does not work with the newest version of google forms. To enable this styling sheet, the google forms needs to be revered to the old version which can be done by clicking on the bottom right hand corner quetion mark and reverting back to the old version.
[Demo form in action](https://james2doyle.github.io/google-form-styling/)

### Stylesheet content

WIP: This stylesheet is a copied default Google form theme, placing variables for colors, and still needs attention to possible stripping of some un-related things.




### Moving Forward

The idea here is to simply copy the form mark Google generates, rather than markdown. This will create a simple stylesheet to add.

Think themes for bootstrap 
markup=unchanged; sylesheets=changed


** the current stylesheet is normalized into something as default as possible so that I can then create a <my-theme-name.css> file that contains all the variables to do the styling, which is u
sing the variables in LESS, working toward a broader option in the future.




### How to create a custom form

* Create a form as normal
* Click the view live form
* Copy everything inside the form tag inluding the form tag itself
* Create a new blank HTML file
* Create an empty div with a `container` class
* Paste all the form markup inside there
* Link the style.css stylsheet
* Test the form and check the response in Google drive

### Hosting the form

Something relatively new to Google Drive is the ability to host static HTML pages.

* Create a public shared folder
* Upload all your **static** html files
* Open the `index.html` file in drive and click the **preview button**
* Copy the link to the page it sends you too
* Share that link with whoever because you are done!

[DEPRECATED]
This is how the [demo form](https://googledrive.com/host/0B3SHb_huRFdyNENfQjVzSGpIOFU/index.html) is hosted.

### lesswatch.js

just run `node lesswatch css` and it will watch all .less files and compile them for you. The lesswatch is written by [idris](https://gist.github.com/idris/1080416).

### If you prefer <3 SASS/STYLUS/BABIES

Well then find and replace all `@varName` signs with `$varName` or just make the variables `varName = value` for Stylus.

I picked LESS because it has a lower barrier to entry than SASS or STYLUS. Even though I <3 Stylus the best.


### License

(The MIT License)

Copyright (c) 2015 James Doyle([@james2doyle](http://twitter.com/james2doyle)) james2doyle@gmail.com

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
