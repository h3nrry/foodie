# foodie 🍜

A running collection of food & drink recommendations, organized by country — compiled from local food blogs rather than personal reviews. Think of it as a curated "best of the blogs" index: each entry links back to the original post it came from, so you can dig into photos, prices, and full write-ups.

一份依國家整理的美食與飲品推薦清單，內容彙整自各地美食部落格（非個人實測心得）。每個項目都附上原始文章連結，方便查閱照片、價位與完整介紹。

## How this works / 使用說明

- The hierarchy is: **Country → City / County → District (or township) → Area**. Each level has its own `<name>_food.md` guide file that links down to the next level; area files list the actual spots (category, address, phone, source).
  階層架構為：**國家 → 直轄市／縣市 → 行政區（或鄉鎮） → 區域**。每一層皆有獨立的 `<名稱>_food.md` 導覽檔案，向下連結至下一層；區域檔案內列出實際店家（分類、地址、電話、來源）。
- Within a country, cities (with real administrative districts) and counties (whose townships act as the "district" level) are separate, sibling entities — see the Taiwan guide for how Hsinchu City and Hsinchu County are split.
  同一國家內，市（有下轄行政區）與縣（鄉鎮扮演「行政區」角色）為並列的獨立項目 — 詳見台灣指南中新竹市與新竹縣的區分方式。
- Every entry cites the blog(s) it was pulled from. Recommendations are aggregated opinions of third-party writers, not first-hand verification — hours, prices, and whether a place still exists can change, so double-check before you go (and book ahead for reservation-only spots).
  每筆資料皆標註來源部落格，為第三方作者的彙整意見，非親自查證；營業時間、價位與店家是否仍營業可能異動，出發前請自行確認（需預約的店家請提前預訂）。

## Countries / 國家

| Country | Guide | Coverage |
|---|---|---|
| Taiwan 台灣 | [`taiwan/taiwan_food.md`](./taiwan/taiwan_food.md) | Hsinchu City 新竹市 + Hsinchu County 新竹縣 (90 spots) |

More countries will be added here as guides are built out.
未來將持續新增其他國家的美食導覽。

## Contributing / 貢獻方式

To add a country, create a `<country>/<country>_food.md` top index. Under it, add one folder per city or county, each with its own `<name>_food.md`. If that city/county has real administrative districts, add `<name>/<district-slug>.md` per district linking to `<name>/<district-slug>/<area-slug>.md` files (see `taiwan/hsinchu/`). If it doesn't, link `<name>_food.md` straight to `<name>/<area-slug>.md` files (see `taiwan/hsinchu-county/zhubei/`, etc.). Cite the source blog post for every recommendation.

新增國家時，請建立 `<國家>/<國家>_food.md` 作為首頁。其下依市／縣分別建立資料夾，各自附上 `<名稱>_food.md`。若該市／縣確實有下轄行政區，請依 `taiwan/hsinchu/` 的架構建立每個行政區的 `<名稱>/<行政區>.md`，再連結至 `<名稱>/<行政區>/<區域>.md`；若沒有下轄行政區，則直接從 `<名稱>_food.md` 連結至 `<名稱>/<區域>.md`（參考 `taiwan/hsinchu-county/zhubei/` 等）。每筆推薦請標註來源部落格文章。

---

© 2026 Henrry Andrian‍​‌​​‌​​​​‌‌​​‌​‌​‌‌​‌‌‌​​‌‌‌​​‌​​‌‌‌​​‌​​‌‌‌‌​​‌​‌​​​​​‌​‌‌​‌‌‌​​‌‌​​‌​​​‌‌‌​​‌​​‌‌​‌​​‌​‌‌​​​​‌​‌‌​‌‌‌​​​‌‌​​‌​​​‌‌​​​​​​‌‌​​‌​​​‌‌​‌‌​‍. All rights reserved.
