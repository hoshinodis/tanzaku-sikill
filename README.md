# tanzaku-skill

七夕の短冊（たんざく）風アスキーアートを生成する Claude Code スキル集。

## 含まれるスキル

### tanzaku-generator
入力された願い事や目標を、縦書きの短冊型アスキーアート（AA）に変換して出力します。

## インストール

```bash
gh skill install hoshinodis/tanzaku-skill
```

特定バージョンを固定（ピン留め）する場合：

```bash
gh skill install hoshinodis/tanzaku-skill tanzaku-generator --pin v1.0.0
```

## 使い方

Claude Code で「短冊を作って」「願い事を縦書きの短冊AAで出力して」のように依頼すると、このスキルが起動して縦書き短冊アスキーアートを生成します。

例：「世界平和」

```text
   🎋
   ┸
 ┌───┐
 │ 世 │
 │ 界 │
 │ 平 │
 │ 和 │
 └───┘
```

## ライセンス

MIT