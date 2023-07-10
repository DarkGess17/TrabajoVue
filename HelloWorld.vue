<template>

  <div id="app" class="container mt-1">
    <div class="row shadow-on-hover border">
      <div class="col-1">
        <div class="logo-container">
          <img src="../assets/empleo.png" alt="Logo de la empresa" class="logo">
        </div>
      </div>
      <div class="col-11">
        <div class="row">
          <div class="col-6">
            <div class="comp
            ny-infnombreCargo:'',o">
            
            </div>
            <h3 style="margin-top: 10px;">{{ nombreCargo }}</h3></div>
          <div class="col-6">
            <div class="company-info">
              <div class="row"> 
                <div class="col-4 text-center"> 
                  <p class="border rounded">{{ (requisitos1) }}</p>
                </div>
                <div class="col-4 text-center"> 
                  <p class="border rounded">{{ (requisitos2) }}</p>
                </div>
                <div class="col-4 text-center"> 
                  <p class="border rounded">{{ (requisitos3) }}</p>
                </div>

              </div>
              
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-2 ">
            <div class="info-item h-100 overflow-auto">
              <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="building" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-building b-icon bi">
                <g data-v-03976c49="">
                  <path fill-rule="evenodd" d="M14.763.075A.5.5 0 0 1 15 .5v15a.5.5 0 0 1-.5.5h-3a.5.5 0 0 1-.5-.5V14h-1v1.5a.5.5 0 0 1-.5.5h-9a.5.5 0 0 1-.5-.5V10a.5.5 0 0 1 .342-.474L6 7.64V4.5a.5.5 0 0 1 .276-.447l8-4a.5.5 0 0 1 .487.022zM6 8.694 1 10.36V15h5V8.694zM7 15h2v-1.5a.5.5 0 0 1 .5-.5h2a.5.5 0 0 1 .5.5V15h2V1.309l-7 3.5V15z"></path>
                  <path d="M2 11h1v1H2v-1zm2 0h1v1H4v-1zm-2 2h1v1H2v-1zm2 0h1v1H4v-1zm4-4h1v1H8V9zm2 0h1v1h-1V9zm-2 2h1v1H8v-1zm2 0h1v1h-1v-1zm2-2h1v1h-1V9zm0 2h1v1h-1v-1zM8 7h1v1H8V7zm2 0h1v1h-1V7zm2 0h1v1h-1V7zM8 5h1v1H8V5zm2 0h1v1h-1V5zm2 0h1v1h-1V5zm0-2h1v1h-1V3z"></path>
                </g>
              </svg>
              <p>{{ nombreEmpresa }}</p>
            </div>
          </div>
          <div class="col-2">
            <div class="info-item h-100 overflow-auto">
              <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="geo alt" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-geo-alt b-icon bi">
                <g data-v-03976c49="">
                  <path d="M12.166 8.94c-.524 1.062-1.234 2.12-1.96 3.07A31.493 31.493 0 0 1 8 14.58a31.481 31.481 0 0 1-2.206-2.57c-.726-.95-1.436-2.008-1.96-3.07C3.304 7.867 3 6.862 3 6a5 5 0 0 1 10 0c0 .862-.305 1.867-.834 2.94zM8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10z"></path>
                <path d="M8 8a2 2 0 1 1 0-4 2 2 0 0 1 0 4zm0 1a3 3 0 1 0 0-6 3 3 0 0 0 0 6z"></path>
              </g>
            </svg>
              <p>{{ ciudad }}</p>
            </div>
          </div>
          <div class="col-2">
            <div class="info-item h-100 overflow-auto">
              <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="cash" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-cash b-icon bi">
                <g data-v-03976c49="">
                  <path d="M8 10a2 2 0 1 0 0-4 2 2 0 0 0 0 4z"></path>
                  <path d="M0 4a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H1a1 1 0 0 1-1-1V4zm3 0a2 2 0 0 1-2 2v4a2 2 0 0 1 2 2h10a2 2 0 0 1 2-2V6a2 2 0 0 1-2-2H3z"></path>
                </g>
              </svg>
              <p>{{ salario }}</p>
            </div>
          </div>
          <div class="col-2">
            <div class="info-item h-100 overflow-auto">
              <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="people" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-people b-icon bi">
                <g data-v-03976c49="">
                  <path d="M15 14s1 0 1-1-1-4-5-4-5 3-5 4 1 1 1 1h8zm-7.978-1A.261.261 0 0 1 7 12.996c.001-.264.167-1.03.76-1.72C8.312 10.629 9.282 10 11 10c1.717 0 2.687.63 3.24 1.276.593.69.758 1.457.76 1.72l-.008.002a.274.274 0 0 1-.014.002H7.022zM11 7a2 2 0 1 0 0-4 2 2 0 0 0 0 4zm3-2a3 3 0 1 1-6 0 3 3 0 0 1 6 0zM6.936 9.28a5.88 5.88 0 0 0-1.23-.247A7.35 7.35 0 0 0 5 9c-4 0-5 3-5 4 0 .667.333 1 1 1h4.216A2.238 2.238 0 0 1 5 13c0-1.01.377-2.042 1.09-2.904.243-.294.526-.569.846-.816zM4.92 10A5.493 5.493 0 0 0 4 13H1c0-.26.164-1.03.76-1.724.545-.636 1.492-1.256 3.16-1.275zM1.5 5.5a3 3 0 1 1 6 0 3 3 0 0 1-6 0zm3-2a2 2 0 1 0 0 4 2 2 0 0 0 0-4z"></path>
              </g>
              </svg>
              <p>{{ vacantes }}</p>
            </div>
          </div>
          <div class="col-2">
            <div class="info-item h-100 overflow-auto">
              <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="calendar3" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-calendar3 b-icon bi"><g data-v-03976c49="">
                <path d="M14 0H2a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V2a2 2 0 0 0-2-2zM1 3.857C1 3.384 1.448 3 2 3h12c.552 0 1 .384 1 .857v10.286c0 .473-.448.857-1 .857H2c-.552 0-1-.384-1-.857V3.857z"></path>
                <path d="M6.5 7a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm-9 3a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm-9 3a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2z"></path>
              </g>
              </svg>
              <p>{{ tiempoPublicacion }}</p>
            </div>
          </div>
          <div class="col-2">
            <div class="info-item h-100 overflow-auto">
             <div class="container"> 
              <div data-v-03976c49="" class="text-truncate row ">
                <div data-v-03976c49="" role="button" title="Medicina prepagada" class="skill-tag custom-skill-tag text-truncate border border-dark text-dark p-1 col-2">
                  <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="heart" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-heart b-icon bi">
                    <g data-v-03976c49="">
                      <path d="m8 2.748-.717-.737C5.6.281 2.514.878 1.4 3.053c-.523 1.023-.641 2.5.314 4.385.92 1.815 2.834 3.989 6.286 6.357 3.452-2.368 5.365-4.542 6.286-6.357.955-1.886.838-3.362.314-4.385C13.486.878 10.4.28 8.717 2.01L8 2.748zM8 15C-7.333 4.868 3.279-3.04 7.824 1.143c.06.055.119.112.176.171a3.12 3.12 0 0 1 .176-.17C12.72-3.042 23.333 4.867 8 15z">

                      </path></g></svg></div>
                      <div data-v-03976c49="" role="button" title="Horario flexible" class="skill-tag custom-skill-tag text-truncate border border-dark text-dark p-1 col-2">
                        <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="watch" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-watch b-icon bi">
                          <g data-v-03976c49=""><path d="M8.5 5a.5.5 0 0 0-1 0v2.5H6a.5.5 0 0 0 0 1h2a.5.5 0 0 0 .5-.5V5z"></path>
                            <path d="M5.667 16C4.747 16 4 15.254 4 14.333v-1.86A5.985 5.985 0 0 1 2 8c0-1.777.772-3.374 2-4.472V1.667C4 .747 4.746 0 5.667 0h4.666C11.253 0 12 .746 12 1.667v1.86a5.99 5.99 0 0 1 1.918 3.48.502.502 0 0 1 .582.493v1a.5.5 0 0 1-.582.493A5.99 5.99 0 0 1 12 12.473v1.86c0 .92-.746 1.667-1.667 1.667H5.667zM13 8A5 5 0 1 0 3 8a5 5 0 0 0 10 0z">

                            </path></g></svg></div>
                            <div data-v-03976c49="" role="button" title="Trabajo remoto parcial" class="skill-tag custom-skill-tag text-truncate border border-dark text-dark p-1 col-2">
                              <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="geo alt" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-geo-alt b-icon bi">
                                <g data-v-03976c49="">
                                  <path d="M12.166 8.94c-.524 1.062-1.234 2.12-1.96 3.07A31.493 31.493 0 0 1 8 14.58a31.481 31.481 0 0 1-2.206-2.57c-.726-.95-1.436-2.008-1.96-3.07C3.304 7.867 3 6.862 3 6a5 5 0 0 1 10 0c0 .862-.305 1.867-.834 2.94zM8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10z"></path>
                                  <path d="M8 8a2 2 0 1 1 0-4 2 2 0 0 1 0 4zm0 1a3 3 0 1 0 0-6 3 3 0 0 0 0 6z">

                                  </path></g></svg></div>
                                  <div data-v-03976c49="" role="button" title="Celebración de días especiales" class="skill-tag custom-skill-tag text-truncate border border-dark text-dark p-1 col-2">
                                    <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="emoji sunglasses" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-emoji-sunglasses b-icon bi">
                                      <g data-v-03976c49="">
                                        <path d="M4.968 9.75a.5.5 0 1 0-.866.5A4.498 4.498 0 0 0 8 12.5a4.5 4.5 0 0 0 3.898-2.25.5.5 0 1 0-.866-.5A3.498 3.498 0 0 1 8 11.5a3.498 3.498 0 0 1-3.032-1.75zM7 5.116V5a1 1 0 0 0-1-1H3.28a1 1 0 0 0-.97 1.243l.311 1.242A2 2 0 0 0 4.561 8H5a2 2 0 0 0 1.994-1.839A2.99 2.99 0 0 1 8 6c.393 0 .74.064 1.006.161A2 2 0 0 0 11 8h.438a2 2 0 0 0 1.94-1.515l.311-1.242A1 1 0 0 0 12.72 4H10a1 1 0 0 0-1 1v.116A4.22 4.22 0 0 0 8 5c-.35 0-.69.04-1 .116z"></path>
                                        <path d="M16 8A8 8 0 1 1 0 8a8 8 0 0 1 16 0zm-1 0A7 7 0 1 0 1 8a7 7 0 0 0 14 0z">

                                        </path></g></svg></div>
                                        <div data-v-03976c49="" role="button" title="Ambiente de trabajo amigable" class="skill-tag custom-skill-tag text-truncate border border-dark text-dark p-1 col-2">
                                          <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="people" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-people b-icon bi">
                                            <g data-v-03976c49="">
                                              <path d="M15 14s1 0 1-1-1-4-5-4-5 3-5 4 1 1 1 1h8zm-7.978-1A.261.261 0 0 1 7 12.996c.001-.264.167-1.03.76-1.72C8.312 10.629 9.282 10 11 10c1.717 0 2.687.63 3.24 1.276.593.69.758 1.457.76 1.72l-.008.002a.274.274 0 0 1-.014.002H7.022zM11 7a2 2 0 1 0 0-4 2 2 0 0 0 0 4zm3-2a3 3 0 1 1-6 0 3 3 0 0 1 6 0zM6.936 9.28a5.88 5.88 0 0 0-1.23-.247A7.35 7.35 0 0 0 5 9c-4 0-5 3-5 4 0 .667.333 1 1 1h4.216A2.238 2.238 0 0 1 5 13c0-1.01.377-2.042 1.09-2.904.243-.294.526-.569.846-.816zM4.92 10A5.493 5.493 0 0 0 4 13H1c0-.26.164-1.03.76-1.724.545-.636 1.492-1.256 3.16-1.275zM1.5 5.5a3 3 0 1 1 6 0 3 3 0 0 1-6 0zm3-2a2 2 0 1 0 0 4 2 2 0 0 0 0-4z">

                                              </path></g></svg></div>
                                              <div data-v-03976c49="" role="button" title="Capacitaciones" class="skill-tag custom-skill-tag text-truncate border border-dark text-dark p-1 col-2">
                                                <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="clipboard check" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-clipboard-check b-icon bi">
                                                  <g data-v-03976c49="">
                                                    <path fill-rule="evenodd" d="M10.854 7.146a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708 0l-1.5-1.5a.5.5 0 1 1 .708-.708L7.5 9.793l2.646-2.647a.5.5 0 0 1 .708 0z"></path><path d="M4 1.5H3a2 2 0 0 0-2 2V14a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V3.5a2 2 0 0 0-2-2h-1v1h1a1 1 0 0 1 1 1V14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3.5a1 1 0 0 1 1-1h1v-1z"></path>
                                                    <path d="M9.5 1a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5h-3a.5.5 0 0 1-.5-.5v-1a.5.5 0 0 1 .5-.5h3zm-3-1A1.5 1.5 0 0 0 5 1.5v1A1.5 1.5 0 0 0 6.5 4h3A1.5 1.5 0 0 0 11 2.5v-1A1.5 1.5 0 0 0 9.5 0h-3z"></path>
            </g>
            </svg>
            </div>
            </div> 
            </div>  
            </div>
          </div>
        </div>
      </div>
    </div>

