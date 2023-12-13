

## Lv.3 ボタンを追加しよう
ボタンを追加して画像とテキストを変えてみよう。

### ・完成後アプリのキャプチャ動画

https://user-images.githubusercontent.com/112265560/215053433-cc18e806-25fb-464e-aab3-1fd4a1365332.mp4

### ・手順
1. 好きな食べ物の画像をダウンロードして`food_image`という名前で`res`の中の`drawable`にコピーしよう。
2. `change_color_button`を`show_profile_button`に変更しよう。textは "名前"に変えよう。
3. `Button`を配置して、`show_food_button`と設定しよう。textには "好きな食べ物"といれてね。
4. `LinearLayout`の`horizontal`を追加して、`linear_layout`と設定しておこう。
5. `linear_layout`の中に`show_profile_button`と`show_food_button`を入れよう。
6. `linear_layout`が一番下に来るように配置して、制約・マージンを付けてきれいに並べよう。
7.  `MainActivity.kt`で、ボタンを押したときの挙動を書いていこう。まずは、`show_profile_button`を押したときに次の挙動が起こるようにしよう。
		
		ImageViewの`profile_image`に画像の`profile_image`が表示されるようにしよう。
		TextViewの`profileLabelText`が"名前"に代わるように使用。
		TextViewの`profileCommentText`が自己紹介に変わるようにしよう。
8. 次に、`show_food_button`を押したときに次の挙動が起こるようにしよう。
		
		ImageViewの`profile_image`に画像の`food_image`が表示されるようにしよう。
		TextViewの`profileLabelText`が"好きな食べ物"に代わるように使用。
		TextViewの`profileCommentText`が食べ物の説明に変わるように（好きに書いてね）
