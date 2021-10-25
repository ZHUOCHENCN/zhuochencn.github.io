# FIT3179-Visualization2

<html>
<head>
  <title>Visualization-Project2</title>
  <!-- Import Vega,Vega-Lite and vega-embed -->
  <script src="https://cdn.jsdelivr.net/npm/vega@5"></script>
  <script src="https://cdn.jsdelivr.net/npm/vega-lite@4"></script>
  <script src="https://cdn.jsdelivr.net/npm/vega-embed@6"></script>

  <!-- Import pure.css -->
  <link rel="stylesheet" href="https://unpkg.com/purecss@2.0.6/build/pure-min.css" integrity="sha384-Uu6IeWbM+gzNVXJcM9XV3SohHtmWE+3VGi496jvgX1jyvDTXfdK+rfZc8C1Aehk5" crossorigin="anonymous">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">


  <!-- Google font -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400&display=swap" rel="stylesheet">

  <!-- import CSS -->
  <link rel="stylesheet" href="style.css">

</head>



<body>


 <div class="page" >


  <div class="title">
    <div class="pure-u-1">
      <h1>Global Energy Consumption</h1>
    </div>
  </div>

  








  
  <div class="pure-a">


    <div class="pure-u-1">
      <h2 style="text-align:center; font-size: 25px;" >Energy Consumption Per Capita</h2>
    </div>


  </div>
 

  <div class="pure-g">

    <div class="pure-u-1-4">
      <br>
      <div class="text">
      </div> 
      <p style="font-size: 19px; font-weight: 400; color:rgb(94, 92, 92);">There is the energy consumption per capita map of <span style="font-weight: 600;">2019</span>, we can find some interesting points:</p>
      <br>
      <ul>
        <li>The value of <span style="font-weight: 400;">Per capita energy consumption</span> in <span style="font-weight: 400;"> developed countries</span> is <span style="font-weight: 400;">greater</span>.</li>
        <br>
        <li><span style="font-weight: 400;">High latitude countries</span> have a <span style="font-weight: 400;">higher</span> per capita energy consumption value.</li>
        <br>
        <li>The country with the <span style="font-weight: 400;">largest per capita energy consumption</span> is <span style="font-weight: 400;">Canada</span>.</li>
      </ul>
    </div>




    <div class="pure-u-3-4">
      <br>
      <h3>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2019 Energy Consumption per capita in each country</h3>
      <div id="vis1" class="vis-container"></div>
    </div>


  </div>
 














    <div class="pure-a">


      <div class="pure-u-1">
      <h2 style="text-align:center; font-size: 25px;">Energy consumption by source</h2>
      </div>


  </div>


  <div class="pure-g">
    <div class="pure-u-1-4">
      <div class="text">
          <br>
          <p style="font-size: 19px; font-weight: 400; color:rgb(94, 92, 92);">There is a line chart showing values of energy consumption by source from <span style="font-weight: 600;">1960</span> to <span style="font-weight: 600;">2015</span>. </p> 
          <br>
          <ul>
          <li><span style="font-weight: 400;">The most energy consumed</span> by human in recent <span style="font-weight: 400;">50</span> years is <span style="font-weight: 400;">Oil</span>.</li>
          <br>
          <li>The consumption of <span style="font-weight: 400;">Oil</span>, <span style="font-weight: 400;">Coal</span> and <span style="font-weight: 400;">Gas </span>are always the <span style="font-weight: 400;">top three</span>.</li>
          <br>
          <li>Only the use of <span style="font-weight: 400;">coal</span> has a <span style="font-weight: 400;">decreasing trend</span> in recent years.</li>
      </ul>
        <br>
      </div>
    </div>
    <div class="pure-u-3-4">
      <h3>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;World Energy Consumption by sources from 1965 to 2016</h3>
      <div id="vis2" class="vis-container"></div>
    </div>
  </div>













 <div class="pure-a">


  <div class="pure-u-1">
  <h2 style="text-align:center; font-size: 25px;">Source of Electricity Production</h2>
  </div>


</div>





  <div class="pure-g">
    <div class="pure-u-3-8">
      <div class="text">
          <br>
          <br>
          <p style="font-size: 19px; font-weight: 400; color:rgb(94, 92, 92);">There is a Sankey Diagram which shows the sources of electricity production in <span style="font-weight: 600;">five countries 2014</span>. </p> 
          <br>
          <ul>
          <li><span style="font-weight: 400;">Most of the electricity</span> in these five countries is generated from <span style="font-weight: 400;">Fossil Fuel</span>.</li>
          <br>
          <li><span style="font-weight: 400;">Australia</span> is the <span style="font-weight: 400;">only country</span> that <span style="font-weight: 400;">does not use Nuclear</span> to produce electricity.</li>
          <br>
          <li><span style="font-weight: 400;">Japan</span> is <span style="font-weight: 400;"></span>the most environmentally friendly of the five countries, with <span style="font-weight: 400;">39%</span> of electricity generated by <span style="font-weight: 400;">non Fossil Fuel</span>.</li>
          <br>
          <li><span style="font-weight: 400;">87%</span> of electricity in <span style="font-weight: 400;">Australia</span> generated from <span style="font-weight: 400;">Fossil Fuel</span>, which is <span style="font-weight: 400;">the highest proportion</span> among the five countries.</li>
          <br>
          <li><span style="font-weight: 400;">A quarter of Japan's electricity</span> is generated by <span style="font-weight: 400;">Nuclear</span>, which is the <span style="font-weight: 400;">highest proportion</span> among the five countries</li>
        </div>
      
    </div>
    <div class="pure-u-5-8">
      <h3>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2014 Sources of Electricity Production for 5 countries</h3>
      <div id="vis3" class="vis-container"></div>
    </div>
  </div>



  













 <div class="pure-a">


  <div class="pure-u-1">
  <h2 style="text-align:center; font-size: 25px;">Energy Consumption and GDP Per Capita</h2>
  </div>


