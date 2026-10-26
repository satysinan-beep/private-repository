APK বানানোর দুটি উপায়:

উপায় ১ — GitHub দিয়ে (কম্পিউটারে কিছু ইনস্টল লাগবে না)
1. github.com এ অ্যাকাউন্ট খুলুন, নতুন private repository বানান।
2. এই ফোল্ডারের সব ফাইল (.github ফোল্ডারসহ) repository-তে আপলোড করুন।
3. Actions ট্যাবে গিয়ে "Build APK" চালান (Run workflow)। ৩-৫ মিনিট লাগবে।
4. শেষ হলে ওই রানের নিচে Artifacts থেকে "gmaam-app" ডাউনলোড করুন। ZIP খুললে .apk পাবেন।

উপায় ২ — Android Studio দিয়ে
1. Android Studio ইনস্টল করুন, File > Open দিয়ে এই ফোল্ডার খুলুন।
2. Sync শেষ হলে Build > Build APK(s) দিন।
3. APK পাবেন app/build/outputs/apk/debug/ ফোল্ডারে।

ফোনে ইনস্টল:
APK ফাইল ফোনে পাঠান, খুলুন, "অজানা উৎস থেকে ইনস্টল" অনুমতি দিন।

লোগো বদলাতে: app/src/main/res/drawable/ic_launcher.xml এর জায়গায় নিজের আইকন দিন
(আমাকে logo.png দিলে আমি আইকন সেট করে দেব)।
