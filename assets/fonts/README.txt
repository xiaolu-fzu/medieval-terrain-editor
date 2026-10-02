像素字体（编辑器 UI 文字用）
========================================

1) PressStart2P.ttf      英文/数字 · 8px 原生 · 115KB
   出处: google/fonts (ofl/pressstart2p)
   授权: SIL Open Font License 1.1

2) zpix.woff2            中文 · 12px 原生 · 944KB
   出处: SolidZORO/zpix-pixel-font v3.3.0 (最像素 Zpix)
   授权: SIL Open Font License 1.1

3) ark-pixel-10px-zh.woff2  中文 · 10px 原生 · 80KB (zh_hans 子集)
   出处: TakWolf/ark-pixel-font 2026.09.25 (方舟像素字体)
   授权: SIL Open Font License 1.1

渲染方式: 先在离屏画布按字体原生尺寸排版, 再按整数倍最近邻放大
          => 任意字号都保持硬边像素颗粒感, 中文英文都不糊
编辑器里的字体选项:
  0 = 中英混排 (英文走 Press Start 2P, 中文自动走 Zpix)  ← 默认推荐
  1 = 只中文 Zpix
  2 = 只中文 方舟像素 10px
  3 = 只英文 Press Start 2P
