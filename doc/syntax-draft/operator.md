# 演算子優先順位
| 文字       | 用法 | 順位 |
|----------|----|----|
| `A ( B )`| 関数 | 1 |
| `( A )`  | 括弧 | 1  |
|          |
| `-A`     | 負値 | 2  |
|          |
| `A * B`  | 乗算 | 3  |
| `A / B`  | 除算 | 3  |
|          |
| `A + B`  | 加算 | 4  |
| `A - B`  | 減算 | 4  |
|          |
| `A == B` | 等号 | 5  |
| `A != B` | 不等号 | 5  |
| `A > B`  | 比較 | 5  |
| `A < B`  | 比較 | 5  |
| `A >= B` | 比較 | 5  |
| `A <= B` | 比較 | 5  |
|          |
| `A = B`  | 代入 | 6  |
