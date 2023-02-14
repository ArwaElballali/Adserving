
# Adserve Website using Next js, tailwind CSS, and a simple back end with sanity 




## Documentation

[Documentation](https://linktodocumentation)

Building and Deploying a fully responsive Modern Adserve website application. With Modern design, animations, the ability to add and edit products dynamically and easily using sanity, and the landing page front-end was built using Next 13, framer motion, and CSS tailwind

The websites mainly contains of these sections:

1. The landing page of the website, and all the sections within it About, Explore, and Get started. 
2. the navbar and the footer on all the pages.
3. the products page. 
4. each product page that contains the may-like products. 
5. the order notifaction final page.



## Deployment

To deploy this project run you need to install the same requirements in the requirements.txt file and install sanity
```bash
 npm install -r requirements.txt
```

```bash
  npm install -g @sanity/cli
```
 to edit the products or add new ones or delete some(in general update the database schema), we start sanity using 

```bash
  sanity start
```
or
```bash
  npx sanity start
```
then run the url, and it accessed by the gmail account.

then run 
```bash
npm run dev 
```
to start the site.
feel free to reach me out for any help.





## Related

The stylings are in both files globals.css and index.js 
in index js there are some const styling variables are using multiple times within a page.

The different landing page sections styles and motions are in the section file.

In constants file there are multiple arrays of objects and arrays that are used among the site.
In component there are the main components such as navbar and footer, products and etc.

Pages file have the main content in js of the pages and the routing between them.

Public file has some constant photos and assets that have been used in the app.
## Screenshots
Desktop Mode 
![App Screenshot](https://i.postimg.cc/J7d7Fxkv/image.png)
Mobile Mode 
![App Screenshot](https://i.postimg.cc/RFWCCnrX/image.png)

Navbar 
![App Screenshot](https://i.postimg.cc/fy7GMwb8/image.png)
 product option takes you to the products page indexproduct.js 
![App Screenshot](https://i.postimg.cc/g2LDCG2R/image.png)
Mobile mode
![App Screenshot](https://i.postimg.cc/WzSFZ45D/image.png)

products displayed here:(indexproduct.js)
![App Screenshot](https://i.postimg.cc/xjtzhS95/image.png)

in mobile view :
![App Screenshot](https://i.postimg.cc/k4SMFz7x/image.png)

when product is clicked the website routes to this dynamic page ([slug].js)

![App Screenshot](https://i.postimg.cc/jjDrvtg9/image.png)
 you can navigate through different product or service images
![App Screenshot](https://i.postimg.cc/FKtjx54Z/image.png)

in mobile view as well:
![App Screenshot](https://i.postimg.cc/Gt98CqRt/image.png)

and at the bottom the other products would be displayed as you may like them as well:

![App Screenshot](https://i.postimg.cc/CMtd8CYC/image.png)
and when buy is clicked this confirmation model is displayed:
![App Screenshot](https://i.postimg.cc/3xPL5hrz/image.png)
and when its confirmed this page would be displaye: (success.js)

![App Screenshot](https://i.postimg.cc/PJPZ5L2y/image.png)

this is the sanity where I can update and change the products and banner data

![App Screenshot](https://i.postimg.cc/ZnDVjBfv/image.png)

Thank you for reading :).
