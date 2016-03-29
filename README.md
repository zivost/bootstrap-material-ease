<h1>Bootstrap-Material-Ease</h1>

<b>This repo is a Fork of `https://github.com/FezVrasta/bootstrap-material-design` repository for easier installation and usage. </b>

<h2>What is this?</h2>
I was facing issues in installing the `bootstrap-material` bower package and hence I decided to extract the necessary files and create a bower package for my own use and well you can use it too.

<h2>How to use this?</h2>
<h3>Prerequisites</h3>
<ol>
<li>Bootstrap CSS and JS</li>
<li>JQuery</li>
</ol>
<p>
You may install this theme using Bower or Manual:
</p>

Bower : `bower install bootstrap-material-ease` <br/>
Manual : Manually Download and Place dist folder appropriately<br/>


<p>Use the below code to initialize the Material Theme</p>
Add the necessary links to your `<head>` element for fonts and stylsheets:
```html
  <!-- Material Design fonts -->
  <link rel="stylesheet" type="text/css" href="//fonts.googleapis.com/css?family=Roboto:300,400,500,700">
  <link rel="stylesheet" type="text/css" href="//fonts.googleapis.com/icon?family=Material+Icons">

  <!-- Bootstrap -->
  <link rel="stylesheet" type="text/css" href="//maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">

  <!-- Bootstrap Material Design -->
  <link rel="stylesheet" type="text/css" href="/vendor/dist/css/bootstrap-material-design.css">
  <link rel="stylesheet" type="text/css" href="/vendor/dist/css/ripples.min.css">
```

Add the necessary links to the end of your `<body>` element for js:
```html
  <!-- JQuery -->
  <script src="//code.jquery.com/jquery-2.2.2.min.js"></script>
  <!-- Bootstrap JS -->
  <script src="//cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/3.3.6/js/bootstrap.js"></script>
  <!-- Material Design JS -->
  <script src="/vendor/bootstrap-material-ease/dist/js/material.js"></script>
  <script src="/vendor/bootstrap-material-ease/dist/js/ripples.js"></script>
  <!-- Bootstrap-Material-Ease Init JS -->
  <script>
      $(function () {
        $.material.init();
      });
  </script>
```

<h3>You are now good to go</h3>
<tt>try the following code</tt>
```html
<!-- Material Design fonts -->
<link rel="stylesheet" type="text/css" href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,700">
<link rel="stylesheet" type="text/css" href="https://fonts.googleapis.com/icon?family=Material+Icons">
<!-- Bootstrap -->
<link rel="stylesheet" type="text/css" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">
<!-- Bootstrap Material Design -->
<link rel="stylesheet" type="text/css" href="../bower-components/bootstrap-material-ease/dist/css/bootstrap-material-design.css">
<link rel="stylesheet" type="text/css" href="../bower-components/bootstrap-material-ease/dist/css/ripples.min.css">
<div class="navbar navbar-inverse">
   <div class="container-fluid">
      <div class="navbar-header">
         <button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-inverse-collapse">
         <span class="icon-bar"></span>
         <span class="icon-bar"></span>
         <span class="icon-bar"></span>
         </button>
         <a class="navbar-brand" href="javascript:void(0)">Bootstrap-Material-Ease</a>
      </div>
      <div class="navbar-collapse collapse navbar-inverse-collapse">
         <ul class="nav navbar-nav">
            <li><a href="javascript:void(0)">Dashboard</a></li>
            <li><a href="javascript:void(0)">Organisation</a></li>
            <li><a href="javascript:void(0)">Reviews</a></li>
            <li><a href="javascript:void(0)">Invite</a></li>
            <li class="active"><a href="javascript:void(0)">Groups</a></li>
            <li><a href="javascript:void(0)">Roles</a></li>
         </ul>
         <ul class="nav navbar-nav navbar-right">
            <li class="dropdown">
               <a href="bootstrap-elements.html" data-target="#" class="dropdown-toggle" data-toggle="dropdown">Settings
               <b class="caret"></b></a>
               <ul class="dropdown-menu">
                  <li><a href="javascript:void(0)">Settings</a></li>
                  <li><a href="javascript:void(0)"></a></li>
                  <li><a href="javascript:void(0)">Feedback</a></li>
                  <li class="divider"></li>
                  <li><a href="javascript:void(0)">Logout</a></li>
               </ul>
            </li>
         </ul>
      </div>
   </div>
</div>
<!-- JQuery -->
<script src="https://code.jquery.com/jquery-2.2.2.min.js"></script>
<!-- Bootstrap JS -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/3.3.6/js/bootstrap.js"></script>
<!-- Material Design JS -->
<script src="../bower-components/bootstrap-material-ease/dist/js/material.js"></script>
<script src="../bower-components/bootstrap-material-ease/dist/js/ripples.js"></script>
<!-- Bootstrap-Material-Ease Init JS -->
<script>
   $(function () {
     $.material.init();
   });
</script>
```

<b>For more codes visit the original developer at https://github.com/FezVrasta/bootstrap-material-design<b>
