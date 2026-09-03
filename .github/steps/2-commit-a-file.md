## ステップ 2: ファイルをコミットする

_ブランチを作成できました！ :tada:_

ブランチを作成すると、`main` ブランチを変更せずにプロジェクトを編集できます。ブランチを用意できたので、ファイルを作成して初めてのコミットを行いましょう！

**コミットとは？** _[コミット](https://docs.github.com/ja/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits)_ は、プロジェクト内のファイルやフォルダーに加えた一連の変更です。コミットはブランチに記録されます。詳しくは「[コミットについて](https://docs.github.com/ja/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits)」をご覧ください。

### :keyboard: 演習: 初めてのコミット

次の手順では、GitHub 上で変更をコミットします。コミットには、ファイルの追加、削除、名前変更、内容の編集など、プロジェクトに加えた変更が記録されます。この演習では、先ほど作成したブランチに新しいファイルを追加し、その変更をコミットします。

> [!NOTE]
> `.md` は Markdown ファイルの拡張子です。Markdown について詳しくは、GitHub Docs の「[基本的な書き込みと書式設定の構文](https://docs.github.com/ja/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)」を読むか、GitHub Skills の演習「[Communicating using Markdown](https://github.com/skills/communicate-using-markdown)」をご利用ください。

1. リポジトリのヘッダーメニューにある **< > Code** タブで、新しいブランチ `my-first-branch` が選択されていることを確認します。

2. **Add file** ドロップダウンを開き、**Create new file** をクリックします。

   <img width="300" alt="新しいファイルを作成する選択肢のスクリーンショット" src="../images/create-new-file-option.png">

3. **Name your file...** フィールドに `PROFILE.md` と入力します。

4. **Enter file contents here** の入力欄に、次の内容をコピーします。

   ```
   Welcome to my GitHub profile!
   ```

   ![PROFILE.md ファイルを追加する画面のスクリーンショット](../images/add-profile-file.png)

5. 内容の入力欄の右上にある **Commit changes...** をクリックします。ダイアログが表示されます。

6. GitHub からコミットメッセージが提案されますが、練習のため自分で設定します。**Commit message** フィールドに `Add PROFILE.md` と入力します。

   - **コミットメッセージ**と、任意で入力できる**詳細な説明**により、変更内容をわかりやすく伝えられます。複数のファイルを含むコミットでは特に役立ちます。

   <img width="400" alt="コミットメッセージを付けて新しいファイルを追加する画面のスクリーンショット" src="../images/commit-message-dialog.png">

7. このレッスンではほかのフィールドは変更せず、**Commit changes** をクリックします。

8. ファイルを変更すると、Mona が作業内容の確認を始めます。少し待って、コメントを確認してください。進捗状況と次のレッスンが返信されます。


<details>
<summary>うまくいかない場合 🤷</summary><br/>

フィードバックが届かない場合は、次の点を確認してください。
- `my-first-branch` ブランチが選択されていることを確認します。
- `PROFILE.md` ファイルが作成され、リポジトリのルートフォルダーにあることを確認します。

</details>
