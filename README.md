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
        background-color: #000000;
        position: fixed;
        top: 0;
        left: 0;
        right: 0;
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 2.5%;
        padding: 15px;
        z-index: 1000;
      }

      .header img {
        width: 80px;
        height: auto;
        cursor: pointer;
        border-radius: 50%;
        transition: transform 1s ease;
      }

      .icon-filter {
        width: 45px;
        height: 45px;
        border-radius: 50%;
        transition: transform 1s ease;
      }

      .icon-container1,
      .icon-container2 {
        position: fixed;
        bottom: 10px;
        height: auto;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        gap: 10px;
      }

      .icon-container1 {
        left: 10px;
      }

      .icon-container2 {
        right: 10px;
      }

      .icon {
        border-radius: 50%;
        display: flex;
        cursor: pointer;
        align-items: center;
        justify-content: center;
        transition: transform 1.5s ease;
      }
      .icon:active,
      .header img:active,
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
        margin-top: 25px;
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 10px;
        width: auto;
      }

      .productss,
      .productss1,
      .productss6 {
        width: 100%;
        min-width: 480px;
        height: auto;
        padding: 5px;
        text-align: center;
        background-color: #252525;
        font-size: 14px;
      }

      .product {
        background-color: #252525;
        border-radius: 5px;
        padding: 5px;
        text-align: center;
        color: #ffffff;
        width: 150px;
        box-sizing: border-box;
        opacity: 0;
        transform: translateY(50px);
      }
      .product.hidden {
        opacity: 0;
        transform: translateY(0px);
        transition: opacity 1s ease, transform 1s ease;
      }

      .product.active {
        opacity: 1;
        transform: translateY(0);
        transition: opacity 1s ease, transform 1s ease;
      }

      .product img {
        width: 140px;
        height: 140px;
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

      .arrow-btn1,
      .arrow-btn2 {
        cursor: pointer;
        font-size: 24px;
        font-weight: bold;
        color: white;
        width: 32px;
        height: 26px;
        padding: 2px;
        background-color: #151515; /* Xanh lá cây */
        border: none;
        border-radius: 30%; /* Bo tròn nút */
        display: flex;
        text-align: center;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
        transition: background-color 0.3s, transform 0.2s;
      }

      .arrow-btn1:hover,
      .arrow-btn2:hover {
        background-color: #252525; /* Đậm hơn khi hover */
        transform: scale(1.1); /* Phóng to nhẹ khi hover */
      }

      .arrow-btn1:active,
      .arrow-btn2:active {
        transform: scale(0.95); /* Nhấn nút nhỏ lại */
      }

      /* Hiệu ứng phát sáng */
      .glow-effect {
        box-shadow: 0 0 15px 3px rgba(255, 255, 255, 0.805); /* Màu vàng phát sáng */
      }
    </style>
  </head>
  <div>
    <!-- Thẻ Tìm -->
    <h6 style="display: none">Nick KVTM</h6>
    <h6 style="display: none">Mua acc KVTM</h6>
    <h6 style="display: none">Bán acc KVTM</h6>
    <h6 style="display: none">KVTM VIP</h6>
    <h6 style="display: none">Acc KVTM rẻ nhất</h6>
    <h6 style="display: none">KVTM full tài nguyên</h6>
    <h6 style="display: none">Mua acc KVTM giá rẻ</h6>
    <h6 style="display: none">Bán acc KVTM uy tín</h6>
    <h6 style="display: none">Tặng acc KVTM</h6>
    <h6 style="display: none">Cửa hàng acc KVTM</h6>
    <h6 style="display: none">Nick Free Fire</h6>
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
    <h6 style="display: none">Nick Clash of Clans</h6>
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
    <h6 style="display: none">Nick Dragon City</h6>
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
    <h6 style="display: none">Nick Liên Quân</h6>
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
    <h6 style="display: none">Nick</h6>
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
      <div class="icon" onclick="filterProducts('kvtm')">
        <img
          src="https://i.pinimg.com/474x/39/2f/3a/392f3a868a6a44adb7b4514709941445.jpg"
          alt="Logo Khu Vườn Trên Mây"
          class="icon-filter"
        />
      </div>

      <div class="icon" onclick="filterProducts('lq')">
        <img
          src="https://i.pinimg.com/474x/e1/14/f3/e114f324ca6461bb9b342f34292b60ad.jpg"
          alt="Logo Liên Quân"
          class="icon-filter"
        />
      </div>

      <div class="icon" onclick="filterProducts('coc')">
        <img
          src="https://i.pinimg.com/474x/8e/ae/cd/8eaecd44d50cf21bead6c2c9d540ceaf.jpg"
          alt="Logo Clash of Clans"
          class="icon-filter"
        />
      </div>

      <img
        src="https://i.pinimg.com/474x/34/59/6a/34596a4db3932a3855c872c2f4833e5d.jpg"
        alt="Logo Home"
        onclick="filterProducts('all')"
      />

      <div class="icon" onclick="filterProducts('dc')">
        <img
          src="https://i.pinimg.com/474x/4b/2f/39/4b2f39d773c23626002eb7eeaacaebd7.jpg"
          alt="Logo Dragon City"
          class="icon-filter"
        />
      </div>

      <div class="icon" onclick="filterProducts('ff')">
        <img
          src="https://i.pinimg.com/474x/bc/12/70/bc1270fbfd9b08f0a98cef6ead98dc7c.jpg"
          alt="Logo Free Fire"
          class="icon-filter"
        />
      </div>

      <div class="icon" onclick="filterProducts('khac')">
        <img
          src="https://i.pinimg.com/474x/a6/6e/d5/a66ed5d684d002c477014c942c803fde.jpg"
          alt="Logo Khác"
          class="icon-filter"
        />
      </div>
    </div>

    <div class="products" id="product-list">
      <div class="productss" id="Test1" style="display: none">
        Không Có Mục Nào
      </div>
      <div class="productss" id="Test2" style="display: none">
        Không Có Mục Nào
      </div>
      <div class="productss" id="Test3" style="display: none">
        Không Có Mục Nào
      </div>
      <div class="productss" id="Test4" style="display: none">
        Không Có Mục Nào
      </div>
      <div class="productss" id="Test5" style="display: none">
        Không Có Mục Nào
      </div>
      <div class="productss" id="Test6" style="display: none">
        Không Có Mục Nào
      </div>

      <!-- Vật Phẩm Khu Vườn Trên Mây -->
      <div class="productss1" id="kvtm">Ngọc</div>
      <div class="product kvtm">
        <img src="IMG 1" alt="Ngọc Đỏ" />
        <div class="product-name">Ngọc Đỏ</div>
        <div class="product-price">Giá 1-1 VNĐ</div>
      </div>
      <div class="product kvtm">
        <img src="IMG 2" alt="Ngọc Xanh" />
        <div class="product-name">Ngọc Xanh</div>
        <div class="product-price">Giá 1-2 VNĐ</div>
      </div>
      <div class="product kvtm">
        <img src="IMG 3" alt="Ngọc Vàng" />
        <div class="product-name">Ngọc Vàng</div>
        <div class="product-price">Giá 1-3 VNĐ</div>
      </div>
      <div class="product kvtm">
        <img src="IMG 4" alt="Ngọc Cam" />
        <div class="product-name">Ngọc Cam</div>
        <div class="product-price">Giá 1-4 VNĐ</div>
      </div>
      <div class="product kvtm">
        <img src="IMG 5" alt="Ngọc Lục" />
        <div class="product-name">Ngọc Lục</div>
        <div class="product-price">Giá 1-5 VNĐ</div>
      </div>
      <div class="product kvtm">
        <img src="IMG 6" alt="Ngọc Tím" />
        <div class="product-name">Ngọc Tím</div>
        <div class="product-price">Giá 1-6 VNĐ</div>
      </div>
      <div class="product kvtm">
        <img src="IMG 7" alt="Ngọc Cầu Vòng" />
        <div class="product-name">Ngọc Cầu Vòng</div>
        <div class="product-price">Giá 1-7 VNĐ</div>
      </div>
      <div class="productss1" id="kvtm">Vật Phẩm Khác</div>
      <div class="product kvtm">
        <img src="IMG 8" alt="Vợt Vàng" />
        <div class="product-name">Vợt Vàng</div>
        <div class="product-price">Giá 1-8 VNĐ</div>
      </div>
      <div class="product kvtm">
        <img src="IMG 9" alt="Vợt Xanh" />
        <div class="product-name">Vợt Xanh</div>
        <div class="product-price">Giá 1-9 VNĐ</div>
      </div>
      <!-- Acc Khu Vườn Trên Mây -->
      <div class="productss1" id="kvtm">Acc Khu Vườn Trên Mây</div>
      <div class="product kvtm">
        <img src="IMG.1" alt="1" />
        <div class="product-name">1</div>
        <div class="product-price">Giá 2-1 VNĐ</div>
      </div>
      <!-- Acc Liên Quân Moblie -->
      <div class="product lq">
        <img src="IMG.1" alt="2" />
        <div class="product-name">2</div>
        <div class="product-price">Giá 2-1 VNĐ</div>
      </div>
      <!-- Acc Clash Of Clans -->
      <div class="product coc">
        <img src="IMG.1" alt="3" />
        <div class="product-name">3</div>
        <div class="product-price">Giá 2-1 VNĐ</div>
      </div>
      <!-- Acc Dragon City -->
      <div class="product dc">
        <img src="IMG.1" alt="4" />
        <div class="product-name">4</div>
        <div class="product-price">Giá 2-1 VNĐ</div>
      </div>
      <!-- Acc Free Fire -->
      <div class="product ff">
        <img src="IMG.1" alt="5" />
        <div class="product-name">5</div>
        <div class="product-price">Giá 2-1 VNĐ</div>
      </div>
      <!-- Thẻ Game -->
      <div class="productss6" id="khac">Thẻ Game</div>
      <div class="product khac">
        <img src="IMG.1" alt="6" />
        <div class="product-name">6</div>
        <div class="product-price">Giá 2-1 VNĐ</div>
      </div>
      <!-- Game Khác -->
      <div class="productss6" id="khac">Game Khác</div>
      <div class="product khac">
        <img src="IMG.1" alt="6" />
        <div class="product-name">6</div>
        <div class="product-price">Giá 2-1 VNĐ</div>
      </div>
    </div>

    <div class="icon-container1">
      <div id="arrowUp1" class="arrow-btn1" style="padding: 5px 0 0 0">^</div>
      <div
        id="arrowDown1"
        class="arrow-btn1"
        style="transform: rotate(180deg); padding: 5px 0 0 0"
      >
        ^
      </div>
    </div>
    <div class="icon-container1">
      <div id="arrowUp2" class="arrow-btn2" style="padding: 5px 0 0 0">^</div>
      <div
        id="arrowDown2"
        class="arrow-btn2"
        style="transform: rotate(180deg); padding: 5px 0 0 0"
      >
        ^
      </div>
    </div>

    <div class="icon-container2">
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
        const element1 = document.querySelectorAll('[id="kvtm"]');
        const element2 = document.querySelectorAll('[id="khac"]');
        const arrow1 = document.querySelectorAll(".arrow-btn1");
        const arrow2 = document.querySelectorAll(".arrow-btn2");
        const Image1 = document.querySelector('img[alt="Logo Home"]');
        const Image2 = document.querySelector(
          'img[alt="Logo Khu Vườn Trên Mây"]'
        );
        const Image3 = document.querySelector('img[alt="Logo Liên Quân"]');
        const Image4 = document.querySelector('img[alt="Logo Clash of Clans"]');
        const Image5 = document.querySelector('img[alt="Logo Dragon City"]');
        const Image6 = document.querySelector('img[alt="Logo Free Fire"]');
        const Image7 = document.querySelector('img[alt="Logo Khác"]');

        // Tìm tất cả các thẻ có class "product kvtm"
        const product1 = document.querySelectorAll(".product.kvtm");
        // Tìm thẻ có id="Test1"
        const test1 = document.getElementById("Test1");
        // Tìm tất cả các thẻ có class "product kvtm"
        const product2 = document.querySelectorAll(".product.lq");
        // Tìm thẻ có id="Test2"
        const test2 = document.getElementById("Test2");
        // Tìm tất cả các thẻ có class "product kvtm"
        const product3 = document.querySelectorAll(".product.coc");
        // Tìm thẻ có id="Test3"
        const test3 = document.getElementById("Test3");
        // Tìm tất cả các thẻ có class "product kvtm"
        const product4 = document.querySelectorAll(".product.dc");
        // Tìm thẻ có id="Test4"
        const test4 = document.getElementById("Test4");
        // Tìm tất cả các thẻ có class "product kvtm"
        const product5 = document.querySelectorAll(".product.ff");
        // Tìm thẻ có id="Test5"
        const test5 = document.getElementById("Test5");
        // Tìm tất cả các thẻ có class "product kvtm"
        const product6 = document.querySelectorAll(".product.khac");
        // Tìm thẻ có id="Test6"
        const test6 = document.getElementById("Test6");
        const delay = 100; // Thời gian delay giữa các phần tử
        let index = 0; // Dùng để tạo hiệu ứng nổi lên lần lượt

        // Hiện hoặc ẩn sản phẩm dựa trên category
        products.forEach((product) => {
          // Kiểm tra nếu sản phẩm phù hợp với bộ lọc
          if (category === "all" || product.classList.contains(category)) {
            product.style.display = "block";
            product.classList.remove("hidden"); // Loại bỏ trạng thái ẩn nếu có

            // Xóa hiệu ứng cũ và thêm lại hiệu ứng để làm mới
            product.classList.remove("active");
            setTimeout(() => {
              product.classList.add("active");
            }, delay * index++);
          } else {
            // Xử lý các sản phẩm không thuộc bộ lọc
            product.classList.remove("active");
            product.classList.add("hidden");
            product.style.display = "none";
          }

          if (category === "all") {
            Image1.classList.add("glow-effect");
          } else {
            Image1.classList.remove("glow-effect");
          }

          // Nếu category là "kvtm", hiển thị các phần tử có id="kvtm", arrowUp và arrowDown
          if (category === "kvtm") {
            element1.forEach((element1) => {
              element1.style.display = "block";
            });
            arrow1.forEach((el) => {
              el.style.display = "block";
            });
            Image2.classList.add("glow-effect");
            // Nếu không có thẻ nào với class "product kvtm"
            if (product1.length === 0) {
              test1.style.display = "block"; // Hiển thị thẻ có id="Test1"
            } else {
              test1.style.display = "none"; // Ẩn thẻ có id="Test1"
            }
          } else {
            // Ngược lại, ẩn các phần tử có id="kvtm", arrowUp1 và arrowDown1
            element1.forEach((element) => {
              element.style.display = "none";
            });
            arrow1.forEach((el) => {
              el.style.display = "none";
            });
            Image2.classList.remove("glow-effect");
            test1.style.display = "none"; // Ẩn thẻ có id="Test1"
          }

          if (category === "lq") {
            Image3.classList.add("glow-effect");
            // Nếu không có thẻ nào với class "product lq"
            if (product2.length === 0) {
              test2.style.display = "block"; // Hiển thị thẻ có id="Test2"
            } else {
              test2.style.display = "none"; // Ẩn thẻ có id="Test2"
            }
          } else {
            Image3.classList.remove("glow-effect");
            test2.style.display = "none"; // Ẩn thẻ có id="Test2"
          }

          if (category === "coc") {
            Image4.classList.add("glow-effect");
            // Nếu không có thẻ nào với class "product lq"
            if (product3.length === 0) {
              test3.style.display = "block"; // Hiển thị thẻ có id="Test3"
            } else {
              test3.style.display = "none"; // Ẩn thẻ có id="Test3"
            }
          } else {
            Image4.classList.remove("glow-effect");
            test3.style.display = "none"; // Ẩn thẻ có id="Test3"
          }

          if (category === "dc") {
            Image5.classList.add("glow-effect");
            // Nếu không có thẻ nào với class "product lq"
            if (product4.length === 0) {
              test4.style.display = "block"; // Hiển thị thẻ có id="Test4"
            } else {
              test4.style.display = "none"; // Ẩn thẻ có id="Test4"
            }
          } else {
            Image5.classList.remove("glow-effect");
            test4.style.display = "none"; // Ẩn thẻ có id="Test4"
          }

          if (category === "ff") {
            Image6.classList.add("glow-effect");
            // Nếu không có thẻ nào với class "product lq"
            if (product5.length === 0) {
              test5.style.display = "block"; // Hiển thị thẻ có id="Test5"
            } else {
              test5.style.display = "none"; // Ẩn thẻ có id="Test5"
            }
          } else {
            Image6.classList.remove("glow-effect");
            test5.style.display = "none"; // Ẩn thẻ có id="Test5"
          }

          // Nếu category là "khac", hiển thị các phần tử có id="khac", arrowUp2 và arrowDown2
          if (category === "khac") {
            element2.forEach((element) => {
              element.style.display = "block";
            });
            arrow2.forEach((el) => {
              el.style.display = "block";
            });
            Image7.classList.add("glow-effect");
            // Nếu không có thẻ nào với class "product lq"
            if (product6.length === 0) {
              test6.style.display = "block"; // Hiển thị thẻ có id="Test6"
            } else {
              test6.style.display = "none"; // Ẩn thẻ có id="Test6"
            }
          } else {
            // Ngược lại, ẩn các phần tử có id="kvtm", arrowUp và arrowDown
            element2.forEach((element) => {
              element.style.display = "none";
            });
            arrow2.forEach((el) => {
              el.style.display = "none";
            });
            Image7.classList.remove("glow-effect");
            test6.style.display = "none"; // Ẩn thẻ có id="Test6"
          }
        });
      }

      // Gọi function filterProducts với "all" để hiển thị tất cả sản phẩm khi DOM đã tải
      document.addEventListener("DOMContentLoaded", () => {
        filterProducts("all");
      });

      let currentIndex1 = 0; // Vị trí phần tử hiện tại

      document.getElementById("arrowUp1").addEventListener("click", () => {
        const products = document.querySelectorAll(".productss1");
        if (currentIndex1 > 0) {
          currentIndex1--;
          navigateTo(products, currentIndex1);
        }
      });

      document.getElementById("arrowDown1").addEventListener("click", () => {
        const products = document.querySelectorAll(".productss1");
        if (currentIndex1 < products.length - 1) {
          currentIndex1++;
          navigateTo(products, currentIndex1);
        }
      });

      let currentIndex2 = 0; // Vị trí phần tử hiện tại

      document.getElementById("arrowUp2").addEventListener("click", () => {
        const productss = document.querySelectorAll(".productss6");
        if (currentIndex2 > 0) {
          currentIndex2--;
          navigateTo(productss, currentIndex2);
        }
      });

      document.getElementById("arrowDown2").addEventListener("click", () => {
        const productss = document.querySelectorAll(".productss6");
        if (currentIndex2 < productss.length - 1) {
          currentIndex2++;
          navigateTo(productss, currentIndex2);
        }
      });

      function navigateTo(elements, index) {
        elements[index].scrollIntoView({ behavior: "smooth", block: "center" });

        // Làm nổi bật phần tử hiện tại
        elements.forEach((el, i) => {
          if (i === index) {
            el.style.background = "#555555";
          } else {
            el.style.background = "#252525";
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
