# Responsive Content Titles
The web is filled with quality content but its presentation has never been more paramount. This code shows you how to implement a popular way of displaying content on your website using responsive tiles. [Solodev](https://www.solodev.com/) will show you how to create tiles which, when clicked, redirect to a page based on the subject of that particular tile. 

## Tutorial

For detailed instructions, view Solodev's [Displaying Content with Responsive Tiles](http://www.solodev.com/blog/web-design/code-examples/displaying-content-with-responsive-tiles.stml) article.

## Demo

Check out a working example on [JSFiddle](https://jsfiddle.net/solodev/ron1wet8/).

## HTML

The responsive content tiles have the following basic HTML markup.

```
<div class="container">
<section class="cms-boxes">
   <div class="container-fluid">
      <div class="row">
         <div class="col-md-4 cms-boxes-outer">
            <div class="cms-boxes-items cms-features">
               <div class="boxes-align">
                  <div class="small-box">
                     <i class="fa fa-4x fa-laptop">&nbsp;</i>
                     <h3>Data Management</h3>
                     <p>Gain valuable insights with WebCorpCo Data.</p>
                  </div>
               </div>
            </div>
         </div>
         <div class="col-md-4 cms-boxes-outer">
            <div class="cms-boxes-items cms-security">
               <div class="boxes-align">
                  <div class="small-box">
                     <i class="fa fa-4x fa-cog">&nbsp;</i>
                     <h3>Enterprise<br> Data Funnel</h3>
                     <p>Pull in realtime data from every source on the web.</p>
                  </div>
               </div>
            </div>
         </div>
         <div class="col-md-4 cms-boxes-outer">
            <div class="cms-boxes-items cms-scalability">
               <div class="boxes-align">
                  <div class="small-box">
                     <i class="fa fa-4x fa-arrows-alt" aria-hidden="true"></i>
                     <h3>Pattern Analysis</h3>
                     <p>The world's most advanced algorithms let loose on your data.</p>
                  </div>
               </div>
            </div>
         </div>
      </div>
      <div class="row">
         <div class="col-md-6 cms-boxes-outer">
            <div class="cms-boxes-items cms-built">
               <div class="boxes-align">
                  <div class="large-box">
                     <i class="fa fa-4x fa-heart" aria-hidden="true"></i>
                     <h3>Award-winning customer service</h3>
                     <p>Award-winning, U.S. based support 24/7. If you need help we are here.</p>
                  </div>
               </div>
            </div>
         </div>
         <div class="col-md-6 cms-boxes-outer">
            <div class="cms-boxes-items cms-documentation">
               <div class="boxes-align">
                  <div class="large-box">
                     <i class="fa fa-4x fa-file-code-o">&nbsp;</i>
                     <h3>Documentation</h3>
                     <p>From connecting data sources to styling reports, we have everything you need to get the most value out of WebCorpCo.</p>
                  </div>
               </div>
            </div>
         </div>
      </div>
   </div>
</section>
```
## CSS

All necessary CSS is in responsive-tiles.css

## External Includes
```
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css">
<link rel="stylesheet" href="responsive-tiles.css">
<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script type="text/javascript" src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
```
