# Moebuntu-kantan-Setup2
Moebuntuのかんたんセットアップアプリ２です。
## 1.このセットアップヘルパーの概要
このセットアップ ヘルパーは、”[mifjpn/Moebuntu-kawaiiUbuntu-ToysOriginal](https://github.com/mifjpn/Moebuntu-kawaiiUbuntu-ToysOriginal)''リポジトリ用です。
リポジトリには、9 つの萌え (またはかわいい) カラー テーマのコレクションがあります。
さらに、プリマスの萌え (またはカワイイ) テーマ (つまり、OS ロード時の画面) も含まれています。
また、萌え (またはカワイイ) サウンド数種類も含まれます。
このかんたんセットアップ アプリ２は、セットアップを簡単にすることを目的としています。

## 2.使い方
### 1)OS環境、ダウンロード、準備。
「UBUNTU22.04Lts」をご用意ください。
このスクリプトは、この OS で動作するはずです。
まず、Firefox でリリース "scripts.tar.xz" をダウンロードします。
次に、このファイルは、ダウンロードフォルダにダウンロードされます。そのフォルダを開いてダブルクリックすれば「アーカイブ　マネージャーが開き」などで展開を促しますので、展開しましょう。
展開すると、「scripts」 フォルダができています。ヘルパー アプリが含まれています。
### 2)最も簡単な使い方の説明
「Nautilus」ファイル マネージャで、「script」フォルダを開きます。
数あるシェルスクリプトの中で、実行するアプリが「Moeset」です。
最も簡単な方法は、この「Moeset」を右クリックし、「プログラムとして実行」を選んで、実行することです。
スクリプトを実行すると「Moebuntu セッティング　ヘルパー２」が表示されます。
### 3)「Moebuntu セッティング　ヘルパー２」の使い方
多くの設定項目の選択画面が表示されます。
ここで、最初に行う設定項目は「1) 基礎の設定(最初にやること)」です。
１を押して、エンターキーを押してください。
基礎の設定をするために、「gnome-shell-extension-manager」のウィンドウが開きます。
ここで何をあなたにしてほしいかを、このヘルパーが項目をあげて表示します。

1.上の「探す」タブを押して、"User Themes"を探してください。 
2.そこの「追加」ボタンを押して、インストールしてください。
3.上の「追加済み」タブを押して、その右のスイッチを「オン」にしてください。（右にスライドでオンです）
　もし、上にスイッチばない場合は、 "use extention"のスイッチを「オン」にしてください。
4."User Themes"の右にあるスイッチを「オン」にしてください。
(その後、ウィンドウを閉じるボタンを押して、このウィンドウを閉じてください)

ここで行うことはそれだけです。
  (豆知識の理由: この方法で GUI を操作する理由は、Gnome-Shell-Extention が GNOME バージョンの変更に適切に反応するようにするためです。)
 
「2) から 10)」 のメニューはそれぞれ「ウィンドウとランチャの色のテーマ」である9色の「テーマの設定です。
これらの設定では、ウインドウとランチャのほかに、ログイン画面を変更できます。
変更する場合は、「ログイン画面を変更しますか？」の質問に「Y」と入力してください。
次に、Moebuntuの基本ログイン画面に変更したい場合は、
　　「Moebuntuの基本ログイン画面を使用する場合は「Y」を押してください。もしくは、自分のオリジナル画像（PNG形式）や同じような見本の画像を使用する場合は「N」を押してください。」に
  　「Y」を入力してください。この場合、Moebuntuの基本ログイン画面を設定して終わり、メニューに戻ります。
ここで「N」を選択すると、自分のオリジナル画像（PNG形式）や同じような見本の画像を使用できます。
ログイン画面に入れたいオリジナルのPNG形式の画像を入力するための質問が出てきます。
「自分のオリジナルのログインイメージ（PNG形式）を使用する場合は、ファイラからそのイメージファイルをドラックアンドドロップしてください。何もせずにリターンボタンを押すと同じような見本のイメージが使用されます。」という質問がでますので、
変更したいPNG形式の画像ファイルがある場合は、nautilusファイルマネージャーからドラッグ アンド ドロップします。 何も入力せずにリターンを押すと、「四国めたんちゃん（東日本大震災からの復興キャラクター）の萌えイメージを使いますか?(Y/N)?」と聞かれますので「Y」を押すと同じような見本の四国めたんのイメージが読み込まれて設定されます。

