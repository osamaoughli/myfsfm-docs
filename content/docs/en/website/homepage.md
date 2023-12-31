
# Homepage



**A homepage is the default landing page of your website.**


ERPNext's Website Module generates a default landing page for your website. You
can customize it in Homepage.


To access the Homepage page in ERPNext, go to:



> 
> Home > Website > Portal > Homepage
> 
> 
> 


## 1. How to setup Home Page


1. Select the Company.
2. Set the Title. This will be shown in the Browser Tab.
3. Configure the Hero Section as explained in the next section.


![Homepage](/files/homepage.png)
*Homepage*



> 
> Make sure your default 'Home Page' is set as `home` in Website Settings for
>  this to work.
> 
> 
> 


## 2. Hero Section


There are three ways in which you can customize the way the Hero Section looks:


1. Tag Line and Description (Default).
2. Homepage Slideshow.
3. Custom Hero Section.


### 2.1 Tag Line and Description


After you set your Tag Line, Description and Hero Image you'll have a decent
looking front page. You can also change the URL for the Explore button under **URL for "All Products"**.


![Website Homepage](/files/website-homepage.png)
*Website Homepage*


### 2.2 Homepage Slideshow


Set the **Hero Section Based On** to **Slideshow** and the **Homepage Slideshow**
field will appear.


![Homepage Slideshow Setting](/files/homepage-slideshow-setting.png)
*Homepage Slideshow Setting*


Now, select an existing Slideshow or create a new one shown as follows:


![Website Slideshow](/files/website-slideshow.png)
*Website Slideshow*



> 
> For best results, make sure all of your slideshow images have same height and
>  their width is greater than the height.
> 
> 
> 


![Website Homepage with Slideshow](/files/website-homepage-slideshow.gif)


### 2.3 Custom Hero Section


The third type of Hero Section allows you to write your own HTML.


Set **Hero Section Based On** to **Hero Section**.


Now create a new Hero Section. Set **Section Based On** as **Custom HTML**.
Write your custom HTML in the Section HTML field.


![Homepage Settings](/files/homepage-hero-custom.png)
*Homepage Settings*


You can write any valid [Bootstrap 4](https://getbootstrap.com/) markup here.


![New Hero Section](/files/hero-custom.png)
*New Hero Section*


It will look something like this:
![Homepage Hero Custom](/files/website-homepage-custom.png)
*Homepage Hero Custom*


## 3. Featured Products


You can also show featured products on your Homepage by adding them to the
Products table.


![Homepage Products Table](/files/homepage-featured-products.png)
*Homepage Products Table*


It will look something like this:
![Featured Products on Homepage](/files/website-featured-products.png)
*Featured Products on Homepage*


## 4. Homepage Section


You can add custom sections on your Homepage by creating new Homepage Sections.



> 
> Go to Website > Portal > Homepage Section
> 
> 
> 


A homepage section can consist of cards or Custom HTML. Set **Section Based On**
to **Cards**.


![New Homepage Section](/files/new-homepage-section.png)
*New Homepage Section*


Add details for each card like Title, Subtitle, Image, Content and Route in the
Section Cards table.


It will look something like this:
![Homepage Section](/files/homepage-section.png)
*Homepage Section*


You can also control the order in which these sections appear by setting the
**Section Order**. 0 will be shown first, followed by 1, and so on.



> 
> To add Sections with Custom HTML refer [Custom Hero Section](#23-custom-hero-section).
> 
> 
> 


## 5. Custom Homepage


ERPNext allows you to have a completely different homepage if you don't want to
use the default one described above.


To setup a custom homepage:


1. Create a [Web Page](/docs/en/website/web-page).
2. Go to Website > Setup > Website Settings.
3. Set Home Page as the `route` of your Web Page.
![](/files/custom-homepage.png)




