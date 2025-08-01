---
title: "Request a Consultation"
url: "/contact/"
---

<p style="max-width: 600px; margin: 2rem auto; text-align: left; font-size: 1.1rem;">
  Use the form below to request a consultation for speaker measurements, buying advice, or setup help.
  <br><br>
  For general questions or community discussions, please visit my
  <a href="https://www.patreon.com/c/erinsaudiocorner" target="_blank">Patreon page</a>.
</p>



<style>
  form {
    max-width: 600;
    margin: 2rem auto;
    padding: 2rem;
    background-color: #fff;
    border-radius: 12px;
    box-shadow: 0 0 12px rgba(0, 0, 0, 0.08);
    font-family: sans-serif;
  }

  label {
    display: block;
    margin-bottom: 6px;
    font-weight: bold;
  }

  input, textarea {
    width: 100%;
    padding: 10px;
    font-size: 1rem;
    margin-bottom: 1rem;
    border: 1px solid #ccc;
    border-radius: 6px;
  }

  button {
    background-color: #2c3e50;
    color: #fff;
    padding: 10px 20px;
    font-size: 1rem;
    border: none;
    border-radius: 6px;
    cursor: pointer;
  }

  button:hover {
    background-color: #1a242f;
  }
</style>

<form action="https://formspree.io/f/xwpqqyda" method="POST">

  <input type="text" name="_honey" style="display:none">

  <label for="name">Name*</label>
  <input type="text" name="name" id="name" required>

  <label for="email">Email*</label>
  <input type="email" name="email" id="email" required>

  <label for="subject">Subject</label>
  <input type="text" name="subject" id="subject">

  <label for="message">Message*</label>
  <textarea name="message" id="message" rows="6" required></textarea>

  <button type="submit">Send Request</button>

  <input type="hidden" name="_next" value="https://www.erinsaudiocorner.com/thank-you/" />


</form>
