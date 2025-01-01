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
        gap: 2%;
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
        border-radius: 50%;
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

      .contact-Chatting img {
        width: 75%;
        margin: 10px 12.5% 0 12.5%;
      }

      .products {
        margin-top: 170.5px;
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 10px;
        width: auto;
      }

      .productss,
      .productss0,
      .productss1,
      .productss2,
      .productss3,
      .productss4,
      .productss5,
      .productss6 {
        width: 100%;
        min-width: 320px;
        height: auto;
        padding: 2.5px 0;
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
        align-items: center;
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
      }

      .product-no {
        position: absolute;
        bottom: 15px;
        width: 100%;
        text-align: center;
        justify-content: center;
        text-shadow: 0 0 12px rgba(0, 0, 0, 0.7);
        font-size: 10px;
      }

      .product-img1 img {
        width: 80px;
        height: 80px;
      }
      .product-img2 img {
        width: 140px;
        height: 140px;
      }

      .product-name {
        display: flex; /* Kích hoạt Flexbox */
        flex-direction: row; /* Sắp xếp phần tử theo hàng ngang */
        justify-content: center; /* Căn giữa các phần tử theo chiều ngang */
        align-items: center; /* Căn giữa các phần tử theo chiều dọc */
        width: max-content-content; /* Đảm bảo chỉ chiếm diện tích vừa đủ nội dung */
        font-size: 10px;
        gap: 1px;
      }

      .product-price {
        font-size: 10px;
        font-weight: bold;
        color: #ff5733;
      }

      .product-pcs {
        font-size: 10px;
        font-weight: bold;
        color: #ffd22d;
      }

      .arrow-btn1,
      .arrow-btn6 {
        cursor: pointer;
        font-size: 28px;
        font-weight: bold;
        color: white;
        width: 40px;
        height: auto;
        background-color: #00000000;
        border-radius: 3px;
        display: flex;
        text-align: center;
        justify-content: center;
        transition: background-color 0.5s, transform 0.5s;
      }

      .arrow-btn1:active,
      .arrow-btn6:active {
        border-radius: 3px;
        box-shadow: 0 0 5px 5px rgba(255, 255, 255, 0.2);
      }

      /* Hiệu ứng phát sáng */
      .glow-effect {
        border-radius: 3px;
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
    <img
      src="https://i.pinimg.com/474x/34/59/6a/34596a4db3932a3855c872c2f4833e5d.jpg"
      alt="Logo"
      style="display: none"
    />
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
      <!-- Vật Phẩm Khu Vườn Trên Mây -->

      <div class="productss1" id="kvtm">Bọ</div>
      <!-- 7 -->
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/b5/59/07/b559076ad355aa4b1675ac55e08f165e.jpg"
            alt="Bọ Rùa"
          />
          <div class="product-no">x1000</div>
        </div>
        <div class="product-name">
          <div class="product-pcs">150</div>
          /
          <div class="product-price">10k</div>
        </div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/ba/04/c8/ba04c8afd5021cb8cc55900cdb0d5c2b.jpg"
            alt="Ốc Sên"
          />
          <div class="product-no">x1000</div>
        </div>
        <div class="product-name">
          <div class="product-pcs">150</div>
          /
          <div class="product-price">10k</div>
        </div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/6d/d7/db/6dd7dbdb030a5f337fa762378e8f07de.jpg"
            alt="Đom Đóm"
          />
          <div class="product-no">x1000</div>
        </div>
        <div class="product-name">
          <div class="product-pcs">100</div>
          /
          <div class="product-price">10k</div>
        </div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/5f/0e/76/5f0e76aae9169c4663d9a8759fdf7bc0.jpg"
            alt="Ong Mật"
          />
          <div class="product-no">x1000</div>
        </div>
        <div class="product-name">
          <div class="product-pcs">100</div>
          /
          <div class="product-price">10k</div>
        </div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/02/8e/0e/028e0e144ec65a0c0673da30de975976.jpg"
            alt="Chuồn Chuồn"
          />
          <div class="product-no">x1000</div>
        </div>
        <div class="product-name">
          <div class="product-pcs">75</div>
          /
          <div class="product-price">10k</div>
        </div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/98/d4/b8/98d4b83c4711d7781c08618317219397.jpg"
            alt="Bươm Bướm"
          />
          <div class="product-no">x1000</div>
        </div>
        <div class="product-name">
          <div class="product-pcs">75</div>
          /
          <div class="product-price">10k</div>
        </div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/b4/0e/0a/b40e0ac8ebec442655827025a39dbc27.jpg"
            alt="Sâu Xanh"
          />
          <div class="product-no">x1000</div>
        </div>
        <div class="product-name">
          <div class="product-pcs">50</div>
          /
          <div class="product-price">10k</div>
        </div>
      </div>
      <div class="productss1" id="kvtm">Hạt Giống</div>
      <!-- 20 -->
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/0e/42/bd/0e42bd37a7df13b7f5148b4506747a44.jpg"
            alt="Hồng"
          />
          <div class="product-no">x1500</div>
        </div>
        <div class="product-name">
          <div class="product-pcs">1500</div>
          /
          <div class="product-price">10k</div>
        </div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/50/b4/e0/50b4e0c0a8529aecb463a3d95b9d72f9.jpg"
            alt="Táo"
          />
          <div class="product-no">x1500</div>
        </div>
        <div class="product-name">
          <div class="product-pcs">1500</div>
          /
          <div class="product-price">10k</div>
        </div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/d8/61/a3/d861a3624e9085350724a4e852cfdd45.jpg"
            alt="Bông"
          />
          <div class="product-no">x1500</div>
        </div>
        <div class="product-name">
          <div class="product-pcs">1500</div>
          /
          <div class="product-price">10k</div>
        </div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/04/4e/c3/044ec3aa766ef7fbdcf1c11e9d95e379.jpg"
            alt="Tuyết"
          />
          <div class="product-no">x1500</div>
        </div>
        <div class="product-name">
          <div class="product-pcs">1500</div>
          /
          <div class="product-price">10k</div>
        </div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/cd/72/ef/cd72ef092b254db4579e94f15352170b.jpg"
            alt="O.Hương"
          />
          <div class="product-no">x1500</div>
        </div>
        <div class="product-name">
          <div class="product-pcs">1500</div>
          /
          <div class="product-price">10k</div>
        </div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/ed/ba/fb/edbafbfc9ceac4bbefa40c39d54bb0bb.jpg"
            alt="Dừa"
          />
          <div class="product-no">x1500</div>
        </div>
        <div class="product-name">
          <div class="product-pcs">1000</div>
          /
          <div class="product-price">10k</div>
        </div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/0a/4b/f5/0a4bf5ace4ac08a31f7a40c2af31dd6f.jpg"
            alt="Chanh"
          />
          <div class="product-no">x1500</div>
        </div>
        <div class="product-name">
          <div class="product-pcs">1000</div>
          /
          <div class="product-price">10k</div>
        </div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/c8/a9/7b/c8a97b486670349beebf540a343d896b.jpg"
            alt="D.Hấu"
          />
          <div class="product-no">x1500</div>
        </div>
        <div class="product-name">
          <div class="product-pcs">1000</div>
          /
          <div class="product-price">10k</div>
        </div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/4d/26/e9/4d26e92b76b8aea854cb58e0746b29f3.jpg"
            alt="Trà"
          />
          <div class="product-no">x1500</div>
        </div>
        <div class="product-name">
          <div class="product-pcs">1000</div>
          /
          <div class="product-price">10k</div>
        </div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/c8/d4/74/c8d4743a5801357e670e039858ca4d04.jpg"
            alt="Mít"
          />
          <div class="product-no">x1500</div>
        </div>
        <div class="product-name">
          <div class="product-pcs">1000</div>
          /
          <div class="product-price">10k</div>
        </div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/a3/3e/fc/a33efcd72ff80a699778a2d5f7f6882a.jpg"
            alt="Dứa"
          />
          <div class="product-no">x1500</div>
        </div>
        <div class="product-name">
          <div class="product-pcs">500</div>
          /
          <div class="product-price">10k</div>
        </div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/ea/df/b2/eadfb2be03c048433f58f29084a952da.jpg"
            alt="Xoài"
          />
          <div class="product-no">x1500</div>
        </div>
        <div class="product-name">
          <div class="product-pcs">500</div>
          /
          <div class="product-price">10k</div>
        </div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/cb/d8/2c/cbd82c87ffbb674d04e60bbf852e0780.jpg"
            alt="Nho"
          />
          <div class="product-no">x1500</div>
        </div>
        <div class="product-name">
          <div class="product-pcs">500</div>
          /
          <div class="product-price">10k</div>
        </div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/5d/c2/9e/5dc29ee4b04df68cea8b27e21fdbbf8a.jpg"
            alt="Lài"
          />
          <div class="product-no">x1500</div>
        </div>
        <div class="product-name">
          <div class="product-pcs">500</div>
          /
          <div class="product-price">10k</div>
        </div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/01/d3/ff/01d3ffb9b03bc825b0669078947fe645.jpg"
            alt="Cúc"
          />
          <div class="product-no">x1500</div>
        </div>
        <div class="product-name">
          <div class="product-pcs">500</div>
          /
          <div class="product-price">10k</div>
        </div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/71/81/5d/71815dd8824f0f053a44347271199173.jpg"
            alt="Bi"
          />
          <div class="product-no">x1500</div>
        </div>
        <div class="product-name">
          <div class="product-pcs">200</div>
          /
          <div class="product-price">10k</div>
        </div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/ae/78/f5/ae78f5769cf8fd98022af0d1bd3ad883.jpg"
            alt="Sen"
          />
          <div class="product-no">x1500</div>
        </div>
        <div class="product-name">
          <div class="product-pcs">200</div>
          /
          <div class="product-price">10k</div>
        </div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/ec/10/23/ec102359c85185194c358439b198cdf7.jpg"
            alt="H.Dương"
          />
          <div class="product-no">x1500</div>
        </div>
        <div class="product-name">
          <div class="product-pcs">200</div>
          /
          <div class="product-price">10k</div>
        </div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/e2/f6/b1/e2f6b14b164297f46626c737d94337ce.jpg"
            alt="V.Quất"
          />
          <div class="product-no">x1500</div>
        </div>
        <div class="product-name">
          <div class="product-pcs">200</div>
          /
          <div class="product-price">10k</div>
        </div>
      </div>
      <div class="product kvtm">
        <div class="product-img1">
          <img
            src="https://i.pinimg.com/474x/8f/87/9b/8f879b0d0877bac37e3d53e477a310ac.jpg"
            alt="Dâu"
          />
          <div class="product-no">x1500</div>
        </div>
        <div class="product-name">
          <div class="product-pcs">200</div>
          /
          <div class="product-price">10k</div>
        </div>
      </div>

      <!-- ACC Game -->
      <!-- Acc Khu Vườn Trên Mây -->

      <!-- Acc Liên Quân Moblie -->

      <!-- Acc Clash Of Clans -->

      <!-- Acc Dragon City -->

      <!-- Acc Free Fire -->

      <!-- Khác -->

      <!-- NỘI DUNG HIỂN THỊ -->
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
    </div>

    <div class="container1">
      <div id="arrowUp1" class="arrow-btn1" style="transform: rotate(-90deg)">
        >
      </div>
      <div id="arrowDown1" class="arrow-btn1" style="transform: rotate(90deg)">
        >
      </div>
    </div>
    <div class="container1">
      <div id="arrowUp6" class="arrow-btn6" style="transform: rotate(-90deg)">
        >
      </div>
      <div id="arrowDown6" class="arrow-btn6" style="transform: rotate(90deg)">
        >
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
        <img
          src="https://i.pinimg.com/474x/b7/ff/a7/b7ffa7483252e829d97ce2978c82ce01.jpg"
          alt="Hướng Dẫn"
        />
        <p style="text-align: center; font-size: 14px">
          ❤️ OTISStore - Chân Thành Cảm Ơn Quý Khách! ❤️
        </p>
      </div>
    </div>

    <script>
      function filterProducts(category) {
        const products = document.querySelectorAll(".product");
        const element0 = document.querySelectorAll('[id="pd0"]');
        const element1 = document.querySelectorAll('[id="kvtm"]');
        const element2 = document.querySelectorAll('[id="lq"]');
        const element3 = document.querySelectorAll('[id="coc"]');
        const element4 = document.querySelectorAll('[id="dc"]');
        const element5 = document.querySelectorAll('[id="ff"]');
        const element6 = document.querySelectorAll('[id="khac"]');
        const arrow1 = document.querySelectorAll(".arrow-btn1");
        const arrow6 = document.querySelectorAll(".arrow-btn6");
        const Image0 = document.querySelector('img[alt="Logo Home"]');
        const Image1 = document.querySelector(
          'img[alt="Logo Khu Vườn Trên Mây"]'
        );
        const Image2 = document.querySelector('img[alt="Logo Liên Quân"]');
        const Image3 = document.querySelector('img[alt="Logo Clash of Clans"]');
        const Image4 = document.querySelector('img[alt="Logo Dragon City"]');
        const Image5 = document.querySelector('img[alt="Logo Free Fire"]');
        const Image6 = document.querySelector('img[alt="Logo Khác"]');

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
        const delay = 50; // Thời gian delay giữa các phần tử
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
            Image0.classList.add("glow-effect");
            element0.forEach((element0) => {
              element0.style.display = "block";
            });
          } else {
            Image0.classList.remove("glow-effect");
            element0.forEach((element0) => {
              element0.style.display = "none";
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
            Image1.classList.add("glow-effect");
            // Nếu không có thẻ nào với class "product kvtm"
            if (product1.length === 0) {
              test1.style.display = "block"; // Hiển thị thẻ có id="Test1"
            } else {
              test1.style.display = "none"; // Ẩn thẻ có id="Test1"
            }
          } else {
            // Ngược lại, ẩn các phần tử có id="kvtm", arrowUp1 và arrowDown1
            element1.forEach((element1) => {
              element1.style.display = "none";
            });
            arrow1.forEach((el) => {
              el.style.display = "none";
            });
            Image1.classList.remove("glow-effect");
            test1.style.display = "none"; // Ẩn thẻ có id="Test1"
          }

          if (category === "lq") {
            element2.forEach((element2) => {
              element2.style.display = "block";
            });
            Image2.classList.add("glow-effect");
            // Nếu không có thẻ nào với class "product lq"
            if (product2.length === 0) {
              test2.style.display = "block"; // Hiển thị thẻ có id="Test2"
            } else {
              test2.style.display = "none"; // Ẩn thẻ có id="Test2"
            }
          } else {
            element2.forEach((element2) => {
              element2.style.display = "none";
            });
            Image2.classList.remove("glow-effect");
            test2.style.display = "none"; // Ẩn thẻ có id="Test2"
          }

          if (category === "coc") {
            element3.forEach((element3) => {
              element3.style.display = "block";
            });
            Image3.classList.add("glow-effect");
            // Nếu không có thẻ nào với class "product lq"
            if (product3.length === 0) {
              test3.style.display = "block"; // Hiển thị thẻ có id="Test3"
            } else {
              test3.style.display = "none"; // Ẩn thẻ có id="Test3"
            }
          } else {
            element3.forEach((element3) => {
              element3.style.display = "none";
            });
            Image3.classList.remove("glow-effect");
            test3.style.display = "none"; // Ẩn thẻ có id="Test3"
          }

          if (category === "dc") {
            element4.forEach((element4) => {
              element4.style.display = "block";
            });
            Image4.classList.add("glow-effect");
            // Nếu không có thẻ nào với class "product lq"
            if (product4.length === 0) {
              test4.style.display = "block"; // Hiển thị thẻ có id="Test4"
            } else {
              test4.style.display = "none"; // Ẩn thẻ có id="Test4"
            }
          } else {
            element4.forEach((element4) => {
              element4.style.display = "none";
            });
            Image4.classList.remove("glow-effect");
            test4.style.display = "none"; // Ẩn thẻ có id="Test4"
          }

          if (category === "ff") {
            element5.forEach((element5) => {
              element5.style.display = "block";
            });
            Image5.classList.add("glow-effect");
            // Nếu không có thẻ nào với class "product lq"
            if (product5.length === 0) {
              test5.style.display = "block"; // Hiển thị thẻ có id="Test5"
            } else {
              test5.style.display = "none"; // Ẩn thẻ có id="Test5"
            }
          } else {
            element5.forEach((element5) => {
              element5.style.display = "none";
            });
            Image5.classList.remove("glow-effect");
            test5.style.display = "none"; // Ẩn thẻ có id="Test5"
          }

          // Nếu category là "khac", hiển thị các phần tử có id="khac", arrowUp2 và arrowDown6
          if (category === "khac") {
            element6.forEach((element6) => {
              element6.style.display = "block";
            });
            arrow6.forEach((el) => {
              el.style.display = "block";
            });
            Image6.classList.add("glow-effect");
            // Nếu không có thẻ nào với class "product lq"
            if (product6.length === 0) {
              test6.style.display = "block"; // Hiển thị thẻ có id="Test6"
            } else {
              test6.style.display = "none"; // Ẩn thẻ có id="Test6"
            }
          } else {
            // Ngược lại, ẩn các phần tử có id="kvtm", arrowUp và arrowDown
            element6.forEach((element6) => {
              element6.style.display = "none";
            });
            arrow6.forEach((el) => {
              el.style.display = "none";
            });
            Image6.classList.remove("glow-effect");
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
        const productss1 = document.querySelectorAll(".productss1");
        if (currentIndex1 > 0) {
          currentIndex1--;
          navigateTo(productss1, currentIndex1);
        }
      });

      document.getElementById("arrowDown1").addEventListener("click", () => {
        const productss1 = document.querySelectorAll(".productss1");
        if (currentIndex1 < productss1.length - 1) {
          currentIndex1++;
          navigateTo(productss1, currentIndex1);
        }
      });

      let currentIndex6 = 0; // Vị trí phần tử hiện tại

      document.getElementById("arrowUp6").addEventListener("click", () => {
        const productss6 = document.querySelectorAll(".productss6");
        if (currentIndex6 > 0) {
          currentIndex6--;
          navigateTo(productss6, currentIndex6);
        }
      });

      document.getElementById("arrowDown6").addEventListener("click", () => {
        const productss6 = document.querySelectorAll(".productss6");
        if (currentIndex6 < productss6.length - 1) {
          currentIndex6++;
          navigateTo(productss6, currentIndex6);
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
          var url = "https://m.me/61569836535180";
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
