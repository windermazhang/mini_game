# 游戏6：加减法小能手 - AI图片生成提示词

## 📋 图片规格要求

### 🎯 基础规格
- **分辨率**：512x512px（标准）/ 1024x1024px（高清）
- **格式**：PNG（推荐，支持透明背景）/ WEBP（体积更小）
- **色彩模式**：RGB，色彩深度24位
- **压缩**：无损压缩，保持细节清晰

### 📱 移动端优化
- **最小尺寸**：256x256px（保证清晰度）
- **最大文件大小**：单张不超过500KB
- **响应式**：支持2x、3x像素密度
- **加载优化**：webp格式优先，png作为后备

### 📁 目录结构
```
games/game6/images/
├── heroes/
│   ├── math-hero-main.png (100x100px) - 主角数学英雄
│   ├── hero-victory.png (100x100px) - 胜利状态
│   └── hero-thinking.png (100x100px) - 思考状态
├── operations/
│   ├── plus-icon.png (50x50px) - 加法图标
│   ├── minus-icon.png (50x50px) - 减法图标
│   └── equals-icon.png (50x50px) - 等号图标
├── achievements/
│   ├── badge-rookie.png (80x80px) - 新手徽章
│   ├── badge-calculator.png (80x80px) - 计算器徽章
│   ├── badge-genius.png (80x80px) - 天才徽章
│   ├── badge-master.png (80x80px) - 大师徽章
│   ├── badge-legend.png (80x80px) - 传奇徽章
│   └── badge-ultimate.png (80x80px) - 终极徽章
├── ui/
│   ├── level-bg.png (300x100px) - 关卡背景
│   ├── button-bg.png (60x60px) - 按钮背景
│   ├── star-effect.png (40x40px) - 星星特效
│   └── lightning-effect.png (60x30px) - 闪电特效
├── backgrounds/
│   ├── superhero-city.jpg (360x640px) - 超级英雄城市
│   └── math-dimension.png (360x640px) - 数学维度
└── decorations/
    ├── number-particles.png (200x200px) - 数字粒子
    ├── formula-trail.png (300x100px) - 公式轨迹
    └── energy-burst.png (150x150px) - 能量爆发
```

### 🎨 HTML中的使用方法
```html
<!-- 在HTML的<head>中添加图片预加载 -->
<link rel="preload" as="image" href="./images/heroes/math-hero-main.png">
<link rel="preload" as="image" href="./images/operations/plus-icon.png">

<!-- 在CSS中使用背景图片 -->
.math-hero {
    background-image: url('./images/heroes/math-hero-main.png');
    background-size: cover;
    background-position: center;
}

<!-- 动态切换图片状态 -->
.hero-character.victory {
    background-image: url('./images/heroes/hero-victory.png');
}

<!-- 在HTML中使用<img>标签 -->
<img src="./images/achievements/badge-rookie.png" alt="新手徽章" class="achievement-badge">
```

## 🎯 游戏主题
**加减法小能手** - 培养0-10加减法混合运算能力，成为数学英雄的训练营

## 🎨 设计风格指导原则
- **主色调**：英雄红橙（#ff6b6b）、胜利金黄（#ffd93d）、活力蓝绿（#4ecdc4）
- **辅助色**：天空蓝（#74b9ff）、薄荷绿（#a8e6cf）、粉红渐变（#fed6e3）
- **风格定位**：超级英雄主题 + 儿童友好 + 现代扁平化设计
- **情感基调**：自信、勇敢、挑战、成就感

## 📱 移动端适配要求
- **尺寸比例**：9:16 竖屏优先，适配横屏模式
- **元素大小**：按钮最小44px，文字最小12px
- **色彩对比**：确保4.5:1对比度，适合儿童视觉
- **触摸友好**：圆角设计，明确的点击区域

---

## 🦸 主角英雄形象系列

### 1. 数学超级英雄（主角）
**中文描述**：数学超级英雄，身穿红橙色渐变斗篷，胸前有金黄色加减号徽章，充满自信的表情，举起拳头做胜利手势，卡通风格，儿童友好设计，明亮的色彩，3D立体效果

**English Prompt**：
```
Cartoon math superhero character, wearing red-orange gradient cape, golden plus-minus symbol badge on chest, confident expression, fist raised in victory pose, child-friendly design, bright vibrant colors, 3D render style, superhero theme, educational game character
```

### 2. 思考中的英雄
**中文描述**：数学英雄思考表情，手托下巴，眼睛闪闪发光有小星星，周围飘浮着数字和运算符号，温暖的金黄色光晕环绕，智慧形象，卡通风格

**English Prompt**：
```
Cartoon math hero in thinking pose, hand on chin, sparkling eyes with small stars, floating numbers and math symbols around, warm golden aura, wisdom representation, child-friendly cartoon style, educational theme
```

### 3. 庆祝胜利的英雄
**中文描述**：超级英雄双手高举庆祝，周围爆发彩色烟花和星星，表情非常开心，斗篷在风中飘扬，背景有彩虹渐变，胜利主题，动感十足

**English Prompt**：
```
Superhero celebrating with both hands raised high, colorful fireworks and stars exploding around, very happy expression, cape flowing in wind, rainbow gradient background, victory theme, dynamic action pose, cartoon style
```

---

## 🎮 游戏元素素材系列

### 4. 加法运算图标
**中文描述**：立体加号图标，金黄色渐变材质，周围有发光效果，现代扁平化设计，适合移动端显示，清晰的轮廓，儿童友好

**English Prompt**：
```
3D plus sign icon, golden gradient material, glowing effect around edges, modern flat design, mobile-friendly display, clear outline, child-friendly design, educational symbol, vibrant colors
```

