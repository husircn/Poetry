<p align="center">
  <a href="https://github.com/chinese-poetry/chinese-poetry">
      <img src="https://avatars3.githubusercontent.com/u/30764933?s=200&v=4" alt="chinese-poetry">
  </a>
</p>

<h2 align="center">chinese-poetry: 最全中文诗歌古典文集数据库</h2>

<p align="center">
  <a href="https://github.com/chinese-poetry/chinese-poetry/blob/master/LICENSE">
    <img height="28px" alt="License" src="http://img.shields.io/badge/license-mit-blue.svg?style=for-the-badge" style="max-width:100%;">
  </a>
  <a href="https://github.com/chinese-poetry/chinese-poetry/graphs/contributors">
    <img height="28px" alt="Contributors" src="https://img.shields.io/github/contributors/chinese-poetry/chinese-poetry.svg?style=for-the-badge" style="max-width:100%;">
  </a>
  <a href="https://www.patreon.com/jackeygao" rel="nofollow">
    <img height="28px" alt="Patreon" src="https://img.shields.io/endpoint.svg?url=https%3A%2F%2Fshieldsio-patreon.vercel.app%2Fapi%3Fusername%3Djackeygao%26type%3Dpledges&style=for-the-badge" style="max-width:100%;">
  </a>
</p>


最全的中华古典文集数据库，包含 5.5 万首唐诗、26 万首宋诗、2.1 万首宋词和其他古典文集。诗人包括唐宋两朝近 1.4 万古诗人，和两宋时期 1.5 千古词人。数据来源于互联网。

**为什么要做这个仓库?** 古诗是中华民族乃至全世界的瑰宝，我们应该传承下去，虽然有古典文集，但大多数人并没有拥有这些书籍。从某种意义上来说，这些庞大的文集离我们是有一定距离的。而电子版方便拷贝，所以此开源数据库诞生了。此数据库通过 JSON 格式分发，可以让你很方便的开始你的项目。

古诗采集没有记录过程，因为古诗数据庞大，目标网站有限制，采集过程经常中断超过了一个星期。2017 年新加入全宋词，[全宋词爬取过程及数据分析](https://jackeygao.github.io/r/words/crawl-ci.html)。

## 高频词分析图

<details open>
  <summary><b>宋词受欢迎的词牌名</b></summary>

<div align="center">
<img src="https://raw.githubusercontent.com/jackeygao/chinese-poetry/master/images/ci_rhythmic_topK.png" alt="两宋喜欢的词牌名">
</div>
</details>

<details>
  <summary><b>宋词高频词</b></summary>
  <img src="https://raw.githubusercontent.com/jackeygao/chinese-poetry/master/images/ci_words_topK.png" alt="宋词高频词" style="max-width:100%;">
</details>

<details>
  <summary><b>宋词作者作品榜</b></summary>
  <img src="https://raw.githubusercontent.com/jackeygao/chinese-poetry/master/images/ci_author_topK.png" alt="宋词作者作品榜" style="max-width:100%;">
</details>

<details>
  <summary><b>唐诗高频词</b></summary>
  <img src="https://raw.githubusercontent.com/jackeygao/chinese-poetry/master/images/tang_text_topK.png" alt="唐诗高频词" style="max-width:100%;">
</details>

<details>
  <summary><b>唐诗作者作品榜</b></summary>
  <img src="https://raw.githubusercontent.com/jackeygao/chinese-poetry/master/images/tang_author_topK.png" alt="唐诗作者作品榜" style="max-width:100%;">
</details>

<details>
  <summary><b>宋诗高频词</b></summary>
  <img src="https://raw.githubusercontent.com/jackeygao/chinese-poetry/master/images/song_text_topK.png" alt="宋诗高频词" style="max-width:100%;">
</details>

<details>
  <summary><b>宋诗作者作品榜</b></summary>
  <img src="https://raw.githubusercontent.com/jackeygao/chinese-poetry/master/images/song_author_topK.png" alt="宋诗作者作品榜" style="max-width:100%;">
</details>

## 数据集

- [唐诗宋诗](./全唐诗)
- [全宋词](./宋词)
- [五代·花间集](./五代诗词/huajianji)
- [五代·南唐二主词](./五代诗词/nantang)
- [论语](./论语)
- [诗经](./诗经)
- [幽梦影](./幽梦影)
- [四书五经](./四书五经)
- [蒙學](./蒙学)
- [纳兰性德诗集](./纳兰性德)

## License

[MIT](https://github.com/chinese-poetry/chinese-poetry/blob/master/LICENSE) 许可证。