<!-- Parte 2 -->
    
  <div class="row shadow-on-hover border">
      <div class="col-1">
        <div class="logo-container">
          <img src="../assets/empleo.png" alt="Logo de la empresa" class="logo">
        </div>
      </div>
      <div class="col-11">
        <div class="row">
          <div class="col-6">
            <div class="comp
            ny-infnombreCargo:'',o">
            
            </div>
            <h3 style="margin-top: 10px;">{{ nombreCargo }}</h3></div>
          <div class="col-6">
            <div class="company-info">
              <div class="row"> 
                <div class="col-4 text-center"> 
                  <p class="border rounded">{{ (requisitos1) }}</p>
                </div>
                <div class="col-4 text-center"> 
                  <p class="border rounded">{{ (requisitos2) }}</p>
                </div>
                <div class="col-4 text-center"> 
                  <p class="border rounded">{{ (requisitos3) }}</p>
                </div>

              </div>
              
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-2 ">
            <div class="info-item h-100 overflow-auto">
              <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="building" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-building b-icon bi">
                <g data-v-03976c49="">
                  <path fill-rule="evenodd" d="M14.763.075A.5.5 0 0 1 15 .5v15a.5.5 0 0 1-.5.5h-3a.5.5 0 0 1-.5-.5V14h-1v1.5a.5.5 0 0 1-.5.5h-9a.5.5 0 0 1-.5-.5V10a.5.5 0 0 1 .342-.474L6 7.64V4.5a.5.5 0 0 1 .276-.447l8-4a.5.5 0 0 1 .487.022zM6 8.694 1 10.36V15h5V8.694zM7 15h2v-1.5a.5.5 0 0 1 .5-.5h2a.5.5 0 0 1 .5.5V15h2V1.309l-7 3.5V15z"></path>
                  <path d="M2 11h1v1H2v-1zm2 0h1v1H4v-1zm-2 2h1v1H2v-1zm2 0h1v1H4v-1zm4-4h1v1H8V9zm2 0h1v1h-1V9zm-2 2h1v1H8v-1zm2 0h1v1h-1v-1zm2-2h1v1h-1V9zm0 2h1v1h-1v-1zM8 7h1v1H8V7zm2 0h1v1h-1V7zm2 0h1v1h-1V7zM8 5h1v1H8V5zm2 0h1v1h-1V5zm2 0h1v1h-1V5zm0-2h1v1h-1V3z"></path>
                </g>
              </svg>
              <p>{{ nombreEmpresa }}</p>
            </div>
          </div>
          <div class="col-2">
            <div class="info-item h-100 overflow-auto">
              <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="geo alt" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-geo-alt b-icon bi">
                <g data-v-03976c49="">
                  <path d="M12.166 8.94c-.524 1.062-1.234 2.12-1.96 3.07A31.493 31.493 0 0 1 8 14.58a31.481 31.481 0 0 1-2.206-2.57c-.726-.95-1.436-2.008-1.96-3.07C3.304 7.867 3 6.862 3 6a5 5 0 0 1 10 0c0 .862-.305 1.867-.834 2.94zM8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10z"></path>
                <path d="M8 8a2 2 0 1 1 0-4 2 2 0 0 1 0 4zm0 1a3 3 0 1 0 0-6 3 3 0 0 0 0 6z"></path>
              </g>
            </svg>
              <p>{{ ciudad }}</p>
            </div>
          </div>
          <div class="col-2">
            <div class="info-item h-100 overflow-auto">
              <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="cash" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-cash b-icon bi">
                <g data-v-03976c49="">
                  <path d="M8 10a2 2 0 1 0 0-4 2 2 0 0 0 0 4z"></path>
                  <path d="M0 4a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H1a1 1 0 0 1-1-1V4zm3 0a2 2 0 0 1-2 2v4a2 2 0 0 1 2 2h10a2 2 0 0 1 2-2V6a2 2 0 0 1-2-2H3z"></path>
                </g>
              </svg>
              <p>{{ salario }}</p>
            </div>
          </div>
          <div class="col-2">
            <div class="info-item h-100 overflow-auto">
              <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="people" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-people b-icon bi">
                <g data-v-03976c49="">
                  <path d="M15 14s1 0 1-1-1-4-5-4-5 3-5 4 1 1 1 1h8zm-7.978-1A.261.261 0 0 1 7 12.996c.001-.264.167-1.03.76-1.72C8.312 10.629 9.282 10 11 10c1.717 0 2.687.63 3.24 1.276.593.69.758 1.457.76 1.72l-.008.002a.274.274 0 0 1-.014.002H7.022zM11 7a2 2 0 1 0 0-4 2 2 0 0 0 0 4zm3-2a3 3 0 1 1-6 0 3 3 0 0 1 6 0zM6.936 9.28a5.88 5.88 0 0 0-1.23-.247A7.35 7.35 0 0 0 5 9c-4 0-5 3-5 4 0 .667.333 1 1 1h4.216A2.238 2.238 0 0 1 5 13c0-1.01.377-2.042 1.09-2.904.243-.294.526-.569.846-.816zM4.92 10A5.493 5.493 0 0 0 4 13H1c0-.26.164-1.03.76-1.724.545-.636 1.492-1.256 3.16-1.275zM1.5 5.5a3 3 0 1 1 6 0 3 3 0 0 1-6 0zm3-2a2 2 0 1 0 0 4 2 2 0 0 0 0-4z"></path>
              </g>
              </svg>
              <p>{{ vacantes }}</p>
            </div>
          </div>
          <div class="col-2">
            <div class="info-item h-100 overflow-auto">
              <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="calendar3" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-calendar3 b-icon bi"><g data-v-03976c49="">
                <path d="M14 0H2a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V2a2 2 0 0 0-2-2zM1 3.857C1 3.384 1.448 3 2 3h12c.552 0 1 .384 1 .857v10.286c0 .473-.448.857-1 .857H2c-.552 0-1-.384-1-.857V3.857z"></path>
                <path d="M6.5 7a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm-9 3a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm-9 3a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2z"></path>
              </g>
              </svg>
              <p>{{ tiempoPublicacion }}</p>
            </div>
          </div>
          <div class="col-2">
            <div class="info-item h-100 overflow-auto">
             <div class="container"> 
              <div data-v-03976c49="" class="text-truncate row ">
                <div data-v-03976c49="" role="button" title="Medicina prepagada" class="skill-tag custom-skill-tag text-truncate border border-dark text-dark p-1 col-2">
                  <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="heart" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-heart b-icon bi">
                    <g data-v-03976c49="">
                      <path d="m8 2.748-.717-.737C5.6.281 2.514.878 1.4 3.053c-.523 1.023-.641 2.5.314 4.385.92 1.815 2.834 3.989 6.286 6.357 3.452-2.368 5.365-4.542 6.286-6.357.955-1.886.838-3.362.314-4.385C13.486.878 10.4.28 8.717 2.01L8 2.748zM8 15C-7.333 4.868 3.279-3.04 7.824 1.143c.06.055.119.112.176.171a3.12 3.12 0 0 1 .176-.17C12.72-3.042 23.333 4.867 8 15z">

                      </path></g></svg></div>
                      <div data-v-03976c49="" role="button" title="Horario flexible" class="skill-tag custom-skill-tag text-truncate border border-dark text-dark p-1 col-2">
                        <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="watch" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-watch b-icon bi">
                          <g data-v-03976c49=""><path d="M8.5 5a.5.5 0 0 0-1 0v2.5H6a.5.5 0 0 0 0 1h2a.5.5 0 0 0 .5-.5V5z"></path>
                            <path d="M5.667 16C4.747 16 4 15.254 4 14.333v-1.86A5.985 5.985 0 0 1 2 8c0-1.777.772-3.374 2-4.472V1.667C4 .747 4.746 0 5.667 0h4.666C11.253 0 12 .746 12 1.667v1.86a5.99 5.99 0 0 1 1.918 3.48.502.502 0 0 1 .582.493v1a.5.5 0 0 1-.582.493A5.99 5.99 0 0 1 12 12.473v1.86c0 .92-.746 1.667-1.667 1.667H5.667zM13 8A5 5 0 1 0 3 8a5 5 0 0 0 10 0z">

                            </path></g></svg></div>
                            <div data-v-03976c49="" role="button" title="Trabajo remoto parcial" class="skill-tag custom-skill-tag text-truncate border border-dark text-dark p-1 col-2">
                              <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="geo alt" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-geo-alt b-icon bi">
                                <g data-v-03976c49="">
                                  <path d="M12.166 8.94c-.524 1.062-1.234 2.12-1.96 3.07A31.493 31.493 0 0 1 8 14.58a31.481 31.481 0 0 1-2.206-2.57c-.726-.95-1.436-2.008-1.96-3.07C3.304 7.867 3 6.862 3 6a5 5 0 0 1 10 0c0 .862-.305 1.867-.834 2.94zM8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10z"></path>
                                  <path d="M8 8a2 2 0 1 1 0-4 2 2 0 0 1 0 4zm0 1a3 3 0 1 0 0-6 3 3 0 0 0 0 6z">

                                  </path></g></svg></div>
                                  <div data-v-03976c49="" role="button" title="Celebración de días especiales" class="skill-tag custom-skill-tag text-truncate border border-dark text-dark p-1 col-2">
                                    <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="emoji sunglasses" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-emoji-sunglasses b-icon bi">
                                      <g data-v-03976c49="">
                                        <path d="M4.968 9.75a.5.5 0 1 0-.866.5A4.498 4.498 0 0 0 8 12.5a4.5 4.5 0 0 0 3.898-2.25.5.5 0 1 0-.866-.5A3.498 3.498 0 0 1 8 11.5a3.498 3.498 0 0 1-3.032-1.75zM7 5.116V5a1 1 0 0 0-1-1H3.28a1 1 0 0 0-.97 1.243l.311 1.242A2 2 0 0 0 4.561 8H5a2 2 0 0 0 1.994-1.839A2.99 2.99 0 0 1 8 6c.393 0 .74.064 1.006.161A2 2 0 0 0 11 8h.438a2 2 0 0 0 1.94-1.515l.311-1.242A1 1 0 0 0 12.72 4H10a1 1 0 0 0-1 1v.116A4.22 4.22 0 0 0 8 5c-.35 0-.69.04-1 .116z"></path>
                                        <path d="M16 8A8 8 0 1 1 0 8a8 8 0 0 1 16 0zm-1 0A7 7 0 1 0 1 8a7 7 0 0 0 14 0z">

                                        </path></g></svg></div>
                                        <div data-v-03976c49="" role="button" title="Ambiente de trabajo amigable" class="skill-tag custom-skill-tag text-truncate border border-dark text-dark p-1 col-2">
                                          <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="people" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-people b-icon bi">
                                            <g data-v-03976c49="">
                                              <path d="M15 14s1 0 1-1-1-4-5-4-5 3-5 4 1 1 1 1h8zm-7.978-1A.261.261 0 0 1 7 12.996c.001-.264.167-1.03.76-1.72C8.312 10.629 9.282 10 11 10c1.717 0 2.687.63 3.24 1.276.593.69.758 1.457.76 1.72l-.008.002a.274.274 0 0 1-.014.002H7.022zM11 7a2 2 0 1 0 0-4 2 2 0 0 0 0 4zm3-2a3 3 0 1 1-6 0 3 3 0 0 1 6 0zM6.936 9.28a5.88 5.88 0 0 0-1.23-.247A7.35 7.35 0 0 0 5 9c-4 0-5 3-5 4 0 .667.333 1 1 1h4.216A2.238 2.238 0 0 1 5 13c0-1.01.377-2.042 1.09-2.904.243-.294.526-.569.846-.816zM4.92 10A5.493 5.493 0 0 0 4 13H1c0-.26.164-1.03.76-1.724.545-.636 1.492-1.256 3.16-1.275zM1.5 5.5a3 3 0 1 1 6 0 3 3 0 0 1-6 0zm3-2a2 2 0 1 0 0 4 2 2 0 0 0 0-4z">

                                              </path></g></svg></div>
                                              <div data-v-03976c49="" role="button" title="Capacitaciones" class="skill-tag custom-skill-tag text-truncate border border-dark text-dark p-1 col-2">
                                                <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="clipboard check" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-clipboard-check b-icon bi">
                                                  <g data-v-03976c49="">
                                                    <path fill-rule="evenodd" d="M10.854 7.146a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708 0l-1.5-1.5a.5.5 0 1 1 .708-.708L7.5 9.793l2.646-2.647a.5.5 0 0 1 .708 0z"></path><path d="M4 1.5H3a2 2 0 0 0-2 2V14a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V3.5a2 2 0 0 0-2-2h-1v1h1a1 1 0 0 1 1 1V14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3.5a1 1 0 0 1 1-1h1v-1z"></path>
                                                    <path d="M9.5 1a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5h-3a.5.5 0 0 1-.5-.5v-1a.5.5 0 0 1 .5-.5h3zm-3-1A1.5 1.5 0 0 0 5 1.5v1A1.5 1.5 0 0 0 6.5 4h3A1.5 1.5 0 0 0 11 2.5v-1A1.5 1.5 0 0 0 9.5 0h-3z"></path>
            </g>
            </svg>
            </div>
            </div> 
            </div>  
            </div>
          </div>
        </div>
      </div>
    </div>

