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
            <transition name="slide">
              <img
                id="carousel-img"
                v-if="showImage"
                :src="currentImage"
                alt="error"
              />
            </transition>
          </div>
          <div class="col-lg-6 my-auto pt-4" data-aos="fade-up">
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
        <div class="col-lg" data-aos="fade-right">
          <img src="../assets/analyze.svg" height="120" class="m-4" />
          <h5 class="ml-md-4 mr-md-4">
            AutoCount Accounting is a powerful tool to manage your business
            data, to analyze your business performance, to share your business
            information and to help you make informed business decisions.
          </h5>
        </div>
        <div class="col-lg" data-aos="fade-up">
          <img src="../assets/robot.svg" height="120" class="m-4" />
          <h5 class="ml-md-4 mr-md-4">
            With its advanced technology such as Microsoft .Net Framework, SQL
            Server and internet ready, AutoCount Accounting stands out as one of
            the best accounting software for today business requirements.
          </h5>
        </div>
        <div class="col-lg" data-aos="fade-left">
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
    <div id="products" class="product-container p-3 p-md-5">
      <div class="product-container--item">
        <div class="product-picture" data-aos="fade-right">
          <img
            id="product-img"
            src="../assets/AutoCount2.png"
            alt="error"
            class="m-4"
          />
        </div>
        <div class="text-container-start" data-aos="fade-left">
          <h3 class="items-title">
            One Item, Multiple Pricing
          </h3>
          <h4>
            You can maintain up to 6 difference selling prices for each item.
            AutoCount also has the option of automatically calculating your
            selling price based on the Item Cost & Markup Percentage keyed in.
          </h4>

          <h3 class="items-title">
            Documents Flow Management
          </h3>
          <h4>
            Have a bird's eye view of your entire documents flow at a glance.
            Easy to track and identify the inter-related documents in one single
            view and zoom in for details.
          </h4>

          <h3 class="items-title">
            Total Integration and Scalable
          </h3>
          <h4>
            Integrates easily with AutoCount suite of software and other
            business application programs. You can upgrade the software anytime
            when your business grows and expand without any worries of data
            loss.
          </h4>

          <h3 class="items-title">
            Financial Report Writer
          </h3>
          <h4>
            The new layout editor allows you to customize nearly any aspect of a
            financial report. It also comes with report conversion capability to
            turn data into visually appealing charts and pivot table, or export
            to excel file for further analysis.
          </h4>

          <h3 class="items-title">
            Smart & Quick Searching
          </h3>
          <h4>
            Intelligent search function allows you to conduct searches in
            multiple columns simultaneously. Our search engine is flexible and
            capable of handling various searching patterns
          </h4>

          <h3 class="items-title">
            Personalized Layout
          </h3>
          <h4>
            Customize the document layout according to your preference or to
            suit your company's needs. Save and share your frequently used
            layout template among your team to save time and minimize repetitive
            tasks.
          </h4>
        </div>
      </div>
      <div class="product-container--item">
        <div class="text-container-start" data-aos="fade-left">
          <h3 class="items-title">
            Fully Integrated With Accounting 2.0
          </h3>
          <h4>
            Posting of POS transaction from multiple outlets to Accounting 2.0
            will immediately produce accurate P&L reports. You shall be better
            supported by one same software vendor, as the result of avoiding
            problems with 3rd party integration, software upgrades/updates, and
            issues of data integrity.
          </h4>

          <h3 class="items-title">
            Posting Friendliness
          </h3>
          <h4>
            Posting to Accounting is now more efficient and controllable. You
            may define the Date Range and Outlets to be posted, check Daily
            Posting Summary, drill down to view details in source document, and
            assign different posting accounts for payment methods, taxes,
            rounding adjustment, voucher, deposit, service charges…
          </h4>

          <h3 class="items-title">
            POS + Purchase/Sales Modules
          </h3>
          <h4>
            Packed with Sales module, Purchase module, analysis reports,
            real-time posting to accounting modules (GL, AR, AP), customizable
            documents and running numbers.
          </h4>

          <h3 class="items-title">
            POS + Inventory Control
          </h3>
          <h4>
            Smart inventory control in stock availability, replenishment,
            costing, pricing, analyzing and reporting. Popular features such as:
            stock categorization, Item Image, multi UOM, replacement items,
            barcode, stock level & backorder controls, batches, serial numbers,
            multi-locations, BOM, item assembly and Item Disassembly.
          </h4>
        </div>
        <div class="product-picture" data-aos="fade-right">
          <img
            id="product-img"
            src="../assets/POS5.png"
            alt="error"
            class="m-4"
          />
        </div>
      </div>
      <div class="product-container--item">
        <div class="product-picture" data-aos="fade-right">
          <img
            id="product-img"
            src="../assets/Edash.png"
            alt="error"
            class="m-4"
          />
        </div>
        <div class="text-container-start" data-aos="fade-left">
          <h3 class="items-title">
            Cloud-Based eDashboard App
          </h3>
          <h4>
            AutoCount POS e-Dashboard app is designed to presents retail or F&B
            sales reporting metrics in a way that is easy to digest.It is a
            one-of-a-kind cloud-based mobile sales app to easily track and
            monitor outlets sales performance from wherever you are, at any time
            of the day. It is available for AutoCount POS 5.0 supporting both
            Android and iOS mobile devices.
          </h4>

          <h3 class="items-title">
            Ease Management
          </h3>
          <h4>
            Business managers can access real-time sales report through a
            mobile-friendly sales dashboard on the go.
          </h4>

          <h3 class="items-title">
            Filter Options
          </h3>
          <h4>
            View outlets sales data at a glance with filters option to keep an
            eye on daily/hourly sales transactions.
          </h4>

          <h3 class="items-title">
            Performance Tracking
          </h3>
          <h4>
            Setting outlet daily, weekly or monthly targets and track
            performance progress on set targets.
          </h4>

          <h3 class="items-title">
            Drill down your sales data to gain insights
          </h3>
          <h4>
            Multi-branch or multi-companies sales performance make sales data
            comparison to help you identify trends or problem areas that need
            attention. Top sales ranking by amount and quantity to make sure you
            always have sufficient top-selling products in-stock.
          </h4>
        </div>
      </div>
      <div class="product-container--item">
        <div class="text-container-start" data-aos="fade-left">
          <h3 class="items-title">
            Manage Everything in One Portal
          </h3>
          <h4>
            Dashboard provides total visibility into your HR & Payroll
            information anytime, anywhere at a glance.
          </h4>

          <h3 class="items-title">
            Personalisation
          </h3>
          <h4>
            Create User Defined Field (UDF) or modify the reports according to
            your own preference. You have full control over your payroll.
          </h4>

          <h3 class="items-title">
            Improve Efficiency
          </h3>
          <h4>
            No more cumbersome submission, complex administrative process and
            calculation errors.
          </h4>

          <h3 class="items-title">
            Get Started Easily
          </h3>
          <h4>
            No installation is required! You do not need an expert to handle
            your payroll system. We take care of the most of it.
          </h4>
          <h3 class="items-title">
            Employee Self-Service
          </h3>
          <h4>
            Be it e-Leave, e-Claim, e-Profile, get first hand updates instantly
            online. You can now avoid the tedious paper works.
          </h4>
        </div>
        <div class="product-picture" data-aos="fade-right">
          <img
            id="product-img"
            src="../assets/AutoCountPayroll.png"
            alt="error"
            class="m-4"
          />
        </div>
      </div>
      <div class="product-container--item">
        <div class="product-picture" data-aos="fade-right">
          <img
            id="product-img"
            src="../assets/SQLpayroll.png"
            alt="error"
            class="m-4"
          />
        </div>
        <div class="text-container-start" data-aos="fade-left">
          <h3 class="items-title">
            Simple Payroll Process
          </h3>
          <h4>
            One click to process your monthly payslip,KWSP, SOCSO, PCB, EIS &
            HRDF
          </h4>

          <h3 class="items-title">
            Simple Leave Process
          </h3>
          <h4>
            Handle employees leave in calendar mode
          </h4>

          <h3 class="items-title">
            Statutory Compliance
          </h3>
          <h4>
            Fast updates to comply with latest EA, Borang A,8A,CP39 forms and
            other government regulatory changes
          </h4>

          <h3 class="items-title">
            Easy Disbursements
          </h3>
          <h4>
            21 banks e-payment payroll disbursement options. All government
            reports have e-submission options
          </h4>

          <h3 class="items-title">
            Other Friendly Features
          </h3>
          <h4>
            Process multiple payroll, allowance, bonus, advance, and loans
            separately from month end payroll, record daily wages and OT
            whenever required, system month end auto process, multiple payslip
            formats, payroll analysis, leave, and HR reports
          </h4>
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
import { Url } from "url";
export default {
  data() {
    return {
      title: "KK Computer",
      images: [
        "../assets/KK_carousel1.jpg",
        "../assets/KK_carousel2.jpg",
        "../assets/KK_carousel3.jpg"
      ],
      curInterval: 0,
      showImage: true
    };
  },
  computed: {
    currentImage() {
      console.log();
      return this.images[this.curInterval];
    }
  },
  mounted() {
    setInterval(() => {
      this.showImage = false;
      setTimeout(() => {
        this.curInterval++;
        if (this.curInterval === this.images.length) {
          this.curInterval = 0;
        }
        this.showImage = true;
      }, 500);
    }, 3000);
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

#products {
  background-color: #ffe4fe;
  min-height: 100vh;
}

#product-img {
  width: 50%;
}

#footer {
  background-color: #252223;
}

#carousel-img {
  max-height: 45vh;
}

.slide-enter-active,
.slide-leave-active {
  transition: all 0.5s;
}

.slide-enter,
.slide-leave-to {
  transform: translateX(-100%);
}

.product-container {
  display: flex;
  flex-direction: column;
}

.product-container--item {
  display: flex;
  width: 100%;
  height: fit-content;
  justify-content: center;
  align-items: center;
  margin: 5rem;
}

.items-title {
  text-decoration: underline;
}

.text-container-start {
  display: flex;
  flex-direction: column;
  text-align: start;
  width: 70%;
}

.text-container-end {
  display: flex;
  flex-direction: column;
  text-align: end;
  width: 70%;
}

.product-picture {
  height: 40vh;
  width: 50%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
</style>
