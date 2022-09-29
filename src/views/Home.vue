<template>
  <div>
    <body>
      <header>
        <div class="bigbox" id="navbarHeader">
          <div>
            <h1 class="title">My Profile</h1>
            <img class="pic" src="../pic/jackieongrass.jpg" />
          </div>
          <div class="info">
            <h2 style="font-family: Sans-serif">Infomation</h2>
            <hr />
            <div class="contentinfo">
              <ul class="listinfo">
                <li>Name: Jedsarid Sangsuwan</li>
                <li>Age : 17 School</li>
                <li>School : Suankularbwitayalairangsit</li>
              </ul>
            </div>
          </div>

          <div class="boxicon">
            <h3>Contact</h3>
            <a href="https://www.instagram.com/jackienyyy/">
              <img class="icon" src="../pic/ig.png" />
            </a>
            <a href="https://www.facebook.com/jedsarid.sangsuwan.3/">
              <img class="icon" src="../pic/facebook.png" />
            </a>
          </div>
        </div>
      </header>

      <!-- <main role="main">
        <section class="jumbotron text-center">
          <div class="container">
            <h1 class="jumbotron-heading">this is my web</h1>
          </div>
        </section>

        <div class="album py-5 bg-light">
          <div class="container">
            <div class="row">
              <div
                class="col-md-4"
                v-for="product in products"
                :key="product._id"
              >
                <div class="card mb-4 box-shadow">
                  <img class="card-img-top" :src="product.image" />
                  <div class="card-body">
                    <h3 class="card-text">{{ product.name }}</h3>
                    <p class="card-text">
                      {{ product.detail }} <br />
                      <span class="text-danger">{{ product.price }} บาท</span>
                    </p>
                    <div class="">
                      <div class="btn-group text-center">
                        <button type="button" class="btn btn-outline-success">
                          Buy now
                        </button>
                        <button type="button" class="btn btn-outline-secondary">
                          Edit
                        </button>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </main> -->

      <footer class="text-muted">
        <div class="container">
          <p class="float-right">
            <a href="#"></a>
          </p>
        </div>
      </footer>
    </body>
  </div>
</template>

// //
<script>
// import axios from "axios";
// export default {
//   data() {
//     return {
//       products: "",
//     };
//   },
//   methods: {
//     async getProduct() {
//       const response = await axios.get(
//         "https://v-shop-backend.herokuapp.com/product"
//       );
//       console.log(response);
//       this.products = response.data;
//     },
//   },
//   mounted() {
//     this.getProduct();
//   },
// };
//
</script>

<style scoped>
.boxicon {
  align-content: flex-start;
  display: inline;
  cursor: pointer;
  transition-property: transform;
  transition-duration: 1s;
}
.listinfo {
  padding-left: 60px;
}
.boxicon:hover {
  transform: scale(1.1, 1.1);
}

/* li {
  display: inline;
} */

.icon {
  width: 50px;
  height: 50px;
  padding: 10px;

  /* align-self: flex-start; */
}
.icon:hover {
  transform: scale(1.1, 1.1);
}
.info {
  text-align: center;
  position: relative;
  align-items: center;
}
.contentinfo {
  text-align: left;
}
.pic {
  width: 300px;
  height: 400px;
  border-radius: 15px;
}

.boxpro {
  width: 1000px;
  height: 500px;
  text-align: center;
  position: absolute;
}

.title {
  color: rgb(68, 70, 68);
  font-family: "Courier New";
}

.bigbox {
  text-align: center;
}
</style>
