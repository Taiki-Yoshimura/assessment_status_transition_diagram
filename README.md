# assessment_status_transition_diagram
## 査定商材の査定状況の遷移図

## usage
1. vscodeにPlantUMLを追加
2. `⌘+,`で設定を開き以下の箇所を変更
  ```
  1. Plantuml: Render → PlantUMLServer
  2. Plantuml: Server → http://localhost:8080
  ```
3. consoleで以下を実行(plantumlの起動)
  ```
  $ docker run --rm -p 8080:8080 plantuml/plantuml-server:jetty 
  ```
4. `Option + D`で図のプレビュー表示
5. 画像を出力する際は以下
```
1. ⌘+shift+pを押す
2. PlantUML: Export Workspace Diagrams
3. 好きな形式を選択
```
