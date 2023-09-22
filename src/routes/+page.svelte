<script async defer src="https://static.cdn.prismic.io/prismic.js?new=true&repo=visite-kaartje-tribe">
        import { SliceZone } from '@prismicio/svelte';

import {components} from '$lib/slices'

export let data

</script>

<div id="cardContainer">
    <article id="animationFront" class="check" style="background-image: url({data.results[0].data.backgroundimage.url})">
      <header>
        <h1>Mokhtar Akle</h1>
        <p><em>Beginnende Front-end Developer</em></p>
        <button id="showCards">
          <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 91 91"
            id="Layer_1" version="1.1" xml:space="preserve">
            <g>
              <path class="st0" d="M8.4,31.9c4-0.8,7.9-1.6,12-1.9c2.6-0.1,5.6,0.5,8.1-0.2c2.4-0.7,3.2-3.7,1.5-5.6c-2.3-2.4-6.4-2.6-9.5-2.6   
              c-1,0-1.9,0-2.9,0.1c1.7-2,3.5-3.9,5.6-5.5c6.2-4.6,14.3-6.7,21.9-6.9c9.6-0.2,19.1,3.8,25.8,10.8c7,7.3,6.9,17.9,12.7,25.5   
              c0.4,0.5,1,0.4,1.2-0.2c3.6-9.1-0.9-21.7-6.8-28.9c-7-8.5-17.8-14.1-28.7-15c-8.7-0.7-18,1.2-25.8,5.1c-4.8,2.5-8.2,6-11.5,9.8   
              c0.2-3,0.4-6,0.6-9c0.3-5.3-7.9-5.2-8.2,0c-0.3,5.7-0.7,11.5-1,17.2C1.5,27.6,3.9,32.9,8.4,31.9z" />
              <path class="st0"
                d="M80.8,58.4c-3.6,0.8-7.3,1.5-11,1.9c-3.2,0.4-6.9-0.1-10,0.8c-2.4,0.7-3.3,3.8-1.5,5.6   
              c2.8,2.8,7.8,2.3,11.4,2.1c0.6,0,1.2-0.1,1.8-0.1c-1.7,2-3.5,3.9-5.6,5.5c-6.2,4.6-14.3,6.7-21.9,6.9c-9.6,0.2-19.1-3.7-25.8-10.7   
              c-7-7.3-6.9-17.8-12.8-25.5c-0.4-0.5-1-0.4-1.2,0.2c-3.6,9.1,0.9,21.7,6.9,28.9c7,8.5,17.8,14,28.7,14.9c8.7,0.7,18-1.2,25.8-5.2   
              c4.8-2.5,8.2-6.1,11.5-9.8c-0.2,3-0.4,6-0.5,9c-0.3,5.3,7.9,5.2,8.2,0c0.3-5.7,0.6-11.5,1-17.2C87.7,62.8,85.3,57.5,80.8,58.4z" />
            </g>
          </svg> <!-- source= https://www.svgrepo.com/svg/422364/arrow-repeat -->
        </button>
      </header>
    </article>

    <article id="frontBackside" class="check">
      <header>
        <h1>Achterkant</h1>
        <p><em>Beginnende Front-end Developer</em></p>
        <button id="showCards">
          <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 91 91"
            id="Layer_1" version="1.1" xml:space="preserve">
            <g>
              <path class="st0" d="M8.4,31.9c4-0.8,7.9-1.6,12-1.9c2.6-0.1,5.6,0.5,8.1-0.2c2.4-0.7,3.2-3.7,1.5-5.6c-2.3-2.4-6.4-2.6-9.5-2.6   
              c-1,0-1.9,0-2.9,0.1c1.7-2,3.5-3.9,5.6-5.5c6.2-4.6,14.3-6.7,21.9-6.9c9.6-0.2,19.1,3.8,25.8,10.8c7,7.3,6.9,17.9,12.7,25.5   
              c0.4,0.5,1,0.4,1.2-0.2c3.6-9.1-0.9-21.7-6.8-28.9c-7-8.5-17.8-14.1-28.7-15c-8.7-0.7-18,1.2-25.8,5.1c-4.8,2.5-8.2,6-11.5,9.8   
              c0.2-3,0.4-6,0.6-9c0.3-5.3-7.9-5.2-8.2,0c-0.3,5.7-0.7,11.5-1,17.2C1.5,27.6,3.9,32.9,8.4,31.9z" />
              <path class="st0"
                d="M80.8,58.4c-3.6,0.8-7.3,1.5-11,1.9c-3.2,0.4-6.9-0.1-10,0.8c-2.4,0.7-3.3,3.8-1.5,5.6   
              c2.8,2.8,7.8,2.3,11.4,2.1c0.6,0,1.2-0.1,1.8-0.1c-1.7,2-3.5,3.9-5.6,5.5c-6.2,4.6-14.3,6.7-21.9,6.9c-9.6,0.2-19.1-3.7-25.8-10.7   
              c-7-7.3-6.9-17.8-12.8-25.5c-0.4-0.5-1-0.4-1.2,0.2c-3.6,9.1,0.9,21.7,6.9,28.9c7,8.5,17.8,14,28.7,14.9c8.7,0.7,18-1.2,25.8-5.2   
              c4.8-2.5,8.2-6.1,11.5-9.8c-0.2,3-0.4,6-0.5,9c-0.3,5.3,7.9,5.2,8.2,0c0.3-5.7,0.6-11.5,1-17.2C87.7,62.8,85.3,57.5,80.8,58.4z" />
            </g>
          </svg> <!-- source= https://www.svgrepo.com/svg/422364/arrow-repeat -->
        </button>
      </header>
    </article>

    
    <div id="openButton">

    </div>
  </div>

  <style>
    * {
  box-sizing:border-box;
}


