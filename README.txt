APK banane ke 2 tareeqe

A) GitHub se (sabse aasan, PC par kuch install nahi)
 1. github.com par naya repository banayen aur is folder ki sari files upload/push karen (.github folder samet).
 2. Repository ke "Actions" tab mein "Build APK" chalayen (push par khud chalta hai).
 3. Run khatam hone par neeche "Artifacts" se ObaidDigitalPro-apk download karen -> andar app-debug.apk hai.

B) Android Studio se
 1. Node 22+ aur Android Studio install karen.
 2. Is folder mein: npm install  ->  npx cap sync android  ->  npx cap open android
 3. Build > Build APK(s).

Ads ki settings: www/index.html mein upar AdMob wale hissay mein (ADS_TEST, REWARD_UNLOCK_MS, INTER_EVERY ...).
Web content badalne ke baad: npx cap sync android
