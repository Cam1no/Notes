## デザインパターンのメリット
http://www.techscore.com/tech/DesignPattern/foundation/foundation1.html/

> デザインパターンとは、「よく出会う問題とそれにうまく対処するための設計」をまとめたものです。 デザインパターンを利用するメリットとして、最初にあげられるのが、「再利用性の高い柔軟な設計ができる」という点です。各パターンには、多くの知恵が凝縮されています。これまでは、設計者の直感や経験などに依存していた設計が、デザインパターンを導入することで、初心者でも先人たちが詰め込んだ「知恵」を利用した設計をすることが可能となります。また、先人たちの知恵を参考にすることで、設計力の向上も期待できます。

## オブジェクト指向の設計方法
http://www.techscore.com/tech/DesignPattern/foundation/foundation2.html/
> オブジェクト指向設計の方法として、いくつかの異なったアプローチがあります。現象を文章として記述し、その中から名詞と動詞を抽出し、それを元にクラスとメソッドを考える方法や、UML などを利用して実世界をモデル化し、現れたオブジェクトを設計に盛り込んでいく方法などです。全ての方法にはそれぞれ理論があり、どれもすばらしいものなのですが、いずれの方法を用いても抽象的な概念をクラスにするという設計に至るのは難しいのです。
> デザインパターンには、このような抽象的な概念をうまく取り入れたものがいくつかあります。例えばStrategy パターンというパターンでは「戦略」をクラスとして抽出していますし、State パターンでは「状態」というさらに抽象的なものをクラスとして抽出しています。
デザインパターンを学習することで、このような抽象的なものをクラスとして抽出する感覚が身についてきます。 現実世界だけを見ていると、なかなか設計がうまくいかないことがあります。こんなときは、デザインパターンを思い出して、抽象的な概念をクラスとして抽出することを考えてみましょう。

## オブジェクト指向における再利用方法
> オブジェクト指向における再利用の方法には、大きく2つあります。ひとつは「継承」で、もうひとつが「オブジェクトコンポジション」という考え方です。

継承について
> 継承を使うとスーパークラスで実装されている内容をサブクラスにも引き継ぐことができます。継承を利用することで、同じ目的を持ったメソッドを何度も実装する必要がなくなります。


オブジェクトコンポジションについて
> 例えば、最近の携帯電話にはSD カードというものを差し込むことができます。この SD カードは、データを記録しておくためのものです。携帯電話本体にもデータを記録しておく機能はありますが、SDカードを挿しこむことで大容量が記録できるように拡張されるわけです。携帯電話は、SDカードの「記録する」という機能を利用して機能を拡張しています。このように、別のオブジェクトが持つ機能を組み合わせて利用することをオブジェクトコンポジションと言うわけです。
