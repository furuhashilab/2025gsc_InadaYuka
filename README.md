# 2025gsc_YukaInada 
2025年ゼミ論から2026年卒論にかけての研究

## Blenderを用いた横浜駅周辺の混雑エリア・危険エリアの立体的な把握

横浜駅周辺を立体的に理解することが可能になる。最終的に卒論時にはウェブサイトあるいはアプリケーションを作成し、人々の混雑状況確認や緊急時の避難経路即決などに役立てる。

## 概要/Abstract
本研究では、自身の生まれ故郷であり観光地でもある横浜駅周辺をBlenderを用いて3Dシミュレーションする。横浜駅は国内有数の巨大ターミナルであり、多くの人々の通勤通学の拠点であると同時に、横浜ベイクオーターや中華街など、神奈川県を代表するスポットの密集地でもある。そのため、駅周辺は日常と観光、大型イベントになどにより複雑なパターンを示すだろう。歴史的に人類はこれまで紙地図やGoogle Mapsに依拠してきたが、混雑や災害時の危険エリアを十分に理解するため、本研究はBlenderによる3D化を通じて、人々の移動を視覚的かつ体感的に理解することで、都市観光における回遊性の分析や、ハザードマップの分かりやすさアップへの応用の可能性を提示する。

The purpose of this study is to use Blender to conduct a 3D simulation of people's movements and behaviors around Yokohama Station, my hometown and a tourist destination. Yokohama Station is one of Japan's largest terminals, serving as a hub for many commuters and students, while also housing Kanagawa Prefecture's most iconic attractions, such as Yokohama Bay Quarter and Chinatown. Therefore, the flow of people around the station will likely exhibit complex patterns due to factors such as daily life, tourism, and large-scale events. Historically, humans have relied on paper maps and Google Maps, but to fully understand the area's role as an evacuation route during congestion and disasters, this study uses Blender to create a 3D simulation of people's movements, providing a visual and experiential understanding of their movements. This suggests potential applications for analyzing urban tourism and improving the clarity of evacuation routes.

## 導入/Introduction
横浜駅周辺は非常に多様な人々が行き交うエリアである。このような大都市の複雑さは混雑や災害時の避難という観点でも重要な課題となる。空間把握ができないままでは、安全で効率的な移動や素早い避難が難しくなる可能性があり、2D地図は立体的な構造を直感的に捉えるには限界がある。そこで本研究では、横浜駅周辺を混雑状況マップ・ハザードマップとして3D空間上に表現する。イベント時や閑散時の観光地内の混雑エリア分析や、災害時における避難の困難なエリアの特定につなげていきたい。また、卒論時には、単なる可視化のみならず、人の動きをリアルタイムで重ねて見ることで、横浜における人々の動きや効率的な避難経路をより具体的に示すことを目指す。

## 研究目的

横浜駅周辺における人の動きを3Dシミュレーションし、従来の2D地図では捉えにくい混雑状況や空間的圧迫、地理感を表現する。

日常から特定イベント時まで、多様な動きパターンを比較しデータをとる事で、より正確に「さまざまな顔の横浜」を把握できる手段を作成する。

DXを用いた都市データサイト・アプリに応用可能な情報を作ることで、防災や観光に役立つ。

将来的に卒論で用いることとなれば、Webサイトやアプリで一般市民や災害救助者、イベント管理者などが閲覧できるプラットフォーム化を目指す。

## 研究方法

1. データ収集
- 衛星データ：Copernicus Blowser - Sentinel1
- ハザードマップ：国土地理院 - 重ねるハザードマップ、重ねるハザードマップ3D
- 従来2Dマップ：OpenStreetMap、Google Maps
- 観光・イベント情報：横浜市観光情報（横浜マラソンやお城EXPOの特設サイト等）

2. 3Dモデリングとシミュレーション
- Blenderで駅周辺空間（駅前、駅付近のビル、歓楽街）を3D可視化。
- ハロウィンやクリスマス、新学期、コロナ禍などさまざまな状況下を衛星データから観察。
- 災害時に避難が難しそうだと考察した建物の提示（建物の高さとハザードマップ資料を軸に考える）

・分析フレーム
- 多くの人がこれまで用いてきた2D地図と比較し、今回3D地図(将来的にはサイトやアプリ)を作成する意義を考える。
- さまざまな年の多様なイベント時や閑散時を比較し、混雑している場所を考察する。
- 2Dハザードマップと立体模型を重ねて感じた危険エリアを提示する。

・研究範囲について
- 駅から徒歩5〜10分圏を予定している
駅周辺の百貨店やベイクォーター、横浜中華街や横浜スタジアムあたりまでを範囲に含むことで、より役立つサイト作りができそうであったため。また、Blenderで3Dモデリングを行う際のことを踏まえ、駅とその近辺までに絞ることで現実的な計画にした。