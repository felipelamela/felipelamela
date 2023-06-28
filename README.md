# Hello There 🤙
```
html
<div id="typing-animation"></div>
<style>
  /* Estilize o contêiner da animação de digitação */
  #typing-animation {
    font-family: monospace;
    white-space: pre;
    overflow: hidden;
    border-right: .15em solid orange;
    margin: 0 auto;
    letter-spacing: .15em;
    animation:
      typing 3.5s steps(40, end),
      blink-caret .75s step-end infinite;
  }

  /* Animação de digitação */
  @keyframes typing {
    from { width: 0 }
    to { width: 100% }
  }

  /* Animação do cursor piscando */
  @keyframes blink-caret {
    from, to { border-color: transparent }
    50% { border-color: orange }
  }
</style>
<script>
  // Texto que será animado
  var text = "Digite seu texto aqui";

  // Função para animar o texto letra por letra
  function typeWriter(text, i, fnCallback) {
    // Verifica se o texto terminou de ser exibido
    if (i < (text.length)) {
      // Adiciona a próxima letra ao elemento HTML
      document.getElementById("typing-animation").innerHTML = text.substring(0, i + 1) + '<span aria-hidden="true"></span>';

      // Aguarda um intervalo antes de chamar a próxima letra
      setTimeout(function () {
        typeWriter(text, i + 1, fnCallback)
      }, 100);
    }
    // Verifica se o texto terminou de ser exibido e chama uma função de retorno, se fornecida
    else if (typeof fnCallback == "function") {
      setTimeout(fnCallback, 700);
    }
  }

  // Inicia a animação
  function StartAnimation() {
    if (typeof text === "string") {
      typeWriter(text, 0, function () {
        // Função de callback (opcional) para realizar ações após a animação ser concluída
      });
    }
  }

  // Inicia a animação automaticamente quando a página carrega
  document.addEventListener('DOMContentLoaded', StartAnimation);
</script>
```

<br>
<br>

# Tech 🖥 

### Language:
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
<br>
### Front-end:
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Chakra](https://img.shields.io/badge/chakra-%234ED1C5.svg?style=for-the-badge&logo=chakraui&logoColor=white)
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white)
![React Native](https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)

![Angular](https://img.shields.io/badge/angular-%23DD0031.svg?style=for-the-badge&logo=angular&logoColor=white)
<br>
### Back-end:
![NestJS](https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)

![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
<br>
### Test:
![cypress](https://img.shields.io/badge/-cypress-%23E5E5E5?style=for-the-badge&logo=cypress&logoColor=058a5e)
![Jest](https://img.shields.io/badge/-jest-%23C21325?style=for-the-badge&logo=jest&logoColor=white)
<br>
<br>

## Formações

### Completa:
- Curso de Formação em Front-end pela Alura.
- Curso de Formação em Python pela Alura.
- Curso de Front-end e UX/UI Design pela Origamid.
- Curso de TypeScript pela Origamid.
- Formação React Developer pela OracleONE.
<br>

### Cursando:
- Ciências da Computação pela Descomplica (incompleto, dois semestres)
- Engenharia da Computação pela Descomplica (Cursando).
- Formação Express pela Alura(Cursando).
- Formação NestJs pela Alura(Cursando).
- Formação NextJs pela Alura(Cursando).
- TypeORM pela Alura(Cursando).
- WebSocket pela Alura(Cursando).
<br>

### Aprovações:
- Aprovação para intensivo da Oracle Cloud Infra .
- Aprovação para intensivo da Oracle MySQL Server Oracle .
- Aprovação para intensivo da Oracle Data Science em OCI e Oracle Analytics
pela Oracle.
- Aprovação para o BootCamp DIO em Java - SpringBoot.
- Aprovação para o BootCamp DIO em Swift.
- Aprovação para o BootCamp DIO em Python.


