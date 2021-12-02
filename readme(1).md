地図アプリ

# api code
AquaAhcxwqCD4ZKrL42WGTPqEWFF8GLOLqMSc6JbVDre5ww7ZuOgHrcs_Cuv0JH0

# Features
 
弊社の山口本店と博多店のマップを表示切替するために
県名のプルダウンメニューを作り県名を選択してもらうことで
地図を切り替えた。

# Requirement

function generateInfobox(lat, lng, map)関数内で
プルダウンメニューのvalue値をifelse分岐させることによって
店名と住所を切り替え表示可能だと考え試してみたがエラーになった。

臨時的な対処策としてgenerateInfoboxY(山口)、generateInfoboxH(博多)
と関数名がユニークなるようにして同じ動きだがtitle,descriptionが
変わるという関数を呼ぶようにした。

同じ動きの関数が何個もあるというのはスマートでないので
改善したい。

# css
今回はcssフォルダを作成せずhtmlと同じディレクトリに配置。
style.css