---
title: Machine Learning
localeTitle: تعلم الآلة
---
## تعلم الآلة

وقد حدد آرثر صامويل ، وهو رائد في مجال الذكاء الاصطناعي ، "تعلم الآلة" في عام 1959 بأنه "مجال الدراسة الذي يمنح أجهزة الكمبيوتر القدرة على التعلم دون مبرمج صريح".

يقدم البروفيسور توم ميتشل من جامعة CMU تعريفًا أكثر رسمية لتعليم الآلة.

> "يقال إن برنامج الكمبيوتر يتعلم من التجربة E فيما يتعلق بفئة معينة من المهام T وقياس الأداء P إذا كان أداءه في المهام في T ، كما تم قياسه بواسطة P ، يتحسن مع الخبرة E."

فكر في مثال خوارزمية تعلم الآلة التي تلعب الشطرنج. في هذا المثال ، يشير `E` إلى تجربة لعب الشطرنج ، `T` هي مهمة لعب الشطرنج ، ويشير `P` إلى احتمال أن البرنامج سيفوز في لعبة الشطرنج التالية.

التعلم الآلي هو بالضبط مثل كيف يتعلم الإنسان. على سبيل المثال ، إذا أراد الإنسان تعلم كيفية لعب البوكر ، فسيتعلم القواعد أولاً. ثم سيحاول الحصول على الخبرة من خلال لعب اللعبة. هذه التجربة ليست سوى مجموعة بيانات ضخمة لآلة باستخدامها تستطيع اتخاذ قرارات ذكية تعيد النظر في المشكلة المقترحة.

بشكل عام ، يمكن تصنيف مشاكل التعلم الآلي إلى تعلم تحت إشراف ، وتعلم غير خاضع للإشراف. في التعلم تحت الإشراف ، لديك الإدخال والإخراج المسمى ، وتشك في وجود علاقة بين المدخلات والمخرجات المسمى. عندما لا تعرف ما هو الإخراج المسمى أو إذا كانت هناك علاقة ، فإن التعلم غير الخاضع للرقابة سيساعدك في العثور على بنية في بياناتك إذا كانت موجودة.

لقد قمنا بتغطية فئتين رئيسيتين من التعلم الآلي ، ولكن هناك أربع فئات واسعة من التعلم الآلي:

1.  التعلم تحت الإشراف
2.  تعليم غير مشرف عليه
3.  التعلم شبه المشروط
4.  تعزيز التعلم

### التعلم تحت الإشراف

التعلم تحت الإشراف هو مهمة التعلم الآلي من استنتاج وظيفة من بيانات التدريب تحت الإشراف. التدريب تتكون البيانات من مجموعة من الأمثلة التدريبية. في التعلم تحت الإشراف ، كل مثال هو زوج يتكون من كائن إدخال (عادة متجه) وقيمة خرج مرغوبة (تسمى أيضًا بالإشارة الإشرافية). علاوة على ذلك ، يمكن أخذ التعلم تحت الإشراف كنموذجين وتصنيف وتراجع.

#### مخطط انسيابي أساسي / خطوات للتعلم تحت الإشراف

1.  جمع مجموعة التدريب.
2.  تقسيم مجموعة التدريب إلى كائن مدخلات (ميزات) وجسم الإخراج (فئات أو قيمة)
3.  قرر ما ستقوم بتطبيقه أو الانحدار أو التصنيف
4.  تقرر أي خوارزمية سوف تقوم بتطبيق ، SVM ، شبكة عميقة ، وما إلى ذلك
5.  تشغيل الخوارزمية على مجموعة التدريب واستخدام نموذج للتنبؤات

#### الدورات:

1.  [مقدمة لتعلم الآلة](https://www.udacity.com/course/intro-to-machine-learning--ud120?autoenroll=true)
2.  [التعلم الآلي - تدرس من قبل: أندرو نغ](https://www.coursera.org/learn/machine-learning)
3.  [علوم البيانات والتعلم الآلي مع بايثون - الأيدي!](https://www.udemy.com/data-science-and-machine-learning-with-python-hands-on/)
4.  [تعلم الآلة](http://ciml.info/)
5.  [The Analytics Edge - يدرس من قبل: MIT](https://www.edx.org/course/the-analytics-edge)

#### موارد الفيديو:

1.  [قناة سراج رافال على يوتيوب](https://www.youtube.com/channel/UCWN3xxRkmTPmbKwht9FuE5A)
2.  [قناة يوتيوب Sentdex ل](https://www.youtube.com/channel/UCfzlCWGWYyIQ0aLC5w48gBQ)

#### معلومات اكثر:

1.  [تعلم الآلة على ويكيبيديا](https://en.wikipedia.org/wiki/Machine_learning)
2.  [التعلم الآلي الغامض: يوتيوب](https://www.youtube.com/watch?v=83uAOzhzs-U)
3.  إذا كنت تريد مقدمة مختصرة عن التعلم الآلي ، وكنت تفضل مقاطع الفيديو ، فجرّب [فيديو مقدمة التعلم الآلي](https://youtu.be/cKxRvEZd3Mw) هذا
4.  إذا كنت تريد معرفة كيفية المضي قدمًا في تعلم تعلم الآلة ، فقم بإلقاء نظرة على هذا [الفيديو](https://youtu.be/nKW8Ndu7Mjw)

## مختبر

[بناء التطبيقات الذكية مع استوديو التعلم آلة أزور](https://github.com/Microsoft/computerscience/blob/master/Labs/AI%20and%20Machine%20Learning/Azure%20Machine%20Learning/Azure%20Machine%20Learning%20(Node).md)