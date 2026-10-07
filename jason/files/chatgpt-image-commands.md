# ChatGPT 生圖指令大全


## 這份檔案怎麼看

| 區塊 | 內容 | 建議怎麼用 |
|---|---|---|
| 第一部分 | 斜線指令的運作原理 | 先看，3 分鐘 |
| 第二部分 | 萬用 Prompt 公式 | 背下來，每次做圖套用 |
| 第三部分 | 各家 AI 生圖工具：連結與用法 | 依你手上的工具挑一個 |
| 第四部分 | 一次設定「指令翻譯器」 | 設定一次，以後打斜線就能用 |
| 第五部分 | 432 個指令完整清單 | 當字典查，用到再翻 |
| 第六部分 | 常用組合技 | 直接抄配方 |
| 第七部分 | 出圖失敗怎麼救 | 卡住再看 |


## 第一部分｜斜線指令的運作原理

先講清楚一件事：ChatGPT 本身沒有內建這些斜線指令。

你在對話框單打 /softglow，AI 只能從字面去猜你要什麼，結果時好時壞。

這份清單的每一個指令，都附了一句「展開句」。展開句才是 AI 真正看得懂的完整英文描述。用法有兩種：

用法 A：直接貼展開句（最快，任何 AI 都能用）
查表 → 複製展開句 → 貼進你的 prompt。

用法 B：設定指令翻譯器（最省事，長期使用推薦）
把這份檔案丟給 AI 當參考資料，之後你只要打 一杯拿鐵 /softglow /purewhite，AI 會自動把斜線換成完整描述再生圖。設定方法在第四部分。

為什麼展開句用英文？各家生圖模型的訓練資料以英文描述為主，風格、光線、鏡頭這類專業詞彙用英文寫，出圖穩定度明顯比較高。你的主體描述可以用中文，風格描述用英文，混著寫完全沒問題。


## 第二部分｜萬用 Prompt 公式

每次做圖，照這個順序填空：

```
【主體】＋【場景】＋【風格指令】＋【光線指令】＋【鏡頭／構圖指令】＋【色調指令】＋【比例】＋【圖中文字】
```
範例（中文主體＋英文展開句）：

```
一杯冰拿鐵放在木頭桌上，旁邊有一本打開的筆記本。
Style: clean commercial product photo.
Lighting: soft diffused lighting, gentle shadows (/softglow), warm golden rim light outlining the subject edges (/goldenrim).
Camera: shallow depth of field, creamy blurred background (/shallowdof).
Color: warm color grading, amber tones (/warmtone).
Aspect ratio: 4:5 vertical.
No text in the image.
```
四個寫 prompt 的原則：

1. 一張圖最多疊 3～4 個指令。 疊太多，AI 會互相打架，出來四不像。
2. 同一類別只挑一個。 /softglow 和 /hardshadow 同時出現，AI 只能二選一亂猜。
3. 比例一定要寫。 IG 輪播寫 4:5 vertical，限動和 Reels 寫 9:16 vertical，YouTube 縮圖寫 16:9 horizontal。
4. 圖裡要有字，就用引號把字框起來。 例：Headline text: "三分鐘學會打光"。不要字就寫 No text in the image.

## 第三部分｜各家 AI 生圖工具：連結與用法

> 各平台的免費額度、方案價格與模型版本更新很快，實際以官網為準。

### 1. ChatGPT（OpenAI）

- 連結： https://chatgpt.com
- 強項： 聽得懂長段中文描述、圖中文字準確度高、可以上傳參考圖直接改。
- 用法：
  1. 開新對話，直接輸入「幫我生成一張圖：」＋你的 prompt。
  2. 要改圖就上傳原圖，寫清楚「保留什麼、只改什麼」。
  3. 不滿意就在同一個對話回覆「背景換成白色，其他不變」，一次只改一個地方。
- 斜線指令支援： 可設定指令翻譯器（用「專案」或「自訂 GPT」，見第四部分）。

### 2. Gemini（Google）

- 連結： https://gemini.google.com
- 強項： 修圖、換背景、換裝、保持同一個人物在不同場景，速度快。
- 用法：
  1. 上傳一張照片，輸入修改指令，例：「保留人物臉部完全不變，背景換成夜市」。
  2. 連續修改時一次只下一個動作，人物比較不會走樣。
- 斜線指令支援： 可設定指令翻譯器（用「Gem」，見第四部分）。

### 3. Midjourney

- 連結： https://www.midjourney.com
- 強項： 美感、質感、藝術風格最強，適合做封面主視覺、氛圍圖。
- 用法：
  1. 用網頁版登入，在上方輸入框輸入英文 prompt。
  2. 句尾加參數：-ar 4:5（比例）、-no text（排除元素）。
  3. 想沿用某張圖的風格，可上傳參考圖當風格參考。
- 斜線指令支援： 不支援翻譯器，請直接貼「展開句」。
- 注意： 中文字幾乎寫不好，要放中文標題的圖建議後製加字。

### 4. Ideogram

- 連結： https://ideogram.ai
- 強項： 圖中文字排版、海報、Logo、標題字。
- 用法： 輸入 prompt 時，要出現的文字用引號框起來，例：a poster with the headline "SUMMER SALE"。
- 斜線指令支援： 直接貼展開句。

### 5. Canva（Magic Media／AI 生圖功能）

- 連結： https://www.canva.com
- 強項： 生完圖直接在同一個畫面排版、加字、套模板，適合不想切換工具的人。
- 用法： 在 Canva 的 AI 生圖功能輸入描述，選擇風格與比例，生完直接拖進設計。
- 斜線指令支援： 直接貼展開句。

### 6. Adobe Firefly

