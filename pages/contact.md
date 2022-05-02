---
layout: page
title: "Contact"
meta_title: "Contact"
# subheadline         : "Contact Form"
teaser: "Feel free to contact us"
permalink: "/contact/"

---
E-mail : [team@agarwoodessentialoils.com](mailto:team@agarwoodessentialoils.com){:target="_blank"}

WhatsApp : [+8613924271047](https://wa.me/8613924271047){:target="_blank"}

Phone : +8613924271047

Address : No.8 Liaohu Road, Liaobu Town, Dongguan City, Guangdong Province, China, 523400
<!-- google map 开始-->
<div>
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3673.2180497938157!2d113.89679431535372!3d22.979007923720292!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x34039d98c14dbc11%3A0xe95a6af9eb92e98a!2sLiaohu%20Road!5e0!3m2!1sen!2s!4v1651379913347!5m2!1sen!2s" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
div>
<div>
  <iframe width="100%" height="450px" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" src="[{{ site.google_map }}](https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3673.2180497938157!2d113.89679431535372!3d22.979007923720292!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x34039d98c14dbc11%3A0xe95a6af9eb92e98a!2sLiaohu%20Road!5e0!3m2!1sen!2s!4v1651379913347!5m2!1sen!2s)"></iframe>
  <br />
</div>

<!-- google map 结束-->

<br><br>
You can also fill in the following form and leave a message to us

<!-- modify this form HTML and place wherever you want your form -->
<form
  action="https://formspree.io/f/xknyqrvq"
  method="POST"
>
  <label>
    Your name:
    <input type="text" name="name">
  </label>
   <label>
    Your email:
    <input type="email" name="email">
  </label>
  <label>
    Your phone:
    <input type="tel" name="phone">
  </label>   
  <label>
    Your message:
    <textarea name="message"></textarea>
  </label>
  <!-- your other form fields go here -->
  <center><button type="submit">Send Message</button></center>
</form>

<!-- <div id="wufoo-zr01gft16qjm0z"> Fill out my <a href="https://weegier.wufoo.com/forms/zr01gft16qjm0z">online form</a>. </div> <script type="text/javascript"> var zr01gft16qjm0z; (function(d, t) { var s = d.createElement(t), options = { 'userName':'weegier', 'formHash':'zr01gft16qjm0z', 'autoResize':true, 'height':'863', 'async':true, 'host':'wufoo.com', 'header':'show', 'ssl':true }; s.src = ('https:' == d.location.protocol ?'https://':'http://') + 'secure.wufoo.com/scripts/embed/form.js'; s.onload = s.onreadystatechange = function() { var rs = this.readyState; if (rs) if (rs != 'complete') if (rs != 'loaded') return; try { zr01gft16qjm0z = new WufooForm(); zr01gft16qjm0z.initialize(options); zr01gft16qjm0z.display(); } catch (e) { } }; var scr = d.getElementsByTagName(t)[0], par = scr.parentNode; par.insertBefore(s, scr); })(document, 'script'); </script> -->


<!-- Contact -->
<!-- <section class="page-section" id="{{ site.data.sitetext[site.locale].contact.section | default: "contact" }}">
  <div class="container">
    <div class="row">
      <div class="col-lg-12 text-center">
        <h2 class="section-heading text-uppercase">
          {{ site.data.sitetext[site.locale].contact.title | markdownify | default: Contact Us }}</h2>
        <h3 class="section-subheading text-muted">{{ site.data.sitetext[site.locale].contact.text | default: "" }}</h3>
      </div>
    </div>
    <div class="row">
      <div class="col-lg-12">
        <form id="contactForm"
          action="https://formspree.io/f/xknyqrvq"
          novalidate="novalidate" method="POST">
          <!--name="sentMessage"-->
<!--           <div class="row">
            <div class="col-md-6">
              <div class="form-group">
                <input name="name" class="form-control" id="name" type="text"
                  placeholder="{{ site.data.sitetext[site.locale].contact.name | default: "Name*" }}"
                  required="required" data-validation-required-message="{{ site.data.sitetext[site.locale].contact.name-validation | default: "Please enter your name." }}">
                <p class="help-block text-danger"></p>
              </div>
              <div class="form-group">
                <input name="_replyto" class="form-control" id="email" type="email"
                  placeholder="{{ site.data.sitetext[site.locale].contact.email | default: "Email*" }}"
                  required="required" data-validation-required-message="{{ site.data.sitetext[site.locale].contact.email-validation | default: "Please enter your email address." }}">
                <p class="help-block text-danger"></p>
              </div>
              <div class="form-group">
                <input name="phone" class="form-control" id="phone" type="tel"
                  placeholder="{{ site.data.sitetext[site.locale].contact.phone | default: "Phone Number*" }}"
                  required="required" data-validation-required-message="{{ site.data.sitetext[site.locale].contact.phone-validation | default: "Please enter your phone number." }}">
                <p class="help-block text-danger"></p>
              </div>
            </div>
            <div class="col-md-6">
              <div class="form-group">
                <textarea name="message" class="form-control" id="message"
                  placeholder="{{ site.data.sitetext[site.locale].contact.message | default: "Message*" }}"
                  required="required" data-validation-required-message="{{ site.data.sitetext[site.locale].contact.message-validation | default: "Please enter a message." }}">
                </textarea>
                <p class="help-block text-danger"></p>
              </div>
            </div>
            <input type="hidden" name="_subject" id="email-subject"
              value="{{ site.data.sitetext[site.locale].contact.subject | default: "Contact Form Submission" }}">
            <div class="clearfix"></div>
            <div class="col-lg-12 text-center">
              <div id="success"></div>
              <button id="sendMessageButton" class="btn btn-primary btn-xl text-uppercase"
                type="submit">{{ site.data.sitetext[site.locale].contact.submit | default: "Send Message" }}</button>
            </div>
            <input type="text" name="_gotcha" style="display:none">
            <input type="hidden" name="_next" value="#" />
          </div>
        </form>
      </div>
    </div>
  </div>
</section>  

-->



<!-- End Contact -->

<!-- 
<form id="fs-frm" name="registration-form" accept-charset="utf-8" action="https://formspree.io/f/xknyqrvq" method="post">
  <fieldset id="fs-frm-inputs">
    <label for="full-name">Full Name</label>
    <input type="text" name="name" id="full-name" placeholder="First and Last" required="">
    <label for="email-address">Email Address</label>
    <input type="email" name="_replyto" id="email-address" placeholder="email@domain.tld" required="">
    <label for="street-address">Street Address</label>
    <input type="text" name="street" id="street-address" placeholder="Street" required="">
    <fieldset class="locale">
      <legend>Locale</legend>
      <input type="text" name="city" placeholder="City" required="">
      <select name="state" required="">
        <option value="" selected="" disabled="">State</option>
      	<option value="AL">Alabama</option>
      	<option value="AK">Alaska</option>
      	<option value="AZ">Arizona</option>
      	<option value="AR">Arkansas</option>
      	<option value="CA">California</option>
      	<option value="CO">Colorado</option>
      	<option value="CT">Connecticut</option>
      	<option value="DE">Delaware</option>
      	<option value="DC">District Of Columbia</option>
      	<option value="FL">Florida</option>
      	<option value="GA">Georgia</option>
      	<option value="HI">Hawaii</option>
      	<option value="ID">Idaho</option>
      	<option value="IL">Illinois</option>
      	<option value="IN">Indiana</option>
      	<option value="IA">Iowa</option>
      	<option value="KS">Kansas</option>
      	<option value="KY">Kentucky</option>
      	<option value="LA">Louisiana</option>
      	<option value="ME">Maine</option>
      	<option value="MD">Maryland</option>
      	<option value="MA">Massachusetts</option>
      	<option value="MI">Michigan</option>
      	<option value="MN">Minnesota</option>
      	<option value="MS">Mississippi</option>
      	<option value="MO">Missouri</option>
      	<option value="MT">Montana</option>
      	<option value="NE">Nebraska</option>
      	<option value="NV">Nevada</option>
      	<option value="NH">New Hampshire</option>
      	<option value="NJ">New Jersey</option>
      	<option value="NM">New Mexico</option>
      	<option value="NY">New York</option>
      	<option value="NC">North Carolina</option>
      	<option value="ND">North Dakota</option>
      	<option value="OH">Ohio</option>
      	<option value="OK">Oklahoma</option>
      	<option value="OR">Oregon</option>
      	<option value="PA">Pennsylvania</option>
      	<option value="RI">Rhode Island</option>
      	<option value="SC">South Carolina</option>
      	<option value="SD">South Dakota</option>
      	<option value="TN">Tennessee</option>
      	<option value="TX">Texas</option>
      	<option value="UT">Utah</option>
      	<option value="VT">Vermont</option>
      	<option value="VA">Virginia</option>
      	<option value="WA">Washington</option>
      	<option value="WV">West Virginia</option>
      	<option value="WI">Wisconsin</option>
      	<option value="WY">Wyoming</option>
      </select>
      <input type="text" name="postal-code" placeholder="12345" required="">
    </fieldset>
    <label for="note">Note</label>
    <textarea rows="2" name="note" id="note" placeholder="Include any additional information"></textarea>
    <input type="hidden" name="_subject" id="email-subject" value="Registration Form Submission">
  </fieldset>
  <input type="submit" value="Register">
</form> 
-->