「11) 萌えテーマを消す」を選択すると、Moebuntuの9色テーマファイルが削除され、UBUNTU既定の「Yaru」のテーマの初期設定に戻ります。
　そして、同時にシステム内に設定してあったMoebuntuの9色のテーマも削除されます。

「12)」と「13)」の選択肢は、萌えアイコンを設定または削除する選択肢です。
　消した場合は、UBUNTU既定のアイコンに戻り、さらに萌えアイコンのフォルダはシステムから削除されます。

「14)萌え起動画面」は、OS読み込み待ち画面の設定に使います。
Moebuntuの基本画面を使用したい場合は、
　　「Moebuntuの基本スクリーンイメージを使う場合「Y」を押してください。
　もしくは、自分のオリジナルのpng形式のイメージを入れる場合、また、同じような見本のイメージを入れる場合は「N」を押してください。」に
 「Y」を入力してください。この場合、Toyさんの基本待ち画面のを設定して終わり、メニューに戻ります。
 ここで「N」を選択すると、自分のオリジナル画像（PNG形式）や同じような見本の画像を使用できます。
OSの起動待ち画面に入れたいオリジナルのPNG形式の画像を入力するための質問が出てきます。
「自分のオリジナル（Png形式の）イメージを起動画面にしたい場合は、ファイラからドラックアンドドロップしてください。そのまま何も入れすにエンターキーを押すと同じような見本のイメージが設定されます。」
という質問がでますので、
変更したいPNG形式の画像ファイルがある場合は、nautilusファイルマネージャーからドラッグ アンド ドロップします。 何も入力せずにリターンを押すと、「四国めたんちゃん（東日本大震災からの復興キャラクター）の萌えイメージを使いますか?(Y/N)?」と聞かれますので「Y」を押すと同じような見本の四国めたんのイメージが読み込まれて設定されます。
(PNG 画像はタイル状に並べられて表示されることに注意してください。ディスプレイにぴったり1枚の画僧にするには、解像度と一致した、画像が必要です。)
「15) 萌え起動画面を消す」は、UBUNTU既定の黒画面にくるくるのついている、OS起動待ち画面に戻ります。さらに、萌え起動画面の設定を解除し、萌え起動画面のフォルダもシステムから消されます。

「16) 萌え壁紙」の選択肢は、デスクトップの壁紙を「Moebuntuロゴ」を貼り付けた萌え画像(カワイイ画像)に切り替える場合に使用します。
　デスクトップの待ち画面に入れたいオリジナルのPNG形式の画像を入力するための質問が出てきます。
　「設定するイメージファイル（JPG形式）をファイラからドラックアンドドロップしてください。そのまま何も入れずにリターンボタンを押した場合は同じような見本のイメージが使用されます。：」
 変更したいJPG形式の画像ファイルがある場合は、nautilusファイルマネージャーからドラッグ アンド ドロップします。 何も入力せずにリターンを押すと、「四国めたんちゃん（東日本大震災からの復興キャラクター）の萌えイメージを使いますか?(Y/N)?」と聞かれますので「Y」を押すと同じような見本の四国めたんのイメージが読み込まれて設定されます。
 
「17) 萌え壁紙を消す」を選択すると、UBUNTU規定のデスクトップの壁紙に戻ります。

選択肢 18) と 19) は、Firefox を　萌え版にするか、（UBUNTU既定の）萌えない版にするために使用します。 

選択肢 20)~23) はサウンドを設定するために使用されます (各バージョンがあります。)
  基本の萌え音は。アメーション素人声優さん作です。
  メイド風萌え音は基本のメイド版です。
  SF風萌え音は、基本の萌え音SFバージョンです。
  初音ミク萌え音は、初音ミクの声で作られています。
  選択肢 24) は、萌え音をすべて削除するために使用されます。

## 3.既知のエラーについて
　Virtual-Box上のUBUNTUの一部で、user-themeが作られない問題が上がっています。しかし、一部の場合であって再現ができませんでした。もし起こった場合は、"Gnome Tweaks"でテーマを設定するか、再起動するといいようです。

## 4.この「Moebuntu Setup Helper」のフォークと改良について
このスクリプトは基本的に MIT ライセンスです。 なのでフォークして、例えば現地語版を作るといいと思います。
ただし、テーマ、起動画面（プリマス）、およびアイコンはToyさんによって作成されています.
そのため、GitHub からダウンロードするスクリプトを作成してください。 （Toyさんのテーマなどの作品はスクリプトに含めないでください。）
よろしくお願いします。
