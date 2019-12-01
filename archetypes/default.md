---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
author : "Nour Araar"
categories : ["TECH"]
featuredpath : "main"
type : "post"
---






<form
  action="https://formspree.io/xbjlgzor"
  method="POST"
>
  <label>
    Your email:
    <input type="text" name="_replyto">
  </label>
  <label>
    Your message:
    <textarea name="message"></textarea>
  </label>
  <label>
    Your Info:
    <textarea name="Info"></textarea>
  </label>

  <!-- your other form fields go here -->

  <button type="submit">Send</button>
</form>