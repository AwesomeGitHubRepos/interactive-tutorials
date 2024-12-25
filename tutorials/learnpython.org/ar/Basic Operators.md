هذا القسم يشرح كيفية استخدام العمليات الأساسية في بايثون.

### العمليات الحسابية

كما هو الحال مع أي لغة برمجة أخرى، يمكن استخدام عمليات الجمع والطرح والضرب والقسمة مع الأرقام.<br>

    number = 1 + 2 * 3 / 4.0
    print(number)

حاول أن تتنبأ بما ستكون النتيجة. هل يتبع بايثون ترتيب العمليات؟

عامل آخر متاح هو عامل المودولو (%)، الذي يعيد باقي القسمة الصحيح. المقسوم % المقسوم عليه = الباقي.

    remainder = 11 % 3
    print(remainder)

استخدام رمزين من الضرب يشكل علاقة القوة.

    squared = 7 ** 2
    cubed = 2 ** 3
    print(squared)
    print(cubed)

### استخدام العمليات مع السلاسل

يدعم بايثون دمج السلاسل النصية باستخدام عامل الجمع:

    helloworld = "hello" + " " + "world"
    print(helloworld)

يدعم بايثون أيضًا ضرب السلاسل لتشكيل سلسلة تحتوي على تسلسل متكرر:

    lotsofhellos = "hello" * 10
    print(lotsofhellos)

### استخدام العمليات مع القوائم

يمكن دمج القوائم مع عوامل الجمع:

    even_numbers = [2,4,6,8]
    odd_numbers = [1,3,5,7]
    all_numbers = odd_numbers + even_numbers
    print(all_numbers)

كما هو الحال في السلاسل، يدعم بايثون أيضًا تشكيل قوائم جديدة بتسلسل متكرر باستخدام عامل الضرب:

    print([1,2,3] * 3)

Exercise
--------

الهدف من هذا التمرين هو إنشاء قائمتين تسميان `x_list` و `y_list`
، تحتويان على 10 نسخ من المتغيرات `x` و `y`، على التوالي.
يُطلب منك أيضًا إنشاء قائمة تسمى `big_list`
، تحتوي على المتغيرات `x` و `y` ، 10 مرات لكل منها ، عن طريق دمج القائمتين اللتين قمت بإنشائهما.