# EasyBank - Making banking easy!!

EasyBank is Frontend Mentor laid around basic layout concepts and JavaScript functionality.


## Table of Content

* [Overview](#overview)
  *  [The Challenge](#challenge)
  *  [Screenshots](#screenshots)
  *  [Website Preview Links](#livepreview)
  * [Features](#features)


* [My Process](#process)
  *  [Build with](#builtwith)
  *  [My Learnings](#mylearning)

*  [Author](#author)
*  [Acknowledgements](#builtwith)
*  [Useful Links](#usefullinks)


## Overview[](#overview)

**The Challenge**

EasyBank was my very first Web development project where I found the workflow of media queries difficult to grasp.


**Screenshots**

![desktop-preview](https://github.com/J11tendra/Easy-Bank/assets/108735984/944a1ac7-8939-4375-92b5-9079639855e5)

![mobile-navigation](https://github.com/J11tendra/Easy-Bank/assets/108735984/41e6b71a-1f4d-442f-be17-9ce9d85a0690)



**Website Preview Link**

#### Url: [Visit Website](https://easy-bank.pages.dev/)

**Features**

-  Fully responsive website
-  Sematic HTML5 markdown
-  Scalable clean code
-  Mobile first approach
-  Multipage


## My Process



**Built with**

![javascript4](https://github.com/J11tendra/Intrinsic/assets/108735984/4437a469-39cc-4707-a183-d10e08767a7a)
![scss3](https://github.com/J11tendra/Intrinsic/assets/108735984/a9245cf8-a5e6-48a1-ac37-2598486cd68b)



**My learnings**

This project has been my learning ground as it pushed me to research about the bugs i encounter during development and found out some better methods to deal with the project.

I figure out the better semantic way to center the buttons.


    <!-- I have the global style for buttons designs. -->
    <!-- The <a> tag is the link to call to action. -->
    a {
        color: $black;
        margin: 0 auto;
        font-weight: $reg;

        @include breakpoint-up(medium) {
            font-size: $font-5;
        }
    }

I used margin auto for images and had its max-width set to some rem.

    <!-- This is a container for all shop items -->

    &__container {
        margin: 0 auto;
        max-width: 25rem;
        width: 100%;

        @include breakpoint-up(medium) {
            max-width: 48rem;
        }

        @include breakpoint-up(large) {
            max-width: 80rem;
        }

        @include breakpoint-up(x-large) {
            max-width: 110rem;
        }
    }

For the individual card


    <!-- This is individual shop item which adapts to display sizes -->

         &__01 {
                height: 15rem;
                max-width: 11.5625rem;
                width: 100%;
                border-radius: 0.25rem;
                background-color: $very-light-gray;
                box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.1);

                @include breakpoint-up(medium) {
                    height: 26.5rem;
                    max-width: 22.8125rem;
                }

                @include breakpoint-up(large) {
                    height: 26.5rem;
                    max-width: 29rem;
                }

                @include breakpoint-up(x-large) {
                    height: 28.5rem;
                    max-width: 30rem;
                }
        }


The Footer section which was challenging for lablet display. I used flex and column gap to stop the content from overflowing.

    .links {
        display: flex;
        flex-direction: column;
        gap: 1.5rem;
        justify-content: space-between;
        align-items: center;
        margin: 3.75rem 0;

        @include breakpoint-up(large) {
            grid-area: links;
            flex-direction: row;
            align-items: flex-start;
            gap: 4rem;
            text-align: left;
            margin: 0 0 3.75rem 0;
        }

        @include breakpoint-up(x-large) {
            gap: 8rem;
        }
    }
    
## Author

Website Design: Frontend Mentor

Development: Jitendra Choudhary


## Acknowledgement

Finally I'd like to thanks all resources i used during the development process that includes all Fontawesome icons and Freepik images.


## Useful Links

_If you would like to improve the project or have a suggestions, feedback or issues. Feel free to contact me on the above links and i'd happy to respond._

Email: [Jitendra Choudhary](info.jiitendra@gmail.com)

Twitter: [JiitendraC](https://twitter.com/JiitendraC)
