# Dependabot Test

次の3つのプルリクが作成される
- パッチバージョンの更新
- developmentのマイナーバージョンの更新
- productionのマイナーバージョンの対象

|依存関係|パッケージ名|バージョン|Dependabotのpatch|Dependabotのdevelopment-minor|Dependabotのproduction-minor|
|-|-|-|-|-|-|
|develop|eslint|8.0.0|8.0.1|8.56.0|-|
|develop|jquery|2.1.0|2.1.4|2.2.4|-|
|production|lodash|3.0.0|3.0.1|-|3.10.1|
|production|request|2.0.0|2.0.1|-|2.6.3|
