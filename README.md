# APK बनाने के कदम (कोई कोडिंग नहीं)
नोट: पहली बार ऐप खोलते समय इंटरनेट चालू रखें (लगभग 60 MB भाषा-फ़ाइल)। उसके बाद ऑफ़लाइन।
1. github.com पर मुफ़्त खाता बनाइए → New repository (नाम: GuideEnglish) → Public।
2. "uploading an existing file" दबाइए। इस ज़िप को खोलकर उसके अंदर की सारी फ़ाइलें/फ़ोल्डर खींचकर डालिए → Commit।
3. अगर `.github` फ़ोल्डर न चढ़े: Add file → Create new file → नाम `.github/workflows/build.yml` → build.yml की सामग्री चिपकाइए → Commit।
4. Actions टैब → "Build APK" → Run workflow। 10–15 मिनट रुकिए।
5. पूरा होने पर नीचे Artifacts में GuideEnglish-APK डाउनलोड करें → ज़िप खोलें → app-debug.apk।
6. फ़ोन में APK खोलिए → "अज्ञात स्रोत से इंस्टॉल" की अनुमति दीजिए → Install।
7. फ़ोन में English (India) आवाज़: Settings → Text-to-speech → Google → Install voice data।
