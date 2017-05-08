# Curriculum-Translation-JP
OpenChain Curriculum Japanese Translation using OmegaT

本プロジェクトでは、The Linux Foundation(LF)が主催するオープンソース コンプライアンス推進プロジェクトOpenChainの主要英文資料を、日本で活動するLF参加企業の貢献者が日本語訳を作成します。翻訳資料を提供することで、日本のあらゆる企業・組織におけるオープンソース コンプライアンスの浸透と普及を目指しています。
1.	プロジェクトへの参加
・　The Linux Foundation Japanに参加を申請、メーリングリストlfj-trans@lists.linuxfoundation.orgに登録してもらう。
・　GitHubのユーザーIDを確保し、メーリングリストにて公開する。本リポジトリへの招待(Invitaion)が送付されるので受諾する。
・　Javaで記述されたコンピュータ翻訳支援ツール、OmegaTの最新版をインストールする。 http://omegat.org/
2．　翻訳作業の開始
・　OmegaTのチーム設定。OmegaTのメニュータブで、「設定」－「チーム．．．」を選択し、翻訳者の名前を設定。 この名前がコミットメッセージに翻訳者として表示される。
・　チームプロジェクトの設定。OmegaTのメニュータブで、「プロジェクト」－「チームプロジェクトのダウンロード...」を選択し、本リポジトリのURLと、新規ローカルフォルダーを指定。 ローカルフォルダーは、MyDocuments/Github/OpenChain等を指定する。 GitHubのユーザーIDとパスワードをきかれる。
・　2回目以降は、ローカルフォルダを開くと、自動的にGitHubと同期する。「設定」－「保存と訳文ファイル生成...」で訳文データの保存周期を設定できる。デフォルトは5分。
・　用語集、参考翻訳もローカルフォルダーに置くことでコミットされると思われるが、まだ試していない。
3．　翻訳作業
・　OmegaT起動後、ローカルフォルダーを開くと、原文一覧が表示されるので、1つの原文を選択。
・　原文は、MS Office形式で準備。
・　原文のタブは、訳文に残す。頻繁にt0, t1などのタブが入っているが、英文字のスペース調整のようなので、タブはそのままにして、スペース文字を削除する。
・　「保存」を選択すると、翻訳メモリ（/omegat/project_save.tmx)が保存され、同時にGitHubにコミット。
・　「訳文のファイルを生成」を指示するとローカルフォルダーのtargetフォルダーに、原文ファイルと同形式の訳文が生成されるので、確認やレビューに使う。ただし、「保存」を行ってもGitHubリモートリポジトリの訳文は変更されない(正確に言うと、リモートは更新されず、ローカルは一時更新された後に元に戻ることがあるが、リモートリポジトリ同期後、再度「訳文のファイルを生成」を指示するとローカルのtargetフォルダーに、他翻訳者の最新コミット分も含めて訳文が生成される)。
4．翻訳方針と免責事項
・　翻訳作業に当たってはOpenChainプロジェクトの翻訳ポリシー（https://wiki.linuxfoundation.org/openchain/spec-translations） に則るものとする
・　翻訳には免責事項として以下の文言を入れる；
　　 　　　「本文書は、The Linux FoundationにおけるOpenChainプロジェクトの英文ドキュメントから翻訳された公式の翻訳版です。翻訳版と英語版との間で何らかの意味の違いがあった場合には、英語版が優先されます。
また、OpenChainは世界中のメンバー企業が参加するプロジェクトではありますが、資料の細部では必ずしも各国の法令を検討していない可能性もあります。本翻訳資料を日本で活用する際には、各企業の法務部門を加えた検討が不可欠です。
“This is an official translation from the OpenChain Project. It has been translated from the original English text. In the event there is confusion between a translation　and the English version, The English text shall take precedence.” 」
5．　スタイルガイド
・　JTF日本語標準スタイルガイド（翻訳用）を一読する。；
https://www.jtf.jp/jp/style_guide/pdf/jtf_style_guide.pdf

  各企業のスタイルガイドとはちょっと違っているかもしれません。15分で一読できるので、「感じ」をつかむこと。 
・　さらに、LF の慣例に従い、以下のように統一する。
  カタカナの複合語は半角スペースで区切る (例: グラフィック ユーザー インターフェイス)。
  
  本文の文体は「ですます調(敬体)」とする。
6．　レビュー
・　各レビュー者は、それぞれ訳文ファイルを生成し、MS　Officeなどにて修正履歴・修正表示・コメントを入れる。修正付きの訳文は、メーリングリストに流すか、GitHubにアップロードする。
・レビュー者が修正をコミットすることもあり得るが、修正量が少ないときに限定されると考えられる。
7．既知の問題
・　複数の翻訳者が並行して同一の文節に作業した場合に、OmegaTがそれぞれを表示するようだが、調整はメーリングリスト。
・　原文・訳文ファイルは、MS OfficeやOpenOfficeでアクセスできるが、OpenOfficeでPowerPointデータをアクセスすると、表示が乱れる。
8．ライセンス
クリエイティブ コモンズ ライセンス
Copyright © 2016 Linux Foundation. The specification is licensed under the Creative Commons Attribution License 4.0 (CC-BY-4.0). A copy of the license can be obtained here: CC-BY-4.0; https://creativecommons.org/licenses/by/4.0/legalcode
