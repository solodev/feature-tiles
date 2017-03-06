# feature-tiles
Displaying the features of your product and/or services is important on your website. While some may use plain text with bullet points, others tend to lean more on the visual side of things to display their features. Using visuals to communicate your features to website visitors has become increasingly more popular to the point of being a best practice. 

Providing visual context to the features gives your website visitors a more immediate understanding of your overall offering. In this article, [Solodev](https://www.solodev.com/) will teach you how to add feature tiles containing [Font Awesome](http://fontawesome.io/) icons to your website. 

## Tutorials

For detailed instructions, view Solodev's [Adding Feature Tiles to your Website with Font Awesome](https://www.solodev.com/blog/web-design/adding-feature-tiles-to-your-website-with-font-awesome.stml) article.

## Demo

Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/o10e33xm/).

## HTML

The feature tiles contain the following basic HTML markup.

```
<section class="main-content">
  <div class="container">
    <h2>WebCorpCo does data better.</h2>
    <h3>These are just some of the features of WebCorpCo.</h3>
    <div class="row">
      <div class="col-md-4 col-sm-6">
        <div class="ct-featureBox">
          <div class="inner">
            <div class="image">
              <i class="fa fa-tachometer" aria-hidden="true"></i>
            </div>
            <h4>Dashboards</h4>
            <p>WebCorpCo. Meaninful data. Powerful insight.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6">
        <div class="ct-featureBox">
          <div class="inner">
            <div class="image">
              <i class="fa fa-pie-chart" aria-hidden="true"></i>
            </div>
            <h4>Semantic Analysis</h4>
            <p>Adding context to mountains of data.</p>
          </div>
        </div>
      </div>
      <div class="clearfix visible-sm"></div>
      <div class="col-md-4 col-sm-6">
        <div class="ct-featureBox">
          <div class="inner">
            <div class="image">
              <i class="fa fa-clock-o" aria-hidden="true"></i>
            </div>
            <h4>Realtime Data</h4>
            <p>No refreshing your browser. All data is analyzed in realtime.</p>
          </div>
        </div>
      </div>
      <div class="clearfix visible-md"></div>
      <div class="col-md-4 col-sm-6">
        <div class="ct-featureBox">
          <div class="inner">
            <div class="image">
              <i class="fa fa-database" aria-hidden="true"></i>
            </div>
            <h4>Data Driven</h4>
            <p>Pull data from any source, including your own databases.</p>
          </div>
        </div>
      </div>
      <div class="clearfix visible-sm"></div>
      <div class="col-md-4 col-sm-6">
        <div class="ct-featureBox">
          <div class="inner">
            <div class="image">
              <i class="fa fa-cube" aria-hidden="true"></i>
            </div>
            <h4>Machine Learning</h4>
            <p>More data, more time, more insight.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6">
        <div class="ct-featureBox">
          <div class="inner">
            <div class="image">
              <i class="fa fa-mobile" aria-hidden="true"></i>
            </div>
            <h4>Mobile App</h4>
            <p>Access WebCorpCo on any Internet connected device.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

```
## CSS

All required CSS is contained in feature-tiles.css

## External Includes

This tutorial includes the following third party resources.

```
<link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet">
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" rel="stylesheet">
<link href="feature-tiles.css" rel="stylesheet">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
```
