1.  I really liked the website's layout, how it consistently had the navigation tab and social media links in the same place under the header and in the footer.

2.  The most obvious difference I can see between your website and my own is that your homepage is much less busy than mine, my website had a huge offputting animation on it's homepage which likely leads to a worse user experience compared to your hopepage.
    Our website's formats are pretty similar overall, I think my codebase may be a bit more maintainable if only because mine has fewer
css fields and works with fewer images.

3.  Your code seems to be well structured and organized and all files have appropriate alphanumeric names.

4.  One issue that I found is that in the homepage the fourth link in the navigation tab has the text "About The Team" whereas in the other pages that link has the text "Meet the team", which isn't a big issue but I think typically this sort of navigation tab would have the same text for each link on every page.  Also, in your footer I believe there's a typo where you meant follow instead of follows.  Overall the elements selected seem to be semantically appropriate, And while there is a sitestyle.css page that outlines most of the general style rules there is some redundancy in the page specific files.  An example of this is in playerresourcestyle.css
main{
    display:flex;
    flex-direction:row;
    align-items:center;
    margin-left: auto;
    margin-right:auto;
    justify-content:center;
    flex-grow:1;
    flex-basis:0px;
}
and sitestyle.css
main{
    display:flex;
    flex-direction:column;
    align-items:center;
    margin-left: auto;
    margin-right:auto;
    justify-content:center;
    flex-grow:1;
    flex-basis:0px;
}
It may make sense to override the flex-direction attribute here but I don't believe it's necessary to reiterate all the other attributes that were already set in the general stylesheet.

5.  Great job on this website overall, I enjoyed reading through it.