- 連結： https://firefly.adobe.com
- 強項： 與 Photoshop 整合，生成填色、延伸畫面很好用，官方主打商用安全。
- 用法： 在網頁版輸入 prompt，或在 Photoshop 框選範圍後用「生成填色」補圖。
- 斜線指令支援： 直接貼展開句。

### 7. Grok（xAI）

- 連結： https://grok.com
- 強項： 寫實人像、速度快。
- 用法： 對話中輸入「生成一張圖：」＋描述。
- 斜線指令支援： 直接貼展開句。

### 8. Claude（Anthropic）

- 連結： https://claude.ai
- 定位： Claude 不直接生圖，但非常適合當「Prompt 寫手」：把你的想法和這份檔案丟給它，請它幫你組出完整英文 prompt，再貼到上面任何一個生圖工具。
- 斜線指令支援： 可用「專案」設定指令翻譯器。

### 該選哪一個？

| 你要做的事 | 推薦工具 |
|---|---|
| IG 輪播、圖中要有中文字 | ChatGPT |
| 修自己的照片、換背景、換裝 | Gemini |
| 高質感封面、氛圍主視覺 | Midjourney |
| 海報標題、Logo 字體 | Ideogram |
| 生完馬上排版 | Canva |
| 商用素材、延伸畫面 | Adobe Firefly |
| 不會寫英文 prompt | Claude 先幫你寫，再拿去生 |


## 第四部分｜一次設定「指令翻譯器」

設定一次，以後打斜線就能用。


### 步驟 1：下載這份 Markdown 檔

就是你現在看的這份。


### 步驟 2：依你的工具建立專屬空間

| 工具 | 去哪裡設定 | 怎麼放檔案 |
|---|---|---|
| ChatGPT | 左側「專案」→ 新增專案，或「探索 GPT」→ 建立自訂 GPT | 上傳這份 .md 當專案檔案／知識檔 |
| Gemini | 「Gem」→ 新增 Gem | 上傳這份 .md 到 Gem 的知識檔 |
| Claude | 「專案」→ 新增專案 | 上傳這份 .md 到專案知識庫 |


### 步驟 3：把下面這段貼進「指示／Instructions」欄位

```
你是「生圖指令翻譯器」。

規則：
1. 我會用中文描述畫面，並在後面加上斜線指令，例如：一杯拿鐵 /softglow /purewhite
2. 請到知識檔《ChatGPT 生圖指令大全》查每個斜線指令的「展開句」。
3. 把我的中文描述翻成英文，再把所有展開句合併，組成一段完整的英文生圖 prompt。
4. 若我沒有指定比例，預設使用 4:5 vertical。
5. 若同一類別出現兩個互相衝突的指令，請先問我要留哪一個。
6. 若查不到某個指令，照字面意思合理推測，並在最後告訴我你怎麼解讀。
7. 在 ChatGPT 或 Gemini 中，組好 prompt 後直接生成圖片；在 Claude 中，輸出完整英文 prompt 讓我複製。
```

### 步驟 4：開始使用

```
一位穿白襯衫的男生坐在咖啡廳用筆電工作 /candid /goldenhour /shallowdof
```
```
這張商品照背景換掉 /changebg /purewhite /productclean
（附上原圖）
```

## 第五部分｜432 個指令完整清單

> 欄位說明：指令＝你要打的斜線；效果＝中文說明；展開句＝直接貼進 prompt 的英文描述。展開句中的 [ ] 請換成你自己的內容。

### 分類 01｜光線・鏡頭・人物

| 指令 | 效果 | 展開句 |
|---|---|---|
| /softglow | 柔光擴散，陰影柔和 | soft diffused lighting, gentle shadows, even tones |
| /hardshadow | 單一硬光 | single hard light source, crisp defined shadows |
| /beamlight | 光束穿過霧氣 | volumetric light beams cutting through haze |
| /darkpoint | 全暗只留一道光 | low-key dark scene lit by a single point of light |
| /brightflat | 明亮無陰影 | bright high-key flat lighting, almost no shadows |
| /shadowcut | 硬朗的幾何陰影 | bold graphic hard-edged shadows across the subject |
| /patternlight | 鏤空圖案光影 | light through a stencil casting patterned shadows, gobo lighting |
| /colorwash | 單色濾光片打光 | single colored gel light washing the whole scene |
| /goldenrim | 暖色輪廓邊光 | warm golden rim light outlining the subject edges |
| /nightglow | 冷調夜間光暈 | cool glowing city night lights, ambient glow |
| /candlelit | 只有燭光 | lit only by warm candlelight, flickering soft shadows |
| /neonwash | 粉藍霓虹光 | pink and blue neon light wash, cyberpunk mood |
| /moonlit | 冷藍月光 | cool blue moonlight, quiet night atmosphere |
| /sunflare | 角落陽光眩光 | sun flare entering from the top corner, natural lens flare |
| /silhouetteonly | 天空前的剪影 | subject as a dark silhouette against a bright sky |
| /reflectedlight | 彩色反射補光 | colored bounce light reflected onto the subject |
| /underlit | 從下方打光 | light coming from below, dramatic upward shadows |
| /sidelit | 側光，半邊入陰影 | strong side light, half of the face in shadow |
| /backlit2 | 背後透出光暈 | backlit subject with a glowing halo outline |
| /spotlit | 窄束聚光燈 | narrow spotlight beam on the subject, dark surroundings |
| /twilighttone | 紫橘色暮光天空 | twilight sky with purple and orange gradient tones |
| /overcastsoft | 陰天柔和光 | soft overcast daylight, no harsh shadows |
| /storminglight | 暴風雨中透出的光 | dramatic storm light breaking through dark clouds |
| /firelight | 閃爍的溫暖火光 | warm flickering firelight glow on faces |


