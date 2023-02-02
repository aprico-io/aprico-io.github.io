---
title: Contact
type: contact
contact_entries:
  - heading: Email
    text: bill@aprico.io
---
We’d love to get in touch with you and show you a demo. We are actively conducting early stage user testing.

<h3 class="f4 b lh-title mb2">How can I get…?</h3>



I﻿f you want to learn more and stay connected, feel free to sign up to our mailing list.


{{< rawhtml >}}
<form name="contact" class="contact-form width-normal" action="/index.html/" method="POST" data-netlify="true">
    <input type="hidden" name="form-name" value="contact" />
    <!-- Text input-->
    <div class="form-group">
        <label class="col-md-4 control-label" for="Name"></label>
        <div class="col-md-4">
            <input id="contact-form-name" name="Name" type="text" placeholder="Name" class="form-control input-md" required="" autocomplete="off">
        </div>
    </div>
    <!-- Text input-->
    <div class="form-group">
        <label class="col-md-4 control-label" for="Email"></label>
        <div class="col-md-4">
            <input id="contact-form-email" name="Email" type="email" placeholder="Email Address" class="form-control input-md" required="" autocomplete="off">
        </div>
    </div>
    <!-- Text input-->
    <div class="form-group">
        <label class="col-md-4 control-label" for="Subject"></label>
        <div class="col-md-4">
            <input id="contact-form-subject" name="Subject" type="text" placeholder="Subject" class="form-control input-md" required="" autocomplete="off">
        </div>
    </div>
    <!-- Textarea -->
    <div class="form-group">
        <label class="col-md-4 control-label" for=""></label>
        <textarea class="form-control" id="contact-form-message" name="Message" placeholder="What's up?" rows="8"></textarea>
    </div>
    <!-- Button -->
    <div class="form-group">
        <button type="submit" value="Submit" id="Form-submit">Submit</button>
    </div>
</form>
{{< /rawhtml >}}
