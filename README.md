# iu-web-app-development
Examples for Web Development Advanced Workbook

Task 3 - product.html 
<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>AuroraBrew Smart Kettle - Product Page</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        margin: 0;
        background: #f7f7f9;
        line-height: 1.6;
      }
      header,
      main,
      footer {
        max-width: 900px;
        margin: 0 auto;
        padding: 1rem 1.5rem;
      }
      header,
      footer {
        text-align: center;
      }
      section {
        background: #fff;
        padding: 1rem 1.5rem;
        margin-bottom: 1.5rem;
        border-radius: 8px;
      }
      img {
        max-width: 100%;
        height: auto;
        border-radius: 8px;
      }
      table {
        border-collapse: collapse;
        width: 100%;
      }
      th,
      td {
        border: 1px solid #ccc;
        padding: 0.6rem;
        text-align: left;
      }
      th {
        background: #2b6cb0;
        color: #fff;
      }
    </style>
  </head>
  <body>
    <header>
      <h1>AuroraBrew Smart Kettle</h1>
      <p><em>Perfect temperature. Every cup.</em></p>
    </header>
    <main>
      <section id="overview">
        <h2>Product Overview</h2>
        <figure>
          <img
            src="https://picsum.photos/seed/kettle/800/400"
            width="800"
            height="400"
            alt="Placeholder for the AuroraBrew Smart Kettle"
          />
          <figcaption>
            Placeholder image for the AuroraBrew Smart Kettle.
          </figcaption>
        </figure>
        <h3>Description</h3>
        <p>
          The <strong>AuroraBrew Smart Kettle</strong> is a 1.7-litre electric
          kettle with app control and temperature settings from 40&nbsp;°C to
          100&nbsp;°C. It keeps the water warm for up to two hours.
        </p>
        <p><a href="details.html">More product information &rarr;</a></p>
      </section>
      <section id="features">
        <h2>Key Features</h2>
        <ul>
          <li>1.7&nbsp;L capacity with double-wall insulation</li>
          <li>Precise temperature control (40-100&nbsp;°C)</li>
          <li>Keep-warm function (2 hours)</li>
          <li>Wi-Fi and smartphone app control</li>
          <li>Automatic shut-off and boil-dry protection</li>
        </ul>
      </section>
      <section id="pricing">
        <h2>Pricing and Availability</h2>
        <table>
          <caption>
            Available editions
          </caption>
          <thead>
            <tr>
              <th scope="col">Edition</th>
              <th scope="col">Colour</th>
              <th scope="col">Price</th>
              <th scope="col">Availability</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>Standard</td>
              <td>Matte black</td>
              <td>&euro;79.00</td>
              <td>In stock</td>
            </tr>
            <tr>
              <td>Premium</td>
              <td>Brushed steel</td>
              <td>&euro;99.00</td>
              <td>In stock</td>
            </tr>
            <tr>
              <td>Limited</td>
              <td>Copper</td>
              <td>&euro;129.00</td>
              <td>Pre-order (3 weeks)</td>
            </tr>
          </tbody>
        </table>
      </section>
      <section id="reviews">
        <h2>Customer Reviews</h2>
        <ul>
          <li>
            <strong>Maria L.</strong><span aria-label="5 out of 5 stars"> - ★★★★★</span> "Boils quickly and the app is
            really handy."
          </li>
          <li>
            <strong>Tom B.</strong><span aria-label="4 out of 5 stars"> - ★★★★☆</span> "Great design, I only wish the cable
            were longer."
          </li>
          <li>
            <strong>Aisha K.</strong><span aria-label="5 out of 5 stars"> - ★★★★★</span> "The 80&nbsp;°C setting makes my
            green tea taste better."
          </li>
        </ul>
      </section>
    </main>
    <footer><p>&copy; 2026 AuroraBrew (fictional company)</p></footer>
  </body>
</html>


Task 4 - products.html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Product Listing</title>
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      crossorigin="anonymous";
    />
  </head>
  <body class="bg-light">
    <div class="container py-4">
      <h1 class="mb-4 text-center">Our Products</h1>
      <div class="row g-4">
        <div class="col-sm-12 col-md-6 col-lg-4">
          <div class="card h-100 shadow-sm">
            <img
              src="https://picsum.photos/seed/p1/600/400"
              class="card-img-top"
              alt="Placeholder for
