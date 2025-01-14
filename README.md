# aidol-questionnaire-ui

A questionnaire survey ui library for Vue.js.

# Installation

``` bash
# yarn
$ yarn add @aidol/questionnaire-ui

# npm
$ npm i @aidol/questionnaire-ui
```

# Usage

``` js
// src/plugins/aidol-questionnaire-ui.js

import Vue from 'vue'
import AidolQuestionnaireUI from '@aidol/questionnaire-ui'

import '@aidol/questionnaire-ui/dist/AidolQuestionnaireUI.css'

Vue.use(AidolQuestionnaireUI)
```

``` js
// src/main.js
import Vue from 'vue'

// ...

import '@/plugins/aidol-questionnaire-ui'

// ...

new Vue({
  // ...
})
```

# Components

1. <a href="./docs/ai-choice.md">ai-choice（选择题，支持单选，多选）</a>
2. <a href="./docs/ai-short-answer.md">ai-short-answer（简答题）</a>
3. <a href="./docs/ai-rate.md">ai-rate（评分）</a>
4. <a href="./docs/ai-rate-group.md">ai-rate-group（评分组）</a>
5. <a href="./docs/ai-custom-rate.md">ai-custom-rate（可自定义的评分）</a>
6. <a href="./docs/ai-block-tips.md">ai-block-tips（提示块）</a>


> TIPS: 需要添加组件，或者更新组件功能的话，请提交 **PR**。

# CHANGE LOG

See <a href="./CHANGELOG.md">CHANGE LOG</a>。