### 分類 02｜拆解看內部

| 指令 | 效果 | 展開句 |
|---|---|---|
| /revealparts | 零件分離懸浮 | exploded view, components floating apart in order |
| /bluecopy | 藍圖工程圖 | technical blueprint drawing, white lines on blue paper |
| /layerpeel | 層層堆疊分離 | stacked layers separated vertically to show inner structure |
| /oldpatent | 復古專利圖頁 | vintage patent drawing page, aged paper, figure labels |
| /gridflat | 零件俯拍平鋪 | knolling layout, all parts laid flat from above in a neat grid |
| /sidecut | 中央俐落剖面 | clean cross-section cut straight through the middle |
| /grainzoom | 表面紋理極致特寫 | extreme macro close-up of surface texture |
| /topdown | 俯視平面圖 | top-down floor plan view |
| /partsfloat | 零件鬆散漂浮 | loose parts floating freely in space |
| /wireframe2 | 透視線框網格 | see-through wireframe mesh render |
| /ghostshell | 透明外殼，看見內部機構 | semi-transparent outer shell revealing the inner mechanism |
| /layerstack | 水平分層留間隙 | horizontal layers stacked with visible gaps between them |
| /techdraw | 標註線與文字說明 | technical illustration with callout lines and labels |
| /skeletonview | 只留內部骨架 | only the inner frame and skeleton visible |
| /diagramline | 零件連線到註解 | parts connected by thin lines to annotation notes |
| /insidebox | 拆掉前牆看內部 | front wall removed to show the interior, dollhouse view |
| /peeledback | 表面掀開一角 | one corner of the surface peeled back to reveal what is inside |
| /openhinge | 像書一樣打開 | opened like a book, both halves visible |
| /transparentshell | 透明玻璃外殼 | clear glass exterior showing all internal parts |
| /innerworks | 內部齒輪特寫 | close-up of internal gears and mechanisms |
| /scaledmodel | 迷你模型剖面 | miniature scale model cutaway |
| /crosshatch | 只用交叉線陰影 | pen illustration using only crosshatch shading |
| /anatomymap | 解剖圖風格標註 | anatomy chart style with labeled parts |
| /buildorder | 由左到右組裝順序 | assembly sequence shown step by step from left to right |


### 分類 03｜海報與卡片

| 指令 | 效果 | 展開句 |
|---|---|---|
| /onemainshot | 戲劇感電影海報 | dramatic cinematic movie poster, single hero shot, space for title |
| /cardformat | 附數值的收藏卡 | collectible trading card with a stats panel and decorative border |
| /gridnine | 九宮格九種視角 | 3x3 grid showing nine different views of the subject |
| /marbleform | 白色大理石雕像 | rendered as a white marble statue |
| /glasscopy | 透明玻璃雕塑 | transparent glass sculpture with light refraction |
| /chromewet | 液態鉻金屬質感 | liquid chrome finish, glossy reflective metal |
| /clayfeel | 帶指紋的黏土 | handmade clay figure with visible fingerprints |
| /paperlayer | 層疊剪紙 | layered cut-paper art with depth and soft shadows |
| /bronzeform | 做舊青銅雕像 | aged bronze statue with green patina |
| /goldstatue | 拋光金色雕像 | polished gold statue with luxurious reflections |
| /icecarve | 融化中的冰雕 | carved ice sculpture, slightly melting with drips |
| /sandsculpt | 精細沙雕 | detailed beach sand sculpture |
| /woodcarve | 帶刀痕的木雕 | hand-carved wood with visible chisel marks |
| /neonoutline | 發光霓虹輪廓 | glowing neon tube outline on a dark wall |
| /stickeredge | 白邊模切貼紙 | die-cut sticker with a thick white border |
| /holoshine | 彩虹鐳射卡 | rainbow holographic foil card |
| /vintagepatch | 舊刺繡布章 | worn embroidered patch with frayed threads |
| /varsitybadge | 校隊字母徽章 | varsity chenille block letter badge |
| /tourposter | 巡演演唱會海報 | concert tour poster with a list of dates |
| /concertflyer | 小型活動傳單 | small event flyer, bold type, photocopied feel |
| /festivalcard | 繽紛節慶卡片 | colorful festival greeting card |
| /zineprint | 粗糙影印小誌 | rough photocopied zine aesthetic, grainy black and white |
| /postermockup | 釘在牆上的海報 | poster taped to a wall, realistic mockup |
| /framedart | 木框裱褙畫作 | artwork in a wooden frame hanging on a wall |


### 分類 04｜商品攝影

| 指令 | 效果 | 展開句 |
|---|---|---|
| /purewhite | 乾淨純白背景 | product on a clean pure white seamless background, e-commerce style |
| /inhandreal | 手持商品 | product held naturally in a real hand |
| /allcolors | 全色系一字排開 | all color variants lined up in a row |
| /floatnoline | 無支撐懸浮 | product floating mid-air with no visible support |
| /bundlepack | 完整成套組合 | full matching set arranged together |
| /nextobject | 旁放物品對照尺寸 | placed beside a common everyday object for scale |
| /liquidfreeze | 液體飛濺定格 | liquid splash frozen mid-air around the product |
| /deviceframe | 放進裝置樣機 | displayed inside a device mockup screen |
| /shelfrow | 零售貨架陳列 | placed on a retail store shelf among other products |
| /handoutshot | 手對手傳遞 | product being passed from one hand to another |
| /giftready | 打開的禮盒 | inside an open gift box with tissue paper |
| /travelcase | 收進旅行包 | packed neatly inside a travel bag |
| /openbox | 剛開箱 | freshly unboxed, open box beside the product |
| /closebox | 密封直立包裝盒 | sealed retail box standing upright |
| /stackedset | 整齊堆疊 | neatly stacked units |
| /rotatingview | 六個角度展示 | six angles of the product shown in one image |
| /macrotexture | 材質微距特寫 | macro close-up of the material texture |
| /coloredbg | 同色系純色背景 | solid backdrop in a color matching the product |
| /lifestylehold | 真實日常使用 | real everyday use in a natural lifestyle setting |
| /outdooruse | 戶外自然使用 | used naturally outdoors |
| /wearingit | 實際穿戴 | worn by a model as intended |
| /demoaction | 使用中的瞬間 | captured mid-use, action moment |
| /cleanupshot | 乾淨精修 | clean, polished, retouched commercial shot |
| /packedtogo | 打包好準備出貨 | packed in a shipping box with label, ready to ship |


