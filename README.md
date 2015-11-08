
Description
-----------

The visual tool for prototyping UI for ReactJS components and Web applications. 
In the builder you can easily combine available components with each other, and see how they look and feel right on a Web page.
Then you can generate a source code of new ReactJS component from the combination. 
 
Tightly integrated with ReactJS Component Exchange. Visit [the project gallery](http://helmetrex.com/Gallery.html) for more information.

Features
--------
* Easily prototype UI of any complexity with available ReactJS components.
* Generate source code for new ReactJS component from any combination of other components.
* Edit source code in other IDEs, the changes automatically will be reflected in the builder workspace.
* Include and use any third-party components or even jQuery plugins in the builder.
* Publish own projects on ReactJS Component Exchange site.
* Create static site with prepared HTML which allows to deploy static content into Web hosting immediately.

Installation
------------

    npm install react-ui-builder -g
    
For upgrading of version it is better to uninstall and then install:
 
    npm uninstall react-ui-builder -g


Running
-------

Builder runs as a webserver.

    react-ui-builder

Usage
-----

  1. Go to **http://localhost:2222/builder** in browser. 

  2. Browse gallery of published projects.

  3. Clone project you liked by specifying __ABSOLUTE__ path to local folder where you want to see the source code of the project. This folder should __exist__ and be __empty__.

  4. Cloning and preparing of the project will take some time. 
Most time will be spent by npm installer, builder starts the installation of dependent npm modules automatically after project is downloaded.

  5. Now you can compose components on page, consider page as a desk where you combine components with each other. 


Migration projects for React UI Builder from v0.2.11 to v0.3.0
----------------------------------------------------------
Please write a letter to support(at)helmetrex.com
For every project you will get a support.


Documentation
-------------

To get familiar with the builder's interface and how it works please visit [ReactJS Component Exchange project gallery](http://helmetrex.com/Gallery.html)

Release Notes
-------------
**0.3.4**

* Builder's config moved to cookies, consequently user account doesn't have to be administrator on local OS.
* Now templates for static-site and live-preview HTML and Page components are in the source code of project bundle.
* Bugs fixed:
    * Notes for newly created component were not created
    * Page doesn't scroll to previous place while reloading after successful webpack compilation

React UI Builder needs support
------------------------------
If you think that it's worth to pledge small amount of money to development of the builder,
please become our patron, visit: [the page on Patreon](https://www.patreon.com/ipselon?ty=h)

Find our patrons [here](https://github.com/ipselon/react-ui-builder/blob/master/PATRONS.md)

