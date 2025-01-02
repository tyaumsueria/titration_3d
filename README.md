# 中和滴定の拡張曲面描画ツール

酸と塩基の平衡定数を決め、それぞれの総濃度を変数とする、3DプロットによりpHの挙動を描画するツール。まずは`titration.ipynb`を開き、説明を読むべし。

導出は [こちらのnoteの記事](https://note.com/lupusaeternus/n/n6189044244e7) を参照されたい。
本ツールについては [こちらのnoteの記事](https://note.com/lupusaeternus/n/n0e27725acdf0) も参照されたい。

`titration.ipynb`をすべて実行すると`out.dat`が出力されるので、
```bash
gnuplot
l 'plot.gp'
```
を実行すると、自由に回転できるプロット画面が表示される。