wireless headphones"
            />
            <div class="card-body">
              <h2 class="card-title h5">Wireless Headphones</h2>
              <p class="card-text">
                Over-ear Bluetooth headphones with noise cancelling and 30 hours
                of battery life.
              </p>
            </div>
          </div>
        </div>
        <div class="col-sm-12 col-md-6 col-lg-4">
          <div class="card h-100 shadow-sm">
            <img
              src="https://picsum.photos/seed/p2/600/400"
              class="card-img-top"
              alt="Placeholder for
smart watch"
            />
            <div class="card-body">
              <h2 class="card-title h5">Smart Watch</h2>
              <p class="card-text">
                Tracks steps, sleep and heart rate, with a bright always-on
                display.
              </p>
            </div>
          </div>
        </div>
        <div class="col-sm-12 col-md-6 col-lg-4">
          <div class="card h-100 shadow-sm">
            <img
              src="https://picsum.photos/seed/p3/600/400"
              class="card-img-top"
              alt="Placeholder for
portable speaker"
            />
            <div class="card-body">
              <h2 class="card-title h5">Portable Speaker</h2>
              <p class="card-text">
                Waterproof speaker with deep bass and 12 hours of playtime.
              </p>
            </div>
          </div>
        </div>
        <div class="col-sm-12 col-md-6 col-lg-4">
          <div class="card h-100 shadow-sm">
            <img
              src="https://picsum.photos/seed/p4/600/400"
              class="card-img-top"
              alt="Placeholder for
laptop backpack"
            />
            <div class="card-body">
              <h2 class="card-title h5">Laptop Backpack</h2>
              <p class="card-text">
                Water-resistant backpack with a padded compartment for 15-inch
                laptops.
              </p>
            </div>
          </div>
        </div>
        <div class="col-sm-12 col-md-6 col-lg-4">
          <div class="card h-100 shadow-sm">
            <img
              src="https://picsum.photos/seed/p5/600/400"
              class="card-img-top"
              alt="Placeholder for
mechanical keyboard"
            />
            <div class="card-body">
              <h2 class="card-title h5">Mechanical Keyboard</h2>
              <p class="card-text">
                Compact keyboard with tactile switches and customisable
                backlight.
              </p>
            </div>
          </div>
        </div>
        <div class="col-sm-12 col-md-6 col-lg-4">
          <div class="card h-100 shadow-sm">
            <img
              src="https://picsum.photos/seed/p6/600/400"
              class="card-img-top"
              alt="Placeholder for
desk lamp"
            />
            <div class="card-body">
              <h2 class="card-title h5">LED Desk Lamp</h2>
              <p class="card-text">
                Dimmable lamp with adjustable colour temperature and a USB
                charging port.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </body>
</html>


Task 5 - vue-demo.html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Vue v-model demo</title>
    <script src="https://unpkg.com/vue@3.5.13/dist/vue.global.prod.js"></script>
    <style>
      body {
        font-family: Arial, sans-serif;
        max-width: 500px;
        margin: 2rem auto;
      }
      input[type="text"] {
        padding: 0.5rem;
        width: 100%;
        box-sizing: border-box;
      }
      .preview {
        margin-top: 1rem;
        padding: 1rem;
        background: #eef;
        border-radius: 6px;
      }
    </style>
  </head>
  <body>
    <div id="app">
      <h1>Live text preview</h1>
      <label for="name">Your name:</label>
      <input
        id="name"
        type="text"
        v-model.trim="name"
        placeholder="Type here..."
      />
      <label><input type="checkbox" v-model="shout" /> SHOUT</label>
      <div class="preview">
        <p v-if="name">Hello, <strong>{{ displayName }}</strong>!</p>
        <p v-else>Please type your name.</p>
        <p>Characters: {{ name.length }}</p>
      </div>
      <button @click="name = ''">Clear</button>
    </div>
    <script>
      const { createApp, ref, computed } = Vue;
      createApp({
        setup() {
          const name = ref("");
          const shout = ref(false);
          const displayName = computed(() =>
            shout.value ? name.value.toUpperCase() : name.value,
          );
          return { name, shout, displayName };
        },
      }).mount("#app");
    </script>
  </body>
</html>
