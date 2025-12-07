# ue_test_content_proj

<br/>!注意!<br/>
UE5.7環境のテンプレートシーンへ移行しました<br/>
https://github.com/nagakagachi/ue_dev_bp_5_7
<br/>

# Analytic Fog
  reference https://blog.mmacklin.com/2010/05/29/in-scattering-demo/

  球 及び 球面円錐 に対するレイの通過経路上でのInscatterをレイマーチではなく解析的に計算するフォグのUEマテリアル実装です.
  
  ![](https://github.com/nagakagachi/ue_test_content_proj/blob/main/img/analyticfog00.png)

  Naga/AnalyticFog にあるマテリアルが該当します.

  描画領域の指定のためにBox等のマテリアルをアサインして利用します.

  |1|2|
  |---|---|
  |![](https://github.com/nagakagachi/ue_test_content_proj/blob/main/img/analyticfog02.png)|![](https://github.com/nagakagachi/ue_test_content_proj/blob/main/img/analyticfog03.png)|
  |3|4|
  |---|---|
  |![](https://github.com/nagakagachi/ue_test_content_proj/blob/main/img/analyticfog04.png)|![](https://github.com/nagakagachi/ue_test_content_proj/blob/main/img/analyticfog05.png)|

  マテリアルパラメータでPointLightモードとSpotLightモードの切り替え, ライト強度, SpotLightの広がりをコントロールします.
  位置や向き, 範囲は適用したオブジェクトでコントロールします.
  
  |1|2|
  |---|---|
  |![](https://github.com/nagakagachi/ue_test_content_proj/blob/main/img/analyticfog06.png)|![](https://github.com/nagakagachi/ue_test_content_proj/blob/main/img/analyticfog07.png)|
  
  
