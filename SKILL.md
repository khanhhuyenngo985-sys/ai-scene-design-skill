# scene-design

---
name: scene-design
description: >
  AI时代场景设计完整方法论，覆盖动画风格与写实风格。包含建筑空间设计语言、
  构图光影、情绪引导、分镜结构、场景板规范及AI出图工作流。
  知识融合自：皓哥内门培训逐字稿 + 白梦客知识库 + 建筑/空间设计专业知识。
---

## 核心理念：场景 = 世界观的物理容器

> 场景设计的终极目标不是"好看"，而是让场景本身成为叙事工具——
> 它承载情绪、定义角色所处的世界、并开放给观众进行二创。

**场景的三重功能：**
1. **叙事锚点**：每一个场景名都是 `@标签`，是 AI 生成的稳定参考点
2. **情绪容器**：场景的光影/构图/色调直接决定观众的情绪体验
3. **IP 宇宙入口**：好的场景，观众会拿去做二创（"雪山湖里"就是一个世界观符号，不是背景图）

---

## 场景设计的 AI 时代范式转变

| 旧范式 | 新范式 |
|--------|--------|
| 场景 = 背景板 | 场景 = 世界观前期容器 |
| 场景服务于角色 | 场景与角色共同叙事 |
| 追求精美写实 | 追求情绪辨识度 |
| 场景固定不变 | 场景开放，供观众/AI 二创 |
| 正面全景图够用 | 需要多角度、多光效变体 |

**关键认知**：设定稿中的场景描述 = 写给 AI 的提示词。场景设定越精准，后续视频生成的氛围越可控，越不需要每次重新描述。

---

## 场景板标准规范（主体库三板之场景板）

> 来源：白梦客知识库 `wiki/AI视频创作/Vidu/主体库大师.md`

| 字段 | 标准 |
|------|------|
| 场景名 | 简洁有辨识度，可作为 `@标签` 引用 |
| 出场集数 | 首次出场集数 |
| 场景描述 | 200字以上：时间段、地点、空间布局、光影基调、氛围 |
| 文生图描述词 | 150字以上，结构：`主体环境 + 光影参数 + 视觉风格 + 情感氛围` |

### 场景描述词结构公式

```
主体环境（地点/空间类型）
+ 时间/天气（决定自然光色温）
+ 空间逻辑（人物动线/机位可能性）
+ 光影参数（主光类型 + 介质 + 光比）
+ 氛围关键词（情绪方向）
+ 风格标签（画风/导演风格参考）
```

### 场景设计三原则

| 原则 | 说明 |
|------|------|
| **空间逻辑** | 场景布局需符合人物动线和摄影机位设置 |
| **时代/世界观特征** | 场景装饰、建筑风格需准确反映世界观背景 |
| **光影优先** | 场景光照设计需考虑时间、天气、情绪氛围需求 |

---

## 分镜命名与场景锚定规则

> 来源：白梦客知识库 `wiki/AI视频创作/Vidu/分镜生成系统.md`

### @标签引用规范

在分镜描述中，场景必须用 `@标签` 锚定：

```
分镜描述格式：
在【时间描述】的【@场景名】中，[@角色名] 做了什么...

示例：
在瓢泼大雨的夜晚，【@废弃剧场】中，[@小丑] 缓缓张开双臂...
```

**场景绘图提示词格式：**
```
@场景名：（室内/室外广角，建立镜头）场景的详细视觉描述...
```

### 禁止代词规则

所有分镜必须是**可独立理解的、自包含的原子化指令**。
- ❌ 禁止：「他站在那里」
- ✅ 要求：「[@角色名] 站在 [@场景名] 的中央」

---

## 建筑风格 × 情绪速查表

> 精确的建筑风格词汇是场景提示词的基础。无论动画还是写实，风格名称决定了 AI 输出的空间气质。

### 西方建筑风格

