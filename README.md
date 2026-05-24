# TCB Components

Animated HTML components cho Techcombank presentations.
Built with Techcombank brand tokens · `Be Vietnam Pro` · zero dependencies.

**Live:** https://[your-username].github.io/tcb-components

---

## Xem nhanh

Mở `index.html` — full showcase 9 components, scroll-triggered, có nút Replay.

## Cấu trúc

```
tcb-components/
├── index.html          ← showcase tất cả 9 components
├── LIBRARY.md          ← annotation: component nào dùng slide nào
├── README.md
└── components/
    ├── 01-stat-counter.html
    ├── 02-progress-bars.html
    ├── 03-staggered-cards.html
    ├── 04-typewriter.html
    ├── 05-timeline.html
    ├── 06-donut-chart.html
    ├── 07-bar-chart.html
    ├── 08-toast-notifications.html
    └── 09-shimmer-reveal.html
```

## Thêm component mới

Nói với Claude: *"Thêm component mới: [mô tả]"*
Claude sẽ tạo file trong `components/`, cập nhật `index.html` và `LIBRARY.md`.

## Brand tokens

```css
--tcb-red:   #ed1b24   /* CTA, accent */
--tcb-navy:  #1b1564   /* authority */
--tcb-gold:  #d6b973   /* premium */
--tcb-bg:    #f5f6f8   /* page background */
--tcb-card:  #ffffff   /* card surface */
```
