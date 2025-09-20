# 2025gsc_YukaInada
2025年ゼミ論

## Blenderを用いた横浜駅周辺の人流シミュレーション

横浜駅周辺を立体的に理解することが可能になる。最終的にはウェブサイトあるいはアプリケーションを作成し、人々の混雑状況確認や緊急時の避難経路即決などに役立てる。

## 概要/Abstract
本研究では、自身の生まれ故郷であり観光地でもある横浜駅周辺の人の動き・行為をBlenderを用いて3Dシミュレーションすることを目的とする。横浜駅は国内有数の巨大ターミナルであり、多くの人々の通勤通学の拠点であると同時に、横浜ベイクオーターや中華街など、神奈川県を代表するスポットの密集地でもある。そのため、駅周辺の人流は日常と観光、大型イベントになどにより複雑なパターンを示すだろう。歴史的に人類はこれまで紙地図やGoogle Mapsに依拠してきたが、混雑時や災害時の避難経路として十分に理解するため、本研究はBlenderによる3D化を通じて、人々の移動を視覚的かつ体感的に理解することで、都市観光における回遊性の分析や、避難経路の分かりやすさアップへの応用の可能性を提示する。

The purpose of this study is to use Blender to conduct a 3D simulation of people's movements and behaviors around Yokohama Station, my hometown and a tourist destination. Yokohama Station is one of Japan's largest terminals, serving as a hub for many commuters and students, while also housing Kanagawa Prefecture's most iconic attractions, such as Yokohama Bay Quarter and Chinatown. Therefore, the flow of people around the station will likely exhibit complex patterns due to factors such as daily life, tourism, and large-scale events. Historically, humans have relied on paper maps and Google Maps, but to fully understand the area's role as an evacuation route during congestion and disasters, this study uses Blender to create a 3D simulation of people's movements, providing a visual and experiential understanding of their movements. This suggests potential applications for analyzing urban tourism and improving the clarity of evacuation routes.

##研究目的

横浜駅周辺における人の動きを3Dシミュレーションし、従来の2D可視化では捉えにくい混雑状況や空間的圧迫、地理感を表現する。

日常から特定イベント時まで、多様な動きパターンを比較しデータをとる事で、より正確に「さまざまな顔の横浜」を把握できる手段を作成する。

DXを用いた都市データサイト・アプリに応用可能な情報を作ることで、防災や観光に役立つ。

将来的に卒論で用いることとなれば、Webサイトやアプリで一般市民や災害救助者、イベント管理者などが閲覧できるプラットフォーム化を目指す。

## 研究方法

1データ収集
- 人流データ：駅周辺の通行量統計（横浜市オープンデータ等）、GPS位置情報サービス（Agoop等）、加えて現地観察を組み合わせる。
- 空間構造データ：駅構内図（公式資料）、周辺地図（OpenStreetMap, Google Maps）、建物3Dモデル（CityGMLや国土地理院データ）。
- 観光・イベント情報：横浜市観光情報（みなとみらい、中華街、山下公園など）、イベントカレンダー。

2. 3Dモデリングとシミュレーション
- Blenderで駅周辺空間（広場、地下街、連絡通路）を3D再現又はアニメーション化。
- 平日朝夕ラッシュ
- 休日状況(中華街などの観光地への人の流れ)
- 災害時避難シナリオ（首都直下地震などを想定）

分析フレーム
- 多くの人がこれまで用いてきた2D地図と今回の	•	3D地図を比較し、使い道別に可能性を検討。
- 混雑している場所や移動速度低下ポイントなどを指標化する。
- 空間要因(観光地)との関連を考察。

## 研究範囲について

# 駅から徒歩5〜10分圏を予定している
駅周辺の百貨店やベイクォーターあたりまで含むことで、多くの人が集まる地を調べることができそうであったため。Blenderでの再現を作成する際のことを踏まえても駅とその近辺に絞ることで現実的な計画にした。