# Iusable Trainer

This repo is a simple Vue.js App to study for law exams. The project uesd an open API providing different
law questions from differnet students at the university of Basel. Since the open API has been removed I added the possibility to load and export json files with exercises.

_This is all still work in progress_

You can change the Api to any endpoint returning a json object. It should return an array called "entries" with the objects containing the following entries:

- task: String containing the task
- order: Array of Strings in the _right_ order.

You can find examples of the datastructure in the _data_ folder. Also using the in app editor allows you to add exercise to the tasks collection and then export the tasks as a json file.

Have fun and let me know if you have any ideas for improvement.

# Dependencies

This project uses different open source dependencies, all licensed under MIT License:

- VueJS (http://vuejs.org), Copyright (c) 2013-present, Yuxi (Evan) You (https://github.com/vuejs/vue/blob/dev/LICENSE)
- autocomplete 2.0.3 (https://autocomplete.trevoreyre.com), Copyright 2019 Trevor Eyre, MIT License (https://github.com/trevoreyre/autocomplete/blob/master/LICENSE)
- uikit 3.2.6 (https://getuikit.com/), Copyright (c) 2013-2018 YOOtheme GmbH, getuikit.com, MIT License (https://github.com/uikit/uikit/blob/develop/LICENSE.md)
- axios (https://github.com/axios/axios), Copyright (c) 2014-present Matt Zabriskie, MIT License (https://github.com/axios/axios/blob/master/LICENSE)
