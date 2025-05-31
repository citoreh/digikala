<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Digikala 1402 - داستان شگفت‌انگیز ما</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Vazir', 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
            background: linear-gradient(135deg, #e91e63 0%, #f44336 100%);
            color: #333;
            overflow-x: hidden;
            direction: rtl;
        }

        .story-section {
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
            padding: 2rem;
        }

        .hero {
            background: linear-gradient(135deg, #e91e63 0%, #f44336 100%);
            color: white;
            text-align: center;
        }

        .hero h1 {
            font-size: 4rem;
            font-weight: 800;
            margin-bottom: 1rem;
            opacity: 0;
            transform: translateY(50px);
            animation: fadeInUp 1s ease forwards;
        }

        .hero p {
            font-size: 1.5rem;
            opacity: 0;
            transform: translateY(30px);
            animation: fadeInUp 1s ease 0.3s forwards;
            max-width: 800px;
            margin: 0 auto;
            line-height: 1.6;
        }

        .digikala-logo {
            width: 200px;
            margin: 2rem auto;
            opacity: 0;
            animation: fadeInUp 1s ease 0.6s forwards;
        }

        .scroll-indicator {
            position: absolute;
            bottom: 2rem;
            left: 50%;
            transform: translateX(-50%);
            opacity: 0;
            animation: fadeIn 1s ease 1s forwards, bounce 2s ease-in-out 2s infinite;
        }

        .scroll-indicator::after {
            content: '↓';
            font-size: 2rem;
            color: white;
        }

        .stats-section {
            background: #f8fafc;
            flex-direction: column;
        }

        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 2rem;
            max-width: 1400px;
            width: 100%;
        }

        .stat-card {
            background: white;
            padding: 2.5rem;
            border-radius: 20px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            text-align: center;
            transform: translateY(100px);
            opacity: 0;
            transition: all 0.8s ease;
            border-top: 4px solid #e91e63;
        }

        .stat-card.visible {
            transform: translateY(0);
            opacity: 1;
        }

        .stat-number {
            font-size: 3.5rem;
            font-weight: bold;
            background: linear-gradient(135deg, #e91e63, #f44336);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin-bottom: 0.5rem;
        }

        .stat-label {
            color: #64748b;
            font-size: 1.2rem;
            font-weight: 600;
        }

        .story-text {
            max-width: 900px;
            margin: 2rem auto;
            font-size: 1.3rem;
            line-height: 1.8;
            text-align: center;
            opacity: 0;
            transform: translateY(30px);
            transition: all 0.8s ease;
        }

        .story-text.visible {
            opacity: 1;
            transform: translateY(0);
        }

        .story-text h2 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            background: linear-gradient(135deg, #e91e63, #f44336);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .interactive-chart {
            background: white;
            border-radius: 20px;
            padding: 2.5rem;
            margin: 2rem auto;
            max-width: 700px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            opacity: 0;
            transform: scale(0.8);
            transition: all 1s ease;
        }

        .interactive-chart.visible {
            opacity: 1;
            transform: scale(1);
        }

        .chart-bar {
            display: flex;
            align-items: center;
            margin: 1.5rem 0;
        }

        .chart-label {
            width: 140px;
            font-weight: 600;
            color: #334155;
            text-align: right;
        }

        .chart-progress {
            flex: 1;
            height: 24px;
            background: #e2e8f0;
            border-radius: 12px;
            margin: 0 1rem;
            overflow: hidden;
        }

        .chart-fill {
            height: 100%;
            background: linear-gradient(90deg, #e91e63, #f44336);
            border-radius: 12px;
            width: 0%;
            transition: width 2s ease;
        }

        .chart-value {
            font-weight: bold;
            color: #475569;
            min-width: 60px;
        }

        .gen-z-section {
            background: linear-gradient(135deg, #8e44ad 0%, #3498db 100%);
            color: white;
        }

        .gen-z-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            max-width: 1000px;
        }

        .gen-z-card {
            background: rgba(255,255,255,0.1);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            padding: 2rem;
            text-align: center;
            transform: rotateY(90deg);
            opacity: 0;
            transition: all 1s ease;
        }

        .gen-z-card.visible {
            transform: rotateY(0deg);
            opacity: 1;
        }

        .timeline {
            background: #1a202c;
            color: white;
        }

        .timeline-container {
            max-width: 1100px;
            position: relative;
        }

        .timeline-item {
            display: flex;
            align-items: center;
            margin: 3rem 0;
            opacity: 0;
            transform: translateX(-100px);
            transition: all 0.8s ease;
        }

        .timeline-item:nth-child(even) {
            transform: translateX(100px);
            flex-direction: row-reverse;
        }

        .timeline-item.visible {
            opacity: 1;
            transform: translateX(0);
        }

        .timeline-icon {
            width: 70px;
            height: 70px;
            background: linear-gradient(135deg, #e91e63, #f44336);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.8rem;
            margin: 0 2rem;
            flex-shrink: 0;
        }

        .timeline-content {
            flex: 1;
            text-align: right;
        }

        .timeline-item:nth-child(even) .timeline-content {
            text-align: left;
        }

        .timeline-title {
            font-size: 1.6rem;
            font-weight: bold;
            margin-bottom: 0.5rem;
        }

        .quiz-section {
            background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
            color: white;
            text-align: center;
        }

        .quiz-card {
            background: rgba(255,255,255,0.15);
            backdrop-filter: blur(15px);
            border-radius: 20px;
            padding: 2.5rem;
            max-width: 600px;
            margin: 2rem auto;
            border: 1px solid rgba(255,255,255,0.2);
        }

        .quiz-button {
            background: white;
            color: #f5576c;
            border: none;
            padding: 1.2rem 2.5rem;
            border-radius: 50px;
            font-weight: bold;
            cursor: pointer;
            margin: 0.7rem;
            transition: all 0.3s ease;
            font-size: 1rem;
        }

        .quiz-button:hover {
            transform: scale(1.05);
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);
        }

        .floating-elements {
            position: absolute;
            width: 100%;
            height: 100%;
            pointer-events: none;
            overflow: hidden;
        }

        .floating-element {
            position: absolute;
            opacity: 0.15;
            animation: float 15s ease-in-out infinite;
            font-size: 2rem;
        }

        @keyframes float {
            0%, 100% {
                transform: translateY(0) rotate(0deg);
            }
            50% {
                transform: translateY(-30px) rotate(180deg);
            }
        }

        @keyframes fadeInUp {
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes fadeIn {
            to {
                opacity: 1;
            }
        }

        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% {
                transform: translateX(-50%) translateY(0);
            }
            40% {
                transform: translateX(-50%) translateY(-10px);
            }
            60% {
                transform: translateX(-50%) translateY(-5px);
            }
        }

        .discount-section {
            background: linear-gradient(135deg, #ff6b6b 0%, #ee5a24 100%);
            color: white;
        }

        .discount-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1.5rem;
            max-width: 800px;
        }

        .discount-item {
            background: rgba(255,255,255,0.1);
            padding: 1.5rem;
            border-radius: 15px;
            text-align: center;
            transform: scale(0);
            opacity: 0;
            transition: all 0.6s ease;
        }

        .discount-item.visible {
            transform: scale(1);
            opacity: 1;
        }

        .seller-card, .delivery-card, .service-card, .eco-card, .success-story, .coverage-item, .contact-channel,
        .ai-card, .ai-feature, .app-card, .app-feature-item, .tech-card, .tech-innovation, .innovation-card, .coming-soon {
            background: rgba(255,255,255,0.15);
            backdrop-filter: blur(10px);
            border-radius: 15px;
            padding: 2rem;
            text-align: center;
            transform: translateY(50px);
            opacity: 0;
            transition: all 0.8s ease;
            border: 1px solid rgba(255,255,255,0.2);
        }

        .seller-card.visible, .delivery-card.visible, .service-card.visible, .eco-card.visible, 
        .success-story.visible, .coverage-item.visible, .contact-channel.visible,
        .ai-card.visible, .ai-feature.visible, .app-card.visible, .app-feature-item.visible,
        .tech-card.visible, .tech-innovation.visible, .innovation-card.visible, .coming-soon.visible {
            transform: translateY(0);
            opacity: 1;
        }

        .seller-card:hover, .delivery-card:hover, .service-card:hover, .eco-card:hover,
        .ai-card:hover, .app-card:hover, .tech-card:hover, .innovation-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 40px rgba(0,0,0,0.2);
        }

        .app-feature-item, .coming-soon {
            padding: 1.5rem;
        }

        .tech-innovation {
            text-align: left;
            padding: 1.5rem;
        }

        .innovation-card {
            background: rgba(255,255,255,0.1);
            border: 1px solid rgba(255,255,255,0.3);
            text-align: left;
        }

        /* Gamification Styles */
        .achievement-badge {
            background: rgba(255,255,255,0.1);
            border: 2px solid rgba(255,255,255,0.3);
            border-radius: 20px;
            padding: 2rem;
            text-align: center;
            cursor: pointer;
            transition: all 0.5s ease;
            position: relative;
            overflow: hidden;
        }

        .achievement-badge.locked {
            filter: grayscale(100%);
            opacity: 0.6;
        }

        .achievement-badge.unlocked {
            filter: grayscale(0%);
            opacity: 1;
            border-color: #f39c12;
            background: rgba(243, 156, 18, 0.2);
            animation: unlockPulse 1s ease;
        }

        .achievement-badge:hover {
            transform: scale(1.05);
            border-color: #f39c12;
        }

        .badge-icon {
            font-size: 3rem;
            margin-bottom: 1rem;
            transition: all 0.5s ease;
        }

        .achievement-badge.unlocked .badge-icon {
            animation: bounceIcon 0.8s ease;
        }

        .badge-title {
            font-size: 1.2rem;
            font-weight: bold;
            margin-bottom: 0.5rem;
        }

        .badge-desc {
            font-size: 0.9rem;
            opacity: 0.8;
            margin-bottom: 1rem;
        }

        .unlock-progress {
            margin-top: 1rem;
        }

        .progress-bar {
            background: rgba(255,255,255,0.2);
            height: 8px;
            border-radius: 4px;
            overflow: hidden;
            margin-bottom: 0.5rem;
        }

        .progress-fill {
            height: 100%;
            background: linear-gradient(90deg, #f39c12, #e74c3c);
            width: 0%;
            transition: width 2s ease;
        }

        .progress-text {
            font-size: 0.8rem;
            opacity: 0.7;
        }

        .milestone {
            background: rgba(255,255,255,0.1);
            border-radius: 15px;
            padding: 1.5rem;
            text-align: center;
            cursor: pointer;
            transition: all 0.3s ease;
            border: 2px solid transparent;
        }

        .milestone:hover {
            background: rgba(255,255,255,0.2);
            border-color: rgba(255,255,255,0.3);
            transform: translateY(-5px);
        }

        .milestone.active {
            border-color: #f39c12;
            background: rgba(243, 156, 18, 0.2);
        }

        .challenge-btn:hover {
            background: rgba(255,255,255,0.2) !important;
            border-color: rgba(255,255,255,0.5) !important;
            transform: scale(1.02);
        }

        .challenge-btn.correct {
            background: rgba(39, 174, 96, 0.3) !important;
            border-color: #27ae60 !important;
            animation: correctAnswer 0.6s ease;
        }

        .challenge-btn.incorrect {
            background: rgba(231, 76, 60, 0.3) !important;
            border-color: #e74c3c !important;
            animation: shake 0.6s ease;
        }

        .reward-level {
            background: rgba(255,255,255,0.1);
            border: 2px solid rgba(255,255,255,0.2);
            border-radius: 20px;
            padding: 2rem;
            text-align: center;
            transition: all 0.3s ease;
        }

        .reward-level.current {
            border-color: #f39c12;
            background: rgba(243, 156, 18, 0.2);
            animation: currentLevel 2s ease infinite;
        }

        .reward-icon {
            font-size: 3rem;
            margin-bottom: 1rem;
        }

        .reward-title {
            font-size: 1.3rem;
            font-weight: bold;
            margin-bottom: 0.5rem;
        }

        .reward-range {
            font-size: 0.9rem;
            opacity: 0.8;
            margin-bottom: 0.5rem;
        }

        .reward-benefit {
            font-size: 0.8rem;
            background: rgba(255,255,255,0.1);
            padding: 0.5rem;
            border-radius: 10px;
        }

        @keyframes unlockPulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.1); }
            100% { transform: scale(1); }
        }

        @keyframes bounceIcon {
            0%, 20%, 50%, 80%, 100% { transform: translateY(0); }
            40% { transform: translateY(-20px); }
            60% { transform: translateY(-10px); }
        }

        @keyframes correctAnswer {
            0% { transform: scale(1); }
            50% { transform: scale(1.1); }
            100% { transform: scale(1); }
        }

        @keyframes shake {
            0%, 100% { transform: translateX(0); }
            10%, 30%, 50%, 70%, 90% { transform: translateX(-5px); }
            20%, 40%, 60%, 80% { transform: translateX(5px); }
        }

        @keyframes currentLevel {
            0%, 100% { box-shadow: 0 0 0 0 rgba(243, 156, 18, 0.7); }
            50% { box-shadow: 0 0 0 20px rgba(243, 156, 18, 0); }
        }

        @keyframes unlockMessage {
            0% { 
                opacity: 0; 
                transform: translate(-50%, -50%) scale(0.5); 
            }
            20% { 
                opacity: 1; 
                transform: translate(-50%, -50%) scale(1.1); 
            }
            30% { 
                transform: translate(-50%, -50%) scale(1); 
            }
            70% { 
                opacity: 1; 
                transform: translate(-50%, -50%) scale(1); 
            }
            100% { 
                opacity: 0; 
                transform: translate(-50%, -50%) scale(0.8); 
            }
        }

        /* Social Sharing Styles */
        .stat-bubble {
            background: rgba(255,255,255,0.1);
            border-radius: 15px;
            padding: 1rem;
            text-align: center;
            backdrop-filter: blur(5px);
        }

        .share-btn {
            transition: all 0.3s ease !important;
        }

        .share-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);
        }

        .challenge-template {
            transition: all 0.3s ease;
        }

        .challenge-template:hover {
            border-color: rgba(255,255,255,0.5) !important;
            background: rgba(255,255,255,0.2) !important;
            transform: translateY(-5px);
        }

        .challenge-template.selected {
            border-color: #f39c12 !important;
            background: rgba(243, 156, 18, 0.2) !important;
        }

        .leaderboard-item {
            transition: all 0.3s ease;
        }

        .leaderboard-item:hover {
            transform: translateX(10px);
            background: rgba(255,255,255,0.1) !important;
        }

        .your-rank {
            animation: yourRankPulse 2s ease-in-out infinite;
        }

        @keyframes yourRankPulse {
            0%, 100% {
                box-shadow: 0 0 0 0 rgba(243, 156, 18, 0.7);
            }
            50% {
                box-shadow: 0 0 0 15px rgba(243, 156, 18, 0);
            }
        }

        #shareable-badge-display {
            position: relative;
            overflow: hidden;
        }

        #shareable-badge-display::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: linear-gradient(45deg, transparent, rgba(255,255,255,0.1), transparent);
            animation: shimmer 3s ease-in-out infinite;
        }

        @keyframes shimmer {
            0% {
                transform: translateX(-100%) translateY(-100%) rotate(45deg);
            }
            50% {
                transform: translateX(100%) translateY(100%) rotate(45deg);
            }
            100% {
                transform: translateX(-100%) translateY(-100%) rotate(45deg);
            }
        }

        .showcase-badge {
            font-size: 2rem;
            padding: 0.5rem;
            background: rgba(255,255,255,0.1);
            border-radius: 10px;
            backdrop-filter: blur(5px);
            transition: all 0.3s ease;
        }

        .showcase-badge.earned {
            background: rgba(243, 156, 18, 0.3);
            animation: badgeGlow 2s ease-in-out infinite;
        }

        @keyframes badgeGlow {
            0%, 100% {
                box-shadow: 0 0 10px rgba(243, 156, 18, 0.5);
            }
            50% {
                box-shadow: 0 0 20px rgba(243, 156, 18, 0.8);
            }
        }

        /* Share notification styles */
        .share-notification {
            position: fixed;
            top: 2rem;
            right: 2rem;
            background: linear-gradient(135deg, #27ae60, #2ecc71);
            color: white;
            padding: 1rem 2rem;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
            z-index: 1000;
            animation: slideInNotification 0.5s ease forwards;
        }

        @keyframes slideInNotification {
            from {
                transform: translateX(100%);
                opacity: 0;
            }
            to {
                transform: translateX(0);
                opacity: 1;
            }
        }

        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2.5rem;
            }
            
            .hero p {
                font-size: 1.1rem;
            }
            
            .stats-grid {
                grid-template-columns: 1fr;
            }
            
            .timeline-item {
                flex-direction: column !important;
                text-align: center !important;
            }
            
            .timeline-content {
                text-align: center !important;
            }
        }
    </style>