| 风格 | 年代 | 视觉特征 | 情绪语言 | AI 提示词 |
|------|------|---------|---------|----------|
| **古希腊** | BC 8C-1C | 柱式（多立克/爱奥尼/科林斯）、三角楣、比例严谨 | 理性、崇高、秩序 | `Greek temple, Doric columns, marble, symmetrical` |
| **古罗马** | BC 1C-5C | 拱券、穹顶、混凝土、宏大公共空间 | 权力、永恒、帝国感 | `Roman architecture, arched vault, grand colonnade` |
| **哥特** | 12C-16C | 尖拱、飞扶壁、彩窗玻璃、高耸尖塔 | 敬畏、神秘、升腾 | `Gothic cathedral, pointed arches, stained glass, ribbed vault` |
| **文艺复兴** | 14C-17C | 圆顶、对称立面、古典柱式复兴、人体比例 | 和谐、人文、理想化 | `Renaissance palazzo, dome, symmetrical facade, classical order` |
| **巴洛克** | 17C-18C | 曲线、装饰繁复、壁画穹顶、明暗戏剧 | 戏剧性、奢华、狂欢 | `Baroque interior, ornate ceiling fresco, dramatic chiaroscuro` |
| **洛可可** | 18C | 贝壳曲线、粉彩、金箔、极致装饰 | 轻盈、甜腻、放纵 | `Rococo salon, pastel colors, gilded ornament, shell motifs` |
| **新古典** | 18C-19C | 回归严谨柱式、对称、简化装饰 | 庄严、理性回归、公共性 | `Neoclassical building, grand columns, pediment, clean lines` |
| **工业革命** | 19C | 铸铁结构、玻璃幕墙、火车站式大跨度 | 进步、机械、力量 | `Industrial architecture, iron framework, glass roof, factory` |
| **新艺术** | 1890-1910 | 有机曲线、植物纹样、铸铁装饰 | 自然、浪漫、颓废 | `Art Nouveau, organic curves, floral ironwork, Mucha style` |
| **装饰艺术** | 1920-1940 | 几何图案、金属光泽、阶梯式轮廓 | 摩登、奢华、速度 | `Art Deco, geometric patterns, chrome, stepped silhouette` |
| **包豪斯/现代主义** | 1920-1970 | 几何纯净、白墙平顶、钢玻璃混凝土 | 理性、极简、乌托邦 | `Bauhaus, flat roof, white walls, glass curtain wall, minimal` |
| **粗野主义** | 1950-1975 | 清水混凝土、巨型体块、裸露结构 | 压迫、力量、反乌托邦 | `Brutalist concrete, raw exposed structure, massive block` |
| **后现代** | 1970-1990 | 拼贴历史符号、色彩对撞、反讽装饰 | 讽刺、游戏、多义 | `Postmodern architecture, colorful, ironic classical reference` |
| **解构主义** | 1980- | 倾斜扭曲、碎片化、非线性 | 不安、挑战、动态 | `Deconstructivist, tilted walls, fragmented forms, Gehry style` |
| **参数化** | 2000- | 流线型曲面、算法生成形态 | 未来、有机科技 | `Parametric architecture, flowing curves, Zaha Hadid style` |

### 东方建筑风格

| 风格 | 视觉特征 | 情绪语言 | AI 提示词 |
|------|---------|---------|----------|
| **中式传统** | 斗拱、飞檐、院落围合、中轴对称 | 礼序、内敛、天人合一 | `traditional Chinese architecture, curved eaves, courtyard, dougong brackets` |
| **中式园林** | 假山水池、漏窗月门、借景框景 | 诗意、隐逸、移步换景 | `Chinese garden, moon gate, rockery, lattice window, borrowed scenery` |
| **日式传统** | 障子纸门、榻榻米、缘侧走廊、枯山水 | 侘寂、空寂、无常 | `Japanese traditional, tatami, shoji screen, engawa, wabi-sabi` |
| **日式侘寂** | 不完美、不均匀、朴素材料、自然老化 | 接受无常、静默之美 | `wabi-sabi interior, imperfect textures, aged wood, muted tones` |
| **韩式韩屋** | 大青瓦、温突地暖、丹青彩画 | 端正、温暖、自然融合 | `Korean hanok, curved tiled roof, ondol floor, wooden structure` |
| **东南亚** | 高脚楼、热带木构、开放通风 | 热带松弛、自然原始 | `Southeast Asian stilted house, tropical wood, open-air, lush vegetation` |

### 虚构/跨界风格

| 风格 | 视觉特征 | 情绪语言 | AI 提示词 |
|------|---------|---------|----------|
| **赛博朋克** | 霓虹密集、巨型广告牌、层叠高架、雨夜 | 异化、压迫、繁华中的孤独 | `cyberpunk city, neon signs, rain-soaked streets, mega structures` |
| **蒸汽朋克** | 齿轮铜管、维多利亚+蒸汽动力 | 复古未来、冒险 | `steampunk, brass gears, Victorian machinery, copper pipes` |
| **废土末日** | 坍塌建筑、锈蚀金属、荒芜植被入侵 | 绝望、重生、荒凉 | `post-apocalyptic ruins, overgrown vegetation, rusted metal, decay` |
| **仙侠** | 云中宫殿、悬崖仙府、瀑布灵池 | 超凡、缥缈、修行 | `xianxia palace on clouds, floating mountains, waterfall, ethereal` |
| **哥特恐怖** | 尖塔、蜘蛛网、阴暗地下室、烛光 | 恐惧、死亡、腐朽 | `Gothic horror mansion, cobwebs, dim candlelight, decaying walls` |
| **太空科幻** | 金属舱壁、圆形走廊、真空窗外星空 | 孤寂、探索、未知 | `sci-fi spaceship interior, metal corridors, viewport, zero gravity` |