<!-- Parte 3 -->

    <div class="row shadow-on-hover border">
      <div class="col-1">
        <div class="logo-container">
          <img src="../assets/empleo.png" alt="Logo de la empresa" class="logo">
        </div>
      </div>
      <div class="col-11">
        <div class="row">
          <div class="col-6">
            <div class="comp
            ny-infnombreCargo:'',o">
            
            </div>
            <h3 style="margin-top: 10px;">{{ nombreCargo }}</h3></div>
          <div class="col-6">
            <div class="company-info">
              <div class="row"> 
                <div class="col-4 text-center"> 
                  <p class="border rounded">{{ (requisitos1) }}</p>
                </div>
                <div class="col-4 text-center"> 
                  <p class="border rounded">{{ (requisitos2) }}</p>
                </div>
                <div class="col-4 text-center"> 
                  <p class="border rounded">{{ (requisitos3) }}</p>
                </div>

              </div>
              
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-2 ">
            <div class="info-item h-100 overflow-auto">
              <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="building" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-building b-icon bi">
                <g data-v-03976c49="">
                  <path fill-rule="evenodd" d="M14.763.075A.5.5 0 0 1 15 .5v15a.5.5 0 0 1-.5.5h-3a.5.5 0 0 1-.5-.5V14h-1v1.5a.5.5 0 0 1-.5.5h-9a.5.5 0 0 1-.5-.5V10a.5.5 0 0 1 .342-.474L6 7.64V4.5a.5.5 0 0 1 .276-.447l8-4a.5.5 0 0 1 .487.022zM6 8.694 1 10.36V15h5V8.694zM7 15h2v-1.5a.5.5 0 0 1 .5-.5h2a.5.5 0 0 1 .5.5V15h2V1.309l-7 3.5V15z"></path>
                  <path d="M2 11h1v1H2v-1zm2 0h1v1H4v-1zm-2 2h1v1H2v-1zm2 0h1v1H4v-1zm4-4h1v1H8V9zm2 0h1v1h-1V9zm-2 2h1v1H8v-1zm2 0h1v1h-1v-1zm2-2h1v1h-1V9zm0 2h1v1h-1v-1zM8 7h1v1H8V7zm2 0h1v1h-1V7zm2 0h1v1h-1V7zM8 5h1v1H8V5zm2 0h1v1h-1V5zm2 0h1v1h-1V5zm0-2h1v1h-1V3z"></path>
                </g>
              </svg>
              <p>{{ nombreEmpresa }}</p>
            </div>
          </div>
          <div class="col-2">
            <div class="info-item h-100 overflow-auto">
              <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="geo alt" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-geo-alt b-icon bi">
                <g data-v-03976c49="">
                  <path d="M12.166 8.94c-.524 1.062-1.234 2.12-1.96 3.07A31.493 31.493 0 0 1 8 14.58a31.481 31.481 0 0 1-2.206-2.57c-.726-.95-1.436-2.008-1.96-3.07C3.304 7.867 3 6.862 3 6a5 5 0 0 1 10 0c0 .862-.305 1.867-.834 2.94zM8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10z"></path>
                <path d="M8 8a2 2 0 1 1 0-4 2 2 0 0 1 0 4zm0 1a3 3 0 1 0 0-6 3 3 0 0 0 0 6z"></path>
              </g>
            </svg>
              <p>{{ ciudad }}</p>
            </div>
          </div>
          <div class="col-2">
            <div class="info-item h-100 overflow-auto">
              <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="cash" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-cash b-icon bi">
                <g data-v-03976c49="">
                  <path d="M8 10a2 2 0 1 0 0-4 2 2 0 0 0 0 4z"></path>
                  <path d="M0 4a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H1a1 1 0 0 1-1-1V4zm3 0a2 2 0 0 1-2 2v4a2 2 0 0 1 2 2h10a2 2 0 0 1 2-2V6a2 2 0 0 1-2-2H3z"></path>
                </g>
              </svg>
              <p>{{ salario }}</p>
            </div>
          </div>
          <div class="col-2">
            <div class="info-item h-100 overflow-auto">
              <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="people" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-people b-icon bi">
                <g data-v-03976c49="">
                  <path d="M15 14s1 0 1-1-1-4-5-4-5 3-5 4 1 1 1 1h8zm-7.978-1A.261.261 0 0 1 7 12.996c.001-.264.167-1.03.76-1.72C8.312 10.629 9.282 10 11 10c1.717 0 2.687.63 3.24 1.276.593.69.758 1.457.76 1.72l-.008.002a.274.274 0 0 1-.014.002H7.022zM11 7a2 2 0 1 0 0-4 2 2 0 0 0 0 4zm3-2a3 3 0 1 1-6 0 3 3 0 0 1 6 0zM6.936 9.28a5.88 5.88 0 0 0-1.23-.247A7.35 7.35 0 0 0 5 9c-4 0-5 3-5 4 0 .667.333 1 1 1h4.216A2.238 2.238 0 0 1 5 13c0-1.01.377-2.042 1.09-2.904.243-.294.526-.569.846-.816zM4.92 10A5.493 5.493 0 0 0 4 13H1c0-.26.164-1.03.76-1.724.545-.636 1.492-1.256 3.16-1.275zM1.5 5.5a3 3 0 1 1 6 0 3 3 0 0 1-6 0zm3-2a2 2 0 1 0 0 4 2 2 0 0 0 0-4z"></path>
              </g>
              </svg>
              <p>{{ vacantes }}</p>
            </div>
          </div>
          <div class="col-2">
            <div class="info-item h-100 overflow-auto">
              <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="calendar3" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-calendar3 b-icon bi"><g data-v-03976c49="">
                <path d="M14 0H2a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V2a2 2 0 0 0-2-2zM1 3.857C1 3.384 1.448 3 2 3h12c.552 0 1 .384 1 .857v10.286c0 .473-.448.857-1 .857H2c-.552 0-1-.384-1-.857V3.857z"></path>
                <path d="M6.5 7a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm-9 3a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm-9 3a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2z"></path>
              </g>
              </svg>
              <p>{{ tiempoPublicacion }}</p>
            </div>
          </div>
          <div class="col-2">
            <div class="info-item h-100 overflow-auto">
             <div class="container"> 
              <div data-v-03976c49="" class="text-truncate row ">
                <div data-v-03976c49="" role="button" title="Medicina prepagada" class="skill-tag custom-skill-tag text-truncate border border-dark text-dark p-1 col-2">
                  <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="heart" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-heart b-icon bi">
                    <g data-v-03976c49="">
                      <path d="m8 2.748-.717-.737C5.6.281 2.514.878 1.4 3.053c-.523 1.023-.641 2.5.314 4.385.92 1.815 2.834 3.989 6.286 6.357 3.452-2.368 5.365-4.542 6.286-6.357.955-1.886.838-3.362.314-4.385C13.486.878 10.4.28 8.717 2.01L8 2.748zM8 15C-7.333 4.868 3.279-3.04 7.824 1.143c.06.055.119.112.176.171a3.12 3.12 0 0 1 .176-.17C12.72-3.042 23.333 4.867 8 15z">

                      </path></g></svg></div>
                      <div data-v-03976c49="" role="button" title="Horario flexible" class="skill-tag custom-skill-tag text-truncate border border-dark text-dark p-1 col-2">
                        <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="watch" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-watch b-icon bi">
                          <g data-v-03976c49=""><path d="M8.5 5a.5.5 0 0 0-1 0v2.5H6a.5.5 0 0 0 0 1h2a.5.5 0 0 0 .5-.5V5z"></path>
                            <path d="M5.667 16C4.747 16 4 15.254 4 14.333v-1.86A5.985 5.985 0 0 1 2 8c0-1.777.772-3.374 2-4.472V1.667C4 .747 4.746 0 5.667 0h4.666C11.253 0 12 .746 12 1.667v1.86a5.99 5.99 0 0 1 1.918 3.48.502.502 0 0 1 .582.493v1a.5.5 0 0 1-.582.493A5.99 5.99 0 0 1 12 12.473v1.86c0 .92-.746 1.667-1.667 1.667H5.667zM13 8A5 5 0 1 0 3 8a5 5 0 0 0 10 0z">

                            </path></g></svg></div>
                            <div data-v-03976c49="" role="button" title="Trabajo remoto parcial" class="skill-tag custom-skill-tag text-truncate border border-dark text-dark p-1 col-2">
                              <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="geo alt" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-geo-alt b-icon bi">
                                <g data-v-03976c49="">
                                  <path d="M12.166 8.94c-.524 1.062-1.234 2.12-1.96 3.07A31.493 31.493 0 0 1 8 14.58a31.481 31.481 0 0 1-2.206-2.57c-.726-.95-1.436-2.008-1.96-3.07C3.304 7.867 3 6.862 3 6a5 5 0 0 1 10 0c0 .862-.305 1.867-.834 2.94zM8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10z"></path>
                                  <path d="M8 8a2 2 0 1 1 0-4 2 2 0 0 1 0 4zm0 1a3 3 0 1 0 0-6 3 3 0 0 0 0 6z">

                                  </path></g></svg></div>
                                  <div data-v-03976c49="" role="button" title="Celebración de días especiales" class="skill-tag custom-skill-tag text-truncate border border-dark text-dark p-1 col-2">
                                    <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="emoji sunglasses" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-emoji-sunglasses b-icon bi">
                                      <g data-v-03976c49="">
                                        <path d="M4.968 9.75a.5.5 0 1 0-.866.5A4.498 4.498 0 0 0 8 12.5a4.5 4.5 0 0 0 3.898-2.25.5.5 0 1 0-.866-.5A3.498 3.498 0 0 1 8 11.5a3.498 3.498 0 0 1-3.032-1.75zM7 5.116V5a1 1 0 0 0-1-1H3.28a1 1 0 0 0-.97 1.243l.311 1.242A2 2 0 0 0 4.561 8H5a2 2 0 0 0 1.994-1.839A2.99 2.99 0 0 1 8 6c.393 0 .74.064 1.006.161A2 2 0 0 0 11 8h.438a2 2 0 0 0 1.94-1.515l.311-1.242A1 1 0 0 0 12.72 4H10a1 1 0 0 0-1 1v.116A4.22 4.22 0 0 0 8 5c-.35 0-.69.04-1 .116z"></path>
                                        <path d="M16 8A8 8 0 1 1 0 8a8 8 0 0 1 16 0zm-1 0A7 7 0 1 0 1 8a7 7 0 0 0 14 0z">

                                        </path></g></svg></div>
                                        <div data-v-03976c49="" role="button" title="Ambiente de trabajo amigable" class="skill-tag custom-skill-tag text-truncate border border-dark text-dark p-1 col-2">
                                          <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="people" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-people b-icon bi">
                                            <g data-v-03976c49="">
                                              <path d="M15 14s1 0 1-1-1-4-5-4-5 3-5 4 1 1 1 1h8zm-7.978-1A.261.261 0 0 1 7 12.996c.001-.264.167-1.03.76-1.72C8.312 10.629 9.282 10 11 10c1.717 0 2.687.63 3.24 1.276.593.69.758 1.457.76 1.72l-.008.002a.274.274 0 0 1-.014.002H7.022zM11 7a2 2 0 1 0 0-4 2 2 0 0 0 0 4zm3-2a3 3 0 1 1-6 0 3 3 0 0 1 6 0zM6.936 9.28a5.88 5.88 0 0 0-1.23-.247A7.35 7.35 0 0 0 5 9c-4 0-5 3-5 4 0 .667.333 1 1 1h4.216A2.238 2.238 0 0 1 5 13c0-1.01.377-2.042 1.09-2.904.243-.294.526-.569.846-.816zM4.92 10A5.493 5.493 0 0 0 4 13H1c0-.26.164-1.03.76-1.724.545-.636 1.492-1.256 3.16-1.275zM1.5 5.5a3 3 0 1 1 6 0 3 3 0 0 1-6 0zm3-2a2 2 0 1 0 0 4 2 2 0 0 0 0-4z">

                                              </path></g></svg></div>
                                              <div data-v-03976c49="" role="button" title="Capacitaciones" class="skill-tag custom-skill-tag text-truncate border border-dark text-dark p-1 col-2">
                                                <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="clipboard check" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-clipboard-check b-icon bi">
                                                  <g data-v-03976c49="">
                                                    <path fill-rule="evenodd" d="M10.854 7.146a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708 0l-1.5-1.5a.5.5 0 1 1 .708-.708L7.5 9.793l2.646-2.647a.5.5 0 0 1 .708 0z"></path><path d="M4 1.5H3a2 2 0 0 0-2 2V14a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V3.5a2 2 0 0 0-2-2h-1v1h1a1 1 0 0 1 1 1V14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3.5a1 1 0 0 1 1-1h1v-1z"></path>
                                                    <path d="M9.5 1a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5h-3a.5.5 0 0 1-.5-.5v-1a.5.5 0 0 1 .5-.5h3zm-3-1A1.5 1.5 0 0 0 5 1.5v1A1.5 1.5 0 0 0 6.5 4h3A1.5 1.5 0 0 0 11 2.5v-1A1.5 1.5 0 0 0 9.5 0h-3z"></path>
            </g>
            </svg>
            </div>
            </div> 
            </div>  
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Parte 4 -->

    <div class="row shadow-on-hover border">
      <div class="col-1">
        <div class="logo-container">
          <img src="../assets/empleo.png" alt="Logo de la empresa" class="logo">
        </div>
      </div>
      <div class="col-11">
        <div class="row">
          <div class="col-6">
            <div class="comp
            ny-infnombreCargo:'',o">
            
            </div>
            <h3 style="margin-top: 10px;">{{ nombreCargo }}</h3></div>
          <div class="col-6">
            <div class="company-info">
              <div class="row"> 
                <div class="col-4 text-center"> 
                  <p class="border rounded">{{ (requisitos1) }}</p>
                </div>
                <div class="col-4 text-center"> 
                  <p class="border rounded">{{ (requisitos2) }}</p>
                </div>
                <div class="col-4 text-center"> 
                  <p class="border rounded">{{ (requisitos3) }}</p>
                </div>

              </div>
              
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-2 ">
            <div class="info-item h-100 overflow-auto">
              <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="building" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-building b-icon bi">
                <g data-v-03976c49="">
                  <path fill-rule="evenodd" d="M14.763.075A.5.5 0 0 1 15 .5v15a.5.5 0 0 1-.5.5h-3a.5.5 0 0 1-.5-.5V14h-1v1.5a.5.5 0 0 1-.5.5h-9a.5.5 0 0 1-.5-.5V10a.5.5 0 0 1 .342-.474L6 7.64V4.5a.5.5 0 0 1 .276-.447l8-4a.5.5 0 0 1 .487.022zM6 8.694 1 10.36V15h5V8.694zM7 15h2v-1.5a.5.5 0 0 1 .5-.5h2a.5.5 0 0 1 .5.5V15h2V1.309l-7 3.5V15z"></path>
                  <path d="M2 11h1v1H2v-1zm2 0h1v1H4v-1zm-2 2h1v1H2v-1zm2 0h1v1H4v-1zm4-4h1v1H8V9zm2 0h1v1h-1V9zm-2 2h1v1H8v-1zm2 0h1v1h-1v-1zm2-2h1v1h-1V9zm0 2h1v1h-1v-1zM8 7h1v1H8V7zm2 0h1v1h-1V7zm2 0h1v1h-1V7zM8 5h1v1H8V5zm2 0h1v1h-1V5zm2 0h1v1h-1V5zm0-2h1v1h-1V3z"></path>
                </g>
              </svg>
              <p>{{ nombreEmpresa }}</p>
            </div>
          </div>
          <div class="col-2">
            <div class="info-item h-100 overflow-auto">
              <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="geo alt" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-geo-alt b-icon bi">
                <g data-v-03976c49="">
                  <path d="M12.166 8.94c-.524 1.062-1.234 2.12-1.96 3.07A31.493 31.493 0 0 1 8 14.58a31.481 31.481 0 0 1-2.206-2.57c-.726-.95-1.436-2.008-1.96-3.07C3.304 7.867 3 6.862 3 6a5 5 0 0 1 10 0c0 .862-.305 1.867-.834 2.94zM8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10z"></path>
                <path d="M8 8a2 2 0 1 1 0-4 2 2 0 0 1 0 4zm0 1a3 3 0 1 0 0-6 3 3 0 0 0 0 6z"></path>
              </g>
            </svg>
              <p>{{ ciudad }}</p>
            </div>
          </div>
          <div class="col-2">
            <div class="info-item h-100 overflow-auto">
              <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="cash" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-cash b-icon bi">
                <g data-v-03976c49="">
                  <path d="M8 10a2 2 0 1 0 0-4 2 2 0 0 0 0 4z"></path>
                  <path d="M0 4a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H1a1 1 0 0 1-1-1V4zm3 0a2 2 0 0 1-2 2v4a2 2 0 0 1 2 2h10a2 2 0 0 1 2-2V6a2 2 0 0 1-2-2H3z"></path>
                </g>
              </svg>
              <p>{{ salario }}</p>
            </div>
          </div>
          <div class="col-2">
            <div class="info-item h-100 overflow-auto">
              <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="people" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-people b-icon bi">
                <g data-v-03976c49="">
                  <path d="M15 14s1 0 1-1-1-4-5-4-5 3-5 4 1 1 1 1h8zm-7.978-1A.261.261 0 0 1 7 12.996c.001-.264.167-1.03.76-1.72C8.312 10.629 9.282 10 11 10c1.717 0 2.687.63 3.24 1.276.593.69.758 1.457.76 1.72l-.008.002a.274.274 0 0 1-.014.002H7.022zM11 7a2 2 0 1 0 0-4 2 2 0 0 0 0 4zm3-2a3 3 0 1 1-6 0 3 3 0 0 1 6 0zM6.936 9.28a5.88 5.88 0 0 0-1.23-.247A7.35 7.35 0 0 0 5 9c-4 0-5 3-5 4 0 .667.333 1 1 1h4.216A2.238 2.238 0 0 1 5 13c0-1.01.377-2.042 1.09-2.904.243-.294.526-.569.846-.816zM4.92 10A5.493 5.493 0 0 0 4 13H1c0-.26.164-1.03.76-1.724.545-.636 1.492-1.256 3.16-1.275zM1.5 5.5a3 3 0 1 1 6 0 3 3 0 0 1-6 0zm3-2a2 2 0 1 0 0 4 2 2 0 0 0 0-4z"></path>
              </g>
              </svg>
              <p>{{ vacantes }}</p>
            </div>
          </div>
          <div class="col-2">
            <div class="info-item h-100 overflow-auto">
              <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="calendar3" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-calendar3 b-icon bi"><g data-v-03976c49="">
                <path d="M14 0H2a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V2a2 2 0 0 0-2-2zM1 3.857C1 3.384 1.448 3 2 3h12c.552 0 1 .384 1 .857v10.286c0 .473-.448.857-1 .857H2c-.552 0-1-.384-1-.857V3.857z"></path>
                <path d="M6.5 7a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm-9 3a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm-9 3a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2z"></path>
              </g>
              </svg>
              <p>{{ tiempoPublicacion }}</p>
            </div>
          </div>
          <div class="col-2">
            <div class="info-item h-100 overflow-auto">
             <div class="container"> 
              <div data-v-03976c49="" class="text-truncate row ">
                <div data-v-03976c49="" role="button" title="Medicina prepagada" class="skill-tag custom-skill-tag text-truncate border border-dark text-dark p-1 col-2">
                  <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="heart" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-heart b-icon bi">
                    <g data-v-03976c49="">
                      <path d="m8 2.748-.717-.737C5.6.281 2.514.878 1.4 3.053c-.523 1.023-.641 2.5.314 4.385.92 1.815 2.834 3.989 6.286 6.357 3.452-2.368 5.365-4.542 6.286-6.357.955-1.886.838-3.362.314-4.385C13.486.878 10.4.28 8.717 2.01L8 2.748zM8 15C-7.333 4.868 3.279-3.04 7.824 1.143c.06.055.119.112.176.171a3.12 3.12 0 0 1 .176-.17C12.72-3.042 23.333 4.867 8 15z">

                      </path></g></svg></div>
                      <div data-v-03976c49="" role="button" title="Horario flexible" class="skill-tag custom-skill-tag text-truncate border border-dark text-dark p-1 col-2">
                        <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="watch" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-watch b-icon bi">
                          <g data-v-03976c49=""><path d="M8.5 5a.5.5 0 0 0-1 0v2.5H6a.5.5 0 0 0 0 1h2a.5.5 0 0 0 .5-.5V5z"></path>
                            <path d="M5.667 16C4.747 16 4 15.254 4 14.333v-1.86A5.985 5.985 0 0 1 2 8c0-1.777.772-3.374 2-4.472V1.667C4 .747 4.746 0 5.667 0h4.666C11.253 0 12 .746 12 1.667v1.86a5.99 5.99 0 0 1 1.918 3.48.502.502 0 0 1 .582.493v1a.5.5 0 0 1-.582.493A5.99 5.99 0 0 1 12 12.473v1.86c0 .92-.746 1.667-1.667 1.667H5.667zM13 8A5 5 0 1 0 3 8a5 5 0 0 0 10 0z">

                            </path></g></svg></div>
                            <div data-v-03976c49="" role="button" title="Trabajo remoto parcial" class="skill-tag custom-skill-tag text-truncate border border-dark text-dark p-1 col-2">
                              <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="geo alt" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-geo-alt b-icon bi">
                                <g data-v-03976c49="">
                                  <path d="M12.166 8.94c-.524 1.062-1.234 2.12-1.96 3.07A31.493 31.493 0 0 1 8 14.58a31.481 31.481 0 0 1-2.206-2.57c-.726-.95-1.436-2.008-1.96-3.07C3.304 7.867 3 6.862 3 6a5 5 0 0 1 10 0c0 .862-.305 1.867-.834 2.94zM8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10z"></path>
                                  <path d="M8 8a2 2 0 1 1 0-4 2 2 0 0 1 0 4zm0 1a3 3 0 1 0 0-6 3 3 0 0 0 0 6z">

                                  </path></g></svg></div>
                                  <div data-v-03976c49="" role="button" title="Celebración de días especiales" class="skill-tag custom-skill-tag text-truncate border border-dark text-dark p-1 col-2">
                                    <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="emoji sunglasses" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-emoji-sunglasses b-icon bi">
                                      <g data-v-03976c49="">
                                        <path d="M4.968 9.75a.5.5 0 1 0-.866.5A4.498 4.498 0 0 0 8 12.5a4.5 4.5 0 0 0 3.898-2.25.5.5 0 1 0-.866-.5A3.498 3.498 0 0 1 8 11.5a3.498 3.498 0 0 1-3.032-1.75zM7 5.116V5a1 1 0 0 0-1-1H3.28a1 1 0 0 0-.97 1.243l.311 1.242A2 2 0 0 0 4.561 8H5a2 2 0 0 0 1.994-1.839A2.99 2.99 0 0 1 8 6c.393 0 .74.064 1.006.161A2 2 0 0 0 11 8h.438a2 2 0 0 0 1.94-1.515l.311-1.242A1 1 0 0 0 12.72 4H10a1 1 0 0 0-1 1v.116A4.22 4.22 0 0 0 8 5c-.35 0-.69.04-1 .116z"></path>
                                        <path d="M16 8A8 8 0 1 1 0 8a8 8 0 0 1 16 0zm-1 0A7 7 0 1 0 1 8a7 7 0 0 0 14 0z">

                                        </path></g></svg></div>
                                        <div data-v-03976c49="" role="button" title="Ambiente de trabajo amigable" class="skill-tag custom-skill-tag text-truncate border border-dark text-dark p-1 col-2">
                                          <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="people" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-people b-icon bi">
                                            <g data-v-03976c49="">
                                              <path d="M15 14s1 0 1-1-1-4-5-4-5 3-5 4 1 1 1 1h8zm-7.978-1A.261.261 0 0 1 7 12.996c.001-.264.167-1.03.76-1.72C8.312 10.629 9.282 10 11 10c1.717 0 2.687.63 3.24 1.276.593.69.758 1.457.76 1.72l-.008.002a.274.274 0 0 1-.014.002H7.022zM11 7a2 2 0 1 0 0-4 2 2 0 0 0 0 4zm3-2a3 3 0 1 1-6 0 3 3 0 0 1 6 0zM6.936 9.28a5.88 5.88 0 0 0-1.23-.247A7.35 7.35 0 0 0 5 9c-4 0-5 3-5 4 0 .667.333 1 1 1h4.216A2.238 2.238 0 0 1 5 13c0-1.01.377-2.042 1.09-2.904.243-.294.526-.569.846-.816zM4.92 10A5.493 5.493 0 0 0 4 13H1c0-.26.164-1.03.76-1.724.545-.636 1.492-1.256 3.16-1.275zM1.5 5.5a3 3 0 1 1 6 0 3 3 0 0 1-6 0zm3-2a2 2 0 1 0 0 4 2 2 0 0 0 0-4z">

                                              </path></g></svg></div>
                                              <div data-v-03976c49="" role="button" title="Capacitaciones" class="skill-tag custom-skill-tag text-truncate border border-dark text-dark p-1 col-2">
                                                <svg data-v-03976c49="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="clipboard check" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-clipboard-check b-icon bi">
                                                  <g data-v-03976c49="">
                                                    <path fill-rule="evenodd" d="M10.854 7.146a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708 0l-1.5-1.5a.5.5 0 1 1 .708-.708L7.5 9.793l2.646-2.647a.5.5 0 0 1 .708 0z"></path><path d="M4 1.5H3a2 2 0 0 0-2 2V14a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V3.5a2 2 0 0 0-2-2h-1v1h1a1 1 0 0 1 1 1V14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3.5a1 1 0 0 1 1-1h1v-1z"></path>
                                                    <path d="M9.5 1a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5h-3a.5.5 0 0 1-.5-.5v-1a.5.5 0 0 1 .5-.5h3zm-3-1A1.5 1.5 0 0 0 5 1.5v1A1.5 1.5 0 0 0 6.5 4h3A1.5 1.5 0 0 0 11 2.5v-1A1.5 1.5 0 0 0 9.5 0h-3z"></path>
            </g>
            </svg>
            </div>
            </div> 
            </div>  
            </div>
          </div>
        </div>
      </div>
    </div>


  </div>




  

  
</template>

<script>
export default {
  data() {
    return {
      nombreCargo:'Supervisor Visitado Médica',
      requisitos1: 'Excel',
      requisitos2: 'Sales',
      requisitos3: 'Selling Ability',
      nombreEmpresa: 'Dentaid',
      ciudad: 'Bogotá',
      salario: '2.5M - 4M COP',
      vacantes: '1 Vacante',
      tiempoPublicacion: '2 days ago',
      
    }
  }
}
</script>

<style>






.logo-container {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 50%;
  height: 70px;
}

.logo {
  width: 70px;
  height: 70px;
}

.company-info {
  text-align: left;
  margin-bottom: 20px;
}

.info-item {
  padding: 10px;
margin-bottom: 10px;
}

.info-item p {
  margin-bottom: 0;
}


.shadow-on-hover {
  transition: box-shadow 0.3s;
}

.shadow-on-hover:hover {
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
}

</style>