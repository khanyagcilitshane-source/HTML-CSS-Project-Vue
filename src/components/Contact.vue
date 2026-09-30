<template>
  <section id="contact" class="contact">

    <div class="container">

      <h2>Contact Me</h2>

      <p>
        Feel free to reach out if you have questions or opportunities.
      </p>

      <p>
        <strong>Phone:</strong> 0696470564
      </p>

      <p>
        <strong>Email:</strong>
        <a href="mailto:khanyagcilitshane@gmail.com">
          khanyagcilitshane@gmail.com
        </a>
      </p>

      <form
        action="https://formspree.io/f/mpqnvodd"
        method="POST"
      >

        <div>
          <label for="name">Your Name:</label>

          <input
            type="text"
            id="name"
            name="name"
            required
          />
        </div>

        <div>
          <label for="email">Your Email:</label>

          <input
            type="email"
            id="email"
            name="email"
            required
          />
        </div>

        <div>
          <label for="message">Your Message:</label>

          <textarea
            id="message"
            name="message"
            rows="6"
            required
          ></textarea>
        </div>

        <button type="submit">
          Send Message
        </button>

      </form>

    </div>

  </section>
</template>