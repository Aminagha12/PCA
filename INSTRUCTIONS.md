# د APK Signed کولو لارښود

## مشکل
Android د unsigned APK فایلونه د Play Protect له امله پاکوي.

## حل — دا 2 فایلونه GitHub کې ځای پر ځای کړئ

### ① .github/workflows/build.yml بدل کړئ
د repo کې موجود build.yml فایل د `build.yml` نه چمتو شوي نوي محتوا سره بدل کړئ.

### ② app/build.gradle بدل کړئ
د repo کې موجود app/build.gradle فایل د `app_build.gradle` نه چمتو شوي نوي محتوا سره بدل کړئ.

## د GitHub Actions چلولو وروسته
1. Actions → ForexRobot run → Artifacts
2. `ForexRobot-SIGNED-APK` download کړئ
3. Unzip کړئ → `app-release.apk` ستاسو signed APK دی

## د install کولو ستونزه که وي
Settings → Security → Install unknown apps → Chrome/Files → Allow