### 分類 05｜鏡頭與構圖

| 指令 | 效果 | 展開句 |
|---|---|---|
| /closeup | 特寫 | tight close-up shot filling the frame |
| /extremeclose | 極致特寫 | extreme close-up of a single detail |
| /wideshot | 廣角全景 | wide establishing shot showing the full environment |
| /birdseye | 鳥瞰俯視 | bird’s-eye view directly from above |
| /wormseye | 蟲視仰角 | worm’s-eye view looking up from the ground |
| /lowangle | 低角度仰拍 | low-angle shot making the subject look powerful |
| /highangle | 高角度俯拍 | high-angle shot looking down at the subject |
| /dutchtilt | 傾斜構圖 | dutch angle, tilted camera for tension |
| /overshoulder | 過肩鏡頭 | over-the-shoulder shot |
| /pov | 第一人稱視角 | first-person point-of-view shot, hands visible |
| /symmetry | 對稱構圖 | perfectly symmetrical centered composition |
| /thirds | 三分法構圖 | subject placed on a rule-of-thirds line |
| /leadline | 引導線構圖 | leading lines drawing the eye to the subject |
| /framein | 框中框 | subject framed by a doorway or window |
| /negspace | 大量留白 | minimal composition with large negative space for text |
| /shallowdof | 淺景深 | shallow depth of field, creamy blurred background |
| /deepfocus | 全景深 | deep focus, everything sharp from front to back |
| /fisheye | 魚眼 | fisheye lens distortion |
| /telephoto | 長焦壓縮 | telephoto lens compression, flattened background |
| /macrolens | 微距鏡頭 | macro lens revealing tiny details |
| /motionblur | 動態模糊 | motion blur showing movement |
| /panning | 追焦 | panning shot, sharp subject with streaked background |
| /tiltshift | 移軸微縮 | tilt-shift miniature effect |
| /drone | 空拍 | aerial drone shot from high above |


### 分類 06｜人像與表情

| 指令 | 效果 | 展開句 |
|---|---|---|
| /headshot | 職業大頭照 | professional headshot, clean neutral background |
| /candid | 自然抓拍 | candid unposed moment, natural behavior |
| /laughing | 開懷大笑 | genuine laughing expression, eyes crinkled |
| /softsmile | 微笑 | soft natural closed-mouth smile |
| /serious | 嚴肅神情 | serious focused expression |
| /surprised | 驚訝 | surprised wide-eyed expression, mouth slightly open |
| /thinking | 沉思 | thoughtful pose, hand on chin |
| /lookaway | 看向遠方 | looking away from the camera into the distance |
| /eyecontact | 直視鏡頭 | direct eye contact with the camera |
| /halfbody | 半身 | half-body portrait from the waist up |
| /fullbody | 全身 | full-body shot from head to toe |
| /profile | 側臉 | side profile portrait |
| /backview | 背影 | shot from behind, face not visible |
| /walking | 走路中 | walking toward the camera with a natural stride |
| /sitting | 坐姿 | sitting casually and relaxed |
| /armscross | 雙手抱胸 | confident pose with arms crossed |
| /pointing | 手指指向 | pointing at something off-frame |
| /groupshot | 團體照 | group of people posed together |
| /coupleshot | 雙人互動 | two people interacting naturally |
| /teamwork | 團隊協作 | team working together around a table |
| /speaker | 台上演講 | speaking on stage holding a microphone |
| /creator | 創作者拍攝 | content creator filming with a phone and ring light |
| /workdesk | 辦公桌工作 | working at a desk with a laptop |
| /streetstyle | 街拍 | street style fashion photo on a city sidewalk |


### 分類 07｜藝術風格與畫風

| 指令 | 效果 | 展開句 |
|---|---|---|
| /oilpaint | 油畫 | classical oil painting with visible brushstrokes |
| /watercolor | 水彩 | soft watercolor with paper texture and bleeding edges |
| /inkwash | 水墨 | Chinese ink wash painting, expressive brush, empty space |
| /ukiyoe | 浮世繪 | Japanese ukiyo-e woodblock print |
| /popart | 普普藝術 | pop art with halftone dots and bold flat colors |
| /impression | 印象派 | impressionist painting, loose dabs of light and color |
| /artdeco | 裝飾藝術 | art deco geometric style, gold and black |
| /artnouveau | 新藝術 | art nouveau flowing organic lines and floral frames |
| /bauhaus | 包浩斯 | Bauhaus geometric shapes and primary colors |
| /minimal | 極簡 | minimalist, few simple shapes, lots of empty space |
| /surreal | 超現實 | surrealist dreamlike scene with impossible elements |
| /pencilsketch | 鉛筆素描 | graphite pencil sketch with soft shading |
| /charcoal | 炭筆 | charcoal drawing with smudged shadows |
| /pastel | 粉彩 | soft chalk pastel drawing |
| /gouache | 不透明水彩 | gouache painting, matte flat colors |
| /linocut | 版畫 | linocut print with bold carved lines |
| /riso | 孔版印刷 | risograph print, grainy texture, limited colors |
| /collage | 拼貼 | mixed media paper collage |
| /mosaic | 馬賽克 | made of small mosaic tiles |
| /stainedglass | 彩繪玻璃 | stained glass window with lead lines |
| /graffiti | 塗鴉 | street graffiti mural on a brick wall |
| /lineart | 線稿 | clean single-weight line art, no shading |
| /vectorflat | 扁平向量 | flat vector illustration, simple shapes |
| /isometric | 等角視圖 | isometric illustration, 30-degree angles |


