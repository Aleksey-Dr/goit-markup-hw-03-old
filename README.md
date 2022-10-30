# goit-markup-hw-03

Repository for homework number 3

23/10/2022

1. Added in styles.css box-sizing to <html>.
2. Added in styles.css Outline to elements.

24/10/2022

1. Added <div> in the Studio page and the Portfolio page.
2. The content <header> placed into <div>.
3. Added class .container for <div> into <header>.
4. Set margin 0 for <body>.

25/10/2022

1. Dimensions containers.
   Width <body> - 1170px. Gutter - 30px.
2. Added radius (4px) and padding: 10px 32px; for hero-button.
3. Removed the .button-title class. The content of the .button-title class is sent to the .hero-button class.
4. Add to class .list:
   padding: 0;
   margin: 0;
5. Add to the .hero-title, .hang-title, .hang-list classes:
   margin-top: 0;
   and the .hero-title:
   margin-bottom: 30px;
   .hang-title:
   margin-bottom: 10px;
6. Add <div> to the Studio page and the Portfolio page. The content "Hero" section placed into a <div> and the content "Hang" section placed into ather <div>. Similarly done for "What are we doing", "Our Team" sections and footer.
7. Add to the .hero-button class:
   padding: 10px 32px;
   border-radius: 4px;
   margin: auto;
8. Add to the .hero class:
   padding-top: 200px;
   padding-bottom: 200px;
9. Removed a .saction class in the Studio and the Portfolio pages.
10. Add a .hang class to the "Hang" section.
11. Add to the .hang class:
    padding-top: 94px.
12. Add to .section-title class:
    margin-top: 0;
    margin-bottom: 50px;
13. Add .we-doing class to the "What are we doing" section.
14. Add to .we-doing class:
    padding: 118px.

26/10/2022

1. Fixed the name to .headrt-page class.
2. Add to the .header-page class:
   padding-top: 24px;
   padding-bottom: 25px;
3. Fixed the property value in the .we-doing class:
   padding: 118px; to padding-top: 94px;
4. Added to the .we-doing class a padding-bottom property whis value 94px.
5. Added to the .our-names class:
   margin-top: 30px;
   margin-bottom: 10px;
6. Add to .our-team p class:
   margin-top: 0;
   margin-bottom: 0;
7. Add .our-team class:
   padding-top: 94px;
   padding-bottom: 94px;
8. Add .container-team class to "Our-team" section.
9. Add to .container-team class:
   background-color: #ffffff;
   padding-bottom: 30px;
10. Add to .footer-back class:
    padding-top: 60px;
    padding-bottom: 60px;
11. Added a .portfolio class for the "Hero" saction in the "Portfolio" page.
12. Added to the .portfolio class:
    padding-top: 94px;
    padding-bottom: 94px;
13. Added to the .filter-button class:
    margin-bottom: 20px;
14. Added to .container-title class:
    margin-top: 0;
    margin-bottom: 4px;
15. Added to the .container-border class:
    padding-bottom: 20px;
    margin-top: 30px;

29/10/2022

1. Added a .imges class for img in the "Studio" and the "Portfolio" pages.
2. Added the property "display" with value "block" to .imges class.
3. /Flex 1/ Added a selector the .nav-ul-site class. Added the property "display" with value "flex" to the .nav-ul-site class.
4. /Flex 2/ Added a selector the .nav-ul-site .item class. Added the property "margin-right" with value "50px".
5. Edge geometry cleaning. Added the pseudo class :last-child. The .item class add the :last-child pseudo class with the property "margin-right:" with value "0".
6. For user convenience added to .nav-ul-site .link:
   display: block;
   padding-top: 12px;
   padding-bottom: 12px;
7. Sorted styles properties into classes.
8. /Flex 3/ Added .header-contacts class. Added to .header-contacts class:
   display: flex;
   margin-left: auto;
9. /Flex 4/ Added a selector the .header-contacts .item class. Added the property "margin-right" with value "50px".
10. For user convenience added to .header-contacts .link:
    display: block;
    padding-top: 12px;
    padding-bottom: 12px;
