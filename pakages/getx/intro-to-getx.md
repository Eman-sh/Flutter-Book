Intro to Get

    1. Why Getx?
    2. What is Getx?

ما هو GetX ؟
حزمة GetX هي عبارة عن مكتبة أو إطار عمل مصغر يستخدم مع Flutter لتسهيل وتسريع كتابة بعض الأوامر، كالأوامر المتعلقة بعملية State Management والتنقل بين الصفحات و تغيير Theme واجهة البرنامج وغيرها من الأمور التي سنتطرق لها بشكل مفصل لاحقاً. تمكنك حزمة GetX من كتابة كود نظيف ومختصر يقوم بالعملية المطلوبة بأكمل وجه ممكن.
للمزيد حول موضوع State Management يمكنك زيارة الرابط التالي: 
https://docs.flutter.dev/development/data-and-backend/state-mgmt/intro

لماذا GetX؟
يتم دعم وتحديث Flutter وحزمه بشكل كبير، وهناك عدد كبير جدا من الحزم والمكتبات الممتازة التي يمكن استخدامها، وأحد هذه الحزم هي GetX ولكنها ليست الوحيدة خاصة في التعامل مع State Management، فهناك حزم ممتازة وأكثر شهرة وتقيما كحزمة Provider وحزمة Redux وحزمة BLoC و Riverpod وغيرها الكثير، ولا يمكن الجزم بأن أحد هذه الحزم أفضل من الآخر أو حتى أسهل في الاستخدام، فالأمر يعتمد على المبرمج نفسه والأسلوب الذي يفضله، فعلى سبيل المثال في حال كانت لديك خبرة في استخدام Redux مع React فإنه من الأوفر لك استخدامه في إنشاء تطبيقات Flutter أيضا وتطوير نفسك فيه بدلا من تعلم شيء جديد من الصفر، وفي حال كنت تعمل مع فريق وكانوا يستخدمون  Provider فمن الأفضل تعلم استخدامه بدلا من حزمة مختلفة وهكذا. لكن في حال لم تكن لديك خبرة مسبقة في أي من الحزم المذكورة أعلاه وكنت ترغب في تعلم إحداها فقد تكون حزمة  GetX خيارك الأفضل، فهي سهلة التعلم وتختصر عليك الكثير من الأوامر وتسرع عملية إنشاء البرامج، كما تمكنك من كتابة كود نظيف ومرتب، وهناك عدد جيد وسريع النمو من المصادر التي يمكن الرجوع لها لتعلم التعامل مع الحزمة وحتى لطلب المساعدة عند مواجهة مشكلة برمجية.
 
رابط الصفحة الرئيسية لحزمة GetX على موقع الرسمي لحزم Dart و Flutter المعروف بـ pub.dev:

https://pub.dev/packages/get


لمعرفة المزيد عن الحزم التي تتعامل مع موضوع State Management في Flutter  يمكنك زيارة الرابط التالي:
https://docs.flutter.dev/development/data-and-backend/state-mgmt/options




الركائز الثلاث لـ GetX:

يتميز عمل GetX  في ثلاث نقاط رئيسية وهي: 



1. عملية State management: لدى حزمة GetX طريقتين رئيسيتين لعملية State management، الأولى هي باستخدام دالة GetBuilder، والثانية والتي تعد reactive state manager أي أنها تفاعلية ( سنتطرق لكل نقطة على حدة وبشكل مفصل لاحقا).
2. عملية Route management: تتميز هذه الحزمة بسهولة كتابة وتنظيم عملية التنقل بين الصفحات، كما توفر لك عدد من الأمور كإضافة snackbars وdialogs و bottomsheets وكل هذا من دون الحاجة إلى استخدام context.
3. عملية Dependency management: 

لدى GetX حل بسيط ولكنه قوي لإدارة عملية Dependency باستخدام controllers. وذلك في سطر برمجي واحد فقط، كما أنه يمكنك من الوصول إليه من الـ view دون الحاجة إلى  استخدام inherited widget أو context. 

لا يقتصر عمل حزمة GetX على الركائز الثلاث هذه فقط، بل يمكن استخدامها والاستفادة منها في جوانب متعددة والتي سيتم ذكرها وتوضيحها في الدروس القادمة بإذن الله.