### 分類 08｜插畫與動漫

| 指令 | 效果 | 展開句 |
|---|---|---|
| /animecel | 日系動畫 | anime cel-shaded style, clean outlines |
| /warmanime | 溫暖手繪動畫感 | warm hand-painted anime film style, soft light, detailed backgrounds |
| /chibi | Q 版 | chibi style, big head and small body |
| /manga | 黑白漫畫 | black and white manga panel with screentone |
| /comicbook | 美式漫畫 | American comic book style, bold ink and halftone |
| /cartoon3d | 3D 卡通 | 3D animated cartoon style, soft lighting, expressive face |
| /picturebook | 繪本 | children’s picture book illustration |
| /kawaii | 可愛風 | kawaii cute style, pastel colors, rounded shapes |
| /pixelart | 像素 | 16-bit pixel art |
| /voxel | 體素 | voxel art made of small cubes |
| /claymation | 黏土動畫 | claymation stop-motion look |
| /papercut | 剪紙插畫 | paper cut illustration with layered depth |
| /sticker | 貼圖 | cute messaging-app sticker style, white outline |
| /emojiset | 表情符號組 | set of emoji icons in a grid |
| /charsheet | 角色設定表 | character reference sheet, front, side and back views |
| /expressions | 表情包 | expression sheet showing 9 different emotions |
| /mascot | 吉祥物 | brand mascot character design, simple and memorable |
| /doodle | 隨手塗鴉 | hand-drawn doodle, loose pen lines |
| /storyboard | 分鏡 | storyboard panels with camera arrows |
| /fourpanel | 四格漫畫 | four-panel comic strip |
| /webtoon | 條漫 | vertical webtoon panel |
| /cyberanime | 賽博動漫 | cyberpunk anime, neon city |
| /fantasyart | 奇幻插畫 | epic fantasy illustration |
| /retroanime | 90 年代動畫 | 1990s retro anime, film grain, muted colors |


### 分類 09｜3D 與材質

| 指令 | 效果 | 展開句 |
|---|---|---|
| /clay3d | 黏土 3D | soft matte 3D clay render |
| /glossy3d | 亮面 3D | glossy plastic 3D render |
| /inflated | 膨脹充氣 | inflated puffy balloon-like 3D shape |
| /glass3d | 霧面玻璃 3D | frosted glass 3D icon with soft glow |
| /metal | 金屬 | brushed metal surface |
| /velvet | 絨布 | soft velvet fabric texture |
| /knit | 毛線編織 | knitted wool texture |
| /felt | 羊毛氈 | needle-felted wool figure |
| /plush | 絨毛玩偶 | soft plush toy |
| /bricks | 積木 | built from colorful toy building bricks |
| /origami | 摺紙 | origami folded paper |
| /porcelain | 陶瓷 | glazed porcelain |
| /jade | 玉石 | carved translucent jade |
| /crystal | 水晶 | faceted crystal with rainbow refraction |
| /liquid | 液態 | liquid flowing form |
| /smoke | 煙霧 | formed from swirling smoke |
| /fire | 火焰 | made of fire |
| /water | 水 | made of splashing water |
| /cloud | 雲朵 | shaped from fluffy clouds |
| /flowerform | 花朵組成 | made entirely of flowers |
| /foodform | 食物組成 | made of food ingredients |
| /miniworld | 微縮世界 | miniature diorama world |
| /lowpoly | 低多邊形 | low-poly 3D, faceted surfaces |
| /isoroom | 等角房間 | isometric 3D room cutaway |


### 分類 10｜色調與調色

| 指令 | 效果 | 展開句 |
|---|---|---|
| /warmtone | 暖色調 | warm color grading, amber tones |
| /cooltone | 冷色調 | cool blue color grading |
| /mono | 黑白 | black and white monochrome |
| /sepia | 復古褐 | sepia tone |
| /pastelpalette | 馬卡龍色 | soft pastel color palette |
| /vivid | 高飽和 | vivid saturated colors |
| /muted | 低飽和 | muted desaturated palette |
| /earthtone | 大地色 | earthy palette of brown, olive and beige |
| /tealorange | 青橙電影色 | teal and orange cinematic color grading |
| /filmfade | 底片褪色 | faded film look with lifted blacks |
| /filmwarm | 暖調底片 | warm 35mm film color with fine grain |
| /filmgreen | 綠調底片 | cool green-tinted film color |
| /duotone | 雙色調 | duotone in two colors |
| /neonpalette | 霓虹配色 | neon palette of magenta, cyan and purple |
| /goldenhour | 黃金時刻 | golden hour warm sunlight |
| /bluehour | 藍調時刻 | blue hour, deep blue sky after sunset |
| /highkey | 高調明亮 | bright airy high-key image |
| /lowkey | 低調暗沉 | dark moody low-key image |
| /hdr | 高動態 | HDR with rich detail in highlights and shadows |
| /matte | 霧面 | matte finish with soft contrast |
| /grain | 顆粒感 | heavy film grain |
| /vignette | 暗角 | dark vignette around the edges |
| /colorpop | 局部色彩 | black and white image with one color accent |
| /brandcolor | 品牌色限定 | color palette restricted to [your brand colors] |


