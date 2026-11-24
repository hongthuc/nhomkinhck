<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nhôm Kính CK - Cửa Nhôm Xingfa & Cửa Kính Cường Lực Đà Nẵng | nhomkinhck.com</title>
  <meta name="description" content="Nhôm Kính CK (nhomkinhck.com) chuyên thiết kế, gia công, thi công Cửa nhôm Xingfa nhập khẩu, Cửa kính cường lực, Cửa nhựa lõi thép, Cầu thang kính, Phòng tắm kính uy tín tại 446 Ngô Quyền, Sơn Trà, Đà Nẵng. Hotline: 0918.060.633." />

  <!-- Meta Open Graph & Twitter Card: Hiển thị ảnh thumbnail là Logo Nhôm Kính CK khi chia sẻ link trên Zalo/Facebook -->
  <meta property="og:type" content="website" />
  <meta property="og:site_name" content="Nhôm Kính CK" />
  <meta property="og:url" content="https://nhomkinhck.com/" />
  <meta property="og:title" content="Nhôm Kính CK - Cửa Nhôm Xingfa & Kính Cường Lực Đà Nẵng" />
  <meta property="og:description" content="Thi công cửa nhôm Xingfa chính hãng, cửa kính cường lực, cầu thang kính, phòng tắm kính giá tốt tại Đà Nẵng. Địa chỉ: 446 Ngô Quyền, Sơn Trà. Hotline: 0918.060.633." />
  <meta property="og:image" content="https://nhomkinhck.com/assets/logo-nhom-kinh-ck-thumbnail.png" />
  <meta property="og:image:width" content="1200" />
  <meta property="og:image:height" content="630" />
  <meta property="og:image:alt" content="Logo Nhôm Kính CK - nhomkinhck.com" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="Nhôm Kính CK - nhomkinhck.com" />
  <meta name="twitter:description" content="Chuyên cửa nhôm Xingfa & kính cường lực cao cấp tại Đà Nẵng - Hotline 0918.060.633" />
  <meta name="twitter:image" content="https://nhomkinhck.com/assets/logo-nhom-kinh-ck-thumbnail.png" />

  <!-- Favicon Logo Nhôm Kính CK -->
  <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='14' fill='%230b3c68'/%3E%3Cpath d='M14 14h36v36H14z' fill='none' stroke='%2338bdf8' stroke-width='3'/%3E%3Cpath d='M28 22c-6 0-10 4-10 10s4 10 10 10h4v-5h-4c-3 0-5-2-5-5s2-5 5-5h4v-5h-4zm8 0v20h5v-7l6 7h6l-7-9 7-11h-6l-6 9v-9h-5z' fill='%23ffffff'/%3E%3Crect x='42' y='12' width='10' height='4' rx='2' fill='%23f59e0b'/%3E%3C/svg%3E" />

  <!-- Font Inter chuẩn hiện đại & sắc nét tiếng Việt -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet" />

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'system-ui', '-apple-system', 'sans-serif'],
          },
          colors: {
            brand: {
              navy: '#0b3c68',      /* Màu chủ đạo theo logo CK */
              dark: '#072a4a',      /* Xanh navy đậm cho hover/footer */
              sky: '#0284c7',       /* Xanh kính kiến trúc */
              light: '#e0f2fe',     /* Xanh kính nhạt nền phụ */
              amber: '#f59e0b',     /* Điểm nhấn vàng kim logo */
              sale: '#dc2626',      /* Đỏ nổi bật cho nhãn % giảm giá */
            }
          }
        }
      }
    };
  </script>

  <style>
    /* Reset cơ bản chống tràn viền & lệch sang phải trên mọi thiết bị */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      font-family: 'Inter', system-ui, -apple-system, sans-serif;
      color: #1e293b;
      background-color: #ffffff;
      scroll-behavior: smooth;
    }

    /* Container chuẩn 95% chiều ngang màn hình máy tính & gọn gàng trên điện thoại */
    .ck-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }
    @media (min-width: 1024px) {
      .ck-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Menu dropdown Flatsome mượt mà trên máy tính */
    .nav-item-dropdown:hover .nav-dropdown-panel,
    .nav-item-dropdown:focus-within .nav-dropdown-panel {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
    }
    .nav-dropdown-panel {
      opacity: 0;
      visibility: hidden;
      transform: translateY(8px);
      transition: all 0.2s ease;
    }

    /* Hiệu ứng chuyển mượt cho 2 banner cùng kích thước */
    .banner-track {
      display: flex;
      transition: transform 0.55s cubic-bezier(0.25, 0.8, 0.25, 1);
      width: 100%;
    }
    .banner-slide {
      flex: 0 0 100%;
      width: 100%;
      min-width: 100%;
    }

    /* Hiệu ứng gợn sóng nhẹ cho nút liên hệ nổi Hotline/Zalo */
    @keyframes ckPulse {
      0% { box-shadow: 0 0 0 0 rgba(11, 60, 104, 0.45); }
      70% { box-shadow: 0 0 0 10px rgba(11, 60, 104, 0); }
      100% { box-shadow: 0 0 0 0 rgba(11, 60, 104, 0); }
    }
    .ck-pulse-btn {
      animation: ckPulse 2.2s infinite;
    }

    /* Đường gạch chân tiêu đề phong cách Flatsome */
    .flatsome-section-title {
      position: relative;
      display: inline-block;
      padding-bottom: 10px;
    }
    .flatsome-section-title::after {
      content: "";
      position: absolute;
      left: 50%;
      bottom: 0;
      transform: translateX(-50%);
      width: 64px;
      height: 3px;
      border-radius: 999px;
      background: linear-gradient(90deg, #0b3c68, #0284c7, #f59e0b);
    }

    /* Đảm bảo hình ảnh không làm vỡ khung */
    img {
      max-width: 100%;
      display: block;
    }

    /* Ẩn scrollbar cho thanh tab lọc dự án trên mobile */
    .no-scrollbar::-webkit-scrollbar {
      display: none;
    }
    .no-scrollbar {
      -ms-overflow-style: none;
      scrollbar-width: none;
    }
  </style>
</head>

<body class="bg-white text-slate-800 antialiased">

  <!-- ===================================================================== -->
  <!-- [FLATSOME TOP BAR] Thông tin ngắn địa chỉ & giờ làm việc               -->
  <!-- ===================================================================== -->
  <div class="bg-brand-dark text-slate-100 text-xs border-b border-white/10">
    <div class="ck-container py-2 flex flex-wrap items-center justify-between gap-2">
      <div class="flex items-center gap-3 flex-wrap">
        <span class="inline-flex items-center gap-1.5">
          <svg class="w-3.5 h-3.5 text-brand-amber shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/>
            <path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/>
          </svg>
          <span>446 Ngô Quyền, Sơn Trà, Đà Nẵng</span>
        </span>
        <span class="hidden sm:inline text-white/30">|</span>
        <span class="hidden sm:inline-flex items-center gap-1.5">
          <svg class="w-3.5 h-3.5 text-brand-amber shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"/>
          </svg>
          <span>Làm việc 24/7 - Khảo sát miễn phí</span>
        </span>
      </div>
      <div class="flex items-center gap-3">
        <span class="hidden md:inline text-slate-300">Website: <strong class="text-white">nhomkinhck.com</strong></span>
        <span class="hidden md:inline text-white/30">|</span>
        <a href="tel:0918060633" class="inline-flex items-center gap-1 font-semibold text-brand-amber hover:text-amber-300 transition">
          <svg class="w-3.5 h-3.5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/>
          </svg>
          <span>0918.060.633</span>
        </a>
      </div>
    </div>
  </div>

  <!-- ===================================================================== -->
  <!-- [FLATSOME HEADER] Logo gọn nhỏ + Thanh tìm kiếm (KHÔNG có nút Gọi ngay) -->
  <!-- ===================================================================== -->
  <header class="sticky top-0 z-40 bg-white shadow-sm border-b border-slate-200/80">
    <!-- Hàng trên: Logo gọn nhỏ + Tìm kiếm + Nút Menu Mobile -->
    <div class="ck-container py-2.5 flex items-center justify-between gap-3">
      <!-- Logo Nhôm Kính CK chuyên nghiệp, chỉnh gọn nhỏ -->
      <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group focus:outline-none" aria-label="Trang chủ Nhôm Kính CK">
        <svg class="w-9 h-9 md:w-10 md:h-10 shrink-0 transition-transform duration-300 group-hover:scale-105" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
          <defs>
            <linearGradient id="ckLogoGrad" x1="0" y1="0" x2="64" y2="64" gradientUnits="userSpaceOnUse">
              <stop offset="0%" stop-color="#0b3c68"/>
              <stop offset="100%" stop-color="#0284c7"/>
            </linearGradient>
          </defs>
          <!-- Nền bo tròn khung kiến trúc -->
          <rect x="2" y="2" width="60" height="60" rx="14" fill="url(#ckLogoGrad)"/>
          <!-- Đường khung cửa nhôm kính tinh tế -->
          <rect x="8" y="8" width="48" height="48" rx="9" stroke="#e0f2fe" stroke-opacity="0.35" stroke-width="2"/>
          <!-- Đường ánh sáng kính chéo -->
          <path d="M12 46L46 12" stroke="#ffffff" stroke-opacity="0.14" stroke-width="6" stroke-linecap="round"/>
          <!-- Chữ C sắc nét -->
          <path d="M29.5 22.5H24.5C20.2 22.5 17 25.8 17 32C17 38.2 20.2 41.5 24.5 41.5H29.5" stroke="#ffffff" stroke-width="4.4" stroke-linecap="round"/>
          <!-- Chữ K mạnh mẽ kết hợp thanh vàng kim -->
          <path d="M35.5 20.5V43.5" stroke="#ffffff" stroke-width="4.4" stroke-linecap="round"/>
          <path d="M47 21.5L37 32L47.5 43" stroke="#f59e0b" stroke-width="4.4" stroke-linecap="round" stroke-linejoin="round"/>
        </svg>
        <div class="leading-tight">
          <div class="text-sm sm:text-base md:text-lg font-extrabold tracking-tight text-brand-navy">
            NHÔM KÍNH <span class="text-brand-sky">CK</span>
          </div>
          <div class="text-[10px] sm:text-[11px] font-medium text-slate-500 tracking-wide">
            nhomkinhck.com
          </div>
        </div>
      </a>

      <!-- Thanh tìm kiếm sản phẩm gọn gàng trên máy tính & máy tính bảng -->
      <div class="hidden md:flex items-center flex-1 max-w-md mx-4">
        <div class="relative w-full">
          <input
            id="desktopSearchInput"
            type="text"
            placeholder="Tìm cửa nhôm Xingfa, kính cường lực, cầu thang..."
            class="w-full pl-4 pr-10 py-2 text-xs lg:text-sm bg-slate-50 border border-slate-300 rounded-full focus:outline-none focus:border-brand-sky focus:bg-white transition"
          />
          <button
            type="button"
            onclick="handleProductSearch()"
            aria-label="Tìm kiếm sản phẩm"
            class="absolute right-1.5 top-1/2 -translate-y-1/2 w-7 h-7 flex items-center justify-center rounded-full bg-brand-navy text-white hover:bg-brand-sky transition"
          >
            <svg class="w-3.5 h-3.5" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" d="M21 21l-4.35-4.35M17 11a6 6 0 11-12 0 6 6 0 0112 0z"/>
            </svg>
          </button>
        </div>
      </div>

      <!-- Khu vực phải header: Chỉ hiện thông tin gọn & nút mở menu mobile (không để nút Gọi Ngay) -->
      <div class="flex items-center gap-2.5 shrink-0">
        <a href="#form-bao-gia" class="hidden sm:inline-flex items-center gap-1.5 px-3.5 py-2 rounded-full bg-brand-light text-brand-navy text-xs font-semibold hover:bg-brand-navy hover:text-white transition">
          <svg class="w-3.5 h-3.5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"/>
          </svg>
          <span>Nhận báo giá</span>
        </a>

        <!-- Nút mở menu trên điện thoại -->
        <button
          id="mobileMenuToggle"
          type="button"
          onclick="toggleMobileMenu()"
          aria-label="Mở danh mục trang web"
          class="lg:hidden inline-flex items-center justify-center p-2.5 rounded-lg border border-slate-200 bg-slate-50 text-brand-navy hover:bg-brand-navy hover:text-white transition"
        >
          <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16M4 18h16"/>
          </svg>
        </button>
      </div>
    </div>

    <!-- ===================================================================== -->
    <!-- [FLATSOME NAVIGATION BAR] Danh mục máy tính viết liền trên 1 hàng      -->
    <!-- Chữ nhỏ gọn, tuyệt đối KHÔNG xuống dòng tên danh mục, KHÔNG tràn viền -->
    <!-- ===================================================================== -->
    <nav class="hidden lg:block bg-brand-navy text-white border-t border-white/10" aria-label="Danh mục chính">
      <div class="ck-container">
        <ul class="flex items-center justify-between w-full list-none m-0 p-0">
          <li class="shrink-0">
            <a href="#trang-chu" class="block px-2.5 xl:px-3.5 py-2.5 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight whitespace-nowrap hover:bg-brand-sky transition rounded-sm">
              Trang chủ
            </a>
          </li>
          <li class="shrink-0">
            <a href="#gioi-thieu" class="block px-2.5 xl:px-3.5 py-2.5 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight whitespace-nowrap hover:bg-brand-sky transition rounded-sm">
              Giới thiệu
            </a>
          </li>

          <!-- Dropdown: Cửa nhôm xingfa -->
          <li class="relative shrink-0 nav-item-dropdown">
            <a href="#san-pham-xingfa" onclick="filterProductsByCategory('xingfa')" class="flex items-center gap-1 px-2.5 xl:px-3.5 py-2.5 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight whitespace-nowrap hover:bg-brand-sky transition rounded-sm">
              <span>Cửa nhôm xingfa</span>
              <svg class="w-3 h-3 opacity-80 shrink-0" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/>
              </svg>
            </a>
            <ul class="nav-dropdown-panel absolute left-0 top-full w-56 bg-white text-slate-700 shadow-xl rounded-b-lg border border-slate-200 py-1.5 z-50 list-none m-0">
              <li><a href="#san-pham-xingfa" onclick="highlightProduct('xingfa-1-canh')" class="block px-4 py-2 text-xs font-medium hover:bg-brand-light hover:text-brand-navy whitespace-nowrap transition">+ Cửa nhôm xingfa 1 cánh</a></li>
              <li><a href="#san-pham-xingfa" onclick="highlightProduct('xingfa-2-canh')" class="block px-4 py-2 text-xs font-medium hover:bg-brand-light hover:text-brand-navy whitespace-nowrap transition">+ Cửa nhôm xingfa 2 cánh</a></li>
              <li><a href="#san-pham-xingfa" onclick="highlightProduct('xingfa-3-canh')" class="block px-4 py-2 text-xs font-medium hover:bg-brand-light hover:text-brand-navy whitespace-nowrap transition">+ Cửa nhôm xingfa 3 cánh</a></li>
              <li><a href="#san-pham-xingfa" onclick="highlightProduct('xingfa-4-canh')" class="block px-4 py-2 text-xs font-medium hover:bg-brand-light hover:text-brand-navy whitespace-nowrap transition">+ Cửa nhôm xingfa 4 cánh</a></li>
              <li><a href="#san-pham-xingfa" onclick="highlightProduct('xingfa-xep-truot')" class="block px-4 py-2 text-xs font-medium hover:bg-brand-light hover:text-brand-navy whitespace-nowrap transition">+ Cửa nhôm xingfa 5 cánh</a></li>
            </ul>
          </li>

          <li class="shrink-0">
            <a href="#danh-muc-san-pham" class="block px-2.5 xl:px-3.5 py-2.5 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight whitespace-nowrap hover:bg-brand-sky transition rounded-sm">
              Cửa kính cường lực
            </a>
          </li>

          <!-- Dropdown: Sản phẩm -->
          <li class="relative shrink-0 nav-item-dropdown">
            <a href="#danh-muc-san-pham" class="flex items-center gap-1 px-2.5 xl:px-3.5 py-2.5 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight whitespace-nowrap hover:bg-brand-sky transition rounded-sm">
              <span>Sản phẩm</span>
              <svg class="w-3 h-3 opacity-80 shrink-0" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/>
              </svg>
            </a>
            <ul class="nav-dropdown-panel absolute left-0 top-full w-52 bg-white text-slate-700 shadow-xl rounded-b-lg border border-slate-200 py-1.5 z-50 list-none m-0">
              <li><a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Cửa nhôm xingfa')" class="block px-4 py-2 text-xs font-medium hover:bg-brand-light hover:text-brand-navy whitespace-nowrap transition">+ Cửa nhôm xingfa</a></li>
              <li><a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Cửa nhựa lõi thép')" class="block px-4 py-2 text-xs font-medium hover:bg-brand-light hover:text-brand-navy whitespace-nowrap transition">+ Cửa nhựa lõi thép</a></li>
              <li><a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Cửa kính tự động')" class="block px-4 py-2 text-xs font-medium hover:bg-brand-light hover:text-brand-navy whitespace-nowrap transition">+ Cửa kính tự động</a></li>
              <li><a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Cầu thang kính')" class="block px-4 py-2 text-xs font-medium hover:bg-brand-light hover:text-brand-navy whitespace-nowrap transition">+ Cầu thang kính</a></li>
              <li><a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Kính ốp bếp')" class="block px-4 py-2 text-xs font-medium hover:bg-brand-light hover:text-brand-navy whitespace-nowrap transition">+ Kính ốp bếp</a></li>
              <li><a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Phòng tắm kính')" class="block px-4 py-2 text-xs font-medium hover:bg-brand-light hover:text-brand-navy whitespace-nowrap transition">+ Phòng tắm kính</a></li>
            </ul>
          </li>

          <li class="shrink-0">
            <a href="#cong-trinh" class="block px-2.5 xl:px-3.5 py-2.5 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight whitespace-nowrap hover:bg-brand-sky transition rounded-sm">
              Công trình
            </a>
          </li>
          <li class="shrink-0">
            <a href="#bang-bao-gia" class="block px-2.5 xl:px-3.5 py-2.5 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight whitespace-nowrap hover:bg-brand-sky transition rounded-sm">
              Báo giá
            </a>
          </li>
          <li class="shrink-0">
            <a href="#tin-tuc" class="block px-2.5 xl:px-3.5 py-2.5 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight whitespace-nowrap hover:bg-brand-sky transition rounded-sm">
              Tin tức
            </a>
          </li>
          <li class="shrink-0">
            <a href="#lien-he" class="block px-2.5 xl:px-3.5 py-2.5 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight whitespace-nowrap hover:bg-brand-sky transition rounded-sm">
              Liên hệ
            </a>
          </li>
        </ul>
      </div>
    </nav>
  </header>

  <!-- ===================================================================== -->
  <!-- [MOBILE DRAWER MENU] Danh mục tối ưu trượt đẹp trên điện thoại         -->
  <!-- ===================================================================== -->
  <div id="mobileMenuOverlay" onclick="closeMobileMenu()" class="fixed inset-0 bg-slate-900/55 z-50 hidden transition-opacity"></div>
  <aside id="mobileMenuDrawer" class="fixed top-0 left-0 bottom-0 w-[84%] max-w-[320px] bg-white z-50 transform -translate-x-full transition-transform duration-300 shadow-2xl flex flex-col">
    <div class="p-4 bg-brand-navy text-white flex items-center justify-between">
      <div class="font-bold text-sm tracking-wide">DANH MỤC NHÔM KÍNH CK</div>
      <button type="button" onclick="closeMobileMenu()" aria-label="Đóng menu" class="p-1.5 rounded-lg bg-white/10 hover:bg-white/20">
        <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/>
        </svg>
      </button>
    </div>

    <!-- Ô tìm kiếm trong menu mobile -->
    <div class="p-3 border-b border-slate-100 bg-slate-50">
      <div class="relative">
        <input id="mobileSearchInput" type="text" placeholder="Tìm sản phẩm nhôm kính..." class="w-full pl-3.5 pr-9 py-2 text-xs rounded-lg border border-slate-300 focus:outline-none focus:border-brand-sky bg-white" />
        <button type="button" onclick="handleMobileSearch()" class="absolute right-1.5 top-1/2 -translate-y-1/2 p-1.5 text-brand-navy">
          <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" d="M21 21l-4.35-4.35M17 11a6 6 0 11-12 0 6 6 0 0112 0z"/>
          </svg>
        </button>
      </div>
    </div>

    <div class="flex-1 overflow-y-auto p-3 space-y-1 text-sm">
      <a href="#trang-chu" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg font-semibold text-brand-navy hover:bg-brand-light">Trang chủ</a>
      <a href="#gioi-thieu" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg font-semibold text-slate-700 hover:bg-brand-light">Giới thiệu</a>

      <!-- Accordion: Cửa nhôm xingfa -->
      <div class="border border-slate-100 rounded-lg overflow-hidden">
        <button type="button" onclick="toggleMobileSubmenu('subXingfa')" class="w-full flex items-center justify-between px-3 py-2.5 font-semibold text-slate-700 bg-slate-50/70 hover:bg-brand-light">
          <span>Cửa nhôm xingfa</span>
          <svg class="w-4 h-4 text-slate-500" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
        </button>
        <div id="subXingfa" class="hidden bg-white pl-4 pr-2 py-1 space-y-1 text-xs border-t border-slate-100">
          <a href="#san-pham-xingfa" onclick="closeMobileMenu(); highlightProduct('xingfa-1-canh')" class="block py-2 text-slate-600 hover:text-brand-navy">+ Cửa nhôm xingfa 1 cánh</a>
          <a href="#san-pham-xingfa" onclick="closeMobileMenu(); highlightProduct('xingfa-2-canh')" class="block py-2 text-slate-600 hover:text-brand-navy">+ Cửa nhôm xingfa 2 cánh</a>
          <a href="#san-pham-xingfa" onclick="closeMobileMenu(); highlightProduct('xingfa-3-canh')" class="block py-2 text-slate-600 hover:text-brand-navy">+ Cửa nhôm xingfa 3 cánh</a>
          <a href="#san-pham-xingfa" onclick="closeMobileMenu(); highlightProduct('xingfa-4-canh')" class="block py-2 text-slate-600 hover:text-brand-navy">+ Cửa nhôm xingfa 4 cánh</a>
          <a href="#san-pham-xingfa" onclick="closeMobileMenu(); highlightProduct('xingfa-xep-truot')" class="block py-2 text-slate-600 hover:text-brand-navy">+ Cửa nhôm xingfa 5 cánh</a>
        </div>
      </div>

      <a href="#danh-muc-san-pham" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg font-semibold text-slate-700 hover:bg-brand-light">Cửa kính cường lực</a>

      <!-- Accordion: Sản phẩm -->
      <div class="border border-slate-100 rounded-lg overflow-hidden">
        <button type="button" onclick="toggleMobileSubmenu('subSanPham')" class="w-full flex items-center justify-between px-3 py-2.5 font-semibold text-slate-700 bg-slate-50/70 hover:bg-brand-light">
          <span>Sản phẩm</span>
          <svg class="w-4 h-4 text-slate-500" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
        </button>
        <div id="subSanPham" class="hidden bg-white pl-4 pr-2 py-1 space-y-1 text-xs border-t border-slate-100">
          <a href="#danh-muc-san-pham" onclick="closeMobileMenu(); selectCategoryQuote('Cửa nhôm xingfa')" class="block py-2 text-slate-600 hover:text-brand-navy">+ Cửa nhôm xingfa</a>
          <a href="#danh-muc-san-pham" onclick="closeMobileMenu(); selectCategoryQuote('Cửa nhựa lõi thép')" class="block py-2 text-slate-600 hover:text-brand-navy">+ Cửa nhựa lõi thép</a>
          <a href="#danh-muc-san-pham" onclick="closeMobileMenu(); selectCategoryQuote('Cửa kính tự động')" class="block py-2 text-slate-600 hover:text-brand-navy">+ Cửa kính tự động</a>
          <a href="#danh-muc-san-pham" onclick="closeMobileMenu(); selectCategoryQuote('Cầu thang kính')" class="block py-2 text-slate-600 hover:text-brand-navy">+ Cầu thang kính</a>
          <a href="#danh-muc-san-pham" onclick="closeMobileMenu(); selectCategoryQuote('Kính ốp bếp')" class="block py-2 text-slate-600 hover:text-brand-navy">+ Kính ốp bếp</a>
          <a href="#danh-muc-san-pham" onclick="closeMobileMenu(); selectCategoryQuote('Phòng tắm kính')" class="block py-2 text-slate-600 hover:text-brand-navy">+ Phòng tắm kính</a>
        </div>
      </div>

      <a href="#cong-trinh" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg font-semibold text-slate-700 hover:bg-brand-light">Công trình</a>
      <a href="#bang-bao-gia" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg font-semibold text-slate-700 hover:bg-brand-light">Báo giá</a>
      <a href="#tin-tuc" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg font-semibold text-slate-700 hover:bg-brand-light">Tin tức</a>
      <a href="#lien-he" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg font-semibold text-slate-700 hover:bg-brand-light">Liên hệ</a>
    </div>

    <div class="p-4 border-t border-slate-200 bg-slate-50 text-xs text-slate-600 space-y-1">
      <div class="font-bold text-brand-navy">NHÔM KÍNH CK ĐÀ NẴNG</div>
      <div>446 Ngô Quyền, Sơn Trà, Đà Nẵng</div>
      <div class="font-semibold text-brand-sky">Hotline/Zalo: 0918.060.633</div>
    </div>
  </aside>

  <!-- ===================================================================== -->
  <!-- [FLATSOME SECTION 1: HERO BANNER SLIDER]                              -->
  <!-- 2 ảnh banner tự trượt chuyên nghiệp, kích thước bằng nhau hoàn toàn,  -->
  <!-- hình ảnh và chữ nằm gọn trong banner, chữ cách xa viền, đủ chữ 100%   -->
  <!-- ===================================================================== -->
  <section id="trang-chu" class="py-3 md:py-4 bg-slate-50">
    <div class="ck-container">
      <div
        id="heroBannerWrapper"
        class="relative w-full overflow-hidden rounded-2xl shadow-lg bg-brand-navy"
      >
        <div id="bannerTrack" class="banner-track">

          <!-- BANNER 1 -->
          <div class="banner-slide">
            <div class="relative w-full h-[360px] sm:h-[380px] md:h-[420px] lg:h-[460px] bg-gradient-to-br from-[#072a4a] via-[#0b3c68] to-[#0284c7] overflow-hidden flex items-center">
              <!-- Họa tiết kiến trúc khung nhôm kính tinh tế làm nền -->
              <div class="absolute inset-0 opacity-15 pointer-events-none">
                <svg class="w-full h-full" preserveAspectRatio="none" viewBox="0 0 1200 460" fill="none">
                  <path d="M0 380L480 0H660L180 460H0V380Z" fill="#ffffff"/>
                  <path d="M740 0H900L440 460H280L740 0Z" fill="#38bdf8"/>
                  <rect x="60" y="36" width="1080" height="388" rx="18" stroke="#ffffff" stroke-width="1.5" stroke-dasharray="8 8"/>
                </svg>
              </div>

              <!-- Nội dung Banner 1: Padding rộng cách xa viền để không bao giờ thiếu chữ -->
              <div class="relative z-10 w-full h-full px-10 sm:px-14 md:px-16 lg:px-20 py-7 sm:py-9 flex flex-col md:flex-row items-center justify-between gap-4 md:gap-8">
                <!-- Cột chữ bên trái -->
                <div class="w-full md:w-[58%] text-white text-center md:text-left flex flex-col justify-center">
                  <div class="text-[11px] sm:text-xs font-bold uppercase tracking-widest text-brand-amber mb-2">
                    NHÔM KÍNH CK ĐÀ NẴNG • NHOMKINHCK.COM
                  </div>
                  <h1 class="text-lg sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-snug mb-2.5 sm:mb-3">
                    Cửa Nhôm Xingfa Nhập Khẩu Chính Hãng Tem Đỏ
                  </h1>
                  <p class="text-xs sm:text-sm md:text-base text-sky-100 leading-relaxed mb-4 sm:mb-5 max-w-xl mx-auto md:mx-0">
                    Gia công chuẩn kỹ thuật, phụ kiện Kinlong đồng bộ, cách âm cách nhiệt vượt trội. Khảo sát &amp; lắp đặt trọn gói tại Đà Nẵng.
                  </p>
                  <div class="flex flex-wrap items-center justify-center md:justify-start gap-2.5">
                    <a href="#san-pham-xingfa" class="px-4 sm:px-6 py-2 sm:py-2.5 rounded-lg bg-brand-amber text-slate-900 font-bold text-xs sm:text-sm hover:bg-amber-400 transition shadow-md">
                      Xem sản phẩm ưu đãi
                    </a>
                    <a href="#form-bao-gia" class="px-4 sm:px-6 py-2 sm:py-2.5 rounded-lg bg-white/15 border border-white/40 text-white font-semibold text-xs sm:text-sm hover:bg-white hover:text-brand-navy transition">
                      Nhận báo giá nhanh
                    </a>
                  </div>
                </div>

                <!-- Cột ảnh thực tế nằm gọn trong banner (ẩn trên màn siêu nhỏ để chữ thoáng 100%, hiện từ sm trở lên) -->
                <div class="hidden sm:flex w-[44%] md:w-[40%] h-[220px] md:h-[290px] lg:h-[340px] items-center justify-center">
                  <div class="w-full h-full rounded-xl overflow-hidden border-2 border-white/30 shadow-2xl bg-white/10 p-1.5">
                    <img
                      data-drive-id="1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-"
                      alt="Cửa đi mở quay 4 cánh nhôm Xingfa Nhôm Kính CK"
                      class="w-full h-full object-cover rounded-lg"
                    />
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- BANNER 2 (Cùng kích thước 100% với Banner 1) -->
          <div class="banner-slide">
            <div class="relative w-full h-[360px] sm:h-[380px] md:h-[420px] lg:h-[460px] bg-gradient-to-br from-[#06233d] via-[#0d4a7c] to-[#0369a1] overflow-hidden flex items-center">
              <div class="absolute inset-0 opacity-15 pointer-events-none">
                <svg class="w-full h-full" preserveAspectRatio="none" viewBox="0 0 1200 460" fill="none">
                  <circle cx="1050" cy="80" r="220" fill="#38bdf8"/>
                  <circle cx="150" cy="400" r="180" fill="#f59e0b"/>
                  <rect x="60" y="36" width="1080" height="388" rx="18" stroke="#ffffff" stroke-width="1.5" stroke-dasharray="8 8"/>
                </svg>
              </div>

              <!-- Nội dung Banner 2: Padding rộng cách xa viền -->
              <div class="relative z-10 w-full h-full px-10 sm:px-14 md:px-16 lg:px-20 py-7 sm:py-9 flex flex-col md:flex-row items-center justify-between gap-4 md:gap-8">
                <div class="w-full md:w-[58%] text-white text-center md:text-left flex flex-col justify-center">
                  <div class="text-[11px] sm:text-xs font-bold uppercase tracking-widest text-brand-amber mb-2">
                    THI CÔNG CHUYÊN NGHIỆP • BẢO HÀNH DÀI HẠN
                  </div>
                  <h2 class="text-lg sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-snug mb-2.5 sm:mb-3">
                    Cửa Kính Cường Lực &amp; Công Trình Khách Sạn Đà Nẵng
                  </h2>
                  <p class="text-xs sm:text-sm md:text-base text-sky-100 leading-relaxed mb-4 sm:mb-5 max-w-xl mx-auto md:mx-0">
                    Cung cấp giải pháp tổng thể: Phòng tắm kính, cầu thang kính, cửa kính tự động, mặt dựng cho nhà phố, resort &amp; khách sạn.
                  </p>
                  <div class="flex flex-wrap items-center justify-center md:justify-start gap-2.5">
                    <a href="#cong-trinh" class="px-4 sm:px-6 py-2 sm:py-2.5 rounded-lg bg-brand-amber text-slate-900 font-bold text-xs sm:text-sm hover:bg-amber-400 transition shadow-md">
                      Xem dự án thực tế
                    </a>
                    <a href="tel:0918060633" class="px-4 sm:px-6 py-2 sm:py-2.5 rounded-lg bg-white/15 border border-white/40 text-white font-semibold text-xs sm:text-sm hover:bg-white hover:text-brand-navy transition">
                      Tư vấn: 0918.060.633
                    </a>
                  </div>
                </div>

                <div class="hidden sm:flex w-[44%] md:w-[40%] h-[220px] md:h-[290px] lg:h-[340px] items-center justify-center">
                  <div class="w-full h-full rounded-xl overflow-hidden border-2 border-white/30 shadow-2xl bg-white/10 p-1.5">
                    <img
                      data-drive-id="1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ"
                      alt="Dự án thi công Nhôm Kính CK tại Đà Nẵng"
                      class="w-full h-full object-cover rounded-lg"
                    />
                  </div>
                </div>
              </div>
            </div>
          </div>

        </div>

        <!-- Nút điều hướng banner gọn gàng sát 2 mép không đè chữ -->
        <button
          type="button"
          onclick="prevSlide()"
          aria-label="Banner trước"
          class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-brand-amber hover:text-slate-900 text-white flex items-center justify-center transition"
        >
          <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M15 19l-7-7 7-7"/></svg>
        </button>
        <button
          type="button"
          onclick="nextSlide()"
          aria-label="Banner tiếp theo"
          class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-brand-amber hover:text-slate-900 text-white flex items-center justify-center transition"
        >
          <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7"/></svg>
        </button>

        <!-- Dấu chấm chỉ báo slide -->
        <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
          <button type="button" onclick="goToSlide(0)" id="dot-0" aria-label="Chuyển đến banner 1" class="w-7 h-2 rounded-full bg-brand-amber transition-all"></button>
          <button type="button" onclick="goToSlide(1)" id="dot-1" aria-label="Chuyển đến banner 2" class="w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all"></button>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- [FLATSOME SECTION 2: GIỚI THIỆU NHÔM KÍNH CK & THÔNG SỐ UY TÍN]       -->
  <!-- ===================================================================== -->
  <section id="gioi-thieu" class="py-10 md:py-14 bg-white">
    <div class="ck-container">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
        <div class="lg:col-span-7">
          <div class="text-xs font-bold uppercase tracking-wider text-brand-sky mb-1.5">VỀ CHÚNG TÔI</div>
          <h2 class="text-xl sm:text-2xl md:text-3xl font-extrabold text-brand-navy mb-3.5 leading-snug">
            CÔNG TY CỬA NHÔM XINGFA ĐÀ NẴNG – NHÔM KÍNH CK
          </h2>
          <p class="text-sm md:text-[15px] text-slate-600 leading-relaxed mb-3">
            <strong>Nhôm Kính CK</strong> (<span class="text-brand-navy font-semibold">nhomkinhck.com</span>) tọa lạc tại <strong>446 Ngô Quyền, Sơn Trà, Đà Nẵng</strong>, là đơn vị chuyên thiết kế, gia công sản xuất và thi công lắp đặt các hạng mục nhôm kính cao cấp hàng đầu tại khu vực Đà Nẵng và Miền Trung.
          </p>
          <p class="text-sm md:text-[15px] text-slate-600 leading-relaxed mb-5">
            Với phương châm <strong>“Bền đẹp cho mọi công trình”</strong>, chúng tôi cung cấp đồng bộ các dòng sản phẩm: Cửa nhôm Xingfa nhập khẩu tem đỏ, Cửa kính cường lực, Cửa nhựa lõi thép, Cửa kính tự động, Cầu thang kính, Kính ốp bếp và Phòng tắm kính với chính sách bảo hành minh bạch và giá thành tối ưu trực tiếp từ xưởng.
          </p>

          <!-- 4 cam kết dịch vụ gọn gàng -->
          <div class="grid grid-cols-1 sm:grid-cols-2 gap-3 text-xs sm:text-sm">
            <div class="flex items-center gap-2.5 p-3 rounded-xl bg-slate-50 border border-slate-200/80">
              <span class="w-7 h-7 rounded-full bg-brand-navy text-white flex items-center justify-center shrink-0 text-xs font-bold">✓</span>
              <span>Khảo sát, tư vấn &amp; đo đạc miễn phí tận nơi</span>
            </div>
            <div class="flex items-center gap-2.5 p-3 rounded-xl bg-slate-50 border border-slate-200/80">
              <span class="w-7 h-7 rounded-full bg-brand-navy text-white flex items-center justify-center shrink-0 text-xs font-bold">✓</span>
              <span>Nhôm Xingfa &amp; phụ kiện Kinlong chính hãng</span>
            </div>
            <div class="flex items-center gap-2.5 p-3 rounded-xl bg-slate-50 border border-slate-200/80">
              <span class="w-7 h-7 rounded-full bg-brand-navy text-white flex items-center justify-center shrink-0 text-xs font-bold">✓</span>
              <span>Giá trực tiếp từ xưởng – Ưu đãi đến 20%</span>
            </div>
            <div class="flex items-center gap-2.5 p-3 rounded-xl bg-slate-50 border border-slate-200/80">
              <span class="w-7 h-7 rounded-full bg-brand-navy text-white flex items-center justify-center shrink-0 text-xs font-bold">✓</span>
              <span>Bảo hành chính hãng dài hạn, hỗ trợ 24/7</span>
            </div>
          </div>
        </div>

        <!-- 4 ô thống kê chuẩn Flatsome Counter Box -->
        <div class="lg:col-span-5 grid grid-cols-2 gap-3.5 sm:gap-4">
          <div class="p-5 rounded-2xl bg-brand-navy text-white text-center shadow-sm">
            <div class="text-2xl sm:text-3xl font-extrabold text-brand-amber">150+</div>
            <div class="text-xs sm:text-sm text-sky-100 mt-1 font-medium">Dự án đã hoàn thành</div>
          </div>
          <div class="p-5 rounded-2xl bg-slate-50 border border-slate-200 text-center">
            <div class="text-2xl sm:text-3xl font-extrabold text-brand-navy">50+</div>
            <div class="text-xs sm:text-sm text-slate-600 mt-1 font-medium">Kỹ thuật viên tay nghề cao</div>
          </div>
          <div class="p-5 rounded-2xl bg-slate-50 border border-slate-200 text-center">
            <div class="text-2xl sm:text-3xl font-extrabold text-brand-navy">100+</div>
            <div class="text-xs sm:text-sm text-slate-600 mt-1 font-medium">Mẫu sản phẩm chuẩn đẹp</div>
          </div>
          <div class="p-5 rounded-2xl bg-brand-sky text-white text-center shadow-sm">
            <div class="text-2xl sm:text-3xl font-extrabold">100%</div>
            <div class="text-xs sm:text-sm text-sky-50 mt-1 font-medium">Khách hàng hài lòng</div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- [FLATSOME SECTION 3: SẢN PHẨM CỬA NHÔM XINGFA ĐÀ NẴNG]                -->
  <!-- 2 cột trên điện thoại, 3 cột trên máy tính, nhãn % giảm giá góc trên  -->
  <!-- bên trái, tên sản phẩm đầy đủ không bị cắt hay tràn ra ngoài          -->
  <!-- ===================================================================== -->
  <section id="san-pham-xingfa" class="py-10 md:py-14 bg-slate-50 border-y border-slate-200/70">
    <div class="ck-container">
      <div class="text-center mb-7 md:mb-9">
        <h2 class="flatsome-section-title text-lg sm:text-2xl md:text-3xl font-extrabold text-brand-navy uppercase">
          BÁO GIÁ CỬA NHÔM XINGFA ĐÀ NẴNG
        </h2>
        <p class="text-xs sm:text-sm text-slate-500 mt-2.5 max-w-2xl mx-auto">
          Sản phẩm cửa nhôm Xingfa gia công chuẩn xác, kính cường lực an toàn, giảm giá ưu đãi trực tiếp từ xưởng Nhôm Kính CK
        </p>
      </div>

      <!-- Lưới sản phẩm: 2 cột cố định trên điện thoại, 3 cột trên máy tính -->
      <div id="productGrid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5 lg:gap-6">
        <!-- Dữ liệu sản phẩm được render tự động bằng JS từ danh sách chuẩn -->
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- [FLATSOME SECTION 4: DANH MỤC SẢN PHẨM NỔI BẬT (6 DANH MỤC)]         -->
  <!-- ===================================================================== -->
  <section id="danh-muc-san-pham" class="py-10 md:py-14 bg-white">
    <div class="ck-container">
      <div class="text-center mb-7 md:mb-9">
        <h2 class="flatsome-section-title text-lg sm:text-2xl md:text-3xl font-extrabold text-brand-navy uppercase">
          SẢN PHẨM NỔI BẬT
        </h2>
        <p class="text-xs sm:text-sm text-slate-500 mt-2.5">
          Các hạng mục nhôm kính kiến trúc chủ lực do Nhôm Kính CK sản xuất &amp; lắp đặt
        </p>
      </div>

      <!-- 2 cột trên điện thoại, 3 cột trên máy tính -->
      <div id="categoryGrid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5 lg:gap-6">
        <!-- Render từ JS với đúng 6 ảnh Google Drive danh mục -->
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- [FLATSOME SECTION 5: BẢNG BÁO GIÁ THAM KHẢO NHÔM KÍNH CK]            -->
  <!-- ===================================================================== -->
  <section id="bang-bao-gia" class="py-10 md:py-14 bg-slate-50 border-y border-slate-200/70">
    <div class="ck-container">
      <div class="text-center mb-7">
        <h2 class="flatsome-section-title text-lg sm:text-2xl md:text-3xl font-extrabold text-brand-navy uppercase">
          BẢNG GIÁ THI CÔNG THAM KHẢO
        </h2>
        <p class="text-xs sm:text-sm text-slate-500 mt-2.5">
          Đơn giá tính theo m² đã bao gồm kính cường lực / kính an toàn &amp; lắp đặt hoàn thiện tại Đà Nẵng
        </p>
      </div>

      <div class="bg-white rounded-2xl shadow-sm border border-slate-200 overflow-hidden">
        <div class="overflow-x-auto w-full">
          <table class="w-full text-left border-collapse min-w-[540px]">
            <thead>
              <tr class="bg-brand-navy text-white text-xs sm:text-sm">
                <th class="py-3.5 px-4 font-semibold">STT</th>
                <th class="py-3.5 px-4 font-semibold">Hạng mục cửa nhôm Xingfa &amp; kính</th>
                <th class="py-3.5 px-4 font-semibold">Hệ nhôm / Độ dày</th>
                <th class="py-3.5 px-4 font-semibold text-right">Đơn giá ưu đãi (VNĐ/m²)</th>
              </tr>
            </thead>
            <tbody class="divide-y divide-slate-200 text-xs sm:text-sm text-slate-700">
              <tr class="hover:bg-slate-50">
                <td class="py-3 px-4 font-semibold text-brand-navy">01</td>
                <td class="py-3 px-4 font-medium">Vách kính cố định nhôm Xingfa</td>
                <td class="py-3 px-4">Hệ 55 – dày 1.4mm</td>
                <td class="py-3 px-4 text-right font-bold text-brand-sale">1.450.000 ₫</td>
              </tr>
              <tr class="hover:bg-slate-50">
                <td class="py-3 px-4 font-semibold text-brand-navy">02</td>
                <td class="py-3 px-4 font-medium">Cửa sổ mở hất / mở quay nhôm Xingfa</td>
                <td class="py-3 px-4">Hệ 55 – dày 1.4mm</td>
                <td class="py-3 px-4 text-right font-bold text-brand-sale">1.750.000 ₫</td>
              </tr>
              <tr class="hover:bg-slate-50">
                <td class="py-3 px-4 font-semibold text-brand-navy">03</td>
                <td class="py-3 px-4 font-medium">Cửa đi mở quay 1 cánh, 2 cánh, 4 cánh Xingfa</td>
                <td class="py-3 px-4">Hệ 55 – dày 2.0mm</td>
                <td class="py-3 px-4 text-right font-bold text-brand-sale">1.890.000 ₫</td>
              </tr>
              <tr class="hover:bg-slate-50">
                <td class="py-3 px-4 font-semibold text-brand-navy">04</td>
                <td class="py-3 px-4 font-medium">Cửa đi mở xếp trượt gấp 4 – 5 – 6 cánh Xingfa</td>
                <td class="py-3 px-4">Hệ 63 – dày 2.0–2.4mm</td>
                <td class="py-3 px-4 text-right font-bold text-brand-sale">2.100.000 ₫</td>
              </tr>
              <tr class="hover:bg-slate-50">
                <td class="py-3 px-4 font-semibold text-brand-navy">05</td>
                <td class="py-3 px-4 font-medium">Cửa kính cường lực bản lề sàn 10mm – 12mm</td>
                <td class="py-3 px-4">Kính cường lực Việt Nhật</td>
                <td class="py-3 px-4 text-right font-bold text-brand-sale">750.000 ₫</td>
              </tr>
              <tr class="hover:bg-slate-50">
                <td class="py-3 px-4 font-semibold text-brand-navy">06</td>
                <td class="py-3 px-4 font-medium">Phòng tắm kính / Cầu thang kính / Kính ốp bếp</td>
                <td class="py-3 px-4">Kính cường lực 8–12mm + Inox 304</td>
                <td class="py-3 px-4 text-right font-bold text-brand-sale">Liên hệ báo giá</td>
              </tr>
            </tbody>
          </table>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- [FLATSOME SECTION 6: CÁC DỰ ÁN NỔI BẬT TẠI ĐÀ NẴNG]                   -->
  <!-- ===================================================================== -->
  <section id="cong-trinh" class="py-10 md:py-14 bg-white">
    <div class="ck-container">
      <div class="text-center mb-6 md:mb-8">
        <h2 class="flatsome-section-title text-lg sm:text-2xl md:text-3xl font-extrabold text-brand-navy uppercase">
          CÁC DỰ ÁN NỔI BẬT TẠI ĐÀ NẴNG
        </h2>
        <p class="text-xs sm:text-sm text-slate-500 mt-2.5">
          Công trình khách sạn, resort và tổ hợp nghỉ dưỡng tiêu biểu do Nhôm Kính CK thi công
        </p>

        <!-- Bộ lọc nhóm công trình gọn gàng giống mẫu Flatsome -->
        <div class="flex items-center justify-center gap-2 mt-5 overflow-x-auto no-scrollbar pb-1">
          <button type="button" onclick="filterProjects('all')" data-proj-tab="all" class="proj-tab-btn px-4 py-1.5 rounded-full text-xs font-semibold bg-brand-navy text-white transition whitespace-nowrap">
            Tất cả dự án
          </button>
          <button type="button" onclick="filterProjects('khach-san')" data-proj-tab="khach-san" class="proj-tab-btn px-4 py-1.5 rounded-full text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light hover:text-brand-navy transition whitespace-nowrap">
            Dự án Khách sạn
          </button>
          <button type="button" onclick="filterProjects('resort')" data-proj-tab="resort" class="proj-tab-btn px-4 py-1.5 rounded-full text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light hover:text-brand-navy transition whitespace-nowrap">
            Dự án Resort &amp; Biển
          </button>
        </div>
      </div>

      <div id="projectGrid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-6">
        <!-- Render 6 dự án Đà Nẵng từ JS -->
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- [FLATSOME SECTION 7: FORM YÊU CẦU & BÁO GIÁ TRANG CHỦ]                -->
  <!-- ===================================================================== -->
  <section id="form-bao-gia" class="py-10 md:py-14 bg-brand-navy text-white">
    <div class="ck-container">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-7 lg:gap-10 items-center">
        <!-- Cột trái: Thông tin tư vấn -->
        <div class="lg:col-span-5 space-y-4">
          <div class="text-xs font-bold uppercase tracking-widest text-brand-amber">
            ĐĂNG KÝ TƯ VẤN &amp; BÁO GIÁ MIỄN PHÍ
          </div>
          <h2 class="text-xl sm:text-2xl md:text-3xl font-extrabold leading-snug">
            Nhận Báo Giá Cửa Nhôm Xingfa &amp; Kính Cường Lực Chi Tiết Trong 15 Phút
          </h2>
          <p class="text-sm text-sky-100 leading-relaxed">
            Để lại thông tin hạng mục công trình của bạn, đội ngũ kỹ thuật <strong>Nhôm Kính CK</strong> sẽ liên hệ tư vấn mẫu mã phù hợp, báo giá chính xác theo kích thước thực tế và hẹn lịch khảo sát miễn phí tại Đà Nẵng.
          </p>
          <div class="space-y-2.5 pt-2 text-sm">
            <div class="flex items-center gap-3">
              <span class="w-8 h-8 rounded-lg bg-white/10 flex items-center justify-center text-brand-amber shrink-0">
                <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a2 2 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
              </span>
              <span>Showroom &amp; Xưởng: <strong>446 Ngô Quyền, Sơn Trà, Đà Nẵng</strong></span>
            </div>
            <div class="flex items-center gap-3">
              <span class="w-8 h-8 rounded-lg bg-white/10 flex items-center justify-center text-brand-amber shrink-0">
                <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
              </span>
              <span>Hotline / Zalo: <a href="tel:0918060633" class="font-bold text-brand-amber hover:underline">0918.060.633</a></span>
            </div>
          </div>
        </div>

        <!-- Cột phải: Form yêu cầu báo giá -->
        <div class="lg:col-span-7">
          <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="bg-white text-slate-800 rounded-2xl p-5 sm:p-7 shadow-xl space-y-4">
            <h3 class="text-base sm:text-lg font-bold text-brand-navy border-b border-slate-100 pb-3">
              Gửi yêu cầu báo giá trực tuyến
            </h3>
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
              <div>
                <label for="qName" class="block text-xs font-semibold text-slate-600 mb-1.5">Họ và tên *</label>
                <input id="qName" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand-sky focus:ring-2 focus:ring-brand-sky/20" />
              </div>
              <div>
                <label for="qPhone" class="block text-xs font-semibold text-slate-600 mb-1.5">Số điện thoại / Zalo *</label>
                <input id="qPhone" type="tel" required placeholder="Ví dụ: 0918.xxx.xxx" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand-sky focus:ring-2 focus:ring-brand-sky/20" />
              </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
              <div>
                <label for="qCategory" class="block text-xs font-semibold text-slate-600 mb-1.5">Hạng mục cần báo giá</label>
                <select id="qCategory" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 bg-white focus:outline-none focus:border-brand-sky focus:ring-2 focus:ring-brand-sky/20">
                  <option value="Cửa nhôm xingfa">Cửa nhôm Xingfa nhập khẩu</option>
                  <option value="Cửa kính cường lực">Cửa kính cường lực</option>
                  <option value="Cửa nhựa lõi thép">Cửa nhựa lõi thép</option>
                  <option value="Cửa kính tự động">Cửa kính tự động</option>
                  <option value="Cầu thang kính">Cầu thang kính</option>
                  <option value="Kính ốp bếp">Kính ốp bếp cường lực</option>
                  <option value="Phòng tắm kính">Phòng tắm kính</option>
                  <option value="Thi công trọn gói công trình">Thi công trọn gói nhà phố / khách sạn</option>
                </select>
              </div>
              <div>
                <label for="qAddress" class="block text-xs font-semibold text-slate-600 mb-1.5">Địa chỉ công trình</label>
                <input id="qAddress" type="text" placeholder="Quận/Huyện tại Đà Nẵng..." class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand-sky focus:ring-2 focus:ring-brand-sky/20" />
              </div>
            </div>

            <div>
              <label for="qNote" class="block text-xs font-semibold text-slate-600 mb-1.5">Ghi chú kích thước / Yêu cầu thêm</label>
              <textarea id="qNote" rows="3" placeholder="Ví dụ: Cần làm 1 bộ cửa đi 4 cánh nhôm Xingfa màu xám ghi, 2 cửa sổ mở hất..." class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand-sky focus:ring-2 focus:ring-brand-sky/20"></textarea>
            </div>

            <button type="submit" class="w-full py-3 px-6 rounded-xl bg-brand-navy hover:bg-brand-sky text-white font-bold text-sm transition shadow-md">
              GỬI YÊU CẦU NHẬN BÁO GIÁ NGAY
            </button>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- [FLATSOME SECTION 8: DANH MỤC CÁC BÀI VIẾT / TIN TỨC TRANG CHỦ]      -->
  <!-- ===================================================================== -->
  <section id="tin-tuc" class="py-10 md:py-14 bg-white">
    <div class="ck-container">
      <div class="text-center mb-7 md:mb-9">
        <h2 class="flatsome-section-title text-lg sm:text-2xl md:text-3xl font-extrabold text-brand-navy uppercase">
          TIN TỨC &amp; KINH NGHIỆM NHÔM KÍNH
        </h2>
        <p class="text-xs sm:text-sm text-slate-500 mt-2.5">
          Chia sẻ kiến thức lựa chọn cửa nhôm Xingfa, kính cường lực và bảo quản công trình bền đẹp
        </p>
      </div>

      <div id="newsGrid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 sm:gap-5">
        <!-- Render 4 bài viết chuyên ngành từ JS -->
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- [FLATSOME SECTION 9: ĐỐI TÁC CỦA CHÚNG TÔI (6 ẢNH ĐỐI TÁC)]          -->
  <!-- ===================================================================== -->
  <section class="py-8 md:py-12 bg-slate-50 border-y border-slate-200/70">
    <div class="ck-container">
      <div class="text-center mb-6">
        <h2 class="flatsome-section-title text-lg sm:text-2xl font-extrabold text-brand-navy uppercase">
          ĐỐI TÁC CỦA CHÚNG TÔI
        </h2>
      </div>
      <div id="partnerGrid" class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4 items-center">
        <!-- Render 6 logo đối tác từ Drive -->
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- [FLATSOME SECTION 10: GOOGLE MAP & FANPAGE FACEBOOK NGOÀI TRANG CHỦ]  -->
  <!-- ===================================================================== -->
  <section id="lien-he" class="py-10 md:py-14 bg-white">
    <div class="ck-container">
      <div class="text-center mb-7 md:mb-9">
        <h2 class="flatsome-section-title text-lg sm:text-2xl md:text-3xl font-extrabold text-brand-navy uppercase">
          BẢN ĐỒ CHỈ ĐƯỜNG &amp; FANPAGE NHÔM KÍNH CK
        </h2>
        <p class="text-xs sm:text-sm text-slate-500 mt-2.5">
          Ghé thăm showroom tại 446 Ngô Quyền, Sơn Trà, Đà Nẵng hoặc kết nối trực tiếp qua Fanpage Facebook
        </p>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
        <!-- Bản đồ Google Map nhúng trực tiếp ngoài trang chủ -->
        <div class="lg:col-span-7 flex flex-col rounded-2xl overflow-hidden border border-slate-200 shadow-sm bg-white">
          <div class="px-4 py-3 bg-brand-navy text-white flex items-center justify-between gap-2 text-xs sm:text-sm">
            <span class="font-semibold truncate">Google Map: 446 Ngô Quyền, Sơn Trà, Đà Nẵng</span>
            <a
              href="https://www.google.com/maps/search/?api=1&query=446+Ng%C3%B4+Quy%E1%BB%81n,+S%C6%A1n+Tr%C3%A0,+%C4%90%C3%A0+N%E1%BA%B5ng"
              target="_blank"
              rel="noopener noreferrer"
              class="shrink-0 px-2.5 py-1 rounded bg-brand-amber text-slate-900 font-bold text-[11px] hover:bg-amber-400 transition"
            >
              Mở Google Maps
            </a>
          </div>
          <div class="w-full flex-1 min-h-[300px] sm:min-h-[340px]">
            <iframe
              title="Bản đồ Nhôm Kính CK - 446 Ngô Quyền, Sơn Trà, Đà Nẵng"
              src="https://maps.google.com/maps?q=446%20Ng%C3%B4%20Quy%E1%BB%81n,%20S%C6%A1n%20Tr%C3%A0,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
              class="w-full h-full min-h-[300px] sm:min-h-[340px] border-0"
              loading="lazy"
              referrerpolicy="no-referrer-when-downgrade"
            ></iframe>
          </div>
        </div>

        <!-- Khung Fanpage Facebook đặt trực tiếp ngoài trang chủ -->
        <div class="lg:col-span-5 flex flex-col rounded-2xl overflow-hidden border border-slate-200 shadow-sm bg-white">
          <div class="px-4 py-3 bg-[#1877f2] text-white flex items-center justify-between text-xs sm:text-sm">
            <div class="flex items-center gap-2 font-semibold">
              <svg class="w-4 h-4 fill-current" viewBox="0 0 24 24"><path d="M22.675 0h-21.35C.597 0 0 .597 0 1.326v21.348C0 23.403.597 24 1.326 24h11.495v-9.294H9.691v-3.622h3.13V8.413c0-3.1 1.893-4.788 4.659-4.788 1.325 0 2.463.099 2.795.143v3.24l-1.918.001c-1.504 0-1.795.715-1.795 1.763v2.313h3.587l-.467 3.622h-3.12V24h6.116c.73 0 1.323-.597 1.323-1.326V1.326C24 .597 23.403 0 22.675 0z"/></svg>
              <span>Fanpage Facebook Chính Thức</span>
            </div>
            <span class="text-[11px] bg-white/20 px-2 py-0.5 rounded-full">Đang hoạt động</span>
          </div>

          <!-- Header Fanpage sống động chuẩn Facebook Page Plugin -->
          <div class="relative h-32 bg-gradient-to-r from-brand-navy to-brand-sky overflow-hidden">
            <img
              data-drive-id="1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ"
              alt="Ảnh bìa Fanpage Nhôm Kính CK"
              class="w-full h-full object-cover opacity-55"
            />
            <div class="absolute inset-0 bg-gradient-to-t from-slate-900/80 via-slate-900/30 to-transparent p-4 flex items-end gap-3">
              <!-- Avatar Logo Nhôm Kính CK -->
              <div class="w-14 h-14 rounded-xl bg-white p-1 shadow-md shrink-0 flex items-center justify-center">
                <svg class="w-full h-full" viewBox="0 0 64 64" fill="none">
                  <rect x="2" y="2" width="60" height="60" rx="14" fill="#0b3c68"/>
                  <path d="M29.5 22.5H24.5C20.2 22.5 17 25.8 17 32C17 38.2 20.2 41.5 24.5 41.5H29.5" stroke="#ffffff" stroke-width="4.4" stroke-linecap="round"/>
                  <path d="M35.5 20.5V43.5" stroke="#ffffff" stroke-width="4.4" stroke-linecap="round"/>
                  <path d="M47 21.5L37 32L47.5 43" stroke="#f59e0b" stroke-width="4.4" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
              </div>
              <div class="text-white min-w-0">
                <div class="font-bold text-sm sm:text-base truncate">Nhôm Kính CK Đà Nẵng</div>
                <div class="text-xs text-slate-200">12.4K người theo dõi • 446 Ngô Quyền, Sơn Trà</div>
              </div>
            </div>
          </div>

          <!-- Bài viết cập nhật gần đây trên Fanpage -->
          <div class="p-4 flex-1 flex flex-col justify-between bg-slate-50/70 space-y-3">
            <div class="bg-white p-3.5 rounded-xl border border-slate-200 text-xs text-slate-600 space-y-2">
              <div class="flex items-center justify-between">
                <span class="font-bold text-brand-navy">Nhôm Kính CK Đà Nẵng</span>
                <span class="text-[11px] text-slate-400">Vừa cập nhật</span>
              </div>
              <p class="leading-relaxed">
                Hoàn thiện bàn giao hệ cửa nhôm Xingfa nhập khẩu tem đỏ kết hợp kính cường lực 10mm cho công trình tại Sơn Trà – Đà Nẵng. Liên hệ <strong>0918.060.633</strong> để nhận ưu đãi lắp đặt trọn gói!
              </p>
              <div class="text-brand-sky font-medium">#NhomKinhCK #CuaNhomXingfaDaNang #CuaKinhCuongLuc</div>
            </div>

            <div class="grid grid-cols-2 gap-2.5 pt-1">
              <a
                href="https://www.facebook.com/"
                target="_blank"
                rel="noopener noreferrer"
                class="flex items-center justify-center gap-1.5 py-2.5 px-3 rounded-xl bg-[#1877f2] hover:bg-blue-700 text-white font-semibold text-xs transition"
              >
                <svg class="w-4 h-4 fill-current" viewBox="0 0 24 24"><path d="M14 9h3l-1 4h-2v9h-4v-9H8V9h2V6.5C10 4.57 11.57 3 13.5 3H17v4h-2c-.55 0-1 .45-1 1v1z"/></svg>
                <span>Theo dõi Fanpage</span>
              </a>
              <a
                href="https://zalo.me/0918060633"
                target="_blank"
                rel="noopener noreferrer"
                class="flex items-center justify-center gap-1.5 py-2.5 px-3 rounded-xl bg-brand-navy hover:bg-brand-sky text-white font-semibold text-xs transition"
              >
                <span>Nhắn tin tư vấn</span>
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- [FLATSOME FOOTER] 4 cột chuẩn cấu trúc UXBuilder Flatsome             -->
  <!-- ===================================================================== -->
  <footer class="bg-brand-dark text-slate-300 pt-11 pb-24 md:pb-8 border-t-4 border-brand-amber">
    <div class="ck-container">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-7 pb-8 border-b border-white/10">
        <!-- Cột 1: Thông tin liên hệ -->
        <div class="space-y-3">
          <div class="flex items-center gap-2.5">
            <svg class="w-8 h-8 shrink-0" viewBox="0 0 64 64" fill="none">
              <rect x="2" y="2" width="60" height="60" rx="14" fill="#0284c7"/>
              <path d="M29.5 22.5H24.5C20.2 22.5 17 25.8 17 32C17 38.2 20.2 41.5 24.5 41.5H29.5" stroke="#ffffff" stroke-width="4.4" stroke-linecap="round"/>
              <path d="M35.5 20.5V43.5" stroke="#ffffff" stroke-width="4.4" stroke-linecap="round"/>
              <path d="M47 21.5L37 32L47.5 43" stroke="#f59e0b" stroke-width="4.4" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>
            <div>
              <div class="text-white font-extrabold text-base">NHÔM KÍNH CK</div>
              <div class="text-[11px] text-sky-300">nhomkinhck.com</div>
            </div>
          </div>
          <p class="text-xs leading-relaxed text-slate-300">
            Chuyên thiết kế, sản xuất và thi công cửa nhôm Xingfa nhập khẩu, cửa kính cường lực, cầu thang kính, phòng tắm kính hàng đầu tại Đà Nẵng.
          </p>
          <ul class="space-y-1.5 text-xs list-none p-0 m-0">
            <li><strong class="text-white">Địa chỉ:</strong> 446 Ngô Quyền, Sơn Trà, Đà Nẵng</li>
            <li><strong class="text-white">Hotline/Zalo:</strong> <a href="tel:0918060633" class="text-brand-amber font-semibold hover:underline">0918.060.633</a></li>
            <li><strong class="text-white">Website:</strong> nhomkinhck.com</li>
          </ul>
        </div>

        <!-- Cột 2: Cửa nhôm Xingfa -->
        <div>
          <h4 class="text-white font-bold text-sm uppercase mb-3.5">Cửa nhôm Xingfa</h4>
          <ul class="space-y-2 text-xs list-none p-0 m-0">
            <li><a href="#san-pham-xingfa" onclick="highlightProduct('xingfa-1-canh')" class="hover:text-brand-amber transition">Cửa nhôm Xingfa 1 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="highlightProduct('xingfa-2-canh')" class="hover:text-brand-amber transition">Cửa nhôm Xingfa 2 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="highlightProduct('xingfa-3-canh')" class="hover:text-brand-amber transition">Cửa nhôm Xingfa 3 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="highlightProduct('xingfa-4-canh')" class="hover:text-brand-amber transition">Cửa nhôm Xingfa 4 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="highlightProduct('xingfa-xep-truot')" class="hover:text-brand-amber transition">Cửa nhôm Xingfa 5 cánh / xếp trượt</a></li>
            <li><a href="#san-pham-xingfa" onclick="highlightProduct('xingfa-mo-hat')" class="hover:text-brand-amber transition">Cửa sổ mở hất 2 cánh nhôm Xingfa</a></li>
          </ul>
        </div>

        <!-- Cột 3: Danh mục sản phẩm -->
        <div>
          <h4 class="text-white font-bold text-sm uppercase mb-3.5">Danh mục dịch vụ</h4>
          <ul class="space-y-2 text-xs list-none p-0 m-0">
            <li><a href="#danh-muc-san-pham" class="hover:text-brand-amber transition">Cửa nhôm Xingfa Đà Nẵng</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-brand-amber transition">Cửa nhựa lõi thép</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-brand-amber transition">Cửa kính tự động</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-brand-amber transition">Cửa kính cường lực</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-brand-amber transition">Cầu thang kính cường lực</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-brand-amber transition">Kính ốp bếp &amp; Phòng tắm kính</a></li>
          </ul>
        </div>

        <!-- Cột 4: Hỗ trợ khách hàng -->
        <div>
          <h4 class="text-white font-bold text-sm uppercase mb-3.5">Hỗ trợ nhanh</h4>
          <ul class="space-y-2 text-xs list-none p-0 m-0 mb-4">
            <li><a href="#bang-bao-gia" class="hover:text-brand-amber transition">Bảng báo giá thi công mới nhất</a></li>
            <li><a href="#cong-trinh" class="hover:text-brand-amber transition">Dự án đã thi công tại Đà Nẵng</a></li>
            <li><a href="#tin-tuc" class="hover:text-brand-amber transition">Kinh nghiệm chọn nhôm kính chuẩn</a></li>
            <li><a href="#form-bao-gia" class="hover:text-brand-amber transition">Đăng ký khảo sát miễn phí tận nơi</a></li>
          </ul>
          <a href="#form-bao-gia" class="inline-block px-4 py-2 rounded-lg bg-brand-amber text-slate-900 font-bold text-xs hover:bg-amber-400 transition">
            Yêu cầu tư vấn ngay
          </a>
        </div>
      </div>

      <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400">
        <div>© 2026 Bản quyền thuộc về <strong class="text-white">Nhôm Kính CK</strong> – nhomkinhck.com</div>
        <div>Địa chỉ: 446 Ngô Quyền, Sơn Trà, Đà Nẵng • Hotline: 0918.060.633</div>
      </div>
    </div>
  </footer>

  <!-- ===================================================================== -->
  <!-- [FLOATING CONTACT BUTTONS] Nút liên hệ nổi bật Zalo, Facebook, Hotline -->
  <!-- Tương thích hoàn hảo trên cả máy tính và điện thoại, không tràn viền  -->
  <!-- ===================================================================== -->

  <!-- Phiên bản Máy tính (cụm nút nổi gọn đẹp góc dưới bên phải) -->
  <div class="hidden md:flex fixed right-4 bottom-5 z-40 flex-col items-end gap-2.5">
    <!-- Zalo -->
    <a
      href="https://zalo.me/0918060633"
      target="_blank"
      rel="noopener noreferrer"
      class="flex items-center gap-2 pl-3 pr-3.5 py-2 rounded-full bg-[#0068ff] hover:bg-blue-600 text-white shadow-lg transition hover:-translate-y-0.5"
      title="Chat Zalo Nhôm Kính CK"
    >
      <span class="w-7 h-7 rounded-full bg-white text-[#0068ff] font-extrabold text-[11px] flex items-center justify-center">Zalo</span>
      <span class="text-xs font-bold">Chat Zalo</span>
    </a>

    <!-- Facebook -->
    <a
      href="https://www.facebook.com/"
      target="_blank"
      rel="noopener noreferrer"
      class="flex items-center gap-2 pl-3 pr-3.5 py-2 rounded-full bg-[#1877f2] hover:bg-blue-700 text-white shadow-lg transition hover:-translate-y-0.5"
      title="Facebook Nhôm Kính CK"
    >
      <span class="w-7 h-7 rounded-full bg-white text-[#1877f2] flex items-center justify-center">
        <svg class="w-4 h-4 fill-current" viewBox="0 0 24 24"><path d="M14 9h3l-1 4h-2v9h-4v-9H8V9h2V6.5C10 4.57 11.57 3 13.5 3H17v4h-2c-.55 0-1 .45-1 1v1z"/></svg>
      </span>
      <span class="text-xs font-bold">Facebook</span>
    </a>

    <!-- Hotline -->
    <a
      href="tel:0918060633"
      class="ck-pulse-btn flex items-center gap-2 pl-3 pr-4 py-2.5 rounded-full bg-brand-sale hover:bg-red-700 text-white shadow-xl transition hover:-translate-y-0.5"
      title="Gọi Hotline Nhôm Kính CK"
    >
      <span class="w-7 h-7 rounded-full bg-white text-brand-sale flex items-center justify-center">
        <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2.4" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/>
        </svg>
      </span>
      <span class="text-xs font-extrabold">0918.060.633</span>
    </a>
  </div>

  <!-- Phiên bản Điện thoại (Thanh liên hệ nổi 3 nút gọn đẹp dưới đáy màn hình) -->
  <div class="md:hidden fixed bottom-0 left-0 right-0 z-40 bg-white/95 backdrop-blur border-t border-slate-200 px-2.5 py-2 shadow-[0_-4px_15px_rgba(0,0,0,0.08)]">
    <div class="grid grid-cols-3 gap-2">
      <a
        href="https://zalo.me/0918060633"
        target="_blank"
        rel="noopener noreferrer"
        class="flex items-center justify-center gap-1.5 py-2.5 rounded-xl bg-[#0068ff] text-white font-bold text-xs shadow-sm active:scale-95 transition"
      >
        <span class="bg-white text-[#0068ff] text-[10px] font-extrabold px-1.5 py-0.5 rounded">Zalo</span>
        <span>Chat Zalo</span>
      </a>
      <a
        href="https://www.facebook.com/"
        target="_blank"
        rel="noopener noreferrer"
        class="flex items-center justify-center gap-1.5 py-2.5 rounded-xl bg-[#1877f2] text-white font-bold text-xs shadow-sm active:scale-95 transition"
      >
        <svg class="w-4 h-4 fill-current shrink-0" viewBox="0 0 24 24"><path d="M14 9h3l-1 4h-2v9h-4v-9H8V9h2V6.5C10 4.57 11.57 3 13.5 3H17v4h-2c-.55 0-1 .45-1 1v1z"/></svg>
        <span>Facebook</span>
      </a>
      <a
        href="tel:0918060633"
        class="flex items-center justify-center gap-1.5 py-2.5 rounded-xl bg-brand-sale text-white font-bold text-xs shadow-sm active:scale-95 transition"
      >
        <svg class="w-3.5 h-3.5 shrink-0" fill="none" stroke="currentColor" stroke-width="2.4" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/>
        </svg>
        <span>Hotline</span>
      </a>
    </div>
  </div>

  <!-- ===================================================================== -->
  <!-- [MODAL CHI TIẾT SẢN PHẨM / BÀI VIẾT] & THÔNG BÁO TOAST (Không alert)  -->
  <!-- ===================================================================== -->
  <div id="detailModal" class="fixed inset-0 z-50 hidden items-center justify-center bg-slate-900/60 p-4">
    <div class="bg-white rounded-2xl max-w-2xl w-full max-h-[88vh] overflow-y-auto shadow-2xl border border-slate-200">
      <div class="sticky top-0 bg-brand-navy text-white px-5 py-3.5 flex items-center justify-between">
        <h3 id="modalTitle" class="text-sm sm:text-base font-bold pr-4">Thông tin chi tiết</h3>
        <button type="button" onclick="closeDetailModal()" aria-label="Đóng cửa sổ" class="p-1 rounded-lg bg-white/15 hover:bg-white/25 transition">
          <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/></svg>
        </button>
      </div>
      <div id="modalBody" class="p-5 text-sm text-slate-700 space-y-4"></div>
    </div>
  </div>

  <!-- Thông báo Toast mượt mà -->
  <div id="toastBox" class="fixed top-20 right-4 z-50 hidden max-w-xs sm:max-w-sm bg-brand-navy text-white px-4 py-3 rounded-xl shadow-2xl border-l-4 border-brand-amber text-xs sm:text-sm font-medium"></div>

  <!-- ===================================================================== -->
  <!-- [JAVASCRIPT] Xử lý ảnh Drive dự phòng, dữ liệu sản phẩm, slider, form -->
  <!-- ===================================================================== -->
  <script>
    /**
     * Hàm tạo URL ảnh từ Google Drive ID và tự động chuyển nguồn dự phòng nếu bị chặn
     */
    function getDriveUrl(id, step) {
      if (step === 0) return `https://lh3.googleusercontent.com/d/${id}=w1000`;
      if (step === 1) return `https://drive.google.com/thumbnail?id=${id}&sz=w1000`;
      return `https://placehold.co/800x600/0b3c68/ffffff?text=Nhom+Kinh+CK`;
    }

    function attachDriveFallback(imgEl, id) {
      imgEl.dataset.fallbackStep = '0';
      imgEl.src = getDriveUrl(id, 0);
      imgEl.onerror = function () {
        const nextStep = parseInt(this.dataset.fallbackStep || '0', 10) + 1;
        if (nextStep <= 2) {
          this.dataset.fallbackStep = String(nextStep);
          this.src = getDriveUrl(id, nextStep);
        } else {
          this.onerror = null;
        }
      };
    }

    function formatVND(price) {
      return price.toLocaleString('vi-VN') + ' ₫';
    }

    /* =================================================================== */
    /* 1. DỮ LIỆU 6 SẢN PHẨM CỬA NHÔM XINGFA CHÍNH TỪ GOOGLE DRIVE         */
    /* =================================================================== */
    const productsData = [
      {
        id: 'xingfa-1-canh',
        name: 'Cửa đi quay mở 1 cánh nhôm xingfa',
        driveId: '1-0eBWGjPwzQ-C9c1Wjws9wt0gbsulkPm',
        originalPrice: 2250000,
        salePrice: 1890000,
        discountPercent: 16,
        specs: 'Nhôm Xingfa nhập khẩu hệ 55 dày 2.0mm, kính cường lực 8mm–10mm, phụ kiện Kinlong đồng bộ, gioăng EPDM kín khít.',
        usage: 'Phù hợp làm cửa thông phòng, cửa ban công, cửa nhà vệ sinh, cửa phụ mặt bên.'
      },
      {
        id: 'xingfa-2-canh',
        name: 'Cửa đi quay mở 2 cánh nhôm xingfa',
        driveId: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
        originalPrice: 2350000,
        salePrice: 1990000,
        discountPercent: 15,
        specs: 'Nhôm Xingfa tem đỏ hệ 55 dày 2.0mm, bản lề 3D chịu lực, khóa đa điểm chống trộm cao cấp, sơn tĩnh điện bền màu.',
        usage: 'Thích hợp làm cửa mặt tiền nhà phố vừa, cửa ra sân vườn hoặc ban công rộng.'
      },
      {
        id: 'xingfa-3-canh',
        name: 'Cửa đi quay mở 3 cánh nhôm xingfa',
        driveId: '17Qi2D8ntACnVrTeRPZ2V7rC0FmI8ecaR',
        originalPrice: 2450000,
        salePrice: 2100000,
        discountPercent: 14,
        specs: 'Nhôm Xingfa hệ 55 dày 2.0mm kết hợp kính an toàn 6.38mm hoặc cường lực 8mm, vận hành êm ái không xệ cánh.',
        usage: 'Lý tưởng cho không gian mở rộng, cửa sảnh phụ, biệt thự và khách sạn tại Đà Nẵng.'
      },
      {
        id: 'xingfa-4-canh',
        name: 'Cửa đi quay mở 4 cánh nhôm xingfa',
        driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
        originalPrice: 2500000,
        salePrice: 2100000,
        discountPercent: 16,
        specs: 'Nhôm Xingfa nhập khẩu Quảng Đông hệ 55 dày 2.0mm, ép góc CNC kín khít, cách âm – chống gió bão miền Trung.',
        usage: 'Lựa chọn hàng đầu cho cửa chính mặt tiền nhà phố, showroom, biệt thự sang trọng.'
      },
      {
        id: 'xingfa-xep-truot',
        name: 'Cửa Nhôm Xingfa Cửa Đi Xếp Trượt',
        driveId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
        originalPrice: 2600000,
        salePrice: 2150000,
        discountPercent: 17,
        specs: 'Nhôm Xingfa hệ 63 dày 2.0–2.4mm chuyên dụng cho cửa 4, 5, 6 cánh xếp gọn tối đa diện tích lối đi, ray trượt êm.',
        usage: 'Tối ưu tầm nhìn cho biệt thự sân vườn, resort ven biển, quán cafe và nhà hàng.'
      },
      {
        id: 'xingfa-mo-hat',
        name: 'Cửa sổ mở hất 2 cánh nhôm Xingfa',
        driveId: '11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA',
        originalPrice: 2100000,
        salePrice: 1785000,
        discountPercent: 15,
        specs: 'Nhôm Xingfa hệ 55 dày 1.4mm, thanh chống gió định vị góc mở 45 độ, chống hắt mưa hiệu quả ngay cả khi trời mưa.',
        usage: 'Chuyên dụng cho nhà cao tầng, khách sạn, căn hộ chung cư và nhà phố hiện đại.'
      }
    ];

    /* =================================================================== */
    /* 2. DỮ LIỆU 6 DANH MỤC SẢN PHẨM NỔI BẬT TỪ GOOGLE DRIVE              */
    /* =================================================================== */
    const categoriesData = [
      {
        title: 'CỬA NHÔM XINGFA',
        driveId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
        desc: 'Cửa đi, cửa sổ nhôm Xingfa nhập khẩu tem đỏ Quảng Đông'
      },
      {
        title: 'CỬA NHỰA LÕI THÉP',
        driveId: '1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA',
        desc: 'Cửa nhựa uPVC lõi thép gia cường cách âm, cách nhiệt tốt'
      },
      {
        title: 'CỬA TỰ ĐỘNG',
        driveId: '1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ',
        desc: 'Cửa kính trượt tự động cảm biến cho khách sạn, showroom'
      },
      {
        title: 'CẦU THANG KÍNH',
        driveId: '1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul',
        desc: 'Lan can cầu thang kính cường lực tay vịn gỗ / inox sang trọng'
      },
      {
        title: 'KÍNH ỐP BẾP',
        driveId: '1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb',
        desc: 'Kính màu cường lực ốp bếp chịu nhiệt, dễ dàng vệ sinh lau chùi'
      },
      {
        title: 'PHÒNG TẮM KÍNH',
        driveId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
        desc: 'Cabin vách tắm kính cường lực 10mm phụ kiện inox 304 chống gỉ'
      }
    ];

    /* =================================================================== */
    /* 3. DỮ LIỆU 6 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG TỪ GOOGLE DRIVE            */
    /* =================================================================== */
    const projectsData = [
      {
        title: 'DỰ ÁN RESORT MỸ SƠN 4 SAO “MY SON HERITAGE RESORT & SPA”',
        driveId: '1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ',
        type: 'resort',
        location: 'Quảng Nam – Đà Nẵng',
        scope: 'Thi công trọn gói hệ cửa nhôm Xingfa xếp trượt, vách kính mặt dựng và phòng tắm kính.'
      },
      {
        title: 'THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE',
        driveId: '1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy',
        type: 'khach-san',
        location: 'Đà Nẵng',
        scope: 'Cung cấp lắp đặt cửa sổ mở hất Xingfa chống bão, cửa đi ban công và vách tắm kính.'
      },
      {
        title: 'DỰ ÁN KHÁCH SẠN RUBY LIGHT',
        driveId: '1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ',
        type: 'khach-san',
        location: 'Đà Nẵng',
        scope: 'Hạng mục cửa kính cường lực sảnh lễ tân, cửa nhôm Xingfa cách âm phòng lưu trú.'
      },
      {
        title: 'THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL',
        driveId: '1za_IJpAm850uulT6IuhBsk1THb3LuPuc',
        type: 'resort',
        location: 'Biển Mỹ Khê, Đà Nẵng',
        scope: 'Hệ nhôm kính chống ăn mòn muối biển, lan can kính cường lực và cửa tự động sảnh.'
      },
      {
        title: 'THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA',
        driveId: '1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64',
        type: 'khach-san',
        location: 'Đà Nẵng',
        scope: 'Lắp đặt đồng bộ toàn bộ hệ cửa nhôm Xingfa nhập khẩu và phòng tắm kính cường lực.'
      },
      {
        title: 'THI CÔNG DỰ ÁN KHÁCH SẠN SOHO',
        driveId: '1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt',
        type: 'khach-san',
        location: 'Đà Nẵng',
        scope: 'Thi công mặt dựng kính hộp cách âm, cửa đi nhôm Xingfa và cửa kính tự động cao cấp.'
      }
    ];

    /* =================================================================== */
    /* 4. DỮ LIỆU 6 ĐỐI TÁC TỪ GOOGLE DRIVE                                */
    /* =================================================================== */
    const partnerDriveIds = [
      '13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk',
      '1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq',
      '1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn',
      '1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT',
      '1SDcarhnX0yypmqdbawICjYBRtFnKngn-',
      '1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg'
    ];

    /* =================================================================== */
    /* 5. DỮ LIỆU CÁC BÀI VIẾT / TIN TỨC TRANG CHỦ                         */
    /* =================================================================== */
    const newsData = [
      {
        title: 'Cửa nhôm Xingfa có phù hợp với khí hậu ven biển Đà Nẵng không?',
        date: '15/11/2026',
        driveId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
        excerpt: 'Khí hậu miền Trung nhiều nắng gió và hơi muối biển đòi hỏi hệ cửa có kết cấu vững chắc, bề mặt sơn tĩnh điện đạt chuẩn...',
        content: 'Nhôm Xingfa nhập khẩu chính hãng có cấu tạo khoang rỗng kèm đường gân gia cường chịu lực cực tốt trước gió bão miền Trung. Lớp sơn tĩnh điện ngoài trời cao cấp kết hợp phụ kiện inox/hợp kim chống ăn mòn giúp cửa không bị han gỉ, bạc màu hay cong vênh dưới thời tiết nắng nóng và hơi muối biển tại Đà Nẵng.'
      },
      {
        title: 'Cách phân biệt nhôm Xingfa nhập khẩu tem đỏ và nhôm giả',
        date: '10/11/2026',
        driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
        excerpt: 'Hướng dẫn kiểm tra mã QR trên tem đỏ Quảng Đông, độ dày thanh nhôm 1.4mm - 2.0mm và ánh kim bên trong khoang nhôm...',
        content: 'Khi lựa chọn cửa nhôm Xingfa, gia chủ nên kiểm tra 4 yếu tố: (1) Tem đỏ có mã QR rõ nét, chữ in sắc sảo; (2) Độ dày chuẩn 2.0mm cho cửa đi và 1.4mm cho cửa sổ; (3) Bên trong thanh nhôm có ánh màu đồng nhẹ do công nghệ mạ crom chống oxy hóa; (4) Góc cửa được bấm ép máy CNC kín khít, không để lộ khe hở.'
      },
      {
        title: 'Cửa nhôm Xingfa có tiết kiệm điện năng và cách âm tốt không?',
        date: '04/11/2026',
        driveId: '11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA',
        excerpt: 'Sự kết hợp giữa thanh profile khoang rỗng, hệ gioăng kép EPDM và kính hộp giúp giảm đáng kể thất thoát nhiệt điều hòa...',
        content: 'Nhờ hệ gioăng kép EPDM đàn hồi cao cùng công nghệ ép góc kín tuyệt đối, cửa nhôm Xingfa giúp ngăn tiếng ồn đô thị và giữ hơi lạnh điều hòa cực hiệu quả. Điều này giúp hộ gia đình và khách sạn tiết kiệm từ 20% đến 30% chi phí điện năng hàng tháng.'
      },
      {
        title: 'Kinh nghiệm chọn phòng tắm kính & cầu thang kính an toàn bền đẹp',
        date: '28/10/2026',
        driveId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
        excerpt: 'Nên dùng kính cường lực dày 10mm hay 12mm? Những lưu ý quan trọng khi chọn phụ kiện Inox 304 chống gỉ sét...',
        content: 'Đối với phòng tắm kính, kính cường lực 10mm kết hợp phụ kiện bản lề, kẹp định vị chuẩn Inox 304 là lựa chọn cân bằng tối ưu giữa độ an toàn và tính thẩm mỹ. Với cầu thang kính cường lực, nên sử dụng kính 10mm–12mm và trụ/pad Inox 304 đặc để đảm bảo chắc chắn lâu dài.'
      }
    ];

    /* =================================================================== */
    /* RENDER SẢN PHẨM (2 CỘT MOBILE, 3 CỘT DESKTOP, GIÁ & GIẢM GIÁ %)     */
    /* =================================================================== */
    function renderProducts(list) {
      const container = document.getElementById('productGrid');
      container.innerHTML = '';

      if (!list.length) {
        container.innerHTML = '<div class="col-span-2 md:col-span-3 text-center py-8 text-sm text-slate-500">Không tìm thấy sản phẩm phù hợp. Vui lòng thử từ khóa khác.</div>';
        return;
      }

      list.forEach((p) => {
        const card = document.createElement('article');
        card.id = 'prod-' + p.id;
        card.className = 'bg-white rounded-xl sm:rounded-2xl border border-slate-200/90 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between group';

        card.innerHTML = `
          <div>
            <!-- Khung ảnh sản phẩm + Nhãn giảm giá % góc trên bên trái -->
            <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
              <span class="absolute top-2 left-2 z-10 px-2 py-0.5 sm:px-2.5 sm:py-1 rounded-md bg-brand-sale text-white text-[11px] sm:text-xs font-extrabold shadow-sm">
                -${p.discountPercent}%
              </span>
              <img
                data-drive-id="${p.driveId}"
                alt="${p.name}"
                loading="lazy"
                class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105 cursor-pointer"
                onclick="openProductModal('${p.id}')"
              />
            </div>

            <!-- Tên sản phẩm đầy đủ không bị cắt hay tràn chữ -->
            <div class="p-2.5 sm:p-4">
              <h3
                onclick="openProductModal('${p.id}')"
                class="text-[12.5px] sm:text-sm md:text-[15px] font-bold text-brand-navy leading-snug break-words cursor-pointer hover:text-brand-sky transition min-h-[2.6rem]"
              >
                ${p.name}
              </h3>

              <!-- Giá gốc và giá ưu đãi -->
              <div class="mt-2 flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                <span class="text-sm sm:text-base font-extrabold text-brand-sale">
                  ${formatVND(p.salePrice)}
                </span>
                <span class="text-[11px] sm:text-xs text-slate-400 line-through">
                  ${formatVND(p.originalPrice)}
                </span>
              </div>
              <div class="text-[10.5px] sm:text-[11px] text-slate-500 mt-0.5">Đơn vị tính: / m²</div>
            </div>
          </div>

          <!-- Nút thao tác gọn đẹp -->
          <div class="px-2.5 pb-3 sm:px-4 sm:pb-4 pt-1 flex items-center gap-1.5 sm:gap-2">
            <button
              type="button"
              onclick="openProductModal('${p.id}')"
              class="flex-1 py-2 px-2 rounded-lg border border-brand-navy text-brand-navy hover:bg-brand-light font-semibold text-[11px] sm:text-xs transition text-center"
            >
              Chi tiết
            </button>
            <button
              type="button"
              onclick="quickOrderProduct('${p.name.replace(/'/g, "\\'")}')"
              class="flex-1 py-2 px-2 rounded-lg bg-brand-navy hover:bg-brand-sky text-white font-semibold text-[11px] sm:text-xs transition text-center"
            >
              Báo giá
            </button>
          </div>
        `;
        container.appendChild(card);
      });

      initDriveImages(container);
    }

    /* =================================================================== */
    /* RENDER 6 DANH MỤC SẢN PHẨM NỔI BẬT                                  */
    /* =================================================================== */
    function renderCategories() {
      const container = document.getElementById('categoryGrid');
      container.innerHTML = '';

      categoriesData.forEach((c) => {
        const card = document.createElement('div');
        card.className = 'bg-white rounded-xl sm:rounded-2xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition group cursor-pointer flex flex-col';
        card.onclick = () => selectCategoryQuote(c.title);

        card.innerHTML = `
          <div class="aspect-[4/3] bg-slate-100 overflow-hidden">
            <img
              data-drive-id="${c.driveId}"
              alt="${c.title}"
              loading="lazy"
              class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105"
            />
          </div>
          <div class="p-3 sm:p-4 text-center flex-1 flex flex-col justify-center">
            <h3 class="text-xs sm:text-sm md:text-[15px] font-extrabold text-brand-navy group-hover:text-brand-sky transition break-words">
              ${c.title}
            </h3>
            <p class="hidden sm:block text-xs text-slate-500 mt-1.5 leading-relaxed">
              ${c.desc}
            </p>
          </div>
        `;
        container.appendChild(card);
      });

      initDriveImages(container);
    }

    /* =================================================================== */
    /* RENDER 6 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG                                */
    /* =================================================================== */
    function renderProjects(filterType = 'all') {
      const container = document.getElementById('projectGrid');
      container.innerHTML = '';

      const filtered = filterType === 'all'
        ? projectsData
        : projectsData.filter((p) => p.type === filterType);

      filtered.forEach((proj) => {
        const card = document.createElement('article');
        card.className = 'bg-white rounded-2xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition group flex flex-col';
        card.innerHTML = `
          <div class="aspect-[16/10] bg-slate-100 overflow-hidden">
            <img
              data-drive-id="${proj.driveId}"
              alt="${proj.title}"
              loading="lazy"
              class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105"
            />
          </div>
          <div class="p-4 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[11px] font-semibold text-brand-sky mb-1">${proj.location}</div>
              <h3 class="text-sm font-extrabold text-brand-navy leading-snug break-words">
                ${proj.title}
              </h3>
              <p class="text-xs text-slate-600 mt-2 leading-relaxed">
                ${proj.scope}
              </p>
            </div>
          </div>
        `;
        container.appendChild(card);
      });

      initDriveImages(container);
    }

    function filterProjects(type) {
      document.querySelectorAll('.proj-tab-btn').forEach((btn) => {
        const isActive = btn.dataset.projTab === type;
        btn.className = isActive
          ? 'proj-tab-btn px-4 py-1.5 rounded-full text-xs font-semibold bg-brand-navy text-white transition whitespace-nowrap'
          : 'proj-tab-btn px-4 py-1.5 rounded-full text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light hover:text-brand-navy transition whitespace-nowrap';
      });
      renderProjects(type);
    }

    /* =================================================================== */
    /* RENDER TIN TỨC TRANG CHỦ                                            */
    /* =================================================================== */
    function renderNews() {
      const container = document.getElementById('newsGrid');
      container.innerHTML = '';

      newsData.forEach((item, idx) => {
        const card = document.createElement('article');
        card.className = 'bg-white rounded-2xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between group';
        card.innerHTML = `
          <div>
            <div class="aspect-[16/10] bg-slate-100 overflow-hidden cursor-pointer" onclick="openNewsModal(${idx})">
              <img
                data-drive-id="${item.driveId}"
                alt="${item.title}"
                loading="lazy"
                class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105"
              />
            </div>
            <div class="p-4">
              <div class="text-[11px] text-slate-400 mb-1">${item.date} • Kiến thức Nhôm Kính</div>
              <h3 onclick="openNewsModal(${idx})" class="text-sm font-bold text-brand-navy leading-snug cursor-pointer hover:text-brand-sky transition">
                ${item.title}
              </h3>
              <p class="text-xs text-slate-600 mt-2 leading-relaxed">
                ${item.excerpt}
              </p>
            </div>
          </div>
          <div class="px-4 pb-4">
            <button type="button" onclick="openNewsModal(${idx})" class="text-xs font-bold text-brand-sky hover:text-brand-navy transition">
              Xem thêm →
            </button>
          </div>
        `;
        container.appendChild(card);
      });

      initDriveImages(container);
    }

    /* =================================================================== */
    /* RENDER 6 ĐỐI TÁC                                                    */
    /* =================================================================== */
    function renderPartners() {
      const container = document.getElementById('partnerGrid');
      container.innerHTML = '';

      partnerDriveIds.forEach((id, i) => {
        const box = document.createElement('div');
        box.className = 'bg-white rounded-xl border border-slate-200 p-3 h-20 sm:h-24 flex items-center justify-center shadow-sm hover:shadow transition';
        box.innerHTML = `
          <img
            data-drive-id="${id}"
            alt="Đối tác Nhôm Kính CK ${i + 1}"
            loading="lazy"
            class="max-h-14 sm:max-h-16 w-auto object-contain"
          />
        `;
        container.appendChild(box);
      });

      initDriveImages(container);
    }

    /* Khởi tạo toàn bộ thẻ <img> có data-drive-id */
    function initDriveImages(root = document) {
      root.querySelectorAll('img[data-drive-id]').forEach((img) => {
        const id = img.getAttribute('data-drive-id');
        if (id && !img.dataset.initialized) {
          img.dataset.initialized = 'true';
          attachDriveFallback(img, id);
        }
      });
    }

    /* =================================================================== */
    /* BANNER SLIDER TỰ TRƯỢT + HỖ TRỢ VUỐT TRÊN ĐIỆN THOẠI                */
    /* =================================================================== */
    let currentSlide = 0;
    const totalSlides = 2;
    let slideTimer = null;

    function updateSliderUI() {
      const track = document.getElementById('bannerTrack');
      track.style.transform = `translateX(-${currentSlide * 100}%)`;
      for (let i = 0; i < totalSlides; i++) {
        const dot = document.getElementById(`dot-${i}`);
        if (dot) {
          dot.className = i === currentSlide
            ? 'w-7 h-2 rounded-full bg-brand-amber transition-all'
            : 'w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all';
        }
      }
    }

    function nextSlide() {
      currentSlide = (currentSlide + 1) % totalSlides;
      updateSliderUI();
      resetSlideTimer();
    }

    function prevSlide() {
      currentSlide = (currentSlide - 1 + totalSlides) % totalSlides;
      updateSliderUI();
      resetSlideTimer();
    }

    function goToSlide(index) {
      currentSlide = index;
      updateSliderUI();
      resetSlideTimer();
    }

    function resetSlideTimer() {
      if (slideTimer) clearInterval(slideTimer);
      slideTimer = setInterval(() => {
        currentSlide = (currentSlide + 1) % totalSlides;
        updateSliderUI();
      }, 5500);
    }

    function initBannerTouchSwipe() {
      const wrapper = document.getElementById('heroBannerWrapper');
      let startX = 0;
      wrapper.addEventListener('touchstart', (e) => {
        startX = e.changedTouches[0].screenX;
      }, { passive: true });
      wrapper.addEventListener('touchend', (e) => {
        const diff = e.changedTouches[0].screenX - startX;
        if (Math.abs(diff) > 45) {
          if (diff < 0) nextSlide();
          else prevSlide();
        }
      }, { passive: true });
    }

    /* =================================================================== */
    /* MENU MOBILE, TÌM KIẾM, MODAL CHI TIẾT & FORM BÁO GIÁ                */
    /* =================================================================== */
    function toggleMobileMenu() {
      const drawer = document.getElementById('mobileMenuDrawer');
      const overlay = document.getElementById('mobileMenuOverlay');
      const isClosed = drawer.classList.contains('-translate-x-full');
      if (isClosed) {
        drawer.classList.remove('-translate-x-full');
        overlay.classList.remove('hidden');
        document.body.style.overflow = 'hidden';
      } else {
        closeMobileMenu();
      }
    }

    function closeMobileMenu() {
      const drawer = document.getElementById('mobileMenuDrawer');
      const overlay = document.getElementById('mobileMenuOverlay');
      drawer.classList.add('-translate-x-full');
      overlay.classList.add('hidden');
      document.body.style.overflow = '';
    }

    function toggleMobileSubmenu(id) {
      const el = document.getElementById(id);
      if (el) el.classList.toggle('hidden');
    }

    function handleProductSearch() {
      const keyword = (document.getElementById('desktopSearchInput').value || '').trim().toLowerCase();
      filterSearch(keyword);
    }

    function handleMobileSearch() {
      const keyword = (document.getElementById('mobileSearchInput').value || '').trim().toLowerCase();
      closeMobileMenu();
      filterSearch(keyword);
    }

    function filterSearch(keyword) {
      const filtered = keyword
        ? productsData.filter((p) => p.name.toLowerCase().includes(keyword) || p.specs.toLowerCase().includes(keyword))
        : productsData;
      renderProducts(filtered);
      document.getElementById('san-pham-xingfa').scrollIntoView({ behavior: 'smooth' });
      showToast(keyword ? `Hiển thị ${filtered.length} sản phẩm phù hợp với "${keyword}"` : 'Đang hiển thị toàn bộ sản phẩm');
    }

    function filterProductsByCategory() {
      renderProducts(productsData);
    }

    function highlightProduct(prodId) {
      renderProducts(productsData);
      setTimeout(() => {
        const el = document.getElementById('prod-' + prodId);
        if (el) {
          el.scrollIntoView({ behavior: 'smooth', block: 'center' });
          el.classList.add('ring-2', 'ring-brand-amber');
          setTimeout(() => el.classList.remove('ring-2', 'ring-brand-amber'), 2200);
        }
      }, 100);
    }

    function selectCategoryQuote(categoryName) {
      const select = document.getElementById('qCategory');
      if (select) {
        for (let i = 0; i < select.options.length; i++) {
          if (select.options[i].text.toLowerCase().includes(categoryName.toLowerCase())) {
            select.selectedIndex = i;
            break;
          }
        }
      }
      document.getElementById('form-bao-gia').scrollIntoView({ behavior: 'smooth' });
      showToast(`Đã chọn hạng mục: ${categoryName}. Điền thông tin để nhận báo giá nhanh!`);
    }

    function quickOrderProduct(productName) {
      const note = document.getElementById('qNote');
      if (note) {
        note.value = `Tôi muốn nhận báo giá chi tiết cho sản phẩm: ${productName}`;
      }
      document.getElementById('form-bao-gia').scrollIntoView({ behavior: 'smooth' });
      showToast(`Đã chọn "${productName}" vào biểu mẫu báo giá.`);
    }

    function openProductModal(prodId) {
      const p = productsData.find((item) => item.id === prodId);
      if (!p) return;
      document.getElementById('modalTitle').textContent = p.name;
      const body = document.getElementById('modalBody');
      body.innerHTML = `
        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 items-start">
          <div class="relative rounded-xl overflow-hidden border border-slate-200 bg-slate-100">
            <span class="absolute top-2 left-2 z-10 px-2.5 py-1 rounded-md bg-brand-sale text-white text-xs font-extrabold">-${p.discountPercent}%</span>
            <img data-drive-id="${p.driveId}" alt="${p.name}" class="w-full aspect-[4/3] object-cover" />
          </div>
          <div class="space-y-2.5">
            <div class="flex items-baseline gap-2.5">
              <span class="text-xl font-extrabold text-brand-sale">${formatVND(p.salePrice)}</span>
              <span class="text-sm text-slate-400 line-through">${formatVND(p.originalPrice)}</span>
            </div>
            <div class="text-xs text-slate-500">Đơn giá tham khảo / m² (Chưa gồm phụ kiện theo bộ)</div>
            <div class="text-xs sm:text-sm leading-relaxed"><strong>Thông số:</strong> ${p.specs}</div>
            <div class="text-xs sm:text-sm leading-relaxed"><strong>Ứng dụng:</strong> ${p.usage}</div>
            <div class="pt-2 flex flex-wrap gap-2">
              <button type="button" onclick="closeDetailModal(); quickOrderProduct('${p.name.replace(/'/g, "\\'")}')" class="px-4 py-2.5 rounded-lg bg-brand-navy text-white text-xs font-bold hover:bg-brand-sky transition">
                Nhận báo giá mẫu này
              </button>
              <a href="tel:0918060633" class="px-4 py-2.5 rounded-lg bg-brand-amber text-slate-900 text-xs font-bold hover:bg-amber-400 transition">
                Gọi: 0918.060.633
              </a>
            </div>
          </div>
        </div>
      `;
      initDriveImages(body);
      const modal = document.getElementById('detailModal');
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function openNewsModal(idx) {
      const item = newsData[idx];
      if (!item) return;
      document.getElementById('modalTitle').textContent = item.title;
      const body = document.getElementById('modalBody');
      body.innerHTML = `
        <div class="rounded-xl overflow-hidden border border-slate-200">
          <img data-drive-id="${item.driveId}" alt="${item.title}" class="w-full max-h-72 object-cover" />
        </div>
        <div class="text-xs text-slate-400">Đăng ngày ${item.date} • Nhôm Kính CK Đà Nẵng</div>
        <p class="text-sm text-slate-700 leading-relaxed">${item.content}</p>
        <div class="p-3.5 rounded-xl bg-brand-light text-brand-navy text-xs font-medium">
          Cần tư vấn kỹ thuật trực tiếp? Liên hệ <strong>Nhôm Kính CK</strong> – 446 Ngô Quyền, Sơn Trà, Đà Nẵng • Hotline/Zalo: <strong>0918.060.633</strong>.
        </div>
      `;
      initDriveImages(body);
      const modal = document.getElementById('detailModal');
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function closeDetailModal() {
      const modal = document.getElementById('detailModal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
    }

    function submitQuoteForm(e) {
      e.preventDefault();
      const name = document.getElementById('qName').value.trim();
      const phone = document.getElementById('qPhone').value.trim();
      const category = document.getElementById('qCategory').value;

      if (!name || !phone) {
        showToast('Vui lòng nhập đầy đủ họ tên và số điện thoại.');
        return;
      }

      showToast(`Cảm ơn ${name}! Nhôm Kính CK đã nhận yêu cầu báo giá "${category}" và sẽ gọi lại số ${phone} trong ít phút.`);
      document.getElementById('quoteForm').reset();
    }

    let toastTimer = null;
    function showToast(message) {
      const box = document.getElementById('toastBox');
      box.textContent = message;
      box.classList.remove('hidden');
      if (toastTimer) clearTimeout(toastTimer);
      toastTimer = setTimeout(() => {
        box.classList.add('hidden');
      }, 4200);
    }

    /* Đóng modal khi click ra ngoài nền tối */
    document.getElementById('detailModal').addEventListener('click', function (e) {
      if (e.target === this) closeDetailModal();
    });

    /* Cho phép nhấn Enter trên ô tìm kiếm */
    document.getElementById('desktopSearchInput').addEventListener('keydown', function (e) {
      if (e.key === 'Enter') handleProductSearch();
    });

    /* Khởi chạy toàn bộ trang web */
    window.addEventListener('DOMContentLoaded', () => {
      initDriveImages(document);
      renderProducts(productsData);
      renderCategories();
      renderProjects('all');
      renderNews();
      renderPartners();
      updateSliderUI();
      resetSlideTimer();
      initBannerTouchSwipe();
    });
  </script>
</body>
</html>
