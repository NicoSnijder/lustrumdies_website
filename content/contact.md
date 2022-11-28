---
title: Contact
description: Neem contact op met de DiesCie
date: 2022-11-26
---

## Contactformulier

<form name="contact" class="contact-form with normal" action="/thank-you/" method="POST" data-netlify="true">
   <input type="hidden" name="form-name" value="contact" />

   <div class="form-group">
      <label class="col-md-4 control-label" for="Name"></label>
      <div class="col-md-4">
          <input id="contact-form-name" name="Name" type="text" placeholder="Naam" class="form-control input-md" required="" autocomplete="off">
      </div>
   </div>

   <div class="form-group">
      <label class="col-md-4 control-label" for="Email"></label>
      <div class="col-md-4">
          <input id="contact-form-email" name="Email" type="email" placeholder="Mail" class="form-control input-md" required="" autocomplete="off">
      </div>
   </div>

   <div class="form-group">
      <label class="col-md-4 control-label" for="Subject"></label>
      <div class="col-md-4">
          <input id="contact-form-subject" name="Subject" type="text" placeholder="Onderwerp" class="form-control input-md" required="" autocomplete="off">
      </div>
   </div>

   <div class="form-group">
      <label class="col-md-4 control-label" for=""></label>
      <textarea class="form-control" id="contact-form-message" name="Message" type="text" placeholder="Bericht" rows="8"></textarea>
   </div>

   <div class="form-group">
      <button type="submit" value="Submit" id="Form-Submit">Submit</button>
   </div>
</form>