### 分類 11｜場景與環境

| 指令 | 效果 | 展開句 |
|---|---|---|
| /cafe | 咖啡廳 | cozy cafe interior with wooden tables |
| /office | 辦公室 | modern bright office |
| /studio | 攝影棚 | photo studio with seamless backdrop |
| /homedesk | 居家書桌 | home desk setup with laptop and plants |
| /street | 城市街道 | busy city street |
| /nightmarket | 夜市 | Taiwanese night market with food stalls and lights |
| /rooftop | 頂樓 | rooftop at sunset with city skyline |
| /beach | 海邊 | sandy beach by the sea |
| /forest | 森林 | lush green forest |
| /mountain | 山景 | mountain landscape |
| /desert | 沙漠 | desert dunes |
| /snow | 雪景 | snowy landscape |
| /rain | 雨天 | rainy street with reflections on wet ground |
| /subway | 捷運車廂 | metro train car interior |
| /library | 圖書館 | quiet library with tall bookshelves |
| /kitchen | 廚房 | home kitchen |
| /bedroom | 臥室 | cozy bedroom |
| /gym | 健身房 | modern gym |
| /classroom | 教室 | classroom with desks and whiteboard |
| /stage | 舞台 | stage with spotlights and audience |
| /space | 太空 | outer space with stars and planets |
| /underwater | 水下 | underwater scene with light rays |
| /futurecity | 未來城市 | futuristic city with flying vehicles |
| /convenience | 便利商店 | Taiwanese convenience store interior |


### 分類 12｜時代與復古

| 指令 | 效果 | 展開句 |
|---|---|---|
| /1920s | 1920 年代 | 1920s era photograph, art deco fashion |
| /1950s | 1950 年代 | 1950s Americana style |
| /1970s | 1970 年代 | 1970s retro film colors |
| /1980s | 1980 年代 | 1980s neon synthwave style |
| /1990s | 1990 年代 | 1990s snapshot with direct flash |
| /y2k | Y2K | Y2K aesthetic, chrome, bubbles, glossy |
| /polaroid | 拍立得 | instant film photo with white frame |
| /disposable | 即可拍 | disposable camera flash photo |
| /vhs | VHS | VHS tape frame with glitch lines |
| /crtscreen | CRT 螢幕 | displayed on an old CRT monitor |
| /oldnewspaper | 舊報紙 | vintage newspaper print |
| /oldmap | 古地圖 | antique hand-drawn map |
| /vintagead | 復古廣告 | 1960s print advertisement |
| /retrocomputer | 復古電腦介面 | early 1990s desktop computer window interface |
| /daguerreo | 銀版照片 | daguerreotype early photograph |
| /taiwanretro | 台灣懷舊 | 1980s Taiwan retro street signage |
| /hongkong | 港風 | 1990s Hong Kong film look with neon signs |
| /showa | 昭和 | Showa-era Japan retro |
| /victorian | 維多利亞版畫 | Victorian engraving illustration |
| /medieval | 中世紀手抄本 | medieval illuminated manuscript |
| /egypt | 古埃及壁畫 | ancient Egyptian wall painting |
| /gongbi | 古風工筆 | Chinese gongbi fine-line painting |
| /retrofuture | 復古未來 | retro-futurism, 1960s vision of the future |
| /steampunk | 蒸汽龐克 | steampunk with brass gears and pipes |


### 分類 13｜字體與排版

> 這一類最適合 ChatGPT 與 Ideogram。要出現的文字請用引號框起來，例如 /bigtitle "三分鐘學會打光"。
| 指令 | 效果 | 展開句 |
|---|---|---|
| /bigtitle | 超大標題 | huge bold headline “[文字]” filling the top third |
| /handletter | 手寫字 | hand-lettered text “[文字]” |
| /brushfont | 毛筆字 | Chinese brush calligraphy “[文字]” |
| /serif | 襯線字 | elegant serif typography |
| /sans | 無襯線字 | clean modern sans-serif typography |
| /neontext | 霓虹字 | glowing neon sign text “[文字]” |
| /chalk | 粉筆字 | chalkboard lettering |
| /3dtext | 立體字 | bold 3D extruded text |
| /bubbletext | 泡泡字 | puffy bubble letters |
| /stamp | 印章字 | rubber stamp text, slightly uneven ink |
| /stencil | 鏤空字 | stencil lettering |
| /graffititext | 塗鴉字 | graffiti lettering |
| /typeposter | 文字海報 | typographic poster, text as the main visual |
| /textmask | 文字遮罩 | image visible only through large letters |
| /highlighter | 螢光筆 | yellow highlighter behind key words |
| /speechbubble | 對話框 | speech bubble containing “[文字]” |
| /sticky | 便利貼 | text written on sticky notes |
| /receipt | 收據 | text printed on a paper receipt |
| /signboard | 招牌 | shop signboard reading “[文字]” |
| /tshirt | T 恤印字 | t-shirt printed with “[文字]” |
| /bookcover | 書封 | book cover with title “[文字]” |
| /magcover | 雜誌封面 | magazine cover layout with masthead and cover lines |
| /quotecard | 金句卡 | centered quote “[文字]” with author name below |
| /infographic | 資訊圖表 | clean infographic with icons, numbers and short labels |


### 分類 14｜社群貼文版面