---

## 空间比例与情绪心理学

> 空间的尺度直接操控观众的身体感知——这是比色调、光影更底层的情绪工具。

### 天花板高度 × 情绪

| 高度 | 体感 | 情绪效果 | 适用情境 |
|------|------|---------|---------|
| < 2.4m | 低矮压迫 | 焦虑、窒息、私密 | 地下室、牢房、密室逃脱 |
| 2.4m~3m | 普通住宅感 | 日常、亲切、安全 | 家庭场景、办公室 |
| 3m~5m | 开阔商业感 | 正式、公共、疏离 | 大堂、画廊、教室 |
| 5m~10m | 挑高仪式感 | 崇敬、仪式、权力 | 教堂、法院、剧院 |
| > 10m | 穹顶巨构 | 渺小、敬畏、神圣 | 大教堂、宫殿、太空站 |

### 空间宽窄 × 情绪

| 空间类型 | 体感 | 情绪效果 | AI 关键词 |
|---------|------|---------|----------|
| 狭窄走廊 < 1.2m | 挤压 | 紧张、追逐、幽闭 | `narrow corridor, claustrophobic, tight space` |
| 标准通道 1.2m~2m | 中性 | 目的性、流动 | `hallway, passage` |
| 宽敞大厅 > 5m | 空旷 | 权力、孤独、自由 | `vast hall, grand space, expansive interior` |
| 无边际空间 | 失重 | 超现实、虚无、解放 | `infinite space, boundless, void` |

### 封闭度 × 情绪

| 封闭程度 | 情绪效果 | 典型场景 |
|---------|---------|---------||
| 全封闭（无窗） | 囚禁、安全、秘密 | 地牢、保险库、暗室 |
| 半封闭（小窗/门缝） | 窥视、渴望、外面的世界 | 监狱、阁楼、病房 |
| 半开放（大窗/阳台） | 连接、过渡、犹豫 | 公寓、办公室、咖啡馆 |
| 全开放（无墙） | 自由、暴露、不安全 | 屋顶、悬崖、废墟 |

---

## 材质 / 质感词汇表

> 材质描述是AI出图从「AI感」到「电影感」的关键分水岭。写实风格尤其依赖精确材质词。

### 硬质材料

| 材质 | 视觉特征 | 情绪倾向 | AI 提示词 |
|------|---------|---------|----------|
| 清水混凝土 | 模板印痕、冷灰、毛孔 | 粗粝、力量、工业 | `raw concrete, exposed concrete, board-formed texture` |
| 抛光大理石 | 高反光、纹理流动 | 奢华、冰冷、权力 | `polished marble, veined marble, reflective stone surface` |
| 风化石材 | 青苔、裂纹、侵蚀 | 时间、历史、衰败 | `weathered stone, moss-covered, eroded surface, ancient` |
| 红砖 | 温暖、粗糙、排列规律 | 工业温情、复古 | `exposed red brick wall, aged brick, mortar joints visible` |
| 钢铁 | 冷光泽、工字梁、焊接点 | 工业、力量、现代 | `steel beam, industrial metal, welded joints` |
| 锈蚀金属 | 橙褐色、斑驳、剥落 | 废弃、时间侵蚀、末日 | `rusted metal, corroded iron, patina, oxidized surface` |
| 铜/黄铜 | 温暖金属光泽、绿锈 | 古典奢华、蒸汽朋克 | `brass finish, copper patina, verdigris` |
| 玻璃 | 透明/半透、反射 | 现代、脆弱、监视 | `glass curtain wall, frosted glass, reflective surface` |
| 瓷砖 | 规整、光洁、缝隙 | 医疗、卫生、冷漠 | `ceramic tiles, subway tiles, glossy tile surface` |

### 软质 / 有机材料

