Python एक बहुत सरल भाषा है, और इसकी सिंटैक्स बहुत सीधी-सादी है। यह प्रोग्रामर्स को बिना अतिरिक्त तैयारी के कोड के प्रोग्राम करने के लिए प्रोत्साहित करता है। Python में सबसे सरल निर्दोष "print" निर्देश है - यह बस एक पंक्ति को प्रिंट करता है (और C के विपरीत एक नई पंक्ति भी शामिल करता है)।

Python की दो प्रमुख संस्करण हैं, Python 2 और Python 3। Python 2 और 3 काफी अलग हैं। यह ट्यूटोरियल Python 3 का उपयोग करता है, क्योंकि यह अधिक अर्थपूर्ण सही है और नए फीचर्स को सपोर्ट करता है।

उदाहरण के लिए, Python 2 और 3 के बीच एक अंतर `print` कथन है। Python 2 में, "print" कथन एक फ़ंक्शन नहीं है, और इसलिए इसे बिना पैरेंथेसिस के बुलाया जाता है। हालांकि, Python 3 में, यह एक फ़ंक्शन है, और इसे पैरेंथेसिस के साथ बुलाना होता है।

Python 3 में एक स्ट्रिंग प्रिंट करने के लिए, बस लिखें:

    print("This line will be printed.")

### इंडेंटेशन

Python ब्लॉक्स के लिए इंडेंटेशन का उपयोग करता है, कर्ली ब्रेसेस के बजाय। दोनों टैब और स्पेस समर्थित हैं, लेकिन मानक इंडेंटेशन के लिए मानक Python कोड चार स्पेसेज़ का उपयोग करता है। उदाहरण के लिए:

    x = 1
    if x == 1:
        # indented four spaces
        print("x is 1.")

Exercise
--------

लाइन "Hello, World!" प्रिंट करने के लिए "print" फ़ंक्शन का उपयोग करें।