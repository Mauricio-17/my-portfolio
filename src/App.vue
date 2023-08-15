<style scoped>
* {
  box-sizing: border-box;
}

a {
  text-decoration: none;
}

.title {
  font-family: 'Ant7', cursive;
}

.paragraph {
  font-family: 'Crimson Text', serif;
}
</style>

<template>
  <v-app>
    <v-main>
      <div class="container">

        <div :class="aligningCenter + ' mt-5'" id="home">
          <v-avatar size="200">
            <v-img src="./assets/mauricio.jpg"> </v-img>
          </v-avatar>
          <h1 class="title text-deep-purple-accent-4  mt-5 mb-5 ">MAURICIO SOLIS</h1>
          <v-card min-width="350" max-width="600" :class="marginTotal" color="blue-lighten-2">
            <v-card-item>
              <h2 class="text-red-darken-3">Desarrollador WEB,
                analista de datos y estudiante</h2>
            </v-card-item>
            <v-card-text>
              <h2 class="text-red-lighten-1  paragraph">
                Programador, autodidacta y entusiasta de la informática con 3+ años involucrado en el desarrollo de Software
                especialmente
                en entornos WEB, dispuesto a prender más de otros profesionales como a colaborar en el aprendizaje del resto, además de dar todo de sí por quienes apuesten por mi profesionalismo.
                Soy desarrollador fullstack orientado más en backend, mayor info en la parte de abajo...
              </h2>
            </v-card-text>
          </v-card>

          <v-card min-width="350" max-width="600" color="blue-lighten-2" :class="marginTotal">
            <v-card-item>
              <h3 class="text-indigo-accent-4">Aquí esta una pequeña lista de las conceptos y tecnologías que mayormente
                uso:</h3>
            </v-card-item>
            <v-card-item>
              <ul>
                <li class="d-flex flex-row">
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <v-img min-width="45" src="./assets/java.png"></v-img>
                  </v-sheet>
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <h3 class="paragraph">Java</h3>
                  </v-sheet>
                </li>
                <li class="d-flex flex-row ">
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <v-img min-width="45" src="./assets/spring_boot.png"></v-img>
                  </v-sheet>
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <h3 class="paragraph">Spring Boot</h3>
                  </v-sheet>
                </li>
                <li class="d-flex flex-row ">
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <v-img min-width="45" src="./assets/javascript.png"></v-img>
                  </v-sheet>
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <h3 class="paragraph">Javascript</h3>
                  </v-sheet>
                </li>
                <li class="d-flex flex-row ">
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <v-img min-width="45" src="./assets/typescript.png"></v-img>
                  </v-sheet>
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <h3 class="paragraph">Typescript</h3>
                  </v-sheet>
                </li>
                <li class="d-flex flex-row ">
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <v-img min-width="45" src="./assets/vue-icon.png"></v-img>
                  </v-sheet>
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <h3 class="paragraph">Vue JS</h3>
                  </v-sheet>
                </li>
                <li class="d-flex flex-row ">
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <v-img min-width="45" src="./assets/express.png"></v-img>
                  </v-sheet>
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <h3 class="paragraph">Express JS</h3>
                  </v-sheet>
                </li>
                <li class="d-flex flex-row ">
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <v-img min-width="45" src="./assets/mysql.png"></v-img>
                  </v-sheet>
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <h3 class="paragraph">MySQL</h3>
                  </v-sheet>
                </li>
                <li class="d-flex flex-row ">
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <v-img min-width="45" src="./assets/python.png"></v-img>
                  </v-sheet>
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <h3 class="paragraph">Python</h3>
                  </v-sheet>
                </li>
                <li class="d-flex flex-row ">
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <v-img min-width="45" src="./assets/flask.png"></v-img>
                  </v-sheet>
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <h3 class="paragraph">Flask</h3>
                  </v-sheet>
                </li>
                <li class="d-flex flex-row ">
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <v-img min-width="45" src="./assets/git_icon.png"></v-img>
                  </v-sheet>
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <h3 class="paragraph">GIT</h3>
                  </v-sheet>
                </li>
                <li class="d-flex flex-row ">
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <h3 class="paragraph">Más por aprender . . .</h3>
                  </v-sheet>
                </li>
              </ul>
            </v-card-item>
          </v-card>

          <v-card min-width="350" max-width="600" color="blue-lighten-2" :class="marginTotal">
            <v-card-item>
              <h3 class="text-indigo-accent-4">Aquí otra lista de tecnologías y conceptos de las que estoy familiarizado.
              </h3>
            </v-card-item>
            <v-card-item>
              <ul>
                <li class="d-flex flex-row">
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <v-img min-width="45" src="./assets/docker.png"></v-img>
                  </v-sheet>
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <h3 class="paragraph">Docker</h3>
                  </v-sheet>
                </li>
                <li class="d-flex flex-row ">
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <v-img min-width="45" src="./assets/ubuntu.png"></v-img>
                  </v-sheet>
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <h3 class="paragraph">GNU/LINUX Ubuntu</h3>
                  </v-sheet>
                </li>
                <li class="d-flex flex-row ">
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <v-img min-width="45" src="./assets/pandas.png"></v-img>
                  </v-sheet>
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <h3 class="paragraph">Análisis de datos con Pandas</h3>
                  </v-sheet>
                </li>
                <li class="d-flex flex-row ">
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <v-img min-width="45" src="./assets/power-bi.png"></v-img>
                  </v-sheet>
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <h3 class="paragraph">Power BI</h3>
                  </v-sheet>
                </li>
                <li class="d-flex flex-row ">
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <v-img min-width="45" src="./assets/postgre.png"></v-img>
                  </v-sheet>
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <h3 class="paragraph">PostgreSQL</h3>
                  </v-sheet>
                </li>
                <li class="d-flex flex-row ">
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <v-img min-width="45" src="./assets/sqlserver.png"></v-img>
                  </v-sheet>
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <h3 class="paragraph">SQL-Server</h3>
                  </v-sheet>
                </li>
                <li class="d-flex flex-row ">
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <v-img min-width="45" src="./assets/selenium.png"></v-img>
                  </v-sheet>
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <h3 class="paragraph">Selenium</h3>
                  </v-sheet>
                </li>
                <li class="d-flex flex-row ">
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <v-img min-width="45" src="./assets/scrapy.png"></v-img>
                  </v-sheet>
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <h3 class="paragraph">Scrapy</h3>
                  </v-sheet>
                </li>
                <li class="d-flex flex-row ">
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <v-img min-width="45" src="./assets/tensorflow.png"></v-img>
                  </v-sheet>
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <h3 class="paragraph">Tensorflow</h3>
                  </v-sheet>
                </li>
                <li class="d-flex flex-row ">
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <v-img min-width="45" src="./assets/blockchain.png"></v-img>
                  </v-sheet>
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <h3 class="paragraph">Blockchain</h3>
                  </v-sheet>
                </li>
                <li class="d-flex flex-row ">
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <v-img min-width="45" max-height="50" src="./assets/solidity.png"></v-img>
                  </v-sheet>
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <h3 class="paragraph">Solidity</h3>
                  </v-sheet>
                </li>
                <li class="d-flex flex-row ">
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <v-img min-width="45" src="./assets/microservice.png"></v-img>
                  </v-sheet>
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <h3 class="paragraph">Microservicios</h3>
                  </v-sheet>
                </li>
                <li class="d-flex flex-row ">
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <v-img min-width="45" src="./assets/Flag_of_the_United_Kingdom.png"></v-img>
                  </v-sheet>
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <h3 class="paragraph">Intermediate English level</h3>
                  </v-sheet>
                </li>
                <li class="d-flex flex-row ">
                  <v-sheet class="ma-2 pa-2 bg-blue-lighten-2">
                    <h3 class="paragraph">Más por aprender . . .</h3>
                  </v-sheet>
                </li>
              </ul>
            </v-card-item>
          </v-card>
        </div>

        <div id="about" :class="aligningCenter + ' mt-5'">
          <v-card min-width="350" max-width="600" color="indigo-lighten-1" :class="marginTotal">
            <v-card-item>
              <v-card-title color="">
                <h3 class="text-teal-accent-3">Acerca de mi</h3>
              </v-card-title>
            </v-card-item>
            <v-card-text>
              <h2 class="mt-2 text-teal-accent-1 paragraph"> Nacido en el 2000, y orientado a llevar un estilo de
                vida balanceada, busco aprender más de
                las personas
                así como colaborar en su aprendizaje. Siempre busco retener buenas cosas en todas mis experiencias.
              </h2>
              <h2 class="mt-2 text-teal-accent-1 paragraph">
                En lo personal práctico el futbol y me gusta salir a pasear y mejorar mi inglés como parte de mi Hobby.
                Desde muy joven estoy interesado en temas de la informática (no solamente en el desarrollo de SW) por lo
                que
                podría abrirme facilmente a otras ramas de IT, es por ello que me considero un "libro abierto" en este campo de la ciencia.

              </h2>
              <h2 class="mt-2 text-teal-accent-1 paragraph">Actualmente estoy enfocado en el desarrollo WEB,
                aunque con un poco de práctica a la vez en
                el Análisis de
                datos con Python.
                Además me encuentro investigando acerca de la tecnología Blockchain como parte de mi proyecto para
                sustentación de tesis universitaria.</h2>
            </v-card-text>
          </v-card>
        </div>

        <h2 id="projects" class="text-light-blue-darken-4 d-flex flex-column align-center mt-4">Mis proyectos</h2>

        <div :class="aligningCenter">
          <h4 class="text-green-accent-4">Mis proyectos recientes</h4>
          <v-card min-width="350" max-width="600" color="cyan-lighten-1" :class="marginTotal">
            <v-card-item>
              <v-card-title color="">
                <h3 class="text-cyan-darken-4"> Sistema Inventario</h3>
              </v-card-title>
            </v-card-item>
            <v-card-item>
              <p><a href="https://github.com/Mauricio-17/inventory-system" target="_blank">Ver código</a></p>
              <p><a href="https://inventory-container.onrender.com/" target="_blank">Ver demostración</a></p>
              <v-img src="./assets/snapshot_inventory.png">
              </v-img>
            </v-card-item>
            <v-card-actions>
              <v-img class="ms-5" src="./assets/docker.png" alt="Docker" max-width="35"></v-img>
              <v-img class="ms-5" src="./assets/spring_boot.png" max-width="35"></v-img>
              <v-img class="ms-5" src="./assets/java.png" alt="Java" max-width="35"></v-img>
              <v-img class="ms-5" src="./assets/vue-icon.png" alt="Vue" max-width="35"></v-img>
              <v-img class="ms-5" src="./assets/javascript.png" alt="Javascript" max-width="35"></v-img>
              <v-img class="ms-5" src="./assets/mysql.png" alt="MySQL" max-width="35"></v-img>
            </v-card-actions>
          </v-card>

          <v-card min-width="350" max-width="600" color="cyan-lighten-1" :class="marginTotal">
            <v-card-item>
              <v-card-title color="">
                <h3 class="text-cyan-darken-4"> Sistema Veterinario</h3>
              </v-card-title>
            </v-card-item>
            <v-card-item>
              <p><a href="https://github.com/Mauricio-17/vet-sys-fullstack-typescript" target="_blank">Ver código</a></p>
              <p><a href="https://vet-sys.onrender.com" target="_blank">Ver demostración</a></p>
              <v-img src="./assets/vetsys_snapshot.png">
              </v-img>
            </v-card-item>
            <v-card-actions>
              <v-img class="ms-5" src="./assets/nodejs.png" max-width="35"></v-img>
              <v-img class="ms-5" src="./assets/express.png" max-width="35"></v-img>
              <v-img class="ms-5" src="./assets/MongoDBAtlas.png" alt="MongoDB" max-width="35"></v-img>
              <v-img class="ms-5" src="./assets/vue-icon.png" alt="Vue" max-width="35"></v-img>
              <v-img class="ms-5" src="./assets/typescript.png" alt="Typescript" max-width="35"></v-img>
            </v-card-actions>
          </v-card>

          <v-card min-width="350" max-width="600" color="cyan-lighten-1" :class="marginTotal">
            <v-card-item>
              <h2 class="text-cyan-darken-4">Web Scraping a la website Audible.com con Scrapy</h2>
            </v-card-item>
            <v-card-item>
              <p><a href="https://github.com/Mauricio-17/WebScraping-Scrapy-AudiblePage" target="_blank">Ver código</a></p>

            </v-card-item>
            <v-card-actions>
              <v-img class="ms-5" src="./assets/scrapy.png" max-width="55" alt="Scrapy"></v-img>
              <v-img class="ms-5" src="./assets/anaconda-py.png" max-width="35" alt="Anaconda"></v-img>
              <v-img class="ms-5" src="./assets/python.png" alt="Python" max-width="35"></v-img>
            </v-card-actions>
          </v-card>
        </div>

        <h4 class="text-light-blue-darken-1 d-flex flex-column align-center mt-4">Más proyectos en mi <a
            href="https://github.com/Mauricio-17?tab=repositories">GitHub</a></h4>

        <h2 id="contacts" class="text-light-blue-darken-4 d-flex flex-column align-center mt-4">Contacto</h2>

        <div :class="aligningCenter">
          <v-card min-width="350" max-width="800" color="lime-lighten-1" :class="marginTotal">
            <v-card-item>
              <v-card-title>
                Contactar
              </v-card-title>
            </v-card-item>

            <v-card-text>
              <form>
                <v-text-field v-model="initialState.name" :counter="10" label="Nombre" required></v-text-field>

                <v-text-field v-model="initialState.email" label="E-mail" required>
                </v-text-field>

                <v-textarea label="Mensaje" required v-model="initialState.message" :counter="10">
                </v-textarea>

                <div class="mt-2">
                  <v-btn class="me-4" @click="send" color="primary">
                    ENVIAR
                  </v-btn>
                  <v-btn @click="clear" color="info">
                    LIMPIAR
                  </v-btn>
                </div>
              </form>
            </v-card-text>

            <v-card-actions>
              <a href="https://twitter.com/Maurici79297912" class="ms-4" target="_blank">
                <v-icon size="40" icon="mdi-twitter"></v-icon>
              </a>
              <a href="mailto:mau.solis5t@gmail.com?Subject=Hiring" class="ms-4" target="_blank">
                <v-icon size="40" icon="mdi-email"></v-icon>
              </a>
              <a href="https://github.com/Mauricio-17" class="ms-4" target="_blank">
                <v-icon size="40" icon="mdi-github"></v-icon>
              </a>
              <a href="https://wa.me/936667905" class="ms-4" target="_blank">
                <v-icon size="40" icon="mdi-whatsapp"></v-icon>
              </a>
              <a href="https://www.linkedin.com/in/mauricio-solis-cipriano-s7" class="ms-4" target="_blank">
                <v-icon size="40" icon="mdi-linkedin"></v-icon>
              </a>
            </v-card-actions>
          </v-card>

        </div>
      </div>

      <v-bottom-navigation bg-color="green-accent-2">
        <v-btn value="recent">
          <a href="#home">
            <v-icon>mdi-home</v-icon><br>Inicio
          </a>
        </v-btn>

        <v-btn value="favorites">
          <a href="#about"><v-icon>mdi-account-search</v-icon><br>Acerca de mi</a>
        </v-btn>

        <v-btn value="nearby">

          <a href="#projects"><v-icon>mdi-folder-multiple</v-icon><br>Proyectos</a>

        </v-btn>
        <v-btn value="nearby">

          <a href="#contacts"><v-icon>mdi-account</v-icon><br>Contactos</a>
        </v-btn>
      </v-bottom-navigation>

    </v-main>
  </v-app>
</template>

<script setup lang="ts">
import { ref, Ref } from 'vue';
import emailjs from '@emailjs/browser';

import { reactive } from 'vue';
import { useVuelidate } from '@vuelidate/core';
import { email, required } from '@vuelidate/validators';



const aligningCenter: string = "d-flex align-center flex-column";

const marginTotal: string = "ma-3";

const initialState = reactive({
  name: '',
  email: '',
  message: ''
});


const send = async () => {
  let item = { ...initialState };

  const SERVICE_ID = "service_svuref8";
  const TEMPLATE_ID = "contact_form";
  const PUBLIC_KEY = "EaOQYwTV-GaKt-1uX";

  try {
    const result = await emailjs.send(SERVICE_ID, TEMPLATE_ID, item, PUBLIC_KEY);
    console.log('SUCCESS! ' + result.status);
    clear();
  }
  catch (err) {
    if (err instanceof Error)
      console.error("FAILED..." + err.message);
  }
  finally {
    console.log('ANYWAY :@');
  }

};


const rules = {
  name: { required },
  email: { required, email },
  message: { required },
  select: { required },
  items: { required },
  checkbox: { required },
};


const clear = () => {
  initialState.email = "";
  initialState.message = "";
  initialState.name = "";
};

</script>
