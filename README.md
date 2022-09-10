# Using Laravel with GoDaddy

## Notes
While creating this walk-through, I was currently building the <a href="https://www.efinancetracker.com">eFinanceTracker</a> website.  You will see efinancetracker.com mentioned in some of the screenshots.  If you see information redacted (blacked-out) in a screenshot, it is because this may be sensitive data for the eFinanceTracker website and does not apply to you.

Also, the screenshots were taken in September 2022, so they may need to be updated.

## Introduction to GoDaddy

<a href="https://www.godaddy.com">GoDaddy</a> is my personal preference for web site hosting.  Not only is GoDaddy affordable, but they have amazing tech support and they have a 99.99% uptime.  With powerful tools built in, such as phpMyAdmin and cPanel, GoDaddy makes it easy to build and host your website from day one, regardless of your web design experience.  Plus, it is nice that I can find and purchase a domain name, purchase hosting, and install a SSL Certificate all in one place!

## Setup your first web page
Once you have purchased a domain name and hosting, you will need to create a basic web page that will show visitors that your new website is being built.  GoDaddy already creates this file for you, but you should edit it and make it more personal to your new site.  The default page that GoDaddy creates will be located in your public_html folder and is named home.html.  You can  in <a href="/resources/html/home.html">find an example of this file</a> in this repository.  You should edit this file however you see fit.  This page will welcome new visitors to your site while your site is in the development stage.

## Create a subdomain
I usually create a subdomain for development while I am building the web site.  Once I am happy with the development stage here, then I will transfer the files to the main site in order to go "live".  This is easily done in GoDaddy's cPanel.
<ul>
  <li>Login to <a href="https://www.godaddy.com">GoDaddy</a></li>
  <li>Navigate to <a href="https://account.godaddy.com/products">Go to My Products</a>.  You should see this link after you login.</li>
  <li>Scroll down to All Products and Services.  It should look something like this:</li>
</ul>
  <img src="/resources/img/godaddy-products.png" />
<ul>
  <li>Find your web site under the Web Hosting section and click on Manage.</li>
  <li>Find the phpMyAdmin link at the top of the page, right-click it, and open this in a new tab.  I will discuss this in another section on this page.</li>
  <li>Click on the cPanel Admin link</li>
  <li>You should see the following, but please note - you can rearrange the order of these sections by dragging the title bar of each section.
</ul>
  <img src="/resources/img/godaddy-cPanel.png" />
<ul>
  <li>Expand the Domains section by clicking on the + and you should see this:</li>
</ul>
  <img src="/resources/img/godaddy-domains-section.png" />
<ul>
  <li>Click on Subdomains</li>
</ul>
  <img src="/resources/img/godaddy-create-subdomain.png" />
