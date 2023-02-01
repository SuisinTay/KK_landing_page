<template>
  <div class="container-fluid m-0 p-0">
    <div id="home-page" class="full-height p-4">
      <div class="container pt-4">
        <div class="row pb-5">
          <div class="col-lg-6 pt-4 my-auto">
            <div class="text-center mb-3 d-block d-lg-none">
              <h1 class="display-3">{{ title }}</h1>
              <h3>
                Trusted AutoCount Dealer in Malaysia.
              </h3>
            </div>
            <img id="carousel-img" src="../assets/KK_carousel1.jpg" alt="" />
          </div>
          <div class="col-lg-6 my-auto pt-4">
            <div class="text-center mb-3 d-none d-lg-block">
              <h1 class="display-3">{{ title }}</h1>
              <h3>
                Trusted AutoCount Dealer in Malaysia.
              </h3>
            </div>

            <div class="border p-3 p-md-5 bg-white rounded shadow">
              <h2>Why Should You choose AutoCount Accounting 2.0?</h2>
              <form action="">
                <div class="form-group">
                  <label for="emailSignup"
                    >Discover why AutoCount Accounting is the fastest growing
                    accounting software in Malaysia.</label
                  >
                  <input
                    id="emailSignup"
                    placeholder="Enter Email"
                    class="form-control"
                  />
                  <small id="emailHelp" class="form-text text-muted"
                    >We'll never share your email address</small
                  >
                  <button type="submit" class="btn btn-success mt-3">
                    Submit Email
                  </button>
                </div>
              </form>
            </div>

            <div id="available" class="p-2"></div>
          </div>
        </div>
      </div>
    </div>
    <div id="about" class="bg-light p-3 p-md-5">
      <div class="row">
        <div class="col-lg">
          <img src="../assets/analyze.svg" height="120" class="m-4" />
          <h5 class="ml-md-4 mr-md-4">
            AutoCount Accounting is a powerful tool to manage your business
            data, to analyze your business performance, to share your business
            information and to help you make informed business decisions.
          </h5>
        </div>
        <div class="col-lg">
          <img src="../assets/robot.svg" height="120" class="m-4" />
          <h5 class="ml-md-4 mr-md-4">
            With its advanced technology such as Microsoft .Net Framework, SQL
            Server and internet ready, AutoCount Accounting stands out as one of
            the best accounting software for today business requirements.
          </h5>
        </div>
        <div class="col-lg">
          <img src="../assets/calculate.svg" height="120" class="m-4" />
          <h5 class="ml-md-4 mr-md-4">
            AutoCount Accounting helps to streamline your business operation. It
            provides strong and stable database for every type of business and
            able to perform all types of account transactions, no matter how
            complicated it is.
          </h5>
        </div>
      </div>
    </div>
    <div id="contact" class="p-4">
      <div class="row justify-content-center mt-3 mb-3">
        <div class="col-lg-4">
          <h2>Have Any Questions?</h2>
          <p>Contact us by filling out the information below</p>

          <form>
            <div class="form-group text-left">
              <input
                type="email"
                class="form-control"
                placeholder="Enter Your Email"
              />
              <textarea
                class="form-control mt-3"
                placeholder="Enter Your Message"
                rows="5"
              ></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Send Message</button>
          </form>
        </div>
      </div>
    </div>
    <div id="footer" class="p-4">
      <footer class="text-light p-4">
        <a
          href="https://www.facebook.com/KK-Computer-Sdn-Bhd-103068108196945"
          target="_blank"
          class="text-warning"
          >Facebook</a
        >
        |
        <a href="https://pandasoftware.my/" class="text-warning">Panda</a>
        <br />
        <small>&copy; 2023, KK Computer SDN BHD</small>
      </footer>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: "KK Computer"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#home-page {
  display: flex;
  align-items: center;
  background-color: #92d2f2;
  background: url("../assets/bg-img-2.jpg") no-repeat center center;
  background-size: cover;
}

#about {
  min-height: 40vh;
}

#contact {
  background-color: #57aeaf;
}

#footer {
  background-color: #252223;
}

#carousel-img {
  max-height: 45vh;
}
</style>
