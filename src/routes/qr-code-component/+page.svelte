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
  .container {
    background: hsl(212, 45%, 89%);
    display: grid;
    height: 100dvh;
    place-items: center;
    width: 100dvw;
  }

  .modal {
    background: white;
    border-radius: 20px;
    display: flex;
    flex-direction: column;
    max-width: 320px;
    padding: 16px;
    width: 100%;
  }

  .qr-code {
    border-radius: 10px;
  }

  .headline {
    font-weight: 700;
    text-align: center;
  }

  .paragraph {
    font-weight: 400;
    text-align: center;
  }
</style>
