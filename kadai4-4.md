## 自動販売機（オブジェクト、DOM、イベント処理）のミニレポート
### Q4-1. Itemクラスのメソッドについて説明せよ。
* showItemListがクラスメソッドである理由を考察せよ。
　　・全商品の情報を一覧で表示するための関数、商品全体として扱うため、クラスメソッドとして定義している
    
* buyItemがインスタンスメソッドである理由を考察せよ。
  ・一つの商品として扱うため、インスタンスメソッドとして扱う。
  
### Q4-2. 商品の購入ボタンをクリックすると、どのような処理でセルの値が減少するか説明せよ。
* 購入された商品の在庫数のセルをどのようにして特定するのか説明せよ。
・購入ボタンを押すとbuyItem()が処理されて在庫が一つ減り、特定は、getElementByidを使う

* 特定したセルの値をどのように変更するのか説明せよ。
  ・取得した要素のtextContentを置き換える
  
### Q4-3. 感想
* 今回の課題で苦労したこと
* 演習を通して理解できたこと
* この自動販売機プログラムの追加機能や課題など
　・売り切れ表示を入れるとよりよくなると感じた。DOM操作の理解が深まった。
