# real-person

## このスキルについて

Claudeにおいて、AIっぽい日本語を減らすためのスキルです。

スキルの中身は [real-person/SKILL.md](real-person/SKILL.md) にあります。

## 何が嬉しいか

このスキルは敢えて完全に人間が書いています。そのため、このスキル自体にAIっぽい表現が入ってしまうリスクが低いです。

シンプルに作っているためトークンの追加消費が少ないです。

## claude.aiで使う

[real-person/SKILL.md](real-person/SKILL.md) をダウンロードし、claude.aiの「カスタマイズ」→「Skills」→「追加」→「Skillsをアップロード」から追加します。

## Claude Codeで使う

real-person フォルダを `~/.claude/skills/` に置きます。

```bash
git clone https://github.com/yuki-keio/real-person.git
cp -r real-person/real-person ~/.claude/skills/
```