| 材质 | 视觉特征 | 情绪倾向 | AI 提示词 |
|------|---------|---------|----------|
| 原木 | 年轮纹理、温暖、节疤 | 自然、质朴、温馨 | `natural wood grain, oak texture, exposed timber, knotted wood` |
| 老旧木板 | 开裂、褪色、虫蛀 | 废弃、怀旧、鬼屋 | `aged wood planks, cracked timber, weathered wooden floor` |
| 竹 | 节纹、翠绿/枯黄、密集 | 东方、禅意、生命力 | `bamboo structure, bamboo grove, warm bamboo interior` |
| 纸/障子 | 半透光、纤维纹理 | 脆弱、日式、私密 | `rice paper screen, translucent paper, shoji texture` |
| 织物/帘幕 | 垂坠、褶皱、飘动 | 柔软、隐蔽、戏剧 | `draped fabric, heavy curtain, velvet texture, billowing cloth` |
| 皮革 | 纹路、磨损、光泽 | 复古、权威、手工 | `aged leather, worn leather surface, cracked patina` |
| 植被/苔藓 | 绿色侵入、湿润 | 生命、遗忘、自然夺回 | `overgrown moss, ivy-covered wall, vegetation reclaiming` |

### 特殊效果材质

| 材质 | AI 提示词 | 适用风格 |
|------|----------|---------||
| 全息/透明屏 | `holographic display, transparent screen, HUD overlay` | 科幻 |
| 魔法发光纹路 | `glowing runes, magical inscriptions, ethereal glow` | 奇幻/仙侠 |
| 冰晶 | `ice crystals, frozen surface, frost patterns, translucent ice` | 冰雪场景 |
| 熔岩裂纹 | `lava cracks, molten glow between rocks, volcanic` | 火山/地狱 |
| 水面反射 | `water reflection, rippled surface, mirror-like water` | 诗意/梦境 |

---

## 室内场景设计规范

### 写实场景核心检查项

> 写实风格场景的说服力 = 细节密度 × 物理逻辑一致性。AI 生成最常暴露的破绽在于空间逻辑和物件合理性。

**必查清单：**
1. **光源合理性**：光从哪来？窗户位置与光照方向是否一致？
2. **比例一致性**：家具、人物、门窗之间的比例是否合理？
3. **磨损逻辑**：高频触碰区域（门把手、扶手）应有使用痕迹
4. **重力逻辑**：物体是否稳定地放置在平面上？布料是否自然垂坠？
5. **时代一致性**：电器、家具、装饰风格是否属于同一时代？
6. **生活痕迹**：杯子上的水渍、书桌上的文件——空间要有「住过人」的感觉

### 常用室内场景模板

| 场景类型 | 空间要素 | 情绪基调 | 材质关键词 |
|---------|---------|---------|----------|
| 老式公寓 | 窄长走廊、小窗、暖色灯泡 | 怀旧、温暖、局促 | 老旧木地板、斑驳墙纸、磨损门把 |
| 现代极简公寓 | 开放式、大落地窗、简约家具 | 疏离、精致、冷感 | 白墙、抛光混凝土、不锈钢、玻璃 |
| 中式老宅/四合院 | 院落围合、木构梁柱、对联 | 礼序、传承、衰败 | 灰砖、老木、红漆柱、砖雕 |
| 日式和室 | 榻榻米、低矮桌、障子门 | 宁静、侘寂、克制 | 竹席、纸门、原木、棉麻 |
| 废弃工厂 | 高挑空间、铁架、碎玻璃 | 荒废、暗力量、重生 | 锈蚀铁、碎混凝土、油渍地面 |
| 医院/实验室 | 白色瓷砖、日光灯、不锈钢 | 无菌、冷漠、控制 | 瓷砖、不锈钢、环氧地坪 |
| 酒吧/夜店 | 低照度、霓虹、镜面反射 | 暧昧、沉醉、地下 | 黑色皮革、镜面、霓虹管 |
| 图书馆/书房 | 高书架、暖色灯、木质台面 | 知性、安全、时间沉淀 | 深色木、皮革、旧纸、黄铜台灯 |

---

## 室外场景设计规范

### 自然环境

| 环境 | 关键视觉元素 | 情绪语言 | AI 提示词模板 |
|------|-----------|---------|-------------|
| 密林 | 树冠遮蔽、光斑、地面落叶 | 神秘、迷失、庇护 | `dense forest, dappled sunlight, leaf litter, canopy overhead` |
| 开阔草原 | 地平线低、天空主导、风吹草动 | 自由、孤独、辽阔 | `vast grassland, low horizon, windswept, endless sky` |
| 海岸/悬崖 | 岩石纹理、浪花飞溅、海天交界 | 壮阔、危险、边界 | `coastal cliff, crashing waves, sea spray, dramatic coastline` |
| 沙漠 | 沙丘曲线、烈日、热气蒸腾 | 极限、孤绝、净化 | `desert dunes, heat haze, harsh sunlight, barren landscape` |
| 雪地 | 白色主导、足迹、枯枝 | 纯洁、死寂、隐忍 | `snow-covered landscape, footprints, bare branches, cold silence` |
| 山峦 | 层叠轮廓、云雾穿插、缩小感 | 敬畏、渺小、超越 | `mountain range, layered peaks, clouds between mountains, vast scale` |
| 水面（湖/河） | 反射、涟漪、对称 | 内省、平静、映射 | `still lake surface, mirror reflection, gentle ripples` |

