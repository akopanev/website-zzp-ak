---
layout: page
---

## Contact

For inquiries regarding my consulting services, please use the form below. I will get back to you as soon as possible.

<style>
    .form-group { margin-bottom: 1.2em; }
    .form-group label { display: block; margin-bottom: 0.4em; }
    .form-group input, .form-group textarea { width: 100%; padding: 10px; box-sizing: border-box; border: 1px solid #ccc; border-radius: 4px; }
    .form-submit { padding: 12px 24px; border: none; background-color: #333; color: white; cursor: pointer; font-size: 1em; border-radius: 4px; }
    .form-submit:hover { background-color: #555; }
</style>

<form action="https://formspree.io/f/mzzvpqre" method="POST">

    <div class="form-group">
        <label for="name">Your Name:</label>
        <input type="text" id="name" name="name" required>
    </div>

    <div class="form-group">
        <label for="email">Your Email:</label>
        <input type="email" id="email" name="email" required>
    </div>

    <div class="form-group">
        <label for="message">Your Message:</label>
        <textarea id="message" name="message" rows="6" required></textarea>
    </div>

    <button type="submit" class="form-submit">Send</button>

</form>