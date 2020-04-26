# rime-hieroglyph-mdc
 埃及象形文字聖書體MdC轉寫
 
 安裝好 小狼毫/trime/prime/中州韻/鼠鬚管 等輸入法後，將兩個 .yaml 文件複製入 rime 系輸入法的“用戶文件夾”後，“重新部署”即可運行。若未能自動加入本輸入法，可能需要在 default.custom.yaml 文件中 patch/schema_list: 下加入一行 '    - {schema: hieroglyph_mdc}' 再部署。
 
 聖書體普通字符（U+13000 ~ U+1342F）若未能自動支持，可在 Win10 中査找 'Segoe UI Historic' 字體（ 'seguihis.ttf' 文件），或下載 'Noto Sans Egyptian Hieroglyphs' 字體。而目前尚無能夠正確顯示聖書體字符組合（需要正確解釋控制符 U+13430 ~ U+1343F ）的字體，不過在可以先加上控制符輸入着，假裝能夠看見正常的顯示，等待能夠正確顯示的字體出現。
 
 其餘說明都在 hieroglyph-mdc.schema.yaml 的文件頭裏面，及自己看 hieroglyph-mdc.dict.yaml 就好了。
 