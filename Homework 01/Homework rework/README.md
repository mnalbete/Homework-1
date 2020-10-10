The first thing i did is change the title tag in the HTML to " horiseon inc." on line 7. By doing this change it makes easier to navigate tabs because the tab says the company name rather then the original text "website".

                                    original html

title website title

                                    rework html

title Horiseon Inc.test title 

The next step I did was change the div text on line 11 and 26 to "Header" the reason for this is to condence the css code to something more simplier. Once i did that change in the html I then went to my css code and made sure the command in the css code corrisponds to the html command. Once I did that change I then notice that i had to delete the . in the css code on the header command so that the code would function and not break. 

                                    original html

div class="header"
        h1 Hori span class="seo" seo span n h1
        div
            ul
                li
                    a href="#search-engine-optimization">Search Engine Optimization a
                li
                li
                    a href="#online-reputation-management">Online Reputation Management a
                li>
                li
                    a href="#social-media-marketing">Social Media Marketing a
                li
            ul
        div
    div

                                    rework html

header
        h1 Hori span class="seo" seo span n h1
        div
            ul
                li
                    a href="#search-engine-optimization" title= "search-engine-optimization">Search Engine Optimization a
                li
                li
                    a href="#online-reputation-management" title="online-reputation-management">Online Reputation Management a
                li
                li
                    a href="#social-media-marketing" title= "social-media-marketing">Social Media Marketing a
                li
            ul
        div
    header

I then added the Tittle command to each of the links provided so that when your mouse hovers over the text it shows the text of what your hovering over. 
                li
                    a href="#search-engine-optimization" title= "search-engine-optimization" Search Engine Optimization a
                li
                li
                    a href="#online-reputation-management" title="online-reputation-management" Online Reputation Management a
                li
                li
                    a href="#social-media-marketing" title= "social-media-marketing" Social Media Marketing a
                li


On line 28 the link to the section where it should go wasnt working so I then added an ID to the text so that once you pressed on the name of search engine optimization it would move to the corrisponding area on the page just like the other two did when you clicked on the names.

                                    original html

    div class="content"
      

                                    rework html

    div id= "search-engine-optimization"  class="content"

the next thing i did so i could condence the css code was on line 29, 36, 43 i changed the class to just "service". The next thing that I added was Alt to the IMG located on line 30, 37, 44 so that if that the picture couldnt be loaded it would show the name of the picture.

                                    original html 

div class="content"
        div class="search-engine-optimization"
            img src="./assets/images/search-engine-optimization.jpg" class="float-left"
            h2 Search Engine Optimization h2
            p
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            p
        div
        div id="online-reputation-management" class="online-reputation-management"
            img src="./assets/images/online-reputation-management.jpg" class="float-right" />
            h2 Online Reputation Management h2
            p
                The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
            p
        div
        div id="social-media-marketing" class="social-media-marketing"
            img src="./assets/images/social-media-marketing.jpg" class="float-left"
            h2 Social Media Marketing h2
            p
                Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.
            p

                                Original css

search-engine-optimization 
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif
    background-color: #0072bb
    color: #ffffff


online-reputation-management 
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif
    background-color: #0072bb;
    color: #ffffff


social-media-marketing 
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif
    background-color: #0072bb
    color: #ffffff

                                    rework html

div class="service"
            img src="./assets/images/search-engine-optimization.jpg" alt= "search engine optimazation" class="float-left" 
            h2 Search Engine Optimization h2
            p
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            p
        div
        div id="online-reputation-management" class="service"
            img src="./assets/images/online-reputation-management.jpg" alt= "online reputation managment" class="float-right"
            h2 Online Reputation Management h2
            p
                The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
            p
        div
        div id="social-media-marketing" class="service"
            img src="./assets/images/social-media-marketing.jpg" alt= "social media marketing" class="float-left" 
             h2 Social Media Marketing h2
            p
                Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.
            p
        div
    div

                                        rework CSS

.service 
    margin-bottom: 20px
    padding: 50px
    height: 300px
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif
    background-color: #0072bb
    color: #ffffff


The next thing I noticed was that i could use multiple css code for multiple html codes so that i may condence and orginize the the css. 
on line 29 i changed the code in the class tag from search engine optimization to service.

                                        orginal css 

search-engine-optimization img 
    max-height: 200px;
}

online-reputation-management img 
    max-height: 200px;


social-media-marketing img 
    max-height: 200px;


search-engine-optimization h2 
    margin-bottom: 20px;
    font-size: 36px;


online-reputation-management h2 
    margin-bottom: 20px;
    font-size: 36px;


social-media-marketing h2 
    margin-bottom: 20px
    font-size: 36px

                                            Rework

service img 
    max-height: 200px;


service h2 
    margin-bottom: 20px
    font-size: 36px

I did the same thing for line 36 and 43. by doing this I was able to delete some of the original css code so that the text and IMG would follow the same rules without writing text for each and every command from the original copy.

                                    Original code 

benefit-lead 
    margin-bottom: 32px
    color: #ffffff


benefit-brand 
    margin-bottom: 32px
    color: #ffffff


benefit-cost 
    margin-bottom: 32px
    color: #ffffff

notice that the 3 codes had the same margin bottom and color assigned to the roles so i deleted 2 of the code and renamed the code just benefit

                                CSS Rework
benefit 
    margin-bottom: 32px
    color: #ffffff

The next thing i notice was it followed the same thing with line 52, 59 and 66. I changed all the class divs to benifit. once i did that i then went to my css code and deleted the necissary code so that the rule would apply.  

                                    Original CSS

benefits {
    margin-right: 20px;
    padding: 20px;
    clear: both;
    float: right;
    width: 20%;
    height: 100%;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #2589bd;


benefit-lead 
    margin-bottom: 32px;
    color: #ffffff;


benefit-brand 
    margin-bottom: 32px;
    color: #ffffff;


benefit-cost 
    margin-bottom: 32px;
    color: #ffffff;


benefit-lead h3 
    margin-bottom: 10px;
    text-align: center;


benefit-brand h3 
    margin-bottom: 10px;
    text-align: center;


benefit-cost h3 
    margin-bottom: 10px;
    text-align: center;


benefit-lead img 
    display: block;
    margin: 10px auto;
    max-width: 150px;


benefit-brand img 
    display: block;
    margin: 10px auto;
    max-width: 150px;


benefit-cost img 
    display: block;
    margin: 10px auto;
    max-width: 150px;

                                        Rework CSS

benefits 
    margin-right: 20px;
    padding: 20px;
    clear: both;
    float: right;
    width: 20%;
    height: 100%;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #2589bd;


benefit 
    margin-bottom: 32px;
    color: #ffffff;


benefit h3 
    margin-bottom: 10px;
    text-align: center;
}

benefit img 
    display: block;
    margin: 10px auto;
    max-width: 150px;