### 城市/人造环境

| 环境 | 关键视觉元素 | 情绪语言 | AI 提示词模板 |
|------|-----------|---------|-------------|
| 老城小巷 | 石板路、窄墙、晾衣绳 | 生活气、故事感、局促 | `narrow old town alley, cobblestone, laundry lines, weathered walls` |
| 现代CBD | 玻璃幕墙、仰拍线条、人流 | 速度、压力、匿名 | `modern cityscape, glass skyscrapers, upward angle, busy street` |
| 雨夜街头 | 湿地面反光、霓虹倒影、伞 | 浪漫、孤独、noir | `rainy night street, wet reflections, neon glow, umbrellas` |
| 施工现场 | 脚手架、塔吊、裸露结构 | 未完成、混乱、生长 | `construction site, scaffolding, crane, exposed structure` |
| 废弃游乐场 | 锈蚀旋转木马、褪色涂装 | 童年消逝、诡异 | `abandoned amusement park, rusted rides, faded paint, eerie` |
| 屋顶天台 | 城市全景、水箱、晾衣架 | 逃离、喘息、视野突变 | `rooftop, city panorama, water tanks, urban escape` |
| 地下通道 | 荧光灯、涂鸦、回声感 | 边缘、地下文化、危险 | `underground passage, fluorescent lights, graffiti, echo` |

---

## 空间动线与机位关系

> 场景不只是一张静态图，更是角色运动和镜头运动的舞台。设计时必须预判动线。

### 动线类型 × 叙事功能

| 动线类型 | 空间特征 | 叙事功能 | 镜头配合 |
|---------|---------|---------|---------||
| **直线型** | 走廊、桥、小路 | 目标明确的前进/追逐 | 跟拍、推轨、一点透视 |
| **环绕型** | 中庭、圆形广场 | 犹豫、仪式、对峙 | 环绕跟拍、360°运镜 |
| **迷宫型** | 老城、仓库群、森林 | 迷失、逃亡、探索 | 手持晃动、POV主观 |
| **垂直型** | 楼梯、电梯、悬崖 | 上升/坠落、权力高低 | 俯拍/仰拍、垂直推拉 |
| **停滞型** | 封闭房间、牢房 | 困境、对话、心理博弈 | 固定机位、缓慢推进 |

### 机位预设 × 空间关系

```
┌────────────────────────────────────────┐
│              全景建立镜头               │ ← 交代空间全貌
│  ┌──────────────────────────────────┐  │
│  │        中景叙事区域              │  │ ← 角色活动主区域
│  │  ┌──────────────────────────┐   │  │
│  │  │    特写情绪区域           │   │  │ ← 面部/手部/物件
│  │  └──────────────────────────┘   │  │
│  └──────────────────────────────────┘  │
│  ↑前景遮挡物                           │ ← 门框/窗框/人物肩部
└────────────────────────────────────────┘
```

**场景设计时必须回答三个问题：**
1. 全景镜头从**哪个角度**拍能最高效地建立空间感？
2. 角色的**主要活动区域**在空间的什么位置？
3. 有没有**天然的前景遮挡物**可以用？（门框、柱子、植物……）

---

## 构图法则：三层景深系统

> 来源：白梦客知识库 `wiki/美学配方/通用线/构图法则.md`
> 核心融合：胡金铨 × 北野武 × 李安

```
前景遮挡（70%权重） + 极简留白（50%权重） + 情绪元素点缀（30%权重）
```

### 前景遮挡（胡金铨美学，70%）

创造画面层次感，是AI生成中提升「电影感」的最有效手法。

| 参数 | 数值 |
|------|------|
| 遮挡比例 | 10%~35% 画面面积 |
| 虚化程度 | 30%~100% |
| 光圈等效 | f/1.4~f/3.5 |

**常用前景物体：**
- 自然：竹子、树枝、芦苇、荷叶、雾气
- 建筑：门框、窗框、屋檐、纱帘、灯笼
- 人物局部：肩部、后脑勺、侧脸轮廓
- 现代：玻璃、栏杆、霓虹招牌

**遮挡比例与效果：**

