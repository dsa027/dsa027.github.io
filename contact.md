---
layout: page
title: Contact
permalink: /contact/
---

Jekyll is a great tool to create static sites, but there’s no backend to send your data to.

<!-- However, you can use free SaaS as a backend for forms, such as [Formspree](https://formspree.io/) to handle form submissions. Sleek has a configured form using formspree ready for you. All you have to do is change the email in `_js/scripts.js` and `.config.yml`.  -->

<!-- Check the form below to see it in action! -->

<!-- ### Example Formspree contact form with validation and reCaptcha -->

<!-- Fill in the form or [email me](mailto:{{site.email}}) to discuss your next project. -->
[Email me](mailto:{{site.email}}) at {{site.email}}.

<form action="https://getsimpleform.com/messages?form_api_token=12876dad34ee4417e9959d98d75c2551" method="post">
  <!-- the redirect_to is optional, the form will redirect to the referrer on submission -->
  <input type='hidden' name='redirect_to' value='https://dsa027.github.io' />
  <input type='text' name='name' placeholder='Your Full Name' />
  <input type='email' name='email' placeholder='Your E-mail Address' />
  <textarea name='message' placeholder='Write your message ...'></textarea>
  <input type='submit' value='Send Message' />
</form>

<!-- {% include form.html %}  -->

<!-- {% include modal.html %} -->
