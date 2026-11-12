<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>CÔNG TY TNHH XÂY DỰNG AN QUÂN PHÁT - Thiết Kế & Thi Công Trọn Gói Đà Nẵng</title>
    <meta name="description" content="CÔNG TY TNHH XÂY DỰNG AN QUÂN PHÁT (anquanphat.com) chuyên Thiết kế Kiến trúc - Thi công Xây dựng - Nội thất trọn gói Khách sạn, Biệt thự, Nhà phố, Căn hộ, Văn phòng tại Đà Nẵng. Hotline: 0915.500.997">
    
    <!-- Open Graph / Thumbnail là ảnh Logo khi gửi link trang web -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://anquanphat.com/">
    <meta property="og:title" content="CÔNG TY TNHH XÂY DỰNG AN QUÂN PHÁT - anquanphat.com">
    <meta property="og:description" content="Chuyên Thiết kế - Thi công Xây dựng - Nội thất trọn gói tại Đà Nẵng. Địa chỉ: 310 Bắc Sơn, Phường An Khê, TP Đà Nẵng. ĐT: 0915.500.997">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1VoQccCJ9Cx6rAny66kwkZb1lZbeH0XRv">
    <meta property="og:image:secure_url" content="https://drive.google.com/thumbnail?id=1VoQccCJ9Cx6rAny66kwkZb1lZbeH0XRv&sz=w1200">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1VoQccCJ9Cx6rAny66kwkZb1lZbeH0XRv">
    <link rel="icon" href="https://lh3.googleusercontent.com/d/1VoQccCJ9Cx6rAny66kwkZb1lZbeH0XRv">

    <!-- Tailwind CSS & Font Awesome & Google Fonts -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            primary: '#0f3e6d',   /* Xanh đậm chủ đạo theo tông logo xây dựng */
                            secondary: '#d97706', /* Vàng đồng / Cam nhấn theo logo */
                            dark: '#092644',
                            light: '#f0f6fc'
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền & chống lệch phải tuyệt đối trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
            background-color: #ffffff;
            color: #1e293b;
        }

        /* Khung giao diện chuẩn Flatsome: 95% chiều ngang trên máy tính */
        .flatsome-container {
            width: 100%;
            max-width: 100%;
            padding-left: 12px;
            padding-right: 12px;
            margin-left: auto;
            margin-right: auto;
        }
        @media (min-width: 1024px) {
            .flatsome-container {
                width: 95%;
                max-width: 95vw;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Tiêu đề Section chuẩn Flatsome (Section Title) */
        .section-title-container {
            margin-bottom: 1.5rem;
        }
        .section-title-main {
            position: relative;
            display: inline-block;
            font-weight: 800;
            text-transform: uppercase;
            color: #0f3e6d;
            letter-spacing: 0.02em;
        }
        .section-title-line {
            height: 3px;
            width: 60px;
            background: linear-gradient(90deg, #0f3e6d 0%, #d97706 100%);
            margin: 8px auto 0;
            border-radius: 2px;
        }

        /* Tối ưu thanh danh mục trên máy tính: nhỏ gọn, viết liền trên 1 hàng, không đứt chữ */
        .desktop-nav-list {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: center;
            gap: 2px 6px;
        }
        .desktop-nav-item {
            white-space: nowrap;
            font-size: 12.5px;
            font-weight: 600;
            color: #1e293b;
            padding: 6px 9px;
            border-radius: 6px;
            transition: all 0.2s ease;
            display: inline-flex;
            align-items: center;
            gap: 4px;
            line-height: 1.2;
        }
        .desktop-nav-item:hover, .desktop-nav-item.active {
            color: #0f3e6d;
            background-color: #f0f6fc;
        }

        /* Dropdown menu chuẩn Flatsome */
        .has-dropdown {
            position: relative;
        }
        .nav-dropdown {
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 230px;
            background: #ffffff;
            border: 1px solid #e2e8f0;
            box-shadow: 0 10px 25px -5px rgba(15, 62, 109, 0.15);
            border-radius: 8px;
            padding: 6px 0;
            opacity: 0;
            visibility: hidden;
            transform: translateY(8px);
            transition: all 0.2s ease;
            z-index: 100;
        }
        .has-dropdown:hover .nav-dropdown {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }
        .nav-dropdown a {
            display: block;
            padding: 8px 14px;
            font-size: 12.5px;
            font-weight: 500;
            color: #334155;
            white-space: nowrap;
            transition: all 0.15s ease;
        }
        .nav-dropdown a:hover {
            background-color: #f0f6fc;
            color: #0f3e6d;
            padding-left: 18px;
        }

        /* Đảm bảo tên sản phẩm hiển thị đầy đủ, không bị cắt chữ hay tràn ra ngoài */
        .product-title-full {
            white-space: normal;
            word-break: break-word;
            overflow-wrap: break-word;
            line-height: 1.38;
        }

        /* Hiệu ứng nút liên hệ nổi */
        @keyframes pulseRing {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 119, 6, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(217, 119, 6, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 119, 6, 0); }
        }
        .pulse-btn {
            animation: pulseRing 2s infinite;
        }
    </style>
</head>
<body class="bg-white text-slate-800 antialiased">

    <!-- ================= TOP BAR ================= -->
    <div id="top-bar" class="bg-brand-dark text-white text-[11px] sm:text-xs py-1.5 border-b border-slate-700/60">
        <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-3 sm:gap-5 truncate">
                <span class="inline-flex items-center gap-1.5">
                    <i class="fa-solid fa-location-dot text-amber-400"></i>
                    <span>310 Bắc Sơn, Phường An Khê, TP Đà Nẵng</span>
                </span>
                <span class="hidden md:inline-flex items-center gap-1.5">
                    <i class="fa-solid fa-globe text-amber-400"></i>
                    <span>anquanphat.com</span>
                </span>
            </div>
            <div class="flex items-center gap-3 sm:gap-4 ml-auto">
                <a href="tel:0915500997" class="hover:text-amber-300 transition inline-flex items-center gap-1 font-medium">
                    <i class="fa-solid fa-phone-volume text-amber-400"></i>
                    <span>0915.500.997</span>
                </a>
                <span class="text-slate-500">|</span>
                <a href="https://www.facebook.com/cong.ty.tnhh.xay.dung.an.quan.phat" target="_blank" rel="noopener noreferrer" class="hover:text-amber-300 transition inline-flex items-center gap-1">
                    <i class="fa-brands fa-facebook"></i>
                    <span class="hidden sm:inline">Fanpage An Quân Phát</span>
                </a>
            </div>
        </div>
    </div>

    <!-- ================= HEADER (FLATSOME HEADER WRAPPER - KHÔNG ĐỂ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN) ================= -->
    <header id="header" class="sticky top-0 z-50 bg-white/95 backdrop-blur border-b border-slate-200 shadow-sm">
        <div class="flatsome-container py-2">
            <div class="flex items-center justify-between gap-3">
                
                <!-- Logo chỉnh gọn nhỏ lại + Tên công ty -->
                <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group max-w-[80%] sm:max-w-none">
                    <div class="w-10 h-10 sm:w-11 sm:h-11 rounded-lg border border-slate-200 bg-white p-0.5 flex items-center justify-center overflow-hidden shrink-0 shadow-sm">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1VoQccCJ9Cx6rAny66kwkZb1lZbeH0XRv" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1VoQccCJ9Cx6rAny66kwkZb1lZbeH0XRv&sz=w400';" 
                            alt="Logo Công Ty TNHH Xây Dựng An Quân Phát" 
                            class="w-full h-full object-contain"
                        >
                    </div>
                    <div class="leading-tight">
                        <span class="block text-[12px] sm:text-[14px] font-extrabold text-brand-primary tracking-tight uppercase">
                            XÂY DỰNG AN QUÂN PHÁT
                        </span>
                        <span class="block text-[10px] sm:text-[11px] font-medium text-amber-600">
                            anquanphat.com • Thiết Kế & Thi Công
                        </span>
                    </div>
                </a>

                <!-- Danh mục trên máy tính: nhỏ gọn, viết liền trên 1 hàng (hoặc xuống hàng 2), không đứt dòng tên danh mục -->
                <nav class="hidden lg:block flex-1" aria-label="Menu chính">
                    <ul class="desktop-nav-list">
                        <li><a href="#trang-chu" class="desktop-nav-item active">Trang chủ</a></li>
                        <li><a href="#gioi-thieu" class="desktop-nav-item">Giới thiệu</a></li>
                        
                        <li class="has-dropdown">
                            <a href="#cong-trinh-thuc-te" class="desktop-nav-item">
                                Công trình thực tế <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                            </a>
                            <div class="nav-dropdown">
                                <a href="#cong-trinh-thuc-te" onclick="filterProjects('all')">Tất cả công trình thực tế</a>
                                <a href="#cong-trinh-thuc-te" onclick="filterProjects('khach-san')">Khách sạn – Căn hộ – Phòng trọ</a>
                                <a href="#cong-trinh-thuc-te" onclick="filterProjects('biet-thu')">Biệt thự cao cấp</a>
                                <a href="#cong-trinh-thuc-te" onclick="filterProjects('nha-pho')">Nhà phố hiện đại</a>
                                <a href="#cong-trinh-thuc-te" onclick="filterProjects('van-phong')">Văn phòng – Thương mại</a>
                            </div>
                        </li>

                        <li class="has-dropdown">
                            <a href="#linh-vuc-hoat-dong" class="desktop-nav-item">
                                Lĩnh vực hoạt động <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                            </a>
                            <div class="nav-dropdown">
                                <a href="#linh-vuc-hoat-dong" onclick="filterServices('thiet-ke')">Thiết kế Kiến trúc – Nội thất</a>
                                <a href="#linh-vuc-hoat-dong" onclick="filterServices('phan-tho')">Thi công phần thô</a>
                                <a href="#linh-vuc-hoat-dong" onclick="filterServices('hoan-thien')">Thi công hoàn thiện</a>
                                <a href="#linh-vuc-hoat-dong" onclick="filterServices('noi-that')">Thi công nội thất</a>
                            </div>
                        </li>

                        <li class="has-dropdown">
                            <a href="#linh-vuc-hoat-dong" class="desktop-nav-item">
                                Mẫu thiết kế <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                            </a>
                            <div class="nav-dropdown">
                                <a href="#linh-vuc-hoat-dong" onclick="filterServices('mau-nha-pho')">Mẫu thiết kế nhà phố</a>
                                <a href="#linh-vuc-hoat-dong" onclick="filterServices('mau-noi-that')">Mẫu thiết kế nội thất</a>
                            </div>
                        </li>

                        <li class="has-dropdown">
                            <a href="#bao-gia" class="desktop-nav-item">
                                Báo giá <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                            </a>
                            <div class="nav-dropdown">
                                <a href="#bao-gia">Báo giá thiết kế kiến trúc</a>
                                <a href="#bao-gia">Báo giá thi công phần thô</a>
                                <a href="#bao-gia">Báo giá thi công hoàn thiện</a>
                                <a href="#bao-gia">Báo giá thi công trọn gói</a>
                            </div>
                        </li>

                        <li><a href="#cong-trinh-thuc-te" class="desktop-nav-item">Dự án Đà Nẵng</a></li>
                        <li><a href="#doi-tac" class="desktop-nav-item">Đối tác</a></li>
                        <li><a href="#tin-tuc" class="desktop-nav-item">Tin tức</a></li>
                        <li><a href="#lien-he" class="desktop-nav-item">Liên hệ</a></li>
                    </ul>
                </nav>

                <!-- Nút mở Menu trên Điện thoại (Không để nút Gọi ngay trên Header) -->
                <button 
                    type="button" 
                    onclick="toggleMobileMenu()" 
                    class="lg:hidden inline-flex items-center justify-center p-2 rounded-lg border border-slate-200 text-brand-primary hover:bg-slate-100 focus:outline-none shrink-0"
                    aria-label="Mở danh mục"
                >
                    <i id="mobile-menu-icon" class="fa-solid fa-bars text-lg"></i>
                </button>
            </div>

            <!-- Thanh danh mục cuộn nhanh dưới Header cho Điện thoại -->
            <div class="lg:hidden mt-2 pt-1.5 border-t border-slate-100 flex items-center gap-1.5 overflow-x-auto no-scrollbar pb-1">
                <a href="#trang-chu" class="whitespace-nowrap text-[11px] font-semibold px-2.5 py-1 rounded bg-brand-primary text-white">Trang chủ</a>
                <a href="#gioi-thieu" class="whitespace-nowrap text-[11px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-slate-700">Giới thiệu</a>
                <a href="#linh-vuc-hoat-dong" class="whitespace-nowrap text-[11px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-slate-700">Lĩnh vực & Mẫu</a>
                <a href="#cong-trinh-thuc-te" class="whitespace-nowrap text-[11px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-slate-700">Dự án Đà Nẵng</a>
                <a href="#bao-gia" class="whitespace-nowrap text-[11px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-slate-700">Báo giá</a>
                <a href="#doi-tac" class="whitespace-nowrap text-[11px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-slate-700">Đối tác</a>
                <a href="#tin-tuc" class="whitespace-nowrap text-[11px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-slate-700">Tin tức</a>
                <a href="#lien-he" class="whitespace-nowrap text-[11px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-slate-700">Bản đồ & Liên hệ</a>
            </div>
        </div>

        <!-- Menu Drawer trên Điện thoại -->
        <div id="mobile-menu-drawer" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-xl">
            <div class="flatsome-container py-3 space-y-2 text-xs">
                <div class="grid grid-cols-2 gap-1.5">
                    <a href="#trang-chu" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-50 font-semibold text-brand-primary">Trang chủ</a>
                    <a href="#gioi-thieu" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-50 font-semibold text-brand-primary">Giới thiệu công ty</a>
                    <a href="#linh-vuc-hoat-dong" onclick="toggleMobileMenu();filterServices('thiet-ke')" class="p-2 rounded bg-slate-50 font-medium text-slate-700">Thiết kế Kiến trúc - Nội thất</a>
                    <a href="#linh-vuc-hoat-dong" onclick="toggleMobileMenu();filterServices('phan-tho')" class="p-2 rounded bg-slate-50 font-medium text-slate-700">Thi công phần thô</a>
                    <a href="#linh-vuc-hoat-dong" onclick="toggleMobileMenu();filterServices('hoan-thien')" class="p-2 rounded bg-slate-50 font-medium text-slate-700">Thi công hoàn thiện</a>
                    <a href="#linh-vuc-hoat-dong" onclick="toggleMobileMenu();filterServices('noi-that')" class="p-2 rounded bg-slate-50 font-medium text-slate-700">Thi công nội thất</a>
                    <a href="#cong-trinh-thuc-te" onclick="toggleMobileMenu();filterProjects('khach-san')" class="p-2 rounded bg-slate-50 font-medium text-slate-700">Khách sạn – Căn hộ</a>
                    <a href="#cong-trinh-thuc-te" onclick="toggleMobileMenu();filterProjects('biet-thu')" class="p-2 rounded bg-slate-50 font-medium text-slate-700">Biệt thự Đà Nẵng</a>
                    <a href="#cong-trinh-thuc-te" onclick="toggleMobileMenu();filterProjects('nha-pho')" class="p-2 rounded bg-slate-50 font-medium text-slate-700">Nhà phố hiện đại</a>
                    <a href="#cong-trinh-thuc-te" onclick="toggleMobileMenu();filterProjects('van-phong')" class="p-2 rounded bg-slate-50 font-medium text-slate-700">Văn phòng & Cải tạo</a>
                    <a href="#bao-gia" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-50 font-semibold text-amber-700">Bảng báo giá & Tư vấn</a>
                    <a href="#doi-tac" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-50 font-medium text-slate-700">Đối tác chiến lược</a>
                    <a href="#tin-tuc" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-50 font-medium text-slate-700">Tin tức xây dựng</a>
                    <a href="#lien-he" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-50 font-medium text-slate-700">Bản đồ & Liên hệ</a>
                </div>
            </div>
        </div>
    </header>

    <!-- ================= MAIN CONTENT (UX BUILDER FLATSOME STRUCTURE) ================= -->
    <main id="trang-chu">

        <!-- 1. BANNER SLIDER TỰ TRƯỢT (2 ẢNH KÍCH THƯỚC BẰNG NHAU, ẢNH ĐIỆN THOẠI RIÊNG BIỆT KHÁC ẢNH MÁY TÍNH, CHỮ NHỎ GỌN KHÔNG TRÀN VIỀN) -->
        <section class="ux-section py-3 bg-slate-50">
            <div class="flatsome-container">
                <div class="relative rounded-xl overflow-hidden shadow-md border border-slate-200 bg-brand-dark">
                    
                    <!-- Vùng chứa 2 Slide kích thước bằng nhau tuyệt đối -->
                    <div id="banner-slider" class="relative w-full h-[220px] sm:h-[250px] md:h-[360px] lg:h-[420px]">
                        
                        <!-- ================= SLIDE 1 ================= -->
                        <div class="banner-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10">
                            
                            <!-- ẢNH BANNER MÁY TÍNH SỐ 1 (Chỉ hiển thị trên máy tính/tablet ngang) -->
                            <div class="hidden md:flex w-full h-full relative items-center bg-gradient-to-r from-[#071e36] via-[#0f3e6d] to-[#124b84]">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk" 
                                    onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk&sz=w1200';"
                                    alt="Banner Máy Tính 1 - Xây Dựng An Quân Phát" 
                                    class="absolute right-0 top-0 w-[52%] h-full object-cover opacity-85"
                                    style="clip-path: polygon(14% 0, 100% 0, 100% 100%, 0% 100%);"
                                >
                                <div class="relative z-10 w-[56%] pl-12 pr-6 py-6 text-white">
                                    <div class="inline-flex items-center gap-2 bg-amber-500/20 border border-amber-400/40 text-amber-300 text-xs font-semibold px-3 py-1 rounded-full mb-2.5">
                                        <span>CÔNG TY TNHH XÂY DỰNG AN QUÂN PHÁT</span>
                                    </div>
                                    <h1 class="text-xl lg:text-2xl xl:text-3xl font-extrabold leading-snug uppercase tracking-tight text-white mb-2">
                                        THIẾT KẾ & THI CÔNG XÂY DỰNG <span class="text-amber-400">TRỌN GÓI TẠI ĐÀ NẴNG</span>
                                    </h1>
                                    <p class="text-xs lg:text-sm text-slate-200 leading-relaxed mb-4 max-w-xl">
                                        Chuyên thiết kế kiến trúc, thi công phần thô, hoàn thiện & nội thất Khách sạn, Biệt thự, Nhà phố, Căn hộ, Văn phòng. Cam kết: An Toàn – Chất Lượng – Đúng Tiến Độ.
                                    </p>
                                    <div class="flex flex-wrap items-center gap-3 text-xs">
                                        <span class="bg-amber-500 text-slate-950 font-bold px-3.5 py-2 rounded-lg">
                                            <i class="fa-solid fa-phone mr-1"></i> Hotline: 0915.500.997
                                        </span>
                                        <span class="bg-white/10 border border-white/25 text-white px-3.5 py-2 rounded-lg">
                                            <i class="fa-solid fa-location-dot text-amber-400 mr-1"></i> 310 Bắc Sơn, P. An Khê, TP Đà Nẵng
                                        </span>
                                    </div>
                                </div>
                            </div>

                            <!-- ẢNH BANNER ĐIỆN THOẠI SỐ 1 (Thiết kế mới khác máy tính, chữ nhỏ gọn nằm trọn bên trong, không tràn viền) -->
                            <div class="flex md:hidden w-full h-full relative items-center justify-center bg-gradient-to-br from-[#071e36] via-[#0f3e6d] to-[#164e87] p-3.5">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1tHGEqsuxKkCkoDofSK_nE70LBMIvGuVW" 
                                    onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1tHGEqsuxKkCkoDofSK_nE70LBMIvGuVW&sz=w800';"
                                    alt="Banner Điện Thoại 1 - Xây Dựng An Quân Phát" 
                                    class="absolute inset-0 w-full h-full object-cover opacity-20"
                                >
                                <div class="relative z-10 w-full max-w-[92%] mx-auto border border-amber-400/40 bg-slate-900/65 backdrop-blur-xs rounded-lg p-3 text-center text-white">
                                    <p class="text-[10px] font-bold text-amber-400 uppercase tracking-wider mb-0.5">
                                        CÔNG TY TNHH XÂY DỰNG AN QUÂN PHÁT
                                    </p>
                                    <h2 class="text-[13px] sm:text-[15px] font-extrabold uppercase leading-tight text-white mb-1">
                                        THIẾT KẾ & XÂY NHÀ TRỌN GÓI ĐÀ NẴNG
                                    </h2>
                                    <p class="text-[10.5px] text-slate-200 leading-snug mb-2">
                                        Khách sạn • Biệt thự • Nhà phố • Căn hộ • Nội thất
                                    </p>
                                    <div class="inline-flex flex-wrap items-center justify-center gap-1.5 text-[10px]">
                                        <span class="bg-amber-500 text-slate-950 font-bold px-2 py-0.5 rounded">
                                            ĐT: 0915.500.997
                                        </span>
                                        <span class="bg-white/15 text-white px-2 py-0.5 rounded">
                                            310 Bắc Sơn, Đà Nẵng
                                        </span>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- ================= SLIDE 2 ================= -->
                        <div class="banner-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0">
                            
                            <!-- ẢNH BANNER MÁY TÍNH SỐ 2 (Chỉ hiển thị trên máy tính/tablet ngang) -->
                            <div class="hidden md:flex w-full h-full relative items-center bg-gradient-to-r from-[#0b2b4c] via-[#0f3e6d] to-[#1e3a5f]">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1PjtEF4hlMU_42b438GmEQhYZTba75kRJ" 
                                    onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1PjtEF4hlMU_42b438GmEQhYZTba75kRJ&sz=w1200';"
                                    alt="Banner Máy Tính 2 - Kiến Trúc Nội Thất An Quân Phát" 
                                    class="absolute right-0 top-0 w-[52%] h-full object-cover opacity-85"
                                    style="clip-path: polygon(14% 0, 100% 0, 100% 100%, 0% 100%);"
                                >
                                <div class="relative z-10 w-[56%] pl-12 pr-6 py-6 text-white">
                                    <div class="inline-flex items-center gap-2 bg-amber-500/20 border border-amber-400/40 text-amber-300 text-xs font-semibold px-3 py-1 rounded-full mb-2.5">
                                        <span>KIẾN TRÚC HIỆN ĐẠI • NỘI THẤT CAO CẤP</span>
                                    </div>
                                    <h2 class="text-xl lg:text-2xl xl:text-3xl font-extrabold leading-snug uppercase tracking-tight text-white mb-2">
                                        GIẢI PHÁP TỐI ƯU CHI PHÍ <span class="text-amber-400">& BẢO HÀNH DÀI HẠN</span>
                                    </h2>
                                    <p class="text-xs lg:text-sm text-slate-200 leading-relaxed mb-4 max-w-xl">
                                        Đội ngũ Kiến trúc sư, Kỹ sư giàu kinh nghiệm trực tiếp giám sát thi công từng hạng mục. Miễn phí 100% hồ sơ thiết kế khi ký hợp đồng thi công trọn gói.
                                    </p>
                                    <div class="flex flex-wrap items-center gap-3 text-xs">
                                        <span class="bg-amber-500 text-slate-950 font-bold px-3.5 py-2 rounded-lg">
                                            <i class="fa-solid fa-calculator mr-1"></i> Tư Vấn & Báo Giá 24/7: 0915.500.997
                                        </span>
                                        <span class="bg-white/10 border border-white/25 text-white px-3.5 py-2 rounded-lg">
                                            <i class="fa-solid fa-globe text-amber-400 mr-1"></i> Website: anquanphat.com
                                        </span>
                                    </div>
                                </div>
                            </div>

                            <!-- ẢNH BANNER ĐIỆN THOẠI SỐ 2 (Thiết kế mới khác máy tính, chữ nhỏ gọn nằm hết bên trong ảnh) -->
                            <div class="flex md:hidden w-full h-full relative items-center justify-center bg-gradient-to-tr from-[#09223c] via-[#0f3e6d] to-[#1e4b7a] p-3.5">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1m7VasLcMXKPk2-mSVgIdO3USOnbaZ_KA" 
                                    onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1m7VasLcMXKPk2-mSVgIdO3USOnbaZ_KA&sz=w800';"
                                    alt="Banner Điện Thoại 2 - Nội Thất An Quân Phát" 
                                    class="absolute inset-0 w-full h-full object-cover opacity-20"
                                >
                                <div class="relative z-10 w-full max-w-[92%] mx-auto border border-sky-300/40 bg-slate-900/65 backdrop-blur-xs rounded-lg p-3 text-center text-white">
                                    <p class="text-[10px] font-bold text-amber-400 uppercase tracking-wider mb-0.5">
                                        AN QUÂN PHÁT • ANQUANPHAT.COM
                                    </p>
                                    <h2 class="text-[13px] sm:text-[15px] font-extrabold uppercase leading-tight text-white mb-1">
                                        THI CÔNG PHẦN THÔ & NỘI THẤT UY TÍN
                                    </h2>
                                    <p class="text-[10.5px] text-slate-200 leading-snug mb-2">
                                        Miễn phí tư vấn thiết kế • Giám sát chuẩn tiến độ
                                    </p>
                                    <div class="inline-flex flex-wrap items-center justify-center gap-1.5 text-[10px]">
                                        <span class="bg-amber-500 text-slate-950 font-bold px-2 py-0.5 rounded">
                                            Hotline: 0915.500.997
                                        </span>
                                        <span class="bg-white/15 text-white px-2 py-0.5 rounded">
                                            P. An Khê, TP Đà Nẵng
                                        </span>
                                    </div>
                                </div>
                            </div>
                        </div>

                    </div>

                    <!-- Nút điều hướng Slider -->
                    <button type="button" onclick="prevBanner()" aria-label="Slide trước" class="absolute left-2 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-black/70 text-white flex items-center justify-center transition">
                        <i class="fa-solid fa-chevron-left text-xs"></i>
                    </button>
                    <button type="button" onclick="nextBanner()" aria-label="Slide tiếp" class="absolute right-2 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-black/70 text-white flex items-center justify-center transition">
                        <i class="fa-solid fa-chevron-right text-xs"></i>
                    </button>

                    <!-- Chấm chỉ báo Slide -->
                    <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                        <button type="button" onclick="goToBanner(0)" class="banner-dot w-6 h-1.5 rounded-full bg-amber-400 transition-all" aria-label="Banner 1"></button>
                        <button type="button" onclick="goToBanner(1)" class="banner-dot w-2.5 h-1.5 rounded-full bg-white/60 transition-all" aria-label="Banner 2"></button>
                    </div>

                </div>
            </div>
        </section>

        <!-- 2. DỊCH VỤ TIÊU BIỂU (3 KHỐI GIỐNG WEB MẪU TINTRUONGTHINH.COM: THIẾT KẾ - THI CÔNG - NỘI THẤT) -->
        <section class="ux-section py-6 bg-white">
            <div class="flatsome-container">
                <div class="grid grid-cols-3 gap-2.5 sm:gap-5">
                    <a href="#linh-vuc-hoat-dong" onclick="filterServices('thiet-ke')" class="group rounded-xl border border-slate-200 bg-brand-light/60 hover:bg-brand-primary p-3 sm:p-5 text-center transition shadow-xs">
                        <div class="w-10 h-10 sm:w-14 sm:h-14 mx-auto mb-2 rounded-full bg-brand-primary group-hover:bg-amber-500 text-white flex items-center justify-center transition">
                            <i class="fa-solid fa-compass-drafting text-base sm:text-2xl"></i>
                        </div>
                        <h3 class="text-xs sm:text-base font-extrabold uppercase text-brand-primary group-hover:text-white">THIẾT KẾ</h3>
                        <p class="hidden sm:block text-xs text-slate-600 group-hover:text-slate-200 mt-1">Kiến trúc & Nội thất 3D</p>
                    </a>
                    <a href="#linh-vuc-hoat-dong" onclick="filterServices('phan-tho')" class="group rounded-xl border border-slate-200 bg-brand-light/60 hover:bg-brand-primary p-3 sm:p-5 text-center transition shadow-xs">
                        <div class="w-10 h-10 sm:w-14 sm:h-14 mx-auto mb-2 rounded-full bg-brand-primary group-hover:bg-amber-500 text-white flex items-center justify-center transition">
                            <i class="fa-solid fa-trowel-bricks text-base sm:text-2xl"></i>
                        </div>
                        <h3 class="text-xs sm:text-base font-extrabold uppercase text-brand-primary group-hover:text-white">THI CÔNG</h3>
                        <p class="hidden sm:block text-xs text-slate-600 group-hover:text-slate-200 mt-1">Phần thô & Xây nhà trọn gói</p>
                    </a>
                    <a href="#linh-vuc-hoat-dong" onclick="filterServices('noi-that')" class="group rounded-xl border border-slate-200 bg-brand-light/60 hover:bg-brand-primary p-3 sm:p-5 text-center transition shadow-xs">
                        <div class="w-10 h-10 sm:w-14 sm:h-14 mx-auto mb-2 rounded-full bg-brand-primary group-hover:bg-amber-500 text-white flex items-center justify-center transition">
                            <i class="fa-solid fa-couch text-base sm:text-2xl"></i>
                        </div>
                        <h3 class="text-xs sm:text-base font-extrabold uppercase text-brand-primary group-hover:text-white">NỘI THẤT</h3>
                        <p class="hidden sm:block text-xs text-slate-600 group-hover:text-slate-200 mt-1">Sản xuất & Lắp đặt hoàn thiện</p>
                    </a>
                </div>
            </div>
        </section>

        <!-- 3. GIỚI THIỆU CÔNG TY & THẾ MẠNH CỦA CHÚNG TÔI (THEO MẪU TINTRUONGTHINH.COM) -->
        <section id="gioi-thieu" class="ux-section py-8 bg-slate-50 border-y border-slate-200/80">
            <div class="flatsome-container">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center mb-8">
                    <div class="lg:col-span-7 space-y-3">
                        <p class="text-xs font-bold uppercase tracking-wider text-amber-600">VỀ CHÚNG TÔI • MST: 0402077732</p>
                        <h2 class="text-lg sm:text-2xl font-extrabold text-brand-primary uppercase">
                            CÔNG TY TNHH XÂY DỰNG AN QUÂN PHÁT
                        </h2>
                        <p class="text-xs sm:text-sm text-slate-700 leading-relaxed">
                            <strong>CÔNG TY TNHH XÂY DỰNG AN QUÂN PHÁT</strong> chuyên <strong>Thiết kế – Xây dựng – Nội thất</strong> các công trình Khách sạn, Biệt thự, Căn hộ, Văn phòng, Nhà phố tại TP Đà Nẵng và khu vực miền Trung. Với tiêu chí <em>“Nhà ở Gia đình – Tiêu chuẩn Công trình”</em>, chúng tôi luôn mang đến trải nghiệm chuyên nghiệp và sự an tâm tuyệt đối cho Quý Khách hàng.
                        </p>
                        <p class="text-xs sm:text-sm text-slate-700 leading-relaxed">
                            Đặt chữ <strong>“TÂM”</strong> trong nghề lên hàng đầu để mỗi công trình luôn đạt chuẩn <strong>“AN TOÀN – CHẤT LƯỢNG – TIẾN ĐỘ – SỰ HÀI LÒNG CỦA KHÁCH HÀNG”</strong>. Đội ngũ kiến trúc sư, kỹ sư giàu kinh nghiệm của An Quân Phát luôn là địa chỉ tin cậy đồng hành dựng xây tổ ấm bền vững.
                        </p>
                        <div class="grid grid-cols-2 sm:grid-cols-3 gap-2.5 pt-2 text-xs">
                            <div class="bg-white p-3 rounded-lg border border-slate-200">
                                <span class="block font-extrabold text-base text-brand-primary">100%</span>
                                <span class="text-slate-600">Vật tư chính hãng đúng hợp đồng</span>
                            </div>
                            <div class="bg-white p-3 rounded-lg border border-slate-200">
                                <span class="block font-extrabold text-base text-brand-primary">05 Năm</span>
                                <span class="text-slate-600">Bảo hành kết cấu công trình</span>
                            </div>
                            <div class="bg-white p-3 rounded-lg border border-slate-200 col-span-2 sm:col-span-1">
                                <span class="block font-extrabold text-base text-brand-primary">24/7</span>
                                <span class="text-slate-600">Tư vấn & báo giá miễn phí</span>
                            </div>
                        </div>
                    </div>
                    <div class="lg:col-span-5">
                        <div class="rounded-xl overflow-hidden border border-slate-200 shadow-sm bg-white">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1XhH8-wtjhLk_y-pM3LmHkPA--u6120g8" 
                                onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1XhH8-wtjhLk_y-pM3LmHkPA--u6120g8&sz=w1000';" 
                                alt="Công trình thực tế Xây Dựng An Quân Phát" 
                                class="w-full h-56 sm:h-64 object-cover"
                            >
                            <div class="p-3 bg-brand-primary text-white text-xs flex items-center justify-between">
                                <span>Trụ sở: 310 Bắc Sơn, P. An Khê, TP Đà Nẵng</span>
                                <span class="font-bold text-amber-400">0915.500.997</span>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- 6 Thế mạnh của chúng tôi (Giống mẫu Tín Trường Thịnh) -->
                <div class="section-title-container text-center">
                    <h3 class="section-title-main text-base sm:text-xl">THẾ MẠNH CỦA CHÚNG TÔI</h3>
                    <div class="section-title-line"></div>
                </div>
                <div class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
                    <div class="bg-white p-3.5 sm:p-5 rounded-xl border border-slate-200 shadow-xs">
                        <div class="w-9 h-9 rounded-lg bg-brand-light text-brand-primary flex items-center justify-center mb-2.5">
                            <i class="fa-solid fa-user-tie"></i>
                        </div>
                        <h4 class="text-xs sm:text-sm font-bold text-brand-primary mb-1 product-title-full">Đội ngũ kiến trúc sư, kỹ sư chuyên nghiệp</h4>
                        <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Kiến trúc sư sáng tạo cùng đội ngũ kỹ sư giám sát hiện trường giàu kinh nghiệm và thợ lành nghề.</p>
                    </div>
                    <div class="bg-white p-3.5 sm:p-5 rounded-xl border border-slate-200 shadow-xs">
                        <div class="w-9 h-9 rounded-lg bg-brand-light text-brand-primary flex items-center justify-center mb-2.5">
                            <i class="fa-solid fa-layer-group"></i>
                        </div>
                        <h4 class="text-xs sm:text-sm font-bold text-brand-primary mb-1 product-title-full">Cập nhật xu hướng kiến trúc hiện đại</h4>
                        <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Ứng dụng giải pháp không gian xanh, thông thoáng, vật liệu mới bền đẹp và phương pháp thi công tiên tiến.</p>
                    </div>
                    <div class="bg-white p-3.5 sm:p-5 rounded-xl border border-slate-200 shadow-xs">
                        <div class="w-9 h-9 rounded-lg bg-brand-light text-brand-primary flex items-center justify-center mb-2.5">
                            <i class="fa-solid fa-clipboard-check"></i>
                        </div>
                        <h4 class="text-xs sm:text-sm font-bold text-brand-primary mb-1 product-title-full">Giám sát tiến độ chuẩn xác</h4>
                        <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Hoàn thành đúng tiến độ cam kết, báo cáo nhật ký công trình thường xuyên để Chủ đầu tư dễ dàng theo dõi.</p>
                    </div>
                    <div class="bg-white p-3.5 sm:p-5 rounded-xl border border-slate-200 shadow-xs">
                        <div class="w-9 h-9 rounded-lg bg-brand-light text-brand-primary flex items-center justify-center mb-2.5">
                            <i class="fa-solid fa-shield-halved"></i>
                        </div>
                        <h4 class="text-xs sm:text-sm font-bold text-brand-primary mb-1 product-title-full">Bảo hành công trình lâu dài</h4>
                        <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Chế độ hậu mãi tận tâm, bảo hành kết cấu và chống thấm chu đáo, hỗ trợ nhanh chóng khi khách hàng cần.</p>
                    </div>
                    <div class="bg-white p-3.5 sm:p-5 rounded-xl border border-slate-200 shadow-xs">
                        <div class="w-9 h-9 rounded-lg bg-brand-light text-brand-primary flex items-center justify-center mb-2.5">
                            <i class="fa-solid fa-hand-holding-dollar"></i>
                        </div>
                        <h4 class="text-xs sm:text-sm font-bold text-brand-primary mb-1 product-title-full">Giá cả hợp lý, dự toán minh bạch</h4>
                        <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Bóc tách khối lượng rõ ràng từng hạng mục, cam kết không phát sinh chi phí ngoài hợp đồng.</p>
                    </div>
                    <div class="bg-white p-3.5 sm:p-5 rounded-xl border border-slate-200 shadow-xs">
                        <div class="w-9 h-9 rounded-lg bg-brand-light text-brand-primary flex items-center justify-center mb-2.5">
                            <i class="fa-solid fa-headset"></i>
                        </div>
                        <h4 class="text-xs sm:text-sm font-bold text-brand-primary mb-1 product-title-full">Hỗ trợ tư vấn miễn phí 24/7</h4>
                        <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Tư vấn phong thủy, thủ tục xin phép xây dựng và thiết kế sơ bộ hoàn toàn miễn phí qua Hotline 0915.500.997.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- 4. LĨNH VỰC HOẠT ĐỘNG & SẢN PHẨM DỊCH VỤ (8 ẢNH THỰC TẾ FILE DRIVE ĐẦU TIÊN - CHIA 2 CỘT TRÊN ĐIỆN THOẠI - KHÔNG NHÃN DÁN - TÊN KHÔNG TRÀN) -->
        <section id="linh-vuc-hoat-dong" class="ux-section py-9 bg-white">
            <div class="flatsome-container">
                <div class="section-title-container text-center">
                    <h2 class="section-title-main text-base sm:text-2xl">LĨNH VỰC HOẠT ĐỘNG & MẪU THIẾT KẾ – THI CÔNG</h2>
                    <div class="section-title-line"></div>
                    <p class="text-xs sm:text-sm text-slate-600 mt-2">Danh mục dịch vụ và sản phẩm thi công thực tế của Công ty TNHH Xây Dựng An Quân Phát</p>
                </div>

                <!-- Bộ lọc Danh mục nhỏ gọn -->
                <div class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-6">
                    <button type="button" onclick="filterServices('all')" class="service-tab-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-brand-primary text-white transition" data-tab="all">Tất cả hạng mục</button>
                    <button type="button" onclick="filterServices('thiet-ke')" class="service-tab-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200 transition" data-tab="thiet-ke">Thiết kế Kiến trúc – Nội thất</button>
                    <button type="button" onclick="filterServices('phan-tho')" class="service-tab-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200 transition" data-tab="phan-tho">Thi công phần thô</button>
                    <button type="button" onclick="filterServices('hoan-thien')" class="service-tab-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200 transition" data-tab="hoan-thien">Thi công hoàn thiện</button>
                    <button type="button" onclick="filterServices('noi-that')" class="service-tab-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200 transition" data-tab="noi-that">Thi công nội thất</button>
                    <button type="button" onclick="filterServices('mau-nha-pho')" class="service-tab-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200 transition" data-tab="mau-nha-pho">Mẫu thiết kế nhà phố</button>
                    <button type="button" onclick="filterServices('mau-noi-that')" class="service-tab-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200 transition" data-tab="mau-noi-that">Mẫu thiết kế nội thất</button>
                </div>

                <!-- Grid 8 sản phẩm/dịch vụ thực tế: Chia 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4), không để nhãn dán -->
                <div id="services-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
                    
                    <!-- Sản phẩm 1 -->
                    <div class="service-card rounded-xl border border-slate-200 overflow-hidden bg-white shadow-xs hover:shadow-md transition flex flex-col" data-category="thiet-ke mau-nha-pho">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1XhH8-wtjhLk_y-pM3LmHkPA--u6120g8" 
                                onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1XhH8-wtjhLk_y-pM3LmHkPA--u6120g8&sz=w800';" 
                                alt="Thiết kế & Thi công trọn gói Nhà phố hiện đại" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-500"
                            >
                        </div>
                        <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <p class="text-[11px] text-amber-600 font-semibold mb-1">Thiết kế Kiến trúc – Nội thất</p>
                                <h3 class="text-xs sm:text-sm font-bold text-slate-800 product-title-full">
                                    Thiết Kế & Thi Công Trọn Gói Nhà Phố Hiện Đại Đà Nẵng
                                </h3>
                            </div>
                            <div class="mt-2.5 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs">
                                <span class="font-bold text-brand-primary">Liên hệ: 0915.500.997</span>
                            </div>
                        </div>
                    </div>

                    <!-- Sản phẩm 2 -->
                    <div class="service-card rounded-xl border border-slate-200 overflow-hidden bg-white shadow-xs hover:shadow-md transition flex flex-col" data-category="phan-tho">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1E3FyPE_5YQLtCRIXo7guuebRGYG24g12" 
                                onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1E3FyPE_5YQLtCRIXo7guuebRGYG24g12&sz=w800';" 
                                alt="Thi công xây dựng phần thô và nhân công hoàn thiện" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-500"
                            >
                        </div>
                        <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <p class="text-[11px] text-amber-600 font-semibold mb-1">Thi công phần thô</p>
                                <h3 class="text-xs sm:text-sm font-bold text-slate-800 product-title-full">
                                    Thi Công Xây Dựng Phần Thô & Kết Cấu Bê Tông Cốt Thép
                                </h3>
                            </div>
                            <div class="mt-2.5 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs">
                                <span class="font-bold text-brand-primary">Liên hệ: 0915.500.997</span>
                            </div>
                        </div>
                    </div>

                    <!-- Sản phẩm 3 -->
                    <div class="service-card rounded-xl border border-slate-200 overflow-hidden bg-white shadow-xs hover:shadow-md transition flex flex-col" data-category="hoan-thien">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1008JYQjkF3zdVYuV6qXZ56Rw2iTbEO5Y" 
                                onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1008JYQjkF3zdVYuV6qXZ56Rw2iTbEO5Y&sz=w800';" 
                                alt="Thi công hoàn thiện mặt tiền và kiến trúc công trình" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-500"
                            >
                        </div>
                        <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <p class="text-[11px] text-amber-600 font-semibold mb-1">Thi công hoàn thiện</p>
                                <h3 class="text-xs sm:text-sm font-bold text-slate-800 product-title-full">
                                    Thi Công Hoàn Thiện Kiến Trúc Mặt Tiền & Chống Thấm
                                </h3>
                            </div>
                            <div class="mt-2.5 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs">
                                <span class="font-bold text-brand-primary">Liên hệ: 0915.500.997</span>
                            </div>
                        </div>
                    </div>

                    <!-- Sản phẩm 4 -->
                    <div class="service-card rounded-xl border border-slate-200 overflow-hidden bg-white shadow-xs hover:shadow-md transition flex flex-col" data-category="noi-that mau-noi-that">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/17vn5wKHbZgE-xsgLzKw42OzqdPmYTI26" 
                                onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=17vn5wKHbZgE-xsgLzKw42OzqdPmYTI26&sz=w800';" 
                                alt="Thiết kế và thi công nội thất phòng khách bếp" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-500"
                            >
                        </div>
                        <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <p class="text-[11px] text-amber-600 font-semibold mb-1">Thi công nội thất</p>
                                <h3 class="text-xs sm:text-sm font-bold text-slate-800 product-title-full">
                                    Thiết Kế & Thi Công Nội Thất Phòng Khách – Bếp Cao Cấp
                                </h3>
                            </div>
                            <div class="mt-2.5 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs">
                                <span class="font-bold text-brand-primary">Liên hệ: 0915.500.997</span>
                            </div>
                        </div>
                    </div>

                    <!-- Sản phẩm 5 -->
                    <div class="service-card rounded-xl border border-slate-200 overflow-hidden bg-white shadow-xs hover:shadow-md transition flex flex-col" data-category="thiet-ke mau-nha-pho">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1KXrcyVScz-DxRuW2PMO-uWL_Ft7ndFoZ" 
                                onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1KXrcyVScz-DxRuW2PMO-uWL_Ft7ndFoZ&sz=w800';" 
                                alt="Mẫu thiết kế biệt thự và nhà phố 3 tầng" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-500"
                            >
                        </div>
                        <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <p class="text-[11px] text-amber-600 font-semibold mb-1">Mẫu thiết kế nhà phố</p>
                                <h3 class="text-xs sm:text-sm font-bold text-slate-800 product-title-full">
                                    Mẫu Thiết Kế Nhà Phố 3 Tầng & Biệt Thự Sân Vườn Đẹp
                                </h3>
                            </div>
                            <div class="mt-2.5 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs">
                                <span class="font-bold text-brand-primary">Liên hệ: 0915.500.997</span>
                            </div>
                        </div>
                    </div>

                    <!-- Sản phẩm 6 -->
                    <div class="service-card rounded-xl border border-slate-200 overflow-hidden bg-white shadow-xs hover:shadow-md transition flex flex-col" data-category="thiet-ke hoan-thien">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1to3oGP6tsGCT-r3Mrid3Xm6NxmNVEVcx" 
                                onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1to3oGP6tsGCT-r3Mrid3Xm6NxmNVEVcx&sz=w800';" 
                                alt="Thiết kế và thi công Khách sạn Căn hộ cho thuê" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-500"
                            >
                        </div>
                        <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <p class="text-[11px] text-amber-600 font-semibold mb-1">Khách sạn – Căn hộ</p>
                                <h3 class="text-xs sm:text-sm font-bold text-slate-800 product-title-full">
                                    Thi Công Trọn Gói Khách Sạn, Căn Hộ Cho Thuê & Apartment
                                </h3>
                            </div>
                            <div class="mt-2.5 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs">
                                <span class="font-bold text-brand-primary">Liên hệ: 0915.500.997</span>
                            </div>
                        </div>
                    </div>

                    <!-- Sản phẩm 7 -->
                    <div class="service-card rounded-xl border border-slate-200 overflow-hidden bg-white shadow-xs hover:shadow-md transition flex flex-col" data-category="noi-that mau-noi-that">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1NmqFX0r491OF3Pf8T9jnmKTDz8rSQcmG" 
                                onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1NmqFX0r491OF3Pf8T9jnmKTDz8rSQcmG&sz=w800';" 
                                alt="Mẫu thiết kế nội thất phòng ngủ và căn hộ" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-500"
                            >
                        </div>
                        <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <p class="text-[11px] text-amber-600 font-semibold mb-1">Mẫu thiết kế nội thất</p>
                                <h3 class="text-xs sm:text-sm font-bold text-slate-800 product-title-full">
                                    Mẫu Thiết Kế & Sản Xuất Nội Thất Gỗ Công Nghiệp – Tự Nhiên
                                </h3>
                            </div>
                            <div class="mt-2.5 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs">
                                <span class="font-bold text-brand-primary">Liên hệ: 0915.500.997</span>
                            </div>
                        </div>
                    </div>

                    <!-- Sản phẩm 8 -->
                    <div class="service-card rounded-xl border border-slate-200 overflow-hidden bg-white shadow-xs hover:shadow-md transition flex flex-col" data-category="phan-tho hoan-thien">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1YPCw88Ee9SQEj9s0jpfWzyF8LUPD8Ku4" 
                                onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1YPCw88Ee9SQEj9s0jpfWzyF8LUPD8Ku4&sz=w800';" 
                                alt="Thi công văn phòng và cải tạo sửa chữa công trình" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-500"
                            >
                        </div>
                        <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <p class="text-[11px] text-amber-600 font-semibold mb-1">Văn phòng & Cải tạo</p>
                                <h3 class="text-xs sm:text-sm font-bold text-slate-800 product-title-full">
                                    Thiết Kế Thi Công Văn Phòng, Showroom & Cải Tạo Nhà Trọn Gói
                                </h3>
                            </div>
                            <div class="mt-2.5 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs">
                                <span class="font-bold text-brand-primary">Liên hệ: 0915.500.997</span>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </section>

        <!-- 5. DANH MỤC CÔNG TRÌNH THỰC TẾ & CÁC DỰ ÁN Ở ĐÀ NẴNG (15 ẢNH DỰ ÁN TRONG FILE DRIVE - CHIA 2 CỘT TRÊN ĐIỆN THOẠI - KHÔNG NHÃN DÁN) -->
        <section id="cong-trinh-thuc-te" class="ux-section py-9 bg-slate-50 border-t border-slate-200">
            <div class="flatsome-container">
                <div class="section-title-container text-center">
                    <h2 class="section-title-main text-base sm:text-2xl">CÔNG TRÌNH THỰC TẾ & DỰ ÁN TẠI ĐÀ NẴNG</h2>
                    <div class="section-title-line"></div>
                    <p class="text-xs sm:text-sm text-slate-600 mt-2">Hình ảnh các dự án tiêu biểu do Công ty TNHH Xây Dựng An Quân Phát thiết kế và thi công tại Đà Nẵng</p>
                </div>

                <!-- Các Tab Danh Mục Dự Án giống mẫu Tín Trường Thịnh -->
                <div class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-6">
                    <button type="button" onclick="filterProjects('all')" class="project-tab-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-brand-primary text-white transition" data-proj="all">Tất cả (15)</button>
                    <button type="button" onclick="filterProjects('khach-san')" class="project-tab-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white border border-slate-200 text-slate-700 hover:bg-slate-100 transition" data-proj="khach-san">Khách sạn – Căn hộ – Phòng trọ</button>
                    <button type="button" onclick="filterProjects('biet-thu')" class="project-tab-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white border border-slate-200 text-slate-700 hover:bg-slate-100 transition" data-proj="biet-thu">Biệt thự</button>
                    <button type="button" onclick="filterProjects('nha-pho')" class="project-tab-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white border border-slate-200 text-slate-700 hover:bg-slate-100 transition" data-proj="nha-pho">Nhà phố</button>
                    <button type="button" onclick="filterProjects('van-phong')" class="project-tab-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white border border-slate-200 text-slate-700 hover:bg-slate-100 transition" data-proj="van-phong">Văn phòng</button>
                </div>

                <!-- Grid 15 Dự Án Đà Nẵng: 2 cột trên điện thoại, 3-4 cột trên máy tính, tên hiển thị đầy đủ không cắt chữ -->
                <div id="projects-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
                    
                    <!-- Dự án 1 -->
                    <div class="project-card rounded-xl border border-slate-200 overflow-hidden bg-white shadow-xs hover:shadow-md transition flex flex-col" data-proj-cat="nha-pho">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk&sz=w800';" alt="Dự án Nhà phố hiện đại Phường An Khê Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                        </div>
                        <div class="p-3 sm:p-3.5">
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 product-title-full">Nhà Phố Hiện Đại 3 Tầng – Phường An Khê, Đà Nẵng</h3>
                            <p class="text-[11px] text-slate-500 mt-1">Thi công trọn gói • Đà Nẵng</p>
                        </div>
                    </div>

                    <!-- Dự án 2 -->
                    <div class="project-card rounded-xl border border-slate-200 overflow-hidden bg-white shadow-xs hover:shadow-md transition flex flex-col" data-proj-cat="biet-thu">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1tHGEqsuxKkCkoDofSK_nE70LBMIvGuVW" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1tHGEqsuxKkCkoDofSK_nE70LBMIvGuVW&sz=w800';" alt="Dự án Biệt thự Khu đô thị Hòa Xuân Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                        </div>
                        <div class="p-3 sm:p-3.5">
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 product-title-full">Biệt Thự Hiện Đại 2 Mặt Tiền – Khu Đô Thị Hòa Xuân, Đà Nẵng</h3>
                            <p class="text-[11px] text-slate-500 mt-1">Thiết kế & Thi công • Đà Nẵng</p>
                        </div>
                    </div>

                    <!-- Dự án 3 -->
                    <div class="project-card rounded-xl border border-slate-200 overflow-hidden bg-white shadow-xs hover:shadow-md transition flex flex-col" data-proj-cat="khach-san">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1PjtEF4hlMU_42b438GmEQhYZTba75kRJ" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1PjtEF4hlMU_42b438GmEQhYZTba75kRJ&sz=w800';" alt="Dự án Căn hộ cho thuê Quận Sơn Trà Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                        </div>
                        <div class="p-3 sm:p-3.5">
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 product-title-full">Căn Hộ Cao Cấp View Biển – Quận Sơn Trà, Đà Nẵng</h3>
                            <p class="text-[11px] text-slate-500 mt-1">Khách sạn – Căn hộ • Đà Nẵng</p>
                        </div>
                    </div>

                    <!-- Dự án 4 -->
                    <div class="project-card rounded-xl border border-slate-200 overflow-hidden bg-white shadow-xs hover:shadow-md transition flex flex-col" data-proj-cat="nha-pho">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1m7VasLcMXKPk2-mSVgIdO3USOnbaZ_KA" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1m7VasLcMXKPk2-mSVgIdO3USOnbaZ_KA&sz=w800';" alt="Dự án Nhà phố Khu Nam Việt Á Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                        </div>
                        <div class="p-3 sm:p-3.5">
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 product-title-full">Nhà Phố Anh Tuấn – Khu Đô Thị Nam Việt Á, Đà Nẵng</h3>
                            <p class="text-[11px] text-slate-500 mt-1">Thi công hoàn thiện • Đà Nẵng</p>
                        </div>
                    </div>

                    <!-- Dự án 5 -->
                    <div class="project-card rounded-xl border border-slate-200 overflow-hidden bg-white shadow-xs hover:shadow-md transition flex flex-col" data-proj-cat="khach-san">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1m0Hxp_Pf-urM1DxMd9GP-iuahuQfiznS" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1m0Hxp_Pf-urM1DxMd9GP-iuahuQfiznS&sz=w800';" alt="Dự án Khách sạn và Căn hộ Ngũ Hành Sơn Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                        </div>
                        <div class="p-3 sm:p-3.5">
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 product-title-full">Tòa Nhà Căn Hộ Dịch Vụ – Quận Ngũ Hành Sơn, Đà Nẵng</h3>
                            <p class="text-[11px] text-slate-500 mt-1">Khách sạn – Căn hộ • Đà Nẵng</p>
                        </div>
                    </div>

                    <!-- Dự án 6 -->
                    <div class="project-card rounded-xl border border-slate-200 overflow-hidden bg-white shadow-xs hover:shadow-md transition flex flex-col" data-proj-cat="nha-pho">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1-JeFJVOKB9-b8SOJFIxqa-Mk9ctbIraF" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1-JeFJVOKB9-b8SOJFIxqa-Mk9ctbIraF&sz=w800';" alt="Dự án Nhà phố Quận Thanh Khê Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                        </div>
                        <div class="p-3 sm:p-3.5">
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 product-title-full">Nhà Phố Gia Đình Anh Bình – Quận Thanh Khê, Đà Nẵng</h3>
                            <p class="text-[11px] text-slate-500 mt-1">Xây nhà trọn gói • Đà Nẵng</p>
                        </div>
                    </div>

                    <!-- Dự án 7 -->
                    <div class="project-card rounded-xl border border-slate-200 overflow-hidden bg-white shadow-xs hover:shadow-md transition flex flex-col" data-proj-cat="biet-thu">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1cmI83UnySYJ5Zt1I8A0kB0n94W4XgXgi" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1cmI83UnySYJ5Zt1I8A0kB0n94W4XgXgi&sz=w800';" alt="Dự án Biệt thự nghỉ dưỡng ven sông Hàn Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                        </div>
                        <div class="p-3 sm:p-3.5">
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 product-title-full">Biệt Thự Nghỉ Dưỡng Sân Vườn – Quận Hải Châu, Đà Nẵng</h3>
                            <p class="text-[11px] text-slate-500 mt-1">Biệt thự cao cấp • Đà Nẵng</p>
                        </div>
                    </div>

                    <!-- Dự án 8 -->
                    <div class="project-card rounded-xl border border-slate-200 overflow-hidden bg-white shadow-xs hover:shadow-md transition flex flex-col" data-proj-cat="van-phong">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1G5cVihRDvTKhbx_tNG5uDoSQtvzc0TTt" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1G5cVihRDvTKhbx_tNG5uDoSQtvzc0TTt&sz=w800';" alt="Dự án Thiết kế thi công Văn phòng công ty tại Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                        </div>
                        <div class="p-3 sm:p-3.5">
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 product-title-full">Thiết Kế & Thi Công Văn Phòng Công Ty – TP Đà Nẵng</h3>
                            <p class="text-[11px] text-slate-500 mt-1">Văn phòng – Thương mại • Đà Nẵng</p>
                        </div>
                    </div>

                    <!-- Dự án 9 -->
                    <div class="project-card rounded-xl border border-slate-200 overflow-hidden bg-white shadow-xs hover:shadow-md transition flex flex-col" data-proj-cat="nha-pho">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1ImsuD--QivYj4IV9Nx10yzvXfmuRmZ8x" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1ImsuD--QivYj4IV9Nx10yzvXfmuRmZ8x&sz=w800';" alt="Dự án Nhà phố Chị Ly Nguyễn Chánh Liên Chiểu Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                        </div>
                        <div class="p-3 sm:p-3.5">
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 product-title-full">Nhà Phố Chị Ly – Đường Nguyễn Chánh, Liên Chiểu, Đà Nẵng</h3>
                            <p class="text-[11px] text-slate-500 mt-1">Thi công trọn gói • Đà Nẵng</p>
                        </div>
                    </div>

                    <!-- Dự án 10 -->
                    <div class="project-card rounded-xl border border-slate-200 overflow-hidden bg-white shadow-xs hover:shadow-md transition flex flex-col" data-proj-cat="nha-pho">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/11oZAhO2AsbGFYm1pdsPS5Vtgkd9IP2yZ" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=11oZAhO2AsbGFYm1pdsPS5Vtgkd9IP2yZ&sz=w800';" alt="Dự án Nhà phố Anh Quang Tiểu La Hải Châu Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                        </div>
                        <div class="p-3 sm:p-3.5">
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 product-title-full">Nhà Phố Anh Quang – Đường Tiểu La, Hải Châu, Đà Nẵng</h3>
                            <p class="text-[11px] text-slate-500 mt-1">Thi công phần thô & hoàn thiện • Đà Nẵng</p>
                        </div>
                    </div>

                    <!-- Dự án 11 -->
                    <div class="project-card rounded-xl border border-slate-200 overflow-hidden bg-white shadow-xs hover:shadow-md transition flex flex-col" data-proj-cat="khach-san">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1qgl8kz47lsoa_Ju2l7xRZ5Jjt8DLC7yy" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1qgl8kz47lsoa_Ju2l7xRZ5Jjt8DLC7yy&sz=w800';" alt="Dự án Căn hộ Hồ Biểu Chánh Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                        </div>
                        <div class="p-3 sm:p-3.5">
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 product-title-full">Căn Hộ Cho Thuê Hồ Biểu Chánh – Quận Hải Châu, Đà Nẵng</h3>
                            <p class="text-[11px] text-slate-500 mt-1">Khách sạn – Căn hộ • Đà Nẵng</p>
                        </div>
                    </div>

                    <!-- Dự án 12 -->
                    <div class="project-card rounded-xl border border-slate-200 overflow-hidden bg-white shadow-xs hover:shadow-md transition flex flex-col" data-proj-cat="biet-thu">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1ugKZwI_07LD42SRgLweM-PeRQt9-01Lw" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1ugKZwI_07LD42SRgLweM-PeRQt9-01Lw&sz=w800';" alt="Dự án Biệt thự Khu đô thị FPT City Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                        </div>
                        <div class="p-3 sm:p-3.5">
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 product-title-full">Biệt Thự Gia Đình – Khu Đô Thị FPT City, Đà Nẵng</h3>
                            <p class="text-[11px] text-slate-500 mt-1">Biệt thự hiện đại • Đà Nẵng</p>
                        </div>
                    </div>

                    <!-- Dự án 13 -->
                    <div class="project-card rounded-xl border border-slate-200 overflow-hidden bg-white shadow-xs hover:shadow-md transition flex flex-col" data-proj-cat="nha-pho">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1QcvBpsk1aY6aHVHIVrZs9ALP17TUWfkK" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1QcvBpsk1aY6aHVHIVrZs9ALP17TUWfkK&sz=w800';" alt="Dự án Nhà phố Khu Phước Lý Cẩm Lệ Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                        </div>
                        <div class="p-3 sm:p-3.5">
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 product-title-full">Nhà Phố Anh Phong – Khu Đô Thị Phước Lý, Đà Nẵng</h3>
                            <p class="text-[11px] text-slate-500 mt-1">Thi công trọn gói • Đà Nẵng</p>
                        </div>
                    </div>

                    <!-- Dự án 14 -->
                    <div class="project-card rounded-xl border border-slate-200 overflow-hidden bg-white shadow-xs hover:shadow-md transition flex flex-col" data-proj-cat="van-phong">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1TWxo6uXoJMty8Qsbu4z8HFR5TeLvWph1" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1TWxo6uXoJMty8Qsbu4z8HFR5TeLvWph1&sz=w800';" alt="Dự án Văn phòng kết hợp Nhà ở Quận Cẩm Lệ Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                        </div>
                        <div class="p-3 sm:p-3.5">
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 product-title-full">Tòa Nhà Văn Phòng Kết Hợp Nhà Ở – Quận Cẩm Lệ, Đà Nẵng</h3>
                            <p class="text-[11px] text-slate-500 mt-1">Văn phòng – Thương mại • Đà Nẵng</p>
                        </div>
                    </div>

                    <!-- Dự án 15 -->
                    <div class="project-card rounded-xl border border-slate-200 overflow-hidden bg-white shadow-xs hover:shadow-md transition flex flex-col" data-proj-cat="nha-pho">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1nv_lSxn0mu-71NGKss3abLOuEMcB-bkQ" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1nv_lSxn0mu-71NGKss3abLOuEMcB-bkQ&sz=w800';" alt="Dự án Nhà phố 3 tầng Bắc Sơn An Khê Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                        </div>
                        <div class="p-3 sm:p-3.5">
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 product-title-full">Nhà Phố Hiện Đại Bắc Sơn – Phường An Khê, Đà Nẵng</h3>
                            <p class="text-[11px] text-slate-500 mt-1">Thiết kế & Thi công nội thất • Đà Nẵng</p>
                        </div>
                    </div>

                </div>
            </div>
        </section>

        <!-- 6. BẢNG BÁO GIÁ THAM KHẢO & FORM YÊU CẦU BÁO GIÁ TRANG CHỦ (GIỐNG MẪU TINTRUONGTHINH.COM) -->
        <section id="bao-gia" class="ux-section py-9 bg-white border-t border-slate-200">
            <div class="flatsome-container">
                <div class="section-title-container text-center">
                    <h2 class="section-title-main text-base sm:text-2xl">BÁO GIÁ THIẾT KẾ – THI CÔNG & ĐĂNG KÝ TƯ VẤN</h2>
                    <div class="section-title-line"></div>
                </div>

                <!-- 4 gói báo giá chuẩn web mẫu (Chia 2 cột trên điện thoại, 4 cột trên máy tính) -->
                <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5 mb-8">
                    <div class="rounded-xl border border-slate-200 p-3.5 sm:p-5 bg-slate-50 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-extrabold uppercase text-brand-primary mb-1 product-title-full">Báo Giá Thiết Kế Kiến Trúc</h3>
                            <p class="text-sm sm:text-lg font-extrabold text-amber-600 mb-2">120.000đ – 180.000đ/m²</p>
                            <ul class="text-[11px] sm:text-xs text-slate-600 space-y-1.5">
                                <li>• Phối cảnh 3D mặt tiền & nội thất</li>
                                <li>• Hồ sơ bản vẽ kiến trúc, kết cấu</li>
                                <li>• Bản vẽ điện nước (M&E) chi tiết</li>
                                <li>• Miễn phí khi thi công trọn gói</li>
                            </ul>
                        </div>
                        <a href="#form-bao-gia" class="mt-3 block text-center text-xs font-bold py-2 rounded-lg bg-brand-primary text-white hover:bg-brand-dark transition">Nhận báo giá</a>
                    </div>

                    <div class="rounded-xl border border-slate-200 p-3.5 sm:p-5 bg-slate-50 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-extrabold uppercase text-brand-primary mb-1 product-title-full">Báo Giá Thi Công Phần Thô</h3>
                            <p class="text-sm sm:text-lg font-extrabold text-amber-600 mb-2">3.500.000đ – 3.900.000đ/m²</p>
                            <ul class="text-[11px] sm:text-xs text-slate-600 space-y-1.5">
                                <li>• Vật tư phần thô chuẩn chính hãng</li>
                                <li>• Nhân công hoàn thiện lành nghề</li>
                                <li>• Giám sát kỹ thuật trực tiếp</li>
                                <li>• Bảo hành kết cấu lên đến 05 năm</li>
                            </ul>
                        </div>
                        <a href="#form-bao-gia" class="mt-3 block text-center text-xs font-bold py-2 rounded-lg bg-brand-primary text-white hover:bg-brand-dark transition">Nhận báo giá</a>
                    </div>

                    <div class="rounded-xl border border-slate-200 p-3.5 sm:p-5 bg-slate-50 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-extrabold uppercase text-brand-primary mb-1 product-title-full">Báo Giá Thi Công Hoàn Thiện</h3>
                            <p class="text-sm sm:text-lg font-extrabold text-amber-600 mb-2">2.200.000đ – 3.200.000đ/m²</p>
                            <ul class="text-[11px] sm:text-xs text-slate-600 space-y-1.5">
                                <li>• Ốp lát gạch, đá, sơn bả hoàn thiện</li>
                                <li>• Lắp đặt cửa nhôm kính, lan can</li>
                                <li>• Thiết bị vệ sinh, hệ thống đèn LED</li>
                                <li>• Chống thấm toàn diện công trình</li>
                            </ul>
                        </div>
                        <a href="#form-bao-gia" class="mt-3 block text-center text-xs font-bold py-2 rounded-lg bg-brand-primary text-white hover:bg-brand-dark transition">Nhận báo giá</a>
                    </div>

                    <div class="rounded-xl border border-amber-400 p-3.5 sm:p-5 bg-amber-50/40 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-extrabold uppercase text-brand-primary mb-1 product-title-full">Báo Giá Thi Công Trọn Gói</h3>
                            <p class="text-sm sm:text-lg font-extrabold text-amber-600 mb-2">5.600.000đ – 7.200.000đ/m²</p>
                            <ul class="text-[11px] sm:text-xs text-slate-600 space-y-1.5">
                                <li>• Chìa khóa trao tay từ A đến Z</li>
                                <li>• Tặng 100% chi phí xin phép & thiết kế</li>
                                <li>• Cam kết không phát sinh chi phí</li>
                                <li>• Bảo hành bảo trì tận tâm dài hạn</li>
                            </ul>
                        </div>
                        <a href="#form-bao-gia" class="mt-3 block text-center text-xs font-bold py-2 rounded-lg bg-amber-500 text-slate-950 hover:bg-amber-400 transition">Nhận báo giá</a>
                    </div>
                </div>

                <!-- FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ (Đúng các trường như tintruongthinh.com) -->
                <div id="form-bao-gia" class="rounded-2xl bg-gradient-to-br from-brand-dark via-brand-primary to-[#154d85] p-5 sm:p-8 text-white shadow-lg">
                    <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                        <div class="lg:col-span-5 space-y-3">
                            <span class="inline-block text-xs font-bold uppercase tracking-wider text-amber-400">MIỄN PHÍ TƯ VẤN & KHẢO SÁT TẠI ĐÀ NẴNG</span>
                            <h3 class="text-lg sm:text-2xl font-extrabold uppercase leading-snug">
                                GỬI YÊU CẦU TƯ VẤN & NHẬN BÁO GIÁ CHI TIẾT
                            </h3>
                            <p class="text-xs sm:text-sm text-slate-200 leading-relaxed">
                                Quý khách vui lòng để lại thông tin công trình, Kỹ sư trưởng của <strong>Xây Dựng An Quân Phát</strong> sẽ liên hệ tư vấn phương án thiết kế và lập bảng dự toán chi phí sát thực tế nhất.
                            </p>
                            <div class="space-y-2 pt-1 text-xs sm:text-sm">
                                <p class="flex items-center gap-2"><i class="fa-solid fa-phone text-amber-400"></i> <span>Hotline/Zalo: <strong>0915.500.997</strong></span></p>
                                <p class="flex items-center gap-2"><i class="fa-solid fa-location-dot text-amber-400"></i> <span>Địa chỉ: 310 Bắc Sơn, Phường An Khê, TP Đà Nẵng</span></p>
                                <p class="flex items-center gap-2"><i class="fa-solid fa-globe text-amber-400"></i> <span>Website: anquanphat.com</span></p>
                            </div>
                        </div>

                        <div class="lg:col-span-7">
                            <form id="quoteRequestForm" onsubmit="submitQuoteForm(event)" class="bg-white text-slate-800 rounded-xl p-4 sm:p-6 shadow-md space-y-3.5">
                                <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                    <div>
                                        <label class="block text-xs font-bold text-slate-700 mb-1">Họ tên Quý khách *</label>
                                        <input type="text" id="custName" required placeholder="Nhập họ và tên..." class="w-full rounded-lg border border-slate-300 px-3 py-2 text-xs sm:text-sm focus:border-brand-primary focus:outline-none">
                                    </div>
                                    <div>
                                        <label class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                                        <input type="tel" id="custPhone" required placeholder="Nhập số điện thoại..." class="w-full rounded-lg border border-slate-300 px-3 py-2 text-xs sm:text-sm focus:border-brand-primary focus:outline-none">
                                    </div>
                                </div>

                                <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                    <div>
                                        <label class="block text-xs font-bold text-slate-700 mb-1">Loại công trình</label>
                                        <select id="projectType" class="w-full rounded-lg border border-slate-300 px-3 py-2 text-xs sm:text-sm focus:border-brand-primary focus:outline-none bg-white">
                                            <option value="Nhà phố">Nhà phố</option>
                                            <option value="Khách sạn – Căn hộ cho thuê – Phòng trọ">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                                            <option value="Biệt thự">Biệt thự</option>
                                            <option value="Văn phòng">Văn phòng</option>
                                            <option value="Cải tạo sửa chữa & Nội thất">Cải tạo sửa chữa & Nội thất</option>
                                            <option value="Chưa xác định">Chưa xác định</option>
                                        </select>
                                    </div>
                                    <div>
                                        <label class="block text-xs font-bold text-slate-700 mb-1">Mức đầu tư dự kiến</label>
                                        <select id="budgetLevel" class="w-full rounded-lg border border-slate-300 px-3 py-2 text-xs sm:text-sm focus:border-brand-primary focus:outline-none bg-white">
                                            <option value="1 - 2 tỷ">1 - 2 tỷ</option>
                                            <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                                            <option value="500 triệu - 1 tỷ">500 triệu - 1 tỷ</option>
                                            <option value="2 - 3 tỷ">2 - 3 tỷ</option>
                                            <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                            <option value="Chưa xác định">Chưa xác định</option>
                                        </select>
                                    </div>
                                </div>

                                <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                    <div>
                                        <label class="block text-xs font-bold text-slate-700 mb-1">Email (nếu có)</label>
                                        <input type="email" id="custEmail" placeholder="example@gmail.com" class="w-full rounded-lg border border-slate-300 px-3 py-2 text-xs sm:text-sm focus:border-brand-primary focus:outline-none">
                                    </div>
                                    <div>
                                        <label class="block text-xs font-bold text-slate-700 mb-1">Diện tích đất / Số tầng dự kiến</label>
                                        <input type="text" id="custArea" placeholder="VD: 5x20m, 3 tầng, tại An Khê..." class="w-full rounded-lg border border-slate-300 px-3 py-2 text-xs sm:text-sm focus:border-brand-primary focus:outline-none">
                                    </div>
                                </div>

                                <button type="submit" class="w-full rounded-lg bg-amber-500 hover:bg-amber-400 text-slate-950 font-extrabold text-xs sm:text-sm py-2.5 px-4 transition shadow-xs uppercase">
                                    <i class="fa-solid fa-paper-plane mr-1.5"></i> GỬI YÊU CẦU NHẬN BÁO GIÁ NGAY
                                </button>

                                <div id="quoteSuccessMsg" class="hidden rounded-lg bg-emerald-50 border border-emerald-300 text-emerald-800 p-3 text-xs font-medium"></div>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- 7. DANH MỤC CÁC ĐỐI TÁC (ĐỐI TÁC VẬT TƯ & CUNG ỨNG CHÍNH HÃNG) -->
        <section id="doi-tac" class="ux-section py-8 bg-slate-50 border-t border-slate-200">
            <div class="flatsome-container">
                <div class="section-title-container text-center">
                    <h2 class="section-title-main text-base sm:text-2xl">ĐỐI TÁC & NHÀ CUNG CẤP VẬT LIỆU UY TÍN</h2>
                    <div class="section-title-line"></div>
                    <p class="text-xs sm:text-sm text-slate-600 mt-2">An Quân Phát hợp tác cùng các thương hiệu vật liệu xây dựng & nội thất hàng đầu Việt Nam</p>
                </div>

                <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-6 gap-2.5 sm:gap-4">
                    <div class="bg-white rounded-xl border border-slate-200 p-3.5 text-center shadow-xs flex flex-col items-center justify-center">
                        <span class="text-xs sm:text-sm font-extrabold text-brand-primary">THÉP HÒA PHÁT</span>
                        <span class="text-[11px] text-slate-500 mt-0.5">Thép xây dựng kết cấu</span>
                    </div>
                    <div class="bg-white rounded-xl border border-slate-200 p-3.5 text-center shadow-xs flex flex-col items-center justify-center">
                        <span class="text-xs sm:text-sm font-extrabold text-brand-primary">GỖ AN CƯỜNG</span>
                        <span class="text-[11px] text-slate-500 mt-0.5">Vật liệu nội thất cao cấp</span>
                    </div>
                    <div class="bg-white rounded-xl border border-slate-200 p-3.5 text-center shadow-xs flex flex-col items-center justify-center">
                        <span class="text-xs sm:text-sm font-extrabold text-brand-primary">SƠN DULUX & JOTUN</span>
                        <span class="text-[11px] text-slate-500 mt-0.5">Sơn nước & chống thấm</span>
                    </div>
                    <div class="bg-white rounded-xl border border-slate-200 p-3.5 text-center shadow-xs flex flex-col items-center justify-center">
                        <span class="text-xs sm:text-sm font-extrabold text-brand-primary">INAX & TOTO</span>
                        <span class="text-[11px] text-slate-500 mt-0.5">Thiết bị vệ sinh chính hãng</span>
                    </div>
                    <div class="bg-white rounded-xl border border-slate-200 p-3.5 text-center shadow-xs flex flex-col items-center justify-center">
                        <span class="text-xs sm:text-sm font-extrabold text-brand-primary">NHÔM XINGFA</span>
                        <span class="text-[11px] text-slate-500 mt-0.5">Hệ cửa nhôm kính cao cấp</span>
                    </div>
                    <div class="bg-white rounded-xl border border-slate-200 p-3.5 text-center shadow-xs flex flex-col items-center justify-center">
                        <span class="text-xs sm:text-sm font-extrabold text-brand-primary">PANASONIC & CADIVI</span>
                        <span class="text-[11px] text-slate-500 mt-0.5">Thiết bị điện & cáp điện</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- 8. DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & KINH NGHIỆM XÂY DỰNG GIỐNG WEB MẪU) -->
        <section id="tin-tuc" class="ux-section py-9 bg-white border-t border-slate-200">
            <div class="flatsome-container">
                <div class="section-title-container text-center">
                    <h2 class="section-title-main text-base sm:text-2xl">TIN TỨC & CẨM NANG XÂY DỰNG</h2>
                    <div class="section-title-line"></div>
                </div>

                <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
                <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                    <article class="rounded-xl border border-slate-200 overflow-hidden bg-white shadow-xs flex flex-col">
                        <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1E3FyPE_5YQLtCRIXo7guuebRGYG24g12" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1E3FyPE_5YQLtCRIXo7guuebRGYG24g12&sz=w600';" alt="Hướng dẫn bảo dưỡng bê tông móng đúng cách" class="w-full h-full object-cover">
                        </div>
                        <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="text-xs sm:text-sm font-bold text-brand-primary product-title-full mb-1.5">
                                    Hướng dẫn bảo dưỡng bê tông móng và sàn đúng kỹ thuật
                                </h3>
                                <p class="text-[11px] sm:text-xs text-slate-600 line-clamp-3">
                                    Trong quá trình thi công phần thô, công tác bảo dưỡng ẩm bê tông móng và sàn đóng vai trò quyết định đến cường độ chịu lực và chống nứt công trình.
                                </p>
                            </div>
                            <span class="mt-2.5 text-[11px] font-semibold text-amber-600">Kinh nghiệm thi công • Đà Nẵng</span>
                        </div>
                    </article>

                    <article class="rounded-xl border border-slate-200 overflow-hidden bg-white shadow-xs flex flex-col">
                        <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/17vn5wKHbZgE-xsgLzKw42OzqdPmYTI26" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=17vn5wKHbZgE-xsgLzKw42OzqdPmYTI26&sz=w600';" alt="Tâm lý học không gian nội thất" class="w-full h-full object-cover">
                        </div>
                        <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="text-xs sm:text-sm font-bold text-brand-primary product-title-full mb-1.5">
                                    Tâm lý học không gian: Thiết kế nội thất tác động đến gia đình thế nào?
                                </h3>
                                <p class="text-[11px] sm:text-xs text-slate-600 line-clamp-3">
                                    Cách bố trí ánh sáng tự nhiên, thông gió và màu sắc vật liệu nội thất giúp mang lại năng lượng tích cực và sự thư thái cho mọi thành viên.
                                </p>
                            </div>
                            <span class="mt-2.5 text-[11px] font-semibold text-amber-600">Kiến thức nội thất • An Quân Phát</span>
                        </div>
                    </article>

                    <article class="rounded-xl border border-slate-200 overflow-hidden bg-white shadow-xs flex flex-col">
                        <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1XhH8-wtjhLk_y-pM3LmHkPA--u6120g8" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1XhH8-wtjhLk_y-pM3LmHkPA--u6120g8&sz=w600';" alt="03 Nỗi lo lớn nhất khi xây nhà" class="w-full h-full object-cover">
                        </div>
                        <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="text-xs sm:text-sm font-bold text-brand-primary product-title-full mb-1.5">
                                    03 Nỗi lo lớn nhất khi xây nhà mà Chủ đầu tư cần biết để phòng tránh
                                </h3>
                                <p class="text-[11px] sm:text-xs text-slate-600 line-clamp-3">
                                    Giải pháp kiểm soát dự toán không phát sinh, lựa chọn vật tư đúng chủng loại và giám sát tiến độ thi công nhà trọn gói tại Đà Nẵng.
                                </p>
                            </div>
                            <span class="mt-2.5 text-[11px] font-semibold text-amber-600">Tư vấn xây nhà • Đà Nẵng</span>
                        </div>
                    </article>

                    <article class="rounded-xl border border-slate-200 overflow-hidden bg-white shadow-xs flex flex-col">
                        <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1008JYQjkF3zdVYuV6qXZ56Rw2iTbEO5Y" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1008JYQjkF3zdVYuV6qXZ56Rw2iTbEO5Y&sz=w600';" alt="Thủ tục xin giấy phép xây dựng tại Đà Nẵng" class="w-full h-full object-cover">
                        </div>
                        <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="text-xs sm:text-sm font-bold text-brand-primary product-title-full mb-1.5">
                                    Quy trình xin giấy phép xây dựng và thiết kế hồ sơ thi công tại Đà Nẵng
                                </h3>
                                <p class="text-[11px] sm:text-xs text-slate-600 line-clamp-3">
                                    Tổng hợp đầy đủ hồ sơ pháp lý, mật độ xây dựng, chiều cao tầng và các lưu ý quan trọng khi chuẩn bị khởi công nhà phố, biệt thự.
                                </p>
                            </div>
                            <span class="mt-2.5 text-[11px] font-semibold text-amber-600">Pháp lý xây dựng • Đà Nẵng</span>
                        </div>
                    </article>
                </div>
            </div>
        </section>

        <!-- 9. ĐƯA GOOGLE MAP & FANPAGE FACEBOOK RA NGOÀI TRANG CHỦ -->
        <section id="lien-he" class="ux-section py-9 bg-slate-50 border-t border-slate-200">
            <div class="flatsome-container">
                <div class="section-title-container text-center">
                    <h2 class="section-title-main text-base sm:text-2xl">BẢN ĐỒ TRỤ SỞ GOOGLE MAP & FANPAGE CHÍNH THỨC</h2>
                    <div class="section-title-line"></div>
                    <p class="text-xs sm:text-sm text-slate-600 mt-2">Địa chỉ: 310 Bắc Sơn, Phường An Khê, TP Đà Nẵng • Điện thoại: 0915.500.997</p>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
                    
                    <!-- Bản đồ Google Map ngoài trang chủ -->
                    <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 shadow-xs overflow-hidden flex flex-col">
                        <div class="p-3.5 bg-brand-primary text-white flex flex-wrap items-center justify-between gap-2 text-xs">
                            <span class="font-bold"><i class="fa-solid fa-map-location-dot text-amber-400 mr-1.5"></i> BẢN ĐỒ GOOGLE MAPS: 310 BẮC SƠN, PHƯỜNG AN KHÊ, TP ĐÀ NẴNG</span>
                            <a href="https://www.google.com/maps/search/?api=1&query=310+B%E1%BA%AFc+S%C6%A1n,+Ph%C6%B0%E1%BB%9Dng+An+Kh%C3%AA,+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener noreferrer" class="bg-amber-500 text-slate-950 font-bold px-2.5 py-1 rounded hover:bg-amber-400 transition">
                                Mở chỉ đường lớn
                            </a>
                        </div>
                        <div class="w-full h-[280px] sm:h-[340px] flex-1">
                            <iframe 
                                title="Bản đồ Công Ty TNHH Xây Dựng An Quân Phát - 310 Bắc Sơn, Phường An Khê, TP Đà Nẵng"
                                src="https://maps.google.com/maps?q=310%20B%E1%BA%AFc%20S%C6%A1n,%20An%20Kh%C3%AA,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed" 
                                class="w-full h-full border-0" 
                                allowfullscreen="" 
                                loading="lazy" 
                                referrerpolicy="no-referrer-when-downgrade">
                            </iframe>
                        </div>
                    </div>

                    <!-- Fanpage Facebook ngoài trang chủ -->
                    <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 shadow-xs overflow-hidden flex flex-col justify-between">
                        <div>
                            <div class="p-3.5 bg-[#1877F2] text-white flex items-center justify-between text-xs">
                                <span class="font-bold"><i class="fa-brands fa-facebook mr-1.5"></i> KẾT NỐI FANPAGE FACEBOOK TRANG CHỦ</span>
                                <a href="https://www.facebook.com/cong.ty.tnhh.xay.dung.an.quan.phat" target="_blank" rel="noopener noreferrer" class="bg-white text-[#1877F2] font-bold px-2.5 py-1 rounded hover:bg-slate-100 transition">
                                    Theo dõi trang
                                </a>
                            </div>

                            <div class="p-4 space-y-3">
                                <div class="flex items-center gap-3">
                                    <img 
                                        src="https://lh3.googleusercontent.com/d/1VoQccCJ9Cx6rAny66kwkZb1lZbeH0XRv" 
                                        onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1VoQccCJ9Cx6rAny66kwkZb1lZbeH0XRv&sz=w400';" 
                                        alt="Logo Fanpage An Quân Phát" 
                                        class="w-12 h-12 rounded-lg border border-slate-200 object-contain p-1 bg-white shrink-0"
                                    >
                                    <div>
                                        <h3 class="text-xs sm:text-sm font-extrabold text-brand-primary uppercase">CÔNG TY TNHH XÂY DỰNG AN QUÂN PHÁT</h3>
                                        <p class="text-[11px] text-slate-500">Thiết kế Kiến trúc • Thi công Xây dựng • Nội thất Đà Nẵng</p>
                                    </div>
                                </div>

                                <!-- Nhúng Facebook Page Plugin + Thẻ truy cập trực tiếp Fanpage -->
                                <div class="w-full overflow-hidden rounded-lg border border-slate-200 bg-slate-50 flex justify-center">
                                    <iframe 
                                        title="Fanpage Công Ty TNHH Xây Dựng An Quân Phát"
                                        src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fcong.ty.tnhh.xay.dung.an.quan.phat&tabs=timeline&width=340&height=180&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true" 
                                        width="340" 
                                        height="180" 
                                        style="border:none;overflow:hidden;max-width:100%;" 
                                        scrolling="no" 
                                        frameborder="0" 
                                        allowfullscreen="true" 
                                        allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                                    </iframe>
                                </div>

                                <div class="text-xs text-slate-600 space-y-1 bg-slate-50 p-3 rounded-lg border border-slate-200/80">
                                    <p><strong>Fanpage:</strong> fb.com/cong.ty.tnhh.xay.dung.an.quan.phat</p>
                                    <p><strong>Trụ sở:</strong> 310 Bắc Sơn, Phường An Khê, TP Đà Nẵng</p>
                                    <p><strong>Hotline / Zalo:</strong> <a href="tel:0915500997" class="font-bold text-brand-primary">0915.500.997</a></p>
                                </div>
                            </div>
                        </div>

                        <div class="px-4 pb-4">
                            <a href="https://www.facebook.com/cong.ty.tnhh.xay.dung.an.quan.phat" target="_blank" rel="noopener noreferrer" class="w-full inline-flex items-center justify-center gap-2 rounded-lg bg-[#1877F2] hover:bg-[#166fe5] text-white font-bold text-xs py-2.5 px-4 transition">
                                <i class="fa-brands fa-facebook-messenger"></i> Nhắn Tin Trực Tiếp Trên Fanpage Facebook
                            </a>
                        </div>
                    </div>

                </div>
            </div>
        </section>

    </main>

    <!-- ================= FOOTER (CHUẨN MẪU TINTRUONGTHINH.COM) ================= -->
    <footer class="bg-brand-dark text-slate-200 pt-10 pb-20 md:pb-8 border-t-4 border-amber-500 text-xs sm:text-sm">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-7 pb-8 border-b border-slate-700/80">
                
                <!-- Cột 1: Thông tin công ty -->
                <div class="lg:col-span-5 space-y-3">
                    <div class="flex items-center gap-3">
                        <div class="w-11 h-11 rounded-lg bg-white p-1 flex items-center justify-center shrink-0">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1VoQccCJ9Cx6rAny66kwkZb1lZbeH0XRv" 
                                onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1VoQccCJ9Cx6rAny66kwkZb1lZbeH0XRv&sz=w400';" 
                                alt="Logo Công Ty TNHH Xây Dựng An Quân Phát" 
                                class="w-full h-full object-contain"
                            >
                        </div>
                        <div>
                            <h3 class="text-sm sm:text-base font-extrabold text-white uppercase">CÔNG TY TNHH XÂY DỰNG AN QUÂN PHÁT</h3>
                            <p class="text-xs text-amber-400 font-medium">AN QUAN PHAT CONSTRUCTION CO.,LTD</p>
                        </div>
                    </div>
                    <ul class="space-y-2 text-xs text-slate-300">
                        <li><i class="fa-solid fa-location-dot text-amber-400 w-5"></i> <strong>Trụ sở:</strong> 310 Bắc Sơn, Phường An Khê, TP Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone text-amber-400 w-5"></i> <strong>Hotline / Zalo:</strong> <a href="tel:0915500997" class="text-amber-300 font-bold hover:underline">0915.500.997</a></li>
                        <li><i class="fa-solid fa-globe text-amber-400 w-5"></i> <strong>Website:</strong> <a href="https://anquanphat.com" class="hover:underline">anquanphat.com</a></li>
                        <li><i class="fa-brands fa-facebook text-amber-400 w-5"></i> <strong>Fanpage:</strong> <a href="https://www.facebook.com/cong.ty.tnhh.xay.dung.an.quan.phat" target="_blank" rel="noopener noreferrer" class="hover:underline">facebook.com/cong.ty.tnhh.xay.dung.an.quan.phat</a></li>
                        <li><i class="fa-solid fa-id-card text-amber-400 w-5"></i> <strong>Mã số thuế:</strong> 0402077732</li>
                    </ul>
                </div>

                <!-- Cột 2: Lĩnh vực hoạt động -->
                <div class="lg:col-span-4 space-y-2.5">
                    <h4 class="text-xs sm:text-sm font-extrabold uppercase text-amber-400 tracking-wide">LĨNH VỰC HOẠT ĐỘNG</h4>
                    <ul class="space-y-2 text-xs text-slate-300">
                        <li><a href="#linh-vuc-hoat-dong" onclick="filterServices('thiet-ke')" class="hover:text-white transition">• Thiết kế Kiến trúc – Nội thất</a></li>
                        <li><a href="#linh-vuc-hoat-dong" onclick="filterServices('phan-tho')" class="hover:text-white transition">• Thi công xây dựng phần thô</a></li>
                        <li><a href="#linh-vuc-hoat-dong" onclick="filterServices('hoan-thien')" class="hover:text-white transition">• Thi công hoàn thiện công trình</a></li>
                        <li><a href="#linh-vuc-hoat-dong" onclick="filterServices('noi-that')" class="hover:text-white transition">• Sản xuất & Thi công nội thất trọn gói</a></li>
                        <li><a href="#cong-trinh-thuc-te" class="hover:text-white transition">• Xây dựng Khách sạn – Căn hộ – Biệt thự – Nhà phố</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Danh mục nhanh -->
                <div class="lg:col-span-3 space-y-2.5">
                    <h4 class="text-xs sm:text-sm font-extrabold uppercase text-amber-400 tracking-wide">HỖ TRỢ KHÁCH HÀNG</h4>
                    <ul class="space-y-2 text-xs text-slate-300">
                        <li><a href="#bao-gia" class="hover:text-white transition">• Báo giá thiết kế kiến trúc</a></li>
                        <li><a href="#bao-gia" class="hover:text-white transition">• Báo giá thi công phần thô</a></li>
                        <li><a href="#bao-gia" class="hover:text-white transition">• Báo giá thi công hoàn thiện</a></li>
                        <li><a href="#bao-gia" class="hover:text-white transition">• Báo giá xây nhà trọn gói</a></li>
                        <li><a href="#lien-he" class="hover:text-white transition">• Chỉ đường Google Maps</a></li>
                    </ul>
                </div>

            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-[11px] text-slate-400 text-center sm:text-left">
                <p>Copyright © CÔNG TY TNHH XÂY DỰNG AN QUÂN PHÁT (anquanphat.com). All rights reserved.</p>
                <p>Địa chỉ: 310 Bắc Sơn, Phường An Khê, TP Đà Nẵng • Hotline: 0915.500.997</p>
            </div>
        </div>
    </footer>

    <!-- ================= CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH MÁY TÍNH & ĐIỆN THOẠI ================= -->
    <div class="fixed left-3 bottom-4 z-50 flex flex-col gap-2.5">
        <!-- Nút Zalo -->
        <a 
            href="https://zalo.me/0915500997" 
            target="_blank" 
            rel="noopener noreferrer" 
            aria-label="Chat Zalo 0915.500.997"
            class="group flex items-center gap-2 bg-[#0068ff] hover:bg-[#0052cc] text-white rounded-full p-2.5 sm:px-3.5 sm:py-2 shadow-lg transition"
        >
            <span class="w-6 h-6 rounded-full bg-white text-[#0068ff] font-extrabold text-[11px] flex items-center justify-center shrink-0">Zalo</span>
            <span class="hidden sm:inline text-xs font-bold pr-1">Chat Zalo</span>
        </a>

        <!-- Nút Facebook Fanpage -->
        <a 
            href="https://www.facebook.com/cong.ty.tnhh.xay.dung.an.quan.phat" 
            target="_blank" 
            rel="noopener noreferrer" 
            aria-label="Fanpage Facebook An Quân Phát"
            class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#145dbf] text-white rounded-full p-2.5 sm:px-3.5 sm:py-2 shadow-lg transition"
        >
            <span class="w-6 h-6 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0">
                <i class="fa-brands fa-facebook-f text-xs"></i>
            </span>
            <span class="hidden sm:inline text-xs font-bold pr-1">Fanpage</span>
        </a>

        <!-- Nút Gọi Hotline nổi bật -->
        <a 
            href="tel:0915500997" 
            aria-label="Gọi Hotline 0915.500.997"
            class="pulse-btn flex items-center gap-2 bg-amber-500 hover:bg-amber-400 text-slate-950 rounded-full px-3 py-2 shadow-lg transition"
        >
            <span class="w-6 h-6 rounded-full bg-slate-950 text-amber-400 flex items-center justify-center shrink-0">
                <i class="fa-solid fa-phone-volume text-xs"></i>
            </span>
            <span class="text-xs font-extrabold pr-1">0915.500.997</span>
        </a>
    </div>

    <!-- ================= JAVASCRIPT XỬ LÝ SLIDER TỰ TRƯỢT, BỘ LỌC DANH MỤC & FORM BÁO GIÁ ================= -->
    <script>
        // 1. Điều khiển Menu Điện thoại
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobile-menu-drawer');
            const icon = document.getElementById('mobile-menu-icon');
            if (drawer.classList.contains('hidden')) {
                drawer.classList.remove('hidden');
                icon.classList.remove('fa-bars');
                icon.classList.add('fa-xmark');
            } else {
                drawer.classList.add('hidden');
                icon.classList.remove('fa-xmark');
                icon.classList.add('fa-bars');
            }
        }

        // 2. Điều khiển 2 Ảnh Banner Tự Trượt Chuyên Nghiệp
        let currentBannerIdx = 0;
        const bannerSlides = document.querySelectorAll('.banner-slide');
        const bannerDots = document.querySelectorAll('.banner-dot');
        let bannerInterval = null;

        function renderBanner(index) {
            currentBannerIdx = (index + bannerSlides.length) % bannerSlides.length;
            bannerSlides.forEach((slide, i) => {
                if (i === currentBannerIdx) {
                    slide.classList.remove('opacity-0', 'z-0');
                    slide.classList.add('opacity-100', 'z-10');
                } else {
                    slide.classList.remove('opacity-100', 'z-10');
                    slide.classList.add('opacity-0', 'z-0');
                }
            });
            bannerDots.forEach((dot, i) => {
                if (i === currentBannerIdx) {
                    dot.classList.remove('w-2.5', 'bg-white/60');
                    dot.classList.add('w-6', 'bg-amber-400');
                } else {
                    dot.classList.remove('w-6', 'bg-amber-400');
                    dot.classList.add('w-2.5', 'bg-white/60');
                }
            });
        }

        function nextBanner() {
            renderBanner(currentBannerIdx + 1);
            resetBannerTimer();
        }

        function prevBanner() {
            renderBanner(currentBannerIdx - 1);
            resetBannerTimer();
        }

        function goToBanner(idx) {
            renderBanner(idx);
            resetBannerTimer();
        }

        function resetBannerTimer() {
            if (bannerInterval) clearInterval(bannerInterval);
            bannerInterval = setInterval(() => {
                renderBanner(currentBannerIdx + 1);
            }, 4500);
        }

        // 3. Lọc Danh mục Lĩnh vực hoạt động & Sản phẩm
        function filterServices(category) {
            const cards = document.querySelectorAll('.service-card');
            const buttons = document.querySelectorAll('.service-tab-btn');

            buttons.forEach(btn => {
                if (btn.getAttribute('data-tab') === category) {
                    btn.classList.remove('bg-slate-100', 'text-slate-700');
                    btn.classList.add('bg-brand-primary', 'text-white');
                } else {
                    btn.classList.remove('bg-brand-primary', 'text-white');
                    btn.classList.add('bg-slate-100', 'text-slate-700');
                }
            });

            cards.forEach(card => {
                const cats = card.getAttribute('data-category') || '';
                if (category === 'all' || cats.includes(category)) {
                    card.classList.remove('hidden');
                } else {
                    card.classList.add('hidden');
                }
            });
        }

        // 4. Lọc Danh mục Dự án thực tế tại Đà Nẵng
        function filterProjects(category) {
            const cards = document.querySelectorAll('.project-card');
            const buttons = document.querySelectorAll('.project-tab-btn');

            buttons.forEach(btn => {
                if (btn.getAttribute('data-proj') === category) {
                    btn.classList.remove('bg-white', 'text-slate-700', 'border', 'border-slate-200');
                    btn.classList.add('bg-brand-primary', 'text-white');
                } else {
                    btn.classList.remove('bg-brand-primary', 'text-white');
                    btn.classList.add('bg-white', 'text-slate-700', 'border', 'border-slate-200');
                }
            });

            cards.forEach(card => {
                const cat = card.getAttribute('data-proj-cat') || '';
                if (category === 'all' || cat === category) {
                    card.classList.remove('hidden');
                } else {
                    card.classList.add('hidden');
                }
            });
        }

        // 5. Xử lý gửi Form Yêu cầu & Báo giá trên trang chủ
        function submitQuoteForm(e) {
            e.preventDefault();
            const name = document.getElementById('custName').value.trim();
            const phone = document.getElementById('custPhone').value.trim();
            const type = document.getElementById('projectType').value;
            const budget = document.getElementById('budgetLevel').value;
            const area = document.getElementById('custArea').value.trim();
            const msgBox = document.getElementById('quoteSuccessMsg');

            msgBox.classList.remove('hidden');
            msgBox.innerHTML = `Cảm ơn <strong>${name}</strong> (SĐT: <strong>${phone}</strong>)! Yêu cầu báo giá hạng mục <strong>${type}</strong> (Mức đầu tư: ${budget}${area ? ', Quy mô: ' + area : ''}) đã được ghi nhận. Bộ phận Kỹ thuật <strong>Xây Dựng An Quân Phát (0915.500.997)</strong> sẽ liên hệ tư vấn ngay cho Quý khách.`;
            document.getElementById('quoteRequestForm').reset();
        }

        window.onload = function() {
            resetBannerTimer();
        };
    </script>
</body>
</html>
