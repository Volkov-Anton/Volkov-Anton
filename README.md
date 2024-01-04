<div id="header" align="center">
  <img src="https://media.giphy.com/media/3knKct3fGqxhK/giphy.gif" width="800" />
  <h1 align="center" style="color: magenta;">¡Bienvenidos a mi perfil, Hackermen!</h1>
  <h3 align="center" id="typewriter">Swift Padawan. Apasionado de la ciencia ficción, los cómics y el cine de los 80. Friki de Pata Negra.</h3>
  <a href="https://twitter.com/Anton_VoIkov" target="_blank">
    <img alt="Seguir en X (anteriormente Twitter)" src="https://img.shields.io/twitter/follow/Anton_VoIkov?style=for-the-badge&logo=x&logoColor=white&color=magenta">
  </a>
</div>

<style>
  @keyframes typewriter {
    from { width: 0; }
    to { width: 100%; }
  }

  #typewriter {
    overflow: hidden;
    border-right: .15em solid magenta;
    white-space: nowrap;
    margin: 0 auto;
    letter-spacing: .15em;
    animation: typewriter 4s steps(40) 1s 1 normal both,
               blinkTextCursor 500ms steps(40) infinite normal;
  }

  @keyframes blinkTextCursor {
    from { border-right-color: magenta; }
    to { border-right-color: transparent; }
  }
</style>

<script>
  var i = 0;
  var txt = 'Swift Padawan. Apasionado de la ciencia ficción, los cómics y el cine de los 80. Friki de Pata Negra.';
  var speed = 50;
  var container = document.getElementById('typewriter');
  
  function typeWriter() {
    if (i < txt.length) {
      container.innerHTML += txt.charAt(i);
      i++;
      setTimeout(typeWriter, speed);
    }
  }

  document.addEventListener('DOMContentLoaded', (event) => {
    typeWriter();
  });
</script>


<hr> <!-- Línea divisoria -->

## 🌟 Mis Áreas de Interés en Desarrollo de Software 🌟

Hola, soy un "joven" padawan en el desarrollo de software con un fuerte interés tanto en el desarrollo de aplicaciones iOS como en la creación de videojuegos con Unreal Engine. Aquí os dejo mis áreas de interés y las tecnologías que me interesan:

### Desarrollo de Aplicaciones iOS
- **Swift** 🚀: Mi sueño es crear una aplicación látigo como la de "The Big Bang Theory", Temporada 5 - Episodio 19.
- **Objective-C** 🧩: Era esto o COBOL, yo qué sé.
- **Xcode** 🛠️: ¿Estás utilizando Xcode? Hago chas y aparezco a tu lado.
- **SwiftUI y UIKit** 🖼️: Wu shu, Chi Kung, Feng Shui... algún día tenía que ampliar mi vocabulario de chino mandarín, ¿no?
- **Core Data** 💾: Trabajando el core, ¡vuuuamos!

### Desarrollo de Videojuegos con Unreal Engine
- **Unreal Engine** 🎮: Fascinado por la creación de mundos y experiencias de juego ricas e inmersivas.
- **C++** 💻
- **Blueprint Visual Scripting** 📝

### Otros Intereses
- **Quarks, Materia oscura, Teoría de cuerdas, Relatividad general, Cosmología cuántica y otras movidas muy tochas** 🌌
- **Comunidad y Aprendizaje Continuo** 🌍📖: Activo en comunidades online, participando en proyectos colaborativos y manteniéndome actualizado con las últimas tendencias y mejores prácticas (ala, para que no digan que no me vendo bien).

---

Estoy emocionado de continuar mi viaje en el mundo del desarrollo de software, aprendiendo y creciendo en estas áreas. ¡Estoy abierto a colaborar en proyectos interesantes y compartir conocimientos con la comunidad!