</head>
<body>
    <!-- Hero Section -->
    <section class="story-section hero">
        <div class="floating-elements">
            <div class="floating-element" style="top: 10%; left: 10%;">🛒</div>
            <div class="floating-element" style="top: 20%; right: 15%;">📱</div>
            <div class="floating-element" style="bottom: 30%; left: 20%;">📦</div>
            <div class="floating-element" style="top: 40%; right: 10%;">🚚</div>
            <div class="floating-element" style="top: 60%; left: 5%;">💳</div>
            <div class="floating-element" style="bottom: 15%; right: 20%;">⭐</div>
        </div>
        <div>
            <div class="digikala-logo">
                <svg width="200" height="60" viewBox="0 0 200 60" style="fill: white;">
                    <text x="100" y="35" text-anchor="middle" font-size="24" font-weight="bold">دیجی‌کالا</text>
                </svg>
            </div>
            <h1>گزارش سال ۱۴۰۲</h1>
            <p>داستان شگفت‌انگیز ما با شما! آماده‌اید تا بدانید چه اتفاقات باورنکردنی‌ای رخ داده؟ بیایید با هم سفری هیجان‌انگیز در دنیای آمار و دستاوردهایمان داشته باشیم!</p>
        </div>
        <div class="scroll-indicator"></div>
    </section>

    <!-- Main Stats Section -->
    <section class="story-section stats-section">
        <div class="story-text">
            <h2>🎯 آمارهای باورنکردنی سال ۱۴۰۲</h2>
            <p>تصور کنید چه اتفاقی افتاده! شما عزیزان نه فقط خرید کردید، بلکه رکوردهای جدیدی خلق کردید. بیایید این داستان شگفت‌انگیز را با اعداد تعریف کنیم...</p>
        </div>
        
        <div class="stats-grid">
            <div class="stat-card" data-delay="0">
                <div class="stat-number" data-target="42000000">0</div>
                <div class="stat-label">کاربر فعال و خوشحال</div>
            </div>
            <div class="stat-card" data-delay="200">
                <div class="stat-number" data-target="285000000">0</div>
                <div class="stat-label">بازدید در سال ۱۴۰۲</div>
            </div>
            <div class="stat-card" data-delay="400">
                <div class="stat-number" data-target="156000000">0</div>
                <div class="stat-label">سفارش تحویل داده شده</div>
            </div>
            <div class="stat-card" data-delay="600">
                <div class="stat-number" data-target="3200">0</div>
                <div class="stat-label">شغل جدید ایجاد شده</div>
            </div>
            <div class="stat-card" data-delay="800">
                <div class="stat-number" data-target="18500000">0</div>
                <div class="stat-label">کالای متنوع</div>
            </div>
            <div class="stat-card" data-delay="1000">
                <div class="stat-number" data-target="97">0%</div>
                <div class="stat-label">رضایت مشتریان</div>
            </div>
        </div>
    </section>

    <!-- Top Searches Section -->
    <section class="story-section">
        <div class="story-text">
            <h2>🔍 محبوب‌ترین جستجوها و خریدها</h2>
            <p>بدانید چه چیزهایی دل شما را برده؟ اینجا لیست پرطرفدارترین کالاهای سال ۱۴۰۲ است...</p>
        </div>
        
        <div class="interactive-chart">
            <h3 style="margin-bottom: 2rem; text-align: center; color: #334155;">پرفروش‌ترین دسته‌بندی‌ها</h3>
            <div class="chart-bar">
                <div class="chart-label">گوشی موبایل</div>
                <div class="chart-progress">
                    <div class="chart-fill" data-width="92"></div>
                </div>
                <div class="chart-value">۹۲٪</div>
            </div>
            <div class="chart-bar">
                <div class="chart-label">پوشاک</div>
                <div class="chart-progress">
                    <div class="chart-fill" data-width="78"></div>
                </div>
                <div class="chart-value">۷۸٪</div>
            </div>
            <div class="chart-bar">
                <div class="chart-label">لوازم خانگی</div>
                <div class="chart-progress">
                    <div class="chart-fill" data-width="74"></div>
                </div>
                <div class="chart-value">۷۴٪</div>
            </div>
            <div class="chart-bar">
                <div class="chart-label">کتاب</div>
                <div class="chart-progress">
                    <div class="chart-fill" data-width="65"></div>
                </div>
                <div class="chart-value">۶۵٪</div>
            </div>
            <div class="chart-bar">
                <div class="chart-label">آرایشی بهداشتی</div>
                <div class="chart-progress">
                    <div class="chart-fill" data-width="58"></div>
                </div>
                <div class="chart-value">۵۸٪</div>
            </div>
        </div>
    </section>

    <!-- Gen Z Section -->
    <section class="story-section gen-z-section">
        <div class="story-text" style="color: white;">
            <h2>🚀 نسل Z و دیجی‌کالا</h2>
            <p>جوان‌های عزیز ما چطور با دیجی‌کالا ارتباط برقرار کردند؟ آمارهای جالب از فعالیت نسل Z...</p>
        </div>
        
        <div class="gen-z-grid">
            <div class="gen-z-card" data-delay="0">
                <div style="font-size: 3rem; margin-bottom: 1rem;">📱</div>
                <div style="font-size: 2rem; font-weight: bold; margin-bottom: 0.5rem;">۸۵٪</div>
                <div>خرید از طریق اپلیکیشن موبایل</div>
            </div>
            <div class="gen-z-card" data-delay="200">
                <div style="font-size: 3rem; margin-bottom: 1rem;">⚡</div>
                <div style="font-size: 2rem; font-weight: bold; margin-bottom: 0.5rem;">۳ دقیقه</div>
                <div>میانگین زمان تصمیم‌گیری برای خرید</div>
            </div>
            <div class="gen-z-card" data-delay="400">
                <div style="font-size: 3rem; margin-bottom: 1rem;">🎯</div>
                <div style="font-size: 2rem; font-weight: bold; margin-bottom: 0.5rem;">۷۲٪</div>
                <div>علاقه به برندهای جدید و مدرن</div>
            </div>
            <div class="gen-z-card" data-delay="600">
                <div style="font-size: 3rem; margin-bottom: 1rem;">💫</div>
                <div style="font-size: 2rem; font-weight: bold; margin-bottom: 0.5rem;">۹۱٪</div>
                <div>استفاده از پیشنهادات هوشمند</div>
            </div>
        </div>
    </section>

    <!-- Discount Section -->
    <section class="story-section discount-section">
        <div class="story-text" style="color: white;">
            <h2>💸 شگفت‌انگیزترین تخفیف‌های سال</h2>
            <p>سال ۱۴۰۲ مملو از تخفیف‌های باورنکردنی بود! ببینید چه صرفه‌جویی‌هایی کردید...</p>
        </div>
        
        <div class="discount-grid">
            <div class="discount-item" data-delay="0">
                <div style="font-size: 2rem; margin-bottom: 0.5rem;">🔥</div>
                <div style="font-size: 1.5rem; font-weight: bold;">۷۰٪</div>
                <div>بیشترین تخفیف</div>
            </div>
            <div class="discount-item" data-delay="200">
                <div style="font-size: 2rem; margin-bottom: 0.5rem;">💰</div>
                <div style="font-size: 1.5rem; font-weight: bold;">۲۸۰ میلیارد</div>
                <div>صرفه‌جویی شما (تومان)</div>
            </div>
            <div class="discount-item" data-delay="400">
                <div style="font-size: 2rem; margin-bottom: 0.5rem;">⚡</div>
                <div style="font-size: 1.5rem; font-weight: bold;">شگفت‌انگیز</div>
                <div>محبوب‌ترین حراجی</div>
            </div>
            <div class="discount-item" data-delay="600">
                <div style="font-size: 2rem; margin-bottom: 0.5rem;">🎁</div>
                <div style="font-size: 1.5rem; font-weight: bold;">۱۲ میلیون</div>
                <div>هدیه رایگان</div>
            </div>
        </div>
    </section>

    <!-- Timeline Section -->
    <section class="story-section timeline">
        <div class="story-text" style="color: white;">
            <h2>📅 مهم‌ترین رویدادهای سال ۱۴۰۲</h2>
            <p>از لحظه‌های "اوه واو!" تا رکوردهای "باورتون میشه؟"، سفری در زمان با ما داشته باشید...</p>
        </div>
        
        <div class="timeline-container">
            <div class="timeline-item">
                <div class="timeline-icon">🎊</div>
                <div class="timeline-content">
                    <div class="timeline-title">فروردین: شروعی پرقدرت</div>
                    <p>سال نو، رکورد نو! ۸ میلیون سفارش تنها در هفته اول سال</p>
                </div>
            </div>
            <div class="timeline-item">
                <div class="timeline-icon">🚀</div>
                <div class="timeline-content">
                    <div class="timeline-title">خرداد: راه‌اندازی بخش‌های جدید</div>
                    <p>پلتفرم ما گسترش یافت - چون چرا به همین یک چیز بسنده کنیم؟</p>
                </div>
            </div>
            <div class="timeline-item">
                <div class="timeline-icon">🤖</div>
                <div class="timeline-content">
                    <div class="timeline-title">شهریور: انقلاب هوش مصنوعی</div>
                    <p>پیشنهادات هوشمند رونمایی شد. عقل از سر رفت!</p>
                </div>
            </div>
            <div class="timeline-item">
                <div class="timeline-icon">💼</div>
                <div class="timeline-content">
                    <div class="timeline-title">آبان: اشتغال‌زایی رکوردی</div>
                    <p>۳۲۰۰ شغل جدید در ۱۷ سال گذشته ایجاد کردیم</p>
                </div>
            </div>
            <div class="timeline-item">
                <div class="timeline-icon">🎯</div>
                <div class="timeline-content">
                    <div class="timeline-title">اسفند: جشن پایان سال</div>
                    <p>پرفروش‌ترین ماه تاریخ! شما عزیزان واقعاً فوق‌العاده هستید</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Seller Success Stories Section -->
    <section class="story-section" style="background: linear-gradient(135deg, #2ecc71 0%, #27ae60 100%); color: white;">
        <div style="max-width: 1200px; width: 100%;">
            <div class="story-text" style="color: white;">
                <h2>🏪 داستان‌های موفقیت فروشندگان</h2>
                <p>فروشندگان عزیز ما قهرمان‌های واقعی سال ۱۴۰۲ بودند! ببینید چه دستاوردهای شگفت‌انگیزی کسب کردند...</p>
            </div>
            
            <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem; margin-top: 3rem;">
                <div class="seller-card" data-delay="0">
                    <div style="font-size: 3rem; margin-bottom: 1rem;">📈</div>
                    <div style="font-size: 2.5rem; font-weight: bold; margin-bottom: 0.5rem;">۱۸۵٪</div>
                    <div style="font-size: 1.1rem;">میانگین رشد فروش سالانه</div>
                    <div style="margin-top: 1rem; font-size: 0.9rem; opacity: 0.9;">فروشندگان کوچک، رشد بزرگ!</div>
                </div>
                
                <div class="seller-card" data-delay="200">
                    <div style="font-size: 3rem; margin-bottom: 1rem;">🏆</div>
                    <div style="font-size: 2.5rem; font-weight: bold; margin-bottom: 0.5rem;">۱۲۰۰</div>
                    <div style="font-size: 1.1rem;">فروشنده جدید موفق</div>
                    <div style="margin-top: 1rem; font-size: 0.9rem; opacity: 0.9;">از صفر تا قهرمان در یک سال</div>
                </div>
                
                <div class="seller-card" data-delay="400">
                    <div style="font-size: 3rem; margin-bottom: 1rem;">💰</div>
                    <div style="font-size: 2.5rem; font-weight: bold; margin-bottom: 0.5rem;">۴۸ میلیارد</div>
                    <div style="font-size: 1.1rem;">درآمد فروشندگان (تومان)</div>
                    <div style="margin-top: 1rem; font-size: 0.9rem; opacity: 0.9;">رکورد تاریخی درآمدزایی</div>
                </div>
            </div>

            <div style="margin-top: 3rem; padding: 2rem; background: rgba(255,255,255,0.1); border-radius: 20px; backdrop-filter: blur(10px);">
                <h3 style="text-align: center; margin-bottom: 2rem; font-size: 1.8rem;">داستان موفقیت ویژه</h3>
                <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 2rem; text-align: center;">
                    <div class="success-story" data-delay="0">
                        <div style="font-size: 2rem; margin-bottom: 1rem;">👨‍💼</div>
                        <div style="font-weight: bold; margin-bottom: 0.5rem;">آقای احمدی</div>
                        <div style="font-size: 0.9rem;">از ۵ سفارش روزانه به ۵۰۰ سفارش!</div>
                    </div>
                    <div class="success-story" data-delay="200">
                        <div style="font-size: 2rem; margin-bottom: 1rem;">👩‍💼</div>
                        <div style="font-weight: bold; margin-bottom: 0.5rem;">خانم زمانی</div>
                        <div style="font-size: 0.9rem;">کسب‌وکار خانگی به برند ملی تبدیل شد</div>
                    </div>
                    <div class="success-story" data-delay="400">
                        <div style="font-size: 2rem; margin-bottom: 1rem;">🏭</div>
                        <div style="font-weight: bold; margin-bottom: 0.5rem;">کارخانه نساجی کاشان</div>
                        <div style="font-size: 0.9rem;">صادرات محصولات به ۱۵ کشور</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Delivery Excellence Section -->
    <section class="story-section" style="background: linear-gradient(135deg, #3498db 0%, #2980b9 100%); color: white;">
        <div style="max-width: 1200px; width: 100%;">
            <div class="story-text" style="color: white;">
                <h2>🚚 قدرت تحویل سریع</h2>
                <p>سرعت نور؟ نه! سرعت دیجی‌کالا! ببینید چطور سفارش‌هایتان با سرعت باورنکردنی به دستتان رسید...</p>
            </div>
            
            <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 2rem;">
                <div class="delivery-card" data-delay="0">
                    <div style="font-size: 3rem; margin-bottom: 1rem;">⚡</div>
                    <div style="font-size: 2.5rem; font-weight: bold; margin-bottom: 0.5rem;">۲۴ ساعت</div>
                    <div style="font-size: 1.1rem;">میانگین زمان تحویل</div>
                </div>
                
                <div class="delivery-card" data-delay="200">
                    <div style="font-size: 3rem; margin-bottom: 1rem;">🗺️</div>
                    <div style="font-size: 2.5rem; font-weight: bold; margin-bottom: 0.5rem;">۱۴۵۰</div>
                    <div style="font-size: 1.1rem;">شهر تحت پوشش</div>
                </div>
                
                <div class="delivery-card" data-delay="400">
                    <div style="font-size: 3rem; margin-bottom: 1rem;">✅</div>
                    <div style="font-size: 2.5rem; font-weight: bold; margin-bottom: 0.5rem;">۹۸.۵٪</div>
                    <div style="font-size: 1.1rem;">تحویل موفق</div>
                </div>
                
                <div class="delivery-card" data-delay="600">
                    <div style="font-size: 3rem; margin-bottom: 1rem;">🚛</div>
                    <div style="font-size: 2.5rem; font-weight: bold; margin-bottom: 0.5rem;">۸۵۰۰</div>
                    <div style="font-size: 1.1rem;">پیک فعال</div>
                </div>
            </div>

            <div style="margin-top: 3rem;">
                <div class="delivery-map" style="background: rgba(255,255,255,0.1); border-radius: 20px; padding: 2rem; backdrop-filter: blur(10px);">
                    <h3 style="text-align: center; margin-bottom: 2rem;">پوشش سراسری ما</h3>
                    <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(150px, 1fr)); gap: 1rem; text-align: center;">
                        <div class="coverage-item" data-delay="0">
                            <div style="font-size: 1.5rem;">🏔️</div>
                            <div style="font-weight: bold;">شمال کشور</div>
                            <div style="font-size: 0.9rem;">۱۰۰٪ پوشش</div>
                        </div>
                        <div class="coverage-item" data-delay="200">
                            <div style="font-size: 1.5rem;">🏜️</div>
                            <div style="font-weight: bold;">مناطق مرکزی</div>
                            <div style="font-size: 0.9rem;">۹۸٪ پوشش</div>
                        </div>
                        <div class="coverage-item" data-delay="400">
                            <div style="font-size: 1.5rem;">🌊</div>
                            <div style="font-weight: bold;">جنوب کشور</div>
                            <div style="font-size: 0.9rem;">۹۵٪ پوشش</div>
                        </div>
                        <div class="coverage-item" data-delay="600">
                            <div style="font-size: 1.5rem;">⛰️</div>
                            <div style="font-weight: bold;">مناطق کوهستانی</div>
                            <div style="font-size: 0.9rem;">۸۷٪ پوشش</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Customer Service Excellence -->
    <section class="story-section" style="background: linear-gradient(135deg, #9b59b6 0%, #8e44ad 100%); color: white;">
        <div style="max-width: 1000px; width: 100%;">
            <div class="story-text" style="color: white;">
                <h2>🎧 خدمات مشتریان فوق‌العاده</h2>
                <p>تیم پشتیبانی ما ۲۴/۷ آماده خدمت! ببینید چطور مشکلاتتان را در کمترین زمان حل کردیم...</p>
            </div>
            
            <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 2rem;">
                <div class="service-card" data-delay="0">
                    <div style="font-size: 3rem; margin-bottom: 1rem;">📞</div>
                    <div style="font-size: 2.5rem; font-weight: bold; margin-bottom: 0.5rem;">۴۵ ثانیه</div>
                    <div style="font-size: 1.1rem;">میانگین پاسخگویی</div>
                </div>
                
                <div class="service-card" data-delay="200">
                    <div style="font-size: 3rem; margin-bottom: 1rem;">😊</div>
                    <div style="font-size: 2.5rem; font-weight: bold; margin-bottom: 0.5rem;">۹۶٪</div>
                    <div style="font-size: 1.1rem;">رضایت از پشتیبانی</div>
                </div>
                
                <div class="service-card" data-delay="400">
                    <div style="font-size: 3rem; margin-bottom: 1rem;">🔄</div>
                    <div style="font-size: 2.5rem; font-weight: bold; margin-bottom: 0.5rem;">۹۲٪</div>
                    <div style="font-size: 1.1rem;">حل مشکل در اولین تماس</div>
                </div>
                
                <div class="service-card" data-delay="600">
                    <div style="font-size: 3rem; margin-bottom: 1rem;">💬</div>
                    <div style="font-size: 2.5rem; font-weight: bold; margin-bottom: 0.5rem;">۱۲ میلیون</div>
                    <div style="font-size: 1.1rem;">تماس پاسخ داده شده</div>
                </div>
            </div>

            <div style="margin-top: 3rem; text-align: center;">
                <div style="background: rgba(255,255,255,0.1); border-radius: 20px; padding: 2rem; backdrop-filter: blur(10px);">
                    <h3 style="margin-bottom: 1.5rem;">کانال‌های ارتباطی ما</h3>
                    <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(120px, 1fr)); gap: 1.5rem;">
                        <div class="contact-channel" data-delay="0">
                            <div style="font-size: 2rem; margin-bottom: 0.5rem;">📱</div>
                            <div>تلفن</div>
                        </div>
                        <div class="contact-channel" data-delay="100">
                            <div style="font-size: 2rem; margin-bottom: 0.5rem;">💬</div>
                            <div>چت آنلاین</div>
                        </div>
                        <div class="contact-channel" data-delay="200">
                            <div style="font-size: 2rem; margin-bottom: 0.5rem;">📧</div>
                            <div>ایمیل</div>
                        </div>
                        <div class="contact-channel" data-delay="300">
                            <div style="font-size: 2rem; margin-bottom: 0.5rem;">📲</div>
                            <div>اپلیکیشن</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- AI & Technology Innovation Section -->
    <section class="story-section" style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); color: white;">
        <div style="max-width: 1200px; width: 100%;">
            <div class="story-text" style="color: white;">
                <h2>🤖 انقلاب هوش مصنوعی دیجی‌کالا</h2>
                <p>سال ۱۴۰۲ سال هوش مصنوعی بود! ببینید چطور AI زندگی خریدتان را راحت‌تر کرد...</p>
            </div>
            
            <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 2rem;">
                <div class="ai-card" data-delay="0">
                    <div style="font-size: 3rem; margin-bottom: 1rem;">🎯</div>
                    <div style="font-size: 2.5rem; font-weight: bold; margin-bottom: 0.5rem;">۸۷٪</div>
                    <div style="font-size: 1.2rem; font-weight: 600;">دقت پیشنهادات هوشمند</div>
                    <div style="margin-top: 1rem; font-size: 0.9rem; opacity: 0.9;">AI می‌داند شما چه می‌خواهید!</div>
                </div>
                
                <div class="ai-card" data-delay="200">
                    <div style="font-size: 3rem; margin-bottom: 1rem;">🔍</div>
                    <div style="font-size: 2.5rem; font-weight: bold; margin-bottom: 0.5rem;">۹۲٪</div>
                    <div style="font-size: 1.2rem; font-weight: 600;">بهبود جستجوی صوتی</div>
                    <div style="margin-top: 1rem; font-size: 0.9rem; opacity: 0.9;">حرف بزنید، ما پیدا می‌کنیم!</div>
                </div>
                
                <div class="ai-card" data-delay="400">
                    <div style="font-size: 3rem; margin-bottom: 1rem;">📊</div>
                    <div style="font-size: 2.5rem; font-weight: bold; margin-bottom: 0.5rem;">۵ ثانیه</div>
                    <div style="font-size: 1.2rem; font-weight: 600;">سرعت بارگذاری صفحات</div>
                    <div style="margin-top: 1rem; font-size: 0.9rem; opacity: 0.9;">سریع‌تر از برق!</div>
                </div>
                
                <div class="ai-card" data-delay="600">
                    <div style="font-size: 3rem; margin-bottom: 1rem;">🛡️</div>
                    <div style="font-size: 2.5rem; font-weight: bold; margin-bottom: 0.5rem;">۹۹.۵٪</div>
                    <div style="font-size: 1.2rem; font-weight: 600;">تشخیص کالای تقلبی</div>
                    <div style="margin-top: 1rem; font-size: 0.9rem; opacity: 0.9;">AI محافظ شماست</div>
                </div>
            </div>

            <div style="margin-top: 3rem; padding: 2rem; background: rgba(255,255,255,0.1); border-radius: 20px; backdrop-filter: blur(10px);">
                <h3 style="text-align: center; margin-bottom: 2rem; font-size: 1.8rem;">ویژگی‌های هوشمند جدید</h3>
                <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 2rem;">
                    <div class="ai-feature" data-delay="0">
                        <div style="font-size: 2rem; margin-bottom: 1rem;">🎨</div>
                        <div style="font-weight: bold; margin-bottom: 0.5rem;">جستجوی تصویری</div>
                        <div style="font-size: 0.9rem;">عکس بگیرید، ما پیدا می‌کنیم</div>
                    </div>
                    <div class="ai-feature" data-delay="200">
                        <div style="font-size: 2rem; margin-bottom: 1rem;">💬</div>
                        <div style="font-weight: bold; margin-bottom: 0.5rem;">چت‌بات هوشمند</div>
                        <div style="font-size: 0.9rem;">پاسخ فوری به سوالاتتان</div>
                    </div>
                    <div class="ai-feature" data-delay="400">
                        <div style="font-size: 2rem; margin-bottom: 1rem;">📱</div>
                        <div style="font-weight: bold; margin-bottom: 0.5rem;">تشخیص رفتار کاربر</div>
                        <div style="font-size: 0.9rem;">تجربه شخصی‌سازی شده</div>
                    </div>
                    <div class="ai-feature" data-delay="600">
                        <div style="font-size: 2rem; margin-bottom: 1rem;">⚡</div>
                        <div style="font-weight: bold; margin-bottom: 0.5rem;">پیش‌بینی تقاضا</div>
                        <div style="font-size: 0.9rem;">همیشه موجود برای شما</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- App Innovation Section -->
    <section class="story-section" style="background: linear-gradient(135deg, #ff6b6b 0%, #ee5a24 100%); color: white;">
        <div style="max-width: 1200px; width: 100%;">
            <div class="story-text" style="color: white;">
                <h2>📱 اپلیکیشن نسل جدید</h2>
                <p>اپ دیجی‌کالا کاملاً متحول شد! ببینید چه ویژگی‌های شگفت‌انگیزی اضافه شده...</p>
            </div>
            
            <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 2rem;">
                <div class="app-card" data-delay="0">
                    <div style="font-size: 3rem; margin-bottom: 1rem;">⚡</div>
                    <div style="font-size: 2.5rem; font-weight: bold; margin-bottom: 0.5rem;">۳۰٪</div>
                    <div style="font-size: 1.2rem; font-weight: 600;">سریع‌تر از نسخه قبل</div>
                    <div style="margin-top: 1rem; font-size: 0.9rem; opacity: 0.9;">بهینه‌سازی کامل کدها</div>
                </div>
                
                <div class="app-card" data-delay="200">
                    <div style="font-size: 3rem; margin-bottom: 1rem;">🎨</div>
                    <div style="font-size: 2.5rem; font-weight: bold; margin-bottom: 0.5rem;">تم تیره</div>
                    <div style="font-size: 1.2rem; font-weight: 600;">محافظت از چشمان شما</div>
                    <div style="margin-top: 1rem; font-size: 0.9rem; opacity: 0.9;">طراحی زیبا و مدرن</div>
                </div>
                
                <div class="app-card" data-delay="400">
                    <div style="font-size: 3rem; margin-bottom: 1rem;">🔍</div>
                    <div style="font-size: 2.5rem; font-weight: bold; margin-bottom: 0.5rem;">جستجو هوشمند</div>
                    <div style="font-size: 1.2rem; font-weight: 600;">پیشنهاد خودکار کلمات</div>
                    <div style="margin-top: 1rem; font-size: 0.9rem; opacity: 0.9;">حتی املا اشتباه هم مشکلی نیست!</div>
                </div>
                
                <div class="app-card" data-delay="600">
                    <div style="font-size: 3rem; margin-bottom: 1rem;">📲</div>
                    <div style="font-size: 2.5rem; font-weight: bold; margin-bottom: 0.5rem;">آفلاین</div>
                    <div style="font-size: 1.2rem; font-weight: 600;">مرور بدون اینترنت</div>
                    <div style="margin-top: 1rem; font-size: 0.9rem; opacity: 0.9;">کش هوشمند محتوا</div>
                </div>
            </div>

            <div style="margin-top: 3rem;">
                <div style="background: rgba(255,255,255,0.1); border-radius: 20px; padding: 2rem; backdrop-filter: blur(10px);">
                    <h3 style="text-align: center; margin-bottom: 2rem;">ویژگی‌های انحصاری اپ</h3>
                    
                    <div class="app-features-grid" style="display: grid; grid-template-columns: repeat(auto-fit, minmax(180px, 1fr)); gap: 1.5rem; text-align: center;">
                        <div class="app-feature-item" data-delay="0">
                            <div style="font-size: 2rem; margin-bottom: 0.5rem;">🛒</div>
                            <div style="font-weight: bold; margin-bottom: 0.3rem;">خرید سریع</div>
                            <div style="font-size: 0.9rem;">یک کلیک، خرید کامل</div>
                        </div>
                        
                        <div class="app-feature-item" data-delay="100">
                            <div style="font-size: 2rem; margin-bottom: 0.5rem;">🎁</div>
                            <div style="font-weight: bold; margin-bottom: 0.3rem;">جایزه روزانه</div>
                            <div style="font-size: 0.9rem;">هر روز ورود، هر روز جایزه</div>
                        </div>
                        
                        <div class="app-feature-item" data-delay="200">
                            <div style="font-size: 2rem; margin-bottom: 0.5rem;">🔔</div>
                            <div style="font-weight: bold; margin-bottom: 0.3rem;">هشدار قیمت</div>
                            <div style="font-size: 0.9rem;">کاهش قیمت رو از دست ندید</div>
                        </div>
                        
                        <div class="app-feature-item" data-delay="300">
                            <div style="font-size: 2rem; margin-bottom: 0.5rem;">📍</div>
                            <div style="font-weight: bold; margin-bottom: 0.3rem;">پیگیری زنده</div>
                            <div style="font-size: 0.9rem;">مسیر پیک را ببینید</div>
                        </div>
                        
                        <div class="app-feature-item" data-delay="400">
                            <div style="font-size: 2rem; margin-bottom: 0.5rem;">💳</div>
                            <div style="font-weight: bold; margin-bottom: 0.3rem;">کیف پول دیجیتال</div>
                            <div style="font-size: 0.9rem;">پرداخت سریع و آسان</div>
                        </div>
                        
                        <div class="app-feature-item" data-delay="500">
                            <div style="font-size: 2rem; margin-bottom: 0.5rem;">🤝</div>
                            <div style="font-weight: bold; margin-bottom: 0.3rem;">خرید گروهی</div>
                            <div style="font-size: 0.9rem;">با دوستان تخفیف بگیرید</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Tech Infrastructure Section -->
    <section class="story-section" style="background: linear-gradient(135deg, #2c3e50 0%, #34495e 100%); color: white;">
        <div style="max-width: 1200px; width: 100%;">
            <div class="story-text" style="color: white;">
                <h2>🏗️ زیرساخت فن‌آوری قدرتمند</h2>
                <p>پشت صحنه دیجی‌کالا چه خبر است؟ ببینید چه فناوری‌های پیشرفته‌ای داریم...</p>
            </div>
            
            <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 2rem;">
                <div class="tech-card" data-delay="0">
                    <div style="font-size: 3rem; margin-bottom: 1rem;">💾</div>
                    <div style="font-size: 2rem; font-weight: bold; margin-bottom: 0.5rem;">۵۰۰ TB</div>
                    <div style="font-size: 1.1rem; font-weight: 600;">ظرفیت ذخیره‌سازی</div>
                    <div style="margin-top: 1rem; font-size: 0.9rem; opacity: 0.9;">داده‌های عظیم، مدیریت هوشمند</div>
                </div>
                
                <div class="tech-card" data-delay="200">
                    <div style="font-size: 3rem; margin-bottom: 1rem;">⚡</div>
                    <div style="font-size: 2rem; font-weight: bold; margin-bottom: 0.5rem;">۹۹.۹٪</div>
                    <div style="font-size: 1.1rem; font-weight: 600;">آپتایم سیستم</div>
                    <div style="margin-top: 1rem; font-size: 0.9rem; opacity: 0.9;">همیشه در دسترس شما</div>
                </div>
                
                <div class="tech-card" data-delay="400">
                    <div style="font-size: 3rem; margin-bottom: 1rem;">🔒</div>
                    <div style="font-size: 2rem; font-weight: bold; margin-bottom: 0.5rem;">۲۵۶ بیت</div>
                    <div style="font-size: 1.1rem; font-weight: 600;">رمزنگاری امنیتی</div>
                    <div style="margin-top: 1rem; font-size: 0.9rem; opacity: 0.9;">حریم خصوصی شما مقدس است</div>
                </div>
                
                <div class="tech-card" data-delay="600">
                    <div style="font-size: 3rem; margin-bottom: 1rem;">🌐</div>
                    <div style="font-size: 2rem; font-weight: bold; margin-bottom: 0.5rem;">۱۵ CDN</div>
                    <div style="font-size: 1.1rem; font-weight: 600;">شبکه توزیع محتوا</div>
                    <div style="margin-top: 1rem; font-size: 0.9rem; opacity: 0.9;">سرعت بالا در همه جا</div>
                </div>
            </div>

            <div style="margin-top: 3rem; padding: 2rem; background: rgba(255,255,255,0.05); border-radius: 20px; backdrop-filter: blur(10px);">
                <h3 style="text-align: center; margin-bottom: 2rem; font-size: 1.8rem;">فناوری‌های نوین</h3>
                <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 2rem;">
                    <div class="tech-innovation" data-delay="0">
                        <div style="display: flex; align-items: center; margin-bottom: 1rem;">
                            <div style="font-size: 2rem; margin-left: 1rem;">🤖</div>
                            <div>
                                <div style="font-weight: bold;">Machine Learning</div>
                                <div style="font-size: 0.9rem; opacity: 0.8;">الگوریتم‌های یادگیری ماشین</div>
                            </div>
                        </div>
                        <div style="font-size: 0.9rem;">پیش‌بینی رفتار مشتری و بهینه‌سازی موجودی</div>
                    </div>
                    
                    <div class="tech-innovation" data-delay="200">
                        <div style="display: flex; align-items: center; margin-bottom: 1rem;">
                            <div style="font-size: 2rem; margin-left: 1rem;">☁️</div>
                            <div>
                                <div style="font-weight: bold;">Cloud Computing</div>
                                <div style="font-size: 0.9rem; opacity: 0.8;">محاسبات ابری مقیاس‌پذیر</div>
                            </div>
                        </div>
                        <div style="font-size: 0.9rem;">زیرساخت انعطاف‌پذیر برای رشد بی‌نهایت</div>
                    </div>
                    
                    <div class="tech-innovation" data-delay="400">
                        <div style="display: flex; align-items: center; margin-bottom: 1rem;">
                            <div style="font-size: 2rem; margin-left: 1rem;">📊</div>
                            <div>
                                <div style="font-weight: bold;">Big Data Analytics</div>
                                <div style="font-size: 0.9rem; opacity: 0.8;">تحلیل کلان‌داده‌ها</div>
                            </div>
                        </div>
                        <div style="font-size: 0.9rem;">درک عمیق از نیازهای مشتریان</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Innovation Lab Section -->
    <section class="story-section" style="background: linear-gradient(135deg, #8e44ad 0%, #9b59b6 100%); color: white;">
        <div style="max-width: 1000px; width: 100%;">
            <div class="story-text" style="color: white;">
                <h2>🔬 آزمایشگاه نوآوری دیجی‌کالا</h2>
                <p>آینده را امروز می‌سازیم! ببینید چه فناوری‌های جذابی در راه است...</p>
            </div>
            
            <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 2rem; margin-top: 2rem;">
                <div class="innovation-card" data-delay="0">
                    <div style="font-size: 3rem; margin-bottom: 1rem;">🥽</div>
                    <div style="font-size: 1.5rem; font-weight: bold; margin-bottom: 1rem;">واقعیت مجازی</div>
                    <div style="font-size: 0.95rem; line-height: 1.6;">کالاها را قبل از خرید در خانه‌تان امتحان کنید. فرش، مبل، لوازم خانگی... همه را مجازی در خانه ببینید!</div>
                </div>
                
                <div class="innovation-card" data-delay="200">
                    <div style="font-size: 3rem; margin-bottom: 1rem;">🚁</div>
                    <div style="font-size: 1.5rem; font-weight: bold; margin-bottom: 1rem;">تحویل با پهپاد</div>
                    <div style="font-size: 0.95rem; line-height: 1.6;">سفارش‌های اورژانسی در کمتر از ۳۰ دقیقه! پهپادهای هوشمند ما آماده پرواز هستند.</div>
                </div>
                
                <div class="innovation-card" data-delay="400">
                    <div style="font-size: 3rem; margin-bottom: 1rem;">🧠</div>
                    <div style="font-size: 1.5rem; font-weight: bold; margin-bottom: 1rem;">AI مکالمه‌ای</div>
                    <div style="font-size: 0.95rem; line-height: 1.6;">مشاور خرید شخصی که مثل انسان با شما صحبت می‌کند و بهترین پیشنهادها را می‌دهد.</div>
                </div>
            </div>

            <div style="margin-top: 3rem; text-align: center; padding: 2rem; background: rgba(255,255,255,0.1); border-radius: 20px; backdrop-filter: blur(10px);">
                <h3 style="margin-bottom: 1.5rem; font-size: 1.6rem;">🚀 در حال توسعه</h3>
                <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(150px, 1fr)); gap: 1.5rem;">
                    <div class="coming-soon" data-delay="0">
                        <div style="font-size: 1.8rem; margin-bottom: 0.5rem;">🔮</div>
                        <div style="font-weight: bold; font-size: 0.9rem;">پیش‌بینی نیاز</div>
                    </div>
                    <div class="coming-soon" data-delay="100">
                        <div style="font-size: 1.8rem; margin-bottom: 0.5rem;">🎯</div>
                        <div style="font-weight: bold; font-size: 0.9rem;">تبلیغات شخصی</div>
                    </div>
                    <div class="coming-soon" data-delay="200">
                        <div style="font-size: 1.8rem; margin-bottom: 0.5rem;">🛍️</div>
                        <div style="font-weight: bold; font-size: 0.9rem;">خرید صوتی</div>
                    </div>
                    <div class="coming-soon" data-delay="300">
                        <div style="font-size: 1.8rem; margin-bottom: 0.5rem;">🤖</div>
                        <div style="font-weight: bold; font-size: 0.9rem;">ربات انبارداری</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Achievement Badges Section -->
    <section class="story-section" style="background: linear-gradient(135deg, #f39c12 0%, #e67e22 100%); color: white;">
        <div style="max-width: 1200px; width: 100%;">
            <div class="story-text" style="color: white;">
                <h2>🏆 مدال‌های افتخار ۱۴۰۲</h2>
                <p>امسال چه مدال‌هایی کسب کردیم؟ بیایید جشن بگیریم! هر کلیک، یک مدال آزاد می‌کند...</p>
            </div>
            
            <div id="achievement-container" style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 2rem; margin-top: 2rem;">
                <div class="achievement-badge locked" data-achievement="customers" onclick="unlockAchievement(this)">
                    <div class="badge-icon">🔒</div>
                    <div class="badge-title">پادشاه مشتریان</div>
                    <div class="badge-desc">۴۲ میلیون کاربر فعال</div>
                    <div class="unlock-progress">
                        <div class="progress-bar">
                            <div class="progress-fill" data-progress="100"></div>
                        </div>
                        <div class="progress-text">کلیک کنید تا باز شود!</div>
                    </div>
                </div>
                
                <div class="achievement-badge locked" data-achievement="speed" onclick="unlockAchievement(this)">
                    <div class="badge-icon">🔒</div>
                    <div class="badge-title">ماستر سرعت</div>
                    <div class="badge-desc">تحویل در ۲۴ ساعت</div>
                    <div class="unlock-progress">
                        <div class="progress-bar">
                            <div class="progress-fill" data-progress="100"></div>
                        </div>
                        <div class="progress-text">کلیک کنید تا باز شود!</div>
                    </div>
                </div>
                
                <div class="achievement-badge locked" data-achievement="ai" onclick="unlockAchievement(this)">
                    <div class="badge-icon">🔒</div>
                    <div class="badge-title">قهرمان هوش مصنوعی</div>
                    <div class="badge-desc">۸۷٪ دقت AI</div>
                    <div class="unlock-progress">
                        <div class="progress-bar">
                            <div class="progress-fill" data-progress="100"></div>
                        </div>
                        <div class="progress-text">کلیک کنید تا باز شود!</div>
                    </div>
                </div>
                
                <div class="achievement-badge locked" data-achievement="satisfaction" onclick="unlockAchievement(this)">
                    <div class="badge-icon">🔒</div>
                    <div class="badge-title">افسانه رضایت</div>
                    <div class="badge-desc">۹۷٪ رضایت مشتریان</div>
                    <div class="unlock-progress">
                        <div class="progress-bar">
                            <div class="progress-fill" data-progress="100"></div>
                        </div>
                        <div class="progress-text">کلیک کنید تا باز شود!</div>
                    </div>
                </div>
                
                <div class="achievement-badge locked" data-achievement="growth" onclick="unlockAchievement(this)">
                    <div class="badge-icon">🔒</div>
                    <div class="badge-title">امپراتور رشد</div>
                    <div class="badge-desc">۱۸۵٪ رشد فروشندگان</div>
                    <div class="unlock-progress">
                        <div class="progress-bar">
                            <div class="progress-fill" data-progress="100"></div>
                        </div>
                        <div class="progress-text">کلیک کنید تا باز شود!</div>
                    </div>
                </div>
                
                <div class="achievement-badge locked" data-achievement="eco" onclick="unlockAchievement(this)">
                    <div class="badge-icon">🔒</div>
                    <div class="badge-title">محافظ زمین</div>
                    <div class="badge-desc">۸۵٪ بسته‌بندی سبز</div>
                    <div class="unlock-progress">
                        <div class="progress-bar">
                            <div class="progress-fill" data-progress="100"></div>
                        </div>
                        <div class="progress-text">کلیک کنید تا باز شود!</div>
                    </div>
                </div>
            </div>
            
            <div id="achievement-score" style="text-align: center; margin-top: 3rem; font-size: 1.5rem;">
                <div style="background: rgba(255,255,255,0.1); padding: 1.5rem; border-radius: 15px; backdrop-filter: blur(10px);">
                    <div>🎯 امتیاز شما: <span id="current-score">0</span> / 600</div>
                    <div style="margin-top: 1rem; font-size: 1rem;" id="rank-display">رتبه: تازه کار</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Interactive Progress Journey -->
    <section class="story-section" style="background: linear-gradient(135deg, #16a085 0%, #1abc9c 100%); color: white;">
        <div style="max-width: 1000px; width: 100%;">
            <div class="story-text" style="color: white;">
                <h2>🚀 سفر پیشرفت ما</h2>
                <p>از ابتدای سال تا الان چه مسیری طی کردیم؟ روی هر مرحله کلیک کنید!</p>
            </div>
            
            <div class="progress-journey" style="margin-top: 3rem;">
                <div class="journey-path" style="position: relative; background: rgba(255,255,255,0.1); border-radius: 50px; height: 100px; margin: 2rem 0;">
                    <div id="journey-progress" style="height: 100%; background: linear-gradient(90deg, #f39c12, #e74c3c); border-radius: 50px; width: 0%; transition: width 2s ease; display: flex; align-items: center; justify-content: flex-end; padding-right: 1rem;">
                        <div style="background: white; color: #e74c3c; border-radius: 50%; width: 60px; height: 60px; display: flex; align-items: center; justify-content: center; font-weight: bold; font-size: 1.2rem;">0%</div>
                    </div>
                </div>
                
                <div class="journey-milestones" style="display: grid; grid-template-columns: repeat(auto-fit, minmax(150px, 1fr)); gap: 1rem; margin-top: 2rem;">
                    <div class="milestone" data-progress="20" onclick="progressTo(20)">
                        <div style="font-size: 2rem; margin-bottom: 0.5rem;">🎯</div>
                        <div style="font-weight: bold;">هدف‌گذاری</div>
                        <div style="font-size: 0.9rem;">فروردین ۱۴۰۲</div>
                    </div>
                    
                    <div class="milestone" data-progress="40" onclick="progressTo(40)">
                        <div style="font-size: 2rem; margin-bottom: 0.5rem;">🚀</div>
                        <div style="font-weight: bold;">شروع قدرتمند</div>
                        <div style="font-size: 0.9rem;">اردیبهشت ۱۴۰۲</div>
                    </div>
                    
                    <div class="milestone" data-progress="60" onclick="progressTo(60)">
                        <div style="font-size: 2rem; margin-bottom: 0.5rem;">🤖</div>
                        <div style="font-weight: bold;">انقلاب AI</div>
                        <div style="font-size: 0.9rem;">شهریور ۱۴۰۲</div>
                    </div>
                    
                    <div class="milestone" data-progress="80" onclick="progressTo(80)">
                        <div style="font-size: 2rem; margin-bottom: 0.5rem;">📈</div>
                        <div style="font-weight: bold;">رشد نجومی</div>
                        <div style="font-size: 0.9rem;">آبان ۱۴۰۲</div>
                    </div>
                    
                    <div class="milestone" data-progress="100" onclick="progressTo(100)">
                        <div style="font-size: 2rem; margin-bottom: 0.5rem;">🏆</div>
                        <div style="font-weight: bold;">تحقق رویا</div>
                        <div style="font-size: 0.9rem;">اسفند ۱۴۰۲</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Interactive Challenge Section -->
    <section class="story-section" style="background: linear-gradient(135deg, #e74c3c 0%, #c0392b 100%); color: white;">
        <div style="max-width: 800px; width: 100%;">
            <div class="story-text" style="color: white;">
                <h2>🎮 چالش دانش دیجی‌کالا</h2>
                <p>آماده‌اید تا دانش‌تان را محک بزنید؟ پاسخ صحیح امتیاز می‌برد!</p>
            </div>
            
            <div class="challenge-game" style="background: rgba(255,255,255,0.1); border-radius: 20px; padding: 2rem; backdrop-filter: blur(10px); margin-top: 2rem;">
                <div id="challenge-question" style="font-size: 1.3rem; margin-bottom: 2rem; text-align: center;">
                    دیجی‌کالا چند میلیون کاربر فعال داشت؟
                </div>
                
                <div class="challenge-options" style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 1rem;">
                    <button class="challenge-btn" onclick="checkAnswer(this, false)" style="background: rgba(255,255,255,0.1); border: 2px solid rgba(255,255,255,0.3); color: white; padding: 1rem; border-radius: 10px; font-size: 1rem; cursor: pointer; transition: all 0.3s ease;">
                        ۳۵ میلیون
                    </button>
                    <button class="challenge-btn" onclick="checkAnswer(this, true)" style="background: rgba(255,255,255,0.1); border: 2px solid rgba(255,255,255,0.3); color: white; padding: 1rem; border-radius: 10px; font-size: 1rem; cursor: pointer; transition: all 0.3s ease;">
                        ۴۲ میلیون
                    </button>
                    <button class="challenge-btn" onclick="checkAnswer(this, false)" style="background: rgba(255,255,255,0.1); border: 2px solid rgba(255,255,255,0.3); color: white; padding: 1rem; border-radius: 10px; font-size: 1rem; cursor: pointer; transition: all 0.3s ease;">
                        ۵۰ میلیون
                    </button>
                    <button class="challenge-btn" onclick="checkAnswer(this, false)" style="background: rgba(255,255,255,0.1); border: 2px solid rgba(255,255,255,0.3); color: white; padding: 1rem; border-radius: 10px; font-size: 1rem; cursor: pointer; transition: all 0.3s ease;">
                        ۳۸ میلیون
                    </button>
                </div>
                
                <div id="challenge-result" style="text-align: center; margin-top: 1.5rem; font-size: 1.2rem; display: none;"></div>
                
                <div style="text-align: center; margin-top: 2rem;">
                    <button id="next-challenge" onclick="nextQuestion()" style="background: #f39c12; border: none; color: white; padding: 1rem 2rem; border-radius: 50px; font-size: 1rem; cursor: pointer; display: none;">
                        سوال بعدی 🎯
                    </button>
                </div>
                
                <div id="challenge-score" style="text-align: center; margin-top: 1.5rem; font-size: 1.1rem;">
                    🎯 امتیاز چالش: <span id="challenge-points">0</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Social Sharing Section -->
    <section class="story-section" style="background: linear-gradient(135deg, #3498db 0%, #2980b9 100%); color: white;">
        <div style="max-width: 1000px; width: 100%;">
            <div class="story-text" style="color: white;">
                <h2>📤 اشتراک‌گذاری دستاوردها</h2>
                <p>امتیاز و مدال‌هایتان را با دوستان به اشتراک بگذارید! چالش کنید و ببینید کی بهتر عمل می‌کند...</p>
            </div>
            
            <div class="sharing-dashboard" style="background: rgba(255,255,255,0.1); border-radius: 20px; padding: 2rem; backdrop-filter: blur(10px); margin-top: 2rem;">
                <div style="text-align: center; margin-bottom: 2rem;">
                    <div style="font-size: 2rem; margin-bottom: 1rem;">🏆</div>
                    <div style="font-size: 1.5rem; font-weight: bold; margin-bottom: 0.5rem;">آمار شخصی شما</div>
                    <div id="personal-stats" style="display: grid; grid-template-columns: repeat(auto-fit, minmax(120px, 1fr)); gap: 1rem; margin-top: 1rem;">
                        <div class="stat-bubble">
                            <div style="font-size: 1.5rem; font-weight: bold;" id="share-total-score">0</div>
                            <div style="font-size: 0.9rem;">امتیاز کل</div>
                        </div>
                        <div class="stat-bubble">
                            <div style="font-size: 1.5rem; font-weight: bold;" id="share-badges-count">0</div>
                            <div style="font-size: 0.9rem;">مدال کسب شده</div>
                        </div>
                        <div class="stat-bubble">
                            <div style="font-size: 1.5rem; font-weight: bold;" id="share-level-name">تازه‌کار</div>
                            <div style="font-size: 0.9rem;">رتبه فعلی</div>
                        </div>
                        <div class="stat-bubble">
                            <div style="font-size: 1.5rem; font-weight: bold;" id="completion-percentage">0%</div>
                            <div style="font-size: 0.9rem;">تکمیل گزارش</div>
                        </div>
                    </div>
                </div>

                <div class="sharing-options" style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 1.5rem; margin-top: 2rem;">
                    <button class="share-btn" onclick="shareToSocial('twitter')" style="background: #1da1f2; border: none; color: white; padding: 1rem; border-radius: 15px; cursor: pointer; transition: all 0.3s ease; display: flex; align-items: center; justify-content: center; gap: 0.5rem;">
                        <span style="font-size: 1.2rem;">🐦</span>
                        <span>اشتراک در توییتر</span>
                    </button>
                    
                    <button class="share-btn" onclick="shareToSocial('linkedin')" style="background: #0077b5; border: none; color: white; padding: 1rem; border-radius: 15px; cursor: pointer; transition: all 0.3s ease; display: flex; align-items: center; justify-content: center; gap: 0.5rem;">
                        <span style="font-size: 1.2rem;">💼</span>
                        <span>اشتراک در لینکدین</span>
                    </button>
                    
                    <button class="share-btn" onclick="shareToSocial('telegram')" style="background: #0088cc; border: none; color: white; padding: 1rem; border-radius: 15px; cursor: pointer; transition: all 0.3s ease; display: flex; align-items: center; justify-content: center; gap: 0.5rem;">
                        <span style="font-size: 1.2rem;">✈️</span>
                        <span>اشتراک در تلگرام</span>
                    </button>
                    
                    <button class="share-btn" onclick="copyShareLink()" style="background: #6c757d; border: none; color: white; padding: 1rem; border-radius: 15px; cursor: pointer; transition: all 0.3s ease; display: flex; align-items: center; justify-content: center; gap: 0.5rem;">
                        <span style="font-size: 1.2rem;">🔗</span>
                        <span>کپی لینک</span>
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- Friend Challenge Section -->
    <section class="story-section" style="background: linear-gradient(135deg, #e74c3c 0%, #c0392b 100%); color: white;">
        <div style="max-width: 1000px; width: 100%;">
            <div class="story-text" style="color: white;">
                <h2>⚔️ چالش دوستان</h2>
                <p>دوستانتان را به چالش بکشید! ببینید کی بهتر می‌تواند گزارش دیجی‌کالا را کاوش کند...</p>
            </div>
            
            <div class="challenge-creator" style="background: rgba(255,255,255,0.1); border-radius: 20px; padding: 2rem; backdrop-filter: blur(10px); margin-top: 2rem;">
                <div style="text-align: center; margin-bottom: 2rem;">
                    <div style="font-size: 2rem; margin-bottom: 1rem;">🎯</div>
                    <div style="font-size: 1.5rem; font-weight: bold;">چالش شخصی‌سازی شده بسازید</div>
                </div>
                
                <div class="challenge-form" style="display: grid; gap: 1.5rem;">
                    <div>
                        <label style="display: block; margin-bottom: 0.5rem; font-weight: bold;">نام دوست:</label>
                        <input type="text" id="friend-name" placeholder="نام دوستتان را وارد کنید..." style="width: 100%; padding: 1rem; border: none; border-radius: 10px; font-size: 1rem;">
                    </div>
                    
                    <div>
                        <label style="display: block; margin-bottom: 0.5rem; font-weight: bold;">نوع چالش:</label>
                        <select id="challenge-type" style="width: 100%; padding: 1rem; border: none; border-radius: 10px; font-size: 1rem;">
                            <option value="score">چالش امتیاز بالا</option>
                            <option value="speed">چالش سرعت</option>
                            <option value="knowledge">چالش دانش</option>
                            <option value="completion">چالش تکمیل</option>
                        </select>
                    </div>
                    
                    <div>
                        <label style="display: block; margin-bottom: 0.5rem; font-weight: bold;">پیام شخصی (اختیاری):</label>
                        <textarea id="personal-message" placeholder="پیام تشویقی یا شوخی برای دوستتان..." style="width: 100%; padding: 1rem; border: none; border-radius: 10px; font-size: 1rem; height: 80px; resize: vertical;"></textarea>
                    </div>
                    
                    <button onclick="createChallenge()" style="background: #f39c12; border: none; color: white; padding: 1.2rem; border-radius: 15px; font-size: 1.1rem; font-weight: bold; cursor: pointer; transition: all 0.3s ease;">
                        🚀 ایجاد چالش و ارسال
                    </button>
                </div>
            </div>

            <div class="challenge-templates" style="margin-top: 3rem;">
                <div style="text-align: center; margin-bottom: 2rem;">
                    <div style="font-size: 1.3rem; font-weight: bold;">قالب‌های آماده چالش</div>
                </div>
                
                <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 1.5rem;">
                    <div class="challenge-template" onclick="useTemplate('competitive')" style="background: rgba(255,255,255,0.1); border-radius: 15px; padding: 1.5rem; cursor: pointer; transition: all 0.3s ease; border: 2px solid transparent;">
                        <div style="font-size: 2rem; margin-bottom: 1rem;">🏆</div>
                        <div style="font-weight: bold; margin-bottom: 0.5rem;">چالش رقابتی</div>
                        <div style="font-size: 0.9rem; opacity: 0.9;">"فکر می‌کنی بهتر از من گزارش دیجی‌کالا رو می‌شناسی؟"</div>
                    </div>
                    
                    <div class="challenge-template" onclick="useTemplate('friendly')" style="background: rgba(255,255,255,0.1); border-radius: 15px; padding: 1.5rem; cursor: pointer; transition: all 0.3s ease; border: 2px solid transparent;">
                        <div style="font-size: 2rem; margin-bottom: 1rem;">😊</div>
                        <div style="font-weight: bold; margin-bottom: 0.5rem;">چالش دوستانه</div>
                        <div style="font-size: 0.9rem; opacity: 0.9;">"بیا با هم گزارش دیجی‌کالا رو کاوش کنیم!"</div>
                    </div>
                    
                    <div class="challenge-template" onclick="useTemplate('funny')" style="background: rgba(255,255,255,0.1); border-radius: 15px; padding: 1.5rem; cursor: pointer; transition: all 0.3s ease; border: 2px solid transparent;">
                        <div style="font-size: 2rem; margin-bottom: 1rem;">😂</div>
                        <div style="font-weight: bold; margin-bottom: 0.5rem;">چالش طنز</div>
                        <div style="font-size: 0.9rem; opacity: 0.9;">"شرط می‌بندم نمی‌تونی تو این چالش من رو شکست بدی!"</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Social Proof & Leaderboard -->
    <section class="story-section" style="background: linear-gradient(135deg, #8e44ad 0%, #9b59b6 100%); color: white;">
        <div style="max-width: 1000px; width: 100%;">
            <div class="story-text" style="color: white;">
                <h2>🏅 تابلو افتخارات</h2>
                <p>ببینید دیگران چه امتیازهایی کسب کرده‌اند! شما در چه رتبه‌ای قرار دارید؟</p>
            </div>
            
            <div class="leaderboard" style="background: rgba(255,255,255,0.1); border-radius: 20px; padding: 2rem; backdrop-filter: blur(10px); margin-top: 2rem;">
                <div style="text-align: center; margin-bottom: 2rem;">
                    <div style="font-size: 2rem; margin-bottom: 1rem;">👑</div>
                    <div style="font-size: 1.5rem; font-weight: bold;">برترین کاوشگران</div>
                </div>
                
                <div class="leaderboard-list">
                    <div class="leaderboard-item rank-1" style="display: flex; align-items: center; padding: 1rem; margin: 1rem 0; background: rgba(255,215,0,0.2); border-radius: 15px; border-right: 4px solid #ffd700;">
                        <div style="font-size: 2rem; margin-left: 1rem;">🥇</div>
                        <div style="flex: 1;">
                            <div style="font-weight: bold; font-size: 1.1rem;">علی محمدی</div>
                            <div style="font-size: 0.9rem; opacity: 0.8;">💎 استاد</div>
                        </div>
                        <div style="text-align: left;">
                            <div style="font-weight: bold; font-size: 1.2rem;">587 امتیاز</div>
                            <div style="font-size: 0.8rem; opacity: 0.8;">6/6 مدال</div>
                        </div>
                    </div>
                    
                    <div class="leaderboard-item rank-2" style="display: flex; align-items: center; padding: 1rem; margin: 1rem 0; background: rgba(192,192,192,0.2); border-radius: 15px; border-right: 4px solid #c0c0c0;">
                        <div style="font-size: 2rem; margin-left: 1rem;">🥈</div>
                        <div style="flex: 1;">
                            <div style="font-weight: bold; font-size: 1.1rem;">سارا احمدی</div>
                            <div style="font-size: 0.9rem; opacity: 0.8;">🥇 کارشناس</div>
                        </div>
                        <div style="text-align: left;">
                            <div style="font-weight: bold; font-size: 1.2rem;">425 امتیاز</div>
                            <div style="font-size: 0.8rem; opacity: 0.8;">5/6 مدال</div>
                        </div>
                    </div>
                    
                    <div class="leaderboard-item rank-3" style="display: flex; align-items: center; padding: 1rem; margin: 1rem 0; background: rgba(205,127,50,0.2); border-radius: 15px; border-right: 4px solid #cd7f32;">
                        <div style="font-size: 2rem; margin-left: 1rem;">🥉</div>
                        <div style="flex: 1;">
                            <div style="font-weight: bold; font-size: 1.1rem;">رضا زمانی</div>
                            <div style="font-size: 0.9rem; opacity: 0.8;">🥇 کارشناس</div>
                        </div>
                        <div style="text-align: left;">
                            <div style="font-weight: bold; font-size: 1.2rem;">398 امتیاز</div>
                            <div style="font-size: 0.8rem; opacity: 0.8;">4/6 مدال</div>
                        </div>
                    </div>
                    
                    <div class="your-rank" style="display: flex; align-items: center; padding: 1rem; margin: 2rem 0 1rem 0; background: rgba(243,156,18,0.3); border-radius: 15px; border: 2px solid #f39c12;">
                        <div style="font-size: 2rem; margin-left: 1rem;">📍</div>
                        <div style="flex: 1;">
                            <div style="font-weight: bold; font-size: 1.1rem;">رتبه شما</div>
                            <div style="font-size: 0.9rem; opacity: 0.8;" id="your-rank-level">🥉 تازه‌کار</div>
                        </div>
                        <div style="text-align: left;">
                            <div style="font-weight: bold; font-size: 1.2rem;"><span id="your-rank-score">0</span> امتیاز</div>
                            <div style="font-size: 0.8rem; opacity: 0.8;"><span id="your-rank-badges">0</span>/6 مدال</div>
                        </div>
                    </div>
                </div>
                
                <div style="text-align: center; margin-top: 2rem; padding-top: 2rem; border-top: 1px solid rgba(255,255,255,0.2);">
                    <div style="font-size: 0.9rem; opacity: 0.8; margin-bottom: 1rem;">تعداد کل شرکت‌کنندگان: ۱۲,۸۴۳ نفر</div>
                    <button onclick="refreshLeaderboard()" style="background: rgba(255,255,255,0.1); border: 1px solid rgba(255,255,255,0.3); color: white; padding: 0.8rem 1.5rem; border-radius: 25px; cursor: pointer; transition: all 0.3s ease;">
                        🔄 بروزرسانی رتبه‌بندی
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- Social Achievement Showcase -->
    <section class="story-section" style="background: linear-gradient(135deg, #16a085 0%, #1abc9c 100%); color: white;">
        <div style="max-width: 1000px; width: 100%;">
            <div class="story-text" style="color: white;">
                <h2>🎖️ نمایشگاه مدال‌ها</h2>
                <p>مدال‌های کسب شده را به صورت گرافیکی به اشتراک بگذارید!</p>
            </div>
            
            <div class="badge-showcase" style="background: rgba(255,255,255,0.1); border-radius: 20px; padding: 2rem; backdrop-filter: blur(10px); margin-top: 2rem;">
                <div id="shareable-badge-display" style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); border-radius: 20px; padding: 3rem 2rem; margin-bottom: 2rem; text-align: center; position: relative;">
                    <div style="font-size: 2.5rem; margin-bottom: 1rem;">🏆</div>
                    <div style="font-size: 1.8rem; font-weight: bold; margin-bottom: 0.5rem;" id="showcase-title">پیشرفت من در گزارش دیجی‌کالا</div>
                    <div style="font-size: 1.2rem; margin-bottom: 2rem;" id="showcase-subtitle">سال ۱۴۰۲</div>
                    
                    <div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 1rem; margin-bottom: 2rem;" id="showcase-badges">
                        <!-- Badges will be populated here -->
                    </div>
                    
                    <div style="font-size: 1.1rem; margin-bottom: 1rem;">
                        <span style="background: rgba(255,255,255,0.2); padding: 0.5rem 1rem; border-radius: 25px; margin: 0 0.5rem;">
                            <span id="showcase-score">0</span> امتیاز
                        </span>
                        <span style="background: rgba(255,255,255,0.2); padding: 0.5rem 1rem; border-radius: 25px; margin: 0 0.5rem;">
                            رتبه <span id="showcase-level">تازه‌کار</span>
                        </span>
                    </div>
                    
                    <div style="font-size: 0.9rem; opacity: 0.8;">🔗 digikala.com/annual-report-2023</div>
                </div>
                
                <div style="text-align: center;">
                    <button onclick="downloadBadgeImage()" style="background: #f39c12; border: none; color: white; padding: 1rem 2rem; border-radius: 15px; font-size: 1rem; font-weight: bold; cursor: pointer; margin: 0 0.5rem; transition: all 0.3s ease;">
                        📥 دانلود تصویر
                    </button>
                    <button onclick="shareBadgeImage()" style="background: #27ae60; border: none; color: white; padding: 1rem 2rem; border-radius: 15px; font-size: 1rem; font-weight: bold; cursor: pointer; margin: 0 0.5rem; transition: all 0.3s ease;">
                        📤 اشتراک‌گذاری
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- Reward System Section -->
    <section class="story-section" style="background: linear-gradient(135deg, #9b59b6 0%, #8e44ad 100%); color: white;">
        <div style="max-width: 1000px; width: 100%;">
            <div class="story-text" style="color: white;">
                <h2>🎁 سیستم پاداش</h2>
                <p>با تعامل بیشتر، پاداش‌های بیشتری دریافت کنید! ببینید چه جوایزی در انتظارتان است...</p>
            </div>
            
            <div class="reward-levels" style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 2rem; margin-top: 2rem;">
                <div class="reward-level" data-level="1">
                    <div class="reward-icon">🥉</div>
                    <div class="reward-title">تازه‌کار</div>
                    <div class="reward-range">0 - 100 امتیاز</div>
                    <div class="reward-benefit">مطالعه گزارش</div>
                </div>
                
                <div class="reward-level" data-level="2">
                    <div class="reward-icon">🥈</div>
                    <div class="reward-title">کاوشگر</div>
                    <div class="reward-range">101 - 300 امتیاز</div>
                    <div class="reward-benefit">دسترسی ویژه</div>
                </div>
                
                <div class="reward-level" data-level="3">
                    <div class="reward-icon">🥇</div>
                    <div class="reward-title">کارشناس</div>
                    <div class="reward-range">301 - 500 امتیاز</div>
                    <div class="reward-benefit">محتوای اختصاصی</div>
                </div>
                
                <div class="reward-level" data-level="4">
                    <div class="reward-icon">💎</div>
                    <div class="reward-title">استاد</div>
                    <div class="reward-range">501+ امتیاز</div>
                    <div class="reward-benefit">تمام امکانات</div>
                </div>
            </div>
            
            <div class="current-level-progress" style="margin-top: 3rem; background: rgba(255,255,255,0.1); border-radius: 20px; padding: 2rem; backdrop-filter: blur(10px);">
                <div style="text-align: center; margin-bottom: 1.5rem;">
                    <div style="font-size: 1.5rem; margin-bottom: 0.5rem;">پیشرفت فعلی شما</div>
                    <div id="user-level" style="font-size: 1.2rem;">🥉 تازه‌کار</div>
                </div>
                
                <div class="level-progress-bar" style="background: rgba(255,255,255,0.2); height: 20px; border-radius: 10px; overflow: hidden; margin-bottom: 1rem;">
                    <div id="level-progress-fill" style="height: 100%; background: linear-gradient(90deg, #f39c12, #e74c3c); width: 0%; transition: width 1s ease;"></div>
                </div>
                
                <div style="display: flex; justify-content: space-between; font-size: 0.9rem;">
                    <span id="current-level-points">0</span>
                    <span id="next-level-points">100</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Environmental Impact -->
    <section class="story-section" style="background: linear-gradient(135deg, #27ae60 0%, #2ecc71 100%); color: white;">
        <div style="max-width: 1000px; width: 100%;">
            <div class="story-text" style="color: white;">
                <h2>🌱 تأثیر مثبت بر محیط زیست</h2>
                <p>مسئولیت اجتماعی برای ما مهم است! ببینید چطور به محیط زیست کمک کردیم...</p>
            </div>
            
            <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 2rem;">
                <div class="eco-card" data-delay="0">
                    <div style="font-size: 3rem; margin-bottom: 1rem;">📦</div>
                    <div style="font-size: 2rem; font-weight: bold; margin-bottom: 0.5rem;">۸۵٪</div>
                    <div style="font-size: 1.1rem;">بسته‌بندی قابل بازیافت</div>
                    <div style="margin-top: 1rem; font-size: 0.9rem; opacity: 0.9;">کاهش ضایعات پلاستیکی</div>
                </div>
                
                <div class="eco-card" data-delay="200">
                    <div style="font-size: 3rem; margin-bottom: 1rem;">🚲</div>
                    <div style="font-size: 2rem; font-weight: bold; margin-bottom: 0.5rem;">۳۰٪</div>
                    <div style="font-size: 1.1rem;">تحویل با وسایل سبز</div>
                    <div style="margin-top: 1rem; font-size: 0.9rem; opacity: 0.9;">کاهش آلودگی هوا</div>
                </div>
                
                <div class="eco-card" data-delay="400">
                    <div style="font-size: 3rem; margin-bottom: 1rem;">🌳</div>
                    <div style="font-size: 2rem; font-weight: bold; margin-bottom: 0.5rem;">۵۰۰۰</div>
                    <div style="font-size: 1.1rem;">درخت کاشته شده</div>
                    <div style="margin-top: 1rem; font-size: 0.9rem; opacity: 0.9;">کمپین سبز دیجی‌کالا</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Quiz Section -->
    <section class="story-section quiz-section">
        <div>
            <h2>🤔 شما چه نوع خریداری هستید؟</h2>
            <p>بیایید شخصیت خریدتان را کشف کنیم!</p>
            
            <div class="quiz-card">
                <h3>چند وقت یکبار به دنبال تخفیف می‌گردید؟</h3>
                <button class="quiz-button" onclick="showResult('deal-hunter')">هر ساعت چک می‌کنم! (وسواسی هستم)</button>
                <button class="quiz-button" onclick="showResult('casual-browser')">هفته‌ای چند بار</button>
                <button class="quiz-button" onclick="showResult('impulse-buyer')">چه تخفیفی؟ من همینجوری می‌خرم!</button>
            </div>
            
            <div id="quiz-result" style="margin-top: 2rem; font-size: 1.5rem; display: none;"></div>
        </div>
    </section>

    <script>
        // Intersection Observer for animations
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                    
                    // Animate counters
                    if (entry.target.classList.contains('stat-card')) {
                        const delay = parseInt(entry.target.dataset.delay) || 0;
                        setTimeout(() => animateCounter(entry.target), delay);
                    }
                    
                    // Animate chart bars
                    if (entry.target.classList.contains('interactive-chart')) {
                        animateChart(entry.target);
                    }

                    // Animate all card types with delays
                    if (entry.target.classList.contains('gen-z-card') || 
                        entry.target.classList.contains('discount-item') ||
                        entry.target.classList.contains('seller-card') ||
                        entry.target.classList.contains('delivery-card') ||
                        entry.target.classList.contains('service-card') ||
                        entry.target.classList.contains('eco-card') ||
                        entry.target.classList.contains('success-story') ||
                        entry.target.classList.contains('coverage-item') ||
                        entry.target.classList.contains('contact-channel') ||
                        entry.target.classList.contains('ai-card') ||
                        entry.target.classList.contains('ai-feature') ||
                        entry.target.classList.contains('app-card') ||
                        entry.target.classList.contains('app-feature-item') ||
                        entry.target.classList.contains('tech-card') ||
                        entry.target.classList.contains('tech-innovation') ||
                        entry.target.classList.contains('innovation-card') ||
                        entry.target.classList.contains('coming-soon') ||
                        entry.target.classList.contains('achievement-badge') ||
                        entry.target.classList.contains('milestone') ||
                        entry.target.classList.contains('reward-level')) {
                        animateCard(entry.target);
                    }
                }
            });
        }, observerOptions);

        // Observe all animatable elements
        document.querySelectorAll('.stat-card, .story-text, .interactive-chart, .timeline-item, .gen-z-card, .discount-item, .seller-card, .delivery-card, .service-card, .eco-card, .success-story, .coverage-item, .contact-channel, .ai-card, .ai-feature, .app-card, .app-feature-item, .tech-card, .tech-innovation, .innovation-card, .coming-soon, .achievement-badge, .milestone, .reward-level').forEach(el => {
            observer.observe(el);
        });

        // Counter animation with Persian/English number formatting
        function animateCounter(card) {
            const number = card.querySelector('.stat-number');
            const target = parseInt(number.dataset.target);
            
            let current = 0;
            const increment = target / 100;
            const timer = setInterval(() => {
                current += increment;
                if (current >= target) {
                    current = target;
                    clearInterval(timer);
                }
                // Format numbers with Persian digits
                const formatted = Math.floor(current).toLocaleString('fa-IR');
                number.textContent = number.dataset.target.includes('%') ? 
                    formatted + '٪' : formatted;
            }, 20);
        }

        // Chart animation
        function animateChart(chart) {
            setTimeout(() => {
                chart.querySelectorAll('.chart-fill').forEach((fill, index) => {
                    setTimeout(() => {
                        fill.style.width = fill.dataset.width + '%';
                    }, index * 300);
                });
            }, 500);
        }

        // Generic card animation handler
        function animateCard(card) {
            const delay = parseInt(card.dataset.delay) || 0;
            setTimeout(() => {
                card.classList.add('visible');
            }, delay);
        }

        // Quiz functionality
        function showResult(type) {
            const results = {
                'deal-hunter': '🔍 شکارچی تخفیف حرفه‌ای! هیچ تخفیفی از دستتان نمی‌رود!',
                'casual-browser': '😎 خریدار باکلاس! هوشمندانه و شیک خرید می‌کنید!',
                'impulse-buyer': '⚡ خریدار برقی! با دل خرید می‌کنید!'
            };
            
            const resultDiv = document.getElementById('quiz-result');
            resultDiv.textContent = results[type];
            resultDiv.style.display = 'block';
            resultDiv.style.animation = 'fadeInUp 0.5s ease';
        }

        // Smooth scrolling enhancement with parallax
        window.addEventListener('scroll', () => {
            const scrolled = window.pageYOffset;
            const parallax = document.querySelector('.hero');
            const speed = scrolled * 0.3;
            
            if (parallax) {
                parallax.style.transform = `translateY(${speed}px)`;
            }
        });

        // Enhanced floating animation
        function createFloatingAnimation() {
            document.querySelectorAll('.floating-element').forEach((element, index) => {
                element.style.animationDelay = `${index * 2}s`;
                element.style.animationDuration = `${12 + (index % 3) * 2}s`;
            });
        }

        createFloatingAnimation();

        // Gamification System
        let gameState = {
            totalScore: 0,
            achievementsUnlocked: 0,
            challengeScore: 0,
            currentQuestion: 0,
            userLevel: 1
        };

        const achievements = {
            customers: { icon: '👑', title: 'پادشاه مشتریان', points: 100 },
            speed: { icon: '⚡', title: 'ماستر سرعت', points: 100 },
            ai: { icon: '🤖', title: 'قهرمان هوش مصنوعی', points: 100 },
            satisfaction: { icon: '😊', title: 'افسانه رضایت', points: 100 },
            growth: { icon: '📈', title: 'امپراتور رشد', points: 100 },
            eco: { icon: '🌱', title: 'محافظ زمین', points: 100 }
        };

        const questions = [
            {
                question: 'دیجی‌کالا چند میلیون کاربر فعال داشت؟',
                options: ['۳۵ میلیون', '۴۲ میلیون', '۵۰ میلیون', '۳۸ میلیون'],
                correct: 1
            },
            {
                question: 'میانگین زمان تحویل سفارش‌ها چند ساعت بود؟',
                options: ['۱۲ ساعت', '۳۶ ساعت', '۲۴ ساعت', '۴۸ ساعت'],
                correct: 2
            },
            {
                question: 'دقت پیشنهادات هوشمند AI چند درصد بود؟',
                options: ['۷۵٪', '۸۰٪', '۸۷٪', '۹۰٪'],
                correct: 2
            },
            {
                question: 'چند درصد از بسته‌بندی‌ها قابل بازیافت بودند؟',
                options: ['۷۰٪', '۸۵٪', '۹۰٪', '۸۰٪'],
                correct: 1
            }
        ];

        // Achievement System
        function unlockAchievement(element) {
            if (element.classList.contains('unlocked')) return;
            
            const achievementType = element.dataset.achievement;
            const achievement = achievements[achievementType];
            
            element.classList.remove('locked');
            element.classList.add('unlocked');
            
            const icon = element.querySelector('.badge-icon');
            icon.textContent = achievement.icon;
            
            gameState.totalScore += achievement.points;
            gameState.achievementsUnlocked++;
            
            updateScore();
            updateLevel();
            showUnlockMessage(achievement);
            
            // Animate progress bar
            const progressFill = element.querySelector('.progress-fill');
            setTimeout(() => {
                progressFill.style.width = '100%';
            }, 100);
            
            element.querySelector('.progress-text').textContent = `✅ باز شد! +${achievement.points} امتیاز`;
        }

        function showUnlockMessage(achievement) {
            const message = document.createElement('div');
            message.style.cssText = `
                position: fixed;
                top: 50%;
                left: 50%;
                transform: translate(-50%, -50%);
                background: linear-gradient(135deg, #f39c12, #e67e22);
                color: white;
                padding: 2rem;
                border-radius: 20px;
                text-align: center;
                z-index: 1000;
                animation: unlockMessage 2s ease forwards;
                box-shadow: 0 20px 40px rgba(0,0,0,0.3);
            `;
            
            message.innerHTML = `
                <div style="font-size: 3rem; margin-bottom: 1rem;">${achievement.icon}</div>
                <div style="font-size: 1.5rem; font-weight: bold; margin-bottom: 0.5rem;">مدال باز شد!</div>
                <div style="font-size: 1.2rem;">${achievement.title}</div>
                <div style="font-size: 1rem; margin-top: 1rem;">+${achievement.points} امتیاز</div>
            `;
            
            document.body.appendChild(message);
            
            setTimeout(() => {
                message.remove();
            }, 2000);
        }

        // Progress Journey
        function progressTo(percentage) {
            const progressBar = document.getElementById('journey-progress');
            const progressText = progressBar.querySelector('div');
            
            progressBar.style.width = percentage + '%';
            progressText.textContent = percentage + '%';
            
            // Update milestone active state
            document.querySelectorAll('.milestone').forEach(milestone => {
                milestone.classList.remove('active');
                if (parseInt(milestone.dataset.progress) <= percentage) {
                    milestone.classList.add('active');
                }
            });
            
            // Award points for progress
            const progressPoints = Math.floor(percentage / 20) * 10;
            if (progressPoints > 0) {
                gameState.totalScore += progressPoints;
                updateScore();
                updateLevel();
            }
        }

        // Challenge System
        function checkAnswer(button, isCorrect) {
            const buttons = document.querySelectorAll('.challenge-btn');
            buttons.forEach(btn => btn.style.pointerEvents = 'none');
            
            if (isCorrect) {
                button.classList.add('correct');
                gameState.challengeScore += 50;
                gameState.totalScore += 50;
                document.getElementById('challenge-result').innerHTML = '🎉 آفرین! پاسخ درست! +50 امتیاز';
            } else {
                button.classList.add('incorrect');
                document.getElementById('challenge-result').innerHTML = '❌ اشتباه! دفعه بعد بهتر!';
                
                // Show correct answer
                buttons.forEach(btn => {
                    if (btn.onclick.toString().includes('true')) {
                        btn.classList.add('correct');
                    }
                });
            }
            
            document.getElementById('challenge-result').style.display = 'block';
            document.getElementById('next-challenge').style.display = 'inline-block';
            document.getElementById('challenge-points').textContent = gameState.challengeScore;
            
            updateScore();
            updateLevel();
        }

        function nextQuestion() {
            gameState.currentQuestion++;
            
            if (gameState.currentQuestion >= questions.length) {
                // Quiz completed
                document.getElementById('challenge-question').textContent = '🎊 تبریک! تمام سوالات پاسخ داده شد!';
                document.querySelector('.challenge-options').style.display = 'none';
                document.getElementById('next-challenge').style.display = 'none';
                document.getElementById('challenge-result').innerHTML = `🏆 امتیاز نهایی: ${gameState.challengeScore}`;
                return;
            }
            
            const question = questions[gameState.currentQuestion];
            document.getElementById('challenge-question').textContent = question.question;
            
            const buttons = document.querySelectorAll('.challenge-btn');
            buttons.forEach((btn, index) => {
                btn.textContent = question.options[index];
                btn.className = 'challenge-btn';
                btn.style.pointerEvents = 'auto';
                btn.onclick = () => checkAnswer(btn, index === question.correct);
            });
            
            document.getElementById('challenge-result').style.display = 'none';
            document.getElementById('next-challenge').style.display = 'none';
        }

        // Level and Score System
        function updateScore() {
            document.getElementById('current-score').textContent = gameState.totalScore;
            document.getElementById('challenge-points').textContent = gameState.challengeScore;
        }

        function updateLevel() {
            const levels = [
                { min: 0, max: 100, name: '🥉 تازه‌کار', icon: '🥉' },
                { min: 101, max: 300, name: '🥈 کاوشگر', icon: '🥈' },
                { min: 301, max: 500, name: '🥇 کارشناس', icon: '🥇' },
                { min: 501, max: Infinity, name: '💎 استاد', icon: '💎' }
            ];
            
            const currentLevel = levels.find(level => 
                gameState.totalScore >= level.min && gameState.totalScore <= level.max
            );
            
            if (currentLevel) {
                document.getElementById('rank-display').textContent = `رتبه: ${currentLevel.name}`;
                document.getElementById('user-level').textContent = currentLevel.name;
                
                // Update reward level highlighting
                document.querySelectorAll('.reward-level').forEach(level => {
                    level.classList.remove('current');
                });
                
                const levelIndex = levels.indexOf(currentLevel);
                const rewardLevels = document.querySelectorAll('.reward-level');
                if (rewardLevels[levelIndex]) {
                    rewardLevels[levelIndex].classList.add('current');
                }
                
                // Update progress bar
                const nextLevel = levels[levelIndex + 1];
                const currentLevelPoints = gameState.totalScore - currentLevel.min;
                const levelRange = nextLevel ? nextLevel.min - currentLevel.min : 100;
                const progressPercentage = Math.min((currentLevelPoints / levelRange) * 100, 100);
                
                document.getElementById('level-progress-fill').style.width = progressPercentage + '%';
                document.getElementById('current-level-points').textContent = gameState.totalScore;
                document.getElementById('next-level-points').textContent = nextLevel ? nextLevel.min : '∞';
            }
        }

        // Initialize gamification
        function initializeGamification() {
            updateScore();
            updateLevel();
            
            // Auto-animate progress bars on achievement cards
            setTimeout(() => {
                document.querySelectorAll('.achievement-badge .progress-fill').forEach(fill => {
                    fill.style.width = fill.dataset.progress + '%';
                });
            }, 1000);
        }

        // Add some mouse interaction effects
        document.querySelectorAll('.stat-card, .gen-z-card, .seller-card, .delivery-card, .service-card, .eco-card, .ai-card, .app-card, .tech-card, .innovation-card').forEach(card => {
            card.addEventListener('mouseenter', function() {
                this.style.transform = 'translateY(-10px) scale(1.02)';
            });
            
            card.addEventListener('mouseleave', function() {
                this.style.transform = 'translateY(0) scale(1)';
            });
        });

        // Initialize everything when page loads
        window.addEventListener('load', () => {
            initializeGamification();
        });
    </script>
</body>
</html>
