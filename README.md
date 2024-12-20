<html lang="vi">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta name="description" content="Chất Lượng - Uy Tín - Tin Cậy." />
    <meta name="author" content="OTISStore" />
    <meta
      name="image"
      content="https://i.pinimg.com/474x/34/59/6a/34596a4db3932a3855c872c2f4833e5d.jpg"
    />
    <title>OTISStore | SHOP ACC CHẤT LƯỢNG - UY TÍN - TIN CẬY</title>
    <link
      rel="icon"
      type="image/jpeg"
      href="https://i.pinimg.com/474x/34/59/6a/34596a4db3932a3855c872c2f4833e5d.jpg"
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
        margin-top: 15px;
        display: flex;
        justify-content: center;
        width: auto;
      }

      .filter-button {
        border: none;
        width: 60px;
        background-color: #000000;
        cursor: pointer;
      }

      .icon-filter {
        width: 45px;
        height: 45px;
        border-radius: 50%;
        transition: transform 0.5s ease;
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

      .icon:active,
      .icon-filter:active {
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
        background-color: #252525;
        border-radius: 5px;
        padding: 5px;
        text-align: center;
        color: #ffffff;
        width: 170px;
        box-sizing: border-box;
      }

      .product img {
        width: 160px;
        height: auto;
        border-radius: 5px;
        object-fit: cover;
      }

      .product-name {
        font-size: 13px;
        margin: 10px 0 5px 0;
      }

      .product-price {
        font-size: 13px;
        font-weight: bold;
        color: #ff5733;
        margin: 0;
      }
    </style>
  </head>
  <div>
    <!-- Thẻ Tìm -->
    <h6 style="display: none">Tài khoản KVTK</h6>
    <h6 style="display: none">Mua acc KVTK</h6>
    <h6 style="display: none">Bán acc KVTK</h6>
    <h6 style="display: none">KVTK VIP</h6>
    <h6 style="display: none">Acc KVTK rẻ nhất</h6>
    <h6 style="display: none">KVTK full tài nguyên</h6>
    <h6 style="display: none">Mua acc KVTK giá rẻ</h6>
    <h6 style="display: none">Bán acc KVTK uy tín</h6>
    <h6 style="display: none">Tặng acc KVTK</h6>
    <h6 style="display: none">Cửa hàng acc KVTK</h6>
    <h6 style="display: none">Tài khoản Free Fire</h6>
    <h6 style="display: none">Mua acc Free Fire</h6>
    <h6 style="display: none">Bán acc Free Fire</h6>
    <h6 style="display: none">Free Fire VIP</h6>
    <h6 style="display: none">Acc Free Fire rẻ nhất</h6>
    <h6 style="display: none">Free Fire full nhân vật</h6>
    <h6 style="display: none">Acc Free Fire full skin</h6>
    <h6 style="display: none">Mua acc Free Fire giá rẻ</h6>
    <h6 style="display: none">Bán acc Free Fire uy tín</h6>
    <h6 style="display: none">Tặng acc Free Fire</h6>
    <h6 style="display: none">Cửa hàng acc Free Fire</h6>
    <h6 style="display: none">Tài khoản Clash of Clans</h6>
    <h6 style="display: none">Mua acc Clash of Clans</h6>
    <h6 style="display: none">Bán acc Clash of Clans</h6>
    <h6 style="display: none">Clash of Clans VIP</h6>
    <h6 style="display: none">Acc Clash of Clans rẻ nhất</h6>
    <h6 style="display: none">Clash of Clans full tài nguyên</h6>
    <h6 style="display: none">Acc Clash of Clans full cấp</h6>
    <h6 style="display: none">Mua acc Clash of Clans giá rẻ</h6>
    <h6 style="display: none">Bán acc Clash of Clans uy tín</h6>
    <h6 style="display: none">Tặng acc Clash of Clans</h6>
    <h6 style="display: none">Cửa hàng acc Clash of Clans</h6>
    <h6 style="display: none">Tài khoản Dragon City</h6>
    <h6 style="display: none">Mua acc Dragon City</h6>
    <h6 style="display: none">Bán acc Dragon City</h6>
    <h6 style="display: none">Dragon City VIP</h6>
    <h6 style="display: none">Acc Dragon City rẻ nhất</h6>
    <h6 style="display: none">Dragon City full rồng</h6>
    <h6 style="display: none">Acc Dragon City full tài nguyên</h6>
    <h6 style="display: none">Mua acc Dragon City giá rẻ</h6>
    <h6 style="display: none">Bán acc Dragon City uy tín</h6>
    <h6 style="display: none">Tặng acc Dragon City</h6>
    <h6 style="display: none">Cửa hàng acc Dragon City</h6>
    <h6 style="display: none">Tài khoản Liên Quân</h6>
    <h6 style="display: none">Mua acc Liên Quân</h6>
    <h6 style="display: none">Bán acc Liên Quân</h6>
    <h6 style="display: none">Liên Quân VIP</h6>
    <h6 style="display: none">Acc Liên Quân rẻ nhất</h6>
    <h6 style="display: none">Liên Quân full tướng</h6>
    <h6 style="display: none">Acc Liên Quân full skin</h6>
    <h6 style="display: none">Mua acc Liên Quân giá rẻ</h6>
    <h6 style="display: none">Bán acc Liên Quân uy tín</h6>
    <h6 style="display: none">Tặng acc Liên Quân</h6>
    <h6 style="display: none">Mua bán acc Liên Quân</h6>
    <h6 style="display: none">Cửa hàng acc Liên Quân</h6>
    <h6 style="display: none">Tài khoản</h6>
    <h6 style="display: none">Mua ac</h6>
    <h6 style="display: none">Bán acc</h6>
    <h6 style="display: none">VIP</h6>
    <h6 style="display: none">Giá rẻ</h6>
    <h6 style="display: none">Full tài nguyên</h6>
    <h6 style="display: none">Full nhân vật</h6>
    <h6 style="display: none">Full skin</h6>
    <h6 style="display: none">Cửa hàng acc</h6>
    <h6 style="display: none">Cửa hàng uy tín</h6>
    <h6 style="display: none">Tặng acc</h6>
    <h6 style="display: none">Mua bán acc</h6>
    <h6 style="display: none">Mùa mới</h6>
    <h6 style="display: none">Cao thủ</h6>
  </div>
  <body>
    <div class="header">
      <img
        src="https://i.pinimg.com/474x/34/59/6a/34596a4db3932a3855c872c2f4833e5d.jpg"
        alt="Logo"
      />
    </div>

    <div class="filter-container">
      <!--      
      <button class="filter-button" onclick="filterProducts('kvtk')">
        <img
          src="https://i.pinimg.com/474x/39/2f/3a/392f3a868a6a44adb7b4514709941445.jpg"
          alt="KVTK"
          class="icon-filter"
        />
      </button>
      <button class="filter-button" onclick="filterProducts('lq')">
        <img
          src="https://i.pinimg.com/474x/e1/14/f3/e114f324ca6461bb9b342f34292b60ad.jpg"
          alt="Liên Quân"
          class="icon-filter"
        />
      </button>
      <button class="filter-button" onclick="filterProducts('ff')">
        <img
          src="https://i.pinimg.com/474x/bc/12/70/bc1270fbfd9b08f0a98cef6ead98dc7c.jpg"
          alt="Free Fire"
          class="icon-filter"
        />
      </button>
      <button class="filter-button" onclick="filterProducts('coc')">
        <img
          src="https://i.pinimg.com/474x/8e/ae/cd/8eaecd44d50cf21bead6c2c9d540ceaf.jpg"
          alt="Clash of Clans"
          class="icon-filter"
        />
      </button>
      <button class="filter-button" onclick="filterProducts('dc')">
        <img
          src="https://i.pinimg.com/474x/4b/2f/39/4b2f39d773c23626002eb7eeaacaebd7.jpg"
          alt="Dragon City"
          class="icon-filter"
        />
      </button>
      -->
    </div>

    <div class="products" id="product-list">
      <!-- Các sản phẩm sẽ được lọc và hiển thị ở đây -->
      <div class="product kvtk">
        <img src="https://via.placeholder.com/150" alt="Vật Phẩm KVTK" />
        <p class="product-name">Vật Phẩm KVTK 1</p>
        <p class="product-price">300,000 VND</p>
      </div>
      <div class="product kvtk">
        <img src="https://via.placeholder.com/150" alt="Vật Phẩm KVTK" />
        <p class="product-name">Vật Phẩm KVTK 1</p>
        <p class="product-price">300,000 VND</p>
      </div>
      <div class="product kvtk">
        <img src="https://via.placeholder.com/150" alt="Vật Phẩm KVTK" />
        <p class="product-name">Vật Phẩm KVTK 1</p>
        <p class="product-price">300,000 VND</p>
      </div>
      <div class="product kvtk">
        <img src="https://via.placeholder.com/150" alt="Vật Phẩm KVTK" />
        <p class="product-name">Vật Phẩm KVTK 1</p>
        <p class="product-price">300,000 VND</p>
      </div>
      <div class="product kvtk">
        <img src="https://via.placeholder.com/150" alt="Vật Phẩm KVTK" />
        <p class="product-name">Vật Phẩm KVTK 1</p>
        <p class="product-price">300,000 VND</p>
      </div>
      <div class="product kvtk">
        <img src="https://via.placeholder.com/150" alt="Vật Phẩm KVTK" />
        <p class="product-name">Vật Phẩm KVTK 1</p>
        <p class="product-price">300,000 VND</p>
      </div>
      <div class="product kvtk">
        <img src="https://via.placeholder.com/150" alt="Vật Phẩm KVTK" />
        <p class="product-name">Vật Phẩm KVTK 1</p>
        <p class="product-price">300,000 VND</p>
      </div>
      <div class="product kvtk">
        <img src="https://via.placeholder.com/150" alt="Vật Phẩm KVTK" />
        <p class="product-name">Vật Phẩm KVTK 1</p>
        <p class="product-price">300,000 VND</p>
      </div>
      <div class="product kvtk">
        <img src="https://via.placeholder.com/150" alt="Vật Phẩm KVTK" />
        <p class="product-name">Vật Phẩm KVTK 1</p>
        <p class="product-price">300,000 VND</p>
      </div>
      <div class="product kvtk">
        <img src="https://via.placeholder.com/150" alt="Vật Phẩm KVTK" />
        <p class="product-name">Vật Phẩm KVTK 1</p>
        <p class="product-price">300,000 VND</p>
      </div>
      <div class="product kvtk">
        <img src="https://via.placeholder.com/150" alt="Vật Phẩm KVTK" />
        <p class="product-name">Vật Phẩm KVTK 1</p>
        <p class="product-price">300,000 VND</p>
      </div>
      <div class="product kvtk">
        <img src="https://via.placeholder.com/150" alt="Vật Phẩm KVTK" />
        <p class="product-name">Vật Phẩm KVTK 1</p>
        <p class="product-price">300,000 VND</p>
      </div>
      <!--
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
      -->
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
          var url = "https://m.me/";
          window.open(url, "_blank");
        } catch (err) {
          console.error("Không thể chuyển đến liên kết! : ", err);
          alert("Đã xảy ra lỗi. Vui lòng thử lại.");
        }
      }

      function toggleContact(contentID) {
        var content = document.getElementById(contentID);
        content.classList.toggle("active");
      }

      window.onload = function () {
        const content = document.getElementById("contact-Chatting");
        content.classList.add("active");
      };
    </script>
  </body>
</html>
