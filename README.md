# プロダクトの紹介
ランダムに出てきた山からオススメレストランを提案してくれるアプリです！

# 工夫した部分
いろんなAPIを掛け合わせするところ！
そして、APIKEYが必要なAPIを使用しました。

# 苦戦した部分

hotpepperグルメのAPIから値を取るときに、なぜかエラーがずっと治せず、
苦戦しました。

原因を探求したところ：

1. CORS問題
2. 細かい"?"とformat問題で値を取れなかったり、取れても処理できなかったりしました。