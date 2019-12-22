# Iusable Trainer

This repo is a simple Vue.js App to study for law exams. The project currently uses an open API providing different
law questions from differnet students at the university of Basel.
You can change the Api to any endpoint returning a json object. It should return an array called "entries" with the objects containing the following entries:

- task: String containing the task
- order: Array of Strings in the _right_ order.

You could use any static json file, or of course use a dynamic source such as a headless CMS (such as Directus, Cockpit or Strapi).

Have fun and let me know if you have any ideas for improvement.

# Dependencies

This project uses different open source dependencies, all licensed under MIT License:

- VueJS (http://vuejs.org), Copyright (c) 2013-present, Yuxi (Evan) You (https://github.com/vuejs/vue/blob/dev/LICENSE)
- autocomplete 2.0.3 (https://autocomplete.trevoreyre.com), Copyright 2019 Trevor Eyre, MIT License (https://github.com/trevoreyre/autocomplete/blob/master/LICENSE)
- uikit 3.2.6 (https://getuikit.com/), Copyright (c) 2013-2018 YOOtheme GmbH, getuikit.com, MIT License (https://github.com/uikit/uikit/blob/develop/LICENSE.md)
- axios (https://github.com/axios/axios), Copyright (c) 2014-present Matt Zabriskie, MIT License (https://github.com/axios/axios/blob/master/LICENSE)
