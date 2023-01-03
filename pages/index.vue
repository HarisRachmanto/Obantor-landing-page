<template>
  <div class="container" display="flex">
    <div class="home">
      <!-- Start halaman 1 -->
      <img src="main.jpg" alt="ff" width="55%" style="float: right" />
      <br /><br /><br /><br /><br /><br />
      <h1>
        <i
          ><b>Making <img src="arah.png" width="8%" /></b
        ></i>
      </h1>
      <h1>
        <i><b>Everybody Feel</b></i>
      </h1>
      <h1>
        <i><b>Valued At Work</b></i>
      </h1>
      <br />
      <p>
        With Our Project Management Application, you can collaborate With your
        team easily and sharing flies are superfast
      </p>
      <b-button pill variant="info">Get Started</b-button
      ><br /><br /><br /><br /><br /><br /><br /><br />
    </div>

    <div class="card" style="margin-top: 40px">
      <b-card-group deck>
        <b-card>
          <img src="user.png" alt="" width="15%" /><br /><br />
          <b-card-text>
            <h4>Team Accounts</h4>
            Work as a team and connect with clients. You will get all the
            facilities from the team management App.
          </b-card-text>
        </b-card>

        <b-card>
          <img src="checked.png" alt="" width="15%" /><br /><br />
          <b-card-text>
            <h4>Top Notch Secured</h4>
            We are certified globalily and we always gurantee your security. We
            will alert you if anything happen.
          </b-card-text>
        </b-card>

        <b-card>
          <img src="group.png" alt="" width="15%" /><br /><br />
          <b-card-text>
            <h4>Engage Customers</h4>
            To have more smooth communication you can collaborate here. So you
            dont need to browse others.
          </b-card-text>
        </b-card>
      </b-card-group>
    </div>
    <br /><br />
    <!-- Stop Halaman 1 -->


    <!-- start halaman 2 -->
    <div class="features">
      <center>
        <h1><b>Key Features</b></h1>
        <i>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex, nemo.</i>
      </center>
      <img src="feature.jpg" alt="" width="550px" style="float: left" /><br><br>
      <b-card no-body class="overflow-hidden" style="max-width: 540px">
        <b-row no-gutters>
          <b-col md="5">
            <center><img src="development.png" alt="" style="width:20%"></center>
            <b-card-body title="Development" style="text-align:center">
              <b-card-text>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Vitae, minus.
              </b-card-text>
            </b-card-body>
          </b-col>
          <b-col md="5">
            <center><img src="web.png" alt="" width="15%"></center>
            <b-card-body title="Web Design" style="text-align:center">
              <b-card-text>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Facere, dicta.
              </b-card-text>
            </b-card-body>
          </b-col>
        </b-row>
      </b-card><br>

      
      <b-card no-body class="overflow-hidden" style="max-width: 540px">
        <b-row no-gutters>
          <b-col md="5">
            <center><img src="branding.png" alt="" width="20%"></center>
            <b-card-body title="Branding" style="text-align:center">
              <b-card-text>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Facere, dicta.
              </b-card-text>
            </b-card-body>
          </b-col>
          <b-col md="5">
            <center><img src="marketing.png" alt="" width="20%"></center>
            <b-card-body title="Marketing" style="text-align:center">
              <b-card-text>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Facere, dicta.
              </b-card-text>
            </b-card-body>
          </b-col>
        </b-row>
      </b-card>
    </div><br><br>
    <!-- stop halaman 2 -->


    <!-- Start halaman 3 -->
    <div class="faq">
      <center><h1><b>FAQ's</b></h1></center>
      <b-card class="text">
    <div class="bg-light text-dark">
      <h5><img src="plus.png" width="15px"> How can I bid for your product?</h5>
    </div>
  </b-card>
      <b-card class="text">
    <div class="bg-light text-dark">
      <h5><img src="plus.png" width="15px"> How can I download your App?</h5>
    </div>
  </b-card>
      <b-card class="text">
    <div class="bg-light text-dark">
      <h5><img src="plus.png" width="15px"> How is the function of your product?</h5>
    </div>
  </b-card>
      <b-card class="text">
    <div class="bg-light text-dark">
      <h5><img src="plus.png" width="15px"> How are you exchange rates calculated?</h5>
    </div>
  </b-card>
      <b-card class="text">
    <div class="bg-light text-dark">
      <h5><img src="plus.png" width="15px"> How can I buy your products?</h5>
    </div>
  </b-card>
    </div><br><br>
    <!-- Stop halaman 3 -->
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: 'Task',
      meta: [
        // hid is used as unique identifier. Do not use `vmid` for it as it will not work
        {
          hid: 'description',
          name: 'description',
          content: 'My custom description',
        },
      ],
    }
  },
  pages: 'index',
}
</script>

<style>
</style>