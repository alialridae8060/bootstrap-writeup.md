# Bootstrap-Writeup.md

## 3/11/2025

## Text Below:How have I processed Bootstrap so far?

### I have processed bootstrap in the equivalency of approaching mastery at best.I will explian when we started with bootstrap with the bootstrap grid practice which we started with breakpoints,containers and container fluids,columns and rows and what I learned them fairly easily and hear are hat I know about them:
   ### <ul> 
### <li>  Breakpoints are basically digital auto adjusters that would auto adjust the foundation of the website in order to make it perfectly viewable on any and all devices being used.</li>
### <li>The difference between container and container fluids is that containers would have the max width change after each breakpoint while container fluid would have 100% width at all breakpoints.</li> 
### <li>Correct indentations are so important when doing bootstrap as they help make the output of the code more readable and reliable.</li>
### <li>Col-size-number is for the size of devices as for example with col-md-4 it works when a device is medium or larger than 768 pixels and their maximum width of the container would be 720 pixels which would divide it up into four equal columns that are medium or larger than 192 pixels and their maximum width is 180 pixels.</li>
### <li>The purpose for giving a div multiple col classes in example col-md-6 and col-xxl-3 is to program a code for responsive layout in the website that would allow the website to adapt to different screen and device sizes either like my iphone 15 or my school issued Chromebook or the smart boards in school.</li>
### <li>A container can be inside a container-fluid in website programming and coding.</li>
###  </ul>
### The first five of bootstrap were easy.The next are the gridpractices for the componets which were all hard to complete but I was able to get through non the less here are the code pieces of all the challenges.

### First the bootstrap-grid-practice:

### <ul>
### <li>  <h1>You hungry for what ?</h1>
       <div class="containerfluid">

            <div class="container">
             .container{
                background-color:darkblue;
                border: 1px;
             }
                <div class="rows">
                    <div class=col-xs-2 col-sm-4 col-md-6 col-lg-8 col-xl-10 col-xxl-12> Chicken</div>
                    <div class=col-xs-2 col-sm-4 col-md-6 col-lg-8 col-xl-10 col-xxl-12> Burgers</div>
                    <div class=col-xs-2 col-sm-4 col-md-6 col-lg-8 col-xl-10 col-xxl-12> Boneless wings</div>
                    <div class=col-xs-2 col-sm-4 col-md-6 col-lg-8 col-xl-10 col-xxl-12> Chicken pot pie</div>
                    <div class=col-xs-2 col-sm-4 col-md-6 col-lg-8 col-xl-10 col-xxl-12> Your wife's cooking</div>
                    </div class>
                </div class="container">
            </div class="containerfluid"> 
### </li>
### </ul>
### Next is the commponets practice:
### <ul>
### <li> First the Html.
           <title>An empty webpage </title> 
<h1>An empty webpage</h1>
    </head>
    <body>
        <!-- HTML -->
        <div class="topnav">
            <a class="active" href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
            <input type="text" placeholder="Search..">
          </div>

        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
        <script src="script.js"></script>
        <script>
                  <p>My big idea for future cooking is the Ulti oven;a fully capable AI oven programmed by humans that makes you a full course meal including cold drinks and cold desserts.
