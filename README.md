# U寶 Codex Pet

以 UCCU Hacker logo 為靈感製作的台灣黑熊 Codex 桌面寵物，保留招牌大眼睛與胸前白色 V 字。

## 安裝

在 Terminal 執行：

```bash
mkdir -p "$HOME/.codex/pets"
git clone https://github.com/uccuhacker/UCCU-Codex-Pet.git \
  "$HOME/.codex/pets/hei-bao-taiwan-black-bear"
```

重新啟動 Codex，接著選擇「U寶」即可。

## 更新

```bash
git -C "$HOME/.codex/pets/hei-bao-taiwan-black-bear" pull
```

## 檔案

```text
hei-bao-taiwan-black-bear/
├── pet.json
└── spritesheet.webp
```

這隻寵物使用 `spriteVersionNumber: 2`，spritesheet 尺寸為 `1536 × 2288`。
