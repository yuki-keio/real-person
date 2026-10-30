real-person

日本語の文章からAIっぽい表現を取り除き、意味を変えずに人が書いたような自然な文章に直すためのClaudeのスキルです。

スキルの中身は real-person/SKILL.md にあります。

claude.aiで使う

real-person/SKILL.md をダウンロードし、claude.aiの「カスタマイズ」→「Skills」→「追加」→「Skillsをアップロード」から追加します。

Claude Codeで使う

real-person フォルダを ~/.claude/skills/ に置きます。

git clone https://github.com/yuki-keio/real-person.git

cp -r real-person/real-person ~/.claude/skills/
