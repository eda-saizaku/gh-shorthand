# PR のレビュー時に使える略語のまとめ

自分がレビュー時に使うためのメモ

## 一般的な略語

| 略語  | 意味                  | 説明                                               |
| ----- | --------------------- | -------------------------------------------------- |
| LGTM  | Looks Good To Me      | コードに問題がなく、マージ可能であることを示す     |
| WIP   | Work In Progress      | まだ作業中で、レビュー準備が整っていないことを示す |
| PTAL  | Please Take A Look    | レビューを依頼する際に使用                         |
| TBR   | To Be Reviewed        | レビューが必要なことを示す                         |
| TL;DR | Too Long; Didn't Read | 長い説明の要約を示す際に使用                       |

## コードレビュー特有の略語

| 略語  | 意味                    | 説明                                                 |
| ----- | ----------------------- | ---------------------------------------------------- |
| IMO   | In My Opinion           | 個人的な意見を述べる際に使用                         |
| IMHO  | In My Humble Opinion    | より控えめに個人的な意見を述べる際に使用             |
| AFAIK | As Far As I Know        | 知る限りでは、という前提で情報を提供する際に使用     |
| IIRC  | If I Remember Correctly | 記憶が正しければ、という前提で情報を提供する際に使用 |
| FYI   | For Your Information    | 参考情報を提供する際に使用                           |
| nits  | Nitpicks                | 些細な指摘や提案を示す                               |
| q     | Question                | 質問がある場合に使用                                 |
| fy    | For You                 | 特定の人向けのコメントを示す                         |
| wip   | Work In Progress        | 作業中であることを示す（WIP と同じ意味）             |

## 技術的な略語

| 略語  | 意味                                                                                                 | 説明                                            |
| ----- | ---------------------------------------------------------------------------------------------------- | ----------------------------------------------- |
| DRY   | Don't Repeat Yourself                                                                                | コードの重複を避けるべきという原則              |
| KISS  | Keep It Simple, Stupid                                                                               | シンプルな設計・実装を心がけるべきという原則    |
| YAGNI | You Aren't Gonna Need It                                                                             | 必要のない機能を実装しないという原則            |
| SOLID | Single responsibility, Open-closed, Liskov substitution, Interface segregation, Dependency inversion | オブジェクト指向プログラミングの 5 つの基本原則 |

## アクション関連の略語

| 略語  | 意味    | 説明                                                               |
| ----- | ------- | ------------------------------------------------------------------ |
| TODO  | To Do   | 後で対応が必要な項目を示す                                         |
| FIXME | Fix Me  | 問題があり、修正が必要な箇所を示す                                 |
| XXX   | -       | 危険または問題のある箇所を示す（TODO や FIXME よりも緊急性が高い） |
| NIT   | Nitpick | 小さな指摘や提案を示す                                             |
