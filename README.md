<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <style>
    @keyframes wave {
      0% { transform: rotate(0deg); }
      15% { transform: rotate(14deg); }
      30% { transform: rotate(-8deg); }
      40% { transform: rotate(14deg); }
      50% { transform: rotate(-4deg); }
      60% { transform: rotate(10deg); }
      100% { transform: rotate(0deg); }
    }

    @keyframes snake {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
    }

    .wave-hand {
      display: inline-block;
      animation: wave 2s infinite;
      transform-origin: 70% 70%;
    }

    .icon-grid img {
      animation: snake 2s infinite ease-in-out;
      display: inline-block;
      margin: 5px;
    }

    .icon-grid img:nth-child(odd) {
      animation-delay: 0.2s;
    }

    .icon-grid img:nth-child(even) {
      animation-delay: 0.4s;
    }
  </style>
</head>
<body>

<h1>Hi <span class="wave-hand">👋</span>, I'm Kuberr</h1>
<p>A passionate frontend developer from Poland</p>
<p>
  ✩ <a href="https://nohello.net/en/" target="_blank">https://nohello.net/en/</a><br>
  ✩ <a href="https://www.paypal.com/paypalme/kuberrr" target="_blank">https://www.paypal.com/paypalme/kuberrr</a>
</p>

<h2>🚀 Languages and Tools I Use</h2>
<div class="icon-grid">
  <a target="_blank" href="#"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="42" height="42" /></a>
  <a target="_blank" href="#"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="42" height="42" /></a>
  <a target="_blank" href="#"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="42" height="42" /></a>
  <a target="_blank" href="#"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="42" height="42" /></a>
  <a target="_blank" href="#"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="42" height="42" /></a>
  <a target="_blank" href="#"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="42" height="42" /></a>
  <a target="_blank" href="#"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="csharp" width="42" height="42" /></a>
  <a target="_blank" href="#"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="42" height="42" /></a>
  <a target="_blank" href="#"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="42" height="42" /></a>
  <a target="_blank" href="#"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/backbonejs/backbonejs-original-wordmark.svg" alt="backbonejs" width="42" height="42" /></a>
  <a target="_blank" href="#"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="42" height="42" /></a>
  <a target="_blank" href="#"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="42" height="42" /></a>
  <a target="_blank" href="#"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="42" height="42" /></a>
  <a target="_blank" href="#"><img src="https://www.vectorlogo.zone/logos/google_cloud/google_cloud-icon.svg" alt="gcp" width="42" height="42" /></a>
  <a target="_blank" href="#"><img src="https://www.vectorlogo.zone/logos/microsoft_azure/microsoft_azure-icon.svg" alt="azure" width="42" height="42" /></a>
  <a target="_blank" href="#"><img src="https://www.vectorlogo.zone/logos/heroku/heroku-icon.svg" alt="heroku" width="42" height="42" /></a>
  <a target="_blank" href="#"><img src="https://www.vectorlogo.zone/logos/pocoo_flask/pocoo_flask-icon.svg" alt="flask" width="42" height="42" /></a>
  <a target="_blank" href="#"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/electron/electron-original.svg" alt="electron" width="42" height="42" /></a>
  <a target="_blank" href="#"><img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="42" height="42" /></a>
  <a target="_blank" href="#"><img src="https://download.blender.org/branding/community/blender_community_badge_white.svg" alt="blender" width="42" height="42" /></a>
  <a target="_blank" href="#"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/photoshop/photoshop-line.svg" alt="photoshop" width="42" height="42" /></a>
  <a target="_blank" href="#"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="42" height="42" /></a>
</div>

</body>
</html>
