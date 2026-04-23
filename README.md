<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>顶尖核心团队 | 企业文化与核心力量</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: "Microsoft YaHei", sans-serif;
        }
        body {
            background-color: #ffffff;
            color: #222222;
            line-height: 1.6;
        }
        /* 头部横幅 */
        .hero-section {
            padding: 80px 20px;
            text-align: center;
        }
        .hero-title {
            font-size: 36px;
            font-weight: 700;
            color: #16a34a;
            margin-bottom: 15px;
        }
        .hero-sub {
            font-size: 16px;
            color: #555;
            max-width: 700px;
            margin: 0 auto 30px;
        }
        .btn-group .btn {
            padding: 10px 24px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            margin: 0 6px;
        }
        .btn-green {
            background-color: #16a34a;
            color: #fff;
        }
        .btn-trans {
            background: transparent;
            color: #16a34a;
        }

        /* 通用区块 */
        .section {
            max-width: 1200px;
            margin: 60px auto;
            padding: 0 20px;
        }
        .section-head {
            text-align: center;
            margin-bottom: 40px;
        }
        .section-tag {
            color: #16a34a;
            font-size: 14px;
            font-weight: 600;
            margin-bottom: 8px;
        }
        .section-title {
            font-size: 26px;
            font-weight: bold;
        }
        .section-desc {
            color: #666;
            margin-top: 10px;
        }

        /* 团队成员网格 */
        .team-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 35px;
        }
        .team-card {
            background: #f8f9fa;
            border-radius: 12px;
            padding: 25px 18px;
            text-align: center;
            transition: 0.3s ease;
        }
        .team-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 8px 20px rgba(22, 163, 74, 0.15);
        }
        .avatar {
            width: 140px;
            height: 140px;
            margin: 0 auto 18px;
            border-radius: 12px;
            overflow: hidden;
        }
        .avatar img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        .member-name {
            font-size: 22px;
            font-weight: bold;
            margin-bottom: 6px;
        }
        .member-post {
            color: #16a34a;
            font-weight: 600;
            margin-bottom: 12px;
        }
        .member-intro {
            font-size: 14px;
            color: #555;
        }

        /* 企业文化板块 */
        .culture-wrap {
            background-color: #f0fdf4;
            padding: 60px 20px;
        }
        .culture-content {
            max-width: 1000px;
            margin: 0 auto;
            text-align: center;
        }
        .culture-list {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }
        .culture-item h4 {
            color: #16a34a;
            font-size: 18px;
            margin-bottom: 10px;
        }

        /* 底部 */
        footer {
            background-color: #111;
            color: #aaa;
            text-align: center;
            padding: 40px 20px;
            margin-top: 60px;
        }
    </style>
</head>
<body>

<!-- 头部Banner -->
<section class="hero-section">
    <h1 class="hero-title">Find Your Favourite Strength</h1>
    <p class="hero-sub">顶尖行业领军团队，用专业与远见，定义行业全新高度，打造长期稳定、极具竞争力的核心壁垒</p>
    <div class="btn-group">
        <button class="btn btn-green">了解团队</button>
        <button class="btn btn-trans">企业文化</button>
    </div>
</section>

<!-- 企业文化板块 -->
<section class="culture-wrap">
    <div class="culture-content">
        <div class="section-head">
            <div class="section-tag">CORPORATE CULTURE</div>
            <h2 class="section-title">企业核心文化</h2>
            <p class="section-desc">诚信为本、极致专业、持续突破、合作共赢</p>
        </div>
        <div class="culture-list">
            <div class="culture-item">
                <h4>使命愿景</h4>
                <p>以顶尖实力赋能行业发展，用长期价值成就客户、回馈伙伴、引领未来</p>
            </div>
            <div class="culture-item">
                <h4>核心价值观</h4>
                <p>极致靠谱、敢为人先、精益求精、拥抱变化、共生共荣</p>
            </div>
            <div class="culture-item">
                <h4>团队精神</h4>
                <p>高度协同、绝对担当、无惧挑战、永不止步、全力交付</p>
            </div>
        </div>
    </div>
</section>

<!-- 核心管理团队 -->
<section class="section">
    <div class="section-head">
        <div class="section-tag">CORE TEAM</div>
        <h2 class="section-title">顶尖核心高管团队</h2>
        <p class="section-desc">行业深耕多年的领军人物，全维度把控战略、技术、产品、运营与风控全局</p>
    </div>

    <div class="team-grid">
        <!-- 张总 -->
        <div class="team-card">
            <div class="avatar">
                <!-- 已更换为稳定接口 avatar.ahk -->
                <img src="https://avatar.ahk.cc/avatar/JOE/100?scale=0.8" alt="张总">
            </div>
            <div class="member-name">张总</div>
            <div class="member-post">创始人 & 全局战略掌舵人</div>
            <div class="member-intro">
                行业资深顶层决策者，十余年赛道深度布局经验，精准把控长期发展方向，统筹全盘战略规划与重大商业决策，是团队绝对核心领航者。
            </div>
        </div>

        <!-- 程总 -->
        <div class="team-card">
            <div class="avatar">
                <img src="https://imgchr.com/i/peRLhbn" alt="程总">
            </div>
            <div class="member-name">程总</div>
            <div class="member-post">首席技术总负责人</div>
            <div class="member-intro">
                全栈技术权威专家，攻克无数行业级技术难题，主导底层核心架构搭建与技术革新，为业务高速稳定运转筑牢最强技术护城河。
            </div>
        </div>

        <!-- 赵总 -->
        <div class="team-card">
            <div class="avatar">
                <img src="https://avatar.ahk.cc/avatar/MAX/100?scale=0.8" alt="赵总">
            </div>
            <div class="member-name">赵总</div>
            <div class="member-post">产品与商业战略官</div>
            <div class="member-intro">
                深度洞悉市场风向与用户需求，主导爆款产品从0到1全流程落地，精准打通商业闭环，持续创造超高商业增量与行业影响力。
            </div>
        </div>

        <!-- 马总 -->
        <div class="team-card">
            <div class="avatar">
                <img src="https://avatar.ahk.cc/avatar/KING/100?scale=0.8" alt="马总">
            </div>
            <div class="member-name">马总</div>
            <div class="member-post">项目与交付总指挥</div>
            <div class="member-intro">
                大型复杂项目全链路管理大师，极强落地攻坚能力，百万级体量项目全程稳交付、零重大失误，保障所有目标高效完美达成。
            </div>
        </div>

        <!-- 秦总 -->
        <div class="team-card">
            <div class="avatar">
                <img src="https://avatar.ahk.cc/avatar/PAUL/100?scale=0.8" alt="秦总">
            </div>
            <div class="member-name">秦总</div>
            <div class="member-post">市场与增长操盘手</div>
            <div class="member-intro">
                全域增长顶尖专家，精通品牌打造与渠道全域布局，快速打开市场、强势破圈，持续放大品牌声量，实现业绩跨越式增长。
            </div>
        </div>

        <!-- 胡总 -->
        <div class="team-card">
            <div class="avatar">
                <img src="https://avatar.ahk.cc/avatar/SEAN/100?scale=0.8" alt="胡总">
            </div>
            <div class="member-name">胡总</div>
            <div class="member-post">风控合规与安全总监</div>
            <div class="member-intro">
                风控与合规领域顶尖权威，搭建全链路风险防控体系，全方位守住安全红线，护航企业长期稳健、行稳致远、基业长青。
            </div>
        </div>
    </div>
</section>

<!-- 底部 -->
<footer>
    <p>顶尖核心管理团队 | 企业文化引领未来</p>
</footer>

</body>
</html>
