# Front-end

Before continuing, make sure you've done all the [installations](https://github.com/paulmondon/Workshop_Scraping/blob/main/Installations.md)

## Step 01 - Get file

get the `scraping.py` file which contains all the imports you will need

## Step 02 - Open palace page

Open palace shop page `https://shop.palaceskateboards.com/` with selenium.

Help yourself with the documentation `https://www.selenium.dev/documentation/`

## Step 03 - Collect all items

In your `Home.vue` file create a new data equal to [this](https://github.com/paulmondon/Workshop_Scraping/blob/main/asides/images/workshop.png) array.
Now you need to create a new component `PostItem.vue`that displays posts informations of one object in the array (import this component in `Home.vue`):
![plot](https://github.com/TristanB12/postApp_workshop/blob/master/asides/images/post.png)

Check the [v-for](https://vuejs.org/v2/guide/list.html) directive to render each posts.

## step 03 - Add post
![plot](https://github.com/TristanB12/postApp_workshop/blob/master/asides/images/home_page.png)

In this last step you want to add an *add post* feature: user can write a message and add it in the array of posts.
In your `Home.vue` create an input and a *add post* button.
Use what you've learned in this workshop to implement this feature. If you want to add an object in the array, use the following syntax:
`array.push(object)`.
