## ステップ 1: ブランチを作成する

_「GitHub 入門」へようこそ！ :wave:_

**GitHub とは？** GitHub は、_[Git](https://docs.github.com/en/get-started/quickstart/github-glossary#git)_ を使ってバージョンを管理する、共同作業のためのプラットフォームです。
オープンソースソフトウェアを共有し、コントリビューションする場として広く利用されています。詳しくは「[オープンソース](https://docs.github.com/en/get-started/quickstart/github-glossary#open-source)」をご覧ください。

:tv: [動画: GitHub とは？](https://www.youtube.com/watch?v=pBy1zgt0XPc)

**リポジトリとは？** _[リポジトリ](https://docs.github.com/en/get-started/quickstart/github-glossary#repository)_ は、ファイルやフォルダーを格納するプロジェクトです。
リポジトリでは、ファイルやフォルダーのバージョンを追跡します。詳しくは、GitHub Docs の
「[リポジトリについて](https://docs.github.com/ja/repositories/creating-and-managing-repositories/about-repositories)」をご覧ください。

**ブランチとは？** _[ブランチ](https://docs.github.com/en/get-started/quickstart/github-glossary#branch)_ は、リポジトリから分岐した並行バージョンです。
リポジトリには、デフォルトで `main` という名前のブランチが 1 つあり、これが基準となるブランチです。
別のブランチを作成すると、リポジトリの `main` ブランチを複製し、メインプロジェクトに影響を与えず安全に変更できます。
多くの人は、プロジェクトのほかの部分に影響を与えず特定の機能に取り組むためにブランチを使います。

ブランチを使うと、自分の作業を `main` ブランチから分離できます。
つまり、ほかの人の作業を守りながらコントリビューションできます。
詳しくは「[ブランチの概要](https://docs.github.com/ja/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches)」をご覧ください。

**プロフィール README とは？** _[プロフィール README](https://docs.github.com/ja/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme)_ は、GitHub.com のコミュニティに自分の情報を伝えられる、GitHub プロフィールの自己紹介欄です。
GitHub では、プロフィールページの上部にプロフィール README が表示されます。詳しくは「[プロフィールの README を管理する](https://docs.github.com/ja/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme)」をご覧ください。

![プロフィール README の例を示すスクリーンショット](../images/example-profile-readme.png)

### :keyboard: 演習: 初めてのブランチ

1. ブラウザーで新しいタブを開き、先ほど作成したリポジトリ（この演習のコピー）に移動します。このタブで手順を読みながら、2 つ目のタブで操作を進めてください。

2. リポジトリのヘッダーメニューにある **< > Code** タブを開きます。

   ![Code タブを強調したスクリーンショット](../images/code-tab-highlight.png)

3. **main** ブランチのドロップダウンをクリックします。

   <img width="300" alt="ブランチ選択を強調したスクリーンショット" src="../images/branch-selection-dropdown.png">

4. **Find or create a branch...** と表示されたテキストボックスに、`my-first-branch` と入力します。
   
   > **注:** 次のステップへ進むため、この名前が自動的に確認されます。:wink:

5. **Create branch: `my-first-branch` from main** をクリックして、ブランチを作成します。

   <img width="300" alt="ブランチ作成の選択肢を強調したスクリーンショット" src="../images/create-branch-prompt.png">

   - 作成したブランチへ自動的に切り替わります。
   - **main** と表示されていたブランチのドロップダウンに、新しいブランチ名が表示されます。

6. ブランチが GitHub にプッシュされると、Mona が作業内容の確認を始めます。少し待って、コメントを確認してください。進捗状況と次のレッスンが返信されます。


<details>
<summary>うまくいかない場合 🤷</summary><br/>

フィードバックが届かない場合は、次の点を確認してください。
- ブランチ名が正確に `my-first-branch` となっていることを確認します。前後にほかの文字を付けないでください。

</details>
