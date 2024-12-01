# 粵語 Emoji
配方: ℞ **rime-emoji-cantonese**

以粵語詞彙描述 Emoji，更符合粵語輸入習慣。

## 使用東風破(plum)安裝
[東風破(plum)](https://github.com/rime/plum) 安裝口令: `bash rime-install rime-emoji-cantonese`

下面以朙月拼音 (`luna_pinyin`) 爲例，爲其添加粵語Emoji支持:
~~~bash
bash rime-install rime-emoji-cantonese:emoji_cantonese:schema=luna_pinyin
~~~

## 手動安裝
1. 下載或克隆本倉庫，將 `opencc` 裏面嘅檔案放入 [Rime用戶資料夾](https://github.com/rime/home/wiki/RimeWithSchemata#rime-%E4%B8%AD%E7%9A%84%E6%95%B8%E6%93%9A%E6%96%87%E4%BB%B6%E5%88%86%E4%BD%88%E5%8F%8A%E4%BD%9C%E7%94%A8) 之下嘅 `opencc` 中

2. 將 `emoji_cantonese_suggestion.yaml` 裏面內容添加到目標方案嘅 custom 檔中

3. 部署(Deploy)