| 遮挡比例 | 效果 |
|---------|------|
| 10%~15% | 自然、干净、轻微框架感 |
| 20%~25% | 层次感、空间感、氛围 |
| 30%~35% | 压迫感、框架感、窥视感 |

**AI 提示词速查：**
```
# 标准前景遮挡
foreground [物体] obstruction, [比例]% frame coverage, shallow DOF

# 竹林场景
foreground bamboo stalks obstruction, 25% frame, shallow DOF

# 窥视感
double frame composition, foreground + doorway frame
```

### 极简留白（北野武美学，50%）

大面积负空间，「计白当黑」，留给观众情绪想象空间。

| 留白比例 | 情绪效果 |
|---------|---------|
| 40%~50% | 呼吸感、舒适、开放 |
| 50%~60% | 沉思、内省、安静 |
| 60%~70% | 孤独、疏离、仪式感 |
| 70%~80% | 极简、压迫、虚无 |

**AI 提示词速查：**
```
# 北野武风格
Beat Takeshi style, figure in vast space
negative space 70%, long static take

# 极简高定线
product 25% frame, negative space 70%
minimalist, black background, rim lighting
```

### 情绪元素点缀（李安，30%）

用单一细节物体传达大情绪。

| 技法 | 描述 |
|------|------|
| 微距细节 | 水滴、烟雾、尘埃、残留物 |
| 色彩点缀 | 小面积（5%~10%）高饱和度色彩 |
| 动态元素 | 飘动的物体、人物小动作 |

### 构图应用原则

1. **层次优先**：先建立前景-中景-背景三层
2. **留白克制**：宁多勿少，保持画面呼吸感
3. **情绪物体**：选择有象征意义的细节
4. **真实感检查**：前景材质是否真实自然？散景是否不规则？光影是否符合物理逻辑？

---

## 光影公式：场景情绪的核心参数

> 来源：白梦客知识库 `wiki/美学配方/通用线/光影公式.md`
> 核心配方：侧逆光+烟雾（70%）× 霓虹漫射（30%）
> 整体美学融合：胡金铨 × 王家卫

### 核心参数速查

```
侧逆光 45°~60° + 烟雾 30%~50% + 光比 2:1~4:1 + 负空间 50%~70%
```

### 侧逆光 + 烟雾（70%，胡金铨武侠禅意）

| 参数 | 数值 |
|------|------|
| 光源位置 | 侧后方 45°~90° |
| 光源高度 | 高于主体 15°~45° |
| 光比 | 2:1~4:1（标准） / 4:1~8:1（高对比戏剧感） |
| 烟雾浓度 | 薄雾 5%~10% / 中雾 10%~20% / 浓雾 20%~40% |

**场景方案示例：**

| 场景 | 光源位置 | 烟雾浓度 | 效果 |
|------|---------|---------|------|
| 竹林 | 侧后方 45° | 薄雾 | 禅意、光束穿透 |
| 旧客栈 | 侧后方 90° | 中雾 | 尘埃光束、复古 |
| 山崖 | 侧后方 45° | 薄雾 | 壮阔、孤独 |
| 旧仓库 | 破损窗口（高对比） | 尘埃 | 神秘、noir |
| 室内窗 | 侧后方 | 薄雾 | 阳光穿透、时光感 |
| 废弃剧场 | 穹顶破洞月光 | 中雾 | 孤独、神圣 |

**AI 提示词模板：**
```
side-backlighting, light from behind subject,
smoke scattering, volumetric light, god rays,
dust particles in light beam,
high contrast, dramatic shadows,
cinematic lighting, film noir influence,
mysterious atmosphere, zen aesthetic
```

### 霓虹漫射（30%，王家卫城市感）

| 霓虹类型 | 色温 | 适用场景 |
|---------|------|---------|
| 暖霓虹 | 2800K~3000K | 餐厅、酒吧、怀旧 |
| 冷霓虹 | 4000K~5000K | 办公、科技、都市疏离 |
| 粉霓虹 | — | 爱情、夜晚、浪漫 |
| 绿霓虹 | — | 赛博、神秘 |

**AI 提示词模板：**
```
neon light, diffused neon glow, soft edge lighting,
city night, neon reflections on wet pavement,
Wong Kar-wai aesthetic, cinematic neon,
color bleeding, soft shadows
```

### 混合光公式

**侧逆光 + 霓虹（城市夜景）：**
```
A figure in neon-lit alley, side-backlighting from street lamp,
smoke in the air, neon glow on face,
high contrast, cinematic, urban night,
Wong Kar-wai style, dramatic shadows
```