</div>





  <div class="pure-g">
    <div class="pure-u-3-8">
      <br>
      <br>
      <br>
      <div class="text">
          <p style="font-size: 19px; font-weight: 400; color:rgb(94, 92, 92);">The Bubble Chart shows the GDP per capita and Energy Consumption per capita from <span style="font-weight: 600;">1990</span> to <span style="font-weight: 600;">2013</span>. </p> 
          <br>
          <ul>
          <li>For <span style="font-weight: 400;">most countries</span>: the <span style="font-weight: 400;">higher the per capita energy consumption</span>, the <span style="font-weight: 400;">higher the per capita GDP</span>.</li>
          <br>
          <li>From <span style="font-weight: 400;">1990</span> to <span style="font-weight: 400;">2013</span>, with the increase of per capita GDP, per capita energy consumption is also increasing.</li>
          <br>
          <li>From <span style="font-weight: 400;">2000</span> to <span style="font-weight: 400;">2013</span>, <span style="font-weight: 400;">South Korea</span> is the only country that the per capita GDP was increasing, but the <span style="font-weight: 400;">per capita energy consumption</span> was <span style="font-weight: 400;">decreasing</span>.</li>
      </div>
      
    </div>
    <div class="pure-u-5-8">
      <h3>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;GDP and Energy Consumption per capita for 7 countries from 1990 to 2013</h3>
      <div id="vis7" class="vis-container"></div>
    </div>
  </div>







  












    <div class="pure-a">


      <div class="pure-u-1">
      <h2 style="text-align:center; font-size: 25px;">Energy Consumption and Co2 Emission</h2>
      </div>
    
    
    </div>

    




  <div class="pure-g">
      <div class="pure-u-3-8">
        <br>
        <br>
        <div class="text">
          <br>
          <p style="font-size: 19px; font-weight: 400; color:rgb(94, 92, 92);">The Line Chart shows the Co2 Emissions from <span style="font-weight: 600;">1970</span> to <span style="font-weight: 600;">2015</span> in <span style="font-weight: 600;">six continent</span>. </p> 
          <br>
          <ul>
          <li>From <span style="font-weight: 400;">1970</span> to <span style="font-weight: 400;">2016</span>, the trend of <span style="font-weight: 400;">Co2 emissions</span> is <span style="font-weight: 400;">increasing</span>.</li>
          <br>
          <li>Carbon dioxide emissions in <span style="font-weight: 400;">North America</span>, <span style="font-weight: 400;">South America</span> and <span style="font-weight: 400;">Europe</span> have <span style="font-weight: 400;">decreased</span> in recent years.</li>
          <br>
          <li><span style="font-weight: 400;">Europe</span> was the <span style="font-weight: 400;">first continent</span> to start <span style="font-weight: 400;">reducing carbon emissions</span>, starting in <span style="font-weight: 400;">1990</span>.</li>

        </div>
      </div>
      <div class="pure-u-5-8">
        <h3>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Co2 Emission in six continent from 1970 to 2015</h3>
        <div id="vis5" class="vis-container"></div>
      </div>
  </div>










  



  </div> <!-- end page -->


<script type="text/javascript">
  var spec1 = "https://raw.githubusercontent.com/ZHUOCHENCN/FIT3179_A2/main/data/1_Map.vg.json";
  var spec2 = "https://raw.githubusercontent.com/ZHUOCHENCN/FIT3179_A2/main/data/2_lineChart.vg.json";
  var spec3 = "https://raw.githubusercontent.com/ZHUOCHENCN/FIT3179_A2/main/data/3_sankey.vg.json";
  var spec5 = "https://raw.githubusercontent.com/ZHUOCHENCN/FIT3179_A2/main/data/5_lineChart_co2.vg.json";
  var spec7 = "https://raw.githubusercontent.com/ZHUOCHENCN/FIT3179_A2/main/data/7_bubble.vg.json";
  


  vegaEmbed('#vis1', spec1, {"actions": false}).then(function(result) {
    // Access the Vega view instance (https://vega.github.io/vega/docs/api/view/) as result.view
  }).catch(console.error);
  
   vegaEmbed('#vis2', spec2, {"actions": false}).then(function(result) {
    // Access the Vega view instance (https://vega.github.io/vega/docs/api/view/) as result.view
  }).catch(console.error);

  vegaEmbed('#vis3', spec3, {"actions": false}).then(function(result) {
    // Access the Vega view instance (https://vega.github.io/vega/docs/api/view/) as result.view
  }).catch(console.error);

  vegaEmbed('#vis5', spec5, {"actions": false}).then(function(result) {
    // Access the Vega view instance (https://vega.github.io/vega/docs/api/view/) as result.view
  }).catch(console.error);

  vegaEmbed('#vis7', spec7, {"actions": false}).then(function(result) {
    // Access the Vega view instance (https://vega.github.io/vega/docs/api/view/) as result.view
  }).catch(console.error);
</script>




</body>
</html>
