# 平衡科學玩具世界 Balance Toys

學思創客 XUESI MAKER 的雷切平衡玩具：老鷹平衡鳥、鵜鶘平衡鳥、國際太空站平衡玩具。

## 網頁

| 頁面 | 檔案 |
|---|---|
| 首頁 | `index.html` |
| 老鷹平衡鳥 第一款 8 步組裝圖 | `eagle/assembly.html` |
| 老鷹平衡鳥 第二款（展翅＋爪子）組裝圖 | `eagle/assembly2.html` |
| 老鷹抓獵物（第二款 V2_3，換獵物重心實驗） | `eagle/assembly3.html` |
| 老鷹 AR 平衡挑戰＋與作品合照（繞著我飛，可選第一款或抓魚的老鷹；`?eagle=prey` 直接開抓魚款；🎨 掃描彩繪身體貼到 3D 老鷹，範例照片在 `eagle/ar_samples/`） | `eagle/ar.html` |
| 鵜鶘平衡實驗室 | `pelican/lab.html` |
| 太空站平衡實驗室 | `iss/lab.html` |

每個頁面都是單一 HTML 檔，Three.js 從 cdnjs 載入；AR 頁的手指辨識（MediaPipe Hands）從 jsDelivr 載入，在使用者裝置上執行，畫面不會上傳。

## AR 浮水印

- 預設浮水印是「學思創客」。網址加 `?brand=zz` 是中正創客，`?brand=zzm` 是中正MAKER。
- 首頁 AR 區塊的「QR 浮水印版本」選單會跟著換 QR，擺攤時選中正創客再截圖列印。
- 在 AR 頁「與作品合照」的浮水印選單選過後，同一支手機會記住。

## 雷切檔

- `pelican/files/`：鵜鶘 v1.1（SVG、DXF、A3 紙板原型）
- `iss/files/`：太空站 v7（SVG、DXF、A3 紙板原型）
- 3 mm 夾板，插槽 2.7 mm（切縫約 0.3 mm）；紅線切割、藍線雕刻。

## 授權

CC BY-NC-SA 4.0（姓名標示—非商業性—相同方式分享）。設計與教材：何政學。
https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh-hant


## 發表紀錄
- 2026-04-26：老鷹平衡鳥（可轉動羽毛配重）於土城區母親節嘉年華中正國中攤位首次公開展示（自由時報報導）。
- 2026-10-30：老鷹第二款「老鷹抓獵物」V2_4 雷切檔以 CC BY-NC-SA 4.0 公開（`eagle/files/`）。
