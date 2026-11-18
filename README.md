<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>CÔNG TY CỔ PHẦN XÂY DỰNG VÀ THƯƠNG MẠI T-HOME | thome.com</title>
    <meta name="description" content="CÔNG TY CỔ PHẦN XÂY DỰNG VÀ THƯƠNG MẠI T-HOME (thome.com) - Chuyên Thiết kế Kiến trúc, Nội thất, Thi công phần thô, Thi công hoàn thiện, Xây nhà trọn gói uy tín tại Đà Nẵng. Địa chỉ: 07 - 09 Võ Quảng, Phường Hòa Xuân, TP Đà Nẵng. Hotline: 0905.436.426">
    <meta name="keywords" content="T-HOME, thome.com, Công ty Cổ phần Xây dựng và Thương mại T-HOME, thiết kế thi công Đà Nẵng, xây nhà trọn gói Đà Nẵng, 07 - 09 Võ Quảng Hòa Xuân Đà Nẵng">
    <link rel="canonical" href="https://thome.com/">

    <!-- Cấu hình Thumbnail là ảnh Logo trang web khi gửi link chia sẻ -->
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="thome.com - CÔNG TY CỔ PHẦN XÂY DỰNG VÀ THƯƠNG MẠI T-HOME">
    <meta property="og:url" content="https://thome.com/">
    <meta property="og:title" content="CÔNG TY CỔ PHẦN XÂY DỰNG VÀ THƯƠNG MẠI T-HOME | Thiết Kế & Thi Công Trọn Gói">
    <meta property="og:description" content="Chuyên Thiết kế – Xây dựng – Nội thất Khách sạn, Biệt thự, Căn hộ, Văn phòng, Nhà phố tại Đà Nẵng. Địa chỉ: 07 - 09 Võ Quảng, P. Hòa Xuân, TP Đà Nẵng. Hotline: 0905.436.426.">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1WmBHNuO5MCo30s7j5KGrl0qpdOxtVywJ">
    <meta property="og:image:secure_url" content="https://drive.google.com/thumbnail?id=1WmBHNuO5MCo30s7j5KGrl0qpdOxtVywJ&sz=w1200">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY CỔ PHẦN XÂY DỰNG VÀ THƯƠNG MẠI T-HOME | thome.com">
    <meta name="twitter:description" content="Thiết kế Kiến trúc - Thi công Xây dựng - Nội thất trọn gói tại Đà Nẵng. Hotline: 0905.436.426">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1WmBHNuO5MCo30s7j5KGrl0qpdOxtVywJ">

    <!-- Favicon lấy từ ảnh Logo -->
    <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/1WmBHNuO5MCo30s7j5KGrl0qpdOxtVywJ">
    <link rel="apple-touch-icon" href="https://lh3.googleusercontent.com/d/1WmBHNuO5MCo30s7j5KGrl0qpdOxtVywJ">

    <!-- Google Fonts: Inter / Montserrat chuẩn Flatsome -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>

    <style>
        :root {
            /* Bảng màu đồng bộ theo Logo T-HOME & phong cách kiến trúc xây dựng */
            --thome-primary: #0f3661;      /* Xanh đậm kiến trúc chủ đạo */
            --thome-primary-dark: #09223f; /* Xanh navy đậm */
            --thome-accent: #d97706;       /* Cam vàng xây dựng nổi bật */
            --thome-accent-light: #f59e0b; /* Vàng kim */
            --thome-bg-soft: #f4f7fa;
        }

        /* Đảm bảo tuyệt đối không tràn viền, không lệch sang phải trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }

        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            font-family: 'Inter', sans-serif;
            color: #1e293b;
            background-color: #ffffff;
            scroll-behavior: smooth;
        }

        /* Thiết kế chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình máy tính */
        .flatsome-container {
            width: 100%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }

        @media (min-width: 1024px) {
            .flatsome-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Tối ưu thanh danh mục (Menu) trên máy tính:
           Tên danh mục viết liền trên 1 hàng, chữ nhỏ gọn, không bị gãy chữ xuống dòng */
        .nav-menu-desktop {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: flex-end;
            gap: 2px 6px;
        }

        @media (min-width: 1200px) {
            .nav-menu-desktop {
                flex-wrap: nowrap;
                gap: 4px;
            }
        }

        .nav-item-link {
            white-space: nowrap !important;
            display: inline-flex;
            align-items: center;
            gap: 4px;
            font-size: 12px;
            font-weight: 700;
            text-transform: uppercase;
            letter-spacing: 0.01em;
            padding: 7px 8px;
            border-radius: 6px;
            color: #1e293b;
            transition: all 0.2s ease;
        }

        @media (min-width: 1366px) {
            .nav-item-link {
                font-size: 12.5px;
                padding: 8px 10px;
            }
        }

        .nav-item-link:hover,
        .nav-item-link.active {
            color: var(--thome-accent);
            background-color: rgba(15, 54, 97, 0.05);
        }

        /* Dropdown danh mục con chuẩn Flatsome */
        .nav-dropdown-parent {
            position: relative;
        }

        .nav-dropdown-menu {
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 220px;
            background: #ffffff;
            border-top: 3px solid var(--thome-accent);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.12);
            border-radius: 0 0 8px 8px;
            padding: 6px 0;
            opacity: 0;
            visibility: hidden;
            transform: translateY(8px);
            transition: all 0.2s ease;
            z-index: 100;
        }

        .nav-dropdown-parent:hover .nav-dropdown-menu {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }

        .nav-dropdown-item {
            display: block;
            padding: 8px 14px;
            font-size: 12.5px;
            font-weight: 600;
            color: #334155;
            white-space: nowrap;
            transition: all 0.15s ease;
        }

        .nav-dropdown-item:hover {
            background-color: #f1f5f9;
            color: var(--thome-primary);
            padding-left: 18px;
        }

        /* Chữ danh mục (Tab lọc) ở trang chủ nhỏ gọn, viết liền 1 hàng không gãy dòng */
        .category-pill-btn {
            white-space: nowrap !important;
            font-size: 12px;
            font-weight: 600;
            padding: 6px 12px;
            border-radius: 9999px;
            border: 1px solid #cbd5e1;
            background-color: #ffffff;
            color: #334155;
            transition: all 0.2s ease;
            cursor: pointer;
        }

        .category-pill-btn:hover,
        .category-pill-btn.active {
            background-color: var(--thome-primary);
            color: #ffffff;
            border-color: var(--thome-primary);
        }

        /* Tiêu đề Section chuẩn Flatsome UX Builder */
        .section-title-container {
            margin-bottom: 1.5rem;
        }

        .section-title-normal {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 14px;
            text-align: center;
        }

        .section-title-normal::before,
        .section-title-normal::after {
            content: "";
            flex: 1;
            max-width: 120px;
            height: 2px;
            background: linear-gradient(90deg, transparent, var(--thome-accent), transparent);
        }

        /* Tên sản phẩm / công trình hiển thị đầy đủ, không bị tràn ra ngoài hoặc thiếu chữ */
        .product-box-title {
            font-size: 13px;
            line-height: 1.4;
            font-weight: 700;
            color: #0f172a;
            white-space: normal !important;
            word-break: break-word;
            overflow-wrap: break-word;
            display: block;
        }

        @media (min-width: 640px) {
            .product-box-title {
                font-size: 14.5px;
            }
        }

        /* Hiệu ứng mượt mà cho Box Flatsome */
        .flatsome-box {
            background: #ffffff;
            border-radius: 10px;
            overflow: hidden;
            border: 1px solid #e2e8f0;
            transition: transform 0.25s ease, box-shadow 0.25s ease;
            display: flex;
            flex-direction: column;
            height: 100%;
        }

        .flatsome-box:hover {
            transform: translateY(-3px);
            box-shadow: 0 12px 24px -6px rgba(15, 54, 97, 0.14);
            border-color: #cbd5e1;
        }

        .flatsome-box-image {
            position: relative;
            width: 100%;
            aspect-ratio: 4 / 3;
            overflow: hidden;
            background-color: #f1f5f9;
        }

        .flatsome-box-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.45s ease;
        }

        .flatsome-box:hover .flatsome-box-image img {
            transform: scale(1.05);
        }

        /* Banner Slider 2 ảnh kích thước bằng nhau tuyệt đối, chữ nằm gọn bên trong cách xa viền */
        .banner-slider-viewport {
            position: relative;
            width: 100%;
            overflow: hidden;
            border-radius: 12px;
            background-color: #09223f;
        }

        /* Nút liên hệ nổi bật Zalo, Facebook, Hotline */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 119, 6, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(217, 119, 6, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 119, 6, 0); }
        }

        .floating-btn-pulse {
            animation: pulse-ring 2s infinite;
        }
    </style>
