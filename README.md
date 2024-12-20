<html lang="vi">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta name="description" content="Chất Lượng, Uy Tín, Tin Cậy." />
    <meta name="author" content="OTISStore" />
    <meta
      name="image"
      content="https://i.pinimg.com/474x/ea/24/e1/ea24e1a0ed40857020ab39336b9fc78c.jpg"
    />
    <title>OTISStore</title>
    <link
      rel="icon"
      type="image/jpeg"
      href="https://i.pinimg.com/474x/6d/ed/ac/6dedac7e01c34c37f226b05591ccde2e.jpg"
    />
    <style>
      body {
        font-family: Arial, sans-serif;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: flex-start;
        background-color: #000000;
        color: #ffffff;
        width: auto;
        user-select: none;
      }

      .header {
        background-color: #151515;
        position: fixed;
        top: 0;
        left: 0;
        right: 0;
        display: flex;
        align-items: center;
        justify-content: center;
        padding: 10px;
        z-index: 1000;
      }

      .header img {
        width: 90px;
        height: auto;
        border-radius: 50%;
        object-fit: cover;
      }

      .filter-container {
        margin-top: 10px;
        display: flex;
        justify-content: center;
        padding: 5px;
        width: auto;
      }

      .filter-button {
        border: none;
        width: auto;
        background-color: #000000;
        cursor: pointer;
      }

      .icon-filter {
        width: 42px;
        height: 42px;
        border-radius: 50%;
      }

      .icon-container {
        position: fixed;
        bottom: 10px;
        right: 10px;
        height: auto;
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 10px;
        cursor: pointer;
      }

      .icon {
        border-radius: 50%;
        display: flex;
        align-items: center;
        justify-content: center;
        transition: transform 0.5s ease;
      }

      .icon:active {
        transform: scale(1.2);
      }

      .icon img {
        width: 45px;
        height: 45px;
        object-fit: cover;
        border-radius: 50%;
      }

      .contact-Chatting {
        position: fixed;
        color: white;
        background-color: #202020;
        border-radius: 10px;
        padding: 10px;
        width: 95%;
        max-width: 400px;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%) scale(0.9);
        opacity: 0;
        transition: transform 0.3s ease, opacity 0.3s ease;
        z-index: 999;
      }

      .contact-Chatting.active {
        transform: translate(-50%, -50%) scale(1);
        opacity: 1;
      }

      .products {
        padding: 10px;
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 10px;
        width: auto;
      }

      .product {
        background-color: #b8aeae;
        border-radius: 10px;
        padding: 5px;
        text-align: center;
        color: #ffffff;
        width: 160px;
        box-sizing: border-box;
      }

      .product img {
        width: 100%;
        height: auto;
        border-radius: 10px;
        object-fit: cover;
      }

      .product-name {
        font-size: 13px;
        margin: 10px 0 0 0;
      }

      .product-price {
        font-size: 13px;
        font-weight: bold;
        color: #ff5733;
        margin: 10px 0 0 0;
      }
    </style>
  </head>

  <body>
    <div class="header">
      <img
        src="https://i.pinimg.com/474x/ea/24/e1/ea24e1a0ed40857020ab39336b9fc78c.jpg"
        alt="Logo"
      />
    </div>

    <div class="filter-container">
      <button class="filter-button" onclick="filterProducts('kvtk')">
        <img
          src="https://via.placeholder.com/50"
          alt="KVTK"
          class="icon-filter"
        />
      </button>
      <button class="filter-button" onclick="filterProducts('lq')">
        <img
          src="https://via.placeholder.com/24"
          alt="Liên Quân"
          class="icon-filter"
        />
      </button>
      <button class="filter-button" onclick="filterProducts('ff')">
        <img
          src="https://via.placeholder.com/24"
          alt="Free Fire"
          class="icon-filter"
        />
      </button>
      <button class="filter-button" onclick="filterProducts('coc')">
        <img
          src="https://via.placeholder.com/24"
          alt="Clash of Clans"
          class="icon-filter"
        />
      </button>
      <button class="filter-button" onclick="filterProducts('dc')">
        <img
          src="https://via.placeholder.com/24"
          alt="Dragon City"
          class="icon-filter"
        />
      </button>
    </div>

    <div class="products" id="product-list">
      <!-- Các sản phẩm sẽ được lọc và hiển thị ở đây -->
      <div class="product kvtk">
        <img src="https://via.placeholder.com/150" alt="Vật Phẩm KVTK" />
        <p class="product-name">Vật Phẩm KVTK 1</p>
        <p class="product-price">300,000 VND</p>
      </div>
      <div class="product lq">
        <img src="https://via.placeholder.com/150" alt="Tài Khoản Liên Quân" />
        <p class="product-name">Tài Khoản Liên Quân 1</p>
        <p class="product-price">500,000 VND</p>
      </div>
      <div class="product ff">
        <img src="https://via.placeholder.com/150" alt="Free Fire" />
        <p class="product-name">Tài Khoản Free Fire 1</p>
        <p class="product-price">600,000 VND</p>
      </div>
      <div class="product coc">
        <img src="https://via.placeholder.com/150" alt="Clash of Clans" />
        <p class="product-name">Tài Khoản Clash of Clans 1</p>
        <p class="product-price">450,000 VND</p>
      </div>
      <div class="product dc">
        <img src="https://via.placeholder.com/150" alt="Dragon City" />
        <p class="product-name">Tài Khoản Dragon City 1</p>
        <p class="product-price">550,000 VND</p>
      </div>
    </div>

    <div class="icon-container">
      <div class="icon" onclick="toggleContact('contact-Chatting')">
        <img
          src="https://i.pinimg.com/474x/e8/9b/26/e89b26c7cc12836e637c7ce3ea36c9bb.jpg"
          alt="Chatting"
        />
      </div>
      <div class="contact-Chatting" id="contact-Chatting">
        <div style="text-align: center; width: 100%">
          <div style="font-size: 18px; font-weight: 600">
            Thông Tin Chi Tiết!
          </div>
          <button
            style="
              position: absolute;
              right: 5px;
              top: 3px;
              background-color: #202020;
              color: white;
              border: none;
            "
            onclick="toggleContact('contact-Chatting')"
          >
            x
          </button>
          <button
            class="order"
            style="
              position: absolute;
              left: 5px;
              top: 3px;
              font-size: 14px;
              background-color: #202020;
              color: white;
              border: none;
            "
            onclick="sendMessageWithClipboard('');"
          >
            Liên Hệ
          </button>
        </div>
        <p style="text-align: center; font-size: 14px">
          ❤️ OTISStore - Chân Thành Cảm Ơn Quý Khách! ❤️
        </p>
      </div>
    </div>

    <script>
      function filterProducts(category) {
        const products = document.querySelectorAll(".product");
        products.forEach((product) => {
          if (product.classList.contains(category) || category === "all") {
            product.style.display = "block";
          } else {
            product.style.display = "none";
          }
        });
      }

      function sendMessageWithClipboard() {
        try {
          const url = "https://m.me/";
          window.open(url, "_blank");
        } catch (err) {
          console.error("Không thể chuyển đến liên kết! : ", err);
          alert("Đã xảy ra lỗi. Vui lòng thử lại.");
        }
      }

      function toggleContact(contentID) {
        const content = document.getElementById(contentID);
        content.classList.toggle("active");
      }

      window.onload = function () {
        const content = document.getElementById("contact-Chatting");
        content.classList.add("active");
      };
    </script>
    
  </body>
</html>
