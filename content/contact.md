---
title: "Contact"
url: "/contact"
summary: "contact"
---

<form name="contact" method="POST" netlify data-netlify="true" action="/contact/success/">
  <p>
    <label>Your Name: <input type="text" name="name" required /></label>
  </p>
  <p>
    <label>Your Email: <input type="email" name="email" required /></label>
  </p>
  <p>
    <label>Subject: <input type="text" name="subject" required /></label>
  </p>
  <p>
    <label>Message: <textarea name="message" rows="4" required></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>

<style>
  form {
    max-width: 600px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    gap: 1rem;
  }
  label {
    display: flex;
    flex-direction: column;
    gap: 0.5rem;
    font-weight: bold;
  }
  input, textarea {
    padding: 0.5rem;
    border: 1px solid #ccc;
    border-radius: 4px;
    font-family: inherit;
    background: var(--entry); 
    color: var(--primary);
  }
  button {
    padding: 0.75rem 1.5rem;
    background-color: var(--primary);
    color: var(--theme);
    border: none;
    border-radius: 4px;
    cursor: pointer;
    font-weight: bold;
  }
  button:hover {
    opacity: 0.9;
  }
</style>
