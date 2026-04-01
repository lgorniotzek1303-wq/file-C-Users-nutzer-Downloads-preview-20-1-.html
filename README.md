[preview (2).html](https://github.com/user-attachments/files/26405499/preview.2.html)[<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<title>Erfolg</title>
<style>
  body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background: #f0f0f0;
  }

  .checkmark {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    display: block;
    stroke-width: 5;
    stroke: white;
    stroke-miterlimit: 10;
    box-shadow: inset 0px 0px 0px #4CAF50;
    animation: fill .4s ease-in-out .4s forwards, scale .3s ease-in-out .9s both;
  }

  .checkmark-circle {
    stroke-dasharray: 166;
    stroke-dashoffset: 166;
    stroke-width: 5;
    stroke-miterlimit: 10;
    stroke: #4CAF50;
    fill: none;
    animation: stroke .6s cubic-bezier(0.65, 0, 0.45, 1) forwards;
  }

  .checkmark-check {
    transform-origin: 50% 50%;
    stroke-dasharray: 48;
    stroke-dashoffset: 48;
    animation: stroke .3s .6s cubic-bezier(0.65, 0, 0.45, 1) forwards;
  }

  @keyframes stroke {
    100% { stroke-dashoffset: 0; }
  }

  @keyframes scale {
    0%, 100% { transform: none; }
    50% { transform: scale(1.1); }
  }

  @keyframes fill {
    100% { box-shadow: inset 0px 0px 0px 50px #4CAF50; }
  }
</style>
</head>
<body>

<svg class="checkmark" viewBox="0 0 52 52">
  <circle class="checkmark-circle" cx="26" cy="26" r="25" />
  <path class="checkmark-check" fill="none" d="M14 27l7 7 16-16"/>
</svg>

</body>
</html>Uploading preview (2).html…]()