**自然光 + 烟雾（室内日光感）：**
```
Sunlight through dusty window, volumetric light,
smoke in light beams, side-backlit,
warm interior, contemplative mood,
cinematic, film grain, nostalgic atmosphere
```

---

## 七情与场景视觉参数速查

> 来源：白梦客知识库 `wiki/创作方法论/导演/情绪引导方法论.md`

**核心原则：情绪不是被"说"出来的，是被"引导"出来的。场景视觉语言直接在观众心里构建情绪。**

### 七情 × 场景导演参数

| 七情 | 色调 | 光影 | 构图 | 典型场景元素 |
|------|------|------|------|------------|
| **惧** | 冷蓝白 60% | 顶光 + 烟雾 | 走廊走不到头、四面墙围死 | 封闭走廊、低矮顶、无尽楼梯 |
| **怒** | 大地 + 红 10% | 侧逆高对比 | 两股力量即将碰撞 | 狭窄巷道、对立门窗 |
| **哀** | 大地 + 苍青 | 侧逆 + 自然光 | 消失点外、冷光边角 | 脚印消失处、拉上的窗帘 |
| **喜** | 琥珀 + 暖白 | 自然光过曝 | 打开的窗户、解放的框架 | 开阔草地、透光窗台 |
| **恶** | 大地灰 | 顶光 | 入侵物占据中心 | 腐败中心物、溢出液体 |
| **爱** | 琥珀 + 苍青 | 侧逆对比 | 裂纹、窗破、帘撕 | 暧昧边界光、反射水面 |
| **欲** | 黑白 + 冷白 | 单一强光源 | 手伸向画面外、永远差一点 | 悬空的手、逆光剪影 |

### 复合情绪场景

| 复合情绪 | 场景元素 | 适合漫剧情境 |
|---------|---------|------------|
| 遗憾 | 脚印消失 + 叠化回放 | 离别场景 |
| 愧疚 | 倾斜构图 + 静默 | 对峙/告白失败 |
| 释然 | 色调渐变暖 + 开放空间 | 成长弧线结局 |
| 心疼 | 边界消失 + 暖光 | 守护/救援场景 |

---

## 分镜结构：场景如何服务于叙事节奏

> 来源：白梦客知识库 `wiki/AI视频创作/Vidu/分镜生成系统.md` + `wiki/AI视频创作/Seedance/分镜模板.md`

### 1+3 叙事矩阵（非对话场景）

每个基础动作单元，生成 4 个分镜——从不同维度呈现同一场景：

| 镜头 | 功能 | 场景侧重 |
|------|------|---------|
| 镜头1 — 标准叙事镜 | 客观呈现事件 | 交代场景全貌，建立空间关系 |
| 镜头2 — 情感聚焦镜 | 角色内心/微表情 | 场景细节作为情绪锚点 |
| 镜头3 — 动态冲击镜 | 速度、力量、视觉冲击 | 场景的动态元素（雨、风、烟） |
| 镜头4 — 氛围意境镜 | 环境、光影与角色互动 | 场景的情绪语言（逆光剪影、雾气等） |

**示例（废弃剧场场景）：**
```
【核心场景绘画提示词】
@废弃剧场：（室内广角，建立镜头）
一座废弃的巴洛克风格大剧院，穹顶破了大洞，
雨水和月光从中洒落。舞台上空无一物，
只有厚重的红色幕布在穿堂风中微微飘动。

【分镜1 — 标准叙事镜】
在月光洒落的[@废弃剧场]舞台中央，[@角色名]缓缓张开双臂，
像是在拥抱整个空无一人的剧场。

【分镜4 — 氛围意境镜】
在深夜的[@废弃剧场]中，镜头从舞台后方逆光拍摄，
[@角色名]张开双臂的剪影被穹顶洒下的月光勾勒出来，
显得孤独而神圣。
```

### 九宫格分镜结构（15 秒片段）

每组 9 个分镜 = 1 个 15 秒片段，场景功能对应结构位置：

```
┌──────────────┬──────────────┬──────────────┐
│ 1-开场（场景） │ 2-环境（气氛） │ 3-情绪（角色） │  ← 铺垫（0~5s）
├──────────────┼──────────────┼──────────────┤
│ 4-转折（冲突） │ 5-高潮（核心） │ 6-爆发（动作） │  ← 核心（5~10s）
├──────────────┼──────────────┼──────────────┤
│ 7-回落（余韵） │ 8-情感（细节） │ 9-定格（余韵） │  ← 收尾（10~15s）
└──────────────┴──────────────┴──────────────┘
```

