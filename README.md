# Volume Flip

Android app (Kotlin) जो Volume Up बटन का व्यवहार बदल देता है:

- Volume Up दबाओ → आवाज़ **कम** होती है
- Volume Up दो बार जल्दी दबाओ → फ़ोन **साइलेंट**
- स्क्रीन बंद (लॉक) हो और Volume Up दबाओ → स्क्रीन **ON**

## APK कैसे बनाएँ

**तरीका 1 – Android Studio:** फ़ोल्डर खोलो → Build → Build APK(s).

**तरीका 2 – GitHub (कंप्यूटर के बिना):**
1. इस फ़ोल्डर को एक नई GitHub repo में upload करो।
2. Actions टैब → "Build APK" चलने दो।
3. पूरा होने पर Artifacts से `VolumeFlip-apk` डाउनलोड करो और फ़ोन में install करो।

## सेटअप (install के बाद)

1. ऐप खोलो → "Accessibility सेटिंग खोलें" → Volume Flip को ON करो।
2. "Do Not Disturb access दें" → Volume Flip को allow करो (साइलेंट मोड के लिए)।
