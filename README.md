# Using Laravel with GoDaddy
## Introduction to GoDaddy

<a href="https://www.godaddy.com">GoDaddy</a> is my personal preference for web site hosting.  Not only is GoDaddy affordable, but they have amazing tech support and they have a 99.99% uptime.  With powerful tools built in, such as phpMyAdmin and cPanel, GoDaddy makes it easy to build and host your website from day one, regardless of your web design experience.  Plus, it is nice that I can find and purchase a domain name, purchase hosting, and install a SSL Certificate all in one place!

## Setup your first web page
Once you have purchased a domain name and hosting, you will need to create a basic web page that will show visitors that your new website is being built.  GoDaddy already creates this file for you, but you should edit it and make it more personal to your new site.  The default page that GoDaddy creates will be located in your public_html folder and is named home.html.  You can  in <a href="/resources/html/home.html">find an example of this file</a> in this repository.  You should edit this file however you see fit.  This page will welcome new visitors to your site while your site is in the development stage.

## Create a subdomain
I usually create a subdomain for development while I am building the web site.  Once I am happy with the development stage here, then I will transfer the files to the main site in order to go "live".  This is easily done in GoDaddy's cPanel.

<ol>
  <li>Login to GoDaddy</li>
  <li>Navigate to <a href="https://account.godaddy.com/products">Go to My Products</a>.  You should see this link after you login.</li>
  <li>Scroll down to All Products and Services</li>
  <li>Find your web site under the Web Hosting section and click on Manage.</li>
  <li>Find the phpMyAdmin link at the top of the page, right-click it, and open this in a new tab.  I will discuss this in another section on this page.</li>
  <li>Click on the cPanel Admin link</li>
</ol>
