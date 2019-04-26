portfolio
=========
This project was part of Udacity's website optimization course
to learn techniques to increase the speed of rendering websites.
I made some changes to the udportfolio repository to improve 
the efficiency of the instructor's webpage.  The following are 
comments I made on the Udacity forum in June, 2014:

My page is http://julie1.github.io/udportfolio/  I scored 97 on mobile and 96 on desktop with the pagespeed
insights suggestions by adding async(this doesn't improve the score) to the javascript references, by inlining the css style and google fonts file(the style doesn't improve the score, the google fonts pushes the score way up), and my adding media="print" to the css print file. My mobile score may be better because I cut out the mobile portion of the style file since I don't have a mobile device. I also used an image compressor to compress the photos which did not help much. As a beginner I found the github pages rather difficult to circumnavigate.

On github after forking your site(Cameron-udportfolio), I had difficulty after editing files on the master and
gh-pages in different ways transferring files between those branches or obtaining 
old files from your site and transferring between the github site and my local repository. I had to do various commands to make the sites compatible for transferring files. These issues are not discussed in the documentation. 
I also didn't realize that you had to add a new file to the gh-pages site
to be able to publish the site.
