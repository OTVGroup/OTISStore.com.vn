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
        cursor: pointer;
        border-radius: 50%;
        transition: transform 1s ease;
      }

      .container1,
      .container2 {
        position: fixed;
        bottom: 10px;
        height: auto;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        gap: 10px;
      }

      .container1 {
        left: 10px;
      }

      .container2 {
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
      .header img:active {
        transform: scale(1.2);
      }

      .icon img {
        width: 40px;
        height: 40px;
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
        margin-top: 20px;
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 10px;
        width: auto;
      }

      .productss,
      .productss0,
      .productss1,
      .productss6 {
        width: 100%;
        min-width: 320px;
        height: auto;
        padding: 5px;
        text-align: center;
        background-color: #252525;
        font-size: 14px;
      }

      .productss0 {
        background-color: #000;
        height: 0;
      }

      .product {
        background-color: #252525;
        border-radius: 5px;
        padding: 5px;
        text-align: center;
        color: #ffffff;
        width: auto;
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

      .product-img1,
      .product-img2 {
        position: relative;
        display: inline-block;
        border-radius: 5px;
      }

      .product-no {
        position: absolute;
        transform: translate(0, -20px); /* Căn giữa theo chiều ngang và dọc */
        width: 100%;
        height: 14px;
        text-align: center;
        justify-content: center;
        border-radius: 0 0 5px 5px;
        background-color: #b2b2b285;
        font-size: 11px;
      }

      .product-img1 img {
        width: 80px;
        height: 80px;
        border-radius: 5px;
        object-fit: cover;
      }
      .product-img2 img {
        width: 140px;
        height: 140px;
        border-radius: 5px;
        object-fit: cover;
      }

      .product-name {
        font-size: 11px;
        margin-top: 5px;
      }

      .product-price {
        font-size: 11px;
        font-weight: bold;
        color: #ff5733;
        margin-top: 3px;
      }

      .arrow-btn1,
      .arrow-btn2 {
        cursor: pointer;
        font-size: 28px;
        font-weight: bold;
        color: white;
        width: 40px;
        height: 28px;
        background-color: #00000000;
        border-radius: 3px;
        display: flex;
        text-align: center;
        transition: background-color 0.5s, transform 0.5s;
      }

      .arrow-btn1:active,
      .arrow-btn2:active {
        box-shadow: 0 0 5px 5px rgba(255, 255, 255, 0.2);
      }

      /* Hiệu ứng phát sáng */
      .glow-effect {
        box-shadow: 0 0 15px 3px rgba(255, 255, 255, 0.805); /* Màu vàng phát sáng */
      }

      .home-button {
        display: inline-flex;
        align-items: center;
        position: fixed;
        justify-content: center;
        top: 0;
        right: 0;
        width: 24px;
        height: 24px;
        z-index: 1001;
        background-color: #2e2e2e;
        border-radius: 0% 0% 0% 10%;
      }

      .home-button a {
        color: white;
        bottom: 1px;
        text-decoration: none;
        font-size: 24px;
      }
      .home-button:hover {
        background-color: #858585;
        transform: scale(1.1);
      }
    </style>
  </head>
  <div style="display: none">
    <!-- Thẻ Tìm -->
    <h6>Nick KVTM</h6>
    <h6>Mua acc KVTM</h6>
    <h6>Bán acc KVTM</h6>
    <h6>KVTM VIP</h6>
    <h6>Acc KVTM rẻ nhất</h6>
    <h6>KVTM full tài nguyên</h6>
    <h6>Mua acc KVTM giá rẻ</h6>
    <h6>Bán acc KVTM uy tín</h6>
    <h6>Tặng acc KVTM</h6>
    <h6>Cửa hàng acc KVTM</h6>
    <h6>Nick Free Fire</h6>
    <h6>Mua acc Free Fire</h6>
    <h6>Bán acc Free Fire</h6>
    <h6>Free Fire VIP</h6>
    <h6>Acc Free Fire rẻ nhất</h6>
    <h6>Free Fire full nhân vật</h6>
    <h6>Acc Free Fire full skin</h6>
    <h6>Mua acc Free Fire giá rẻ</h6>
    <h6>Bán acc Free Fire uy tín</h6>
    <h6>Tặng acc Free Fire</h6>
    <h6>Cửa hàng acc Free Fire</h6>
    <h6>Nick Clash of Clans</h6>
    <h6>Mua acc Clash of Clans</h6>
    <h6>Bán acc Clash of Clans</h6>
    <h6>Clash of Clans VIP</h6>
    <h6>Acc Clash of Clans rẻ nhất</h6>
    <h6>Clash of Clans full tài nguyên</h6>
    <h6>Acc Clash of Clans full cấp</h6>
    <h6>Mua acc Clash of Clans giá rẻ</h6>
    <h6>Bán acc Clash of Clans uy tín</h6>
    <h6>Tặng acc Clash of Clans</h6>
    <h6>Cửa hàng acc Clash of Clans</h6>
    <h6>Nick Dragon City</h6>
    <h6>Mua acc Dragon City</h6>
    <h6>Bán acc Dragon City</h6>
    <h6>Dragon City VIP</h6>
    <h6>Acc Dragon City rẻ nhất</h6>
    <h6>Dragon City full rồng</h6>
    <h6>Acc Dragon City full tài nguyên</h6>
    <h6>Mua acc Dragon City giá rẻ</h6>
    <h6>Bán acc Dragon City uy tín</h6>
    <h6>Tặng acc Dragon City</h6>
    <h6>Cửa hàng acc Dragon City</h6>
    <h6>Nick Liên Quân</h6>
    <h6>Mua acc Liên Quân</h6>
    <h6>Bán acc Liên Quân</h6>
    <h6>Liên Quân VIP</h6>
    <h6>Acc Liên Quân rẻ nhất</h6>
    <h6>Liên Quân full tướng</h6>
    <h6>Acc Liên Quân full skin</h6>
    <h6>Mua acc Liên Quân giá rẻ</h6>
    <h6>Bán acc Liên Quân uy tín</h6>
    <h6>Tặng acc Liên Quân</h6>
    <h6>Mua bán acc Liên Quân</h6>
    <h6>Cửa hàng acc Liên Quân</h6>
    <h6>Tài khoản</h6>
    <h6>Nick</h6>
    <h6>Mua ac</h6>
    <h6>Bán acc</h6>
    <h6>VIP</h6>
    <h6>Giá rẻ</h6>
    <h6>Full tài nguyên</h6>
    <h6>Full nhân vật</h6>
    <h6>Full skin</h6>
    <h6>Cửa hàng acc</h6>
    <h6>Cửa hàng uy tín</h6>
    <h6>Tặng acc</h6>
    <h6>Mua bán acc</h6>
    <h6>Mùa mới</h6>
    <h6>Cao thủ</h6>
  </div>
  <body>
    <div class="home-button"><a href="#" title="Go to Home">&#8962;</a></div>
    <div class="header">
      <img
        src="https://i.pinimg.com/474x/39/2f/3a/392f3a868a6a44adb7b4514709941445.jpg"
        alt="Logo Khu Vườn Trên Mây"
        style="width: 40px; height: 40px"
        onclick="filterProducts('kvtm')"
      />

      <img
        src="https://i.pinimg.com/474x/e1/14/f3/e114f324ca6461bb9b342f34292b60ad.jpg"
        alt="Logo Liên Quân"
        style="width: 40px; height: 40px"
        onclick="filterProducts('lq')"
      />

      <img
        src="https://i.pinimg.com/474x/8e/ae/cd/8eaecd44d50cf21bead6c2c9d540ceaf.jpg"
        alt="Logo Clash of Clans"
        style="width: 40px; height: 40px"
        onclick="filterProducts('coc')"
      />

      <img
        src="https://i.pinimg.com/474x/34/59/6a/34596a4db3932a3855c872c2f4833e5d.jpg"
        alt="Logo Home"
        style="border: 2px solid rgb(255, 255, 255); width: 60px; height: 60px"
        onclick="filterProducts('all')"
      />

      <img
        src="https://i.pinimg.com/474x/4b/2f/39/4b2f39d773c23626002eb7eeaacaebd7.jpg"
        alt="Logo Dragon City"
        style="width: 40px; height: 40px"
        onclick="filterProducts('dc')"
      />

      <img
        src="https://i.pinimg.com/474x/bc/12/70/bc1270fbfd9b08f0a98cef6ead98dc7c.jpg"
        alt="Logo Free Fire"
        style="width: 40px; height: 40px"
        onclick="filterProducts('ff')"
      />

      <img
        src="https://i.pinimg.com/474x/a6/6e/d5/a66ed5d684d002c477014c942c803fde.jpg"
        alt="Logo Khác"
        style="width: 40px; height: 40px"
        onclick="filterProducts('khac')"
      />
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
      <div class="productss1" id="kvtm">Sấy</div>
      <!-- 15 -->
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/21/4a/df/214adf99940201d44be9846e9285232e.jpg"
            alt="Hồng Sấy"
          />
          <div class="product-no">1</div>
        </div>
        <div class="product-name">Hồng Sấy</div>
        <div class="product-price">1đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/c4/a7/cc/c4a7ccf71acdb6aec54daa5e6d71fb6a.jpg"
            alt="Táo Sấy"
          />
          <div class="product-no">2</div>
        </div>
        <div class="product-name">Táo Sấy</div>
        <div class="product-price">2đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/44/d5/db/44d5db02f58245d0eaa29ac8f5ea8ea4.jpg"
            alt="Oải Hương"
          />
          <div class="product-no">3</div>
        </div>
        <div class="product-name">Oải Hương</div>
        <div class="product-price">3đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/d1/36/ac/d136ac2f9613e3c9b7613d6eea3153c1.jpg"
            alt="Dừa Sấy"
          />
          <div class="product-no">4</div>
        </div>
        <div class="product-name">Dừa Sấy</div>
        <div class="product-price">4đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/fe/37/47/fe3747ac5fb68ea29eaacb7335194a2a.jpg"
            alt="Hạt Dưa"
          />
          <div class="product-no">5</div>
        </div>
        <div class="product-name">Hạt Dưa</div>
        <div class="product-price">5đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/3a/cc/0f/3acc0fff30a54670af357237b0fc897d.jpg"
            alt="Trà Sấy"
          />
          <div class="product-no">6</div>
        </div>
        <div class="product-name">Trà Sấy</div>
        <div class="product-price">6đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/3c/63/59/3c6359a8032cef802b8be4968941c97e.jpg"
            alt="Mít Sấy"
          />
          <div class="product-no">7</div>
        </div>
        <div class="product-name">Mít Sấy</div>
        <div class="product-price">7đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/44/48/b1/4448b17a17ed37068a9b1dd5f07f85f5.jpg"
            alt="Dứa Sấy"
          />
          <div class="product-no">8</div>
        </div>
        <div class="product-name">Dứa Sấy</div>
        <div class="product-price">8đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/d9/b3/b1/d9b3b10cdb34e0b97cd8b6b7b08c9c20.jpg"
            alt="Xoài Sấy"
          />
          <div class="product-no">9</div>
        </div>
        <div class="product-name">Xoài Sấy</div>
        <div class="product-price">9đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/bf/ca/31/bfca3109ec4d1139edd23d6cfa892064.jpg"
            alt="Lài Sấy"
          />
          <div class="product-no">10</div>
        </div>
        <div class="product-name">Lài Sấy</div>
        <div class="product-price">10đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/1a/55/8a/1a558a5de7056e3e92255d782146282c.jpg"
            alt="Cúc Sấy"
          />
          <div class="product-no">11</div>
        </div>
        <div class="product-name">Cúc Sấy</div>
        <div class="product-price">11đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/db/dc/f3/dbdcf339aca99d0f379dd7b832b176c5.jpg"
            alt="Hạt Sen"
          />
          <div class="product-no">12</div>
        </div>
        <div class="product-name">Hạt Sen</div>
        <div class="product-price">12đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/77/19/34/77193423f65343aef01b697688c12337.jpg"
            alt="Nho Sấy"
          />
          <div class="product-no">13</div>
        </div>
        <div class="product-name">Nho Sấy</div>
        <div class="product-price">13đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/f0/7f/5c/f07f5c64972ae0a6b36e68852dbae018.jpg"
            alt="Hạt H.Dương"
          />
          <div class="product-no">14</div>
        </div>
        <div class="product-name">Hạt H.Dương</div>
        <div class="product-price">14đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/41/87/22/418722c2007d0dd224d1445fb03eec31.jpg"
            alt="Việt Quất"
          />
          <div class="product-no">15</div>
        </div>
        <div class="product-name">Việt Quất</div>
        <div class="product-price">15đ</div>
      </div>
      <div class="productss1" id="kvtm">Nước Ép</div>
      <!-- 11 -->
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/24/89/30/2489301bc6cfbf6c06117e6b2bc18d88.jpg"
            alt="Nước Táo"
          />
          <div class="product-no">1</div>
        </div>
        <div class="product-name">Nước Táo</div>
        <div class="product-price">1đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/31/7b/00/317b00880e894b49e97d85877c2b0112.jpg"
            alt="Nước Tinh Khiết"
          />
          <div class="product-no">2</div>
        </div>
        <div class="product-name">Nước Tinh Khiết</div>
        <div class="product-price">2đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/4d/3d/ce/4d3dce43fc370f7b88dd83a2b79898c8.jpg"
            alt="Nước Dừa"
          />
          <div class="product-no">3</div>
        </div>
        <div class="product-name">Nước Dừa</div>
        <div class="product-price">3đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/f0/ca/f1/f0caf199abebfe35629b35424ddb58c1.jpg"
            alt="Nước Chanh"
          />
          <div class="product-no">4</div>
        </div>
        <div class="product-name">Nước Chanh</div>
        <div class="product-price">4đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/df/40/b0/df40b07fd8795ca1bd668510bf916401.jpg"
            alt="Nước Dưa Hấu"
          />
          <div class="product-no">5</div>
        </div>
        <div class="product-name">Nước Dưa Hấu</div>
        <div class="product-price">5đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/d3/ee/32/d3ee320098453df46b882e405e4a1b5f.jpg"
            alt="Sinh Tố Mít"
          />
          <div class="product-no">6</div>
        </div>
        <div class="product-name">Sinh Tố Mít</div>
        <div class="product-price">6đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/f3/15/ae/f315aeb25f643210a486c2cad55a27cc.jpg"
            alt="Nước Dứa"
          />
          <div class="product-no">7</div>
        </div>
        <div class="product-name">Nước Dứa</div>
        <div class="product-price">7đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/20/f4/2d/20f42d7c2acac57126e5806054068d53.jpg"
            alt="Sinh Tố Xoài"
          />
          <div class="product-no">8</div>
        </div>
        <div class="product-name">Sinh Tố Xoài</div>
        <div class="product-price">8đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/fb/c9/ae/fbc9ae57da21c3821e3b45741a803d5d.jpg"
            alt="Nước Nho"
          />
          <div class="product-no">9</div>
        </div>
        <div class="product-name">Nước Nho</div>
        <div class="product-price">9đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/ed/36/f0/ed36f00669c8617fcc2129ddaa8edd9f.jpg"
            alt="Nước Việt Quất"
          />
          <div class="product-no">10</div>
        </div>
        <div class="product-name">Nước Việt Quất</div>
        <div class="product-price">10đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/a5/6a/7d/a56a7dfa4d5453650c2af919e4ff2806.jpg"
            alt="Nước Dâu"
          />
          <div class="product-no">11</div>
        </div>
        <div class="product-name">Nước Dâu</div>
        <div class="product-price">11đ</div>
      </div>
      <div class="productss1" id="kvtm">Vải</div>
      <!-- 8 -->
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/34/de/0a/34de0a0b909827f42dc53d00e0b8760d.jpg"
            alt="Vải Đỏ"
          />
          <div class="product-no">1</div>
        </div>
        <div class="product-name">Vải Đỏ</div>
        <div class="product-price">1đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/9c/e8/53/9ce853e70a0fc549d85bc38662d55540.jpg"
            alt="Vải Vàng"
          />
          <div class="product-no">1</div>
        </div>
        <div class="product-name">Vải Vàng</div>
        <div class="product-price">2đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/04/4f/04/044f04650a308ece32d597a7a7a435cf.jpg"
            alt="Vải Tím"
          />
          <div class="product-no">1</div>
        </div>
        <div class="product-name">Vải Tím</div>
        <div class="product-price">3đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/e1/3a/29/e13a2958d046f137fbaa8f4c8efca934.jpg"
            alt="Vải Xanh Lục"
          />
          <div class="product-no">1</div>
        </div>
        <div class="product-name">Vải Xanh Lục</div>
        <div class="product-price">4đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/27/f1/da/27f1da5a75e6c469c5ff9f0bc67bf5ae.jpg"
            alt="Vải Trắng"
          />
          <div class="product-no">1</div>
        </div>
        <div class="product-name">Vải Trắng</div>
        <div class="product-price">5đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/15/f4/70/15f470c482380b1650fcc500939c045a.jpg"
            alt="Vải Hồng"
          />
          <div class="product-no">1</div>
        </div>
        <div class="product-name">Vải Hồng</div>
        <div class="product-price">6đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/67/56/9e/67569e1d046ca36d4b09003802c29ea0.jpg"
            alt="Vải Đen"
          />
          <div class="product-no">1</div>
        </div>
        <div class="product-name">Vải Đen</div>
        <div class="product-price">7đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/5e/12/b7/5e12b7c896ab6d647368c945befc27d1.jpg"
            alt="Vải Xanh Biển"
          />
          <div class="product-no">1</div>
        </div>
        <div class="product-name">Vải Xanh Biển</div>
        <div class="product-price">8đ</div>
      </div>
      <div class="productss1" id="kvtm">Ngọc</div>
      <!-- 7 -->
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/cd/d2/04/cdd204f58ab6b093a94617f692f91398.jpg"
            alt="Ngọc Đỏ"
          />
          <div class="product-no">1</div>
        </div>
        <div class="product-name">Ngọc Đỏ</div>
        <div class="product-price">1đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/00/99/27/009927a35caced1eaa1598e8d5149f32.jpg"
            alt="Ngọc Xanh"
          />
          <div class="product-no">1</div>
        </div>
        <div class="product-name">Ngọc Xanh</div>
        <div class="product-price">2đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/bc/19/9c/bc199c0f7626e3ab3f6cc0babf75086e.jpg"
            alt="Ngọc Vàng"
          />
          <div class="product-no">1</div>
        </div>
        <div class="product-name">Ngọc Vàng</div>
        <div class="product-price">3đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/a7/ef/ca/a7efca33165c810e1c81f31273fd50db.jpg"
            alt="Ngọc Tím"
          />
          <div class="product-no">1</div>
        </div>
        <div class="product-name">Ngọc Tím</div>
        <div class="product-price">4đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/fa/4c/f6/fa4cf62cb997beb2d999646501971b08.jpg"
            alt="Ngọc Cam"
          />
          <div class="product-no">1</div>
        </div>
        <div class="product-name">Ngọc Cam</div>
        <div class="product-price">5đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/b0/37/3b/b0373bb243f8aaaa0c6e16bda1af4d68.jpg"
            alt="Ngọc Lục"
          />
          <div class="product-no">1</div>
        </div>
        <div class="product-name">Ngọc Lục</div>
        <div class="product-price">6đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/53/5f/04/535f041f4fda0806ad0cdacbe2a8c1ac.jpg"
            alt="Ngọc Cầu Vòng"
          />
          <div class="product-no">1</div>
        </div>
        <div class="product-name">Ngọc Cầu Vòng</div>
        <div class="product-price">7đ</div>
      </div>
      <div class="productss1" id="kvtm">Tinh Dầu</div>
      <!-- 8 -->
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/17/bb/c3/17bbc3a474173a2a3606b5c52a09b1d2.jpg"
            alt="TD Hoa Hông"
          />
          <div class="product-no">1</div>
        </div>
        <div class="product-name">TD Hoa Hông</div>
        <div class="product-price">1đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/95/6a/8b/956a8b1f1615d9ad44ec8f17bd932a99.jpg"
            alt="TD Táo"
          />
          <div class="product-no">2</div>
        </div>
        <div class="product-name">TD Táo</div>
        <div class="product-price">2đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/a8/d0/59/a8d059c90b1c0317e6a3b6e016eb4337.jpg"
            alt="TD Oải Hương"
          />
          <div class="product-no">3</div>
        </div>
        <div class="product-name">TD Oải Hương</div>
        <div class="product-price">3đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/77/47/92/774792634d8e275cfef841cdf916f4b9.jpg"
            alt="TD Dừa"
          />
          <div class="product-no">4</div>
        </div>
        <div class="product-name">TD Dừa</div>
        <div class="product-price">4đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/5a/7d/25/5a7d2535ebc04bc9c0995b23936e9edd.jpg"
            alt="TD Chanh"
          />
          <div class="product-no">5</div>
        </div>
        <div class="product-name">TD Chanh</div>
        <div class="product-price">5đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/63/8f/a0/638fa0d5611df72ebdfeea0eb0314502.jpg"
            alt="TD Sen"
          />
          <div class="product-no">6</div>
        </div>
        <div class="product-name">TD Sen</div>
        <div class="product-price">6đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/37/7f/5a/377f5a7747c0f94595338dcccdf28020.jpg"
            alt="TD Việt Quất"
          />
          <div class="product-no">7</div>
        </div>
        <div class="product-name">TD Việt Quất</div>
        <div class="product-price">7đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/42/34/cc/4234cc123fe4c6bb98cade9ea1e81e5f.jpg"
            alt="TD Dâu"
          />
          <div class="product-no">8</div>
        </div>
        <div class="product-name">TD Dâu</div>
        <div class="product-price">8đ</div>
      </div>
      <div class="productss1" id="kvtm">Trà</div>
      <!-- 9 -->
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/14/82/c8/1482c876db5b1feb655e3153cc70f2a5.jpg"
            alt="Trà Hoa Hồng"
          />
          <div class="product-no">1</div>
        </div>
        <div class="product-name">Trà Hoa Hồng</div>
        <div class="product-price">1đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/11/f5/8e/11f58e166036ba5945e000548b05c19a.jpg"
            alt="Trà Đá"
          />
          <div class="product-no">2</div>
        </div>
        <div class="product-name">Trà Đá</div>
        <div class="product-price">2đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/b5/dd/fa/b5ddfa07ceb81f1d59e12235a982a003.jpg"
            alt="Trà Táo"
          />
          <div class="product-no">3</div>
        </div>
        <div class="product-name">Trà Táo</div>
        <div class="product-price">3đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/80/5c/88/805c88803e4c4fb07f3c5bb67476ce74.jpg"
            alt="Trà Chanh"
          />
          <div class="product-no">4</div>
        </div>
        <div class="product-name">Trà Chanh</div>
        <div class="product-price">4đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/da/e8/b3/dae8b3a5ebedb5fcbbf20d45837a9f82.jpg"
            alt="Trà Nho"
          />
          <div class="product-no">5</div>
        </div>
        <div class="product-name">Trà Nho</div>
        <div class="product-price">5đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/2b/18/db/2b18db2f31c5c7a354057237b104e6ec.jpg"
            alt="Trà Hoa Cúc"
          />
          <div class="product-no">6</div>
        </div>
        <div class="product-name">Trà Hoa Cúc</div>
        <div class="product-price">6đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/6b/09/56/6b09567b8140b76c3d6841788ce34c8d.jpg"
            alt="Trà Trái Cây"
          />
          <div class="product-no">7</div>
        </div>
        <div class="product-name">Trà Trái Cây</div>
        <div class="product-price">7đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/3d/d0/e3/3dd0e3866a96a1bb47283350ef05ac1b.jpg"
            alt="Trà Việt Quất"
          />
          <div class="product-no">8</div>
        </div>
        <div class="product-name">Trà Việt Quất</div>
        <div class="product-price">8đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/44/03/9b/44039b6151c6f60c22855f4e47087c98.jpg"
            alt="Trà Sen"
          />
          <div class="product-no">9</div>
        </div>
        <div class="product-name">Trà Sen</div>
        <div class="product-price">9đ</div>
      </div>
      <div class="productss1" id="kvtm">Hoa Tươi</div>
      <!-- 6 -->
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/34/51/18/345118545c002472189aed34cb76839b.jpg"
            alt="Bó Hồng"
          />
          <div class="product-no">1</div>
        </div>
        <div class="product-name">Bó Hồng</div>
        <div class="product-price">1đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/46/0a/36/460a362f2bd6ea7703bff97ad83e38b3.jpg"
            alt="Bó Oải Hương"
          />
          <div class="product-no">2</div>
        </div>
        <div class="product-name">Bó Oải Hương</div>
        <div class="product-price">2đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/b3/04/4b/b3044bd9c3ed15c7ebd84bd077df0b74.jpg"
            alt="Bó Cúc"
          />
          <div class="product-no">3</div>
        </div>
        <div class="product-name">Bó Cúc</div>
        <div class="product-price">3đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/2a/58/29/2a5829719ac9e81ebf82ecaa920990b3.jpg"
            alt="Bó H.Dương"
          />
          <div class="product-no">4</div>
        </div>
        <div class="product-name">Bó H.Dương</div>
        <div class="product-price">4đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/1e/ff/cd/1effcd81a91deb90557b18cc61bfcd2e.jpg"
            alt="Bó Sen"
          />
          <div class="product-no">5</div>
        </div>
        <div class="product-name">Bó Sen</div>
        <div class="product-price">5đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/e7/6d/18/e76d18c99eaa470d21876e32535e46e8.jpg"
            alt="Bó Lài"
          />
          <div class="product-no">6</div>
        </div>
        <div class="product-name">Bó Lài</div>
        <div class="product-price">6đ</div>
      </div>
      <div class="productss1" id="kvtm">Nước Hoa</div>
      <!-- 7 -->
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/3d/89/52/3d8952a7333c2c119e40ba7d3b3bacdb.jpg"
            alt="Nước Hoa Hồng"
          />
          <div class="product-no">1</div>
        </div>
        <div class="product-name">Nước Hoa Hồng</div>
        <div class="product-price">1đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/18/cb/4e/18cb4ee1b6ce58fe61f8f1cb76775391.jpg"
            alt="NH Hương Táo"
          />
          <div class="product-no">2</div>
        </div>
        <div class="product-name">NH Hương Táo</div>
        <div class="product-price">2đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/30/b8/23/30b823bb3ef9ef2ecbb5389a9e385177.jpg"
            alt="NH Oải Hương"
          />
          <div class="product-no">3</div>
        </div>
        <div class="product-name">NH Oải Hương</div>
        <div class="product-price">3đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/5a/4a/eb/5a4aeba7b8e7b850133bde04f292622f.jpg"
            alt="NH Hương Chanh"
          />
          <div class="product-no">4</div>
        </div>
        <div class="product-name">NH Hương Chanh</div>
        <div class="product-price">4đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/e0/42/d5/e042d563b47c00913f57e2760181002c.jpg"
            alt="NH Việt Quất"
          />
          <div class="product-no">5</div>
        </div>
        <div class="product-name">NH Việt Quất</div>
        <div class="product-price">5đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/85/41/e3/8541e3afc4e5c1d14d280de8066e15bd.jpg"
            alt="NH Hương Sen"
          />
          <div class="product-no">6</div>
        </div>
        <div class="product-name">NH Hương Sen</div>
        <div class="product-price">6đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/32/9f/7a/329f7ab3017aaf1beb177ff2195ebc45.jpg"
            alt="NH Hương Dâu"
          />
          <div class="product-no">7</div>
        </div>
        <div class="product-name">NH Hương Dâu</div>
        <div class="product-price">7đ</div>
      </div>
      <div class="productss1" id="kvtm">Túi Hương</div>
      <!-- 6 -->
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/56/17/fd/5617fd802158c3e7a87bfde533800659.jpg"
            alt="Túi Hoa Hồng"
          />
          <div class="product-no">1</div>
        </div>
        <div class="product-name">Túi Hoa Hồng</div>
        <div class="product-price">1đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/1b/08/e7/1b08e7abeac16908dee04440f1b1e4f6.jpg"
            alt="Túi Hương Táo"
          />
          <div class="product-no">2</div>
        </div>
        <div class="product-name">Túi Hương Táo</div>
        <div class="product-price">2đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/b5/f9/9f/b5f99f87baee64677c914432e05c9c0f.jpg"
            alt="Túi Oải Hương"
          />
          <div class="product-no">3</div>
        </div>
        <div class="product-name">Túi Oải Hương</div>
        <div class="product-price">3đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/73/fa/ab/73faabb95c4a1d6fe5685cf0fd387421.jpg"
            alt="Túi Hương Chanh"
          />
          <div class="product-no">4</div>
        </div>
        <div class="product-name">Túi Hương Chanh</div>
        <div class="product-price">4đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/95/8a/3b/958a3b4992061a2bc62893e2e919897f.jpg"
            alt="Túi Việt Quất"
          />
          <div class="product-no">5</div>
        </div>
        <div class="product-name">Túi Việt Quất</div>
        <div class="product-price">5đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/be/b4/d8/beb4d8fb2b98de8dfbbc4e271b198eeb.jpg"
            alt="Túi Hương Sen"
          />
          <div class="product-no">6</div>
        </div>
        <div class="product-name">Túi Hương Sen</div>
        <div class="product-price">6đ</div>
      </div>
      <div class="productss1" id="kvtm">Vật Phẩm May</div>
      <!-- 8 -->
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/8d/03/89/8d0389c5521ee6438f8d4f756ca9df25.jpg"
            alt="Khăn Đỏ"
          />
          <div class="product-no">1</div>
        </div>
        <div class="product-name">Khăn Đỏ</div>
        <div class="product-price">1đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/31/cd/c8/31cdc871dc99cce25fea576a239d3048.jpg"
            alt="Đầm Bạch Tuyết"
          />
          <div class="product-no">2</div>
        </div>
        <div class="product-name">Đầm Bạch Tuyết</div>
        <div class="product-price">2đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/fe/75/3c/fe753c0de0157c26d17bae1fd1eee402.jpg"
            alt="Thảm Bay"
          />
          <div class="product-no">3</div>
        </div>
        <div class="product-name">Thảm Bay</div>
        <div class="product-price">3đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/df/93/2f/df932f0f676eaeafccf5bf00bdb06066.jpg"
            alt="Nón Bá Tước"
          />
          <div class="product-no">4</div>
        </div>
        <div class="product-name">Nón Bá Tước</div>
        <div class="product-price">4đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/0c/dd/ab/0cddabbd2d098015252712f5c4d4f717.jpg"
            alt="Túi Chuột Chù"
          />
          <div class="product-no">5</div>
        </div>
        <div class="product-name">Túi Chuột Chù</div>
        <div class="product-price">5đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/5c/f2/41/5cf24177b04536fef40c7f57546954ec.jpg"
            alt="Nơ Công Chúa"
          />
          <div class="product-no">6</div>
        </div>
        <div class="product-name">Nơ Công Chúa</div>
        <div class="product-price">6đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/5e/0b/ff/5e0bff47ac3a79c04ac36942474ac2b3.jpg"
            alt="Áo Choàng"
          />
          <div class="product-no">7</div>
        </div>
        <div class="product-name">Áo Choàng</div>
        <div class="product-price">7đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/b5/83/0d/b5830d6bff4472762b7c6ead86d126e6.jpg"
            alt="Giày Đi Hia"
          />
          <div class="product-no">8</div>
        </div>
        <div class="product-name">Giày Đi Hia</div>
        <div class="product-price">8đ</div>
      </div>
      <div class="productss1" id="kvtm">Bọ</div>
      <!-- 7 -->
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/b5/59/07/b559076ad355aa4b1675ac55e08f165e.jpg"
            alt="Bọ Rùa"
          />
          <div class="product-no">1</div>
        </div>
        <div class="product-name">Bọ Rùa</div>
        <div class="product-price">1đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/ba/04/c8/ba04c8afd5021cb8cc55900cdb0d5c2b.jpg"
            alt="Ốc Sên"
          />
          <div class="product-no">2</div>
        </div>
        <div class="product-name">Ốc Sên</div>
        <div class="product-price">2đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/6d/d7/db/6dd7dbdb030a5f337fa762378e8f07de.jpg"
            alt="Đom Đóm"
          />
          <div class="product-no">3</div>
        </div>
        <div class="product-name">Đom Đóm</div>
        <div class="product-price">3đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/5f/0e/76/5f0e76aae9169c4663d9a8759fdf7bc0.jpg"
            alt="Ong Mật"
          />
          <div class="product-no">4</div>
        </div>
        <div class="product-name">Ong Mật</div>
        <div class="product-price">4đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/02/8e/0e/028e0e144ec65a0c0673da30de975976.jpg"
            alt="Chuồn Chuồn"
          />
          <div class="product-no">5</div>
        </div>
        <div class="product-name">Chuồn Chuồn</div>
        <div class="product-price">5đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/98/d4/b8/98d4b83c4711d7781c08618317219397.jpg"
            alt="Bươm Bướm"
          />
          <div class="product-no">6</div>
        </div>
        <div class="product-name">Bươm Bướm</div>
        <div class="product-price">6đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/b4/0e/0a/b40e0ac8ebec442655827025a39dbc27.jpg"
            alt="Sâu Xanh"
          />
          <div class="product-no">7</div>
        </div>
        <div class="product-name">Sâu Xanh</div>
        <div class="product-price">7đ</div>
      </div>
      <div class="productss1" id="kvtm">Vật Phẩm Khác</div>
      <!-- 8 -->
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/cd/80/c0/cd80c01c223117492d6f11b31cbfb297.jpg"
            alt="Vợt Vàng"
          />
          <div class="product-no">1</div>
        </div>
        <div class="product-name">Vợt Vàng</div>
        <div class="product-price">1đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/4d/e1/3c/4de13ce0975519b0ab30911689682d37.jpg"
            alt="Vợt Xanh"
          />
          <div class="product-no">2</div>
        </div>
        <div class="product-name">Vợt Xanh</div>
        <div class="product-price">2đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/30/e9/10/30e910a6889550872708484b49942ae8.jpg"
            alt="Thỏi Đồng"
          />
          <div class="product-no">3</div>
        </div>
        <div class="product-name">Thỏi Đồng</div>
        <div class="product-price">3đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/f9/8f/19/f98f198b25c78d9edddfee506f253856.jpg"
            alt="Thỏi Bạc"
          />
          <div class="product-no">4</div>
        </div>
        <div class="product-name">Thỏi Bạc</div>
        <div class="product-price">4đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/3a/54/ad/3a54ade9144b0869933585794f7ab560.jpg"
            alt="Thỏi Vàng"
          />
          <div class="product-no">5</div>
        </div>
        <div class="product-name">Thỏi Vàng</div>
        <div class="product-price">5đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/7f/7a/2a/7f7a2a9dc91d6b8262a305782ff50e0b.jpg"
            alt="Thỏi Bạch Kim"
          />
          <div class="product-no">6</div>
        </div>
        <div class="product-name">Thỏi Bạch Kim</div>
        <div class="product-price">6đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/88/a7/e4/88a7e40dc4c265cd76cf491c50aa16e4.jpg"
            alt="Keo Dán Mây"
          />
          <div class="product-no">7</div>
        </div>
        <div class="product-name">Keo Dán Mây</div>
        <div class="product-price">7đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/95/f8/0a/95f80ae795637d540e04105123cd216b.jpg"
            alt="Lọ Nước Thần"
          />
          <div class="product-no">8</div>
        </div>
        <div class="product-name">Lọ Nước Thần</div>
        <div class="product-price">8đ</div>
      </div>
      <div class="productss1" id="kvtm">Vàng & Vật Phẩm Sự Kiện</div>
      <!-- 11 -->
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/34/59/6a/34596a4db3932a3855c872c2f4833e5d.jpg"
            alt="VP1"
          />
          <div class="product-no">1</div>
        </div>
        <div class="product-name">VP1</div>
        <div class="product-price">1đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/34/59/6a/34596a4db3932a3855c872c2f4833e5d.jpg"
            alt="VP2"
          />
          <div class="product-no">2</div>
        </div>
        <div class="product-name">VP2</div>
        <div class="product-price">2đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/34/59/6a/34596a4db3932a3855c872c2f4833e5d.jpg"
            alt="VP3"
          />
          <div class="product-no">3</div>
        </div>
        <div class="product-name">VP3</div>
        <div class="product-price">3đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/34/59/6a/34596a4db3932a3855c872c2f4833e5d.jpg"
            alt="VP4"
          />
          <div class="product-no">4</div>
        </div>
        <div class="product-name">VP4</div>
        <div class="product-price">4đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/34/59/6a/34596a4db3932a3855c872c2f4833e5d.jpg"
            alt="VP5"
          />
          <div class="product-no">5</div>
        </div>
        <div class="product-name">VP5</div>
        <div class="product-price">5đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/34/59/6a/34596a4db3932a3855c872c2f4833e5d.jpg"
            alt="VP6"
          />
          <div class="product-no">6</div>
        </div>
        <div class="product-name">VP6</div>
        <div class="product-price">6đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/34/59/6a/34596a4db3932a3855c872c2f4833e5d.jpg"
            alt="VP7"
          />
          <div class="product-no">7</div>
        </div>
        <div class="product-name">VP7</div>
        <div class="product-price">7đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/34/59/6a/34596a4db3932a3855c872c2f4833e5d.jpg"
            alt="VP8"
          />
          <div class="product-no">8</div>
        </div>
        <div class="product-name">VP8</div>
        <div class="product-price">8đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/34/59/6a/34596a4db3932a3855c872c2f4833e5d.jpg"
            alt="VP9"
          />
          <div class="product-no">9</div>
        </div>
        <div class="product-name">VP9</div>
        <div class="product-price">9đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/34/59/6a/34596a4db3932a3855c872c2f4833e5d.jpg"
            alt="VP10"
          />
          <div class="product-no">10</div>
        </div>
        <div class="product-name">VP10</div>
        <div class="product-price">10đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/eb/6f/98/eb6f98c146554c6a1706063d3b0ccda8.jpg"
            alt="Vàng"
          />
          <div class="product-no">11</div>
        </div>
        <div class="product-name">Vàng</div>
        <div class="product-price">11đ</div>
      </div>
      <div class="productss1" id="kvtm">Hạt Giống</div>
      <!-- 20 -->
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/0e/42/bd/0e42bd37a7df13b7f5148b4506747a44.jpg"
            alt="Hồng"
          />
          <div class="product-no">1</div>
        </div>
        <div class="product-name">Hồng</div>
        <div class="product-price">1đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/50/b4/e0/50b4e0c0a8529aecb463a3d95b9d72f9.jpg"
            alt="Táo"
          />
          <div class="product-no">2</div>
        </div>
        <div class="product-name">Táo</div>
        <div class="product-price">2đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/d8/61/a3/d861a3624e9085350724a4e852cfdd45.jpg"
            alt="Bông"
          />
          <div class="product-no">3</div>
        </div>
        <div class="product-name">Bông</div>
        <div class="product-price">3đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/04/4e/c3/044ec3aa766ef7fbdcf1c11e9d95e379.jpg"
            alt="Tuyết"
          />
          <div class="product-no">4</div>
        </div>
        <div class="product-name">Tuyết</div>
        <div class="product-price">4đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/cd/72/ef/cd72ef092b254db4579e94f15352170b.jpg"
            alt="Oải Hương"
          />
          <div class="product-no">5</div>
        </div>
        <div class="product-name">Oải Hương</div>
        <div class="product-price">5đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/ed/ba/fb/edbafbfc9ceac4bbefa40c39d54bb0bb.jpg"
            alt="Dừa"
          />
          <div class="product-no">6</div>
        </div>
        <div class="product-name">Dừa</div>
        <div class="product-price">6đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/0a/4b/f5/0a4bf5ace4ac08a31f7a40c2af31dd6f.jpg"
            alt="Chanh"
          />
          <div class="product-no">7</div>
        </div>
        <div class="product-name">Chanh</div>
        <div class="product-price">7đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/c8/a9/7b/c8a97b486670349beebf540a343d896b.jpg"
            alt="Dưa Hấu"
          />
          <div class="product-no">8</div>
        </div>
        <div class="product-name">Dưa Hấu</div>
        <div class="product-price">8đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/4d/26/e9/4d26e92b76b8aea854cb58e0746b29f3.jpg"
            alt="Trà"
          />
          <div class="product-no">9</div>
        </div>
        <div class="product-name">Trà</div>
        <div class="product-price">9đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/c8/d4/74/c8d4743a5801357e670e039858ca4d04.jpg"
            alt="Mít"
          />
          <div class="product-no">10</div>
        </div>
        <div class="product-name">Mít</div>
        <div class="product-price">10đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/a3/3e/fc/a33efcd72ff80a699778a2d5f7f6882a.jpg"
            alt="Dứa"
          />
          <div class="product-no">11</div>
        </div>
        <div class="product-name">Dứa</div>
        <div class="product-price">11đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/ea/df/b2/eadfb2be03c048433f58f29084a952da.jpg"
            alt="Xòa"
          />
          <div class="product-no">12</div>
        </div>
        <div class="product-name">Xòa</div>
        <div class="product-price">12đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/cb/d8/2c/cbd82c87ffbb674d04e60bbf852e0780.jpg"
            alt="Nho"
          />
          <div class="product-no">13</div>
        </div>
        <div class="product-name">Nho</div>
        <div class="product-price">13đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/5d/c2/9e/5dc29ee4b04df68cea8b27e21fdbbf8a.jpg"
            alt="Lài"
          />
          <div class="product-no">14</div>
        </div>
        <div class="product-name">Lài</div>
        <div class="product-price">14đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/01/d3/ff/01d3ffb9b03bc825b0669078947fe645.jpg"
            alt="Cúc"
          />
          <div class="product-no">15</div>
        </div>
        <div class="product-name">Cúc</div>
        <div class="product-price">15đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/71/81/5d/71815dd8824f0f053a44347271199173.jpg"
            alt="Bi"
          />
          <div class="product-no">16</div>
        </div>
        <div class="product-name">Bi</div>
        <div class="product-price">16đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/ae/78/f5/ae78f5769cf8fd98022af0d1bd3ad883.jpg"
            alt="Sen"
          />
          <div class="product-no">17</div>
        </div>
        <div class="product-name">Sen</div>
        <div class="product-price">17đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/ec/10/23/ec102359c85185194c358439b198cdf7.jpg"
            alt="Hướng Dương"
          />
          <div class="product-no">18</div>
        </div>
        <div class="product-name">Hướng Dương</div>
        <div class="product-price">18đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/e2/f6/b1/e2f6b14b164297f46626c737d94337ce.jpg"
            alt="Việt Quất"
          />
          <div class="product-no">19</div>
        </div>
        <div class="product-name">Việt Quất</div>
        <div class="product-price">19đ</div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/8f/87/9b/8f879b0d0877bac37e3d53e477a310ac.jpg"
            alt="Dâu"
          />
          <div class="product-no">20</div>
        </div>
        <div class="product-name">Dâu</div>
        <div class="product-price">20đ</div>
      </div>

      <div class="productss0" id="pd0"></div>
      <!-- Acc Khu Vườn Trên Mây -->
      <div class="productss1" id="kvtm">Acc Khu Vườn Trên Mây</div>
      <div class="product kvtm">
        <div class="product-img2">
          <img
            src="https://i.pinimg.com/474x/34/59/6a/34596a4db3932a3855c872c2f4833e5d.jpg"
            alt="1"
          />
          <div class="product-no">1024</div>
        </div>
        <div class="product-name">1</div>
        <div class="product-price">2-1 VNĐ</div>
      </div>
      <!-- Acc Liên Quân Moblie -->
      <div class="product lq">
        <div class="product-img2">
          <img
            src="https://i.pinimg.com/474x/34/59/6a/34596a4db3932a3855c872c2f4833e5d.jpg"
            alt="2"
          />
        </div>
        <div class="product-name">2</div>
        <div class="product-price">2-1 VNĐ</div>
      </div>
      <!-- Acc Clash Of Clans -->
      <div class="product coc">
        <div class="product-img2">
          <img
            src="https://i.pinimg.com/474x/34/59/6a/34596a4db3932a3855c872c2f4833e5d.jpg"
            alt="3"
          />
        </div>
        <div class="product-name">3</div>
        <div class="product-price">2-1 VNĐ</div>
      </div>
      <!-- Acc Dragon City -->
      <div class="product dc">
        <div class="product-img2">
          <img
            src="https://i.pinimg.com/474x/34/59/6a/34596a4db3932a3855c872c2f4833e5d.jpg"
            alt="4"
          />
        </div>
        <div class="product-name">4</div>
        <div class="product-price">2-1 VNĐ</div>
      </div>
      <!-- Acc Free Fire -->
      <div class="product ff">
        <div class="product-img2">
          <img
            src="https://i.pinimg.com/474x/34/59/6a/34596a4db3932a3855c872c2f4833e5d.jpg"
            alt="5"
          />
        </div>
        <div class="product-name">5</div>
        <div class="product-price">2-1 VNĐ</div>
      </div>
      <!-- Thẻ Game -->
      <div class="productss6" id="khac">Thẻ Game</div>
      <div class="product khac">
        <div class="product-img2">
          <img
            src="https://i.pinimg.com/474x/34/59/6a/34596a4db3932a3855c872c2f4833e5d.jpg"
            alt="6"
          />
          <div class="product-no">1024</div>
        </div>
        <div class="product-name">6</div>
        <div class="product-price">2-1 VNĐ</div>
      </div>
      <!-- Game Khác -->
      <div class="productss6" id="khac">Game Khác</div>
      <div class="product khac">
        <div class="product-img2">
          <img
            src="https://i.pinimg.com/474x/34/59/6a/34596a4db3932a3855c872c2f4833e5d.jpg"
            alt="6"
          />
        </div>
        <div class="product-name">6</div>
        <div class="product-price">2-1 VNĐ</div>
      </div>
    </div>

    <div class="container1">
      <div id="arrowUp1" class="arrow-btn1">^</div>
      <div id="arrowDown1" class="arrow-btn1" style="transform: rotate(180deg)">
        ^
      </div>
    </div>
    <div class="container1">
      <div id="arrowUp2" class="arrow-btn2">^</div>
      <div id="arrowDown2" class="arrow-btn2" style="transform: rotate(180deg)">
        ^
      </div>
    </div>

    <div class="container2">
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
        const element3 = document.querySelectorAll('[id="pd0"]');
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
            element3.forEach((element3) => {
              element3.style.display = "block";
            });
          } else {
            Image1.classList.remove("glow-effect");
            element3.forEach((element3) => {
              element3.style.display = "none";
            });
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
