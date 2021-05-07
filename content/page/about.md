---
title: About
description: Why and what.
date: '2021-04-29'
aliases:
  - about-me
  - contact
license: 
lastmod: '2021-04-29'
menu:
    main: 
        weight: -90
        pre: user
---

Hi, I am Alessandro Bolis and I created this site in order to experiment writing articles and share some of my thoughts about tech, videogames and science.

This is a static site generated with [Hugo](https://gohugo.io), hosted on [Github](https://github.com) and deployed through [Netlify](https://www.netlify.com). The theme i am using is a modified version of [this one](https://themes.gohugo.io/hugo-theme-stack/). 

If you wish to contact me for any reason, feel free to go ahead and fill the contact form below or text me via [telegram](https://t.me/edgarprime). 

<center>
<form name="contact" method="POST" data-netlify="true">
  <div class="form-group row">
    <div class="col-8">
      <div class="input-group">
        <div class="input-group-addon">
          <i class="fa fa-user"></i>
        </div>
        <input id="name" name="name" placeholder="Name" type="text" required="required" class="form-control">
      </div>
    </div>
  </div>
  <div class="form-group row">
    <div class="col-8">
      <div class="input-group">
        <div class="input-group-addon">
          <i class="fa fa-envelope"></i>
        </div>
        <input id="email" name="email" placeholder="E-mail Address" type="text" required="required" class="form-control">
      </div>
    </div>
  </div>
  <div class="form-group row">
    <div class="col-8">
      <textarea id="message" name="message" placeholder="Message" cols="30" rows="10" required="required" class="form-control"></textarea>
    </div>
  </div>
  <div class="field">
  <div data-netlify-recaptcha="true"></div>
  </div>
  <div class="form-group row">
    <div class="offset-4 col-8">
      <button name="submit" type="submit" class="btn btn-primary">Send</button>
    </div>
  </div>
</form>
</center>