#cardContainer {
  display: flex;
  flex-flow: row nowrap;
  justify-content: center;
  position: relative;
}

header {
  display:flex;
  flex-direction:column;
  justify-content:center;
  align-items:center;
  justify-content:flex-end;
  
}

h1 {
  margin:2rem 0 1rem;
  color: rgba(0,239,255,1);
  font-size: 2.5em;
  font-style: italic;

}

header > p { 
  margin:0;
  color: white;
  padding:0 4em 0 4em;
}

#animationFront {
  height: 75vh;
  max-width: 25em;
  min-width:20em;
  display:flex;
  flex-direction:column;
  align-items:center;
  background-image: url(../assets/stock-background.jpg); /* Photo by Philippe Donn: https://www.pexels.com/photo/stars-1257860/ */
  background-position: center;
  background-size: cover;
  box-shadow:0 0 20px 20px rgba(0,0,0,.1);
  border-radius:1rem;
  transition:.25s;
  z-index: 4;
  
}

#frontBackside{
  height: 75vh;
  max-width: 25em;
  min-width:20em;
  display:flex;
  flex-direction:column;
  align-items:center;
  background-image: url(../assets/stock-background.jpg); /* Photo by Philippe Donn: https://www.pexels.com/photo/stars-1257860/ */
  background-position: center;
  background-size: cover;
  box-shadow:0 0 20px 20px rgba(0,0,0,.1);
  border-radius:1rem;
  transition: 2s;
  z-index: 3;
  position: absolute;
  color: red;
  opacity: 0;
}

button {
  border:none;
  position: absolute;
  right: 48.5%;
  top: 60%;
  width:2.5rem;
  height:2.5rem;
  transform: scale(4);
  background: none;
  border-radius:50%;
  padding:.25rem;
  transition:.25s;
}
button:hover svg{
  transform: rotate(-180deg);
  transition: .5s;
}

svg {
  fill: rgba(128, 116, 128, 0.671);
  position: absolute;
  opacity: 0;
  top: 18%;
  left: 18%;
  width: 2em;
  transition-delay: .25s;
  animation-name: buttonAppear, buttonGlow;
  animation-duration: 4s, 4s;
  animation-delay: 1.5s, 5.5s;
  animation-iteration-count: 1, infinite;
  animation-direction: normal, alternate;
  animation-timing-function: ease-in, ease-in-out;
  animation-fill-mode: forwards;
  
}
button svg:nth-of-type(2) {
  opacity:0;
  transition-delay: 0ms;
} 

#openButton{
  padding: 40vh 3em;
  position: absolute;
  z-index: 4;
  right: -20%;
}


@keyframes rotation {
  from{
    transform: rotate(0);

  }
  to{
    transform: rotate(-15deg) translateX(-2em);
  }
}

@keyframes rotationB {
  from{
    transform: rotate(-15deg) translateX(-2em);

  }
  to{
    transform: rotate(0deg) translateX(0);
  }
}

@keyframes flip {
  from{
  }
  to{
    transform: translateY(-2em);
  }
  
}

@keyframes flipB {
  from{
    transform: translateY(-2em);

  }
  to{
    transform: translateY(0);
  }
  
}

@keyframes rotater {
  from{

  }
  to{
    transform: rotate(15deg) translateX(2em) translateY(-3em);
  }
}

@keyframes rotaterB {
  from{
    transform: rotate(15deg) translateX(2em) translateY(-3em);

  }
  to{
    transform: rotate(0) translateX(0) translateY(0);

  }
}

@keyframes flipper {
  0%{
    transform: rotateY(0) scale(1);
  }
  25%{
    transform: rotateY(90deg) scale(1.1);
    filter: brightness(0.75);
  }
  50%{
    transform: rotateY(180deg) scale(1.25);
    filter: brightness(0.5);
  }
  75%{
    transform: rotateY(270deg);
    filter: brightness(0);
  }
  100%{
    transform: rotateY(360deg) scale(1);
    filter: brightness(0);
    opacity: 0;
  }
  
}


@keyframes flipperB {
  0%{
    transform: rotateY(360deg) scale(1);
    filter: brightness(0);
  }
  25%{
    transform: rotateY(270deg);
    filter: brightness(0);
  }
  50%{
    transform: rotateY(180deg) scale(1.25);
    filter: brightness(0.5);
  }
  75%{
    transform: rotateY(90deg) scale(1.1);
    filter: brightness(0.75);
  }
  100%{
    transform: rotateY(0) scale(1);
  }
  
}

@keyframes buttonAppear{
  0%{
    opacity: 0;
  }
  100%{
    opacity: 100%;
  }
}

@keyframes buttonGlow {
  0%{
    filter: drop-shadow(0px 0px 10px   rgba(255, 255, 255, 0))
    drop-shadow(0px 0px 20px rgb(255 0 255 / 0))
    drop-shadow(0px 0px 30px  rgb(0 255 255 / 0));
  }
  50%{
    filter: drop-shadow(0px 0px 10px   rgb(255 255 255 / 1))
    drop-shadow(0px 0px 20px rgb(255 0 255 / 1))
    drop-shadow(0px 0px 30px  rgb(0 255 255 / 1));
  }
  100%{
    filter: drop-shadow(0px 0px 10px rgb(255 255 255 / 0))
    drop-shadow(0px 0px 20px rgb(255 0 255 / 0))
    drop-shadow(0px 0px 30px  rgb(0 255 255 / 0));
  }
} 
  </style>