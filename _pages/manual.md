---
layout: default
title: Manual del Juego
permalink: /manual/
---

<div class="manual-container">
  <h1 class="text-center">Manual de Abisal</h1>
  
  <!-- Índice Flotante -->
  <div class="manual-index">
    <h3>Índice</h3>
    <ul>
      <li><a href="#componentes">Componentes del juego</a></li>
      <li><a href="#consideraciones">Consideraciones</a></li>
      <li><a href="#preparacion">Preparación</a></li>
      <li><a href="#primera">Primera parte</a></li>
      <li><a href="#segunda">Segunda parte</a></li>
      <li><a href="#puntuacion">Puntuación</a></li>
      <li><a href="#final">Condiciones de victoria</a></li>
    </ul>
  </div>

  <!-- Sección Componentes -->
  <div class="manual-section">
    <h2 id="componentes">Componentes del Juego</h2>
    <div class="components-grid">
      <div class="component-card">
        <!--<img src="/assets/img/manual/componentes.jpg" alt="Componentes del juego"> -->
        <div class="component-list">
          <p>1 Tablero principal</p>
          <p>68 Cartas de interpretación</p>
          <p>20 Cartas de evento</p>
          <p>8 Cartas de rol oculto</p>
          <p>5 Contadores de presagio</p>
          <p>5 Contadores de diplomacia</p>
        </div>
      </div>
    </div>
  </div>

  <!-- Sección Consideraciones -->
  <div class="manual-section">
    <h2 id="consideraciones">Consideraciones Iniciales</h2>
    <div class="warning-box">
      <ul class="rules-list">
      <li>No se debe hacer comunicación verbal entre facciones.</li>
      <li>La facción que envía el regalo tampoco se debe comunicar verbalmente.</li>
      <li>Los únicos que pueden hablar son los integrantes de la facción que recibe el regalo.</li>
      </ul>
    </div>
  </div>

  <!-- Sección Preparación -->
  <div class="manual-section">
    <h2 id="preparacion">Preparación del Juego</h2>
    <ol class="setup-steps">
      <li>Colocar el tablero en el centro del área de juego</li>
      <li>Se ubican los mazos de cartas en el tablero. Y se separan los tokens.</li>
      <li>Se reparten las cartas de rol oculto. según el número de jugadores:</li>
      <li>2 jugadores: sin rol de belicista.</li>
      <li>3 o 4 jugadores: un rol de belicista.</li>
      <li>5 0 6 jugadores: dos roles de belicista.</li>
    </ol>
  </div>

  <!-- Primera Parte del Juego -->
  <div class="manual-section">
    <h2 id="primera">Primera parte de la ronda de juego</h2>

    <div class="phase-steps">
      <div class="step-card">
        <h3>Paso 1:</h3>
        <p>La facción inicial arrastra una carta de evento, la cual se puede tener una de dos intenciones, Paz o Guerra.</p>
        <div class="event-types">
          <div class="event-card peace">
            <h4>Evento de Paz</h4>
            <p>Si sale paz los participantes de dicha facción seleccionarán de las cartas en sus manos una cuya imagen pueda representar una ofrenda de paz, mientras que el jugador de rol oculto deberá infiltrar una carta con el objetivo de que se malinterprete el regalo.</p>
          </div>
          <div class="event-card war">
            <h4>Evento de Guerra</h4>
            <p>Esto significa que el paquete fue alterado por saboteadores. En este escenario los jugadores deben seleccionar cartas que se puedan interpretar como una advertencia, y el jugador de rol oculto deberá seleccionar una carta que confunda a la otra facción.</p>
          </div>
        </div>
      </div>

      <div class="step-card">
        <h3>Paso 2 - Selección Secreta</h3>
        <p>Una vez seleccionadas las cartas se deben poner mostrando el reverso. Tus compañeros no deben ver tu elección de carta, esto podría arruinar la experiencia de juego.</p>
        <div class="important-note">
          <p>¡Ningún compañero debe ver tu elección!</p>
        </div>
      </div>
      <div class="step-card">
        <h3>Paso 3</h3>
        <p>Es el turno de la otra facción de decidir si aceptan la ofrenda o no. Dependiendo de la interpretación que como grupo hagan de las cartas que se enviaron junto al posible regalo. En esta etapa se permite la comunicación con tus compañeros de facción.</p>
        <ul class="decision-list">
          <li>Aceptar la ofrenda</li>
          <li>Rechazar el paquete</li>
        </ul>
      </div>
      <div class="step-card">
        <h3>Paso 4</h3>
        <p>Una vez decidida la acción. Deberán tomar la carta y resolver según la carta. Luego, deben calcular las respectivas consecuencias.</p>
      </div>
    </div>
  </div>

  <!-- Segunda Parte del Juego -->
  <div class="manual-section">
    <h2 id="segunda">Segunda parte de la ronda de juego</h2>
    
    <div class="phase-steps">
      <div class="step-card">
        <h3>Paso 5</h3>
        <p> Ahora la facción que recibe o descarta la ofrenda, debe hacer los pasos descritos en la primera parte. Y al finalizar el 4to paso, se deben calcular las respectivas puntuaciones. De esta forma se completa una ronda de juego, donde ambas facciones envían un regalo y reciben uno de vuelta.</p>
      </div>

      <div class="step-card">
        <h3>Paso 4 - Ejecución y Consecuencias</h3>
        <p>En cualquier momento los jugadores pueden acusar a un integrante de ser el saboteador. Si esto ocurre esta persona debe mostrar su rol y se resuelve de la siguiente manera:</p>
        <ol class="consequence-steps">
          <li>Si el rol oculto era el de belicista. Este jugador es eliminado.</li>
          <li>Si su rol era pacifista se aumenta un token de presagio de guerra.</li>
        </ol>
      </div>
    </div>
  </div>

  <!-- Sistema de Puntuación -->
  <div class="manual-section">
    <h2 id="puntuacion">Puntuación</h2>
    
    <div class="scoring-grid">
      <div class="scenario-card">
        <h3>Aceptar Ofrenda</h3>
        <div class="outcome peace">
          <p>Si era de paz: +1 contador de Diplomacia</p>
        </div>
        <div class="outcome war">
          <p>Si era guerra: +1 Contador de Presagio de Guerra</p>
        </div>
      </div>

      <div class="scenario-card">
        <h3>Rechazar Ofrenda</h3>
        <div class="outcome peace">
          <p>Si era de paz: +1 Contador de Presagio</p>
        </div>
      </div>
    </div>
  </div>

  <!-- Final del Juego -->
  <div class="manual-section">
    <h2 id="final">Condiciones de Victoria</h2>
    
    <div class="victory-conditions">
      <div class="victory-card diplomats">
        <h3>Victoria Diplomática</h3>
        <p>5 intercambios pacíficos exitosos</p>
        <p>Equipo diplomático gana</p>
      </div>

      <div class="victory-card warmongers">
        <h3>Victoria Belicista</h3>
        <p>Contador de presagio alcanza 5</p>
        <p>Equipo belicista gana</p>
      </div>
    </div>
  </div>

  <!-- Nota Final -->
  <div class="fun-note">
    <h3>¡Recuerda!</h3>
    <p>¡El objetivo principal es divertirse!</p>
  </div>
</div>