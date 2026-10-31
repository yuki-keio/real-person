# real-person

## このスキルについて

Claudeにおいて、AIっぽい日本語を減らすためのスキルです。

スキルの中身は [skills/real-person/SKILL.md](skills/real-person/SKILL.md) にあります。

## 何が嬉しいか

・このスキルは敢えて人間が書いています。そのため、このスキル自体にAIっぽい表現が入ってしまうリスクが低いです。

・シンプルに作っているためトークンの追加消費が少ないです。

## claude.aiで使う

[skills/real-person/SKILL.md](skills/real-person/SKILL.md) をダウンロードし、claude.aiの「カスタマイズ」→「Skills」→「追加」→「Skillsをアップロード」から追加します。

## Claude Codeで使う

`skills/real-person` フォルダを `~/.claude/skills/` に置きます。

```bash
git clone https://github.com/yuki-keio/real-person.git
cp -r real-person/skills/real-person ~/.claude/skills/
```

## データの扱い

このスキルの中身は文章の書き方の指示だけです。プログラムの実行や外部へのデータ送信はありません。

## English

real-person is a skill that helps Claude write natural Japanese. It lists patterns that make Japanese text read as AI-written, such as too many commas, unnatural metaphors, overused hiragana, unusual word choices, and references the reader cannot follow. Claude uses it when you ask it to make Japanese text sound natural, and when it writes or edits Japanese documents, emails, articles, or reports for people to read. When it edits existing text, it keeps the original meaning and does not add guesses or filler.

This skill only contains writing instructions. It does not run programs or send data anywhere.
