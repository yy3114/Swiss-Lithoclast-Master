<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Swiss Lithoclast Master 簡報</title>
    <!-- 引入 Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- 引入 Tone.js CDN -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/tone/14.8.49/Tone.min.js"></script>
    <style>
        /* 自定義字體為 Inter */
        body {
            font-family: 'Inter', sans-serif;
        }
        /* 隱藏內容的默認樣式 */
        .content-hidden {
            max-height: 0;
            overflow: hidden;
            padding-top: 0;
            padding-bottom: 0;
            transition: max-height 0.5s ease-out, padding 0.5s ease-out;
        }
        /* 顯示內容的樣式 */
        .content-visible {
            max-height: 1000px; /* 足夠大的值以容納內容 */
            padding-top: 1rem;
            padding-bottom: 1rem;
            transition: max-height 0.5s ease-in, padding 0.5s ease-in;
        }
        /* 自定義旋轉類別 */
        .svg-rotate-45 {
            transform: rotate(45deg);
        }
    </style>
</head>
<body class="bg-gradient-to-br from-blue-50 to-indigo-100 min-h-screen p-4 sm:p-6 md:p-8 text-gray-800">

    <div class="max-w-4xl mx-auto bg-white shadow-2xl rounded-xl p-6 sm:p-8 md:p-10 border border-gray-200">
        <!-- 主標題與小字 -->
        <h1 class="text-3xl sm:text-4xl font-extrabold text-center text-indigo-700 mb-4 pb-2 border-b-2 border-indigo-200">
            Swiss Lithoclast Master 碎石系統
            <br>
            <small class="block text-lg sm:text-xl font-semibold text-gray-500 mt-2">醫院新進儀器，增進手術效率</small>
        </h1>

        <!-- 示意圖 -->
        <div class="mb-8 text-center">
            <img src="https://i.postimg.cc/mrwFV7KF/Swiss-Litho-Clast-2-PN3-Hand-Piece-Front-Copy.jpg"
                 alt="Swiss Lithoclast Master PN3"
                 class="w-full h-auto rounded-lg shadow-lg max-w-xl mx-auto object-cover"
                 onerror="this.onerror=null;this.src='https://placehold.co/800x400/D1D5DB/4B5563?text=圖片載入失敗';">
            <p class="text-sm text-gray-500 mt-2">（圖片：Swiss Lithoclast Master PN3）</p>
        </div>


        <!-- 區塊 1: 產品概述與綜合醫療設備供應商 -->
        <div id="section1-container" class="mb-6 bg-gradient-to-r from-blue-100 to-purple-100 p-4 rounded-lg shadow-lg transition-all duration-300">
            <button class="flex justify-between items-center w-full py-3 text-left font-semibold text-lg sm:text-xl text-blue-800 focus:outline-none" onclick="toggleContent('section1')">
                <span>一、產品概述與綜合醫療設備供應商</span>
                <!-- SVG 圖示：更大、更粗、有陰影且可旋轉 -->
                <svg id="section1-icon" class="w-8 h-8 text-blue-800 transition-transform duration-300 shadow-md" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="4" d="M12 4v16m-8-8h16"></path>
                </svg>
            </button>
            <div id="section1-content" class="content-hidden px-2 text-gray-700 leading-relaxed">
                <p class="mb-2">Swiss Lithoclast Master 是一款由 EMS SA (Electro Medical Systems SA) 開發，並由 Healthware India 等公司銷售的先進碎石設備。它整合了氣動（Pneumatic）和超音波（Ultrasound）能量，專為體內碎石術設計，主要用於治療泌尿系統結石，包括腎結石、輸尿管結石和膀胱結石。</p>
                <p>Healthware India 的產品列表顯示，除了泌尿科的碎石和前列腺治療外，Healthware India 還提供介入性超音波、ESWT（體外震波治療）、泌尿科耗材、內腔減重手術（Endobariatrics）以及神經外科的手術雷射和術中超音波換能器等產品和服務。這表明 Healthware India 是一家綜合性的醫療設備和服務供應商。</p>
            </div>
        </div>

        <!-- 區塊 2: 核心雙重碎石技術：氣動與超音波 -->
        <div id="section2-container" class="mb-6 bg-gradient-to-r from-green-100 to-blue-100 p-4 rounded-lg shadow-lg transition-all duration-300">
            <button class="flex justify-between items-center w-full py-3 text-left font-semibold text-lg sm:text-xl text-green-800 focus:outline-none" onclick="toggleContent('section2')">
                <span>二、核心雙重碎石技術：氣動與超音波</span>
                <!-- SVG 圖示：更大、更粗、有陰影且可旋轉 -->
                <svg id="section2-icon" class="w-8 h-8 text-green-800 transition-transform duration-300 shadow-md" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="4" d="M12 4v16m-8-8h16"></path>
                </svg>
            </button>
            <div id="section2-content" class="content-hidden px-2 text-gray-700 leading-relaxed">
                <h3 class="font-bold text-md sm:text-lg mb-2 text-green-700">氣動碎石（Pneumatic Lithotripsy）</h3>
                <ul class="list-disc list-inside ml-4 mb-4">
                    <li><b>原理：</b> 根據牛頓作用與反作用定律，透過壓縮空氣產生彈道能量，彈丸擊中探頭將衝擊波傳遞到結石。</li>
                    <li><b>作用：：</b> 主要用於「粗碎」或「快速粗碎」，能有效分解堅硬和大型結石。</li>
                    <li><b>特點與優勢：</b> 可調節頻率（1-12 Hz）和功率，減少探頭位移，減少「推回效應」，提高碎石控制，重量輕、符合人體工學，易於消毒和探頭更換，探頭和手柄耐用性極高，被譽為體內碎石術的「黃金標準」。</li>
                </ul>
                <h3 class="font-bold text-md sm:text-lg mb-2 text-green-700">超音波碎石（Ultrasonic Lithotripsy）</h3>
                <ul class="list-disc list-inside ml-4 mb-4">
                    <li><b>原理：</b> 透過探頭尖端的快速振動來研磨結石成碎片。</li>
                    <li><b>作用：：</b> 主要用於「細碎」和「粉碎」。</li>
                    <li><b>特點與創新：</b> 具有可調節功率和佔空比。超音波能量與抽吸功能同時作用，可完全清除結石碎片。新型 Vario 超音波手柄設計優化了換能器，提高了效率和穩定性。</li>
                </ul>
                <h3 class="font-bold text-md sm:text-lg mb-2 text-green-700">同時使用（Simultaneous Use）</h3>
                <ul class="list-disc list-inside ml-4">
                    <li><b>效果：</b> 允許氣動和超音波能量同時使用，以達到「乘法作用」或「增強效果」，顯著縮短治療時間並提高結石清除率。</li>
                </ul>
            </div>
        </div>

        <!-- 區塊 3: 配套系統與配件 -->
        <div id="section3-container" class="mb-6 bg-gradient-to-r from-purple-100 to-pink-100 p-4 rounded-lg shadow-lg transition-all duration-300">
            <button class="flex justify-between items-center w-full py-3 text-left font-semibold text-lg sm:text-xl text-purple-800 focus:outline-none" onclick="toggleContent('section3')">
                <span>三、碎石配套系統與多樣化配件</span>
                <!-- SVG 圖示：更大、更粗、有陰影且可旋轉 -->
                <svg id="section3-icon" class="w-8 h-8 text-purple-800 transition-transform duration-300 shadow-md" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="4" d="M12 4v16m-8-8h16"></path>
                </svg>
            </button>
            <div id="section3-content" class="content-hidden px-2 text-gray-700 leading-relaxed">
                <h3 class="font-bold text-md sm:text-lg mb-2 text-purple-700">Swiss LithoVac® 抽吸技術</h3>
                <ul class="list-disc list-inside ml-4 mb-4">
                    <li><b>功能：</b> 提供受控抽吸，用於完全清除結石碎片，將傳統輸尿管鏡轉變為高性能單元。</li>
                    <li><b>優勢：</b> 實現「連續流動儀器」、「增強視野」和「控制結石位移」，系統緊湊輕便，易於清潔維護。</li>
                </ul>
                <h3 class="font-bold text-md sm:text-lg mb-2 text-purple-700">Swiss LithoPump®</h3>
                <ul class="list-disc list-inside ml-4 mb-4">
                    <li><b>功能：</b> 完全氣動驅動的抽吸泵，基於文丘里原理，精確調節碎石術所需的抽吸壓力。</li>
                    <li><b>優勢：：</b> 操作安全、無噪音、無需電力，易於設置，可高度調節負壓，確保視野清晰，無壓力峰值，採用雙重細菌過濾系統。</li>
                </ul>
                <h3 class="font-bold text-md sm:text-lg mb-2 text-purple-700">探頭種類與其他配件</h3>
                <ul class="list-disc list-inside ml-4">
                    <li>提供多種尺寸和長度的超音波探頭和氣動探頭，以及用於軟性輸尿管鏡和腎鏡的軟性探頭。</li>
                    <li>其他配件包括腳踏開關、碎石捕獲器、EMS 內窺鏡及配件、手柄適配器、Swiss LithoCart（運輸和存儲）和壓縮機。</li>
                </ul>
            </div>
        </div>

        <!-- 區塊 4: 臨床應用與效益 -->
        <div id="section4-container" class="mb-6 bg-gradient-to-r from-yellow-100 to-orange-100 p-4 rounded-lg shadow-lg transition-all duration-300">
            <button class="flex justify-between items-center w-full py-3 text-left font-semibold text-lg sm:text-xl text-orange-800 focus:outline-none" onclick="toggleContent('section4')">
                <span>四、卓越臨床應用與顯著效益</span>
                <!-- SVG 圖示：更大、更粗、有陰影且可旋轉 -->
                <svg id="section4-icon" class="w-8 h-8 text-orange-800 transition-transform duration-300 shadow-md" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="4" d="M12 4v16m-8-8h16"></path>
                </svg>
            </button>
            <div id="section4-content" class="content-hidden px-2 text-gray-700 leading-relaxed">
                <h3 class="font-bold text-md sm:text-lg mb-2 text-orange-700">腎臟鹿角形結石治療（PNL）</h3>
                <ul class="list-disc list-inside ml-4 mb-4">
                    <li>一項研究比較顯示，Swiss Lithoclast Master 在碎石/清除速度方面更有效快速（平均58分鐘 vs 標準氣動機的65分鐘），統計學意義顯著（p < 0.01）。</li>
                    <li>殘餘碎片率顯著降低（Lithoclast Master 組為4% vs 氣動碎石機組為16%），併發症發生率無顯著差異。</li>
                </ul>
                <h3 class="font-bold text-md sm:text-lg mb-2 text-orange-700">輸尿管結石治療</h3>
                <ul class="list-disc list-inside ml-4 mb-4">
                    <li>被證明是治療輸尿管結石的安全有效方法，總體成功率為93.5%。</li>
                    <li>成功率受結石位置（上輸尿管結石易向上移位）、大小和腎積水程度影響。</li>
                    <li>併發症發生率低（輸尿管穿孔率從4.9%到2.6%不等），無輸尿管狹窄報告。</li>
                </ul>
                <h3 class="font-bold text-md sm:text-lg mb-2 text-orange-700">整體效益</h3>
                <ul class="list-disc list-inside ml-4">
                    <li><b>快速有效：</b> 臨床證明碎石速度比 Swiss LithoClast® Standard 快四倍，比標準超音波碎石機快兩倍以上。</li>
                    <li><b>減少堵塞：</b> 有助於防止超音波手柄和探頭中的結石碎片堵塞。</li>
                    <li><b>適用性廣：</b> 適用於腎臟、輸尿管和膀胱結石，無論結石大小或成分。</li>
                </ul>
            </div>
        </div>

        <!-- 區塊 5: 與其他碎石技術的比較及總結 -->
        <div id="section5-container" class="mb-6 bg-gradient-to-r from-teal-100 to-cyan-100 p-4 rounded-lg shadow-lg transition-all duration-300">
            <button class="flex justify-between items-center w-full py-3 text-left font-semibold text-lg sm:text-xl text-teal-800 focus:outline-none" onclick="toggleContent('section5')">
                <span>五、與其他碎石技術比較與總結</span>
                <!-- SVG 圖示：更大、更粗、有陰影且可旋轉 -->
                <svg id="section5-icon" class="w-8 h-8 text-teal-800 transition-transform duration-300 shadow-md" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="4" d="M12 4v16m-8-8h16"></path>
                </svg>
            </button>
            <div id="section5-content" class="content-hidden px-2 text-gray-700 leading-relaxed">
                <h3 class="font-bold text-md sm:text-lg mb-2 text-teal-700">與其他碎石技術的比較</h3>
                <ul class="list-disc list-inside ml-4 mb-4">
                    <li><b>電水力碎石（EHL）：</b> 碎石率高但組織創傷和併發症率更高。</li>
                    <li><b>單純超音波碎石（USL）：</b> 需要大直徑儀器和直通操作通道，可能需要術前輸尿管擴張。</li>
                    <li><b>雷射碎石（如 Holmium:YAG laser）：</b> 能分解所有結石成分，但碎片較小，效率較低。Swiss Lithoclast 在安全性與成本效益方面具明顯優勢。</li>
                </ul>
                <h3 class="font-bold text-md sm:text-lg mb-2 text-teal-700">總結</h3>
                <p class="mb-2">Swiss Lithoclast Master 作為一種結合了氣動和超音波能量的體內碎石系統，在治療泌尿系統結石方面展現出顯著的優勢。它能夠實現快速、有效的結石粉碎和清除，同時最大限度地減少殘餘碎片和併發症。</p>
                <p>其可調節的碎石參數、高效的抽吸系統以及多種探頭選擇，使其成為處理各類結石的全面且可靠的解決方案。儘管在處理大型上輸尿管結石時存在向上移位的潛在風險，但透過配合輔助裝置，其臨床效益仍然顯著。</p>
                <p class="font-semibold italic mt-4 text-center text-teal-600">
                    "Lithoclast® Master is an effective intracorporeal lithotripter during percutaneous nephrolithotomy in the treatment of renal staghorn calculi for stone fragmentation/clearance with minimal residual fragments and complications."
                </p>
                <p class="font-semibold italic text-center text-teal-600">
                    "In conclusion, pneumatic lithotripsy with Swiss Lithoclast is an effective and safe treatment modality for ureter stones."
                </p>
                <p class="mt-2 text-center text-teal-700">
                    Swiss Lithoclast Master 的綜合性能使其成為目前體內碎石領域的一項領先技術。
                </p>
            </div>
        </div>

    </div>

    <script>
        // 初始化 Tone.js Synth 和 AudioContext 狀態
        let spinSynth;
        let audioContextStarted = false;

        function startAudioContext() {
            // 只有在 AudioContext 尚未啟動時才啟動它並初始化 Synth
            if (!audioContextStarted) {
                // 啟動 Tone.js 的 AudioContext
                Tone.start().then(() => {
                    // 使用 PolySynth 來播放多個音符（如琶音）以模擬旋轉聲
                    spinSynth = new Tone.PolySynth(Tone.Synth, {
                        oscillator: { type: "triangle" }, // 三角波產生更柔和的聲音
                        envelope: {
                            attack: 0.005,
                            decay: 0.1, // 稍微延長衰減時間
                            sustain: 0.0,
                            release: 0.1
                        }
                    }).toDestination();
                    audioContextStarted = true;
                    console.log("AudioContext started and PolySynth initialized for spinning sound.");
                }).catch(e => {
                    console.error("Error starting AudioContext:", e);
                });
            }
        }

        function toggleContent(sectionIdToToggle) {
            // 每次點擊都嘗試啟動 AudioContext (如果尚未啟動)
            startAudioContext();

            const allSections = ['section1', 'section2', 'section3', 'section4', 'section5'];

            allSections.forEach(currentSectionId => {
                const content = document.getElementById(`${currentSectionId}-content`);
                const icon = document.getElementById(`${currentSectionId}-icon`);

                if (currentSectionId === sectionIdToToggle) {
                    // 點擊的項目，切換其狀態
                    const isVisible = content.classList.contains('content-visible');
                    if (isVisible) {
                        // 如果可見，則收合
                        content.classList.remove('content-visible');
                        content.classList.add('content-hidden');
                        icon.classList.remove('svg-rotate-45'); // 移除旋轉
                    } else {
                        // 如果隱藏，則展開並播放音效
                        content.classList.remove('content-hidden');
                        content.classList.add('content-visible');
                        icon.classList.add('svg-rotate-45'); // 添加旋轉
                        if (spinSynth && audioContextStarted) {
                            // 播放一個短促的上升琶音來模擬旋轉聲
                            spinSynth.triggerAttackRelease(["C5", "E5"], "16n"); // 播放 C5 和 E5 兩個音符，持續 16 分音符
                        }
                    }
                } else {
                    // 其他項目，如果打開則收合
                    if (content.classList.contains('content-visible')) {
                        content.classList.remove('content-visible');
                        content.classList.add('content-hidden');
                        icon.classList.remove('svg-rotate-45'); // 移除旋轉
                    }
                }
            });
        }

        // 確保在頁面加載後，所有內容都是隱藏的，並且圖示處於初始狀態（未旋轉的十字）
        document.addEventListener('DOMContentLoaded', () => {
            const sections = ['section1', 'section2', 'section3', 'section4', 'section5'];
            sections.forEach(sectionId => {
                const content = document.getElementById(`${sectionId}-content`);
                const icon = document.getElementById(`${sectionId}-icon`);
                if (content && icon) {
                    content.classList.add('content-hidden');
                    icon.classList.remove('svg-rotate-45'); // 確保初始狀態是未旋轉的十字
                }
            });
        });
    </script>
</body>
</html>

