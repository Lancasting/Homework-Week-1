# Homework-Week-1
The finished assignment for week 1 homework.

References: 
/* http://meyerweb.com/eric/tools/css/reset/ 
   v2.0 | 20110126
   License: none (public domain)
*/

What has been done:

This was removed: .benefit-cost h3 {
                    margin-bottom: 10px;
}

I brought these together since they were redundant in the CSS code:
.benefit-lead img,
.benefit-brand img,
.benefit-cost img {
    display: block;
    margin: 10px auto;
    max-width: 150px;

Paragraphs on the page like .search-engine-optimization, .online-reputation-management, .social-media-marketing were all brought together since they all have the same values: {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;

.search-engine-optimization img .online-reputation-management img, .social-media-marketing img were all brought together because of the same values:  {
    max-height: 200px;
}

.search-engine-optimization h2, .online-reputation-management h2, .social-media-marketing h2, were all brought together because of the same values: {
    margin-bottom: 20px;
    font-size 36px;

    added alt tags to the images in the HTML

    Brought the p tag items all together on one line

    Added closing tag to Benefit cost image

    Added spacing between divs to read easier

    Added proper indentation to the divs so it looks cleaner

    Added a Reset CSS file for multiple browsers

    Removed some language in the footer paragraph that wasn't doing anything

    Brought P and content in CSS down to where it appears in the HTML

    Removed span (because it wasn't mentioned in the CSS) in the html and brought header h1 together in CSS:

    .header h1 {
    display: inline-block;
    font-size: 48px;
    color: #d9dcd6;
}

