# zurek-portfolio

[Visit the Deployed Site](https://azurek17.github.io/zurek-portfolio/)

![Zurek-Portfolio](./images/project%202.png)

## Description

This site was built to help assist a potental employer to browse through by profolio and review code to see if i would be a good canidate for an open poition.


## Usage

The Webpage consist of three main sections. An About Me, My Portfolio, and Contact me. 


Header:

At the top of the page I provided my name, title, and a navagtion bar. The navagation bar includes About Me, My Protfolio, and Contact Me. If you click a section in the navagation bar, it sends you to it on the page. This was accomplished by creating an anchor tags.

Example:

'''html

            <a href="#about">About Me</a 



-----------------------------------------------------------------------

### About Me:

This section provides a little infomation about me.  I also listed Current Knowledge, By the End of 2023, and Furture.  I used Unorder lists to accomplish that.

Example of code: 

'''html

                        <ul>
                            <p>Current Knowledge:</p>
                            <li>xxxxxx</li>
                            <li>xxxxxx</li>
                            <!-- additional code omitted for clarity  -->
                        </ul> 
                        <ul>
                            <p>By end of 2023:</p>
                            <li>xxxxxxx</li>
                             <li>xxxxxx</li>
                            <!-- additional code omitted for clarity  -->
                        </ul>
                        <ul>
                            <p>Future:</p>
                            <li>xxxxxxxx,</li>
                             <li>xxxxxx</li>
                            <!-- additional code omitted for clarity  -->
                        </ul> 



-----------------------------------------------------------------------------

### My porfolio:

This section displays my projects.  By clicking on the project, it will open a new tab, and sends you to the projects repository to be viewed.  

Example of code:

'''html

        <a href="https://#######" target="_blank"><img src="##" alt="##"><h4>Horiseon Consulting</h4></a>
        <!-- additional code omitted for clarity  -->



I've make the porfolio image links interactive. When you hover over them, select them, etc, they change colors.  This was accomplish using CSS

Example of code:

'''CSS

        a:link  {
            color: blue;
        }

        a:visited {
            color: blue;
        } 

        a:hover {
            color: red;  
        }

        a:active {
            color:green;
        }

------------------------------------------------------------

### Contact:

This section provides a couple ways to contact me.  By email address, LinkedIN webpage, and a Github page.  By clicking on the email address, it will start an email with may email address in the To: field.  The LinkedIN and Github links will open new tabs in your broswer and send you to my pages.

Example of code:

'''html

    <a href="mailto:andyzurek@gmail.com" target="_blank"> andyzurek@gmail.com</a>
    <a href="https://linkedin.com/in/andy-zurek-374bb9291" target="_blank">andy-zurek-374bb9291</a>
<!-- code modifed for clarity  -->


© 2023 github.com/AZurek17/zurek-porfolio Confidential and Proprietary. All Rights Reserved.

