<template>
  <v-app id="home">
    <NavBar />
    <v-container fluid>
      <div class="head">
        <v-row>
          <v-col cols="5">
            <div style="position: relative" class="mt-16">
              <h1 class="text-grey">Hello,</h1>
              <h1 class="text-white">I'm Sakti Alfansyah Putra</h1>
              <span class="text-grey"
                >Back End Developer with Laravel Framework</span
              ><br />

              <v-btn tile dark class="text-yellow mt-8" variant="outlined">
                Contact me
              </v-btn>
            </div>
          </v-col>
          <v-col cols="2">
            <div
              style="
                position: absolute;
                z-index: 9999;
                bottom: 0;
                margin-left: auto;
                margin-right: auto;
                left: 0;
                right: 0;
                text-align: center;
              "
              class="mt-16"
            >
              <v-icon>fas fa-angle-double-down</v-icon>
            </div>
          </v-col>
          <v-col cols="5">
            <div style="position: relative; z-index: 9999" class="mt-16">
              <v-img src="i13.png" contain max-height="300"></v-img>
            </div>
          </v-col>
        </v-row>
      </div>
      <v-col cols="12" class="mt-16" id="about">
        <div>
          <v-row>
            <v-col cols="12" sm="6">
              <div class="egg">
                <v-img src="i14.png" max-height="300" class=""></v-img>
              </div>
            </v-col>
            <v-col cols="12" sm="6">
              <h5 class="mt-16">About Me</h5>
              <div style="width: 120px">
                <v-slider
                  v-model="slider2"
                  color="yellow"
                  label="track-color"
                ></v-slider>
              </div>
              <h4 class="mt-n4">I Am a Back End Developer</h4>
              <p class="text-grey">
                As a skilled Back End Developer with expertise in Laravel, I
                possess a strong understanding of web development principles and
                server-side technologies. I have hands-on experience in
                designing, developing, and maintaining robust and scalable
                applications. My proficiency in Laravel's MVC architecture,
                Eloquent ORM, and RESTful APIs allows me to efficiently create
                efficient and secure back-end solutions. I am well-versed in
                database management, ensuring seamless integration with
                front-end technologies and optimizing application performance.
                As a detail-oriented problem solver, I strive to deliver
                high-quality code and collaborate effectively with
                cross-functional teams to meet project objectives
              </p>
              <v-btn tile dark color="yellow" class="mt-4">
                Download Resume
              </v-btn>
            </v-col>
          </v-row>
        </div>
      </v-col>
      <div class="text-center mt-4">
        <h2>What we Do</h2>
        <div style="width: 120px; margin: 0 auto">
          <v-slider
            v-model="slider2"
            color="yellow"
            label="track-color"
          ></v-slider>
        </div>
      </div>
      <v-col cols="12" class="padd" id="portfolio">
        <div class="first" id="project">
          <v-row class="services-grid">
            <v-col cols="12" md="4">
              <div class="child">
                <v-btn
                  icon="fas fa-laptop"
                  color="#FBDF7E"
                  class="text-white"
                ></v-btn>
                <h3 class="ml-3 mt-4">Web Application Development</h3>
                <p
                  class="text-grey ml-3 mt-4 text-caption"
                  style="text-align: justify"
                >
                  I have a proven track record of developing full-fledged web
                  applications from the ground up, using Laravel as the core
                  framework. From conceptualization to deployment, I ensure that
                  each application is tailored to meet the specific needs and
                  requirements of the client.
                </p>
              </div>
            </v-col>
            <v-col cols="12" md="4">
              <div class="child">
                <v-btn
                  icon="fas fa-database"
                  color="#FBDF7E"
                  class="text-white"
                ></v-btn>
                <h3 class="ml-3 mt-4">Database Management</h3>
                <p
                  class="text-grey ml-3 mt-4 text-caption"
                  style="text-align: justify"
                >
                  With a deep understanding of Laravel's integration with
                  popular database management systems like MySQL and PostgreSQL,
                  I design and manage efficient database structures. This
                  ensures smooth data handling and retrieval, contributing to
                  the overall performance of the applications.
                </p>
              </div>
            </v-col>
            <v-col cols="12" md="4">
              <div class="child">
                <v-btn
                  icon="fas fa-code"
                  color="#FBDF7E"
                  class="text-white"
                ></v-btn>
                <h3 class="ml-3 mt-4">API Development</h3>
                <p
                  class="text-grey ml-3 mt-4 text-caption"
                  style="text-align: justify"
                >
                  I excel in crafting RESTful APIs that facilitate seamless
                  communication between front-end and back-end components of web
                  applications. This allows for easy integration with various
                  third-party services and enhances the application's
                  functionality.
                </p>
              </div>
            </v-col>
          </v-row>
        </div>
      </v-col>
      <v-col cols="12" class="padd mb-8" id="portfolio">
        <div class="first" id="project">
          <v-row class="services-grid">
            <v-col cols="12" md="4">
              <div class="child">
                <v-btn
                  icon="fas fa-cogs"
                  color="#FBDF7E"
                  class="text-white"
                ></v-btn>
                <h3 class="ml-3 mt-4">Problem-Solving Skills</h3>
                <p
                  class="text-grey ml-3 mt-4 text-caption"
                  style="text-align: justify"
                >
                  I thrive in troubleshooting and resolving technical challenges
                  that may arise during the development process. My ability to
                  analyze issues and implement effective solutions ensures
                  smooth development cycles.
                </p>
              </div>
            </v-col>
            <v-col cols="12" md="4">
              <div class="child">
                <v-btn
                  icon="fas fa-wrench"
                  color="#FBDF7E"
                  class="text-white"
                ></v-btn>
                <h3 class="ml-3 mt-4">Migration and Maintenance</h3>
                <p
                  class="text-grey ml-3 mt-4 text-caption"
                  style="text-align: justify"
                >
                  As part of my services, I handle database migrations and
                  perform routine maintenance on Laravel applications. This
                  ensures that the applications remain up-to-date, efficient,
                  and free of technical debt.
                </p>
              </div>
            </v-col>
            <v-col cols="12" md="4">
              <div class="child">
                <v-btn
                  icon="fas fa-users"
                  color="#FBDF7E"
                  class="text-white"
                ></v-btn>
                <h3 class="ml-3 mt-4">Team Collaboration</h3>
                <p
                  class="text-grey ml-3 mt-4 text-caption"
                  style="text-align: justify"
                >
                  Working harmoniously in a team environment is second nature to
                  me. I collaborate effectively with Front-end Developers, UI/UX
                  Designers, and other stakeholders, contributing to the
                  successful completion of complex projects.
                </p>
              </div>
            </v-col>
          </v-row>
        </div>
      </v-col>
      <v-divider></v-divider>
      <v-col cols="12" sm="12" id="services">
        <div class="d-flex justify-center mb-6 mt-6">
          <v-btn color="#FBDF7E" class="mr-2">All</v-btn>
          <!-- <v-btn class="mr-2" variant="tonal">Web Design</v-btn>
          <v-btn class="mr-2" variant="tonal">Front Design</v-btn>
          <v-btn class="mr-2" variant="tonal"> Photography</v-btn>
          <v-btn variant="tonal"> Illustration</v-btn> -->
        </div>
      </v-col>
      <v-col cols="12" class="imgHover">
        <v-row class="fill-height" align="center" justify="center">
          <template v-for="(item, i) in items" :key="i">
            <v-col cols="12" md="4">
              <v-hover v-slot="{ isHovering, props }">
                <v-card
                  :elevation="isHovering ? 12 : 2"
                  :class="{ 'on-hover': isHovering }"
                  v-bind="props"
                >
                  <v-img :src="item.img" height="225px" cover> </v-img>
                </v-card>
              </v-hover>
            </v-col>
          </template>
        </v-row>
      </v-col>
      <!-- <v-col cols="12" sm="12">
        <div class="d-flex justify-center mb-6">
          <v-btn color="#FBDF7E" class="mt-4">Load More</v-btn>
        </div>
      </v-col>
      <v-col cols="12" id="page">
        <div class="pre">
          <v-row>
            <v-col cols="12" sm="4">
              <v-card class="mx-auto" max-width="344" height="">
                <v-img src="i10.jpg" height="200px" cover></v-img>

                <v-card-title> We provide you the best </v-card-title>

                <v-card-subtitle>
                  By AAE IdeaPro | 06 Sep 2022
                </v-card-subtitle>
                <v-card-text>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit
                  rem saepe sapiente deleniti, odio non laborum fuga.
                </v-card-text>
              </v-card>
            </v-col>
            <v-col cols="12" sm="4">
              <v-card class="mx-auto" max-width="344" height="">
                <v-img src="i11.jpg" height="200px" cover></v-img>

                <v-card-title> We provide you the best </v-card-title>

                <v-card-subtitle>
                  By AAE IdeaPro | 06 Sep 2022
                </v-card-subtitle>
                <v-card-text>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit
                  rem saepe sapiente deleniti, odio non laborum fuga.
                </v-card-text>
              </v-card>
            </v-col>
            <v-col cols="12" sm="4">
              <v-card class="mx-auto" max-width="344" height="">
                <v-img src="i12.jpg" height="200px" cover></v-img>

                <v-card-title> We provide you the best </v-card-title>

                <v-card-subtitle>
                  By AAE IdeaPro | 06 Sep 2022
                </v-card-subtitle>
                <v-card-text>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit
                  rem saepe sapiente deleniti, odio non laborum fuga.
                </v-card-text>
              </v-card>
            </v-col>
          </v-row>
        </div>
      </v-col> -->
      <!-- <v-col cols="12" id="biog">
        <div class="hire">
          <v-row>
            <v-col cols="12" sm="8">
              <h1 class="mt-9">Hire me for your awesome project</h1>
              <p class="text-grey">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod
                itaque, eaque molestiae deleniti, earum voluptate eos id dicta
                at, blanditiis
              </p>
            </v-col>
            <v-col cols="12" sm="4">
              <v-btn color="#FBDF7E" class="mt-15">Hire Me</v-btn>
            </v-col>
          </v-row>
        </div>
      </v-col> -->
      <v-col cols="12" sm="12" class="px-16" id="contact">
        <v-row>
          <v-col cols="12" sm="4">
            <div class="child">
              <h1>Contact info.</h1>
              <v-btn
                icon="fas fa-map-marker-alt"
                color=""
                class="mt-10"
                variant="outlined"
              ></v-btn
              ><br />
              <span class="text-caption"
                >Berlian Street 17A Bangselok Sumenep </span
              ><br />
              <v-btn
                icon="fas fa-phone-alt"
                color=""
                class="mt-10"
                variant="outlined"
              ></v-btn
              ><br />
              <span class="text-caption">085334954057 ( Whatsapp ) </span>
              <br />
              <v-btn
                icon="fas fa-envelope"
                color=""
                class="mt-10"
                variant="outlined"
              ></v-btn
              ><br />
              <span class="text-caption">saktialfansyahp@gmail.com </span>
              <br />
            </div>
          </v-col>
          <v-col cols="12" sm="8">
            <h1 class="mt-8">Send your message</h1>
            <v-divider></v-divider>
            <span class="text-caption"
              >Please don't hesitate to reach out to me with any inquiries,
              opportunities, or feedback you may have. Whether it's regarding my
              application, collaboration proposals, or any other matter, I am
              eager to hear from you. I will do my best to respond promptly and
              am looking forward to engaging in meaningful discussions. Thank
              you for considering my profile, and I hope to connect with you
              soon.</span
            >
            <v-row class="mt-10">
              <v-col cols="12" sm="6">
                <v-text-field
                  label="Name"
                  persistent-hint
                  variant="outlined"
                ></v-text-field>
              </v-col>
              <v-col cols="12" sm="6">
                <v-text-field
                  label="Phone No"
                  persistent-hint
                  variant="outlined"
                ></v-text-field>
              </v-col>
            </v-row>
            <v-textarea
              label="Message"
              persistent-hint
              variant="outlined"
            ></v-textarea>
            <v-btn color="#FBDF7E" class="mt-2">Submit Now</v-btn>
          </v-col>
        </v-row>
      </v-col>
    </v-container>
    <FooterView />
  </v-app>