| 指令 | 效果 | 展開句 |
|---|---|---|
| /igcarousel | IG 輪播封面 | 4:5 vertical Instagram carousel cover with bold headline |
| /igstory | IG 限動 | 9:16 vertical Instagram story layout |
| /reelcover | Reels 封面 | 9:16 vertical cover with title inside the center safe zone |
| /ytthumb | YouTube 縮圖 | 16:9 thumbnail, expressive face plus 3-word headline |
| /beforeafter | 前後對比 | split-screen before and after comparison |
| /vsbattle | 對決 | VS comparison split screen with two sides |
| /listicle | 清單貼文 | numbered list layout |
| /stepcard | 步驟卡 | step-by-step cards with numbers |
| /postcard | 社群貼文截圖 | social media post screenshot card |
| /chatshot | 對話截圖 | chat conversation screenshot |
| /notesapp | 備忘錄 | phone notes app screenshot |
| /memeformat | 迷因 | meme layout with top and bottom text |
| /quotepost | 語錄貼文 | quote post with large centered text |
| /datacard | 數據卡 | one big number stat card with short caption |
| /flowchart | 流程圖 | clean flowchart with arrows |
| /mindmap | 心智圖 | mind map branching from a central idea |
| /timeline | 時間軸 | horizontal timeline with milestones |
| /checklist | 勾選清單 | checklist with tick boxes |
| /tierlist | 排行榜 | tier list ranked S, A, B, C |
| /pricecard | 價目卡 | price card with plans and prices |
| /eventpost | 活動公告 | event announcement with date, time and place |
| /courseposter | 課程文宣 | course promotion poster with title, speaker and date |
| /testimonial | 好評卡 | customer review card with stars |
| /ctaend | 結尾 CTA | closing slide with “留言「[關鍵字]」” call to action |


### 分類 15｜圖片編輯與修圖

> 這一類要先上傳原圖，最適合 ChatGPT 與 Gemini。
| 指令 | 效果 | 展開句 |
|---|---|---|
| /removebg | 去背 | remove the background, keep the subject on plain white |
| /changebg | 換背景 | replace the background with [場景], keep the subject identical |
| /keepface | 鎖臉 | keep the face exactly identical, change only [要改的地方] |
| /outfitswap | 換裝 | change the outfit to [服裝], keep face and pose |
| /relight | 重新打光 | relight the photo with [光線], keep everything else |
| /upscale | 提升畫質 | sharpen and enhance details, keep composition |
| /colorize | 黑白上色 | colorize this black and white photo naturally |
| /restore | 老照片修復 | restore this old photo, fix scratches and fading |
| /removeobj | 移除物件 | remove [物件] and fill the area naturally |
| /addobj | 加入物件 | add [物件] to the scene with matching light and shadow |
| /extend | 延伸畫面 | extend the image beyond its borders, matching the scene |
| /crop45 | 改 4:5 | recompose to 4:5 vertical without cutting the subject |
| /agechange | 年齡變化 | show the same person at age [年齡] |
| /expression | 改表情 | change the expression to [表情], keep identity |
| /pose | 改姿勢 | change the pose to [姿勢], keep identity and outfit |
| /stylize | 套畫風 | convert this photo into [畫風] |
| /toon | 照片變卡通 | turn this photo into a cartoon character, keep likeness |
| /sketchify | 照片變素描 | turn this photo into a pencil sketch |
| /productclean | 商品修圖 | clean up dust, fix reflections, sharpen product edges |
| /skinretouch | 自然修膚 | natural skin retouch, keep real skin texture |
| /textreplace | 改圖中文字 | replace the text “[原文字]” with “[新文字]”, same font style |
| /translate | 圖中文字翻譯 | translate all text in the image to [語言], keep layout |
| /consistent | 角色一致 | same character as the reference, placed in [新場景] |
| /mergetwo | 兩圖合成 | combine image 1 and image 2 into one natural scene |


### 分類 16｜食物與餐飲

| 指令 | 效果 | 展開句 |
|---|---|---|
| /menushot | 菜單照 | clean menu photo of the dish, appetizing |
| /flatlay | 俯拍擺盤 | overhead flat lay of dishes on a table |
| /steam | 冒熱氣 | visible steam rising from hot food |
| /drip | 醬汁滴落 | sauce dripping slowly |
| /cheesepull | 起司牽絲 | stretchy melted cheese pull |
| /pourshot | 倒入瞬間 | liquid being poured, frozen moment |
| /ingredients | 食材散落 | raw ingredients scattered around the dish |
| /cutopen | 切面 | cut open to show the inside layers |
| /bento | 便當 | bento box neatly arranged |
| /streetfood | 小吃攤 | street food stall atmosphere |
| /bubbletea | 手搖飲 | bubble tea cup with condensation drops |
| /coffeeart | 拉花 | latte art in a ceramic cup |
| /dessert | 甜點 | elegant dessert plating |
| /cocktail | 調酒 | cocktail glass with garnish, bar lighting |
| /rustictable | 木桌質感 | rustic wooden table surface |
| /marbletable | 大理石桌 | white marble table surface |
| /darkfood | 暗調美食 | dark moody food photography |
| /brightfood | 明亮美食 | bright airy food photography |
| /deliverybox | 外送包裝 | takeaway packaging with food |
| /chefhand | 主廚手部 | chef’s hands plating the dish |
| /familymeal | 家庭餐桌 | family dinner table with shared dishes |
| /foodpack | 食品包裝 | packaged food product design |
| /recipecard | 食譜卡 | recipe card with ingredients and steps |
| /foodposter | 美食海報 | food promotion poster with bold title |


### 分類 17｜空間與室內設計

