{% set socials_text -%}
{%- if exercise_title -%}
GitHub Skills の実践演習「{{ exercise_title }}」を完了しました！ 🎉
{%- else -%}
GitHub Skills の実践演習を完了しました！ 🎉
{%- endif %}

{{ repository_url }}

#GitHubSkills #OpenSource #GitHubLearn
{%- endset -%}

<div align="center">

# 🎉 {{ login }} さん、おめでとうございます！ 🎉

<img src="https://octodex.github.com/images/welcometocat.png" height="200px" alt="演習の完了を祝う Welcometocat" />

### 🌟 演習を完了しました！ 🌟

## 🚀 成果を共有しましょう！

**身に付けたスキルを共有して、ほかの人にも学ぶきっかけを届けましょう！**

<a href="https://twitter.com/intent/tweet?text={{ socials_text | urlencode }}" target="_blank" rel="noopener noreferrer">
  <img src="https://img.shields.io/badge/X%20%E3%81%A7%E5%85%B1%E6%9C%89-1da1f2?style=for-the-badge&logo=x&logoColor=white" alt="X で共有" />
</a>
<a href="https://bsky.app/intent/compose?text={{ socials_text | urlencode }}" target="_blank" rel="noopener noreferrer">
  <img src="https://img.shields.io/badge/Bluesky%20%E3%81%A7%E5%85%B1%E6%9C%89-0085ff?style=for-the-badge&logo=bluesky&logoColor=white" alt="Bluesky で共有" />
</a>
<a href="https://www.linkedin.com/feed/?shareActive=true&text={{ socials_text | urlencode }}" target="_blank" rel="noopener noreferrer">
  <img src="https://img.shields.io/badge/LinkedIn%20%E3%81%A7%E5%85%B1%E6%9C%89-0077b5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn で共有" />
</a>

### 🎯 次に進みましょう

**この調子で学び続けましょう！**

[![](https://img.shields.io/badge/%E6%BC%94%E7%BF%92%E3%81%AB%E6%88%BB%E3%82%8B-%E2%86%92-1f883d?style=for-the-badge&logo=github&labelColor=197935)]({{ issue_url }})
[![GitHub Skills](https://img.shields.io/badge/GitHub%20Skills%20%E3%82%92%E8%A6%8B%E3%82%8B-000000?style=for-the-badge&logo=github&logoColor=white)](https://learn.github.com/skills)

*実際に作ることが、何よりの学びになります！* 🚀

</div>

---

&copy; 2025 GitHub &bull; [行動規範](https://www.contributor-covenant.org/ja/version/2/1/code_of_conduct/) &bull; [MIT License](https://gh.io/mit)