**场景镜头在九宫格中的位置：**
- `分镜1` = 场景建立镜头（广角/全景）
- `分镜2` = 环境气氛镜头（光影/色调呈现）
- `分镜4/5` = 场景与角色动作的核心互动
- `分镜9` = 场景的情绪收尾（常用：远景拉远 / 环境特写定格）

---

## 导演风格 × 场景美学速查

> 来源：白梦客知识库 `wiki/创作方法论/导演/情绪引导方法论.md`

| 导演风格 | 场景构图核心 | 光影参数 | AI 风格词 |
|---------|-----------|---------|----------|
| **胡金铨** | 前景遮挡 30% + 深景深背景 | 侧逆光 45°~60°，烟雾 30%~50% | `King Hu aesthetic, bamboo, volumetric light` |
| **王家卫** | 残缺构图，只拍局部 | 大面积黑暗 + 小块霓虹光 | `Wong Kar-wai style, neon glow, fragmented` |
| **北野武** | 宽阔比例，人物占比小 | 自然光，阴天柔光，高对比 | `Beat Takeshi style, vast empty space` |
| **李安** | 情绪物件点缀 | 自然侧逆光，叙事结合 | `Ang Lee style, emotional detail, soft natural light` |
| **塔可夫斯基** | 长镜头静水面，时间感 | 慢移动光源 + 薄雾 | `Tarkovsky aesthetic, slow burn, water surface` |

---

## 类型片场景视觉参考

| 类型 | 场景特征 | 光影推荐 | 色调 |
|------|---------|---------|------|
| 古装/武侠 | 服装考究、场景宏大（竹林/客栈/山崖） | 侧逆光 + 薄雾 | 大地色 + 琥珀 |
| 现代都市 | 场景真实、霓虹街头、咖啡馆 | 霓虹漫射 + 雨面反光 | 苍青 + 暖霓虹 |
| 科幻赛博 | 场景前卫、金属感、冷峻 | 单一强光 + 粒子 | 冷蓝 + 霓虹绿 |
| 奇幻异世界 | 场景梦幻、自然奇景 | 自然光过曝 + 体积光 | 饱和高对比 |
| 末日废土 | 荒废建筑、破烂质感 | 高对比顶光 + 浓雾 | 大地灰 + 消色 |

---

## 场景设计工作流

```mermaid
graph TD
    A[确定故事世界观] --> B[列出核心场景清单]
    B --> C[为每个场景写200字场景描述]
    C --> D[确定场景情绪功能\n对应七情参数]
    D --> E[套用光影公式\n侧逆光/霓虹/混合]
    E --> F[套用构图法则\n前景遮挡/留白比例]
    F --> G[生成场景板文生图描述词]
    G --> H[出图验证场景氛围]
    H --> I{氛围正确？}
    I -- 否 --> E
    I -- 是 --> J[锁定@场景名标签]
    J --> K[与角色/道具板整合\n生成分镜序列]
```

---

## 场景板输出模板

```markdown
## 场景板

| 场景名 | 出场集数 | 场景描述 | 文生图描述词 |
|--------|---------|---------|------------|
| @废弃剧场 | 第1集 | 一座废弃的巴洛克风格大剧院，穹顶破损，
雨水和月光从中洒落。舞台空无一物，
红色幕布在穿堂风中微动。
整体氛围：孤独、神圣、衰败的仪式感。 | abandoned baroque theater interior, broken dome ceiling,
moonlight and rain falling through the gap,
empty stage with heavy red curtains in the wind,
side-backlighting from moonlight above, misty atmosphere,
volumetric light beams, dramatic shadows,
melancholic and sacred mood, cinematic,
King Hu aesthetic, 2.35:1 aspect ratio |
```

---

## 速查：场景设计关键决策点

| 决策 | 推荐做法 |
|------|---------|
| 场景需要传达什么情绪？ | 先定七情，再选光影/构图参数 |
| 光影选哪种？ | 70% 侧逆光+烟雾；城市夜景加 30% 霓虹漫射 |
| 构图层次怎么建立？ | 前景遮挡（胡金铨）+ 极简留白（北野武）+ 情绪细节（李安）|
| 场景描述给 AI 多少字？ | 文生图描述词 150 字以上，含：光影/色调/风格/情感关键词 |
| 场景在分镜中如何引用？ | 用 `@场景名` 标签，禁止代词，保持原子化 |
| 如何防止场景 AI 输出随机性？ | 先出场景板设定图，锁定后作为参考图输入 |
| 场景只要一张正面图吗？ | 不够，需四镜（标准/情感/动态/氛围）覆盖不同叙事需求 |
| 场景和角色如何配合？ | 场景色彩应与角色色块形成对比/互补，避免视觉相融 |
