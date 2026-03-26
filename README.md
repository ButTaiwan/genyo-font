![源樣明體/源様明朝](https://buttaiwan.github.io/font/pics/genyo.png)

# 源樣明體 & 源起明體 | 源様明朝 & 源起明朝 | GenYo Serif & Genki Serif

[繁體中文](#繁體中文) | [日本語](#日本語) | [English](#english)

---

## 繁體中文

「源樣明體」系列是基於思源宋體 (Source Han Serif) 的開放原始碼中文字型。本專案透過自動化程式調整，使其更接近傳統印刷體的審美風格。在 Ver 2.000 中，正式新增了「源起明體」系列——針對「TW (月版)」因部件來源不一導致的楷化轉折不協調進行了斷筆處理，視覺更趨一致。本系列亦是後續「源流」、「源雲」等字型的開發基礎。

### 🌟 Ver 2.0 / 2.1 更新核心

* **雙系列並行**：
    * **源樣明體 (GenYo)**：維持思源原有造形。
    * **源起明體 (Genki)**：針對「月」系列中因部件來源不一導致的楷化轉折不協調，進行程式化斷筆處理，視覺更趨一致。後續的源流、源雲等字型皆是以源起為基礎衍生。
* **中文版本分化：TW vs. TC**
    * 🌙 **TW (月版)**：採用台灣近年多數字型習慣的通俗寫法（例如「者」無點），適合現代文書與簡報。
    * 🔴 **TC (丹版)**：傳承傳統鉛字印刷體風格，保留古雅的字形特徵，適合書籍排版與經典設計。
* **字集大幅擴充**：
    * 底本全面升級至 **思源宋體 V2.0**。
    * 針對 **台客語漢字** 擴充支援至 CJK Extension H 範圍。
    * 收錄 **HKSCS 2021** 增補字符集與 **jf7000 當務字集** v0.9。
* **本土語言支援**：完整支援台羅、客語、原住民族語拼音，新增 **白話字 (POJ) 大寫 ᴺ**。
* **標點符號優化**：
    * **標點回歸全形**：修正了 1.5 版括號過窄的問題，恢復全形樣式。
    * **特定符號比例寬**：針對 `‘’“”` 採用比例寬版本，確保如 `It’s` 的英文排列正常。

---

## 日本語

「源様明朝」および「源起明朝」は、Adobe の「源ノ明朝 (Source Han Serif)」をベースに開発された、伝統的な活字スタイルを目指したフリーフォントです。Ver 2.000 では、TW 版などで見られたエレメントの不整合を解消するため、プログラムによる断筆処理を施した「源起明朝」シリーズを追加しました。本シリーズは、後に続く「源流明朝」や「源雲明朝」の開発ベースとなっています。

### 🌟 Ver 2.0 / 2.1 の主な変更点

* **二つのシリーズ**：
    * **源様明朝 (GenYo)**：元の造形を維持したデザイン。
    * **源起明朝 (Genki)**：TW/TC版におけるエレメントの不整合を解消するため、プログラムによる断筆処理を施した新シリーズ。
* **用途に応じた使い分け：JP vs. PJP**
    * **JP (等幅)**：テキスト入力や標準的な文書作成に適した固定幅バージョン。
    * **PJP (プロポーション)**：かな・記号を比例幅（プロポーション）に設定。映像の字幕やデザインに最適です。
* **多言語対応の強化**：
    * 韓国語 **KS X 1001** 範囲内のハングル（2350字）と IME 用字母を追加。
    * 縦組み時のダッシュの配置問題を解決。
* **技術的な改善**：Word や Illustrator での行間・バウンディングボックスの問題を改善し、オフィスソフト等の「B」ボタンで正しく太字が適用されるよう対応（ttc 版のみ）。

---

## English

**GenYo Serif** and **Genki Serif** are open-source Pan-CJK font families derived from Adobe’s Source Han Serif. They are designed to emulate the aesthetic of traditional typeface printing through localized glyph variants. Starting from Ver 2.000, Genki Serif was introduced as a new branch featuring automated "broken-stroke" processing to unify disparate glyph origins, serving as the technical foundation for the subsequent GenRyu and GenWan series.

### 🌟 Key Enhancements in Ver 2.0 / 2.1

* **Two Distinct Series**:
    * **GenYo Serif**: Maintains original stroke connections.
    * **Genki Serif**: Features automated "broken-stroke" (disconnected) processing to unify disparate glyph origins in modern Chinese writing styles.
* **Localized Variants for Traditional Chinese**:
    * **TW**: Modern common stroke conventions used in contemporary Taiwan.
    * **TC**: Classic letterpress printing style with traditional stroke forms.
* **Localized Variants for Japanese**:
    * **JP (Monospaced)**: Standard fixed-width version for general text.
    * **PJP (Proportional)**: Proportional spacing for Kana and punctuation, ideal for graphic design and subtitles.
* **Expanded Character Sets**:
    * **Taiwanese & Hakka Hanzi**: Extended support within the **CJK Extension H** range.
    * **HKSCS 2021** & **jf7000 (v0.9)**: Comprehensive coverage for modern and specialized usage.
    * **Hangul**: Added 2,350 syllables within the **KS X 1001** range.
* **Technical Refinements**: 
    * Reverted Chinese brackets to **Full-width**.
    * Adjusted `‘’“”` to proportional widths to ensure proper alignment for English text (e.g., `It’s`).
    * Available in both **TTC (Collection)** and **OTF** formats.

---

## 📜 歷史更新 / 履歴 / Version History

### Ver 2.100 (2024/08/22)
* 中文 TW、TC 版人工重製約百字常用字寫法，使風格更統一。
* 新增韓文 **KS X 1001** 編碼範圍內音節與相容字母。
* 提供傳統粗體模式，讓軟體 **Bold (B)** 按鈕生效（新增 X 版作為 R 版的粗體，僅限 ttc 版）。

### Ver 2.000 (2024/07/25)
* **重大重製**：以思源 V2.0 為底本全新製作。
* **版本分化**：中文分為 **TW** 與 **TC** 版；日文分為 **JP** 與 **PJP** 版。
* **系列擴充**：正式釋出「源起明體」系列。
* **字集擴充**：新增 jf7000 當務字集、HKSCS 2021 漢字，以及 CJK Ext. H 台客語漢字。
* **問題修復**：修正直排破折號置中問題、標點改回全形。

### Ver 1.500 (2020/04/11)
* 重製所有注音符號與方音符號，提高注音符號品質。
* 支援台客語漢字及羅馬拼音、注音直排。
* 假名與引號類橫排時改為比例寬（2.000 後中文標點已改回全形）。
* 修改數字2、3、問號為較習慣的形式
* 改以 **ttc** 形式釋出雙語版本。

### Ver 1.300 (2018/09/24)
* 修改部分 KR 版本不理想的文字對應，並統一部份文字部件。

### Ver 1.200 (2018/08/19)
* 解決 Word 等環境直排時標點符號無法正常旋轉的問題。

---

## ⚖️ 授權條款 / ライセンス / License

本字型基於 **SIL Open Font License 1.1** 授權。
* 您可以免費商用，無需支付授權費用。
* 您可基於本授權規定再散佈或改造本字型。
* 關於授權細節與免責事項，請詳讀 `SIL_Open_Font_License_1.1.txt` 檔案。

このフォントは SIL Open Font License 1.1 のもとで無償にて公開します。免責条項などに関してはライセンスをご確認ください。