</head>
<body class="bg-white text-slate-800 antialiased">

    <!-- =========================================================================
         TOP BAR: Thông tin địa chỉ & số điện thoại (Chuẩn mẫu tintruongthinh.com)
         ========================================================================= -->
    <div class="bg-[#0f3661] text-white text-xs py-2 border-b border-white/10">
        <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
                <span class="inline-flex items-center gap-1.5">
                    <i class="fa-solid fa-building text-amber-400"></i>
                    <strong class="font-semibold">CÔNG TY CỔ PHẦN XÂY DỰNG VÀ THƯƠNG MẠI T-HOME</strong>
                </span>
                <span class="hidden md:inline-flex items-center gap-1.5 text-slate-200">
                    <i class="fa-solid fa-location-dot text-amber-400"></i>
                    07 - 09 Võ Quảng, Phường Hòa Xuân, TP Đà Nẵng
                </span>
            </div>
            <div class="flex items-center gap-4">
                <a href="tel:0905436426" class="inline-flex items-center gap-1.5 text-amber-300 hover:text-white font-semibold">
                    <i class="fa-solid fa-phone-volume"></i>
                    <span>0905.436.426</span>
                </a>
                <span class="hidden sm:inline text-white/30">|</span>
                <a href="https://www.facebook.com/THIETKE.THICONG.THOME" target="_blank" rel="noopener noreferrer" class="hidden sm:inline-flex items-center gap-1 hover:text-amber-300">
                    <i class="fa-brands fa-facebook"></i>
                    <span>Fanpage T-HOME</span>
                </a>
                <span class="hidden sm:inline text-white/30">|</span>
                <span class="hidden sm:inline text-slate-200 font-medium">thome.com</span>
            </div>
        </div>
    </div>

    <!-- =========================================================================
         HEADER: Logo chỉnh gọn nhỏ lại + Thanh danh mục viết liền trên 1 hàng
         (Không để nút Gọi ngay trên Header để tránh tràn viền)
         ========================================================================= -->
    <header id="header" class="sticky top-0 z-40 bg-white/95 backdrop-blur-md shadow-sm border-b border-slate-200">
        <div class="flatsome-container py-2">
            <div class="flex items-center justify-between gap-3">
                <!-- Logo chỉnh gọn nhỏ lại -->
                <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group">
                    <div class="w-10 h-10 sm:w-11 sm:h-11 rounded-lg overflow-hidden border border-slate-200 bg-white flex items-center justify-center p-0.5 shrink-0 shadow-xs">
                        <img id="site-logo-img"
                             src="https://lh3.googleusercontent.com/d/1WmBHNuO5MCo30s7j5KGrl0qpdOxtVywJ"
                             onerror="if(this.src.indexOf('drive.google.com/thumbnail')===-1){this.src='https://drive.google.com/thumbnail?id=1WmBHNuO5MCo30s7j5KGrl0qpdOxtVywJ&sz=w400';}else{this.src='https://placehold.co/120x120/0f3661/f59e0b?text=T-HOME';}"
                             alt="Logo CÔNG TY CỔ PHẦN XÂY DỰNG VÀ THƯƠNG MẠI T-HOME"
                             class="w-full h-full object-contain">
                    </div>
                    <div class="leading-tight">
                        <span class="block text-sm sm:text-base font-extrabold text-[#0f3661] tracking-tight group-hover:text-amber-600 transition-colors">T-HOME</span>
                        <span class="block text-[10px] sm:text-[11px] font-semibold text-slate-500">XÂY DỰNG & THƯƠNG MẠI</span>
                    </div>
                </a>

                <!-- Danh mục trên máy tính: chữ nhỏ gọn, tên danh mục viết liền trên 1 hàng không gãy chữ -->
                <nav class="hidden lg:block flex-1" aria-label="Danh mục chính">
                    <ul class="nav-menu-desktop">
                        <li>
                            <a href="#trang-chu" class="nav-item-link active">Trang chủ</a>
                        </li>
                        <li>
                            <a href="#gioi-thieu" class="nav-item-link">Giới thiệu</a>
                        </li>
                        <li class="nav-dropdown-parent">
                            <a href="#cong-trinh-thuc-te" class="nav-item-link">
                                <span>Công trình thực tế</span>
                                <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                            </a>
                            <div class="nav-dropdown-menu">
                                <a href="#cong-trinh-thuc-te" onclick="filterSection('thi-cong', 'all')" class="nav-dropdown-item">Tất cả công trình</a>
                                <a href="#cong-trinh-thuc-te" onclick="filterSection('thi-cong', 'khach-san-can-ho')" class="nav-dropdown-item">Khách sạn – Căn hộ – Phòng trọ</a>
                                <a href="#cong-trinh-thuc-te" onclick="filterSection('thi-cong', 'biet-thu')" class="nav-dropdown-item">Biệt thự</a>
                                <a href="#cong-trinh-thuc-te" onclick="filterSection('thi-cong', 'nha-pho')" class="nav-dropdown-item">Nhà phố</a>
                                <a href="#cong-trinh-thuc-te" onclick="filterSection('thi-cong', 'van-phong')" class="nav-dropdown-item">Văn phòng</a>
                            </div>
                        </li>
                        <li class="nav-dropdown-parent">
                            <a href="#linh-vuc-hoat-dong" class="nav-item-link">
                                <span>Lĩnh vực hoạt động</span>
                                <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                            </a>
                            <div class="nav-dropdown-menu">
                                <a href="#linh-vuc-hoat-dong" class="nav-dropdown-item">Thiết kế Kiến trúc – Nội thất</a>
                                <a href="#linh-vuc-hoat-dong" class="nav-dropdown-item">Thi công phần thô</a>
                                <a href="#linh-vuc-hoat-dong" class="nav-dropdown-item">Thi công hoàn thiện</a>
                                <a href="#linh-vuc-hoat-dong" class="nav-dropdown-item">Thi công nội thất</a>
                            </div>
                        </li>
                        <li class="nav-dropdown-parent">
                            <a href="#cong-trinh-thuc-te" class="nav-item-link">
                                <span>Mẫu thiết kế</span>
                                <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                            </a>
                            <div class="nav-dropdown-menu">
                                <a href="#cong-trinh-thuc-te" onclick="filterSection('thi-cong', 'nha-pho')" class="nav-dropdown-item">Mẫu thiết kế nhà phố</a>
                                <a href="#cong-trinh-thuc-te" onclick="filterSection('thi-cong', 'biet-thu')" class="nav-dropdown-item">Mẫu thiết kế biệt thự</a>
                                <a href="#cong-trinh-thuc-te" onclick="filterSection('thi-cong', 'noi-that')" class="nav-dropdown-item">Mẫu thiết kế nội thất</a>
                            </div>
                        </li>
                        <li>
                            <a href="#du-an-da-nang" class="nav-item-link">Dự án Đà Nẵng</a>
                        </li>
                        <li class="nav-dropdown-parent">
                            <a href="#bao-gia" class="nav-item-link">
                                <span>Báo giá</span>
                                <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                            </a>
                            <div class="nav-dropdown-menu">
                                <a href="#bao-gia" class="nav-dropdown-item">Báo giá thiết kế kiến trúc</a>
                                <a href="#bao-gia" class="nav-dropdown-item">Báo giá thi công phần thô</a>
                                <a href="#bao-gia" class="nav-dropdown-item">Báo giá thi công hoàn thiện</a>
                                <a href="#bao-gia" class="nav-dropdown-item">Báo giá thi công trọn gói</a>
                            </div>
                        </li>
                        <li>
                            <a href="#doi-tac" class="nav-item-link">Đối tác</a>
                        </li>
                        <li>
                            <a href="#tin-tuc" class="nav-item-link">Tin tức</a>
                        </li>
                        <li>
                            <a href="#lien-he" class="nav-item-link">Liên hệ</a>
                        </li>
                    </ul>
                </nav>

                <!-- Nút mở Menu trên Điện thoại -->
                <button id="mobile-menu-toggle" type="button" aria-label="Mở danh mục" class="lg:hidden inline-flex items-center gap-1.5 px-3 py-2 rounded-lg bg-slate-100 hover:bg-slate-200 text-[#0f3661] text-xs font-bold">
                    <i class="fa-solid fa-bars text-base"></i>
                    <span>DANH MỤC</span>
                </button>
            </div>

            <!-- Thanh cuộn nhanh danh mục trên Điện thoại (giúp xem trên điện thoại đẹp & tiện lợi) -->
            <div class="lg:hidden mt-2 pt-2 border-t border-slate-100 flex items-center gap-1.5 overflow-x-auto no-scrollbar pb-1">
                <a href="#trang-chu" class="whitespace-nowrap px-2.5 py-1 rounded-md bg-[#0f3661] text-white text-[11px] font-semibold">Trang chủ</a>
                <a href="#gioi-thieu" class="whitespace-nowrap px-2.5 py-1 rounded-md bg-slate-100 text-slate-700 text-[11px] font-semibold">Giới thiệu</a>
                <a href="#linh-vuc-hoat-dong" class="whitespace-nowrap px-2.5 py-1 rounded-md bg-slate-100 text-slate-700 text-[11px] font-semibold">Lĩnh vực hoạt động</a>
                <a href="#cong-trinh-thuc-te" class="whitespace-nowrap px-2.5 py-1 rounded-md bg-slate-100 text-slate-700 text-[11px] font-semibold">Thi công thực tế</a>
                <a href="#du-an-da-nang" class="whitespace-nowrap px-2.5 py-1 rounded-md bg-slate-100 text-slate-700 text-[11px] font-semibold">Dự án Đà Nẵng</a>
                <a href="#bao-gia" class="whitespace-nowrap px-2.5 py-1 rounded-md bg-slate-100 text-slate-700 text-[11px] font-semibold">Báo giá</a>
                <a href="#doi-tac" class="whitespace-nowrap px-2.5 py-1 rounded-md bg-slate-100 text-slate-700 text-[11px] font-semibold">Đối tác</a>
                <a href="#tin-tuc" class="whitespace-nowrap px-2.5 py-1 rounded-md bg-slate-100 text-slate-700 text-[11px] font-semibold">Tin tức</a>
                <a href="#lien-he" class="whitespace-nowrap px-2.5 py-1 rounded-md bg-slate-100 text-slate-700 text-[11px] font-semibold">Liên hệ</a>
            </div>
        </div>

        <!-- Drawer Menu trên Điện thoại -->
        <div id="mobile-menu-panel" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-xl">
            <div class="flatsome-container py-3 grid grid-cols-2 gap-2 text-xs font-bold">
                <a href="#trang-chu" class="mobile-nav-link p-2.5 rounded-lg bg-slate-50 hover:bg-amber-50 text-[#0f3661] flex items-center gap-2">
                    <i class="fa-solid fa-house text-amber-600"></i> Trang chủ
                </a>
                <a href="#gioi-thieu" class="mobile-nav-link p-2.5 rounded-lg bg-slate-50 hover:bg-amber-50 text-[#0f3661] flex items-center gap-2">
                    <i class="fa-solid fa-circle-info text-amber-600"></i> Giới thiệu
                </a>
                <a href="#cong-trinh-thuc-te" class="mobile-nav-link p-2.5 rounded-lg bg-slate-50 hover:bg-amber-50 text-[#0f3661] flex items-center gap-2">
                    <i class="fa-solid fa-helmet-safety text-amber-600"></i> Công trình thực tế
                </a>
                <a href="#linh-vuc-hoat-dong" class="mobile-nav-link p-2.5 rounded-lg bg-slate-50 hover:bg-amber-50 text-[#0f3661] flex items-center gap-2">
                    <i class="fa-solid fa-layer-group text-amber-600"></i> Lĩnh vực hoạt động
                </a>
                <a href="#cong-trinh-thuc-te" class="mobile-nav-link p-2.5 rounded-lg bg-slate-50 hover:bg-amber-50 text-[#0f3661] flex items-center gap-2">
                    <i class="fa-solid fa-compass-drafting text-amber-600"></i> Mẫu thiết kế
                </a>
                <a href="#du-an-da-nang" class="mobile-nav-link p-2.5 rounded-lg bg-slate-50 hover:bg-amber-50 text-[#0f3661] flex items-center gap-2">
                    <i class="fa-solid fa-city text-amber-600"></i> Dự án Đà Nẵng
                </a>
                <a href="#bao-gia" class="mobile-nav-link p-2.5 rounded-lg bg-slate-50 hover:bg-amber-50 text-[#0f3661] flex items-center gap-2">
                    <i class="fa-solid fa-file-invoice-dollar text-amber-600"></i> Báo giá
                </a>
                <a href="#doi-tac" class="mobile-nav-link p-2.5 rounded-lg bg-slate-50 hover:bg-amber-50 text-[#0f3661] flex items-center gap-2">
                    <i class="fa-solid fa-handshake text-amber-600"></i> Đối tác
                </a>
                <a href="#tin-tuc" class="mobile-nav-link p-2.5 rounded-lg bg-slate-50 hover:bg-amber-50 text-[#0f3661] flex items-center gap-2">
                    <i class="fa-solid fa-newspaper text-amber-600"></i> Tin tức
                </a>
                <a href="#lien-he" class="mobile-nav-link p-2.5 rounded-lg bg-slate-50 hover:bg-amber-50 text-[#0f3661] flex items-center gap-2">
                    <i class="fa-solid fa-map-location-dot text-amber-600"></i> Liên hệ & Map
                </a>
            </div>
        </div>
    </header>

    <main id="main">

        <!-- =========================================================================
             [UX BUILDER SECTION: SLIDER BANNER]
             2 ảnh banner tự trượt chuyên nghiệp kích thước bằng nhau (viewBox 1600x640),
             thiết kế hình ảnh và chữ nằm trong hết banner, chữ cách xa viền ảnh banner,
             đảm bảo trên điện thoại và máy tính không bao giờ bị thiếu chữ hay cắt chữ.
             ========================================================================= -->
        <section id="trang-chu" class="section py-3 sm:py-4 bg-slate-50">
            <div class="flatsome-container">
                <div class="banner-slider-viewport shadow-md">
                    <div id="banner-track" class="flex transition-transform duration-700 ease-in-out w-full">

                        <!-- SLIDE 1: Thiết Kế & Thi Công Xây Dựng Trọn Gói T-HOME -->
                        <div class="w-full shrink-0">
                            <svg viewBox="0 0 1600 640" class="w-full h-auto block select-none" preserveAspectRatio="xMidYMid meet" role="img" aria-label="Banner 1 Công ty Cổ phần Xây dựng và Thương mại T-HOME">
                                <defs>
                                    <linearGradient id="bgGrad1" x1="0%" y1="0%" x2="100%" y2="100%">
                                        <stop offset="0%" stop-color="#07192e"/>
                                        <stop offset="55%" stop-color="#0f3661"/>
                                        <stop offset="100%" stop-color="#174a82"/>
                                    </linearGradient>
                                    <linearGradient id="goldGrad1" x1="0%" y1="0%" x2="100%" y2="0%">
                                        <stop offset="0%" stop-color="#f59e0b"/>
                                        <stop offset="100%" stop-color="#fbbf24"/>
                                    </linearGradient>
                                    <clipPath id="imgClip1">
                                        <rect x="930" y="75" width="530" height="490" rx="22"/>
                                    </clipPath>
                                </defs>

                                <!-- Nền Banner 1 -->
                                <rect width="1600" height="640" fill="url(#bgGrad1)"/>

                                <!-- Họa tiết lưới kiến trúc kỹ thuật bên trong -->
                                <g stroke="#ffffff" stroke-opacity="0.06" stroke-width="1">
                                    <line x1="0" y1="120" x2="1600" y2="120"/>
                                    <line x1="0" y1="260" x2="1600" y2="260"/>
                                    <line x1="0" y1="400" x2="1600" y2="400"/>
                                    <line x1="0" y1="540" x2="1600" y2="540"/>
                                    <line x1="160" y1="0" x2="160" y2="640"/>
                                    <line x1="520" y1="0" x2="520" y2="640"/>
                                    <line x1="880" y1="0" x2="880" y2="640"/>
                                    <line x1="1240" y1="0" x2="1240" y2="640"/>
                                </g>

                                <!-- Viền an toàn cách xa mép banner -->
                                <rect x="65" y="45" width="1470" height="550" rx="24" fill="none" stroke="#fbbf24" stroke-opacity="0.3" stroke-width="2"/>

                                <!-- Khung hình ảnh công trình nằm gọn trong Banner 1 -->
                                <rect x="922" y="67" width="546" height="506" rx="26" fill="none" stroke="url(#goldGrad1)" stroke-width="3"/>
                                <g clip-path="url(#imgClip1)">
                                    <rect x="930" y="75" width="530" height="490" fill="#1e3a5f"/>
                                    <image href="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT" x="930" y="75" width="530" height="490" preserveAspectRatio="xMidYMid slice"/>
                                    <rect x="930" y="435" width="530" height="130" fill="#07192e" fill-opacity="0.82"/>
                                    <text x="1195" y="485" fill="#fbbf24" font-family="Inter, sans-serif" font-size="22" font-weight="800" text-anchor="middle">KIẾN TẠO KHÔNG GIAN SỐNG ĐẲNG CẤP</text>
                                    <text x="1195" y="520" fill="#e2e8f0" font-family="Inter, sans-serif" font-size="17" font-weight="600" text-anchor="middle">Biệt Thự • Nhà Phố • Khách Sạn • Căn Hộ • Văn Phòng</text>
                                </g>

                                <!-- Toàn bộ chữ cách xa viền banner (tọa độ X=120..880, Y=115..535) -->
                                <rect x="120" y="95" width="410" height="42" rx="21" fill="url(#goldGrad1)"/>
                                <text x="325" y="123" fill="#07192e" font-family="Inter, sans-serif" font-size="20" font-weight="800" text-anchor="middle">WEBSITE CHÍNH THỨC: THOME.COM</text>

                                <text x="120" y="195" fill="#ffffff" font-family="Inter, sans-serif" font-size="34" font-weight="800">CÔNG TY CỔ PHẦN XÂY DỰNG</text>
                                <text x="120" y="248" fill="#fbbf24" font-family="Inter, sans-serif" font-size="38" font-weight="800">VÀ THƯƠNG MẠI T-HOME</text>

                                <text x="120" y="305" fill="#e2e8f0" font-family="Inter, sans-serif" font-size="23" font-weight="600">Chuyên Thiết Kế Kiến Trúc – Thi Công Xây Dựng – Nội Thất</text>
                                <text x="120" y="342" fill="#cbd5e1" font-family="Inter, sans-serif" font-size="20" font-weight="500">An Toàn – Chất Lượng – Đúng Tiến Độ – Tối Ưu Chi Phí</text>

                                <!-- Các cam kết nổi bật -->
                                <g transform="translate(120, 375)">
                                    <rect x="0" y="0" width="365" height="52" rx="10" fill="#ffffff" fill-opacity="0.1" stroke="#fbbf24" stroke-opacity="0.4"/>
                                    <text x="20" y="33" fill="#fbbf24" font-family="Inter, sans-serif" font-size="20" font-weight="700">✓ Miễn phí 100% thiết kế khi thi công</text>

                                    <rect x="385" y="0" width="385" height="52" rx="10" fill="#ffffff" fill-opacity="0.1" stroke="#fbbf24" stroke-opacity="0.4"/>
                                    <text x="405" y="33" fill="#fbbf24" font-family="Inter, sans-serif" font-size="20" font-weight="700">✓ Bảo hành kết cấu công trình dài hạn</text>
                                </g>

                                <!-- Thông tin liên hệ cách xa viền dưới -->
                                <rect x="120" y="455" width="770" height="90" rx="14" fill="#07192e" fill-opacity="0.75" stroke="#fbbf24" stroke-width="1.5"/>
                                <text x="145" y="493" fill="#fbbf24" font-family="Inter, sans-serif" font-size="22" font-weight="800">HOTLINE TƯ VẤN: 0905.436.426</text>
                                <text x="145" y="527" fill="#ffffff" font-family="Inter, sans-serif" font-size="19" font-weight="600">Địa chỉ: 07 - 09 Võ Quảng, Phường Hòa Xuân, TP Đà Nẵng</text>
                            </svg>
                        </div>

                        <!-- SLIDE 2: Giải Pháp Thi Công Phần Thô & Xây Nhà Trọn Gói Chìa Khóa Trao Tay -->
                        <div class="w-full shrink-0">
                            <svg viewBox="0 0 1600 640" class="w-full h-auto block select-none" preserveAspectRatio="xMidYMid meet" role="img" aria-label="Banner 2 Giải Pháp Xây Dựng Trọn Gói T-HOME Đà Nẵng">
                                <defs>
                                    <linearGradient id="bgGrad2" x1="0%" y1="0%" x2="100%" y2="100%">
                                        <stop offset="0%" stop-color="#09223f"/>
                                        <stop offset="50%" stop-color="#123e6b"/>
                                        <stop offset="100%" stop-color="#0b2948"/>
                                    </linearGradient>
                                    <clipPath id="imgClip2A">
                                        <rect x="930" y="75" width="255" height="490" rx="18"/>
                                    </clipPath>
                                    <clipPath id="imgClip2B">
                                        <rect x="1205" y="75" width="255" height="490" rx="18"/>
                                    </clipPath>
                                </defs>

                                <!-- Nền Banner 2 -->
                                <rect width="1600" height="640" fill="url(#bgGrad2)"/>

                                <!-- Đường viền an toàn cách xa mép ảnh -->
                                <rect x="65" y="45" width="1470" height="550" rx="24" fill="none" stroke="#f59e0b" stroke-opacity="0.35" stroke-width="2"/>

                                <!-- 2 khung ảnh công trình thực tế nằm gọn bên phải -->
                                <g clip-path="url(#imgClip2A)">
                                    <rect x="930" y="75" width="255" height="490" fill="#1e3a5f"/>
                                    <image href="https://lh3.googleusercontent.com/d/1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff" x="930" y="75" width="255" height="490" preserveAspectRatio="xMidYMid slice"/>
                                    <rect x="930" y="475" width="255" height="90" fill="#07192e" fill-opacity="0.85"/>
                                    <text x="1057" y="527" fill="#fbbf24" font-family="Inter, sans-serif" font-size="18" font-weight="800" text-anchor="middle">DỰ ÁN ĐÀ NẴNG</text>
                                </g>
                                <rect x="930" y="75" width="255" height="490" rx="18" fill="none" stroke="#fbbf24" stroke-width="2.5"/>

                                <g clip-path="url(#imgClip2B)">
                                    <rect x="1205" y="75" width="255" height="490" fill="#1e3a5f"/>
                                    <image href="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz" x="1205" y="75" width="255" height="490" preserveAspectRatio="xMidYMid slice"/>
                                    <rect x="1205" y="475" width="255" height="90" fill="#07192e" fill-opacity="0.85"/>
                                    <text x="1332" y="527" fill="#fbbf24" font-family="Inter, sans-serif" font-size="18" font-weight="800" text-anchor="middle">THI CÔNG THỰC TẾ</text>
                                </g>
                                <rect x="1205" y="75" width="255" height="490" rx="18" fill="none" stroke="#fbbf24" stroke-width="2.5"/>

                                <!-- Nội dung chữ cách xa viền ảnh banner -->
                                <rect x="120" y="95" width="460" height="42" rx="21" fill="#f59e0b"/>
                                <text x="350" y="123" fill="#07192e" font-family="Inter, sans-serif" font-size="20" font-weight="800" text-anchor="middle">NHÀ Ở GIA ĐÌNH – TIÊU CHUẨN CÔNG TRÌNH</text>

                                <text x="120" y="195" fill="#ffffff" font-family="Inter, sans-serif" font-size="34" font-weight="800">GIẢI PHÁP XÂY NHÀ TRỌN GÓI</text>
                                <text x="120" y="248" fill="#fbbf24" font-family="Inter, sans-serif" font-size="36" font-weight="800">CHÌA KHÓA TRAO TAY TẠI ĐÀ NẴNG</text>

                                <text x="120" y="305" fill="#e2e8f0" font-family="Inter, sans-serif" font-size="22" font-weight="600">• Thi công phần thô &amp; hoàn thiện chuẩn kỹ thuật xây dựng</text>
                                <text x="120" y="343" fill="#e2e8f0" font-family="Inter, sans-serif" font-size="22" font-weight="600">• Giám sát công trình chặt chẽ, vật tư chính hãng 100%</text>
                                <text x="120" y="381" fill="#e2e8f0" font-family="Inter, sans-serif" font-size="22" font-weight="600">• Báo giá minh bạch, cam kết không phát sinh chi phí</text>

                                <rect x="120" y="425" width="770" height="115" rx="14" fill="#07192e" fill-opacity="0.8" stroke="#f59e0b" stroke-width="1.5"/>
                                <text x="145" y="465" fill="#fbbf24" font-family="Inter, sans-serif" font-size="22" font-weight="800">CÔNG TY CỔ PHẦN XÂY DỰNG VÀ THƯƠNG MẠI T-HOME</text>
                                <text x="145" y="498" fill="#ffffff" font-family="Inter, sans-serif" font-size="20" font-weight="700">Hotline/Zalo: 0905.436.426  |  Website: thome.com</text>
                                <text x="145" y="526" fill="#cbd5e1" font-family="Inter, sans-serif" font-size="18" font-weight="500">Trụ sở: 07 - 09 Võ Quảng, Phường Hòa Xuân, TP Đà Nẵng</text>
                            </svg>
                        </div>

                    </div>

                    <!-- Nút điều hướng Banner -->
                    <button type="button" onclick="changeSlide(-1)" aria-label="Slide trước" class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/40 hover:bg-amber-500 text-white flex items-center justify-center transition">
                        <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
                    </button>
                    <button type="button" onclick="changeSlide(1)" aria-label="Slide tiếp theo" class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/40 hover:bg-amber-500 text-white flex items-center justify-center transition">
                        <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
                    </button>

                    <!-- Chấm tròn báo vị trí Slide -->
                    <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 flex items-center gap-2">
                        <button type="button" onclick="goToSlide(0)" id="slider-dot-0" aria-label="Banner 1" class="w-6 h-2 rounded-full bg-amber-400 transition-all"></button>
                        <button type="button" onclick="goToSlide(1)" id="slider-dot-1" aria-label="Banner 2" class="w-2.5 h-2 rounded-full bg-white/60 transition-all"></button>
                    </div>
                </div>
            </div>
        </section>

        <!-- =========================================================================
             [UX BUILDER SECTION: DỊCH VỤ TIÊU BIỂU & GIỚI THIỆU T-HOME]
             Thiết kế giống web mẫu tintruongthinh.com:
             3 khối Dịch Vụ Tiêu Biểu (THIẾT KẾ - THI CÔNG - NỘI THẤT) + Giới thiệu + 6 Thế mạnh
             ========================================================================= -->
        <section id="gioi-thieu" class="section py-8 sm:py-12 bg-white">
            <div class="flatsome-container">

                <!-- 3 Khối Dịch Vụ Tiêu Biểu chuẩn web mẫu -->
                <div class="grid grid-cols-3 gap-2.5 sm:gap-6 mb-10">
                    <a href="#linh-vuc-hoat-dong" class="group rounded-xl p-3 sm:p-6 bg-[#f8fafc] hover:bg-[#0f3661] border border-slate-200 transition-all text-center shadow-xs">
                        <div class="w-10 h-10 sm:w-14 sm:h-14 mx-auto rounded-full bg-amber-500/15 group-hover:bg-amber-500 text-amber-600 group-hover:text-white flex items-center justify-center mb-2 sm:mb-3 transition-colors">
                            <i class="fa-solid fa-compass-drafting text-lg sm:text-2xl"></i>
                        </div>
                        <h3 class="text-xs sm:text-lg font-extrabold text-[#0f3661] group-hover:text-white uppercase">THIẾT KẾ</h3>
                        <p class="hidden sm:block text-xs text-slate-500 group-hover:text-slate-200 mt-1">Kiến trúc – Kết cấu – Nội thất 3D</p>
                    </a>

                    <a href="#cong-trinh-thuc-te" class="group rounded-xl p-3 sm:p-6 bg-[#f8fafc] hover:bg-[#0f3661] border border-slate-200 transition-all text-center shadow-xs">
                        <div class="w-10 h-10 sm:w-14 sm:h-14 mx-auto rounded-full bg-amber-500/15 group-hover:bg-amber-500 text-amber-600 group-hover:text-white flex items-center justify-center mb-2 sm:mb-3 transition-colors">
                            <i class="fa-solid fa-trowel-bricks text-lg sm:text-2xl"></i>
                        </div>
                        <h3 class="text-xs sm:text-lg font-extrabold text-[#0f3661] group-hover:text-white uppercase">THI CÔNG</h3>
                        <p class="hidden sm:block text-xs text-slate-500 group-hover:text-slate-200 mt-1">Phần thô – Hoàn thiện – Trọn gói</p>
                    </a>

                    <a href="#du-an-da-nang" class="group rounded-xl p-3 sm:p-6 bg-[#f8fafc] hover:bg-[#0f3661] border border-slate-200 transition-all text-center shadow-xs">
                        <div class="w-10 h-10 sm:w-14 sm:h-14 mx-auto rounded-full bg-amber-500/15 group-hover:bg-amber-500 text-amber-600 group-hover:text-white flex items-center justify-center mb-2 sm:mb-3 transition-colors">
                            <i class="fa-solid fa-couch text-lg sm:text-2xl"></i>
                        </div>
                        <h3 class="text-xs sm:text-lg font-extrabold text-[#0f3661] group-hover:text-white uppercase">NỘI THẤT</h3>
                        <p class="hidden sm:block text-xs text-slate-500 group-hover:text-slate-200 mt-1">Sản xuất &amp; Lắp đặt đồng bộ</p>
                    </a>
                </div>

                <!-- Giới thiệu Công ty & Thế mạnh của chúng tôi -->
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 sm:gap-8 items-center">
                    <div class="lg:col-span-5 bg-[#0f3661] text-white rounded-2xl p-5 sm:p-7 shadow-md">
                        <div class="flex items-center gap-3 mb-4">
                            <img src="https://lh3.googleusercontent.com/d/1WmBHNuO5MCo30s7j5KGrl0qpdOxtVywJ"
                                 onerror="this.src='https://drive.google.com/thumbnail?id=1WmBHNuO5MCo30s7j5KGrl0qpdOxtVywJ&sz=w300'"
                                 alt="Logo T-HOME"
                                 class="w-12 h-12 rounded-lg bg-white p-1 object-contain shrink-0">
                            <div>
                                <span class="text-amber-400 text-xs font-bold uppercase tracking-wider">Về chúng tôi • thome.com</span>
                                <h2 class="text-base sm:text-lg font-extrabold leading-snug">CÔNG TY CỔ PHẦN XÂY DỰNG VÀ THƯƠNG MẠI T-HOME</h2>
                            </div>
                        </div>
                        <p class="text-xs sm:text-sm text-slate-200 leading-relaxed mb-3">
                            <strong>T-HOME</strong> chuyên <strong>Thiết kế – Xây dựng – Nội thất</strong> các công trình Khách sạn, Biệt thự, Căn hộ, Văn phòng, Nhà phố tại TP Đà Nẵng và khu vực miền Trung.
                        </p>
                        <p class="text-xs sm:text-sm text-slate-200 leading-relaxed mb-4">
                            Với tiêu chí <em>“Nhà ở Gia đình – Tiêu chuẩn Công trình”</em>, chúng tôi luôn đặt chữ <strong>“TÂM”</strong> và chữ <strong>“TÍN”</strong> lên hàng đầu để mỗi công trình đều đạt chuẩn: <strong>AN TOÀN – CHẤT LƯỢNG – TIẾN ĐỘ – SỰ HÀI LÒNG CỦA KHÁCH HÀNG</strong>.
                        </p>
                        <div class="space-y-2 text-xs sm:text-sm border-t border-white/15 pt-4">
                            <div class="flex items-start gap-2">
                                <i class="fa-solid fa-location-dot text-amber-400 mt-1"></i>
                                <span><strong>Địa chỉ:</strong> 07 - 09 Võ Quảng, Phường Hòa Xuân, TP Đà Nẵng</span>
                            </div>
                            <div class="flex items-center gap-2">
                                <i class="fa-solid fa-phone text-amber-400"></i>
                                <span><strong>Hotline:</strong> <a href="tel:0905436426" class="text-amber-300 font-bold hover:underline">0905.436.426</a></span>
                            </div>
                            <div class="flex items-center gap-2">
                                <i class="fa-solid fa-globe text-amber-400"></i>
                                <span><strong>Website:</strong> thome.com</span>
                            </div>
                        </div>
                    </div>

                    <!-- 6 Thế mạnh của T-HOME (Giống bố cục web mẫu tintruongthinh.com) -->
                    <div class="lg:col-span-7">
                        <div class="mb-4">
                            <span class="text-xs font-bold uppercase text-amber-600 tracking-wider">Giá trị cốt lõi</span>
                            <h3 class="text-lg sm:text-2xl font-extrabold text-[#0f3661]">THẾ MẠNH CỦA CHÚNG TÔI</h3>
                        </div>
                        <div class="grid grid-cols-2 sm:grid-cols-2 gap-3 sm:gap-4">
                            <div class="p-3.5 sm:p-4 rounded-xl bg-slate-50 border border-slate-200">
                                <div class="w-8 h-8 rounded-lg bg-[#0f3661] text-amber-400 flex items-center justify-center mb-2 text-sm">
                                    <i class="fa-solid fa-user-tie"></i>
                                </div>
                                <h4 class="text-xs sm:text-sm font-bold text-[#0f3661] mb-1">Đội ngũ KTS, Kỹ sư chuyên nghiệp</h4>
                                <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Kiến trúc sư sáng tạo cùng đội ngũ kỹ sư giàu kinh nghiệm và thợ lành nghề.</p>
                            </div>

                            <div class="p-3.5 sm:p-4 rounded-xl bg-slate-50 border border-slate-200">
                                <div class="w-8 h-8 rounded-lg bg-[#0f3661] text-amber-400 flex items-center justify-center mb-2 text-sm">
                                    <i class="fa-solid fa-lightbulb"></i>
                                </div>
                                <h4 class="text-xs sm:text-sm font-bold text-[#0f3661] mb-1">Cập nhật xu hướng hiện đại</h4>
                                <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Ứng dụng giải pháp kiến trúc xanh, vật liệu mới và biện pháp thi công tiên tiến.</p>
                            </div>

                            <div class="p-3.5 sm:p-4 rounded-xl bg-slate-50 border border-slate-200">
                                <div class="w-8 h-8 rounded-lg bg-[#0f3661] text-amber-400 flex items-center justify-center mb-2 text-sm">
                                    <i class="fa-solid fa-clipboard-check"></i>
                                </div>
                                <h4 class="text-xs sm:text-sm font-bold text-[#0f3661] mb-1">Giám sát tiến độ chuẩn xác</h4>
                                <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Báo cáo nhật ký công trình thường xuyên, cam kết bàn giao đúng tiến độ hợp đồng.</p>
                            </div>

                            <div class="p-3.5 sm:p-4 rounded-xl bg-slate-50 border border-slate-200">
                                <div class="w-8 h-8 rounded-lg bg-[#0f3661] text-amber-400 flex items-center justify-center mb-2 text-sm">
                                    <i class="fa-solid fa-shield-halved"></i>
                                </div>
                                <h4 class="text-xs sm:text-sm font-bold text-[#0f3661] mb-1">Bảo hành công trình lâu dài</h4>
                                <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Chế độ hậu mãi tận tâm, bảo hành kết cấu dài hạn giúp gia chủ hoàn toàn an tâm.</p>
                            </div>

                            <div class="p-3.5 sm:p-4 rounded-xl bg-slate-50 border border-slate-200">
                                <div class="w-8 h-8 rounded-lg bg-[#0f3661] text-amber-400 flex items-center justify-center mb-2 text-sm">
                                    <i class="fa-solid fa-scale-balanced"></i>
                                </div>
                                <h4 class="text-xs sm:text-sm font-bold text-[#0f3661] mb-1">Giá cả hợp lý, minh bạch</h4>
                                <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Dự toán chi tiết từng hạng mục vật tư, tối ưu ngân sách và không phát sinh.</p>
                            </div>

                            <div class="p-3.5 sm:p-4 rounded-xl bg-slate-50 border border-slate-200">
                                <div class="w-8 h-8 rounded-lg bg-[#0f3661] text-amber-400 flex items-center justify-center mb-2 text-sm">
                                    <i class="fa-solid fa-headset"></i>
                                </div>
                                <h4 class="text-xs sm:text-sm font-bold text-[#0f3661] mb-1">Hỗ trợ tư vấn miễn phí 24/7</h4>
                                <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Tư vấn công năng, phong thủy và thủ tục xin phép xây dựng tận tình 24/7.</p>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </section>

        <!-- =========================================================================
             [UX BUILDER SECTION: LĨNH VỰC HOẠT ĐỘNG (4 Danh mục từ web mẫu)]
             Thiết kế Kiến trúc – Nội thất | Thi công phần thô | Thi công hoàn thiện | Thi công nội thất
             Chia 2 cột trên điện thoại, 4 cột trên máy tính, không nhãn dán
             ========================================================================= -->
        <section id="linh-vuc-hoat-dong" class="section py-8 sm:py-12 bg-[#f4f7fa]">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <h2 class="section-title-normal text-base sm:text-2xl font-extrabold text-[#0f3661] uppercase">
                        <span>LĨNH VỰC HOẠT ĐỘNG</span>
                    </h2>
                    <p class="text-center text-xs sm:text-sm text-slate-600 mt-1">Giải pháp thiết kế và thi công xây dựng đồng bộ tại T-HOME</p>
                </div>

                <!-- Chia 2 cột trên giao diện điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4) -->
                <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                    <div class="flatsome-box">
                        <div class="flatsome-box-image">
                            <img src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT"
                                 onerror="this.src='https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w800'"
                                 alt="Thiết kế Kiến trúc – Nội thất T-HOME" loading="lazy">
                        </div>
                        <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="product-box-title">Thiết kế Kiến trúc – Nội thất</h3>
                                <p class="text-[11px] sm:text-xs text-slate-500 mt-1.5 leading-relaxed">Lên phương án mặt bằng công năng 2D, phối cảnh 3D ngoại thất, kết cấu và hồ sơ điện nước đồng bộ.</p>
                            </div>
                            <a href="#form-bao-gia" class="mt-3 inline-flex items-center gap-1 text-xs font-bold text-[#0f3661] hover:text-amber-600">
                                <span>Nhận tư vấn thiết kế</span>
                                <i class="fa-solid fa-arrow-right text-[10px]"></i>
                            </a>
                        </div>
                    </div>

                    <div class="flatsome-box">
                        <div class="flatsome-box-image">
                            <img src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
                                 onerror="this.src='https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w800'"
                                 alt="Thi công phần thô T-HOME" loading="lazy">
                        </div>
                        <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="product-box-title">Thi công phần thô &amp; Nhân công hoàn thiện</h3>
                                <p class="text-[11px] sm:text-xs text-slate-500 mt-1.5 leading-relaxed">Thi công móng, kết cấu bê tông cốt thép, xây tô tường đúng tiêu chuẩn kỹ thuật xây dựng Việt Nam.</p>
                            </div>
                            <a href="#form-bao-gia" class="mt-3 inline-flex items-center gap-1 text-xs font-bold text-[#0f3661] hover:text-amber-600">
                                <span>Xem đơn giá phần thô</span>
                                <i class="fa-solid fa-arrow-right text-[10px]"></i>
                            </a>
                        </div>
                    </div>

                    <div class="flatsome-box">
                        <div class="flatsome-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t"
                                 onerror="this.src='https://drive.google.com/thumbnail?id=1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t&sz=w800'"
                                 alt="Thi công hoàn thiện T-HOME" loading="lazy">
                        </div>
                        <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="product-box-title">Thi công hoàn thiện công trình</h3>
                                <p class="text-[11px] sm:text-xs text-slate-500 mt-1.5 leading-relaxed">Ốp lát gạch đá, sơn bả, trần thạch cao, cửa nhôm kính, lan can và lắp đặt thiết bị điện nước hoàn chỉnh.</p>
                            </div>
                            <a href="#form-bao-gia" class="mt-3 inline-flex items-center gap-1 text-xs font-bold text-[#0f3661] hover:text-amber-600">
                                <span>Nhận báo giá hoàn thiện</span>
                                <i class="fa-solid fa-arrow-right text-[10px]"></i>
                            </a>
                        </div>
                    </div>

                    <div class="flatsome-box">
                        <div class="flatsome-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT"
                                 onerror="this.src='https://drive.google.com/thumbnail?id=1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT&sz=w800'"
                                 alt="Thi công nội thất trọn gói T-HOME" loading="lazy">
                        </div>
                        <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="product-box-title">Thi công nội thất &amp; Xây nhà trọn gói</h3>
                                <p class="text-[11px] sm:text-xs text-slate-500 mt-1.5 leading-relaxed">Sản xuất và lắp đặt nội thất phòng khách, bếp, phòng ngủ đồng bộ bản vẽ 3D, chìa khóa trao tay.</p>
                            </div>
                            <a href="#form-bao-gia" class="mt-3 inline-flex items-center gap-1 text-xs font-bold text-[#0f3661] hover:text-amber-600">
                                <span>Tư vấn trọn gói</span>
                                <i class="fa-solid fa-arrow-right text-[10px]"></i>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- =========================================================================
             [UX BUILDER SECTION: HÌNH ẢNH THỰC TẾ THI CÔNG XÂY DỰNG & SẢN PHẨM DỊCH VỤ]
             Lấy đủ 9 file ảnh thực tế thi công xây dựng trong Google Drive,
             đưa vào đúng danh mục và tên sản phẩm/hạng mục chuẩn.
             Chia 2 cột trên điện thoại, không để nhãn dán, tên không bị tràn hoặc thiếu chữ.
             ========================================================================= -->
        <section id="cong-trinh-thuc-te" class="section py-8 sm:py-12 bg-white">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <h2 class="section-title-normal text-base sm:text-2xl font-extrabold text-[#0f3661] uppercase">
                        <span>CÔNG TRÌNH &amp; HẠNG MỤC THI CÔNG THỰC TẾ</span>
                    </h2>
                    <p class="text-center text-xs sm:text-sm text-slate-600 mt-1">Hình ảnh thực tế thi công xây dựng và hoàn thiện của T-HOME tại công trình</p>
                </div>

                <!-- Thanh danh mục lọc nhỏ gọn, viết liền trên 1 hàng không gãy chữ -->
                <div class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-6">
                    <button type="button" onclick="filterSection('thi-cong', 'all')" data-group="thi-cong" data-filter="all" class="category-pill-btn active">Tất cả hạng mục</button>
                    <button type="button" onclick="filterSection('thi-cong', 'phan-tho')" data-group="thi-cong" data-filter="phan-tho" class="category-pill-btn">Thi công phần thô</button>
                    <button type="button" onclick="filterSection('thi-cong', 'nha-pho')" data-group="thi-cong" data-filter="nha-pho" class="category-pill-btn">Nhà phố</button>
                    <button type="button" onclick="filterSection('thi-cong', 'biet-thu')" data-group="thi-cong" data-filter="biet-thu" class="category-pill-btn">Biệt thự</button>
                    <button type="button" onclick="filterSection('thi-cong', 'khach-san-can-ho')" data-group="thi-cong" data-filter="khach-san-can-ho" class="category-pill-btn">Khách sạn – Căn hộ – Phòng trọ</button>
                    <button type="button" onclick="filterSection('thi-cong', 'noi-that')" data-group="thi-cong" data-filter="noi-that" class="category-pill-btn">Hoàn thiện &amp; Nội thất</button>
                    <button type="button" onclick="filterSection('thi-cong', 'van-phong')" data-group="thi-cong" data-filter="van-phong" class="category-pill-btn">Văn phòng</button>
                </div>

                <!-- Grid 9 ảnh thực tế thi công: 2 cột trên điện thoại (grid-cols-2), 3 cột trên máy tính (lg:grid-cols-3) -->
                <div id="grid-thi-cong" class="grid grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-5">

                    <!-- Ảnh thi công 1: 13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz -->
                    <article class="flatsome-box item-thi-cong" data-category="phan-tho nha-pho">
                        <div class="flatsome-box-image">
                            <img src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
                                 onerror="this.src='https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w800'"
                                 alt="Thi công phần thô kết cấu móng và khung bê tông cốt thép nhà phố" loading="lazy">
                        </div>
                        <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="product-box-title">Thi công phần thô kết cấu móng và khung bê tông cốt thép nhà phố</h3>
                                <p class="text-[11px] sm:text-xs text-slate-500 mt-1">Danh mục: Thi công phần thô – Nhà phố</p>
                            </div>
                        </div>
                    </article>

                    <!-- Ảnh thi công 2: 1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR -->
                    <article class="flatsome-box item-thi-cong" data-category="phan-tho biet-thu">
                        <div class="flatsome-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR"
                                 onerror="this.src='https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w800'"
                                 alt="Thi công lắp dựng cốt thép dầm sàn và đổ bê tông thương phẩm" loading="lazy">
                        </div>
                        <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="product-box-title">Thi công lắp dựng cốt thép dầm sàn và đổ bê tông thương phẩm</h3>
                                <p class="text-[11px] sm:text-xs text-slate-500 mt-1">Danh mục: Thi công phần thô – Biệt thự</p>
                            </div>
                        </div>
                    </article>

                    <!-- Ảnh thi công 3: 1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv -->
                    <article class="flatsome-box item-thi-cong" data-category="phan-tho nha-pho">
                        <div class="flatsome-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv"
                                 onerror="this.src='https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w800'"
                                 alt="Thi công xây tường bao và ngăn phòng gạch tuynel chuẩn kỹ thuật" loading="lazy">
                        </div>
                        <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="product-box-title">Thi công xây tường bao và ngăn phòng gạch tuynel chuẩn kỹ thuật</h3>
                                <p class="text-[11px] sm:text-xs text-slate-500 mt-1">Danh mục: Thi công phần thô – Nhà phố</p>
                            </div>
                        </div>
                    </article>

                    <!-- Ảnh thi công 4: 1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_ -->
                    <article class="flatsome-box item-thi-cong" data-category="phan-tho khach-san-can-ho">
                        <div class="flatsome-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_"
                                 onerror="this.src='https://drive.google.com/thumbnail?id=1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_&sz=w800'"
                                 alt="Thi công khung kết cấu công trình căn hộ và nhà phố cao tầng" loading="lazy">
                        </div>
                        <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="product-box-title">Thi công khung kết cấu công trình căn hộ và nhà phố cao tầng</h3>
                                <p class="text-[11px] sm:text-xs text-slate-500 mt-1">Danh mục: Khách sạn – Căn hộ – Phòng trọ</p>
                            </div>
                        </div>
                    </article>

                    <!-- Ảnh thi công 5: 1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO -->
                    <article class="flatsome-box item-thi-cong" data-category="nha-pho noi-that">
                        <div class="flatsome-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO"
                                 onerror="this.src='https://drive.google.com/thumbnail?id=1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO&sz=w800'"
                                 alt="Thi công tô trát tường, chống thấm và lắp đặt hệ thống điện nước âm tường" loading="lazy">
                        </div>
                        <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="product-box-title">Thi công tô trát tường, chống thấm và lắp đặt hệ thống điện nước âm tường</h3>
                                <p class="text-[11px] sm:text-xs text-slate-500 mt-1">Danh mục: Thi công hoàn thiện – Nhà phố</p>
                            </div>
                        </div>
                    </article>

                    <!-- Ảnh thi công 6: 1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t -->
                    <article class="flatsome-box item-thi-cong" data-category="nha-pho biet-thu">
                        <div class="flatsome-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t"
                                 onerror="this.src='https://drive.google.com/thumbnail?id=1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t&sz=w800'"
                                 alt="Thi công hoàn thiện mặt tiền kiến trúc nhà phố hiện đại tại Đà Nẵng" loading="lazy">
                        </div>
                        <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="product-box-title">Thi công hoàn thiện mặt tiền kiến trúc nhà phố hiện đại tại Đà Nẵng</h3>
                                <p class="text-[11px] sm:text-xs text-slate-500 mt-1">Danh mục: Thi công hoàn thiện – Nhà phố</p>
                            </div>
                        </div>
                    </article>

                    <!-- Ảnh thi công 7: 1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_ -->
                    <article class="flatsome-box item-thi-cong" data-category="biet-thu noi-that">
                        <div class="flatsome-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_"
                                 onerror="this.src='https://drive.google.com/thumbnail?id=1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_&sz=w800'"
                                 alt="Thi công ốp lát gạch đá, trần thạch cao và sơn nước hoàn thiện" loading="lazy">
                        </div>
                        <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="product-box-title">Thi công ốp lát gạch đá, trần thạch cao và sơn nước hoàn thiện</h3>
                                <p class="text-[11px] sm:text-xs text-slate-500 mt-1">Danh mục: Thi công hoàn thiện – Biệt thự</p>
                            </div>
                        </div>
                    </article>

                    <!-- Ảnh thi công 8: 1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT -->
                    <article class="flatsome-box item-thi-cong" data-category="noi-that van-phong">
                        <div class="flatsome-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT"
                                 onerror="this.src='https://drive.google.com/thumbnail?id=1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT&sz=w800'"
                                 alt="Thi công lắp đặt nội thất gỗ và không gian phòng khách – bếp hiện đại" loading="lazy">
                        </div>
                        <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="product-box-title">Thi công lắp đặt nội thất gỗ và không gian phòng khách – bếp hiện đại</h3>
                                <p class="text-[11px] sm:text-xs text-slate-500 mt-1">Danh mục: Thi công nội thất – Văn phòng &amp; Nhà ở</p>
                            </div>
                        </div>
                    </article>

                    <!-- Ảnh thi công 9: 1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn -->
                    <article class="flatsome-box item-thi-cong" data-category="nha-pho biet-thu khach-san-can-ho">
                        <div class="flatsome-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn"
                                 onerror="this.src='https://drive.google.com/thumbnail?id=1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn&sz=w800'"
                                 alt="Nghiệm thu và bàn giao công trình xây dựng trọn gói chìa khóa trao tay" loading="lazy">
                        </div>
                        <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="product-box-title">Nghiệm thu và bàn giao công trình xây dựng trọn gói chìa khóa trao tay</h3>
                                <p class="text-[11px] sm:text-xs text-slate-500 mt-1">Danh mục: Xây nhà trọn gói T-HOME</p>
                            </div>
                        </div>
                    </article>

                </div>
            </div>
        </section>

        <!-- =========================================================================
             [UX BUILDER SECTION: DANH MỤC CÁC DỰ ÁN Ở ĐÀ NẴNG]
             Lấy đủ 10 file ảnh dự án ở Đà Nẵng trong Google Drive đưa ra trang chủ.
             Chia 2 cột trên điện thoại, 5 cột trên màn hình lớn, không để nhãn dán.
             ========================================================================= -->
        <section id="du-an-da-nang" class="section py-8 sm:py-12 bg-[#f4f7fa]">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <h2 class="section-title-normal text-base sm:text-2xl font-extrabold text-[#0f3661] uppercase">
                        <span>DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG</span>
                    </h2>
                    <p class="text-center text-xs sm:text-sm text-slate-600 mt-1">Các dự án Thiết kế &amp; Thi công trọn gói của T-HOME tại Hòa Xuân, Cẩm Lệ, Hải Châu, Sơn Trà, Ngũ Hành Sơn – TP Đà Nẵng</p>
                </div>

                <!-- Danh mục lọc Dự án Đà Nẵng nhỏ gọn -->
                <div class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-6">
                    <button type="button" onclick="filterSection('du-an', 'all')" data-group="du-an" data-filter="all" class="category-pill-btn active">Tất cả dự án Đà Nẵng</button>
                    <button type="button" onclick="filterSection('du-an', 'nha-pho-dn')" data-group="du-an" data-filter="nha-pho-dn" class="category-pill-btn">Nhà phố Đà Nẵng</button>
                    <button type="button" onclick="filterSection('du-an', 'biet-thu-dn')" data-group="du-an" data-filter="biet-thu-dn" class="category-pill-btn">Biệt thự Đà Nẵng</button>
                    <button type="button" onclick="filterSection('du-an', 'can-ho-ks-dn')" data-group="du-an" data-filter="can-ho-ks-dn" class="category-pill-btn">Khách sạn – Căn hộ</button>
                    <button type="button" onclick="filterSection('du-an', 'van-phong-dn')" data-group="du-an" data-filter="van-phong-dn" class="category-pill-btn">Văn phòng – Thương mại</button>
                </div>

                <!-- Grid 10 Dự án Đà Nẵng: 2 cột trên điện thoại (grid-cols-2), 5 cột trên máy tính (lg:grid-cols-5) -->
                <div id="grid-du-an" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">

                    <!-- Dự án Đà Nẵng 1: 157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT -->
                    <article class="flatsome-box item-du-an" data-category="nha-pho-dn">
                        <div class="flatsome-box-image">
                            <img src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT"
                                 onerror="this.src='https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w800'"
                                 alt="Dự án Nhà phố hiện đại 3 tầng Khu đô thị sinh thái Hòa Xuân – Đà Nẵng" loading="lazy">
                        </div>
                        <div class="p-3 flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="product-box-title">Dự án Nhà phố hiện đại 3 tầng KĐT Hòa Xuân – Đà Nẵng</h3>
                                <p class="text-[11px] text-slate-500 mt-1">P. Hòa Xuân, TP Đà Nẵng</p>
                            </div>
                        </div>
                    </article>

                    <!-- Dự án Đà Nẵng 2: 1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff -->
                    <article class="flatsome-box item-du-an" data-category="biet-thu-dn">
                        <div class="flatsome-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff"
                                 onerror="this.src='https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w800'"
                                 alt="Dự án Biệt thự phố không gian xanh Nam Hòa Xuân – Đà Nẵng" loading="lazy">
                        </div>
                        <div class="p-3 flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="product-box-title">Dự án Biệt thự phố không gian xanh Nam Hòa Xuân – Đà Nẵng</h3>
                                <p class="text-[11px] text-slate-500 mt-1">Q. Cẩm Lệ, TP Đà Nẵng</p>
                            </div>
                        </div>
                    </article>

                    <!-- Dự án Đà Nẵng 3: 1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz -->
                    <article class="flatsome-box item-du-an" data-category="nha-pho-dn">
                        <div class="flatsome-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz"
                                 onerror="this.src='https://drive.google.com/thumbnail?id=1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz&sz=w800'"
                                 alt="Dự án Nhà phố 3 tầng 1 tum Khu Nam Việt Á – Đà Nẵng" loading="lazy">
                        </div>
                        <div class="p-3 flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="product-box-title">Dự án Nhà phố 3 tầng 1 tum Khu Nam Việt Á – Đà Nẵng</h3>
                                <p class="text-[11px] text-slate-500 mt-1">Q. Ngũ Hành Sơn, TP Đà Nẵng</p>
                            </div>
                        </div>
                    </article>

                    <!-- Dự án Đà Nẵng 4: 1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k -->
                    <article class="flatsome-box item-du-an" data-category="can-ho-ks-dn">
                        <div class="flatsome-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k"
                                 onerror="this.src='https://drive.google.com/thumbnail?id=1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k&sz=w800'"
                                 alt="Dự án Căn hộ dịch vụ cho thuê cao cấp ven biển Sơn Trà – Đà Nẵng" loading="lazy">
                        </div>
                        <div class="p-3 flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="product-box-title">Dự án Căn hộ dịch vụ cao cấp ven biển Sơn Trà – Đà Nẵng</h3>
                                <p class="text-[11px] text-slate-500 mt-1">Q. Sơn Trà, TP Đà Nẵng</p>
                            </div>
                        </div>
                    </article>

                    <!-- Dự án Đà Nẵng 5: 1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N -->
                    <article class="flatsome-box item-du-an" data-category="biet-thu-dn">
                        <div class="flatsome-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N"
                                 onerror="this.src='https://drive.google.com/thumbnail?id=1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N&sz=w800'"
                                 alt="Dự án Biệt thự 2 mặt tiền khu Euro Village – Đà Nẵng" loading="lazy">
                        </div>
                        <div class="p-3 flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="product-box-title">Dự án Biệt thự 2 mặt tiền khu Euro Village – Đà Nẵng</h3>
                                <p class="text-[11px] text-slate-500 mt-1">TP Đà Nẵng</p>
                            </div>
                        </div>
                    </article>

                    <!-- Dự án Đà Nẵng 6: 1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML -->
                    <article class="flatsome-box item-du-an" data-category="nha-pho-dn">
                        <div class="flatsome-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML"
                                 onerror="this.src='https://drive.google.com/thumbnail?id=1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML&sz=w800'"
                                 alt="Dự án Nhà phố lệch tầng thông thoáng Quận Hải Châu – Đà Nẵng" loading="lazy">
                        </div>
                        <div class="p-3 flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="product-box-title">Dự án Nhà phố lệch tầng thông thoáng Quận Hải Châu – Đà Nẵng</h3>
                                <p class="text-[11px] text-slate-500 mt-1">Q. Hải Châu, TP Đà Nẵng</p>
                            </div>
                        </div>
                    </article>

                    <!-- Dự án Đà Nẵng 7: 1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF -->
                    <article class="flatsome-box item-du-an" data-category="van-phong-dn nha-pho-dn">
                        <div class="flatsome-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF"
                                 onerror="this.src='https://drive.google.com/thumbnail?id=1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF&sz=w800'"
                                 alt="Dự án Nhà phố kết hợp Văn phòng kinh doanh Cẩm Lệ – Đà Nẵng" loading="lazy">
                        </div>
                        <div class="p-3 flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="product-box-title">Dự án Nhà phố kết hợp Văn phòng kinh doanh Cẩm Lệ – Đà Nẵng</h3>
                                <p class="text-[11px] text-slate-500 mt-1">Q. Cẩm Lệ, TP Đà Nẵng</p>
                            </div>
                        </div>
                    </article>

                    <!-- Dự án Đà Nẵng 8: 1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A -->
                    <article class="flatsome-box item-du-an" data-category="biet-thu-dn">
                        <div class="flatsome-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A"
                                 onerror="this.src='https://drive.google.com/thumbnail?id=1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A&sz=w800'"
                                 alt="Dự án Biệt thự nghỉ dưỡng sân vườn Hòa Quý – Đà Nẵng" loading="lazy">
                        </div>
                        <div class="p-3 flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="product-box-title">Dự án Biệt thự nghỉ dưỡng sân vườn Hòa Quý – Đà Nẵng</h3>
                                <p class="text-[11px] text-slate-500 mt-1">Q. Ngũ Hành Sơn, TP Đà Nẵng</p>
                            </div>
                        </div>
                    </article>

                    <!-- Dự án Đà Nẵng 9: 1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80 -->
                    <article class="flatsome-box item-du-an" data-category="nha-pho-dn">
                        <div class="flatsome-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80"
                                 onerror="this.src='https://drive.google.com/thumbnail?id=1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80&sz=w800'"
                                 alt="Dự án Nhà phố mặt tiền Võ Quảng – Hòa Xuân – Đà Nẵng" loading="lazy">
                        </div>
                        <div class="p-3 flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="product-box-title">Dự án Nhà phố mặt tiền Hòa Xuân – Cẩm Lệ – Đà Nẵng</h3>
                                <p class="text-[11px] text-slate-500 mt-1">P. Hòa Xuân, TP Đà Nẵng</p>
                            </div>
                        </div>
                    </article>

                    <!-- Dự án Đà Nẵng 10: 1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4 -->
                    <article class="flatsome-box item-du-an" data-category="can-ho-ks-dn van-phong-dn">
                        <div class="flatsome-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4"
                                 onerror="this.src='https://drive.google.com/thumbnail?id=1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4&sz=w800'"
                                 alt="Dự án Tổ hợp Căn hộ & Văn phòng hiện đại Thanh Khê – Đà Nẵng" loading="lazy">
                        </div>
                        <div class="p-3 flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="product-box-title">Dự án Tổ hợp Căn hộ &amp; Văn phòng hiện đại Thanh Khê – Đà Nẵng</h3>
                                <p class="text-[11px] text-slate-500 mt-1">Q. Thanh Khê, TP Đà Nẵng</p>
                            </div>
                        </div>
                    </article>

                </div>
            </div>
        </section>

        <!-- =========================================================================
             [UX BUILDER SECTION: BẢNG BÁO GIÁ THIẾT KẾ & THI CÔNG (Chuẩn mẫu tintruongthinh.com)]
             Chia 2 cột trên điện thoại, 4 cột trên máy tính
             ========================================================================= -->
        <section id="bao-gia" class="section py-8 sm:py-12 bg-white">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <h2 class="section-title-normal text-base sm:text-2xl font-extrabold text-[#0f3661] uppercase">
                        <span>BÁO GIÁ THIẾT KẾ &amp; THI CÔNG T-HOME</span>
                    </h2>
                    <p class="text-center text-xs sm:text-sm text-slate-600 mt-1">Hoàn trả 100% chi phí thiết kế khi ký hợp đồng thi công xây dựng trọn gói</p>
                </div>

                <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
                <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                    <div class="rounded-xl border border-slate-200 bg-slate-50 p-3.5 sm:p-5 flex flex-col justify-between">
                        <div>
                            <h3 class="product-box-title text-[#0f3661]">Báo giá Thiết kế Kiến trúc</h3>
                            <p class="text-base sm:text-xl font-extrabold text-amber-600 my-2">99.000đ – 250.000đ/m²</p>
                            <ul class="text-[11px] sm:text-xs text-slate-600 space-y-1.5">
                                <li>• Hồ sơ thiết kế Kiến trúc chi tiết</li>
                                <li>• Hồ sơ chi tiết Kết cấu &amp; Điện nước</li>
                                <li>• Phối cảnh 3D ngoại thất &amp; nội thất</li>
                                <li>• Hỗ trợ hồ sơ xin phép xây dựng</li>
                            </ul>
                        </div>
                        <a href="#form-bao-gia" class="mt-4 block text-center py-2 px-3 rounded-lg bg-[#0f3661] hover:bg-amber-600 text-white text-xs font-bold transition">Nhận báo giá</a>
                    </div>

                    <div class="rounded-xl border border-slate-200 bg-slate-50 p-3.5 sm:p-5 flex flex-col justify-between">
                        <div>
                            <h3 class="product-box-title text-[#0f3661]">Báo giá Thi công Phần thô</h3>
                            <p class="text-base sm:text-xl font-extrabold text-amber-600 my-2">3.500.000đ – 3.900.000đ/m²</p>
                            <ul class="text-[11px] sm:text-xs text-slate-600 space-y-1.5">
                                <li>• Vật tư chuẩn chính hãng Hòa Phát, Việt Úc</li>
                                <li>• Thi công móng, cột, dầm, sàn, xây tô</li>
                                <li>• Nhân công hoàn thiện điện nước</li>
                                <li>• Giám sát kỹ thuật trực tiếp tại công trình</li>
                            </ul>
                        </div>
                        <a href="#form-bao-gia" class="mt-4 block text-center py-2 px-3 rounded-lg bg-[#0f3661] hover:bg-amber-600 text-white text-xs font-bold transition">Nhận báo giá</a>
                    </div>

                    <div class="rounded-xl border border-slate-200 bg-slate-50 p-3.5 sm:p-5 flex flex-col justify-between">
                        <div>
                            <h3 class="product-box-title text-[#0f3661]">Báo giá Thi công Hoàn thiện</h3>
                            <p class="text-base sm:text-xl font-extrabold text-amber-600 my-2">2.200.000đ – 3.200.000đ/m²</p>
                            <ul class="text-[11px] sm:text-xs text-slate-600 space-y-1.5">
                                <li>• Ốp lát gạch nền, gạch tường, đá cầu thang</li>
                                <li>• Trần thạch cao, sơn nước Dulux/Jotun</li>
                                <li>• Cửa nhôm kính Xingfa, lan can, thiết bị vệ sinh</li>
                                <li>• Cam kết đúng chủng loại vật tư hợp đồng</li>
                            </ul>
                        </div>
                        <a href="#form-bao-gia" class="mt-4 block text-center py-2 px-3 rounded-lg bg-[#0f3661] hover:bg-amber-600 text-white text-xs font-bold transition">Nhận báo giá</a>
                    </div>

                    <div class="rounded-xl border border-slate-200 bg-slate-50 p-3.5 sm:p-5 flex flex-col justify-between">
                        <div>
                            <h3 class="product-box-title text-[#0f3661]">Báo giá Xây nhà Trọn gói</h3>
                            <p class="text-base sm:text-xl font-extrabold text-amber-600 my-2">5.600.000đ – 7.500.000đ/m²</p>
                            <ul class="text-[11px] sm:text-xs text-slate-600 space-y-1.5">
                                <li>• Miễn phí 100% thiết kế &amp; xin phép XD</li>
                                <li>• Bao gồm toàn bộ phần thô &amp; hoàn thiện</li>
                                <li>• Không phát sinh chi phí ngoài hợp đồng</li>
                                <li>• Bàn giao chìa khóa trao tay đúng tiến độ</li>
                            </ul>
                        </div>
                        <a href="#form-bao-gia" class="mt-4 block text-center py-2 px-3 rounded-lg bg-[#0f3661] hover:bg-amber-600 text-white text-xs font-bold transition">Nhận báo giá</a>
                    </div>
                </div>
            </div>
        </section>

        <!-- =========================================================================
             [UX BUILDER SECTION: FORM YÊU CẦU TƯ VẤN VÀ BÁO GIÁ TRANG CHỦ]
             Đầy đủ các trường giống web mẫu tintruongthinh.com
             ========================================================================= -->
        <section id="form-bao-gia" class="section py-8 sm:py-12 bg-[#0f3661] text-white">
            <div class="flatsome-container">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 sm:gap-8 items-center">
                    <div class="lg:col-span-5">
                        <span class="text-amber-400 text-xs font-bold uppercase tracking-wider">Hỗ trợ nhanh chóng 24/7</span>
                        <h2 class="text-xl sm:text-3xl font-extrabold mt-1 mb-3">ĐĂNG KÝ YÊU CẦU TƯ VẤN &amp; NHẬN BÁO GIÁ MIỄN PHÍ</h2>
                        <p class="text-xs sm:text-sm text-slate-200 leading-relaxed mb-5">
                            Quý khách hàng vui lòng để lại thông tin công trình, đội ngũ Kiến trúc sư &amp; Kỹ sư trưởng của <strong>CÔNG TY CỔ PHẦN XÂY DỰNG VÀ THƯƠNG MẠI T-HOME</strong> sẽ liên hệ tư vấn phương án mặt bằng và gửi bảng dự toán chi tiết.
                        </p>
                        <div class="space-y-3 text-xs sm:text-sm bg-white/10 p-4 rounded-xl border border-white/15">
                            <div class="flex items-center gap-2.5">
                                <i class="fa-solid fa-phone-volume text-amber-400 text-base"></i>
                                <span>Hotline trực tiếp: <strong class="text-amber-300">0905.436.426</strong></span>
                            </div>
                            <div class="flex items-start gap-2.5">
                                <i class="fa-solid fa-location-dot text-amber-400 text-base mt-0.5"></i>
                                <span>Văn phòng: <strong>07 - 09 Võ Quảng, Phường Hòa Xuân, TP Đà Nẵng</strong></span>
                            </div>
                            <div class="flex items-center gap-2.5">
                                <i class="fa-brands fa-facebook text-amber-400 text-base"></i>
                                <span>Fanpage: <strong>facebook.com/THIETKE.THICONG.THOME</strong></span>
                            </div>
                        </div>
                    </div>

                    <div class="lg:col-span-7">
                        <form id="quote-request-form" onsubmit="handleQuoteSubmit(event)" class="bg-white text-slate-800 rounded-2xl p-5 sm:p-7 shadow-xl">
                            <h3 class="text-base sm:text-lg font-extrabold text-[#0f3661] uppercase mb-4">MIỄN PHÍ TƯ VẤN &amp; KHẢO SÁT BÁO GIÁ</h3>
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                                <div>
                                    <label for="customer-name" class="block text-xs font-bold text-slate-700 mb-1">Họ và tên *</label>
                                    <input id="customer-name" type="text" required placeholder="Nhập họ tên của quý khách" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-xs sm:text-sm focus:outline-none focus:border-[#0f3661]">
                                </div>
                                <div>
                                    <label for="customer-phone" class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại *</label>
                                    <input id="customer-phone" type="tel" required placeholder="Ví dụ: 0905 436 426" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-xs sm:text-sm focus:outline-none focus:border-[#0f3661]">
                                </div>
                                <div>
                                    <label for="project-type" class="block text-xs font-bold text-slate-700 mb-1">Loại công trình</label>
                                    <select id="project-type" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-xs sm:text-sm bg-white focus:outline-none focus:border-[#0f3661]">
                                        <option value="Nhà phố">Nhà phố</option>
                                        <option value="Biệt thự">Biệt thự</option>
                                        <option value="Khách sạn – Căn hộ cho thuê – Phòng trọ">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                                        <option value="Văn phòng">Văn phòng</option>
                                        <option value="Cải tạo sửa chữa & Nội thất">Cải tạo sửa chữa &amp; Nội thất</option>
                                    </select>
                                </div>
                                <div>
                                    <label for="budget-level" class="block text-xs font-bold text-slate-700 mb-1">Mức đầu tư dự kiến</label>
                                    <select id="budget-level" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-xs sm:text-sm bg-white focus:outline-none focus:border-[#0f3661]">
                                        <option value="Từ 1 - 2 tỷ">Từ 1 - 2 tỷ</option>
                                        <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                                        <option value="Từ 500 triệu - 1 tỷ">Từ 500 triệu - 1 tỷ</option>
                                        <option value="Từ 2 - 3 tỷ">Từ 2 - 3 tỷ</option>
                                        <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                    </select>
                                </div>
                                <div>
                                    <label for="customer-email" class="block text-xs font-bold text-slate-700 mb-1">Email (nếu có)</label>
                                    <input id="customer-email" type="email" placeholder="Nhập địa chỉ email" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-xs sm:text-sm focus:outline-none focus:border-[#0f3661]">
                                </div>
                                <div>
                                    <label for="project-area" class="block text-xs font-bold text-slate-700 mb-1">Diện tích đất / Số tầng dự kiến</label>
                                    <input id="project-area" type="text" placeholder="Ví dụ: 5x20m, 3 tầng tại Hòa Xuân" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-xs sm:text-sm focus:outline-none focus:border-[#0f3661]">
                                </div>
                                <div class="sm:col-span-2">
                                    <label for="customer-note" class="block text-xs font-bold text-slate-700 mb-1">Nội dung yêu cầu chi tiết</label>
                                    <textarea id="customer-note" rows="2" placeholder="Nhập nhu cầu thiết kế, thi công phần thô hoặc xây nhà trọn gói..." class="w-full px-3.5 py-2 rounded-lg border border-slate-300 text-xs sm:text-sm focus:outline-none focus:border-[#0f3661]"></textarea>
                                </div>
                            </div>
                            <button type="submit" class="mt-4 w-full py-3 px-5 rounded-lg bg-amber-500 hover:bg-amber-600 text-slate-950 font-extrabold text-xs sm:text-sm uppercase tracking-wide transition shadow-md">
                                <i class="fa-solid fa-paper-plane mr-1.5"></i> GỬI YÊU CẦU NHẬN BÁO GIÁ NGAY
                            </button>
                            <div id="quote-form-feedback" class="hidden mt-3 p-3 rounded-lg bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs font-semibold"></div>
                        </form>
                    </div>
                </div>
            </div>
        </section>

        <!-- =========================================================================
             [UX BUILDER SECTION: DANH MỤC CÁC BÀI VIẾT / TIN TỨC TRANG CHỦ]
             Chia 2 cột trên điện thoại, 4 cột trên máy tính (Giống web mẫu tintruongthinh.com)
             ========================================================================= -->
        <section id="tin-tuc" class="section py-8 sm:py-12 bg-white">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <h2 class="section-title-normal text-base sm:text-2xl font-extrabold text-[#0f3661] uppercase">
                        <span>TIN TỨC &amp; KINH NGHIỆM XÂY DỰNG</span>
                    </h2>
                    <p class="text-center text-xs sm:text-sm text-slate-600 mt-1">Cập nhật kiến thức thiết kế kiến trúc, kỹ thuật thi công và cẩm nang xây nhà tại Đà Nẵng</p>
                </div>

                <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
                <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                    <article class="flatsome-box">
                        <div class="flatsome-box-image">
                            <img src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
                                 onerror="this.src='https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w600'"
                                 alt="Hướng dẫn bảo dưỡng bê tông móng và sàn đúng kỹ thuật" loading="lazy">
                        </div>
                        <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="product-box-title">Hướng dẫn bảo dưỡng bê tông móng và dầm sàn đúng cách trong xây dựng</h3>
                                <p class="text-[11px] sm:text-xs text-slate-500 mt-1.5 leading-relaxed">Quy trình giữ ẩm và bảo dưỡng bê tông cốt thép giúp kết cấu công trình đạt cường độ tối đa, chống nứt sàn.</p>
                            </div>
                            <span class="mt-2.5 text-[11px] font-bold text-[#0f3661]">Kỹ thuật thi công • T-HOME</span>
                        </div>
                    </article>

                    <article class="flatsome-box">
                        <div class="flatsome-box-image">
                            <img src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT"
                                 onerror="this.src='https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w600'"
                                 alt="03 Nỗi lo lớn nhất khi xây nhà mà chủ đầu tư thường gặp phải" loading="lazy">
                        </div>
                        <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="product-box-title">03 Nỗi lo lớn nhất khi xây nhà mà Chủ đầu tư đều cần biết để phòng tránh</h3>
                                <p class="text-[11px] sm:text-xs text-slate-500 mt-1.5 leading-relaxed">Giải pháp kiểm soát ngân sách không phát sinh, đảm bảo tiến độ và lựa chọn vật tư chính hãng tại Đà Nẵng.</p>
                            </div>
                            <span class="mt-2.5 text-[11px] font-bold text-[#0f3661]">Cẩm nang xây nhà • T-HOME</span>
                        </div>
                    </article>

                    <article class="flatsome-box">
                        <div class="flatsome-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT"
                                 onerror="this.src='https://drive.google.com/thumbnail?id=1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT&sz=w600'"
                                 alt="Tâm lý học không gian và tầm quan trọng của thiết kế nội thất" loading="lazy">
                        </div>
                        <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="product-box-title">Tâm lý học không gian: Thiết kế kiến trúc &amp; nội thất tác động đến tổ ấm thế nào?</h3>
                                <p class="text-[11px] sm:text-xs text-slate-500 mt-1.5 leading-relaxed">Cách bố trí ánh sáng tự nhiên, thông gió giếng trời và vật liệu nội thất mang lại năng lượng tích cực.</p>
                            </div>
                            <span class="mt-2.5 text-[11px] font-bold text-[#0f3661]">Kiến trúc &amp; Nội thất • T-HOME</span>
                        </div>
                    </article>

                    <article class="flatsome-box">
                        <div class="flatsome-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80"
                                 onerror="this.src='https://drive.google.com/thumbnail?id=1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80&sz=w600'"
                                 alt="Thủ tục xin giấy phép xây dựng nhà ở tại TP Đà Nẵng" loading="lazy">
                        </div>
                        <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="product-box-title">Kinh nghiệm xin giấy phép xây dựng và quy chuẩn chiều cao tầng tại Đà Nẵng</h3>
                                <p class="text-[11px] sm:text-xs text-slate-500 mt-1.5 leading-relaxed">Tổng hợp hồ sơ pháp lý cần chuẩn bị trước khi khởi công xây dựng nhà phố, biệt thự tại TP Đà Nẵng.</p>
                            </div>
                            <span class="mt-2.5 text-[11px] font-bold text-[#0f3661]">Pháp lý xây dựng • T-HOME</span>
                        </div>
                    </article>
                </div>
            </div>
        </section>

        <!-- =========================================================================
             [UX BUILDER SECTION: DANH MỤC CÁC ĐỐI TÁC]
             Các đối tác cung ứng vật tư & thiết bị xây dựng chính hãng của T-HOME
             ========================================================================= -->
        <section id="doi-tac" class="section py-8 sm:py-10 bg-[#f4f7fa]">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <h2 class="section-title-normal text-base sm:text-2xl font-extrabold text-[#0f3661] uppercase">
                        <span>ĐỐI TÁC ĐỒNG HÀNH CÙNG T-HOME</span>
                    </h2>
                    <p class="text-center text-xs sm:text-sm text-slate-600 mt-1">Cam kết sử dụng vật tư xây dựng và trang thiết bị hoàn thiện chính hãng 100%</p>
                </div>

                <!-- Chia 2 cột trên điện thoại, 5 cột trên máy tính -->
                <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
                    <div class="bg-white rounded-xl p-3.5 border border-slate-200 text-center flex flex-col items-center justify-center shadow-2xs">
                        <span class="text-sm sm:text-base font-extrabold text-[#0f3661]">THÉP HÒA PHÁT</span>
                        <span class="text-[11px] text-slate-500 mt-0.5">Đối tác Thép xây dựng</span>
                    </div>
                    <div class="bg-white rounded-xl p-3.5 border border-slate-200 text-center flex flex-col items-center justify-center shadow-2xs">
                        <span class="text-sm sm:text-base font-extrabold text-[#0f3661]">SƠN DULUX &amp; JOTUN</span>
                        <span class="text-[11px] text-slate-500 mt-0.5">Đối tác Sơn hoàn thiện</span>
                    </div>
                    <div class="bg-white rounded-xl p-3.5 border border-slate-200 text-center flex flex-col items-center justify-center shadow-2xs">
                        <span class="text-sm sm:text-base font-extrabold text-[#0f3661]">GẠCH ĐỒNG TÂM</span>
                        <span class="text-[11px] text-slate-500 mt-0.5">Gạch ốp lát &amp; Vật liệu</span>
                    </div>
                    <div class="bg-white rounded-xl p-3.5 border border-slate-200 text-center flex flex-col items-center justify-center shadow-2xs">
                        <span class="text-sm sm:text-base font-extrabold text-[#0f3661]">TOTO &amp; INAX</span>
                        <span class="text-[11px] text-slate-500 mt-0.5">Thiết bị vệ sinh cao cấp</span>
                    </div>
                    <div class="bg-white rounded-xl p-3.5 border border-slate-200 text-center flex flex-col items-center justify-center shadow-2xs">
                        <span class="text-sm sm:text-base font-extrabold text-[#0f3661]">GỖ AN CƯỜNG</span>
                        <span class="text-[11px] text-slate-500 mt-0.5">Vật liệu Nội thất cao cấp</span>
                    </div>
                    <div class="bg-white rounded-xl p-3.5 border border-slate-200 text-center flex flex-col items-center justify-center shadow-2xs">
                        <span class="text-sm sm:text-base font-extrabold text-[#0f3661]">NHÔM XINGFA</span>
                        <span class="text-[11px] text-slate-500 mt-0.5">Hệ cửa nhôm kính</span>
                    </div>
                    <div class="bg-white rounded-xl p-3.5 border border-slate-200 text-center flex flex-col items-center justify-center shadow-2xs">
                        <span class="text-sm sm:text-base font-extrabold text-[#0f3661]">PANASONIC &amp; SINO</span>
                        <span class="text-[11px] text-slate-500 mt-0.5">Thiết bị điện công trình</span>
                    </div>
                    <div class="bg-white rounded-xl p-3.5 border border-slate-200 text-center flex flex-col items-center justify-center shadow-2xs">
                        <span class="text-sm sm:text-base font-extrabold text-[#0f3661]">NHỰA BÌNH MINH</span>
                        <span class="text-[11px] text-slate-500 mt-0.5">Hệ thống cấp thoát nước</span>
                    </div>
                    <div class="bg-white rounded-xl p-3.5 border border-slate-200 text-center flex flex-col items-center justify-center shadow-2xs">
                        <span class="text-sm sm:text-base font-extrabold text-[#0f3661]">XI MĂNG KIM ĐỈNH</span>
                        <span class="text-[11px] text-slate-500 mt-0.5">Vật tư kết cấu phần thô</span>
                    </div>
                    <div class="bg-white rounded-xl p-3.5 border border-slate-200 text-center flex flex-col items-center justify-center shadow-2xs">
                        <span class="text-sm sm:text-base font-extrabold text-[#0f3661]">SƠN CHỐNG THẤM SIKA</span>
                        <span class="text-[11px] text-slate-500 mt-0.5">Hóa chất chống thấm</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- =========================================================================
             [UX BUILDER SECTION: ĐƯA FANPAGE & GOOGLE MAP RA NGOÀI TRANG CHỦ]
             - Fanpage: https://www.facebook.com/THIETKE.THICONG.THOME
             - Địa chỉ: 07 - 09 Võ Quảng, Phường Hòa Xuân, TP Đà Nẵng
             - Link Google Map: https://share.google/VXhkB2cKd2KSKHH9x
             ========================================================================= -->
        <section id="lien-he" class="section py-8 sm:py-12 bg-white border-t border-slate-200">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <h2 class="section-title-normal text-base sm:text-2xl font-extrabold text-[#0f3661] uppercase">
                        <span>KẾT NỐI FANPAGE &amp; BẢN ĐỒ CHỈ ĐƯỜNG T-HOME</span>
                    </h2>
                    <p class="text-center text-xs sm:text-sm text-slate-600 mt-1">Trụ sở: 07 - 09 Võ Quảng, Phường Hòa Xuân, TP Đà Nẵng | Hotline: 0905.436.426</p>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6">

                    <!-- Cột 1: Đưa Fanpage ra ngoài trang chủ -->
                    <div class="lg:col-span-5 bg-slate-50 rounded-2xl p-4 sm:p-5 border border-slate-200 flex flex-col justify-between">
                        <div>
                            <div class="flex items-center justify-between gap-2 mb-3">
                                <h3 class="text-sm sm:text-base font-extrabold text-[#0f3661] flex items-center gap-2">
                                    <i class="fa-brands fa-facebook text-blue-600 text-lg"></i>
                                    <span>FANPAGE CHÍNH THỨC T-HOME</span>
                                </h3>
                                <a href="https://www.facebook.com/THIETKE.THICONG.THOME" target="_blank" rel="noopener noreferrer" class="text-xs font-bold text-blue-600 hover:underline">
                                    Mở Facebook <i class="fa-solid fa-up-right-from-square text-[10px]"></i>
                                </a>
                            </div>

                            <!-- Card trực quan Fanpage T-HOME + Plugin nhúng Facebook -->
                            <div class="rounded-xl overflow-hidden border border-slate-200 bg-white mb-3">
                                <div class="p-3 flex items-center gap-3 bg-gradient-to-r from-[#0f3661] to-[#1a4f8b] text-white">
                                    <img src="https://lh3.googleusercontent.com/d/1WmBHNuO5MCo30s7j5KGrl0qpdOxtVywJ"
                                         onerror="this.src='https://drive.google.com/thumbnail?id=1WmBHNuO5MCo30s7j5KGrl0qpdOxtVywJ&sz=w200'"
                                         alt="Logo Fanpage T-HOME" class="w-11 h-11 rounded-lg bg-white p-0.5 object-contain shrink-0">
                                    <div class="min-w-0">
                                        <a href="https://www.facebook.com/THIETKE.THICONG.THOME" target="_blank" rel="noopener noreferrer" class="font-bold text-xs sm:text-sm hover:underline block truncate">
                                            CÔNG TY CỔ PHẦN XÂY DỰNG VÀ THƯƠNG MẠI T-HOME
                                        </a>
                                        <span class="text-[11px] text-amber-300 block">@THIETKE.THICONG.THOME • Thiết kế &amp; Thi công</span>
                                    </div>
                                </div>
                                <div class="w-full overflow-hidden flex justify-center bg-white">
                                    <iframe
                                        title="Fanpage Thiết Kế Thi Công T-HOME"
                                        src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2FTHIETKE.THICONG.THOME&tabs=timeline&width=380&height=280&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true"
                                        width="380"
                                        height="280"
                                        style="border:none;overflow:hidden;max-width:100%;"
                                        scrolling="no"
                                        frameborder="0"
                                        allowfullscreen="true"
                                        allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                                    </iframe>
                                </div>
                            </div>
                        </div>

                        <a href="https://www.facebook.com/THIETKE.THICONG.THOME" target="_blank" rel="noopener noreferrer" class="w-full py-2.5 px-4 rounded-lg bg-blue-600 hover:bg-blue-700 text-white font-bold text-xs sm:text-sm text-center flex items-center justify-center gap-2 transition">
                            <i class="fa-brands fa-facebook-messenger"></i>
                            <span>THEO DÕI &amp; NHẮN TIN QUA FANPAGE T-HOME</span>
                        </a>
                    </div>

                    <!-- Cột 2: Đưa ảnh Google Map & Bản đồ tương tác ra ngoài trang chủ -->
                    <div class="lg:col-span-7 bg-slate-50 rounded-2xl p-4 sm:p-5 border border-slate-200 flex flex-col justify-between">
                        <div>
                            <div class="flex flex-wrap items-center justify-between gap-2 mb-3">
                                <h3 class="text-sm sm:text-base font-extrabold text-[#0f3661] flex items-center gap-2">
                                    <i class="fa-solid fa-map-location-dot text-red-600 text-lg"></i>
                                    <span>BẢN ĐỒ GOOGLE MAP: 07 - 09 VÕ QUẢNG, HÒA XUÂN, ĐÀ NẴNG</span>
                                </h3>
                                <a href="https://share.google/VXhkB2cKd2KSKHH9x" target="_blank" rel="noopener noreferrer" class="text-xs font-bold text-red-600 hover:underline">
                                    Mở Google Maps <i class="fa-solid fa-location-arrow text-[10px]"></i>
                                </a>
                            </div>

                            <!-- Bản đồ Google Map trực tiếp + Hình ảnh sơ đồ vị trí 07 - 09 Võ Quảng -->
                            <div class="rounded-xl overflow-hidden border border-slate-200 bg-white mb-3">
                                <iframe
                                    title="Google Map 07 - 09 Võ Quảng, Phường Hòa Xuân, TP Đà Nẵng"
                                    src="https://maps.google.com/maps?q=07+V%C3%B5+Qu%E1%BA%A3ng,+H%C3%B2a+Xu%C3%A2n,+C%E1%BA%A9m+L%E1%BB%87,+%C4%90%C3%A0+N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                                    class="w-full h-60 sm:h-72 border-0 block"
                                    loading="lazy"
                                    referrerpolicy="no-referrer-when-downgrade">
                                </iframe>
                                <a href="https://share.google/VXhkB2cKd2KSKHH9x" target="_blank" rel="noopener noreferrer" class="block p-3 bg-white hover:bg-amber-50 border-t border-slate-200 transition">
                                    <div class="flex items-center justify-between gap-3">
                                        <div class="flex items-center gap-2.5">
                                            <div class="w-9 h-9 rounded-lg bg-red-100 text-red-600 flex items-center justify-center shrink-0">
                                                <i class="fa-solid fa-location-dot text-lg"></i>
                                            </div>
                                            <div>
                                                <p class="text-xs sm:text-sm font-extrabold text-[#0f3661]">CÔNG TY CỔ PHẦN XÂY DỰNG VÀ THƯƠNG MẠI T-HOME</p>
                                                <p class="text-[11px] sm:text-xs text-slate-600">Địa chỉ: 07 - 09 Võ Quảng, Phường Hòa Xuân, TP Đà Nẵng</p>
                                            </div>
                                        </div>
                                        <span class="px-3 py-1.5 rounded-lg bg-[#0f3661] text-white text-xs font-bold shrink-0">Chỉ đường</span>
                                    </div>
                                </a>
                            </div>
                        </div>

                        <a href="https://share.google/VXhkB2cKd2KSKHH9x" target="_blank" rel="noopener noreferrer" class="w-full py-2.5 px-4 rounded-lg bg-[#0f3661] hover:bg-amber-600 text-white font-bold text-xs sm:text-sm text-center flex items-center justify-center gap-2 transition">
                            <i class="fa-solid fa-diamond-turn-right"></i>
                            <span>XEM VỊ TRÍ TRÊN GOOGLE MAPS (07 - 09 VÕ QUẢNG, HÒA XUÂN)</span>
                        </a>
                    </div>

                </div>
            </div>
        </section>

    </main>

    <!-- =========================================================================
         FOOTER: Chuẩn cấu trúc Flatsome UX Builder
         ========================================================================= -->
    <footer class="bg-[#09223f] text-slate-200 pt-10 pb-20 lg:pb-8 border-t-4 border-amber-500">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-8 pb-8 border-b border-white/10">

                <!-- Cột 1: Thông tin công ty -->
                <div class="lg:col-span-5">
                    <div class="flex items-center gap-3 mb-3">
                        <img src="https://lh3.googleusercontent.com/d/1WmBHNuO5MCo30s7j5KGrl0qpdOxtVywJ"
                             onerror="this.src='https://drive.google.com/thumbnail?id=1WmBHNuO5MCo30s7j5KGrl0qpdOxtVywJ&sz=w200'"
                             alt="Logo T-HOME" class="w-11 h-11 rounded-lg bg-white p-1 object-contain">
                        <div>
                            <h3 class="text-sm sm:text-base font-extrabold text-white">CÔNG TY CỔ PHẦN XÂY DỰNG VÀ THƯƠNG MẠI T-HOME</h3>
                            <span class="text-xs text-amber-400 font-semibold">Website: thome.com</span>
                        </div>
                    </div>
                    <ul class="space-y-2 text-xs sm:text-sm text-slate-300">
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-location-dot text-amber-400 mt-1"></i>
                            <span><strong>Trụ sở:</strong> 07 - 09 Võ Quảng, Phường Hòa Xuân, TP Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-phone text-amber-400"></i>
                            <span><strong>Hotline/Zalo:</strong> <a href="tel:0905436426" class="text-amber-300 font-bold hover:underline">0905.436.426</a></span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-brands fa-facebook text-amber-400"></i>
                            <span><strong>Fanpage:</strong> <a href="https://www.facebook.com/THIETKE.THICONG.THOME" target="_blank" rel="noopener noreferrer" class="hover:text-white underline">facebook.com/THIETKE.THICONG.THOME</a></span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-map-pin text-amber-400"></i>
                            <span><strong>Google Map:</strong> <a href="https://share.google/VXhkB2cKd2KSKHH9x" target="_blank" rel="noopener noreferrer" class="hover:text-white underline">Xem bản đồ chỉ đường</a></span>
                        </li>
                    </ul>
                </div>

                <!-- Cột 2: Lĩnh vực hoạt động -->
                <div class="lg:col-span-3">
                    <h4 class="text-sm font-extrabold text-amber-400 uppercase mb-3">LĨNH VỰC HOẠT ĐỘNG</h4>
                    <ul class="space-y-2 text-xs sm:text-sm">
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-300">• Thiết kế Kiến trúc – Nội thất</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-300">• Thi công phần thô</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-300">• Thi công hoàn thiện</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-300">• Thi công nội thất trọn gói</a></li>
                        <li><a href="#du-an-da-nang" class="hover:text-amber-300">• Các dự án tiêu biểu tại Đà Nẵng</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Danh mục công trình & Báo giá -->
                <div class="lg:col-span-4">
                    <h4 class="text-sm font-extrabold text-amber-400 uppercase mb-3">DANH MỤC &amp; BÁO GIÁ</h4>
                    <div class="grid grid-cols-2 gap-2 text-xs sm:text-sm">
                        <a href="#cong-trinh-thuc-te" class="hover:text-amber-300">• Nhà phố hiện đại</a>
                        <a href="#bao-gia" class="hover:text-amber-300">• Báo giá thiết kế</a>
                        <a href="#cong-trinh-thuc-te" class="hover:text-amber-300">• Biệt thự sân vườn</a>
                        <a href="#bao-gia" class="hover:text-amber-300">• Báo giá phần thô</a>
                        <a href="#cong-trinh-thuc-te" class="hover:text-amber-300">• Khách sạn – Căn hộ</a>
                        <a href="#bao-gia" class="hover:text-amber-300">• Báo giá hoàn thiện</a>
                        <a href="#cong-trinh-thuc-te" class="hover:text-amber-300">• Văn phòng</a>
                        <a href="#bao-gia" class="hover:text-amber-300">• Báo giá trọn gói</a>
                    </div>
                </div>

            </div>

            <div class="pt-5 flex flex-wrap items-center justify-between gap-2 text-xs text-slate-400">
                <p>Copyright 2026 © <strong>CÔNG TY CỔ PHẦN XÂY DỰNG VÀ THƯƠNG MẠI T-HOME (thome.com)</strong>. All rights reserved.</p>
                <p>Địa chỉ: 07 - 09 Võ Quảng, Phường Hòa Xuân, TP Đà Nẵng | SĐT: 0905.436.426</p>
            </div>
        </div>
    </footer>

    <!-- =========================================================================
         CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE
         Tương thích hoàn hảo trên cả máy tính và điện thoại, không gây tràn viền
         ========================================================================= -->
    <div class="fixed bottom-4 right-3 sm:right-5 z-50 flex flex-col items-end gap-2.5">
        <!-- Nút Facebook Fanpage -->
        <a href="https://www.facebook.com/THIETKE.THICONG.THOME" target="_blank" rel="noopener noreferrer"
           aria-label="Chat Facebook T-HOME"
           class="flex items-center gap-2 px-3 py-2 sm:px-3.5 sm:py-2.5 rounded-full bg-[#1877F2] hover:bg-blue-700 text-white shadow-lg transition transform hover:scale-105">
            <i class="fa-brands fa-facebook-f text-sm sm:text-base w-4 text-center"></i>
            <span class="text-xs font-bold">Facebook</span>
        </a>

        <!-- Nút Liên hệ Zalo -->
        <a href="https://zalo.me/0905436426" target="_blank" rel="noopener noreferrer"
           aria-label="Chat Zalo 0905.436.426"
           class="flex items-center gap-2 px-3 py-2 sm:px-3.5 sm:py-2.5 rounded-full bg-[#0068FF] hover:bg-blue-600 text-white shadow-lg transition transform hover:scale-105">
            <span class="w-4 h-4 rounded-full bg-white text-[#0068FF] font-black text-[10px] flex items-center justify-center">Z</span>
            <span class="text-xs font-bold">Chat Zalo</span>
        </a>

        <!-- Nút Hotline nổi bật -->
        <a href="tel:0905436426"
           aria-label="Gọi Hotline 0905.436.426"
           class="floating-btn-pulse flex items-center gap-2 px-3.5 py-2.5 sm:px-4 sm:py-3 rounded-full bg-amber-500 hover:bg-amber-600 text-slate-950 shadow-xl transition transform hover:scale-105">
            <i class="fa-solid fa-phone-volume text-sm sm:text-base"></i>
            <span class="text-xs sm:text-sm font-extrabold">0905.436.426</span>
        </a>
    </div>

    <!-- =========================================================================
         JAVASCRIPT XỬ LÝ SLIDER TỰ TRƯỢT, BỘ LỌC DANH MỤC & FORM BÁO GIÁ
         ========================================================================= -->
    <script>
        // 1. Điều khiển 2 ảnh Banner tự trượt chuyên nghiệp
        let currentBannerIndex = 0;
        const totalBanners = 2;
        let bannerInterval = null;

        function updateBannerPosition() {
            const track = document.getElementById('banner-track');
            const dot0 = document.getElementById('slider-dot-0');
            const dot1 = document.getElementById('slider-dot-1');
            if (!track) return;

            track.style.transform = 'translateX(-' + (currentBannerIndex * 100) + '%)';

            if (dot0 && dot1) {
                if (currentBannerIndex === 0) {
                    dot0.className = 'w-6 h-2 rounded-full bg-amber-400 transition-all';
                    dot1.className = 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
                } else {
                    dot0.className = 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
                    dot1.className = 'w-6 h-2 rounded-full bg-amber-400 transition-all';
                }
            }
        }

        function changeSlide(step) {
            currentBannerIndex = (currentBannerIndex + step + totalBanners) % totalBanners;
            updateBannerPosition();
            resetBannerTimer();
        }

        function goToSlide(index) {
            currentBannerIndex = index;
            updateBannerPosition();
            resetBannerTimer();
        }

        function resetBannerTimer() {
            if (bannerInterval) clearInterval(bannerInterval);
            bannerInterval = setInterval(function () {
                currentBannerIndex = (currentBannerIndex + 1) % totalBanners;
                updateBannerPosition();
            }, 5000);
        }

        // 2. Bộ lọc danh mục Công trình thực tế & Dự án Đà Nẵng
        function filterSection(groupName, filterKey) {
            const buttons = document.querySelectorAll('button[data-group="' + groupName + '"]');
            buttons.forEach(function (btn) {
                if (btn.getAttribute('data-filter') === filterKey) {
                    btn.classList.add('active');
                } else {
                    btn.classList.remove('active');
                }
            });

            const itemSelector = groupName === 'thi-cong' ? '.item-thi-cong' : '.item-du-an';
            const items = document.querySelectorAll(itemSelector);

            items.forEach(function (item) {
                const cats = item.getAttribute('data-category') || '';
                if (filterKey === 'all' || cats.indexOf(filterKey) !== -1) {
                    item.style.display = 'flex';
                } else {
                    item.style.display = 'none';
                }
            });
        }

        // 3. Xử lý gửi Form Yêu cầu tư vấn & Báo giá
        function handleQuoteSubmit(event) {
            event.preventDefault();
            const name = document.getElementById('customer-name').value.trim();
            const phone = document.getElementById('customer-phone').value.trim();
            const type = document.getElementById('project-type').value;
            const budget = document.getElementById('budget-level').value;
            const feedback = document.getElementById('quote-form-feedback');

            if (feedback) {
                feedback.classList.remove('hidden');
                feedback.innerHTML = '<i class="fa-solid fa-circle-check mr-1.5"></i> Cảm ơn <strong>' + name + '</strong> (' + phone + ')! Yêu cầu tư vấn <strong>' + type + '</strong> (Mức đầu tư: ' + budget + ') đã được gửi tới bộ phận Kỹ thuật T-HOME. Chúng tôi sẽ liên hệ lại ngay qua số <strong>0905.436.426</strong>.';
            }
            document.getElementById('quote-request-form').reset();
        }

        // 4. Đóng/Mở Menu trên điện thoại
        window.onload = function () {
            resetBannerTimer();

            const mobileToggle = document.getElementById('mobile-menu-toggle');
            const mobilePanel = document.getElementById('mobile-menu-panel');
            if (mobileToggle && mobilePanel) {
                mobileToggle.addEventListener('click', function () {
                    mobilePanel.classList.toggle('hidden');
                });

                const mobileLinks = mobilePanel.querySelectorAll('.mobile-nav-link');
                mobileLinks.forEach(function (link) {
                    link.addEventListener('click', function () {
                        mobilePanel.classList.add('hidden');
                    });
                });
            }
        };
    </script>
</body>
</html>
