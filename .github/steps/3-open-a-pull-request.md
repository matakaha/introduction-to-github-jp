## ステップ 3: pull request を作成する

_コミットできました！ :sparkles:_

プロジェクトを変更してコミットを作成できたので、pull request を使って変更内容を共有しましょう！

**pull request とは？** _[pull request](https://docs.github.com/en/get-started/quickstart/github-glossary#pull-request)_ は、共同作業を行う場所です。自分のブランチで行った変更をほかの人に示し、その変更を受け入れる、却下する、または追加の変更を提案するといったやり取りができます。この演習で作成する pull request では、自分のブランチにある変更とプロジェクトの `main` ブランチを並べて比較し、変更の取り込みを提案します。詳しくは「[Pull Request](https://docs.github.com/ja/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)」をご覧ください。

### :keyboard: 演習: pull request を作成する

コミット後、ブランチに最近プッシュされたことを示すメッセージと **Compare & pull request** ボタンが表示されているかもしれません。

![メッセージと Compare & pull request ボタンのスクリーンショット](../images/compare-pull-request-button.png)

pull request を自動的に作成する場合は、**Compare & pull request** ボタンをクリックし、以下の手順 5 に進みます。手動での作成を練習する場合は、手順 1 から 4 を行ってください。

1. リポジトリのヘッダーメニューにある **Pull requests** タブをクリックします。
2. **New pull request** ボタンをクリックします。
3. ドロップダウンメニューで次のブランチを選択します。
   
   - **base:** `main`
   - **compare:** `my-first-branch`

   ![base と compare のブランチ選択を示すスクリーンショット](../images/branch-selection-comparison.png)

4. **Create pull request** をクリックします。

5. pull request のタイトルを入力します。デフォルトではコミットメッセージがタイトルになります。この演習では、フィールドの内容を `Add my first file` に変更します。

6. 次のフィールドには、変更内容の**説明**を入力できます。ここまでに行ったことを簡潔に入力してください。これまでに、新しいブランチの作成、ファイルの作成、コミットを行いました。

   ![pull request の作成フォームを示すスクリーンショット](../images/create-pull-request-form.png)

7. **Create pull request** をクリックします。

8. 共同作業を行う場所ができると、Mona が作業内容の確認を始めます。少し待って、コメントを確認してください。進捗状況と次のレッスンが返信されます。


<details>
<summary>うまくいかない場合 🤷</summary><br/>

フィードバックが届かない場合は、次の点を確認してください。
- pull request のタイトルが正しいことを確認します。
- pull request に説明が入力されていることを確認します。

</details>
