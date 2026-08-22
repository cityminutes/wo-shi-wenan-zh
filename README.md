# AI 品牌敘事｜我是文案策略與故事創作 Skill

一個把品牌訪談、策略提煉與風格化寫作整合成完整工作坊的繁體中文 Codex Skill。

它不從空白頁直接生成幾句漂亮文案，而是先找出品牌真正值得被記住的核心，再建立可延伸到命名、標語、故事與未來內容的敘事系統。

## 核心方法

```text
品牌訪談 → 核心隱喻 → 風格權重 → 五部分敘事系統 → 延伸內容
```

Skill 會逐步釐清品牌／專案、具體特色、目標受眾、溝通挑戰與風格偏好。使用者可從 18 種風格中選擇 2–4 種，並指定一種主導風格；其餘風格只作為有層次的輔助。

## 產出內容

1. 三個核心概念隱喻與最強方向
2. 品牌命名意涵
3. Slogan、理念 Tagline 與社群 Hashtag
4. 約 300 字品牌故事
5. 敘事支點、推薦詞彙庫與禁用詞彙庫

## 六項創作原則

- 情感定錨
- 核心隱喻驅動
- 感性血肉與理性骨架並存
- 精準語言優先
- 不靠引號替抽象概念壯膽
- 主導／輔助風格的層次化融合

交付前還會檢查過度解釋的對比句、抽象引號、無證據主張與風格混濁，只輸出完成重寫後的乾淨版本。

## 適用情境

- 新品牌的核心敘事與語調建立
- 建案、精品、文化策展與公共品牌文案
- 品牌命名概念與 Slogan 發展
- 將零散產品特色轉化為可延伸的創意主軸
- 為社群、EDM 與網站建立一致的內容母體

## 安裝

```bash
git clone https://github.com/cityminutes/ai-brand-storytelling-zh.git ~/.codex/skills/ai-brand-storytelling-zh
```

在 Codex 中輸入：

```text
使用 $ai-brand-storytelling-zh 訪談我，並為這個品牌建立核心敘事系統。
```

如果已有完整 brief，也可以直接貼上。Skill 會整理已知資訊，只追問真正缺少的策略條件。

## Repository 結構

```text
ai-brand-storytelling-zh/
├── SKILL.md
├── README.md
├── agents/openai.yaml
└── references/
    ├── styles.md
    └── exemplars.md
```

英文版：[AI Brand Storytelling](https://github.com/cityminutes/ai-brand-storytelling-en)
