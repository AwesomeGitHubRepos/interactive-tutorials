عادةً ما نعرّف دالة باستخدام الكلمة المفتاحية def في مكان ما في الشيفرة وندعوها كلما احتجنا إلى استخدامها.

    def sum(a,b):
        return a + b

    a = 1
    b = 2
    c = sum(a,b)
    print(c)

الآن بدلاً من تعريف الدالة في مكان ما واستدعائها، يمكننا استخدام دوال lambda في بايثون، وهي دوال تُعرف ضمنياً في المكان الذي نستخدمها فيه. لذا لا نحتاج إلى إعلان دالة في مكان ما وإعادة زيارة الشيفرة فقط لاستخدامها مرة واحدة.

لا تحتاج دوال lambda إلى اسم، لذا تُعرف أيضاً بالدوال المجهولة. نعرف دالة lambda باستخدام الكلمة المفتاحية lambda.

    your_function_name = lambda inputs : output

إذن المثال السابق للمجموع باستخدام دالة lambda سيكون،

    a = 1
    b = 2
    sum = lambda x,y : x + y
    c = sum(a,b)
    print(c)

هنا نقوم بإسناد دالة lambda إلى المتغير **sum**، وعند تقديم المتغيرات، أي a و b، تعمل كأنها دالة عادية.

Exercise
--------
اكتب برنامجاً يستخدم دوال lambda للتحقق مما إذا كان العدد في القائمة المعطاة فردياً. اطبع "True" إذا كان العدد فردياً أو "False" إذا لم يكن كذلك لكل عنصر.