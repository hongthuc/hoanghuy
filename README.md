<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Cơ Sở Điêu Khắc Đá Tự Nhiên Hoàng Huy | Đá Mỹ Nghệ Non Nước Cao Cấp - hoanghuy.com</title>
    <meta name="description" content="Cơ sở điêu khắc đá tự nhiên Hoàng Huy (hoanghuy.com) - Chuyên cung cấp đá mỹ nghệ cao cấp: Tượng Phật, Đài phun nước, Linh vật, Lăng mộ, Lan can, Công trình đá. Đá tự nhiên, chạm khắc tinh xảo, giá xưởng tại Làng đá Non Nước, Đà Nẵng. Hotline: 0938 534 827.">

    <!-- Open Graph / Thumbnail Logo khi chia sẻ link trang web hoanghuy.com -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://hoanghuy.com/">
    <meta property="og:site_name" content="hoanghuy.com - Đá Tự Nhiên Hoàng Huy">
    <meta property="og:title" content="Cơ Sở Điêu Khắc Đá Tự Nhiên Hoàng Huy - Đá Mỹ Nghệ Non Nước Giá Xưởng">
    <meta property="og:description" content="Chuyên cung cấp đá mỹ nghệ cao cấp: Tượng Phật – Đài phun nước – Linh vật, Lăng mộ – Lan can – Công trình đá. Đá tự nhiên – Chạm khắc tinh xảo – Giá xưởng. ĐT: 0938 534 827.">
    <meta property="og:image" content="https://placehold.co/1200x630/1e293b/d97706?text=HOANG+HUY+STONE+-+HOANGHUY.COM">
    <meta property="og:image:alt" content="Logo Cơ Sở Điêu Khắc Đá Tự Nhiên Hoàng Huy - hoanghuy.com">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Cơ Sở Điêu Khắc Đá Tự Nhiên Hoàng Huy - hoanghuy.com">
    <meta name="twitter:image" content="https://placehold.co/1200x630/1e293b/d97706?text=HOANG+HUY+STONE+-+HOANGHUY.COM">

    <!-- Tailwind CSS & Font Awesome & Google Fonts -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700;900&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        /* Bảng màu đồng bộ theo màu Logo Hoàng Huy (Vàng Đồng Hoàng Gia & Xanh Đá Đậm) */
                        brand: {
                            light: '#fef3c7',
                            gold: '#d97706',
                            primary: '#9a5b13',
                            dark: '#78350f',
                            slate: '#1e293b',
                            charcoal: '#0f172a'
                        }
                    },
                    fontFamily: {
                        sans: ['Roboto', 'sans-serif']
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền và chống lệch phải tuyệt đối trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden;
            font-family: 'Roboto', sans-serif;
            background-color: #f8fafc;
            color: #1e293b;
            scroll-behavior: smooth;
        }

        /* Chiều ngang giao diện trên máy tính đúng bằng 95% kích thước màn hình máy tính, căn giữa chuẩn */
        .flatsome-container {
            width: 100%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 10px;
            padding-right: 10px;
        }
        @media (min-width: 1024px) {
            .flatsome-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Menu danh mục trên máy tính: chữ nhỏ gọn, viết liền không xuống dòng từng từ, nằm trên 1 hàng hoặc xuống hàng 2 */
        .desktop-nav-list {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: center;
            gap: 2px 6px;
            margin: 0;
            padding: 4px 0;
            list-style: none;
        }
        .desktop-nav-item {
            position: relative;
        }
        .desktop-nav-link {
            display: inline-flex;
            align-items: center;
            gap: 4px;
            white-space: nowrap; /* Tuyệt đối không xuống dòng bên trong tên danh mục */
            font-size: 12px;
            font-weight: 700;
            text-transform: uppercase;
            color: #ffffff;
            padding: 7px 9px;
            border-radius: 4px;
            transition: background-color 0.2s ease, color 0.2s ease;
            letter-spacing: 0.2px;
        }
        .desktop-nav-link:hover, .desktop-nav-link.active {
            background-color: rgba(255, 255, 255, 0.16);
            color: #fde68a;
        }

        /* Dropdown Submenu chuẩn Flatsome */
        .flatsome-dropdown {
            display: none;
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 220px;
            background: #ffffff;
            border-top: 3px solid #9a5b13;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.15);
            border-radius: 0 0 6px 6px;
            z-index: 100;
            padding: 6px 0;
        }
        .desktop-nav-item:hover .flatsome-dropdown {
            display: block;
        }
        .flatsome-dropdown a {
            display: block;
            padding: 8px 14px;
            font-size: 13px;
            color: #334155;
            white-space: nowrap;
            border-bottom: 1px solid #f1f5f9;
            transition: all 0.15s ease;
        }
        .flatsome-dropdown a:last-child {
            border-bottom: none;
        }
        .flatsome-dropdown a:hover {
            background-color: #fef3c7;
            color: #9a5b13;
            padding-left: 18px;
        }

        /* Tiêu đề Section chuẩn Flatsome UX Builder (Section Title Container) */
        .section-title-container {
            margin-bottom: 20px;
        }
        .section-title-main {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 100%;
            position: relative;
        }
        .section-title-main::before,
        .section-title-main::after {
            content: "";
            flex: 1;
            height: 2px;
            background-color: #e2e8f0;
        }
        .section-title-text {
            padding: 6px 18px;
            background-color: #9a5b13;
            color: #ffffff;
            font-weight: 700;
            font-size: 15px;
            text-transform: uppercase;
            letter-spacing: 0.5px;
            border-radius: 4px;
            text-align: center;
            margin: 0 12px;
        }
        @media (min-width: 768px) {
            .section-title-text {
                font-size: 17px;
                padding: 8px 24px;
            }
        }

        /* Nhãn % giảm giá góc trên bên trái giống chuẩn Flatsome */
        .flatsome-sale-badge {
            position: absolute;
            top: 8px;
            left: 8px;
            z-index: 10;
            background-color: #d97706;
            color: #ffffff;
            font-weight: 700;
            font-size: 11px;
            width: 38px;
            height: 38px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 2px 6px rgba(0,0,0,0.22);
            line-height: 1;
        }

        /* Tên sản phẩm hiển thị đầy đủ, không bị cắt chữ hay tràn ra ngoài */
        .product-title-full {
            display: block;
            width: 100%;
            white-space: normal;
            word-wrap: break-word;
            overflow-wrap: break-word;
            line-height: 1.4;
            font-size: 13.5px;
            font-weight: 600;
            color: #1e293b;
            margin-bottom: 6px;
        }
        @media (min-width: 768px) {
            .product-title-full {
                font-size: 14.5px;
            }
        }

        /* Hiệu ứng rung nhẹ cho nút Hotline/Zalo nổi */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(154, 91, 19, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(154, 91, 19, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(154, 91, 19, 0); }
        }
        .pulse-btn {
            animation: pulse-ring 2s infinite;
        }
    </style>
</head>
<body>

    <!-- ==================== HEADER FLATSOME (KHÔNG CÓ THANH UXBUILDER, KHÔNG ĐỂ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN) ==================== -->
    <header id="header" class="w-full bg-white shadow-sm sticky top-0 z-40">
        <!-- Top Bar -->
        <div class="bg-brand-slate text-slate-200 text-xs py-1.5 border-b border-slate-700">
            <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
                <div class="flex items-center gap-2 truncate">
                    <i class="fa-solid fa-gem text-amber-400"></i>
                    <span class="font-medium">Cơ sở điêu khắc đá tự nhiên Hoàng Huy – Tinh hoa đá mỹ nghệ Non Nước</span>
                </div>
                <div class="hidden md:flex items-center gap-4 text-slate-300">
                    <span><i class="fa-solid fa-location-dot text-amber-400 mr-1"></i>Đường Quán Khái 10, Làng đá Non Nước, Ngũ Hành Sơn, Đà Nẵng</span>
                    <span><i class="fa-solid fa-globe text-amber-400 mr-1"></i>hoanghuy.com</span>
                </div>
            </div>
        </div>

        <!-- Header Main (Logo chỉnh gọn nhỏ lại + Thanh tìm kiếm Flatsome) -->
        <div class="py-2.5 bg-white border-b border-slate-100">
            <div class="flatsome-container flex items-center justify-between gap-3">
                <!-- Nút mở Menu trên Điện Thoại -->
                <button onclick="toggleMobileMenu()" aria-label="Mở danh mục" class="lg:hidden p-2 rounded border border-slate-200 text-brand-slate hover:bg-amber-50">
                    <i class="fa-solid fa-bars text-lg"></i>
                </button>

                <!-- Logo Mới Chuyên Nghiệp - Đã chỉnh gọn nhỏ lại -->
                <a href="#trang-chu" class="flex items-center gap-2.5 group shrink-0">
                    <div class="w-10 h-10 md:w-11 md:h-11 rounded-lg bg-gradient-to-br from-brand-slate via-slate-800 to-brand-primary flex items-center justify-center shadow border border-amber-500/40 shrink-0">
                        <!-- Biểu tượng Logo Đá Mỹ Nghệ Hoàng Huy -->
                        <svg class="w-7 h-7 md:w-8 md:h-8" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <polygon points="32,4 58,18 58,46 32,60 6,46 6,18" stroke="#f59e0b" stroke-width="3" fill="#1e293b"/>
                            <path d="M32 10L48 36H16L32 10Z" fill="#d97706" opacity="0.85"/>
                            <text x="32" y="43" text-anchor="middle" fill="#ffffff" font-size="18" font-weight="900" font-family="Roboto, sans-serif">HH</text>
                        </svg>
                    </div>
                    <div class="leading-tight">
                        <div class="text-sm md:text-base font-black tracking-tight text-brand-slate uppercase">
                            ĐÁ TỰ NHIÊN <span class="text-brand-primary">HOÀNG HUY</span>
                        </div>
                        <div class="text-[10px] md:text-[11px] font-medium text-slate-500">
                            hoanghuy.com • Đá Mỹ Nghệ Non Nước
                        </div>
                    </div>
                </a>

                <!-- Ô Tìm Kiếm Sản Phẩm Chuẩn Flatsome (Trên máy tính) -->
                <div class="hidden md:flex flex-1 max-w-md mx-4">
                    <div class="relative w-full flex">
                        <input id="desktopSearchInput" type="text" oninput="handleSearchProduct(this.value)" placeholder="Tìm tượng Phật, linh vật, đài phun nước, lăng mộ đá..." class="w-full pl-3.5 pr-10 py-1.5 text-xs md:text-sm border border-slate-300 rounded-l-md focus:outline-none focus:border-brand-primary">
                        <button onclick="handleSearchProduct(document.getElementById('desktopSearchInput').value)" class="bg-brand-primary hover:bg-brand-dark text-white px-4 py-1.5 rounded-r-md text-sm transition">
                            <i class="fa-solid fa-magnifying-glass"></i>
                        </button>
                    </div>
                </div>

                <!-- Cam kết ngắn gọn trên Desktop (Không để nút gọi ngay để tránh tràn viền) -->
                <div class="hidden xl:flex items-center gap-4 text-xs text-slate-600 shrink-0">
                    <div class="flex items-center gap-1.5">
                        <i class="fa-solid fa-award text-brand-primary text-base"></i>
                        <span>Đá Tự Nhiên 100%</span>
                    </div>
                    <div class="flex items-center gap-1.5">
                        <i class="fa-solid fa-hammer text-brand-primary text-base"></i>
                        <span>Chạm Khắc Tinh Xảo</span>
                    </div>
                    <div class="flex items-center gap-1.5">
                        <i class="fa-solid fa-warehouse text-brand-primary text-base"></i>
                        <span>Giá Xưởng Tận Gốc</span>
                    </div>
                </div>
            </div>

            <!-- Thanh tìm kiếm gọn trên Điện Thoại -->
            <div class="flatsome-container mt-2 md:hidden">
                <div class="relative w-full flex">
                    <input id="mobileSearchInput" type="text" oninput="handleSearchProduct(this.value)" placeholder="Tìm kiếm sản phẩm đá mỹ nghệ..." class="w-full pl-3 pr-9 py-1.5 text-xs border border-slate-300 rounded-l focus:outline-none focus:border-brand-primary">
                    <button onclick="handleSearchProduct(document.getElementById('mobileSearchInput').value)" class="bg-brand-primary text-white px-3 py-1.5 rounded-r text-xs">
                        <i class="fa-solid fa-magnifying-glass"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- Header Bottom: Thanh Danh Mục Sản Phẩm Trên Máy Tính (Chữ nhỏ gọn, viết liền không gãy chữ, nằm trên 1 hàng hoặc xuống hàng 2) -->
        <nav class="hidden lg:block bg-brand-primary shadow-inner">
            <div class="flatsome-container">
                <ul class="desktop-nav-list">
                    <li class="desktop-nav-item">
                        <a href="#trang-chu" onclick="filterByCategory('all')" class="desktop-nav-link active">
                            <i class="fa-solid fa-house text-[11px]"></i> Trang chủ
                        </a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-phat')" class="desktop-nav-link">
                            Tượng Phật <i class="fa-solid fa-angle-down text-[10px]"></i>
                        </a>
                        <div class="flatsome-dropdown">
                            <a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-phat')">Tượng Phật Quan Âm</a>
                            <a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-phat')">Tượng Phật Di Lặc</a>
                            <a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-phat')">Tượng Phật Thích Ca</a>
                            <a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-phat')">Tượng Phật A Di Đà</a>
                            <a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-phat')">Tượng Địa Tạng Vương Bồ Tát</a>
                            <a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-phat')">Tượng Phật Nghìn Mắt Nghìn Tay</a>
                            <a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-phat')">Tượng Phúc Lộc Thọ</a>
                            <a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-phat')">Tượng Đạt Ma - Chú Tiểu</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-cong-giao')" class="desktop-nav-link">
                            Tượng Công Giáo <i class="fa-solid fa-angle-down text-[10px]"></i>
                        </a>
                        <div class="flatsome-dropdown">
                            <a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-cong-giao')">Tượng Đức Mẹ Ban Ơn</a>
                            <a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-cong-giao')">Tượng Chúa Giêsu</a>
                            <a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-cong-giao')">Tượng Thánh Giuse</a>
                            <a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-cong-giao')">Tượng Thiên Thần Đá</a>
                            <a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-cong-giao')">14 Chặng Đàng Thánh Giá</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-dong-vat')" class="desktop-nav-link">
                            Tượng Động Vật <i class="fa-solid fa-angle-down text-[10px]"></i>
                        </a>
                        <div class="flatsome-dropdown">
                            <a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-dong-vat')">Tượng Kỳ Lân - Nghê Đá</a>
                            <a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-dong-vat')">Tượng Sư Tử Đá</a>
                            <a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-dong-vat')">Tượng Tỳ Hưu Phong Thủy</a>
                            <a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-dong-vat')">Tượng Rồng Đá - Cá Chép Hóa Rồng</a>
                            <a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-dong-vat')">Tượng Voi Đá - Ngựa Đá</a>
                            <a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-dong-vat')">Tượng Chó Đá - Đại Bàng Đá</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#khu-vuc-san-pham" onclick="filterByCategory('do-tho-da')" class="desktop-nav-link">
                            Đồ Thờ Đá <i class="fa-solid fa-angle-down text-[10px]"></i>
                        </a>
                        <div class="flatsome-dropdown">
                            <a href="#khu-vuc-san-pham" onclick="filterByCategory('do-tho-da')">Lư Hương Đá Tự Nhiên</a>
                            <a href="#khu-vuc-san-pham" onclick="filterByCategory('do-tho-da')">Bàn Thờ Đá - Bàn Lễ Đá</a>
                            <a href="#khu-vuc-san-pham" onclick="filterByCategory('do-tho-da')">Cây Hương Đá Ngoài Trời</a>
                            <a href="#khu-vuc-san-pham" onclick="filterByCategory('do-tho-da')">Đỉnh Hương - Bát Hương Đá</a>
                            <a href="#khu-vuc-san-pham" onclick="filterByCategory('do-tho-da')">Chân Đèn - Búp Sen Đá</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#khu-vuc-san-pham" onclick="filterByCategory('da-kien-truc')" class="desktop-nav-link">
                            Đá Trang Trí Kiến Trúc <i class="fa-solid fa-angle-down text-[10px]"></i>
                        </a>
                        <div class="flatsome-dropdown">
                            <a href="#khu-vuc-san-pham" onclick="filterByCategory('da-kien-truc')">Đài Phun Nước Bằng Đá</a>
                            <a href="#khu-vuc-san-pham" onclick="filterByCategory('da-kien-truc')">Lăng Mộ Đá Tự Nhiên</a>
                            <a href="#khu-vuc-san-pham" onclick="filterByCategory('da-kien-truc')">Lan Can Đá - Cổng Đá</a>
                            <a href="#khu-vuc-san-pham" onclick="filterByCategory('da-kien-truc')">Bảng Hiệu Đá Tự Nhiên</a>
                            <a href="#khu-vuc-san-pham" onclick="filterByCategory('da-kien-truc')">Đèn Đá Sân Vườn - Bàn Ghế Đá</a>
                            <a href="#khu-vuc-san-pham" onclick="filterByCategory('da-kien-truc')">Đá Kê Chân Cột Nhà Gỗ</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#khu-vuc-san-pham" onclick="filterByCategory('sp-khac')" class="desktop-nav-link">
                            SP Khác <i class="fa-solid fa-angle-down text-[10px]"></i>
                        </a>
                        <div class="flatsome-dropdown">
                            <a href="#khu-vuc-san-pham" onclick="filterByCategory('sp-khac')">Tượng Đá Nghệ Thuật</a>
                            <a href="#khu-vuc-san-pham" onclick="filterByCategory('sp-khac')">Tượng Chăm Pa - Phù Điêu</a>
                            <a href="#khu-vuc-san-pham" onclick="filterByCategory('sp-khac')">Tượng Cô Gái Nghệ Thuật</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#doi-tac" class="desktop-nav-link">Đối Tác</a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#bai-viet" class="desktop-nav-link">Bài Viết</a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#gioi-thieu" class="desktop-nav-link">Về Chúng Tôi</a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#form-bao-gia" class="desktop-nav-link">Báo Giá & Liên Hệ</a>
                    </li>
                </ul>
            </div>
        </nav>

        <!-- Drawer Danh Mục Trên Điện Thoại -->
        <div id="mobileMenuDrawer" class="fixed inset-0 bg-black/60 z-50 hidden lg:hidden">
            <div class="w-72 max-w-[85vw] bg-white h-full overflow-y-auto p-4 flex flex-col justify-between shadow-2xl">
                <div>
                    <div class="flex items-center justify-between pb-3 border-b border-slate-200">
                        <span class="font-bold text-brand-slate text-sm uppercase">Danh Mục Hoàng Huy</span>
                        <button onclick="toggleMobileMenu()" class="w-8 h-8 rounded bg-slate-100 text-slate-700 flex items-center justify-center">
                            <i class="fa-solid fa-xmark"></i>
                        </button>
                    </div>
                    <ul class="mt-3 space-y-1 text-sm font-medium text-slate-700">
                        <li><a href="#trang-chu" onclick="filterByCategory('all'); toggleMobileMenu()" class="block py-2 px-3 rounded hover:bg-amber-50 hover:text-brand-primary"><i class="fa-solid fa-house mr-2 text-brand-primary"></i>Trang chủ</a></li>
                        <li><a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-phat'); toggleMobileMenu()" class="block py-2 px-3 rounded hover:bg-amber-50 hover:text-brand-primary"><i class="fa-solid fa-dharmachakra mr-2 text-brand-primary"></i>Tượng Phật Đá</a></li>
                        <li><a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-cong-giao'); toggleMobileMenu()" class="block py-2 px-3 rounded hover:bg-amber-50 hover:text-brand-primary"><i class="fa-solid fa-cross mr-2 text-brand-primary"></i>Tượng Công Giáo</a></li>
                        <li><a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-dong-vat'); toggleMobileMenu()" class="block py-2 px-3 rounded hover:bg-amber-50 hover:text-brand-primary"><i class="fa-solid fa-shield-cat mr-2 text-brand-primary"></i>Tượng Động Vật - Linh Vật</a></li>
                        <li><a href="#khu-vuc-san-pham" onclick="filterByCategory('do-tho-da'); toggleMobileMenu()" class="block py-2 px-3 rounded hover:bg-amber-50 hover:text-brand-primary"><i class="fa-solid fa-fire-flame-simple mr-2 text-brand-primary"></i>Đồ Thờ Đá Mỹ Nghệ</a></li>
                        <li><a href="#khu-vuc-san-pham" onclick="filterByCategory('da-kien-truc'); toggleMobileMenu()" class="block py-2 px-3 rounded hover:bg-amber-50 hover:text-brand-primary"><i class="fa-solid fa-archway mr-2 text-brand-primary"></i>Đá Trang Trí Kiến Trúc</a></li>
                        <li><a href="#khu-vuc-san-pham" onclick="filterByCategory('sp-khac'); toggleMobileMenu()" class="block py-2 px-3 rounded hover:bg-amber-50 hover:text-brand-primary"><i class="fa-solid fa-Monument mr-2 text-brand-primary"></i>Lăng Mộ - Lan Can - SP Khác</a></li>
                        <li><a href="#doi-tac" onclick="toggleMobileMenu()" class="block py-2 px-3 rounded hover:bg-amber-50 hover:text-brand-primary"><i class="fa-solid fa-handshake mr-2 text-brand-primary"></i>Đối Tác Tiêu Biểu</a></li>
                        <li><a href="#bai-viet" onclick="toggleMobileMenu()" class="block py-2 px-3 rounded hover:bg-amber-50 hover:text-brand-primary"><i class="fa-solid fa-newspaper mr-2 text-brand-primary"></i>Bài Viết Hữu Ích</a></li>
                        <li><a href="#form-bao-gia" onclick="toggleMobileMenu()" class="block py-2 px-3 rounded hover:bg-amber-50 hover:text-brand-primary"><i class="fa-solid fa-file-signature mr-2 text-brand-primary"></i>Yêu Cầu Báo Giá</a></li>
                        <li><a href="#bando-fanpage" onclick="toggleMobileMenu()" class="block py-2 px-3 rounded hover:bg-amber-50 hover:text-brand-primary"><i class="fa-solid fa-map-location-dot mr-2 text-brand-primary"></i>Bản Đồ & Fanpage</a></li>
                    </ul>
                </div>
                <div class="pt-3 border-t border-slate-200 text-xs text-slate-600 space-y-1">
                    <p class="font-bold text-brand-slate">CƠ SỞ ĐÁ TỰ NHIÊN HOÀNG HUY</p>
                    <p>Đ/c: Đường Quán Khái 10, Làng đá Non Nước, Ngũ Hành Sơn, Đà Nẵng</p>
                    <p class="font-bold text-brand-primary">Hotline/Zalo: 0938 534 827</p>
                </div>
            </div>
        </div>
    </header>

    <!-- ==================== 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU ==================== -->
    <!-- Thiết kế ảnh banner Điện Thoại KHÁC VỚI ảnh banner Máy Tính để chữ nhỏ gọn, nằm hoàn toàn bên trong ảnh, tuyệt đối không tràn viền -->
    <section id="trang-chu" class="py-3">
        <div class="flatsome-container">
            <div class="relative w-full overflow-hidden rounded-lg shadow-md border border-slate-200 bg-brand-slate">

                <!-- ================= SLIDE 1 ================= -->
                <div id="bannerSlide0" class="banner-slide block w-full transition-opacity duration-500">
                    <!-- PHIÊN BẢN BANNER MÁY TÍNH (SLIDE 1): Chiều cao cố định 360px bằng đúng Slide 2 -->
                    <div class="hidden md:flex w-full h-[360px] bg-gradient-to-r from-slate-900 via-slate-800 to-amber-900 relative overflow-hidden items-center justify-between px-12 py-6">
                        <div class="w-[58%] z-10 pr-4">
                            <p class="text-amber-400 text-xs font-bold uppercase tracking-widest mb-1.5">
                                CƠ SỞ ĐIÊU KHẮC ĐÁ TỰ NHIÊN HOÀNG HUY • HOANGHUY.COM
                            </p>
                            <h1 class="text-white text-xl lg:text-2xl font-black leading-snug uppercase mb-2">
                                CHUYÊN CUNG CẤP ĐÁ MỸ NGHỆ CAO CẤP TẠI XƯỞNG NON NƯỚC
                            </h1>
                            <div class="space-y-1 text-slate-200 text-xs lg:text-sm mb-3">
                                <p><i class="fa-solid fa-check text-amber-400 mr-1.5"></i><strong>Tượng Phật – Đài phun nước – Linh vật phong thủy</strong></p>
                                <p><i class="fa-solid fa-check text-amber-400 mr-1.5"></i><strong>Lăng mộ – Lan can – Công trình đá kiến trúc</strong></p>
                                <p><i class="fa-solid fa-check text-amber-400 mr-1.5"></i><strong>Đá tự nhiên 100% – Chạm khắc tinh xảo – Giá xưởng</strong></p>
                            </div>
                            <div class="inline-flex flex-wrap items-center gap-3 text-xs text-amber-200 bg-black/30 px-3 py-1.5 rounded border border-amber-500/30">
                                <span><i class="fa-solid fa-location-dot mr-1"></i>Đường Quán Khái 10, Làng đá Non Nước, Đà Nẵng</span>
                                <span>•</span>
                                <span class="font-bold text-white"><i class="fa-solid fa-phone mr-1 text-amber-400"></i>0938 534 827</span>
                            </div>
                        </div>
                        <div class="w-[40%] z-10 grid grid-cols-2 gap-2.5 h-[290px]">
                            <div class="rounded-lg overflow-hidden border-2 border-amber-400/50 bg-slate-800 h-full">
                                <img src="https://drive.google.com/thumbnail?id=1N-y5XXiHtBRzJlG5_-3BjvNmrdquT9p2&sz=w800"
                                     onerror="this.onerror=null;this.src='https://placehold.co/400x500/1e293b/f59e0b?text=Tuong+Phat+Hoang+Huy';"
                                     alt="Tượng đá Hoàng Huy" class="w-full h-full object-cover">
                            </div>
                            <div class="rounded-lg overflow-hidden border-2 border-amber-400/50 bg-slate-800 h-full">
                                <img src="https://drive.google.com/thumbnail?id=12EdHqcjosKt_y6AMLWuHwH3rRck5rxse&sz=w800"
                                     onerror="this.onerror=null;this.src='https://placehold.co/400x500/1e293b/f59e0b?text=Dai+Phun+Nuoc+Da';"
                                     alt="Chế tác đá Hoàng Huy" class="w-full h-full object-cover">
                            </div>
                        </div>
                    </div>

                    <!-- PHIÊN BẢN BANNER ĐIỆN THOẠI RIÊNG BIỆT (SLIDE 1): Chiều cao cố định 230px bằng đúng Slide 2, chữ nhỏ gọn nằm hết trong ảnh -->
                    <div class="flex md:hidden w-full h-[230px] bg-gradient-to-b from-slate-900 via-slate-800 to-amber-950 relative overflow-hidden flex-col justify-center items-center text-center px-5 py-3">
                        <div class="w-full max-w-full overflow-hidden z-10">
                            <p class="text-[10px] font-bold text-amber-400 uppercase tracking-wider mb-1">
                                HOANGHUY.COM • LÀNG ĐÁ NON NƯỚC
                            </p>
                            <h2 class="text-white text-[13px] font-extrabold uppercase leading-tight mb-1.5 px-1">
                                CƠ SỞ ĐIÊU KHẮC ĐÁ TỰ NHIÊN HOÀNG HUY
                            </h2>
                            <p class="text-slate-200 text-[11px] leading-snug mb-1 px-2">
                                Tượng Phật – Đài phun nước – Linh vật<br>
                                Lăng mộ – Lan can – Công trình đá
                            </p>
                            <p class="text-amber-300 text-[10.5px] font-semibold mb-2">
                                Đá tự nhiên • Chạm khắc tinh xảo • Giá xưởng
                            </p>
                            <div class="inline-block bg-amber-600/90 text-white text-[10.5px] font-bold px-2.5 py-1 rounded">
                                Đ/c: Quán Khái 10, Đà Nẵng • ĐT: 0938 534 827
                            </div>
                        </div>
                    </div>
                </div>

                <!-- ================= SLIDE 2 ================= -->
                <div id="bannerSlide1" class="banner-slide hidden w-full transition-opacity duration-500">
                    <!-- PHIÊN BẢN BANNER MÁY TÍNH (SLIDE 2): Chiều cao cố định 360px bằng đúng Slide 1 -->
                    <div class="hidden md:flex w-full h-[360px] bg-gradient-to-r from-amber-950 via-slate-900 to-slate-800 relative overflow-hidden items-center justify-between px-12 py-6">
                        <div class="w-[58%] z-10 pr-4">
                            <p class="text-amber-400 text-xs font-bold uppercase tracking-widest mb-1.5">
                                NGHỆ NHÂN ĐIÊU KHẮC LÂU NĂM • BẢO HÀNH ĐÁ TRỌN ĐỜI
                            </p>
                            <h2 class="text-white text-xl lg:text-2xl font-black leading-snug uppercase mb-2">
                                CHẾ TÁC TƯỢNG ĐÁ & CÔNG TRÌNH TÂM LINH THEO YÊU CẦU
                            </h2>
                            <div class="space-y-1 text-slate-200 text-xs lg:text-sm mb-3">
                                <p><i class="fa-solid fa-star text-amber-400 mr-1.5"></i>Đá cẩm thạch, đá trắng, đá xanh Ấn Độ, đá nguyên khối 100%</p>
                                <p><i class="fa-solid fa-star text-amber-400 mr-1.5"></i>Vận chuyển và lắp đặt tận nơi trên toàn quốc & xuất khẩu quốc tế</p>
                                <p><i class="fa-solid fa-star text-amber-400 mr-1.5"></i>Báo giá trực tiếp tại xưởng sản xuất không qua trung gian</p>
                            </div>
                            <div class="inline-flex flex-wrap items-center gap-3 text-xs text-amber-200 bg-black/30 px-3 py-1.5 rounded border border-amber-500/30">
                                <span><i class="fa-solid fa-Location-arrow mr-1"></i>Khu chế tác Làng đá Non Nước – Ngũ Hành Sơn – Đà Nẵng</span>
                                <span>•</span>
                                <span class="font-bold text-white">Hotline/Zalo: 0938 534 827</span>
                            </div>
                        </div>
                        <div class="w-[40%] z-10 grid grid-cols-2 gap-2.5 h-[290px]">
                            <div class="rounded-lg overflow-hidden border-2 border-amber-400/50 bg-slate-800 h-full">
                                <img src="https://drive.google.com/thumbnail?id=1_enlCf1hPn-9vF0mqmgzwsE4E35lcHIX&sz=w800"
                                     onerror="this.onerror=null;this.src='https://placehold.co/400x500/1e293b/f59e0b?text=Linh+Vat+Phong+Thuy';"
                                     alt="Linh vật đá Hoàng Huy" class="w-full h-full object-cover">
                            </div>
                            <div class="rounded-lg overflow-hidden border-2 border-amber-400/50 bg-slate-800 h-full">
                                <img src="https://drive.google.com/thumbnail?id=1Etj-_9HDOdkysFJNKetZ52YNAyEX1eu-&sz=w800"
                                     onerror="this.onerror=null;this.src='https://placehold.co/400x500/1e293b/f59e0b?text=Cong+Trinh+Da';"
                                     alt="Công trình đá Hoàng Huy" class="w-full h-full object-cover">
                            </div>
                        </div>
                    </div>

                    <!-- PHIÊN BẢN BANNER ĐIỆN THOẠI RIÊNG BIỆT (SLIDE 2): Chiều cao cố định 230px bằng đúng Slide 1, chữ nhỏ gọn nằm hết trong ảnh -->
                    <div class="flex md:hidden w-full h-[230px] bg-gradient-to-b from-amber-950 via-slate-900 to-slate-800 relative overflow-hidden flex-col justify-center items-center text-center px-5 py-3">
                        <div class="w-full max-w-full overflow-hidden z-10">
                            <p class="text-[10px] font-bold text-amber-400 uppercase tracking-wider mb-1">
                                UY TÍN TẠI XƯỞNG • GIAO LẮP TOÀN QUỐC
                            </p>
                            <h2 class="text-white text-[13px] font-extrabold uppercase leading-tight mb-1.5 px-1">
                                CHẾ TÁC ĐÁ MỸ NGHỆ NGUYÊN KHỐI THEO YÊU CẦU
                            </h2>
                            <p class="text-slate-200 text-[11px] leading-snug mb-1 px-2">
                                Đá Cẩm Thạch • Đá Xanh Ấn Độ • Đá Trắng Tự Nhiên<br>
                                Bảo hành trọn đời chất lượng đá tại xưởng
                            </p>
                            <p class="text-amber-300 text-[10.5px] font-semibold mb-2">
                                Khu chế tác Làng đá Non Nước – Ngũ Hành Sơn – Đà Nẵng
                            </p>
                            <div class="inline-block bg-brand-primary text-white text-[10.5px] font-bold px-2.5 py-1 rounded">
                                Tư vấn & Báo giá: 0938 534 827
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Nút Chuyển Slide Trái / Phải -->
                <button onclick="changeBannerSlide(-1)" aria-label="Slide trước" class="absolute left-2 top-1/2 -translate-y-1/2 w-7 h-7 md:w-9 md:h-9 rounded-full bg-black/40 hover:bg-black/70 text-white flex items-center justify-center z-20 transition">
                    <i class="fa-solid fa-chevron-left text-xs md:text-sm"></i>
                </button>
                <button onclick="changeBannerSlide(1)" aria-label="Slide tiếp" class="absolute right-2 top-1/2 -translate-y-1/2 w-7 h-7 md:w-9 md:h-9 rounded-full bg-black/40 hover:bg-black/70 text-white flex items-center justify-center z-20 transition">
                    <i class="fa-solid fa-chevron-right text-xs md:text-sm"></i>
                </button>

                <!-- Chấm tròn báo trạng thái Slide -->
                <div class="absolute bottom-2 left-1/2 -translate-x-1/2 flex items-center gap-2 z-20">
                    <button id="bannerDot0" onclick="goToBannerSlide(0)" class="w-2.5 h-2.5 rounded-full bg-amber-400 transition"></button>
                    <button id="bannerDot1" onclick="goToBannerSlide(1)" class="w-2.5 h-2.5 rounded-full bg-white/50 transition"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== DANH MỤC SẢN PHẨM TRANG CHỦ (CHỮ NHỎ GỌN, ĐẸP TRÊN MÁY TÍNH & ĐIỆN THOẠI) ==================== -->
    <section class="py-5 bg-white border-y border-slate-200">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-main">
                    <h2 class="section-title-text">DANH MỤC SẢN PHẨM CHÍNH</h2>
                </div>
            </div>

            <!-- Chia 2 cột trên điện thoại, 6 cột trên máy tính, chữ danh mục nhỏ gọn nằm trên 1 dòng -->
            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-2.5 md:gap-3.5">
                <a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-phat')" class="group border border-slate-200 rounded-lg overflow-hidden bg-slate-50 hover:border-brand-primary hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
                        <img src="https://drive.google.com/thumbnail?id=1N-y5XXiHtBRzJlG5_-3BjvNmrdquT9p2&sz=w600"
                             onerror="this.onerror=null;this.src='https://placehold.co/400x300/1e293b/f59e0b?text=Tuong+Phat';"
                             alt="Tượng Phật Đá" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2 text-center bg-white">
                        <h3 class="text-xs font-bold text-brand-slate group-hover:text-brand-primary uppercase whitespace-nowrap overflow-hidden text-ellipsis">
                            Tượng Phật Đá
                        </h3>
                        <p class="text-[11px] text-slate-500">Quan Âm, Di Lặc, Thích Ca</p>
                    </div>
                </a>

                <a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-cong-giao')" class="group border border-slate-200 rounded-lg overflow-hidden bg-slate-50 hover:border-brand-primary hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
                        <img src="https://drive.google.com/thumbnail?id=1hSmK3rXsUikb8MqBd4haZ6bgUMHO8_Pc&sz=w600"
                             onerror="this.onerror=null;this.src='https://placehold.co/400x300/1e293b/f59e0b?text=Tuong+Cong+Giao';"
                             alt="Tượng Công Giáo" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2 text-center bg-white">
                        <h3 class="text-xs font-bold text-brand-slate group-hover:text-brand-primary uppercase whitespace-nowrap overflow-hidden text-ellipsis">
                            Tượng Công Giáo
                        </h3>
                        <p class="text-[11px] text-slate-500">Đức Mẹ, Chúa Giêsu, Giuse</p>
                    </div>
                </a>

                <a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-dong-vat')" class="group border border-slate-200 rounded-lg overflow-hidden bg-slate-50 hover:border-brand-primary hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
                        <img src="https://drive.google.com/thumbnail?id=1_enlCf1hPn-9vF0mqmgzwsE4E35lcHIX&sz=w600"
                             onerror="this.onerror=null;this.src='https://placehold.co/400x300/1e293b/f59e0b?text=Tuong+Dong+Vat';"
                             alt="Tượng Động Vật" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2 text-center bg-white">
                        <h3 class="text-xs font-bold text-brand-slate group-hover:text-brand-primary uppercase whitespace-nowrap overflow-hidden text-ellipsis">
                            Tượng Động Vật
                        </h3>
                        <p class="text-[11px] text-slate-500">Kỳ Lân, Sư Tử, Tỳ Hưu, Rồng</p>
                    </div>
                </a>

                <a href="#khu-vuc-san-pham" onclick="filterByCategory('do-tho-da')" class="group border border-slate-200 rounded-lg overflow-hidden bg-slate-50 hover:border-brand-primary hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
                        <img src="https://drive.google.com/thumbnail?id=1FjkJWoKEGTKrEolABBL8b3P62PREo-4h&sz=w600"
                             onerror="this.onerror=null;this.src='https://placehold.co/400x300/1e293b/f59e0b?text=Do+Tho+Da';"
                             alt="Đồ Thờ Đá" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2 text-center bg-white">
                        <h3 class="text-xs font-bold text-brand-slate group-hover:text-brand-primary uppercase whitespace-nowrap overflow-hidden text-ellipsis">
                            Đồ Thờ Đá
                        </h3>
                        <p class="text-[11px] text-slate-500">Lư Hương, Cây Hương, Bàn Lễ</p>
                    </div>
                </a>

                <a href="#khu-vuc-san-pham" onclick="filterByCategory('da-kien-truc')" class="group border border-slate-200 rounded-lg overflow-hidden bg-slate-50 hover:border-brand-primary hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
                        <img src="https://drive.google.com/thumbnail?id=12EdHqcjosKt_y6AMLWuHwH3rRck5rxse&sz=w600"
                             onerror="this.onerror=null;this.src='https://placehold.co/400x300/1e293b/f59e0b?text=Da+Kien+Truc';"
                             alt="Đá Trang Trí Kiến Trúc" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2 text-center bg-white">
                        <h3 class="text-xs font-bold text-brand-slate group-hover:text-brand-primary uppercase whitespace-nowrap overflow-hidden text-ellipsis">
                            Đá Trang Trí Kiến Trúc
                        </h3>
                        <p class="text-[11px] text-slate-500">Đài Phun Nước, Lăng Mộ, Lan Can</p>
                    </div>
                </a>

                <a href="#khu-vuc-san-pham" onclick="filterByCategory('sp-khac')" class="group border border-slate-200 rounded-lg overflow-hidden bg-slate-50 hover:border-brand-primary hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
                        <img src="https://drive.google.com/thumbnail?id=1ayS6Qj6yH5YovdU7MBHBdmUpgrN0R6nE&sz=w600"
                             onerror="this.onerror=null;this.src='https://placehold.co/400x300/1e293b/f59e0b?text=Tuong+Nghe+Thuat';"
                             alt="Sản Phẩm Đá Khác" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2 text-center bg-white">
                        <h3 class="text-xs font-bold text-brand-slate group-hover:text-brand-primary uppercase whitespace-nowrap overflow-hidden text-ellipsis">
                            SP Khác & Công Trình
                        </h3>
                        <p class="text-[11px] text-slate-500">Tượng Nghệ Thuật, Đèn Đá, Biển Đá</p>
                    </div>
                </a>
            </div>
        </div>
    </section>

    <!-- ==================== GIỚI THIỆU & 4 CAM KẾT VÀNG (THEO MẪU DANGUYENCONG.COM) ==================== -->
    <section id="gioi-thieu" class="py-6">
        <div class="flatsome-container">
            <div class="bg-white rounded-lg p-4 md:p-6 border border-slate-200 shadow-sm mb-5">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-center">
                    <div class="lg:col-span-7 space-y-2.5">
                        <h2 class="text-lg md:text-xl font-black text-brand-primary uppercase">
                            Cơ Sở Điêu Khắc Đá Tự Nhiên Hoàng Huy
                        </h2>
                        <p class="text-sm font-semibold text-slate-700">
                            Cảm ơn quý khách hàng đã đến với xưởng chế tác đá mỹ nghệ của chúng tôi!
                        </p>
                        <p class="text-xs md:text-sm text-slate-600 leading-relaxed">
                            <strong>Cơ Sở Điêu Khắc Đá Tự Nhiên Hoàng Huy (<a href="https://hoanghuy.com" class="text-brand-primary underline">hoanghuy.com</a>)</strong> chuyên cung cấp và chế tác các sản phẩm đá mỹ nghệ cao cấp: <strong>Tượng Phật – Đài phun nước – Linh vật phong thủy, Lăng mộ – Lan can – Công trình đá kiến trúc</strong>. Toàn bộ tác phẩm đều được chế tác từ <strong>đá tự nhiên nguyên khối 100%</strong>, chạm khắc tinh xảo bởi đội ngũ nghệ nhân lành nghề tại Làng đá mỹ nghệ Non Nước Đà Nẵng với mức <strong>giá xưởng tận gốc</strong>.
                        </p>
                        <p class="text-xs md:text-sm text-slate-600 leading-relaxed">
                            Nếu quý khách có bất kỳ nhu cầu tư vấn về mẫu mã, kích thước phong thủy, chất liệu đá hoặc vận chuyển lắp đặt toàn quốc, xin vui lòng liên hệ trực tiếp qua <strong>Hotline/Zalo: <a href="tel:0938534827" class="text-brand-primary font-bold">0938 534 827</a></strong> hoặc ghé thăm xưởng tại <strong>Đường Quán Khái 10, Khu chế tác Làng đá mỹ nghệ Non Nước – Ngũ Hành Sơn – Đà Nẵng</strong>.
                        </p>
                    </div>
                    <div class="lg:col-span-5">
                        <div class="grid grid-cols-2 gap-2.5">
                            <img src="https://drive.google.com/thumbnail?id=1wx0-xXrwEa0azmS9vzUEPLt_y8yFFnOF&sz=w600"
                                 onerror="this.onerror=null;this.src='https://placehold.co/400x300/1e293b/f59e0b?text=Xuong+Da+Hoang+Huy';"
                                 alt="Xưởng điêu khắc đá Hoàng Huy" class="w-full h-36 md:h-44 object-cover rounded border border-slate-200">
                            <img src="https://drive.google.com/thumbnail?id=1ISDjvu4NO6WtUm4r-MHlt7yC1RVqTx4a&sz=w600"
                                 onerror="this.onerror=null;this.src='https://placehold.co/400x300/1e293b/f59e0b?text=Che+Tac+Tinh+Xao';"
                                 alt="Nghệ nhân đá Non Nước Hoàng Huy" class="w-full h-36 md:h-44 object-cover rounded border border-slate-200">
                        </div>
                    </div>
                </div>
            </div>

            <!-- 4 Cam Kết Của Hoàng Huy Với Khách Hàng (Giống bố cục 4 cột Flatsome của web mẫu) -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3">
                <div class="bg-white p-3.5 md:p-4 rounded-lg border border-slate-200 shadow-sm flex flex-col items-center text-center">
                    <div class="w-11 h-11 rounded-full bg-amber-100 text-brand-primary flex items-center justify-center mb-2 text-lg">
                        <i class="fa-solid fa-gem"></i>
                    </div>
                    <h3 class="text-xs md:text-sm font-bold text-brand-slate uppercase mb-1">Sản phẩm chất lượng</h3>
                    <p class="text-xs text-slate-600 leading-relaxed">
                        Chế tác từ đá tự nhiên nguyên khối 100%, tuyển chọn kỹ lưỡng, bền vững vĩnh cửu trước mọi thời tiết.
                    </p>
                </div>
                <div class="bg-white p-3.5 md:p-4 rounded-lg border border-slate-200 shadow-sm flex flex-col items-center text-center">
                    <div class="w-11 h-11 rounded-full bg-amber-100 text-brand-primary flex items-center justify-center mb-2 text-lg">
                        <i class="fa-solid fa-layer-group"></i>
                    </div>
                    <h3 class="text-xs md:text-sm font-bold text-brand-slate uppercase mb-1">Mẫu mã đa dạng</h3>
                    <p class="text-xs text-slate-600 leading-relaxed">
                        Đầy đủ Tượng Phật, Công Giáo, Linh vật, Đài phun nước, Lăng mộ, Lan can và nhận đặt theo yêu cầu riêng.
                    </p>
                </div>
                <div class="bg-white p-3.5 md:p-4 rounded-lg border border-slate-200 shadow-sm flex flex-col items-center text-center">
                    <div class="w-11 h-11 rounded-full bg-amber-100 text-brand-primary flex items-center justify-center mb-2 text-lg">
                        <i class="fa-solid fa-hands-holding-circle"></i>
                    </div>
                    <h3 class="text-xs md:text-sm font-bold text-brand-slate uppercase mb-1">Nghệ nhân lâu năm</h3>
                    <p class="text-xs text-slate-600 leading-relaxed">
                        Đội ngũ nghệ nhân Làng đá Non Nước giàu kinh nghiệm, chạm khắc tỉ mỉ, có hồn và chuẩn phong thủy.
                    </p>
                </div>
                <div class="bg-white p-3.5 md:p-4 rounded-lg border border-slate-200 shadow-sm flex flex-col items-center text-center">
                    <div class="w-11 h-11 rounded-full bg-amber-100 text-brand-primary flex items-center justify-center mb-2 text-lg">
                        <i class="fa-solid fa-headset"></i>
                    </div>
                    <h3 class="text-xs md:text-sm font-bold text-brand-slate uppercase mb-1">Giá xưởng & Tận tâm</h3>
                    <p class="text-xs text-slate-600 leading-relaxed">
                        Báo giá gốc trực tiếp tại xưởng Quán Khái 10, giao hàng và lắp đặt an toàn trên toàn quốc & quốc tế.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== KHU VỰC SẢN PHẨM THỰC TẾ (16 ẢNH GOOGLE DRIVE + % GIẢM GIÁ GÓC TRÊN BÊN TRÁI GIỐNG FLATSOME) ==================== -->
    <section id="khu-vuc-san-pham" class="py-5">
        <div class="flatsome-container">

            <!-- Bộ lọc nhanh danh mục sản phẩm (Thiết kế gọn gàng cho cả máy tính & điện thoại) -->
            <div class="bg-white p-3 rounded-lg border border-slate-200 shadow-sm mb-5 flex flex-wrap items-center justify-between gap-2">
                <div class="flex flex-wrap items-center gap-1.5" id="categoryFilterButtons">
                    <button onclick="filterByCategory('all')" data-cat="all" class="cat-filter-btn bg-brand-primary text-white text-xs font-bold px-3 py-1.5 rounded transition whitespace-nowrap">
                        Tất cả sản phẩm (16)
                    </button>
                    <button onclick="filterByCategory('tuong-phat')" data-cat="tuong-phat" class="cat-filter-btn bg-slate-100 hover:bg-amber-100 text-slate-700 text-xs font-semibold px-3 py-1.5 rounded transition whitespace-nowrap">
                        Tượng Phật Đá
                    </button>
                    <button onclick="filterByCategory('tuong-cong-giao')" data-cat="tuong-cong-giao" class="cat-filter-btn bg-slate-100 hover:bg-amber-100 text-slate-700 text-xs font-semibold px-3 py-1.5 rounded transition whitespace-nowrap">
                        Tượng Công Giáo
                    </button>
                    <button onclick="filterByCategory('tuong-dong-vat')" data-cat="tuong-dong-vat" class="cat-filter-btn bg-slate-100 hover:bg-amber-100 text-slate-700 text-xs font-semibold px-3 py-1.5 rounded transition whitespace-nowrap">
                        Tượng Động Vật - Linh Vật
                    </button>
                    <button onclick="filterByCategory('do-tho-da')" data-cat="do-tho-da" class="cat-filter-btn bg-slate-100 hover:bg-amber-100 text-slate-700 text-xs font-semibold px-3 py-1.5 rounded transition whitespace-nowrap">
                        Đồ Thờ Đá
                    </button>
                    <button onclick="filterByCategory('da-kien-truc')" data-cat="da-kien-truc" class="cat-filter-btn bg-slate-100 hover:bg-amber-100 text-slate-700 text-xs font-semibold px-3 py-1.5 rounded transition whitespace-nowrap">
                        Đài Phun Nước - Lăng Mộ - Kiến Trúc
                    </button>
                    <button onclick="filterByCategory('sp-khac')" data-cat="sp-khac" class="cat-filter-btn bg-slate-100 hover:bg-amber-100 text-slate-700 text-xs font-semibold px-3 py-1.5 rounded transition whitespace-nowrap">
                        SP Khác
                    </button>
                </div>
                <div id="filterStatusText" class="text-xs text-slate-500 font-medium">
                    Hiển thị 16 tác phẩm thực tế tại xưởng Hoàng Huy
                </div>
            </div>

            <!-- Danh sách tất cả các phân khu sản phẩm theo đúng bố cục web mẫu danguyencong.com -->
            <div id="allProductSections" class="space-y-8"></div>

        </div>
    </section>

    <!-- ==================== DANH MỤC CÁC ĐỐI TÁC TIÊU BIỂU ==================== -->
    <section id="doi-tac" class="py-6 bg-white border-t border-b border-slate-200">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-main">
                    <h2 class="section-title-text">ĐỐI TÁC & KHÁCH HÀNG TIÊU BIỂU</h2>
                </div>
            </div>
            <p class="text-center text-xs md:text-sm text-slate-600 mb-5 max-w-3xl mx-auto">
                Cơ sở điêu khắc đá tự nhiên Hoàng Huy tự hào là đối tác chế tác, cung ứng và thi công đá mỹ nghệ cho nhiều công trình tâm linh, chùa chiền, giáo xứ, khu nghỉ dưỡng và tập đoàn xây dựng trên toàn quốc.
            </p>

            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3">
                <div class="p-3.5 rounded-lg border border-slate-200 bg-slate-50 hover:border-brand-primary transition text-center flex flex-col items-center justify-center">
                    <div class="w-11 h-11 rounded-full bg-amber-100 text-brand-primary flex items-center justify-center mb-2 text-lg">
                        <i class="fa-solid fa-vihara"></i>
                    </div>
                    <h3 class="text-xs font-bold text-brand-slate uppercase">Hệ Thống Tự Viện & Chùa</h3>
                    <p class="text-[11px] text-slate-500 mt-0.5">Tượng Phật & Đồ Thờ Đá</p>
                </div>

                <div class="p-3.5 rounded-lg border border-slate-200 bg-slate-50 hover:border-brand-primary transition text-center flex flex-col items-center justify-center">
                    <div class="w-11 h-11 rounded-full bg-amber-100 text-brand-primary flex items-center justify-center mb-2 text-lg">
                        <i class="fa-solid fa-church"></i>
                    </div>
                    <h3 class="text-xs font-bold text-brand-slate uppercase">Các Giáo Xứ Công Giáo</h3>
                    <p class="text-[11px] text-slate-500 mt-0.5">Tượng Đài Đức Mẹ & Các Thánh</p>
                </div>

                <div class="p-3.5 rounded-lg border border-slate-200 bg-slate-50 hover:border-brand-primary transition text-center flex flex-col items-center justify-center">
                    <div class="w-11 h-11 rounded-full bg-amber-100 text-brand-primary flex items-center justify-center mb-2 text-lg">
                        <i class="fa-solid fa-hotel"></i>
                    </div>
                    <h3 class="text-xs font-bold text-brand-slate uppercase">Resort & Khu Nghỉ Dưỡng</h3>
                    <p class="text-[11px] text-slate-500 mt-0.5">Đài Phun Nước & Tượng Cảnh Quan</p>
                </div>

                <div class="p-3.5 rounded-lg border border-slate-200 bg-slate-50 hover:border-brand-primary transition text-center flex flex-col items-center justify-center">
                    <div class="w-11 h-11 rounded-full bg-amber-100 text-brand-primary flex items-center justify-center mb-2 text-lg">
                        <i class="fa-solid fa-building-columns"></i>
                    </div>
                    <h3 class="text-xs font-bold text-brand-slate uppercase">Công Viên Tâm Linh</h3>
                    <p class="text-[11px] text-slate-500 mt-0.5">Lăng Mộ Đá & Lan Can Đá</p>
                </div>

                <div class="p-3.5 rounded-lg border border-slate-200 bg-slate-50 hover:border-brand-primary transition text-center flex flex-col items-center justify-center">
                    <div class="w-11 h-11 rounded-full bg-amber-100 text-brand-primary flex items-center justify-center mb-2 text-lg">
                        <i class="fa-solid fa-compass-drafting"></i>
                    </div>
                    <h3 class="text-xs font-bold text-brand-slate uppercase">Nhà Thầu Kiến Trúc</h3>
                    <p class="text-[11px] text-slate-500 mt-0.5">Chân Tảng Cột & Đá Công Trình</p>
                </div>

                <div class="p-3.5 rounded-lg border border-slate-200 bg-slate-50 hover:border-brand-primary transition text-center flex flex-col items-center justify-center">
                    <div class="w-11 h-11 rounded-full bg-amber-100 text-brand-primary flex items-center justify-center mb-2 text-lg">
                        <i class="fa-solid fa-ship"></i>
                    </div>
                    <h3 class="text-xs font-bold text-brand-slate uppercase">Đối Tác Xuất Khẩu</h3>
                    <p class="text-[11px] text-slate-500 mt-0.5">Vận Chuyển Đá Quốc Tế</p>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== CÂU HỎI THƯỜNG GẶP & FORM YÊU CẦU BÁO GIÁ TRANG CHỦ ==================== -->
    <section id="form-bao-gia" class="py-7">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6">

                <!-- Cột Trái: Những câu hỏi thường gặp về điêu khắc đá (Giống danguyencong.com) -->
                <div class="lg:col-span-6 bg-white p-4 md:p-6 rounded-lg border border-slate-200 shadow-sm">
                    <h2 class="text-base md:text-lg font-black text-brand-slate uppercase mb-4 pb-2 border-b-2 border-brand-primary">
                        Những câu hỏi về điêu khắc đá bạn sẽ quan tâm
                    </h2>

                    <div class="space-y-2.5">
                        <div class="border border-slate-200 rounded-md overflow-hidden">
                            <button onclick="toggleFaq(0)" class="w-full text-left px-3.5 py-2.5 bg-slate-50 hover:bg-amber-50 font-bold text-xs md:text-sm text-brand-slate flex items-center justify-between">
                                <span>1. Vì sao khách hàng tin tưởng chọn Đá Tự Nhiên Hoàng Huy?</span>
                                <i id="faqIcon0" class="fa-solid fa-minus text-brand-primary text-xs"></i>
                            </button>
                            <div id="faqContent0" class="px-3.5 py-2.5 text-xs md:text-sm text-slate-600 leading-relaxed bg-white border-t border-slate-100">
                                Cơ sở điêu khắc đá tự nhiên Hoàng Huy trực tiếp sản xuất tại Đường Quán Khái 10, Khu chế tác Làng đá mỹ nghệ Non Nước, Đà Nẵng. Chúng tôi cam kết đá tự nhiên nguyên khối 100%, chạm khắc tinh xảo bởi nghệ nhân lâu năm và mức giá gốc tại xưởng không qua trung gian.
                            </div>
                        </div>

                        <div class="border border-slate-200 rounded-md overflow-hidden">
                            <button onclick="toggleFaq(1)" class="w-full text-left px-3.5 py-2.5 bg-slate-50 hover:bg-amber-50 font-bold text-xs md:text-sm text-brand-slate flex items-center justify-between">
                                <span>2. Các loại đá nào thường được Hoàng Huy sử dụng chế tác?</span>
                                <i id="faqIcon1" class="fa-solid fa-plus text-brand-primary text-xs"></i>
                            </button>
                            <div id="faqContent1" class="hidden px-3.5 py-2.5 text-xs md:text-sm text-slate-600 leading-relaxed bg-white border-t border-slate-100">
                                Chúng tôi sử dụng đá cẩm thạch trắng, cẩm thạch xám, đá vàng cà rốt, đá granite tự nhiên, đá xanh Thanh Hóa, đá xanh Ấn Độ và đá ngọc Onyx cao cấp phù hợp cho từng dòng Tượng Phật, Linh Vật, Đài Phun Nước hay Lăng Mộ Đá.
                            </div>
                        </div>

                        <div class="border border-slate-200 rounded-md overflow-hidden">
                            <button onclick="toggleFaq(2)" class="w-full text-left px-3.5 py-2.5 bg-slate-50 hover:bg-amber-50 font-bold text-xs md:text-sm text-brand-slate flex items-center justify-between">
                                <span>3. Hoàng Huy có nhận điêu khắc đá theo mẫu yêu cầu riêng không?</span>
                                <i id="faqIcon2" class="fa-solid fa-plus text-brand-primary text-xs"></i>
                            </button>
                            <div id="faqContent2" class="hidden px-3.5 py-2.5 text-xs md:text-sm text-slate-600 leading-relaxed bg-white border-t border-slate-100">
                                Có. Quý khách chỉ cần gửi hình ảnh, bản vẽ hoặc kích thước mong muốn qua Zalo <strong>0938 534 827</strong>, nghệ nhân Hoàng Huy sẽ tư vấn kích thước Lỗ Ban chuẩn phong thủy và chế tác hoàn thiện đúng 100% yêu cầu.
                            </div>
                        </div>

                        <div class="border border-slate-200 rounded-md overflow-hidden">
                            <button onclick="toggleFaq(3)" class="w-full text-left px-3.5 py-2.5 bg-slate-50 hover:bg-amber-50 font-bold text-xs md:text-sm text-brand-slate flex items-center justify-between">
                                <span>4. Chính sách vận chuyển, lắp đặt và bảo hành như thế nào?</span>
                                <i id="faqIcon3" class="fa-solid fa-plus text-brand-primary text-xs"></i>
                            </button>
                            <div id="faqContent3" class="hidden px-3.5 py-2.5 text-xs md:text-sm text-slate-600 leading-relaxed bg-white border-t border-slate-100">
                                Xưởng Hoàng Huy giao hàng và lắp đặt trọn gói tận nơi trên toàn quốc (63 tỉnh thành) và đóng kiện gỗ xuất khẩu quốc tế. Toàn bộ sản phẩm được bảo hành trọn đời về chất lượng đá tự nhiên.
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Cột Phải: Form Yêu Cầu Tư Vấn Và Báo Giá Tại Trang Chủ -->
                <div class="lg:col-span-6 bg-white p-4 md:p-6 rounded-lg border-2 border-brand-primary shadow-sm">
                    <h2 class="text-base md:text-lg font-black text-brand-primary uppercase mb-1">
                        Form Yêu Cầu Tư Vấn & Báo Giá Nhanh
                    </h2>
                    <p class="text-xs text-slate-600 mb-4">
                        Quý khách để lại thông tin, xưởng Đá Tự Nhiên Hoàng Huy sẽ liên hệ báo giá gốc tại xưởng chỉ trong 5 phút!
                    </p>

                    <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="space-y-3">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1">Họ và tên quý khách *</label>
                                <input id="qName" type="text" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 text-xs md:text-sm border border-slate-300 rounded focus:outline-none focus:border-brand-primary">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                                <input id="qPhone" type="tel" required placeholder="Ví dụ: 0938 534 827" class="w-full px-3 py-2 text-xs md:text-sm border border-slate-300 rounded focus:outline-none focus:border-brand-primary">
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1">Hạng mục quan tâm</label>
                                <select id="qCategory" class="w-full px-3 py-2 text-xs md:text-sm border border-slate-300 rounded focus:outline-none focus:border-brand-primary bg-white">
                                    <option value="Tượng Phật Đá Tự Nhiên">Tượng Phật Đá Tự Nhiên</option>
                                    <option value="Tượng Công Giáo Bằng Đá">Tượng Công Giáo Bằng Đá</option>
                                    <option value="Linh Vật Phong Thủy (Kỳ Lân, Sư Tử, Tỳ Hưu, Rồng)">Linh Vật Phong Thủy (Kỳ Lân, Sư Tử, Rồng...)</option>
                                    <option value="Đài Phun Nước Bằng Đá">Đài Phun Nước Bằng Đá</option>
                                    <option value="Đồ Thờ Đá (Lư Hương, Bàn Lễ, Cây Hương)">Đồ Thờ Đá (Lư Hương, Bàn Lễ, Cây Hương)</option>
                                    <option value="Lăng Mộ Đá - Lan Can Đá - Công Trình Đá">Lăng Mộ Đá - Lan Can Đá - Công Trình Đá</option>
                                    <option value="Chế tác theo mẫu riêng">Chế tác theo mẫu riêng</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1">Kích thước / Chất liệu dự kiến</label>
                                <input id="qSize" type="text" placeholder="VD: Cao 1m5, đá cẩm thạch trắng..." class="w-full px-3 py-2 text-xs md:text-sm border border-slate-300 rounded focus:outline-none focus:border-brand-primary">
                            </div>
                        </div>

                        <div>
                            <label class="block text-xs font-bold text-slate-700 mb-1">Yêu cầu chi tiết & Địa chỉ nhận hàng</label>
                            <textarea id="qNote" rows="3" placeholder="Nhập yêu cầu cụ thể về mẫu sản phẩm hoặc địa chỉ lắp đặt..." class="w-full px-3 py-2 text-xs md:text-sm border border-slate-300 rounded focus:outline-none focus:border-brand-primary"></textarea>
                        </div>

                        <button type="submit" class="w-full bg-brand-primary hover:bg-brand-dark text-white font-bold text-xs md:text-sm uppercase py-2.5 px-4 rounded shadow transition flex items-center justify-center gap-2">
                            <i class="fa-solid fa-paper-plane"></i> Gửi Yêu Cầu Nhận Báo Giá Giá Xưởng
                        </button>
                    </form>
                </div>

            </div>
        </div>
    </section>

    <!-- ==================== DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC - BÀI VIẾT HỮU ÍCH GIỐNG DANGUYENCONG.COM) ==================== -->
    <section id="bai-viet" class="py-6 bg-white border-t border-slate-200">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-main">
                    <h2 class="section-title-text">TIN TỨC - BÀI VIẾT HỮU ÍCH</h2>
                </div>
            </div>

            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-4">
                <!-- Bài viết 1 -->
                <article class="bg-slate-50 rounded-lg border border-slate-200 overflow-hidden hover:shadow-md transition flex flex-col justify-between">
                    <div>
                        <div class="aspect-[16/10] w-full overflow-hidden bg-slate-200">
                            <img src="https://drive.google.com/thumbnail?id=1N-y5XXiHtBRzJlG5_-3BjvNmrdquT9p2&sz=w600"
                                 onerror="this.onerror=null;this.src='https://placehold.co/600x400/1e293b/f59e0b?text=Tuong+Phat+Da';"
                                 alt="Hướng dẫn chọn tượng Phật đá tự nhiên" class="w-full h-full object-cover">
                        </div>
                        <div class="p-3">
                            <span class="text-[11px] text-brand-primary font-semibold">Kiến thức tâm linh</span>
                            <h3 class="product-title-full mt-1">
                                Hướng dẫn cách chọn Tượng Phật bằng đá tự nhiên nguyên khối chuẩn phong thủy tại xưởng
                            </h3>
                            <p class="text-xs text-slate-600 line-clamp-3">
                                Tìm hiểu kinh nghiệm lựa chọn đá cẩm thạch trắng nguyên khối khi thỉnh tượng Phật Quan Âm, Phật Di Lặc và Phật Thích Ca giúp không gian thờ tự trang nghiêm, thanh tịnh.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 pt-1">
                        <a href="#form-bao-gia" class="text-xs font-bold text-brand-primary hover:underline">Tư vấn chi tiết <i class="fa-solid fa-arrow-right ml-1"></i></a>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="bg-slate-50 rounded-lg border border-slate-200 overflow-hidden hover:shadow-md transition flex flex-col justify-between">
                    <div>
                        <div class="aspect-[16/10] w-full overflow-hidden bg-slate-200">
                            <img src="https://drive.google.com/thumbnail?id=12EdHqcjosKt_y6AMLWuHwH3rRck5rxse&sz=w600"
                                 onerror="this.onerror=null;this.src='https://placehold.co/600x400/1e293b/f59e0b?text=Dai+Phun+Nuoc+Da';"
                                 alt="Đài phun nước bằng đá tự nhiên" class="w-full h-full object-cover">
                        </div>
                        <div class="p-3">
                            <span class="text-[11px] text-brand-primary font-semibold">Kiến trúc sân vườn</span>
                            <h3 class="product-title-full mt-1">
                                Đài phun nước bằng đá tự nhiên – Điểm nhấn vượng khí và đẳng cấp cho biệt thự, sân vườn
                            </h3>
                            <p class="text-xs text-slate-600 line-clamp-3">
                                Các mẫu đài phun nước đá cẩm thạch nhiều tầng chạm khắc hoa sen, cá chép, thiên thần giúp kích hoạt nguồn năng lượng thủy khí dồi dào và tài lộc cho gia chủ.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 pt-1">
                        <a href="#form-bao-gia" class="text-xs font-bold text-brand-primary hover:underline">Tư vấn chi tiết <i class="fa-solid fa-arrow-right ml-1"></i></a>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="bg-slate-50 rounded-lg border border-slate-200 overflow-hidden hover:shadow-md transition flex flex-col justify-between">
                    <div>
                        <div class="aspect-[16/10] w-full overflow-hidden bg-slate-200">
                            <img src="https://drive.google.com/thumbnail?id=1_enlCf1hPn-9vF0mqmgzwsE4E35lcHIX&sz=w600"
                                 onerror="this.onerror=null;this.src='https://placehold.co/600x400/1e293b/f59e0b?text=Ky+Lan+Su+Tu+Da';"
                                 alt="Ý nghĩa tượng Kỳ Lân và Sư Tử đá" class="w-full h-full object-cover">
                        </div>
                        <div class="p-3">
                            <span class="text-[11px] text-brand-primary font-semibold">Phong thủy linh vật</span>
                            <h3 class="product-title-full mt-1">
                                Ý nghĩa và cách đặt Tượng Kỳ Lân Đá, Sư Tử Đá, Tỳ Hưu Đá trấn trạch thu hút tài lộc
                            </h3>
                            <p class="text-xs text-slate-600 line-clamp-3">
                                Cách phân biệt vị trí đặt cặp Kỳ Lân đá, Nghê đá Việt và Sư Tử đá trước cổng cơ quan, biệt thự, nhà thờ họ để trấn trạch, hóa giải sát khí hiệu quả.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 pt-1">
                        <a href="#form-bao-gia" class="text-xs font-bold text-brand-primary hover:underline">Tư vấn chi tiết <i class="fa-solid fa-arrow-right ml-1"></i></a>
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article class="bg-slate-50 rounded-lg border border-slate-200 overflow-hidden hover:shadow-md transition flex flex-col justify-between">
                    <div>
                        <div class="aspect-[16/10] w-full overflow-hidden bg-slate-200">
                            <img src="https://drive.google.com/thumbnail?id=1FjkJWoKEGTKrEolABBL8b3P62PREo-4h&sz=w600"
                                 onerror="this.onerror=null;this.src='https://placehold.co/600x400/1e293b/f59e0b?text=Lang+Mo+Lan+Can+Da';"
                                 alt="Lư hương đá và lăng mộ đá Non Nước" class="w-full h-full object-cover">
                        </div>
                        <div class="p-3">
                            <span class="text-[11px] text-brand-primary font-semibold">Công trình tâm linh</span>
                            <h3 class="product-title-full mt-1">
                                Báo giá Lư hương đá, Lan can đá và Khu lăng mộ đá tự nhiên nguyên khối tại xưởng Non Nước
                            </h3>
                            <p class="text-xs text-slate-600 line-clamp-3">
                                Tổng hợp các mẫu lư hương đá chạm rồng chầu mặt nguyệt, bàn lễ đá, cây hương ngoài trời và khu lăng mộ đá hoa cương, đá xanh nguyên khối bền đẹp trăm năm.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 pt-1">
                        <a href="#form-bao-gia" class="text-xs font-bold text-brand-primary hover:underline">Tư vấn chi tiết <i class="fa-solid fa-arrow-right ml-1"></i></a>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- ==================== ĐƯA FANPAGE & ẢNH BẢN ĐỒ GOOGLE MAP RA NGOÀI TRANG CHỦ ==================== -->
    <section id="bando-fanpage" class="py-7">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-main">
                    <h2 class="section-title-text">KẾT NỐI FANPAGE & BẢN ĐỒ CHỈ ĐƯỜNG TỚI XƯỞNG HOÀNG HUY</h2>
                </div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5">
                <!-- Cột 1: Fanpage Facebook Chính Thức Ngoài Trang Chủ -->
                <div class="lg:col-span-5 bg-white p-4 rounded-lg border border-slate-200 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between pb-3 mb-3 border-b border-slate-200">
                            <div class="flex items-center gap-2">
                                <i class="fa-brands fa-facebook text-blue-600 text-xl"></i>
                                <h3 class="text-sm md:text-base font-bold text-brand-slate uppercase">Fanpage Chính Thức</h3>
                            </div>
                            <a href="https://www.facebook.com/profile.php?id=61557323583991" target="_blank" rel="noopener noreferrer" class="text-xs font-bold text-blue-600 hover:underline">
                                Mở Facebook <i class="fa-solid fa-up-right-from-square ml-1"></i>
                            </a>
                        </div>

                        <!-- Khung hiển thị trực quan Fanpage Cơ sở điêu khắc đá tự nhiên Hoàng Huy -->
                        <div class="rounded-lg overflow-hidden border border-slate-200 bg-slate-50">
                            <div class="h-28 bg-gradient-to-r from-slate-900 via-brand-primary to-amber-700 relative p-3 flex items-end">
                                <div class="flex items-center gap-3">
                                    <div class="w-14 h-14 rounded-full bg-brand-slate border-2 border-white flex items-center justify-center text-amber-400 font-black text-lg shadow">
                                        HH
                                    </div>
                                    <div class="text-white">
                                        <h4 class="font-bold text-sm leading-tight">Cơ sở điêu khắc đá tự nhiên Hoàng Huy</h4>
                                        <p class="text-[11px] text-amber-200">Đá mỹ nghệ cao cấp • Giá xưởng Non Nước</p>
                                    </div>
                                </div>
                            </div>
                            <div class="p-3.5 space-y-2 text-xs text-slate-700">
                                <p class="font-medium text-slate-800">
                                    <i class="fa-solid fa-circle-check text-blue-600 mr-1"></i> Chuyên cung cấp đá mỹ nghệ cao cấp: Tượng Phật – Đài phun nước – Linh vật, Lăng mộ – Lan can – Công trình đá.
                                </p>
                                <p><i class="fa-solid fa-gem text-brand-primary mr-1.5"></i> Đá tự nhiên – Chạm khắc tinh xảo – Giá xưởng</p>
                                <p><i class="fa-solid fa-location-dot text-brand-primary mr-1.5"></i> Đường Quán Khái 10, Khu chế tác Làng đá mỹ nghệ Non Nước – Ngũ Hành Sơn – Đà Nẵng</p>
                                <p><i class="fa-solid fa-phone text-brand-primary mr-1.5"></i> Hotline / Zalo: <strong>0938 534 827</strong></p>

                                <!-- Iframe Nhúng Fanpage Facebook -->
                                <div class="w-full overflow-hidden rounded border border-slate-200 bg-white pt-1">
                                    <iframe
                                        title="Fanpage Cơ sở điêu khắc đá tự nhiên Hoàng Huy"
                                        src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fprofile.php%3Fid%3D61557323583991&tabs=timeline&width=340&height=180&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true"
                                        width="100%" height="180" style="border:none;overflow:hidden" scrolling="no" frameborder="0" allowfullscreen="true" allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                                    </iframe>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="mt-3 pt-3 border-t border-slate-100 flex flex-wrap gap-2">
                        <a href="https://www.facebook.com/profile.php?id=61557323583991" target="_blank" rel="noopener noreferrer" class="flex-1 bg-blue-600 hover:bg-blue-700 text-white text-center text-xs font-bold py-2.5 px-3 rounded transition">
                            <i class="fa-brands fa-facebook-f mr-1.5"></i> Theo Dõi Fanpage Hoàng Huy
                        </a>
                        <a href="https://zalo.me/0938534827" target="_blank" rel="noopener noreferrer" class="flex-1 bg-brand-primary hover:bg-brand-dark text-white text-center text-xs font-bold py-2.5 px-3 rounded transition">
                            <i class="fa-solid fa-comment-dots mr-1.5"></i> Nhắn Tin Zalo
                        </a>
                    </div>
                </div>

                <!-- Cột 2: Ảnh & Bản Đồ Google Map Ngoài Trang Chủ -->
                <div class="lg:col-span-7 bg-white p-4 rounded-lg border border-slate-200 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="flex flex-wrap items-center justify-between gap-2 pb-3 mb-3 border-b border-slate-200">
                            <div class="flex items-center gap-2">
                                <i class="fa-solid fa-map-location-dot text-red-600 text-xl"></i>
                                <div>
                                    <h3 class="text-sm md:text-base font-bold text-brand-slate uppercase">Bản Đồ Google Map Xưởng Chế Tác</h3>
                                    <p class="text-xs text-slate-500">Đường Quán Khái 10, Khu chế tác Làng đá mỹ nghệ Non Nước – Ngũ Hành Sơn – Đà Nẵng</p>
                                </div>
                            </div>
                            <a href="https://www.google.com/maps/search/?api=1&query=Đường+Quán+Khái+10,+Khu+chế+tác+Làng+đá+mỹ+nghệ+Non+Nước,+Ngũ+Hành+Sơn,+Đà+Nẵng" target="_blank" rel="noopener noreferrer" class="text-xs font-bold bg-red-600 hover:bg-red-700 text-white px-3 py-1.5 rounded transition">
                                <i class="fa-solid fa-diamond-turn-right mr-1"></i> Chỉ Đường Google Maps
                            </a>
                        </div>

                        <!-- Bản đồ Google Maps trực tiếp ngoài trang chủ -->
                        <div class="w-full h-[310px] md:h-[340px] rounded-lg overflow-hidden border border-slate-300 relative bg-slate-100">
                            <iframe
                                title="Bản đồ Google Maps Cơ sở điêu khắc đá tự nhiên Hoàng Huy - Đường Quán Khái 10, Non Nước, Đà Nẵng"
                                src="https://maps.google.com/maps?q=%C4%90%C6%B0%E1%BB%9Dng%20Qu%C3%A1n%20Kh%C3%A1i%2010,%20L%C3%A0ng%20%C4%91%C3%A1%20m%E1%BB%B9%20ngh%E1%BB%87%20Non%20N%C6%B0%E1%BB%9Bc,%20Ng%C5%A9%20H%C3%A0nh%20S%C6%A1n,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                                width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade">
                            </iframe>
                        </div>
                    </div>

                    <div class="mt-3 pt-3 border-t border-slate-100 flex flex-wrap items-center justify-between gap-2 text-xs text-slate-600">
                        <div>
                            <i class="fa-solid fa-location-crosshairs text-brand-primary mr-1"></i>
                            <strong>Vị trí xưởng:</strong> Đường Quán Khái 10, Làng đá Non Nước, Quận Ngũ Hành Sơn, TP. Đà Nẵng
                        </div>
                        <div class="font-bold text-brand-primary">
                            Đón khách tham quan xưởng 24/7 • ĐT: 0938 534 827
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== FOOTER CHUẨN FLATSOME (GIỐNG CẤU TRÚC DANGUYENCONG.COM) ==================== -->
    <footer class="bg-brand-slate text-slate-300 pt-10 pb-6 border-t-4 border-brand-primary text-xs md:text-sm">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6 pb-8 border-b border-slate-700">
                <!-- Cột 1: Thông tin Cơ sở Hoàng Huy -->
                <div class="space-y-2.5">
                    <h3 class="text-white font-bold text-sm uppercase tracking-wide border-b border-amber-500/40 pb-2">
                        CƠ SỞ ĐIÊU KHẮC ĐÁ TỰ NHIÊN HOÀNG HUY
                    </h3>
                    <p class="text-slate-300 text-xs leading-relaxed">
                        Chuyên cung cấp đá mỹ nghệ cao cấp: Tượng Phật – Đài phun nước – Linh vật, Lăng mộ – Lan can – Công trình đá. Đá tự nhiên nguyên khối – Chạm khắc tinh xảo – Giá xưởng.
                    </p>
                    <ul class="space-y-1.5 text-xs">
                        <li><i class="fa-solid fa-location-dot text-amber-400 mr-2"></i><strong>Địa chỉ:</strong> Đường Quán Khái 10, Khu chế tác Làng đá mỹ nghệ Non Nước – Ngũ Hành Sơn – Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone text-amber-400 mr-2"></i><strong>Điện thoại / Zalo:</strong> <a href="tel:0938534827" class="text-amber-300 font-bold">0938 534 827</a></li>
                        <li><i class="fa-solid fa-globe text-amber-400 mr-2"></i><strong>Website:</strong> <a href="https://hoanghuy.com" class="text-amber-300">https://hoanghuy.com</a></li>
                        <li><i class="fa-brands fa-facebook text-amber-400 mr-2"></i><strong>Fanpage:</strong> <a href="https://www.facebook.com/profile.php?id=61557323583991" target="_blank" rel="noopener noreferrer" class="text-amber-300 hover:underline">Đá Tự Nhiên Hoàng Huy</a></li>
                    </ul>
                </div>

                <!-- Cột 2: Tượng Phật & Tượng Công Giáo -->
                <div class="space-y-2">
                    <h3 class="text-white font-bold text-sm uppercase tracking-wide border-b border-amber-500/40 pb-2">
                        TƯỢNG PHẬT & CÔNG GIÁO
                    </h3>
                    <ul class="space-y-1.5 text-xs">
                        <li><a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-phat')" class="hover:text-amber-400"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Tượng Phật Quan Âm Bằng Đá</a></li>
                        <li><a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-phat')" class="hover:text-amber-400"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Tượng Phật Di Lặc Phong Thủy</a></li>
                        <li><a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-phat')" class="hover:text-amber-400"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Tượng Phật Thích Ca - A Di Đà</a></li>
                        <li><a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-phat')" class="hover:text-amber-400"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Tượng Địa Tạng - Nghìn Mắt Nghìn Tay</a></li>
                        <li><a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-cong-giao')" class="hover:text-amber-400"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Tượng Đức Mẹ Ban Ơn Đá Cẩm Thạch</a></li>
                        <li><a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-cong-giao')" class="hover:text-amber-400"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Tượng Chúa Giêsu - Thánh Giuse</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Linh Vật, Đồ Thờ & Công Trình Đá -->
                <div class="space-y-2">
                    <h3 class="text-white font-bold text-sm uppercase tracking-wide border-b border-amber-500/40 pb-2">
                        LINH VẬT & CÔNG TRÌNH ĐÁ
                    </h3>
                    <ul class="space-y-1.5 text-xs">
                        <li><a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-dong-vat')" class="hover:text-amber-400"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Tượng Kỳ Lân - Sư Tử - Tỳ Hưu Đá</a></li>
                        <li><a href="#khu-vuc-san-pham" onclick="filterByCategory('tuong-dong-vat')" class="hover:text-amber-400"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Tượng Rồng Đá - Cá Chép Hóa Rồng</a></li>
                        <li><a href="#khu-vuc-san-pham" onclick="filterByCategory('da-kien-truc')" class="hover:text-amber-400"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Đài Phun Nước Bằng Đá Tự Nhiên</a></li>
                        <li><a href="#khu-vuc-san-pham" onclick="filterByCategory('da-kien-truc')" class="hover:text-amber-400"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Lăng Mộ Đá - Lan Can Đá Chạm Rồng</a></li>
                        <li><a href="#khu-vuc-san-pham" onclick="filterByCategory('do-tho-da')" class="hover:text-amber-400"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Lư Hương Đá - Cây Hương - Bàn Lễ Đá</a></li>
                        <li><a href="#khu-vuc-san-pham" onclick="filterByCategory('da-kien-truc')" class="hover:text-amber-400"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Bảng Hiệu Đá - Đá Kê Chân Cột</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Hỗ Trợ Khách Hàng -->
                <div class="space-y-2">
                    <h3 class="text-white font-bold text-sm uppercase tracking-wide border-b border-amber-500/40 pb-2">
                        CHÍNH SÁCH & CAM KẾT
                    </h3>
                    <ul class="space-y-1.5 text-xs">
                        <li><a href="#gioi-thieu" class="hover:text-amber-400"><i class="fa-solid fa-check text-amber-400 mr-1.5"></i>Giới thiệu Cơ sở Đá Hoàng Huy</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-amber-400"><i class="fa-solid fa-check text-amber-400 mr-1.5"></i>Chính sách bảo hành đá trọn đời</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-amber-400"><i class="fa-solid fa-check text-amber-400 mr-1.5"></i>Vận chuyển & lắp đặt toàn quốc</a></li>
                        <li><a href="#bando-fanpage" class="hover:text-amber-400"><i class="fa-solid fa-check text-amber-400 mr-1.5"></i>Chỉ đường tới xưởng Quán Khái 10</a></li>
                    </ul>
                    <div class="pt-2">
                        <div class="p-3 rounded bg-slate-800 border border-slate-700 text-xs">
                            <p class="text-amber-400 font-bold uppercase mb-1">Tư Vấn Trực Tiếp Tại Xưởng</p>
                            <p class="text-white font-black text-base">0938 534 827</p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400">
                <p>Copyright 2026 © <strong>Cơ Sở Điêu Khắc Đá Tự Nhiên Hoàng Huy (hoanghuy.com)</strong>. All rights reserved.</p>
                <p>Đường Quán Khái 10, Làng đá mỹ nghệ Non Nước, Ngũ Hành Sơn, Đà Nẵng</p>
            </div>
        </div>
    </footer>

    <!-- ==================== CÁC NÚT LIÊN HỆ NỔI BẬT ZALO, FACEBOOK, HOTLINE TƯƠNG THÍCH MÁY TÍNH & ĐIỆN THOẠI ==================== -->
    <div class="fixed left-3 bottom-4 z-40 flex flex-col gap-2.5">
        <!-- Nút Zalo nổi bật -->
        <a href="https://zalo.me/0938534827" target="_blank" rel="noopener noreferrer"
           class="flex items-center gap-2 bg-blue-600 hover:bg-blue-700 text-white rounded-full p-2.5 md:px-3.5 md:py-2 shadow-lg transition">
            <span class="w-6 h-6 rounded-full bg-white text-blue-600 font-black text-[11px] flex items-center justify-center shrink-0">Zalo</span>
            <span class="hidden md:inline text-xs font-bold pr-1">Chat Zalo: 0938.534.827</span>
        </a>

        <!-- Nút Facebook Fanpage nổi bật -->
        <a href="https://www.facebook.com/profile.php?id=61557323583991" target="_blank" rel="noopener noreferrer"
           class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-800 text-white rounded-full p-2.5 md:px-3.5 md:py-2 shadow-lg transition">
            <span class="w-6 h-6 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0">
                <i class="fa-brands fa-facebook-f text-xs"></i>
            </span>
            <span class="hidden md:inline text-xs font-bold pr-1">Fanpage Hoàng Huy</span>
        </a>

        <!-- Nút Hotline nổi bật -->
        <a href="tel:0938534827"
           class="pulse-btn flex items-center gap-2 bg-brand-primary hover:bg-brand-dark text-white rounded-full p-2.5 md:px-4 md:py-2.5 shadow-xl transition">
            <span class="w-6 h-6 rounded-full bg-white text-brand-primary flex items-center justify-center shrink-0">
                <i class="fa-solid fa-phone-volume text-xs"></i>
            </span>
            <span class="text-xs font-extrabold pr-1">0938 534 827</span>
        </a>
    </div>

    <!-- ==================== HỘP THOẠI XEM CHI TIẾT SẢN PHẨM & THÔNG BÁO (THAY THẾ HOÀN TOÀN ALERT) ==================== -->
    <div id="customModal" class="fixed inset-0 bg-black/65 z-50 hidden items-center justify-center p-3">
        <div class="bg-white rounded-lg max-w-lg w-full overflow-hidden shadow-2xl border border-slate-200">
            <div class="bg-brand-primary text-white px-4 py-3 flex items-center justify-between">
                <h3 id="modalTitle" class="font-bold text-sm uppercase">Thông tin sản phẩm tại xưởng Hoàng Huy</h3>
                <button onclick="closeCustomModal()" class="text-white hover:text-amber-200 text-lg leading-none">&times;</button>
            </div>
            <div id="modalBody" class="p-4 text-xs md:text-sm text-slate-700 space-y-3 max-h-[80vh] overflow-y-auto"></div>
        </div>
    </div>

    <!-- ==================== JAVASCRIPT QUẢN LÝ 16 ẢNH SẢN PHẨM GOOGLE DRIVE, SLIDER & BỘ LỌC ==================== -->
    <script>
        /* Danh sách 16 sản phẩm thực tế từ 16 file Google Drive do khách hàng cung cấp,
           được phân vào đúng các danh mục của web mẫu danguyencong.com và Hoàng Huy */
        const PRODUCTS_DATA = [
            {
                id: 1,
                driveId: '1N-y5XXiHtBRzJlG5_-3BjvNmrdquT9p2',
                name: 'Tượng Phật Quan Âm Bồ Tát đứng đài sen đá cẩm thạch trắng tự nhiên nguyên khối',
                category: 'tuong-phat',
                categoryLabel: 'Tượng Phật Đá',
                oldPrice: '22.000.000₫',
                newPrice: '18.500.000₫',
                discount: '-16%'
            },
            {
                id: 2,
                driveId: '12EdHqcjosKt_y6AMLWuHwH3rRck5rxse',
                name: 'Đài phun nước bằng đá cẩm thạch tự nhiên 3 tầng chạm hoa sen cao cấp',
                category: 'da-kien-truc',
                categoryLabel: 'Đá Trang Trí Kiến Trúc',
                oldPrice: '35.000.000₫',
                newPrice: '28.000.000₫',
                discount: '-20%'
            },
            {
                id: 3,
                driveId: '1_enlCf1hPn-9vF0mqmgzwsE4E35lcHIX',
                name: 'Tượng Kỳ Lân Nghê đá phong thủy trấn trạch đá cẩm thạch nguyên khối (Cặp)',
                category: 'tuong-dong-vat',
                categoryLabel: 'Tượng Động Vật',
                oldPrice: '24.000.000₫',
                newPrice: '19.500.000₫',
                discount: '-19%'
            },
            {
                id: 4,
                driveId: '1Etj-_9HDOdkysFJNKetZ52YNAyEX1eu-',
                name: 'Tượng Phật Di Lặc kéo bao tiền chúc phúc đá tự nhiên nguyên khối tại xưởng',
                category: 'tuong-phat',
                categoryLabel: 'Tượng Phật Đá',
                oldPrice: '19.000.000₫',
                newPrice: '15.800.000₫',
                discount: '-17%'
            },
            {
                id: 5,
                driveId: '1hSmK3rXsUikb8MqBd4haZ6bgUMHO8_Pc',
                name: 'Tượng Đức Mẹ Ban Ơn bằng đá cẩm thạch trắng tự nhiên nguyên khối chạm khắc tinh xảo',
                category: 'tuong-cong-giao',
                categoryLabel: 'Tượng Công Giáo',
                oldPrice: '21.000.000₫',
                newPrice: '17.500.000₫',
                discount: '-17%'
            },
            {
                id: 6,
                driveId: '1wx0-xXrwEa0azmS9vzUEPLt_y8yFFnOF',
                name: 'Tượng Sư Tử đá phong thủy canh cổng biệt thự đá tự nhiên nguyên khối (Cặp)',
                category: 'tuong-dong-vat',
                categoryLabel: 'Tượng Động Vật',
                oldPrice: '28.000.000₫',
                newPrice: '23.500.000₫',
                discount: '-16%'
            },
            {
                id: 7,
                driveId: '1ISDjvu4NO6WtUm4r-MHlt7yC1RVqTx4a',
                name: 'Tượng Phật Thích Ca Mâu Ni ngồi tòa sen đá trắng Non Nước nguyên khối',
                category: 'tuong-phat',
                categoryLabel: 'Tượng Phật Đá',
                oldPrice: '26.000.000₫',
                newPrice: '21.500.000₫',
                discount: '-17%'
            },
            {
                id: 8,
                driveId: '1FjkJWoKEGTKrEolABBL8b3P62PREo-4h',
                name: 'Lư hương đá cẩm thạch tự nhiên chạm song long chầu nguyệt ngoài trời',
                category: 'do-tho-da',
                categoryLabel: 'Đồ Thờ Đá',
                oldPrice: '16.500.000₫',
                newPrice: '13.500.000₫',
                discount: '-18%'
            },
            {
                id: 9,
                driveId: '1A44FOPRsylr8qTPu3Nl_T3UPMYQ7oY9R',
                name: 'Tượng Tỳ Hưu đá phong thủy chiêu tài giữ lộc đá tự nhiên nguyên khối (Cặp)',
                category: 'tuong-dong-vat',
                categoryLabel: 'Tượng Động Vật',
                oldPrice: '18.000.000₫',
                newPrice: '14.900.000₫',
                discount: '-17%'
            },
            {
                id: 10,
                driveId: '1JBkClNq1t_XIu7xMUy_akyzscUyw-1Vo',
                name: 'Tượng Phật A Di Đà bằng đá tự nhiên nguyên khối chạm khắc tinh xảo',
                category: 'tuong-phat',
                categoryLabel: 'Tượng Phật Đá',
                oldPrice: '25.000.000₫',
                newPrice: '20.500.000₫',
                discount: '-18%'
            },
            {
                id: 11,
                driveId: '1Jw3kfSZSnIjn9hvejPcV3DozSAwuhoWW',
                name: 'Cây hương đá thờ Thiên ngoài trời đá cẩm thạch tự nhiên nguyên khối',
                category: 'do-tho-da',
                categoryLabel: 'Đồ Thờ Đá',
                oldPrice: '14.500.000₫',
                newPrice: '11.900.000₫',
                discount: '-18%'
            },
            {
                id: 12,
                driveId: '104LxoMllxAVN9KbtmEHDQTfutfTvxqER',
                name: 'Lăng mộ đá tự nhiên nguyên khối chạm tứ linh hoa văn truyền thống cao cấp',
                category: 'da-kien-truc',
                categoryLabel: 'Đá Trang Trí Kiến Trúc',
                oldPrice: '45.000.000₫',
                newPrice: '38.000.000₫',
                discount: '-15%'
            },
            {
                id: 13,
                driveId: '1Ng1N8t7-6-O2zlMZ6KPOTo8RMBlE7PDR',
                name: 'Tượng Chúa Kito Vua và Đức Mẹ đá cẩm thạch tự nhiên nguyên khối xuất khẩu',
                category: 'tuong-cong-giao',
                categoryLabel: 'Tượng Công Giáo',
                oldPrice: '23.000.000₫',
                newPrice: '19.200.000₫',
                discount: '-16%'
            },
            {
                id: 14,
                driveId: '19jbWQf33X14CXxuaC3ivGwPxGW9Yldhw',
                name: 'Tượng Cá Chép Hóa Rồng phun nước phong thủy đá tự nhiên nguyên khối',
                category: 'tuong-dong-vat',
                categoryLabel: 'Tượng Động Vật',
                oldPrice: '20.000.000₫',
                newPrice: '16.500.000₫',
                discount: '-17%'
            },
            {
                id: 15,
                driveId: '1ayS6Qj6yH5YovdU7MBHBdmUpgrN0R6nE',
                name: 'Lan can đá tự nhiên chạm hoa sen & Tượng đá nghệ thuật trang trí công trình',
                category: 'sp-khac',
                categoryLabel: 'SP Khác & Công Trình',
                oldPrice: '15.000.000₫',
                newPrice: '12.500.000₫',
                discount: '-17%'
            },
            {
                id: 16,
                driveId: '1Z8dA5CIIW54MhsZx2OZlhnrAp303nXiK',
                name: 'Bàn lễ đá - Bàn thờ đá tự nhiên ngoài trời chạm rồng phượng tinh xảo',
                category: 'do-tho-da',
                categoryLabel: 'Đồ Thờ Đá',
                oldPrice: '19.500.000₫',
                newPrice: '16.000.000₫',
                discount: '-18%'
            }
        ];

        /* Danh sách các phân khu danh mục sản phẩm hiển thị ngoài trang chủ giống chuẩn danguyencong.com */
        const CATEGORY_SECTIONS = [
            { key: 'tuong-phat', title: 'TƯỢNG PHẬT ĐÁ TỰ NHIÊN' },
            { key: 'tuong-cong-giao', title: 'TƯỢNG CÔNG GIÁO BẰNG ĐÁ' },
            { key: 'tuong-dong-vat', title: 'TƯỢNG ĐỘNG VẬT - LINH VẬT PHONG THỦY' },
            { key: 'do-tho-da', title: 'ĐỒ THỜ ĐÁ MỸ NGHỆ' },
            { key: 'da-kien-truc', title: 'ĐÁ TRANG TRÍ KIẾN TRÚC - ĐÀI PHUN NƯỚC - LĂNG MỘ' },
            { key: 'sp-khac', title: 'LAN CAN ĐÁ & SẢN PHẨM ĐÁ MỸ NGHỆ KHÁC' }
        ];

        /* Tạo HTML cho từng thẻ sản phẩm chuẩn Flatsome:
           - Chia 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4)
           - Chỉ để duy nhất vòng tròn % giảm giá ở góc trên bên trái (không để nhãn dán phụ)
           - Tên sản phẩm hiển thị đầy đủ, không bị cắt chữ hay tràn ra ngoài */
        function createProductCardHTML(product) {
            const imgUrl = `https://drive.google.com/thumbnail?id=${product.driveId}&sz=w800`;
            const fallbackUrl = `https://placehold.co/600x600/1e293b/f59e0b?text=Da+Tu+Nhien+Hoang+Huy`;

            return `
                <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-primary transition flex flex-col justify-between">
                    <div>
                        <div class="relative aspect-square w-full overflow-hidden bg-slate-100 group cursor-pointer" onclick="openProductModal(${product.id})">
                            <span class="flatsome-sale-badge">${product.discount}</span>
                            <img src="${imgUrl}"
                                 onerror="this.onerror=null;this.src='${fallbackUrl}';"
                                 alt="${product.name}"
                                 loading="lazy"
                                 class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 md:p-3">
                            <div class="text-[11px] text-slate-500 mb-1">${product.categoryLabel}</div>
                            <h3 class="product-title-full cursor-pointer hover:text-brand-primary transition" onclick="openProductModal(${product.id})">
                                ${product.name}
                            </h3>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 md:px-3 md:pb-3 pt-1 border-t border-slate-100">
                        <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                            <span class="text-[11px] md:text-xs text-slate-400 line-through">${product.oldPrice}</span>
                            <span class="text-xs md:text-sm font-extrabold text-red-600">${product.newPrice}</span>
                        </div>
                        <div class="grid grid-cols-2 gap-1.5">
                            <button onclick="openProductModal(${product.id})" class="w-full bg-slate-100 hover:bg-slate-200 text-slate-700 font-bold text-[11px] py-1.5 px-2 rounded transition text-center">
                                Chi tiết
                            </button>
                            <a href="https://zalo.me/0938534827" target="_blank" rel="noopener noreferrer" class="w-full bg-brand-primary hover:bg-brand-dark text-white font-bold text-[11px] py-1.5 px-2 rounded transition text-center">
                                Đặt mua
                            </a>
                        </div>
                    </div>
                </div>
            `;
        }

        /* Hiển thị các phân khu sản phẩm ngoài trang chủ */
        function renderProducts(selectedCategory = 'all', searchKeyword = '') {
            const container = document.getElementById('allProductSections');
            const statusText = document.getElementById('filterStatusText');
            const normalizedQuery = searchKeyword.trim().toLowerCase();

            // Lọc theo từ khóa tìm kiếm nếu có
            if (normalizedQuery.length > 0) {
                const matched = PRODUCTS_DATA.filter(item =>
                    item.name.toLowerCase().includes(normalizedQuery) ||
                    item.categoryLabel.toLowerCase().includes(normalizedQuery)
                );
                statusText.textContent = `Tìm thấy ${matched.length} sản phẩm phù hợp với "${searchKeyword}"`;

                if (matched.length === 0) {
                    container.innerHTML = `
                        <div class="bg-white p-6 rounded-lg border border-slate-200 text-center">
                            <p class="text-sm font-bold text-slate-700 mb-1">Không tìm thấy sản phẩm phù hợp với từ khóa "${searchKeyword}"</p>
                            <p class="text-xs text-slate-500 mb-3">Quý khách vui lòng thử từ khóa khác hoặc liên hệ Zalo 0938 534 827 để nhận mẫu theo yêu cầu.</p>
                            <button onclick="filterByCategory('all')" class="bg-brand-primary text-white text-xs font-bold px-4 py-2 rounded">Xem tất cả 16 sản phẩm</button>
                        </div>
                    `;
                    return;
                }

                container.innerHTML = `
                    <div>
                        <div class="section-title-container">
                            <div class="section-title-main">
                                <h2 class="section-title-text">KẾT QUẢ TÌM KIẾM SẢN PHẨM (${matched.length})</h2>
                            </div>
                        </div>
                        <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-4 gap-2.5 md:gap-4">
                            ${matched.map(createProductCardHTML).join('')}
                        </div>
                    </div>
                `;
                return;
            }

            // Hiển thị theo danh mục được chọn
            if (selectedCategory !== 'all') {
                const sectionInfo = CATEGORY_SECTIONS.find(s => s.key === selectedCategory);
                const filteredList = PRODUCTS_DATA.filter(item => item.category === selectedCategory);
                statusText.textContent = `Đang hiển thị ${filteredList.length} sản phẩm trong danh mục ${sectionInfo ? sectionInfo.title : ''}`;

                container.innerHTML = `
                    <div>
                        <div class="section-title-container">
                            <div class="section-title-main">
                                <h2 class="section-title-text">${sectionInfo ? sectionInfo.title : 'SẢN PHẨM ĐÁ MỸ NGHỆ'}</h2>
                            </div>
                        </div>
                        <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-4 gap-2.5 md:gap-4">
                            ${filteredList.map(createProductCardHTML).join('')}
                        </div>
                    </div>
                `;
                return;
            }

            // Mặc định: Hiển thị khối "SẢN PHẨM NỔI BẬT TẠI XƯỞNG" (Đầy đủ 16 ảnh thực tế) + Từng danh mục giống danguyencong.com
            statusText.textContent = 'Hiển thị đầy đủ 16 tác phẩm thực tế tại xưởng Hoàng Huy';

            let html = `
                <div>
                    <div class="section-title-container">
                        <div class="section-title-main">
                            <h2 class="section-title-text">SẢN PHẨM THỰC TẾ MỚI NHẤT TẠI XƯỞNG HOÀNG HUY</h2>
                        </div>
                    </div>
                    <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-4 gap-2.5 md:gap-4">
                        ${PRODUCTS_DATA.map(createProductCardHTML).join('')}
                    </div>
                </div>
            `;

            CATEGORY_SECTIONS.forEach(sec => {
                const items = PRODUCTS_DATA.filter(p => p.category === sec.key);
                if (items.length > 0) {
                    html += `
                        <div>
                            <div class="section-title-container">
                                <div class="section-title-main">
                                    <h2 class="section-title-text">${sec.title}</h2>
                                </div>
                            </div>
                            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-4 gap-2.5 md:gap-4">
                                ${items.map(createProductCardHTML).join('')}
                            </div>
                        </div>
                    `;
                }
            });

            container.innerHTML = html;
        }

        /* Lọc sản phẩm theo danh mục và cập nhật nút đang chọn */
        function filterByCategory(categoryKey) {
            const desktopInput = document.getElementById('desktopSearchInput');
            const mobileInput = document.getElementById('mobileSearchInput');
            if (desktopInput) desktopInput.value = '';
            if (mobileInput) mobileInput.value = '';

            const buttons = document.querySelectorAll('.cat-filter-btn');
            buttons.forEach(btn => {
                if (btn.getAttribute('data-cat') === categoryKey) {
                    btn.className = 'cat-filter-btn bg-brand-primary text-white text-xs font-bold px-3 py-1.5 rounded transition whitespace-nowrap';
                } else {
                    btn.className = 'cat-filter-btn bg-slate-100 hover:bg-amber-100 text-slate-700 text-xs font-semibold px-3 py-1.5 rounded transition whitespace-nowrap';
                }
            });

            renderProducts(categoryKey, '');
        }

        /* Tìm kiếm sản phẩm trực tiếp */
        function handleSearchProduct(keyword) {
            renderProducts('all', keyword);
        }

        /* Xem chi tiết sản phẩm trong hộp thoại (Modal) */
        function openProductModal(productId) {
            const product = PRODUCTS_DATA.find(p => p.id === productId);
            if (!product) return;

            const modal = document.getElementById('customModal');
            const modalTitle = document.getElementById('modalTitle');
            const modalBody = document.getElementById('modalBody');
            const imgUrl = `https://drive.google.com/thumbnail?id=${product.driveId}&sz=w1000`;

            modalTitle.textContent = product.categoryLabel;
            modalBody.innerHTML = `
                <div class="relative aspect-square w-full max-h-72 overflow-hidden rounded border border-slate-200 bg-slate-100">
                    <span class="flatsome-sale-badge">${product.discount}</span>
                    <img src="${imgUrl}"
                         onerror="this.onerror=null;this.src='https://placehold.co/600x600/1e293b/f59e0b?text=Da+Tu+Nhien+Hoang+Huy';"
                         alt="${product.name}" class="w-full h-full object-contain">
                </div>
                <h4 class="font-bold text-sm md:text-base text-brand-slate">${product.name}</h4>
                <div class="flex items-center gap-2">
                    <span class="text-xs text-slate-400 line-through">${product.oldPrice}</span>
                    <span class="text-base font-black text-red-600">${product.newPrice}</span>
                    <span class="text-xs bg-amber-100 text-brand-primary font-bold px-2 py-0.5 rounded">Giá gốc tại xưởng</span>
                </div>
                <ul class="text-xs text-slate-600 space-y-1 bg-slate-50 p-3 rounded border border-slate-200">
                    <li><i class="fa-solid fa-check text-brand-primary mr-1.5"></i><strong>Chất liệu:</strong> Đá tự nhiên nguyên khối 100% tuyển chọn</li>
                    <li><i class="fa-solid fa-check text-brand-primary mr-1.5"></i><strong>Chế tác:</strong> Chạm khắc tinh xảo tại xưởng Đá Tự Nhiên Hoàng Huy</li>
                    <li><i class="fa-solid fa-check text-brand-primary mr-1.5"></i><strong>Địa chỉ xưởng:</strong> Đường Quán Khái 10, Khu chế tác Làng đá mỹ nghệ Non Nước – Ngũ Hành Sơn – Đà Nẵng</li>
                    <li><i class="fa-solid fa-check text-brand-primary mr-1.5"></i><strong>Vận chuyển:</strong> Giao hàng và lắp đặt tận nơi trên toàn quốc</li>
                </ul>
                <div class="flex flex-wrap gap-2 pt-2">
                    <a href="tel:0938534827" class="flex-1 bg-brand-primary hover:bg-brand-dark text-white text-center font-bold text-xs py-2.5 px-3 rounded">
                        <i class="fa-solid fa-phone mr-1"></i> Gọi 0938 534 827
                    </a>
                    <a href="https://zalo.me/0938534827" target="_blank" rel="noopener noreferrer" class="flex-1 bg-blue-600 hover:bg-blue-700 text-white text-center font-bold text-xs py-2.5 px-3 rounded">
                        <i class="fa-solid fa-comment-dots mr-1"></i> Nhắn Zalo Báo Giá
                    </a>
                </div>
            `;

            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeCustomModal() {
            const modal = document.getElementById('customModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        /* Điều khiển 2 ảnh Banner tự trượt kích thước bằng nhau */
        let currentBannerIndex = 0;
        let bannerInterval = null;

        function showBannerSlide(index) {
            const slide0 = document.getElementById('bannerSlide0');
            const slide1 = document.getElementById('bannerSlide1');
            const dot0 = document.getElementById('bannerDot0');
            const dot1 = document.getElementById('bannerDot1');

            currentBannerIndex = (index + 2) % 2;
            if (currentBannerIndex === 0) {
                slide0.classList.remove('hidden');
                slide0.classList.add('block');
                slide1.classList.remove('block');
                slide1.classList.add('hidden');
                dot0.className = 'w-2.5 h-2.5 rounded-full bg-amber-400 transition';
                dot1.className = 'w-2.5 h-2.5 rounded-full bg-white/50 transition';
            } else {
                slide1.classList.remove('hidden');
                slide1.classList.add('block');
                slide0.classList.remove('block');
                slide0.classList.add('hidden');
                dot1.className = 'w-2.5 h-2.5 rounded-full bg-amber-400 transition';
                dot0.className = 'w-2.5 h-2.5 rounded-full bg-white/50 transition';
            }
        }

        function changeBannerSlide(step) {
            showBannerSlide(currentBannerIndex + step);
            resetBannerTimer();
        }

        function goToBannerSlide(index) {
            showBannerSlide(index);
            resetBannerTimer();
        }

        function resetBannerTimer() {
            if (bannerInterval) clearInterval(bannerInterval);
            bannerInterval = setInterval(() => {
                showBannerSlide(currentBannerIndex + 1);
            }, 5000);
        }

        /* Đóng / Mở Menu trên điện thoại */
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobileMenuDrawer');
            drawer.classList.toggle('hidden');
        }

        /* Đóng / Mở Câu hỏi thường gặp (Accordion FAQ) */
        function toggleFaq(index) {
            const content = document.getElementById('faqContent' + index);
            const icon = document.getElementById('faqIcon' + index);
            if (!content || !icon) return;

            const isHidden = content.classList.contains('hidden');
            if (isHidden) {
                content.classList.remove('hidden');
                icon.className = 'fa-solid fa-minus text-brand-primary text-xs';
            } else {
                content.classList.add('hidden');
                icon.className = 'fa-solid fa-plus text-brand-primary text-xs';
            }
        }

        /* Xử lý gửi Form Yêu cầu tư vấn & Báo giá tại trang chủ */
        function submitQuoteForm(event) {
            event.preventDefault();
            const name = document.getElementById('qName').value.trim();
            const phone = document.getElementById('qPhone').value.trim();
            const category = document.getElementById('qCategory').value;
            const size = document.getElementById('qSize').value.trim() || 'Tư vấn theo phong thủy';
            const note = document.getElementById('qNote').value.trim() || 'Báo giá gốc tại xưởng';

            const modal = document.getElementById('customModal');
            const modalTitle = document.getElementById('modalTitle');
            const modalBody = document.getElementById('modalBody');

            modalTitle.textContent = 'Đã ghi nhận yêu cầu báo giá';
            modalBody.innerHTML = `
                <div class="p-3 rounded bg-amber-50 border border-amber-200 text-slate-800 space-y-1.5">
                    <p class="font-bold text-brand-primary text-sm"><i class="fa-solid fa-circle-check mr-1.5"></i>Cảm ơn quý khách ${name}!</p>
                    <p class="text-xs">Xưởng <strong>Đá Tự Nhiên Hoàng Huy (hoanghuy.com)</strong> đã nhận thông tin yêu cầu báo giá của quý khách:</p>
                    <ul class="text-xs space-y-1 pt-1">
                        <li>• <strong>Số điện thoại / Zalo:</strong> ${phone}</li>
                        <li>• <strong>Hạng mục:</strong> ${category}</li>
                        <li>• <strong>Kích thước / Chất liệu:</strong> ${size}</li>
                        <li>• <strong>Ghi chú:</strong> ${note}</li>
                    </ul>
                </div>
                <p class="text-xs text-slate-600">Nghệ nhân của xưởng sẽ liên hệ lại qua số <strong>${phone}</strong> trong ít phút tới, hoặc quý khách có thể bấm kết nối Zalo trực tiếp bên dưới:</p>
                <div class="flex gap-2 pt-1">
                    <a href="https://zalo.me/0938534827" target="_blank" rel="noopener noreferrer" class="flex-1 bg-blue-600 hover:bg-blue-700 text-white text-center font-bold text-xs py-2.5 px-3 rounded">
                        Chat Zalo: 0938 534 827
                    </a>
                    <button onclick="closeCustomModal()" class="bg-slate-200 hover:bg-slate-300 text-slate-800 font-bold text-xs py-2.5 px-4 rounded">
                        Đóng
                    </button>
                </div>
            `;

            modal.classList.remove('hidden');
            modal.classList.add('flex');
            document.getElementById('quoteForm').reset();
        }

        /* Khởi chạy trang web khi tải xong */
        window.addEventListener('DOMContentLoaded', () => {
            renderProducts('all', '');
            resetBannerTimer();
        });
    </script>
</body>
</html>
