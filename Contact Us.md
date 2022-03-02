# Contact Us

<div class="w-full max-w-none">

<form name="contact" method="POST" netlify netlify-honeypot="bot-field"  data-netlify-recaptcha="true">
  <p class="hidden">
    <label>
      Don’t fill this out if you’re human: <input name="bot-field" />
    </label>
  </p>
  <p>
    <label class="flex flex-col">Your Name: <input type="text" name="name" /></label>   
  </p>
  <p>
    <label class="flex flex-col">Your Email: <input type="email" name="email" /></label>
  </p>
  <p>
    <label class="flex flex-col">Message: <textarea name="message"></textarea></label>
  </p>
  <p>
    <button class="border border-black px-4 " type="submit">Send</button>
  </p>
  <p><div class="m-8" data-netlify-recaptcha="true"></div></p>
</form>




</div>
