---
title: "Contact Me"
permalink: /contact/
author_profile = false
---
<form action="https://formspree.io/f/mwpwdgoq" method="POST">
  <div style="display: flex; gap: 20px;">
    <div style="flex: 1;">
      <label for="fname">First name *</label><br>
      <input type="text" id="fname" name="First Name" required style="width: 100%; border: none; border-bottom: 2px solid black; padding: 5px;">
    </div>
    <div style="flex: 1;">
      <label for="lname">Last name</label><br>
      <input type="text" id="lname" name="Last Name" style="width: 100%; border: none; border-bottom: 2px solid black; padding: 5px;">
    </div>
  </div>
  
  <div style="margin-top: 20px;">
    <label for="email">Email *</label><br>
    <input type="email" id="email" name="Email" required style="width: 100%; border: none; border-bottom: 2px solid black; padding: 5px;">
  </div>
  
  <div style="margin-top: 20px;">
    <label for="message">Write a message</label><br>
    <textarea id="message" name="Write something here!" rows="5" style="width: 100%; border: none; border-bottom: 2px solid black; padding: 5px;"></textarea>
  </div>
  
  <div style="margin-top: 30px;">
    <button type="submit" style="background-color: black; color: white; padding: 10px 25px; border-radius: 25px; border: none; cursor: pointer;">Submit</button>
  </div>
</form>