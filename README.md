# Python_for_OrgChemist

同人誌「Python 学生化学実験」のコードをJupyter Notebookの形式で公開します。

## 認知された誤植

### P10 変数として利用できる文字
☀は変数として利用できない。

```python
晴れ = "晴れ"
```
ならば可能。

### P28 globalキーワード：関数名が未定義

誤：`global_var_add10()`<br>
正：`modify_global() `