</template>

<script>
import { defineComponent } from "vue";
import NavBar from "../components/NavBar.vue";
import FooterView from "../components/FooterView.vue";

// Components
//import HelloWorld from '../components/HelloWorld.vue';

export default defineComponent({
  name: "HomeView",
  setup() {
    return {
      slider2: 50,

      items: [
        {
          img: "i3.png",
        },
        {
          img: "i4.png",
        },
        {
          img: "i5.png",
        },
      ],
    };
  },
  components: {
    NavBar,
    FooterView,
  },
});
</script>
<style scoped>
.v-container {
  padding: 16px 0 16px 0;
}

.head {
  position: relative;
  text-align: center;
  padding: 12px;
  margin-bottom: 6px;
  height: 400px;
  width: 100%;
  color: white;
}
.head:before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 50%;
  background: black;
  transform: skew(0deg, 6deg);
}
.head:after {
  content: "";
  position: absolute;
  top: 0;
  right: 0;
  height: 100%;
  width: 50%;
  background: black;
  transform: skew(0deg, -6deg);
}
.egg {
  display: block;
  margin-left: 100px;
  margin-top: 50px;
  width: 356px;
  height: 350px;
  background-color: #fbdf7e;
  border-radius: 50% 50% 50% 50% / 60% 60% 40% 40%;
}
.first {
  width: 100%;
  height: 280px;
  text-align: center;
  padding: 2rem 2rem;
}
.child {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: center;
  margin-right: 8px;
}
.imgHover {
  padding: 0 200px;
}
.pre {
  width: 100%;
  height: 380px;
  text-align: center;
  padding: 0 200px;
  background-color: #f5f5f5;
}
.hire {
  width: 100%;
  height: 200px;
  padding: 0 200px;
  background-color: #e9e9e9;
  margin-top: -24px;
}
</style>
