# Gemini API 密钥、使用小贴士与模型简介 ✨

大家好！为了方便大家使用 Gemini API 并充分利用其强大的功能，我们整理了这份小文档。

这里包含了我们目前拥有的 API 密钥、一些关于免费额度的重要提醒，以及几款常用模型的简单介绍。

## API 密钥分配 - 各取所需，避免“堵车”哦！🚗💨

为了确保大家在使用 API 时都能顺畅无阻，避免因为请求太频繁而互相影响（踩到速率限制的“坑”），我们把密钥做了个平均的分配（不够整除所有可能有多有少）。

请小伙伴们尽量使用自己名下的 Key ：

### 李文倩 👩‍💻
*   `AIzaSyDPw0HxibB26dAJAePMqM7-WgDc1ptQ34w`
*   `AIzaSyBqedWB6PXcyHlb76W53VpTgE47BXBvjHA`
*   `AIzaSyBGWPzZKTE-v86YFO__PVbr6DnItfYZRgo`
*   `AIzaSyCDuZeEAqeuTytghLlz2QwuJVvSrJVC5UQ`
*   `AIzaSyB23YRUKdE5BtMLGNX-M2yG6lQfz4bzC0U`

### 施潮剑 👨‍🔬
*   `AIzaSyCI27dXOnU1KFxErxw8vLYA1jFRknmFSp0`
*   `AIzaSyCwu_EXDuBYzmENDbzHiR7k9F_iD8bGVh8`
*   `AIzaSyDFIMCbtlKOzWCQpmbaHiOkSPT1kqBEWRg`
*   `AIzaSyA6CWDhbJFTCWMaRATe5hYKxCu6IOLR1jQ`
*   `AIzaSyBZhXhR-Yy4ZBLsaGzDgW5mLp91bT8V1kc`

### 王浩智 💡
*   `AIzaSyAlUeppa39LElCqwGavDoqrxKa7nE9uSog`
*   `AIzaSyAyH-wEK4FJfFmjlZ8bvzhgMC0ubU1hQjI`
*   `AIzaSyCi0yvmcpt3ARgZ08TlLsb-UnT8OmYHzYg`
*   `AIzaSyDLdGphRqFDaxPHw75cVfgwBgAyjOhUFC8`
*   `AIzaSyA4Orjh23s1h6nz2iWFKNopNaLI4tJMZxY`

### 赵翔 🚀
*   `AIzaSyB7SoqXme1ol4uUj842SgnX9Bh4gNutpqM`
*   `AIzaSyAmIk-AQeSAjdwojdkZDurdeQ-njy77C58`
*   `AIzaSyBahqJ5ttXVl4-VxUByT7MVLaUmeEUHrO0`
*   `AIzaSyDqRP32m_1xq3H_EvR9asnOnfLoTqAQlj0`
*   `AIzaSyB51J0biLKpm7UyLlaTTzGPlpLETEm5be4`

### 苏彦榕 🎨
*   `AIzaSyDLwnvqpWyof0fndUHKuqAn5KFfOY4jC7w`
*   `AIzaSyA7pgz9xqQc1DXzFhV6_UcHHLMS7HitwhM`
*   `AIzaSyDrVmoGOFoJ8R0YLeXBN_0dB8VWkWUlEqY`
*   `AIzaSyD6vlLyaTaf_0KlXRmiw1J3w2zPA6q2K-c`

### 杨樟林 🌳
*   `AIzaSyBVkTfNwI-4JSfkpuj4PY-o0bDaeGw220c`
*   `AIzaSyAQZq_BJ5gcGvtaeJapxfPXPWnHdHAxY7o`
*   `AIzaSyBUl0gNwpOMwx4vuIxANyEu6KJ4KTm9AOA`
*   `AIzaSyAzdyfZCgHKJi3EvZRzvP7uD0NQf1OY3UM`

### 安泉 💧
*   `AIzaSyAz1SlU6I5BcuxK5WWhpXcYDkP6mg96d6k`
*   `AIzaSyBfscBNYH7lbpBQUXDEFxWtnllz1KfpynY`
*   `AIzaSyCpUNJxnYBso0Z33JITX7sc9utTiqGUZCQ`
*   `AIzaSyCz6L3VTzr9aMjY2hxC1xJwOSoWuzNM2i4`

---

## 免费层级使用限制 - 省着点用，免费的很香！💰

大家注意，Gemini API 的免费额度是有一些“规则”的，主要是看这三个指标：

*   **RPM (每分钟请求数):** 一分钟内能调多少次。
*   **RPD (每日请求数):** 一天总共能调多少次。
*   **TPM (每分钟令牌数):** 一分钟内处理的文字量（Token 数）。

哪个指标先超了，API 就可能会暂时停摆！比如某个模型 RPM 是 10，你一分钟请求了 11 次，就算其他额度没用完，也可能会报错。

下面是各个模型免费版的具体“限速”情况，供大家参考：

| Model                          | RPM | TPM         | RPD   | 温馨提示                               |
| ------------------------------ | --- | ----------- | ----- | -------------------------------------- |
| Gemini 2.5 Flash Preview 04-17 | 10  | 250,000     | 500   | 新鲜出炉的 Flash 预览版！             |
| Gemini 2.5 Pro Experimental    | 5   | 250,000     | 25    | Pro 实验版，RPM 和 RPD 比较严格哦！    |
| Gemini 2.5 Pro Preview         | -   | -           | -     | 暂时没看到明确限制，但悠着点用总没错 |
| Gemini 2.0 Flash               | 15  | 1,000,000   | 1,500 | 经典 Flash，额度相对宽松             |
| Gemini 2.0 Flash Experimental  | 10  | 1,000,000   | 1,500 | 带图像生成的 Flash 实验版            |
| Gemini 2.0 Flash-Lite          | 30  | 1,000,000   | 1,500 | 轻量版 Flash，RPM 最高！             |
| Gemini 1.5 Flash               | 15  | 1,000,000   | 1,500 | 1.5 时代的 Flash                     |
| Gemini 1.5 Flash-8B            | 15  | 1,000,000   | 1,500 | 1.5 Flash 的 8B 版本                 |
| Gemini 1.5 Pro                 | 2   | 32,000      | 50    | 1.5 Pro 免费额度最少，省着用！       |

**注意:** Gemini 2.5 Pro Preview 目前没有明确的免费层级限制，不过还是建议大家合理使用。

---

## 可用模型简介 - 看看哪个是你的菜？🤔

目前我们主要关注这几款 Gemini 模型：

### Gemini 2.5 Pro
* **概述:** 目前性能最强的版本，在准确率和处理能力方面表现出色。
* **功能:** 支持多模态输入，包括文字、图片、音频和视频处理，具备复杂问题分析和大数据处理能力。
* **适用场景:** 适合需要高性能的编程任务、复杂推理分析，以及多模态数据处理场景。

### Gemini 2.5 Flash
* **概述:** 性能与速度的平衡之选，具备全面的处理能力。
* **功能:** 支持文字、图片、音频和视频处理，提供可控的推理深度和资源使用配置。
* **适用场景:** 适合需要快速响应的高频调用场景，可根据需求调整推理深度。

### Gemini 2.0 Flash
* **概述:** 新一代通用模型，提供全面的功能支持。
* **功能:** 支持多种输入类型处理，可进行代码生成、图像生成、文件分析和数据可视化等任务。
* **特点:** 响应速度快，性能稳定，适合构建AI助手应用。

如有任何疑问或建议，欢迎在群内讨论交流。
