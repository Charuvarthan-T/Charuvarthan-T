<div class="hero">
  <h1 class="vibrate-text">
    "Escape while it’s still a choice."
  </h1>
</div>

<style>
  body {
    margin: 0;
    background: #000;
    overflow: hidden;
    font-family: Arial, sans-serif;
  }

  .hero {
    background-color: #000;
    height: 100vh;

    display: flex;
    justify-content: center;
    align-items: center;
  }

  .vibrate-text {
    color: white;
    font-size: 32px;
    font-weight: 500;
    letter-spacing: 1px;

    animation:
      vibrate 0.08s infinite alternate,
      glow 2s infinite ease-in-out;

    text-shadow:
      0 0 5px rgba(255,255,255,0.4),
      0 0 10px rgba(255,255,255,0.2),
      0 0 20px rgba(255,255,255,0.1);
  }

  @keyframes vibrate {
    0% {
      transform: translate(0px, 0px);
    }

    25% {
      transform: translate(-2px, 1px);
    }

    50% {
      transform: translate(2px, -1px);
    }

    75% {
      transform: translate(-1px, -2px);
    }

    100% {
      transform: translate(2px, 2px);
    }
  }

  @keyframes glow {
    0% {
      opacity: 0.7;
    }

    50% {
      opacity: 1;
    }

    100% {
      opacity: 0.7;
    }
  }
</style>
