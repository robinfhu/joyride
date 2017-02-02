Welcome to Joyride
=====================

Joyride is an easy to configure jQuery site tour wizard.

Installation Guide:      http://www.zurb.com/playground/jquery-joyride-feature-tour-plugin

Joyride is MIT-licensed and absolutely free to use.

Features on Robin Hu's Fork
=============

* The addition of a "Previous" button (thanks to Nate Lowry for this code).
* For the last tooltip in the tutorial, show the word "Done" in the next button.
* Adding a new method, "started", which will return true if Joyride is in progress.
* Moved the `preStepCallback` to after the tooltip has become visible, to allow for position adjustments.
* Minor CSS changes.
* A new `data-adjustment` attribute, which lets you modify the top/left position of the tooltip.
* A fix made so that the internal 'defaults' object is not overriden on every joyride initialization.

Example of the `data-adjustment`. This will move the tooltip 30 pixels down and 20 pixels left.


    <li data-id="element-1" data-adjustment="30,-20"></li>



Documentation
==============

Comprehensive documentation is available on the Joyride homepage listed above.

Repo Contents
=============

* README
* DEMO - Demo specific files, not necessary to use the plugin
* joyride-2.1.css - Default Joyride styles, required
* jquery-1.10.1.js - A version of jQuery, required, 1.4.3+ is required
* jquery.joyride-2.1.js - The heart of Joyride, required
* modernizr.mq.js - A custom build of Modernizr with just mediaqueries
* jquery.cookie.js - required for cookie support.
* .gitignore - Those pesky DS_Store files...this is not part of the plugin

ZURB
====

Joyride was made by [ZURB](http://www.zurb.com), a product design company in Campbell, CA.

If Joyride knocks your socks off the way we hope it does and you want more, why not check out [our jobs](http://www.zurb.com/talent/jobs)?

MIT Open Source License
=======================

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
