# [Progress of Ruby/Numo: Numerical Computing for Ruby](http://rubykaigi.org/2017/presentations/masa16tanaka.html)

* Speaker: Masahiro TANAKA / 田中昌宏

Background information / 事前資料

## Main topic: [Ruby/Numo project](https://github.com/ruby-numo)

### Ruby/Numo modules:

* [Numo::NArray](https://github.com/ruby-numo/narray) - N-dimensional Numerical Array library.
    * [Numo::NArray概要](https://github.com/ruby-numo/narray/wiki/Numo::NArray%E6%A6%82%E8%A6%81) (wiki in Japanese) - Brief description of Numo::NArray features.
    * [Numo::NArray vs numpy](https://github.com/ruby-numo/narray/wiki/Numo-vs-numpy)

* [Numo::Linalg](https://github.com/ruby-numo/linalg) - Linear Algebra library (Interface to [BLAS](http://www.netlib.org/blas/)/[LAPACK](http://www.netlib.org/lapack/)).
* [Numo::GSL](https://github.com/ruby-numo/gsl) - Ruby interface for [GSL (GNU Scientific Library)](http://www.gnu.org/software/gsl/).
* [Numo::FFTE](https://github.com/ruby-numo/ffte) - Ruby interface for [FFTE (A Fast Fourier Transform library with radix-2,3,5)](http://www.ffte.jp/).
* [Numo::Gnuplot](https://github.com/ruby-numo/gnuplot) - Simple and easy-to-use Gnuplot interface ([Demo repository](https://github.com/ruby-numo/gnuplot-demo)).

Related presentation:

* [Ruby科学データ処理ツールの開発 NArrayとPwrake](https://www.slideshare.net/masa16tanaka/narray-pwrake) (slide in Japanese)
    * Background of NArray development including new design for Numo::NArray.

### External Sources / 外部ソース:

* [MF](http://medfreak.info/)
    * [【Ruby】numo-gnuplotで遊ぶ](http://medfreak.info/?p=2492)
    * [Rubyの行列計算ライブラリ Numo::NArray 覚え書き](http://medfreak.info/?page_id=3551)
    * [落書き numo-gnuplot でCT画像を3Dにしてみる](http://medfreak.info/?p=2597)
    * [落書き Numo/NArray 最小近傍法](http://medfreak.info/?p=2823)
    * [Rubyでフーリエ変換 Numo::FFTE を試してみる](http://medfreak.info/?p=2843)
    * [【Ruby】Numo::NArray でニューラルネットワークでMNIST認識](http://medfreak.info/?p=2975)
    * [【Ruby】 Numo::Gnuplot で箱ひげ図 (boxplot)](http://medfreak.info/?p=3758)
    * [numo-gnuplot playground](http://medfreak.info/?p=4018)

* [Tech Blog by Akanuma Hiroaki](http://blog.akanumahiroaki.com/) - 「[ゼロから作るDeep Learning](https://www.oreilly.co.jp/books/9784873117584/)」のRuby/Numoへの移植
    * [NumPyとNumo::NArray, Matrixでの演算の比較](http://blog.akanumahiroaki.com/entry/2017/03/10/140000)
    * [3層ニューラルネットワーク実装](http://blog.akanumahiroaki.com/entry/2017/03/17/090000)
    * [MNISTデータセットをNArray配列として扱う](http://blog.akanumahiroaki.com/entry/2017/03/23/091000)
    * [ニューラルネットワークの推論処理](http://blog.akanumahiroaki.com/entry/2017/03/27/083000)
    * [ニューラルネットワークの数値微分による学習アルゴリズムの実装](http://blog.akanumahiroaki.com/entry/2017/04/03/083000)
    * [ニューラルネットワークの誤差逆伝播法による学習アルゴリズムの実装](http://blog.akanumahiroaki.com/entry/2017/04/15/160000)
    * [各種パラメータ最適化手法の実装（SGD, Momentum, AdaGrad, Adam）](http://blog.akanumahiroaki.com/entry/2017/04/21/090000)

* [@naitohの日記](http://naitoh.hatenablog.com/)
    * [RejectKaigi 2017で『Rubyで機械学習を行うための「巨人の肩に乗る」別の方法』という発表をしました](http://naitoh.hatenablog.com/entry/2017/08/20/221410)

## Information of the first NArray (inherited by Numo::NArray)
* [NArray home page](https://masa16.github.io/narray/)
* [RubyKaigi 2010 talk](http://rubykaigi.org/2010/ja/events/83/)
    * [slide](https://www.slideshare.net/masa16tanaka/narray-and-scientific-computing-with-ruby)

### External Sources / 外部ソース:

* [「それ NArray でできるよ」 by tmaedaさん](https://speakerdeck.com/tmaedax/sore-narray-dedekiruyo) (slide in Japanese)