### 5. 减法运算图标
**中文描述**：立体减号图标，橙红色渐变，发光边缘效果，与加号配套设计，现代简约风格，适合儿童教育游戏

**English Prompt**：
```
3D minus sign icon, orange-red gradient, glowing edge effects, matching design with plus sign, modern minimalist style, suitable for children's educational games, clear symbol
```

### 6. 等号运算图标
**中文描述**：立体等号图标，蓝绿色渐变，发光效果，与其他运算符号形成统一设计语言，清晰易识别

**English Prompt**：
```
3D equals sign icon, blue-green gradient, glowing effects, unified design language with other math symbols, clear and recognizable, educational icon design
```

---

## 🏆 成就奖励系列

### 7. 胜利奖杯
**中文描述**：金色奖杯，顶部有数学英雄徽章，底座刻有"加减法小能手"字样，周围有光芒四射效果，立体渲染，庆祝主题

**English Prompt**：
```
Golden trophy with math hero badge on top, base engraved with achievement text, radiating light beams around, 3D render, celebration theme, victory symbol, educational achievement
```

### 8. 连胜徽章
**中文描述**：圆形徽章设计，中央是火焰图案，周围环绕数字，红橙色渐变背景，金边装饰，表示连续答对的成就

**English Prompt**：
```
Circular badge design, flame pattern in center, numbers surrounding, red-orange gradient background, golden border decoration, representing consecutive correct answers achievement
```

### 9. 速度闪电徽章
**中文描述**：闪电形状徽章，明亮的黄色和白色，表示快速答题，动感效果，适合儿童喜好的设计

**English Prompt**：
```
Lightning bolt shaped badge, bright yellow and white colors, representing fast answering, dynamic effects, child-appealing design, speed achievement symbol
```

---

## 🌟 UI界面元素系列

### 10. 游戏按钮设计
**中文描述**：圆角矩形按钮，渐变色彩（薄荷绿到粉红色），柔和阴影效果，适合触摸操作，现代扁平化风格

**English Prompt**：
```
Rounded rectangle button, gradient colors from mint green to pink, soft shadow effects, touch-friendly design, modern flat style, mobile UI element, child-friendly interface
```

### 11. 进度条设计
**中文描述**：胶囊形状进度条，彩虹渐变填充色，未填充部分为半透明白色，有光泽效果，现代UI设计

**English Prompt**：
```
Capsule-shaped progress bar, rainbow gradient fill color, unfilled part in semi-transparent white, glossy effects, modern UI design, colorful and engaging
```

### 12. 数字显示框
**中文描述**：数字显示用的圆角方框，金黄色边框，白色半透明背景，内部可显示大号数字，清晰易读

**English Prompt**：
```
Rounded square frame for number display, golden border, white semi-transparent background, designed for large numbers, clear and readable, educational UI element
```

---

## 🎊 特效装饰系列

### 13. 庆祝烟花
**中文描述**：彩色烟花爆炸效果，多种颜色的星星和圆点散开，适合答对题目时的庆祝动画，欢快氛围

**English Prompt**：
```
Colorful fireworks explosion effect, various colored stars and dots spreading out, suitable for correct answer celebrations, joyful atmosphere, particle effects
```

### 14. 星星光粒子
**中文描述**：小星星粒子效果，金黄色和白色，闪闪发光，适合背景装饰和成功反馈，童话般的效果

**English Prompt**：
```
Small star particle effects, golden and white colors, sparkling and glowing, suitable for background decoration and success feedback, fairy-tale like effects
```

### 15. 彩虹背景元素
**中文描述**：柔和的彩虹弧形，半透明效果，作为背景装饰元素，营造积极正面的学习氛围

**English Prompt**：
```
Soft rainbow arc shapes, semi-transparent effects, background decoration elements, creating positive learning atmosphere, colorful and gentle design
```

---

## 🎨 色彩搭配建议

### 主色彩组合
```css
/* 英雄红橙渐变 */
background: linear-gradient(45deg, #ff6b6b, #ffd93d);

/* 活力蓝绿渐变 */
background: linear-gradient(45deg, #4ecdc4, #44a08d);

/* 天空蓝渐变 */
background: linear-gradient(45deg, #74b9ff, #0984e3);

/* 薄荷粉渐变 */
background: linear-gradient(45deg, #a8edea, #fed6e3);

/* 胜利紫渐变 */
background: linear-gradient(135deg, #667eea, #764ba2);
```

### 文字色彩
- **主标题**：#4a154b（深紫色）
- **副标题**：#8b4513（棕色）
- **按钮文字**：#ffffff（白色）
- **提示文字**：#666666（深灰色）

## 📱 移动端特殊要求

### 触摸优化
- 所有交互元素最小44px×44px
- 按钮间距最少8px
- 圆角半径8-15px增加亲和力

### 视觉层次
- 主要元素使用高对比度
- 次要元素适当降低透明度
- 重要信息使用暖色系突出

### 动画效果建议
- 按钮点击：缩放0.95倍回弹
- 成功反馈：粒子爆炸+震动
- 错误反馈：左右摇摆
- 过渡动画：0.3秒缓动

## 🎯 使用指南

### 图片尺寸建议
- **角色图标**：512×512px（高分辨率）
- **UI元素**：256×256px或128×128px
- **背景元素**：1024×1024px
- **特效素材**：256×256px（支持透明背景）

### 文件格式
- **PNG**：支持透明背景的UI元素
- **SVG**：可缩放的图标和符号
- **JPG**：不需要透明的背景图片

### 生成平台推荐
1. **BoardMix AI**（中文界面，适合批量生成）
2. **Fotor AI**（高质量，适合精细调整）
3. **Stable Diffusion Online**（免费，适合实验）

每个提示词都已针对儿童教育游戏优化，确保生成的图片既有趣又具有教育价值！ 🎮✨ 