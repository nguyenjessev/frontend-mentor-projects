<div class="container">
  <main class="modal">
    <img
      src="/qr-code-component/image-qr-code.png"
      alt="QR code"
      class="qr-code"
    />

    <h2 class="headline">Improve your front-end skills by building projects</h2>

    <p class="paragraph">
      Scan the QR code to visit Frontend Mentor and take your coding skills to
      the next level
    </p>
  </main>
</div>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap');

  *,
  *::before,
  *::after {
    font-family: 'Outfit', sans-serif;
  }

  .container {
    background: hsl(212, 45%, 89%);
    display: grid;
    height: 100dvh;
    padding: 1rem;
    place-items: center;
    width: 100dvw;
  }

  .modal {
    background: white;
    border-radius: 20px;
    display: flex;
    flex-direction: column;
    max-width: 320px;
    min-width: 0; /* Needed because child img prevent parent from shrinking */
    padding: 16px;
    width: 100%;
  }

  .qr-code {
    border-radius: 10px;
  }

  .headline {
    color: hsl(218, 44%, 22%);
    font-weight: 700;
    margin: 1.5rem 0.5rem 0;
    text-align: center;
  }

  .paragraph {
    color: hsl(220, 15%, 55%);
    font-size: 15px;
    font-weight: 400;
    margin: 1rem 1rem;
    text-align: center;
  }
</style>
