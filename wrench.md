- :wrench: コメントアウト(cmd + /)
- :wrench: 一括コメントアウト(cmd + a && cmd + /)
- :wrench: 短形選択(始点をクリックしてから、終点を［Shift］＋［Option］＋左クリック)
- :wrench: タブ移動(ctrl + tab)
- :wrench: 新しいterminal、ブラウザのタブを開く(cmd + t)
- :wrench: タブを閉じる(cmd + w)
- :wrench: 右２列レイアウト(ctrl + ¥)
- :wrench: ファイル名検索(cmd + p)
- :wrench: word検索(cmd + f)
- :wrench: コマンドパレットを開く(cmd + shift + p)
- :wrench: 一時停止(ctrl + z)
- :wrench: 停止(ctrl + c)
- :wrench: 選択行を下にコピー(option + shift + ↓)
- :wrench: コマンド表示(ctrl + r)peco
- :wrench: レポジトリ表示(ctrl + g)ghq
- :wrench: 同名の値の同時選択(cmd + d)
- :wrench: 行の削除(cmd + x)
- :wrench: １つ前の状態に戻る(cmd + z)
- :wrench: tmux, 起動(tmux)
- :wrench: tmux,セッションの一覧(tmux ls)
- :wrench: tmux,デタッチ(ctrl+b d)
- :wrench: tmux,アタッチ(tmux )
- :wrench: tmux,アタッチ(tmux a -t \<session名>)
- :wrench: tmux,時計表示(ctrl+b t)
- :wrench: 行の先頭に移動(ctrl+a)
- :wrench: tmux,横に分ける(ctrl+b %)
- :wrench: tmux,縦に分ける(ctrl+b ")
- :wrench: tmux,ペイン破棄(ctrl+d)
- :wrench: tmux,ペイン移動(ctrl+b o)
- :wrench: tmux,ペイン拡大/縮小(ctrl+b z)
- :wrench: tmux,新規ウィンドウ(ctrl+b c)
- :wrench: tmux,次のウィンドウ(ctrl+b n)
- :wrench: tmux,ウィンドウの名前を変える(ctrl+b ,)


- :wrench: debug, 1 gem 'binding.pry', gem 'pry-doc', 2 binding.pry(ブレイクポイント)
```ruby
# https://pikawaka.com/rails/pry

# https://zenn.dev/offers/articles/20220602-binding-pry-debug-tips

# exit => 終了

# show-routes => 現在のルーティングを確認
# show-routes --grep user => userを含むroutesを表示

# show-models => 現在のモデルを確認
# show-model User => Userモデルを確認

# show-source => クラスやモジュール、メソッドの定義を確認

# show-doc => クラスやモジュール、メソッドのドキュメントを確認

# @ => binding.pryを埋め込んだ位置の確認

```
