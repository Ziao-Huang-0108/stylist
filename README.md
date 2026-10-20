# STYLIST

AI 个人造型师网站 MVP / An AI personal stylist web MVP.

填风格与预算，生成可购买穿搭，用无脸模特在试衣间试看。  
Fill in style & budget → get shoppable outfits → try them on a faceless model.

视觉：Frutiger Metro 时装小游戏封面感。  
Visual: Frutiger Metro, fashion mini-game cover vibe.

## Features / 功能

- 封面 + 背景音乐 / Cover page + background music  
- 造型台：偏好、预算、模特档案 / Style desk: prefs, budget, model profiles  
- 试衣间：换一套、并排、详情、空白模特拼装 / Fitting room: swap, lineup, details, blank model  
- 本地持久化 / Browser localStorage  
- 无 API Key 时用 mock 商品兜底 / Mock catalog fallback without API key  

## Stack / 技术栈

Next.js 15 · React 19 · TypeScript · Tailwind v4 · Framer Motion · Zod · OpenAI（optional）

## Setup / 启动

```bash
npm install
cp .env.example .env.local
npm run dev
```

Open http://localhost:3000

| Env | Note |
|---|---|
| `OPENAI_API_KEY` | Optional / 可选 |
| `OPENAI_MODEL` | Default `gpt-4o-mini` |
| `PRODUCT_SEARCH_PROVIDER` | `mock` |

## Pages / 页面

`/` cover · `/create` style desk · `/showroom` fitting room

## Not in MVP / 未包含

Real commerce APIs · wardrobe upload · accounts · illustrated model upgrade  
真实电商 · 衣橱上传 · 账号 · 立绘升级
