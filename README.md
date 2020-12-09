# 漢語拼音系統轉寫

配方： ℞ **baopaau/rime-pinyin-translating**

基於 [Rime](http://rime.im) 的拼音互譯輸入方案，可以將漢語拼音轉寫爲注音符號等其他形式。

空格鍵輸出上屏碼

聲調輸入方法與地球拼音相同（`- / < \`，或以` ; `代一聲，以` , `代三聲，以` > `代四聲）

另設單擊` v `鍵（按一次輸入第一聲，按兩次輸入第二聲，如此類推）

## 目標形式
- [`pinyin_to_mps.schema.yaml`](pinyin_to_mps.schema.yaml)：國語注音符號
  - 輸入法：[rime-bopomofo](https://github.com/rime/rime-bopomofo)
- [`pinyin_to_mps2.schema.yaml`](pinyin_to_mps2.schema.yaml)：國語注音符號第二式
  - 輸入法：[baopaau/rime-mps2](https://github.com/baopaau/rime-mps2)
- [`pinyin_to_gr.schema.yaml`](pinyin_to_gr.schema.yaml)：國語羅馬字
  - 輸入法：[Chingyat/rime-romatzyh](https://github.com/chingyat/rime-romatzyh)
  - 輸入法：[baopaau/rime-romatzyh](https://github.com/baopaau/rime-romatzyh) 
- [`pinyin_to_yale.schema.yaml`](pinyin_to_yale.schema.yaml)：漢語耶魯拼音
  - 輸入法：[baopaau/rime-yale-mandarin](https://github.com/baopaau/rime-yale-mandarin)
- [`pinyin_to_gorlor.schema.yaml`](pinyin_to_gorlor.schema.yaml)：三拼國羅（by Tiing）
  - [原帖介紹](https://www.newsmth.net/nForum/#!article/Linguistics/79330)
  - 輸入法：[baopaau/rime-gorlor](https://github.com/baopaau/rime-gorlor) 


    
## 安裝

本方案依賴於

  - [地球拼音](https://github.com/rime/rime-terra-pinyin) ℞ **`terra-pinyin`**

[東風破](https://github.com/rime/plum) 安裝口令： `bash rime-install baopaau/rime-pinyin-translating`
