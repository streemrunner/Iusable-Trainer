# Iusable Trainer

This repo is a simple Vue.js App to study for law exams. The project currently uses an open API providing different
law questions from differnet students at the university of Basel.
You can change the Api to any endpoint returning a json object. It should return an array called "entries" with the objects containing the following entries:

- task: String containing the task
- order: Array of Strings in the _right_ order.

You could use any static json file, or of course use a dynamic source such as a headless CMS (such as Directus, Cockpit or Strapi).

Have fun and let me know if you have any ideas for improvement.
