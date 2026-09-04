{%- set all_passed = (results_table | selectattr("passed") | length) == (results_table | length) %}

{%- if all_passed %}

## ステップ {{ step_number }} - 合格 ✅

{%- else %}

## ステップ {{ step_number }} - 不合格 ❌

{%- endif %}

{%- if all_passed %}
<img src="https://octodex.github.com/images/inflatocat.png" align="right" height="150px" alt="ステップの合格を示す Inflatocat" />
{%- else %}

<img src="https://octodex.github.com/images/spidertocat.png" align="right" height="100px" alt="ステップの不合格を示す Spidertocat" />
いくつかの確認項目に合格していません。以下の結果を確認して、もう一度試してください。

間違いを見つけて修正しましょう！ 🤔
{%- endif %}

| 結果 | 確認項目 |
| ---- | -------- |

{%- for row in results_table %}
| {% if row.passed -%}✅ - 合格{%- else -%}❌ - 不合格{%- endif %} | {{ row.description }} |
{%- endfor %}

{%- if tips and tips.length %}

### ヒント

{%- for tip in tips %}

- {{ tip }}
  {%- endfor %}

{%- endif %}