| 指令 | 效果 | 展開句 |
|---|---|---|
| /livingroom | 客廳 | spacious living room interior |
| /japandi | 日式北歐 | Japandi interior, light wood, neutral tones |
| /industrial | 工業風 | industrial interior, exposed brick and metal |
| /scandi | 北歐 | Scandinavian interior, white walls, light wood |
| /wabisabi | 侘寂 | wabi-sabi interior, raw plaster, natural imperfection |
| /luxury | 輕奢 | modern luxury interior, marble and brass details |
| /midcentury | 中世紀現代 | mid-century modern interior |
| /boho | 波希米亞 | bohemian interior with rattan and plants |
| /minimalhome | 極簡居家 | minimalist home, very few objects |
| /cozyroom | 溫馨小房 | small cozy room with warm lamps |
| /shopfront | 店面門面 | shop front facade |
| /retail | 店內陳列 | retail store interior display |
| /officedesign | 辦公空間 | modern office space design |
| /cafedesign | 咖啡廳設計 | cafe interior design |
| /floorplan | 平面配置圖 | furnished floor plan, top view |
| /render3d | 室內 3D 渲染 | photorealistic 3D interior render |
| /beforereno | 裝修前後 | before and after renovation comparison |
| /moodboard | 情緒板 | interior mood board with samples and photos |
| /materialboard | 材質板 | material board with wood, stone and fabric swatches |
| /daylight | 自然採光 | natural daylight through large windows |
| /nightinterior | 夜間燈光 | interior at night with warm lighting |
| /container | 貨櫃屋 | shipping container architecture |
| /exterior | 建築外觀 | building exterior view |
| /garden | 庭院 | landscaped garden courtyard |


### 分類 18｜品牌與 Logo

| 指令 | 效果 | 展開句 |
|---|---|---|
| /logomark | 圖形標誌 | simple symbol logo, flat, scalable |
| /wordmark | 文字標誌 | wordmark logo spelling “[品牌名]” |
| /monogram | 字母組合 | monogram logo from initials “[字母]” |
| /emblem | 徽章型 | emblem logo enclosed in a badge shape |
| /mascotlogo | 吉祥物 Logo | mascot character logo |
| /lineicon | 線條 icon | thin line icon, single stroke weight |
| /iconset | icon 組 | consistent set of 9 icons in a grid |
| /appicon | App icon | rounded-square app icon |
| /brandboard | 品牌規範板 | brand identity board with logo, colors and fonts |
| /mockupcard | 名片樣機 | business card mockup on a desk |
| /mockupcup | 杯子樣機 | logo printed on a coffee cup mockup |
| /mockupbag | 提袋樣機 | logo on a tote bag mockup |
| /mockupshirt | 衣服樣機 | logo on a t-shirt mockup |
| /signage | 招牌樣機 | logo on an outdoor sign mockup |
| /packaging | 包裝設計 | product packaging design |
| /label | 標籤設計 | product label design |
| /brandsticker | 品牌貼紙 | die-cut brand sticker |
| /pattern | 品牌圖騰 | seamless repeating brand pattern |
| /colorpalette | 配色卡 | color palette card with 5 swatches and hex codes |
| /avatar | 頭像 Logo | circular profile picture logo |
| /socialkit | 社群視覺套組 | social media kit with matching post templates |
| /badge | 認證章 | certification badge |
| /seal | 復古印章 | vintage round seal stamp |
| /merch | 周邊 | branded merchandise set |


## 第六部分｜常用組合技

照抄就能用。把 [ ] 換成你的內容。

1. 電商商品主圖

```
[你的商品] /purewhite /softglow /cleanupshot  4:5 vertical
```
2. 有質感的商品情境照

```
[你的商品] 放在木頭桌上 /lifestylehold /goldenhour /shallowdof /filmwarm
```
3. IG 輪播封面

```
/igcarousel /bigtitle "[你的標題]" /negspace /warmtone
```
4. YouTube 縮圖

```
一個驚訝的男生指著旁邊 /ytthumb /surprised /pointing /vivid /bigtitle "[三個字]"
```
5. 個人品牌形象照（上傳自己的照片）

```
/keepface /headshot /studio /softglow  只換背景和服裝
```
6. 產品拆解圖

```
[你的產品] /revealparts /techdraw /purewhite
```
7. 課程文宣

```
/courseposter /bigtitle "[課程名稱]" /speaker /tealorange  4:5 vertical
```
8. 吉祥物設計（一次做齊）

```
[角色描述] /mascot /cartoon3d /charsheet
```
做好之後再下：

```
同一隻角色 /consistent /expressions
```
9. 復古感生活照

```
[人物描述] 在街頭 /disposable /1990s /grain
```
10. 室內設計提案圖

```
[坪數與空間] /japandi /render3d /daylight
```

## 第七部分｜出圖失敗怎麼救

| 狀況 | 原因 | 解法 |
|---|---|---|
| 圖跟想像差很多 | 指令疊太多、互相衝突 | 砍到 3 個以內，同類只留一個 |
| 中文字錯字、亂碼 | 字太多或字太小 | 一張圖的中文字控制在 20 字內，或生完圖再用 Canva 後製加字 |
| 人臉跑掉 | 一次改太多東西 | 加 /keepface，一次只改一件事 |
| 比例不對 | 沒寫比例 | 句尾加 4:5 vertical 或 9:16 vertical |
| 每次風格都不一樣 | 沒有固定描述 | 把滿意那張的完整 prompt 存起來，下次整段複製再改主體 |
| Midjourney 看不懂 | 斜線指令不通用 | 改貼「展開句」英文 |
| 改了一個地方，其他地方也變了 | 指令太模糊 | 明確寫「其他全部保持不變，只改 [某處]」 |

最後一個習慣： 每次做出滿意的圖，把整段 prompt 存進 Notion。一個月後你會有一份只屬於你的指令庫，做圖速度會快好幾倍。

