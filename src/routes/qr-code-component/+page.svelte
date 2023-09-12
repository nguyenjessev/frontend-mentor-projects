<div class="container">
  <main class="modal">
    <img
      src="/qr-code-component/image-qr-code.png"
      alt="QR code"
      class="qr-code"
    />
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
</style>
