---
title: "Reset Your Password"
date: 2018-06-11T13:16:35-04:00
draft: false
type: administrative
noindex: true
---

<div id="loader-cont"></div>

<form id="password-reset" data-parsley-validate>
  <p class="mb-40">Please enter a new secure password in the fields below.</p>

  <div class="field">
    <label class="label" for="new-password">New Password:</label>
    <div class="control">
      <input class="input is-medium" name="new-password" id="new-password" type="password" placeholder="Enter your new password..." required />
    </div>
  </div>

  <div class="field">
    <label class="label" for="confirm-password">Confirm Password:</label>
    <div class="control">
      <input class="input is-medium" name="confirm-password" id="confirm-password" type="password" placeholder="Confirm your new password..." required data-parsley-equalto="#new-password" />
    </div>
  </div>

  <div class="field is-grouped is-grouped-centered">
    <div class="control">
      <button class="button cta-lg is-large rounded accent-btn raised is-link password-reset-btn">Submit</button>
    </div>
  </div>
</form>
