---
title: Yarn
localeTitle: غزل
---
## غزل

Yarn هو مدير حزم لرمزك. يسمح لك باستخدام ومشاركة التعليمات البرمجية مع مطورين آخرين من جميع أنحاء العالم. يعمل هذا الغزل بسرعة وأمان وبشكل موثوق بحيث لا تقلق بشأن تبعيات المشروع.

يتيح لك الغزل استخدام حلول مطورين آخرين لمشاكل مختلفة ، مما يسهل عليك تطوير البرامج. إذا كان لديك مشاكل ، يمكنك الإبلاغ عن المشكلات أو المساهمة مرة أخرى ، وعندما يتم إصلاح المشكلة ، يمكنك استخدام الغزل للحفاظ على كل ذلك محدثًا.

يتم مشاركة الكود من خلال شيء يسمى حزمة (يشار إليه أحيانًا باسم وحدة نمطية). تحتوي الحزمة على كافة التعليمات البرمجية التي يتم مشاركتها بالإضافة إلى ملف package.json الذي يصف الحزمة.

لاستخدام خيوط الغزل ، يجب عليك تثبيتها على نظامك أولاً. هناك روابط في نهاية هذه المقالة لمساعدتك في القيام بذلك في أي نظام التشغيل الخاص بك.

عندما يكون لديك خيوط مثبتة ، يمكنك البدء في استخدامها. فيما يلي بعض الأوامر الأكثر شيوعًا التي ستحتاج إليها.

### استخدام الغزل

**بدء مشروع جديد**

 `yarn init 
` 

سيفتح الأمر `yarn init` نموذجًا تفاعليًا لإنشاء مشروع غزل. ينشئ `yarn init` `package.json` ملف `package.json` يخزن المعلومات حول مشروعك. سيتم فتح هذا النموذج التفاعلي بالأسئلة التالية:

 `name (your-project): 
 version (1.0.0): 
 description: 
 entry point (index.js): 
 git repository: 
 author: 
 license (MIT): 
` 

يمكنك إما كتابة الإجابات لكل خيار أو فقط اضغط على إدخال دون كتابة أي شيء لاستخدام الافتراضي أو ترك فارغ. يمكنك دائمًا الانتقال إلى محرر النصوص المفضل لديك لتغيير ملف `package.json` ، إذا لزم الأمر.

يجب أن يكون ملف `package.json` الخاص بك مشابهاً لهذا:

 `{ 
  "name": "your-new-project", 
  "version": "1.0.0", 
  "description": "A description of your new project.", 
  "main": "index.js", 
  "repository": { 
    "url": "https://github.com/your-username/your-new-project", 
    "type": "git" 
  }, 
  "author": "Your Name <your_name@example.com>", 
  "license": "MIT" 
 } 
` 

**إضافة تبعية**

 `yarn add [package] 
` 

**ترقية التبعية**

 `yarn upgrade [package] 
` 

**إزالة التبعية**

 `yarn remove [package] 
` 

**تثبيت جميع تبعيات المشروع**

 `yarn install 
` 

#### معلومات اكثر:

*   [موقع الغزل](https://yarnpkg.com)
*   [وثائق الغزل](https://yarnpkg.com/en/docs)
*   [تثبيت الغزل](https://yarnpkg.com/en/docs/install)
*   [غزل مقابل npm](https://www.pluralsight.com/guides/node-js/yarn-a-package-manager-for-node-js)