11. /Flex 5/ Added a .container-header class for <div> into <header>. Added to the .container-header class:
    display: flex;
    align-items: center;
12. /Flex 6/ Added a .nav-main class for <nav> into <header>. Added to the .nav-main class:
    display: flex;
    align-items: center;
13. Added to the .logo class:
    display: block;
    padding-top: 5px;
    padding-bottom: 5px;
    margin-right: 93px;
14. Fixed the value property .header-page class:
15. /Flex 7/ Added a .hang-list class. Added the value property .hang-list class:
    display: flex;
16. Added a .hang-list .item:not(:last-child) pseudo-class. Added the value property .hang-list .item:not(:last-child) pseudo-class:
    margin-right: 30px;
17. Added .item class to <li> into "Hang" section.
18. /Flex 8/ Added a .we-doing .list selector. Added the value property to .we-doing .list selector:
    display: flex;
19. /Flex 9/ Added a .our-team .list selector. Added the value property to .our-team .list selector:
    display: flex;
20. Added .item class to <li> into "Hero" section in "Portfolio" page.

30/10/2022

1.  Added the values properties .container class:
    box-sizing: border-box;
    padding-right: 15px;
    padding-left: 15px;
2.  /Flex 10/ Added a .hang-list .item selector. Added the value property to .hang-list .item selector:
    width: 270px;
3.  /Flex 11/ Added a .portfolio .list selector. Added the value property to .portfolio .list selector:
    display: flex;
4.  /Flex 12/ Added a .container-portfolio selector. Added the value property to .container-portfolio selector:
    flex-wrap: wrap;
5.  /Geometry/ Added a .container-portfolio .link selector. Added the value property to .container-portfolio .item selector:
    display: block;
    width: 370px;
6.  .container-border > li selector sent to comment.
7.  /Geometry/ Added a .container-portfolio .item:not(:nth-child(3n)) structural pseudo-class. Added the value property to .container-portfolio .item:not(:nth-child(3n)) structural pseudo-class:
    margin-right: 30px;
8.  /Geometry/ Added a .container-portfolio .item:not(:nth-last-child(-n + 3)) structural pseudo-class. Added the value property to .container-portfolio .item:not(:nth-last-child(-n + 3)) structural pseudo-class:
    margin-bottom: 30px;
9.  Added .item class to <li> into "What are we doing" section in "Studio" page.
10. /Geometry/ Added a .we-doing .item selector. Added the value property to .we-doing .item selector:
    display: block;
    width: 370px;
11. /Geometry/ Added a .we-doing .item:not(:last-child) pseudo-class. Added the value property .we-doing .item:not(:last-child) pseudo-class:
    margin-right: 30px;
12. /Geometry/ Added the value property to .logo-footer class:
    display: block;
    For user convenience:
    padding-top: 5px;
    padding-bottom: 5px;
    margin-bottom: 15px;
13. /Geometry/ Added a .footer-list class to <li> into <footer>.
14. /Geometry/ Added a .address-footer .footer-list selector. Added the value property .address-footer .footer-list selector:
    padding-bottom: 5px;
15. /Geometry/ Fixed the value property .footer-back class:
    padding-top: 60px to 55px;
    padding-bottom: 60px to 55px;
16. Added modern-normalize.min.css to "Studio" and "Portfolio" pages.
17. Added the value property to .filter-button class:
    border-color: #f5f4fa;
    border-radius: 4px;
18. Added the value property to .filter-button:hover,
    .filter-button:focus class:
    border-color: #2196f3;
19. /Geometry/ Added a .portfolio .item-button:not(:last-child) pseudo-class. Added the value property .portfolio .item-button:not(:last-child) pseudo-class:
    margin-right: 8px;
20. Fixed the value property .filter-button class:
    margin-bottom: 20px to 50px;
21. /Flex 13/ Added a .portfolio-list class. Added the value property to ..portfolio-list class:
    justify-content: center;
22. Fixed the value property .header-page class:
    background-color: #ececec; to #ffffff;.
    Added the value property:
    border-bottom: 1px solid #ececec;