### </li>
### <li> Next the CSS.
body { background-color: #ff4b1e; }

h2 { border-bottom: 4px solid #ff711e; }

.container {
  color: #ff5e1e;
  background-color: #ef4511;
  padding: 20px;
}

button {
  background-color: #f08307;
  color: #ff2d1e;
  border: 4px solid #ff311e;
  padding: 10px;
}
:root {
  --red: #ff261e;
  --orange: hsl(25, 94%, 50%);
}

body { background-color: var(--orange); }

h2 { border-bottom: 6px solid var(--orange); }

.container {
  color: var(--orange);
  background-color: var(--orange);
  padding: 20px;
}

button {
  background-color: var(--red);
  color: var(--orange);
  border: 4px solid var(--red);
  padding: 10px;
}
:root {
  --red: #ed6d64;
  --orange: #f17f0d;
}

body { background-color: var(--red); }

h2 { border-bottom: 6px solid var(--orange); }

.container {
  color: var(--red);
  background-color: var(--orange);
  padding: 20px;
}

button {
  background-color: var(--orange);
  color: var(--red);
  border: 4px solid var(--red);
  padding: 10px;
}
$grid-breakpoints: (
  xs: 0,
  sm: 576px,
  md: 768px,
  lg: 992px,
  xl: 1200px,
  xxl: 1400px
);
// Base class
.callout {}

// Modifier classes
.callout-info {}
.callout-warning {}
.callout-danger {}
### </li>
### <li> Finally the script.js.
.topnav {
    overflow: hidden;
    background-color: #e9e9e9;
  }

  /* Style the links inside the navigation bar */
  .topnav a {
    float: left;
    display: block;
    color: black;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
    font-size: 17px;
  }

  /* Change the color of links on hover */
  .topnav a:hover {
    background-color: #ddd;
    color: black;
  }

  /* Style the "active" element to highlight the current page */
  .topnav a.active {
    background-color: #2196F3;
    color: white;
  }

  /* Style the search box inside the navigation bar */
  .topnav input[type=text] {
    float: right;
    padding: 6px;
    border: none;
    margin-top: 8px;
    margin-right: 16px;
    font-size: 17px;
  }

  /* When the screen is less than 600px wide, stack the links and the search field vertically instead of horizontally */
  @media screen and (max-width: 600px) {
    .topnav a, .topnav input[type=text] {
      float: none;
      display: block;
      text-align: left;
      width: 100%;
      margin: 0;
      padding: 14px;
    }
    .topnav input[type=text] {
      border: 1px solid #ccc;
    }
  }
  $grid-breakpoints: (
    xs: 0,
    sm: 576px,
    md: 768px,
    lg: 992px,
    xl: 1200px,
    xxl: 1400px
  );
  // Base class
  .callout {}

  // Modifier classes
  .callout-info {}
  .callout-warning {}
  .callout-danger {}
          </style>
### </li>
### </ul>
### These are examples on how I struggled but eventually perserved at bootstrap.
### Now for the bootstarp challenge.
### <ul>
### <li> First the tool-tips
        <button type="button" class="btn btn-secondary"
        data-bs-toggle="tooltip" data-bs-placement="top"
        data-bs-custom-class="This requires... "
        data-bs-title="Javascript">
  This requires...
</button>
### </li>
### <li> Next the list group.
 <ul class="list-group">
        <li class="list-group-item">HTML</li>
        <li class="list-group-item">CSS</li>
        <li class="list-group-item">Command Line</li>
        <li class="list-group-item">Github</li>
        <li class="list-group-item">Bootstrap</li>
      </ul>
      
### </li>
### <li> Finally the Navbar.
        <a class="nav-link" href="#advanced">Advanced</a>
        <a class="nav-link" href="#web">Web</a>
        <a class="nav-link" href="#design">Design</a>

### </li>
### </ul>
### Now finally all my notes from everything else.
### 2/26/2025:Bootstrap:Is a free front-end framework for faster and easier web development.It can also be imported like any other CSS file.This would include HTML and CSS designs.We will be using getbootstrap.com.
### https://getbootstrap.com/docs/5.3/getting-started/introduction/ 
### 2/27/2025:Notes from video: 
### 1.We can use the starter code in bootstrap.com to jumpstart our coding on the website and this code can always be found at tiny.cc/bootstrapbin.
### 2.Breakpoints are basically digital auto adjusters that would auto adjust the foundation of the website in order to make it perfectly viewable on any and all devices being used.
### 3.The difference between container and container fluids is that containers would have the max width change after each breakpoint while container fluid would have 100% width at all breakpoints. 
### 4.Correct indentations are so important when doing bootstrap as they help make the output of the code more readable and reliable.
### 5.I think col-size-number is for the size of devices as for example with col-md-4 it works when a device is medium or larger than 768 pixels and their maximum width of the container would be 720 pixels which would divide it up into four equal columns that are medium or larger than 192 pixels and their maximum width is 180 pixels.
### 6.The purpose for giving a div multiple col classes in example col-md-6 and col-xxl-3 is to program a code for responsive layout in the website that would allow the website to adapt to different screen and device sizes either like my iphone 15 or my school issued Chromebook or the smart boards in school.
### 7.A container can be inside a container-fluid in website programming and coding.
### 2/28/2025:

 <div class="container">
  <div class="row">
    <div class="col">
      Column
    </div>
    <div class="col">
      Column
    </div>
    <div class="col">
      Column
    </div>
  </div>
</div>

### 3/6/2025:Quiz notes.
###  1.Col-md-4 means the div will take up ⅓ on devices that are medium size and up.
###  2.Rows and columns must be inside of either a container or container fluid.
###  3.Any columns must always be inside a row.
###  4.Col-sm-6 and Col-lg-2 demonstrate 3 different layouts. 
### Notes from the second video.
### 1.The two keys of success to tinkering when loyoing bootstrap components is to be curious about things that would interest you and to be brave to make mistakes when tinkering with new tools.
### 2.This is an old IDE with a different way of previewing files. Remember to use the http-server command in your IDE.
### 3.The current Bootstrap version number on their website is not listed but the highest is 5.3 .
### 4.In your IDE, this “wrap lines” setting should already be enabled.
### 5.I saw Mr.Muller use a variety of tools such as div class and containers and he would use various tips that would help him reduce the amount of code needing to be written and I can use them for the same effect.
### 3/11/2025:Challenges when it comes to bootstrap is how much code is needed.Another would be the needed code for everything.
### This wriote ups show everything on how I processed bootstrap and everything Learnb't and did while learning about bootstrap.







         






 
