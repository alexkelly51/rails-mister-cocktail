# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

<!-- add this backk to the new page -->

<ul class="alerts">
  <% if @cocktail.errors %>
    <% @cocktail.errors.full_messages.each do |message| %>
    <li><%= message %></li>
    <% end %>
  <% end %>
</ul>


<%= simple_form_for(@cocktail) do |f| %>
<%= f.input :name %>
<%= f.submit %>
<% end %>





<body>
<nav class="navbar navbar-default navbar-fixed-top">
      <div class="container">
        <div class="navbar-header">
          <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
            <span class="sr-only">Toggle navigation</span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
          <a class="navbar-brand" href="#">Transparent to Solid Nav</a>
        </div>
        <div id="navbar" class="collapse navbar-collapse">
          <ul class="nav navbar-nav navbar-right">
            <li><a href="#">About</a></li>
            <li><a href="#">Link</a></li>
            <li><a href="#">Another Link</a></li>
          </ul>
        </div><!--/.nav-collapse -->
      </div>
    </nav>

<div class="image">
   <h1 class="heading">Main Heading</h1>
   <p><button class="btn btn-large">Big Button</button></p>
</div>
<div class="about">
   <h2>Main Description</h2>
   <p>Roll on the floor purring your whiskers off intrigued by the shower burrow under covers, and play time, rub face on everything, intently sniff hand, or pelt around the house and up and down stairs chasing phantoms. Attack feet. Damn that dog shake treat bag under the bed drink water out of the faucet for lick butt love to play with owner's hair tie. Swat at dog give attitude.</p>
</div>

</body>













<div class="navbar-wagon">
  <!-- Logo -->
  <a href="/" class="navbar-wagon-brand">
    <img src="images/logo.png" alt="logo">
  </a>

  <!-- Right Navigation -->
  <div class="navbar-wagon-right hidden-xs hidden-sm">

    <a href="" class="navbar-wagon-item navbar-wagon-link">Host</a>
    <a href="" class="navbar-wagon-item navbar-wagon-link">Trips</a>
    <a href="" class="navbar-wagon-item navbar-wagon-link">Messages</a>

    <!-- Profile picture with dropdown list -->
    <div class="navbar-wagon-item">
      <div class="dropdown">
        <img src="https://kitt.lewagon.com/placeholder/users/ssaunier" class="avatar dropdown-toggle" id="navbar-wagon-menu" data-toggle="dropdown">
        <ul class="dropdown-menu dropdown-menu-right navbar-wagon-dropdown-menu">
          <li><a href="#">Profile</a></li>
          <li><a href="#">Dashboard</a></li>
          <li><a href="#">Log Out</a></li>
        </ul>
      </div>
    </div>
  </div>

  <!-- Dropdown appearing on mobile only -->
  <div class="navbar-wagon-item hidden-md hidden-lg">
    <div class="dropdown">
      <i class="fa fa-bars dropdown-toggle" data-toggle="dropdown"></i>
      <ul class="dropdown-menu dropdown-menu-right navbar-wagon-dropdown-menu">
        <li><a href="#">Host</a></li>
        <li><a href="#">Trips</a></li>
        <li><a href="#">Messagese</a></li>
      </ul>
    </div>
  </div>
</div>

<div class="banner" style="background-image: linear-gradient(-225deg, rgba(0,101,168,0.6) 0%, rgba(0,36,61,0.6) 50%), url('https://kitt.lewagon.com/placeholder/cities/berlin');">
  <div class="banner-content">
    <h1>Le Wagon Berlin</h1>
    <p>Learn to code with us in Berlin</p>
    <a class="btn btn-primary btn-lg">Start now</a>
  </div>
</div>

<!--  -->
<h2>Add a new Cocktail</h2>
<h2>Add a new Cocktail</h2>
<h2>Add a new Cocktail</h2>
<h2>Add a new Cocktail</h2>
<h2>Add a new Cocktail</h2>
<h2>Add a new Cocktail</h2>
<h2>Add a new Cocktail</h2>
<h2>Add a new Cocktail</h2>
<h2>Add a new Cocktail</h2>
<h2>Add a new Cocktail</h2>
<h2>Add a new Cocktail</h2>
<h2>Add a new Cocktail</h2>
<h2>Add a new Cocktail</h2>
<h2>Add a new Cocktail</h2>
