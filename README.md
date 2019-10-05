# Supplementary information


Table S1. List of the SSR markers used for marker-assisted selection in breeding of Suzumaru-R.

Table S2. List of polymorphic sites between Suzumaru and Suzumaru R.

## Supplementary Method (解析の方法について) 
### SCN抵抗性のマーカーと解析 <Br>
「スズマルR」育成時, SCN抵抗性をマーカーで選抜するためにSCN抵抗性遺伝子に連鎖したDNAマーカーを作成した.　　
rhg1, rhg2, およびRhg4抵抗性遺伝子の供与親として利用されるスズヒメ(rhg1s, rhg2s, Rhg4 : レース1抵抗性), ゲテンシラズ(rhg1g, rhg2g : レース3抵抗性)の各抵抗性遺伝子型を区別するDNAマーカーとして, 1抵抗性につき3 つのプライマーをPCR 反応液中に同時に混合しPCRを行うことでPCR産物のサイズの違いから遺伝子型を判定できる共優性マーカーを作成し (Table 1), rhg1s, rhg2gおよびRhg4を選抜した. PCR条件は以下の通りである. 
  
  
* PCR条件 <Br> 
種子由来DNA 1uL　　 <Br>
10 x buffer 1 uL　　 <Br>
dNTP (10mM) 0.8uL　　 <Br>
Qiagen HotStarTaq 0.05L　 <Br>　
プライマー1~3 (20M) 各0.1uL　 <Br>
最終液量が10uLになるように滅菌水を加えよく混合 <Br>


* PCR の反応条件 <Br>
95℃で15 分間　　 <Br>
94℃・30 秒間　　 <Br>
55℃・30 秒間　　 <Br>
72℃・2分間　　 <Br>
x35サイクル    <Br>
に72℃・5分間インキュベート後低温保存. <Br>
  

* 遺伝子型の確認　　 <Br>
PCR産物の一部を2%アガロースゲルで電気泳動をし、バンドサイズ(抵抗性型が分子量が大きい)とバンド本数(へテロでは2本のバンドを検出)を元に遺伝子型を判定した. 
<Br>
  <Br>
    <Br>
### 「スズマル」および「スズマルR」間の遺伝的背景同質性比較
「スズマル」および「スズマルR」の葉および種子からゲノムDNAを抽出し, 150bpペアエンドでHiSeq X (イルミナ社)による全ゲノムシーケンスを実施し, それぞれ4.4Gb (14.8Mペアエンドリード, リード深度x4.4 )および5.0Gb (16.7Mペアエンドリード, リード深度x4.5 )の配列情報をfastqファイルとして取得し，前処理として、[trimmomatic-0.30] (http://www.usadellab.org/cms/index.php?page=trimmomatic) (Bolger et al. 2014)を用いて低品質配列やアダプター配列などを除去した。その後, BWA (Li and Durbin 2009)を用いてWilliams 82のダイズ参照配列(Soybean reference genome version 2.0 : Glyma. Wm82.a2 (Gmax275) : http://genome.jgi.doe.gov/pages/dynamicOrganismDownload.jsf?organism=Phytozome#, ダウンロード日： 2015年5月15日)に処理したリードをマッピングし, Picard v2.7.1 (http://broadinstitute.github.io/picard/) を用いて重複リードを除去した。最終的に前処理後のリードのうち, 「スズマル」で98.4% (26,682,197リード, 13.3Mペアエンドリード)、「スズマルR」で99.4% (23,483,095リード, 11.7Mペアエンドリード)が参照ゲノムにマッピングされた. 5本以上のリードでカバーされたゲノム領域の被覆率は, 「スズマル」および「スズマルR」でそれぞれ89.65%および88.1%(scaffoldを除いた染色体の被覆率は90.4%および88.9%)であった. GATK v.3.7.0 (McKenna et al. 2010)の RealignerTargetCreator, IndelRealignerを用いてリードを再アラインメント後HaplotypeCallerを用いて参照ゲノム配列に対する両品種の多型を検出した. 5本以上のリードでカバーされ, かつクオリティスコアが100以上のサイトを両品種で抽出し, さらに両品種間で多型が見られるサイトを抽出後, ヘテロやマルチアリルが検出されたサイトを除いた合計12,277サイトを解析に使用した. 


###########

Ogiso-Tanaka E, Kurosaki H, Yamashita Y, Takeuchi T, Taguchi-Shiobara F and Hajika M. (2019)<Br>
Identity of “Suzumaru” and “Suzumaru-R” revealed by whole genome sequencing<Br>
(in submitted)<Br>
<Br>
<Br>
小木曽映里, 黒崎英樹, 山下陽子, 竹内徹, 田口文緒, 羽鹿牧太 (2019)<Br>
ゲノムから見た「スズマル」と「スズマルR」の同質性. 農研機構研究報告 (リバイス中）<Br>
