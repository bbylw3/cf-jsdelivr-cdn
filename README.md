# Cloudflare jsDelivr CDN
# Cloudflare jsDelivr 私有 CDN

This repository provides **two deployment modes** for building a private,
up-to-date CDN based on jsDelivr using Cloudflare’s edge network.

本仓库提供 **两种部署方案**，用于基于 Cloudflare 构建私有、可控、
且始终保持最新的 jsDelivr CDN。

---

## Available Modes | 可用方案

### 1. Cloudflare Workers (Recommended)
- Full control
- Wrangler-based deployment
- Best for production use

### 2. Cloudflare Pages
- Zero configuration
- No Wrangler required
- GitHub → Pages → Done

---

## Usage | 使用方式

Replace jsDelivr URLs:

```html
https://cdn.jsdelivr.net/npm/package@version/file
