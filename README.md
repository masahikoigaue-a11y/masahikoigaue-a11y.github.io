# GitHub Pages サンプル

このリポジトリは `index.html` をそのまま公開できる構成です。

## 公開手順（最短）
1. GitHubで新しいリポジトリを作成（例: `my-homepage`）
2. このフォルダをpush
   - `git init`
   - `git add .`
   - `git commit -m "Initial homepage"`
   - `git branch -M main`
   - `git remote add origin https://github.com/<your-id>/my-homepage.git`
   - `git push -u origin main`
3. GitHubの `Settings` → `Pages`
4. `Build and deployment` で以下を設定
   - `Source`: `Deploy from a branch`
   - `Branch`: `main` / `/(root)`
5. 数分待つと公開URLが表示される
   - `https://<your-id>.github.io/my-homepage/`

## 反映確認
`index.html` を修正して `git push` すると、自動で再デプロイされます。
