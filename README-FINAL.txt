FLIP RUSH 7 ANDROID APP - FINAL v1.0 RELEASE SOURCE
===================================================

Live game URL:
https://flip-rush-7-60k8.onrender.com/

Android package ID:
com.fliprush7.app

Version:
1.0.0 (versionCode 1)

This is intentionally a FLAT GitHub project. All files can live directly in the repository root.
Gradle reconstructs the Android source and launcher-icon resource folders during the build.

IMPORTANT:
- Do not upload Flip-Rush-7-release-key.jks to a public repository.
- Do not upload Flip-Rush-7-GitHub-Secrets-PRIVATE.txt to a public repository.
- Keep both files backed up somewhere safe. They are the permanent Android signing identity.
- Normal Flip Rush 7 game changes continue to happen on the live website and DO NOT require a new APK.
- A new signed APK is only needed for changes to the native Android wrapper itself.

To build the permanent signed app, put FINAL-RELEASE-WORKFLOW.yml in your GitHub Actions workflow
(the workflow can be created/pasted in GitHub's Actions editor), create the four Actions secrets from
the separate PRIVATE secrets file, and run the workflow manually. GitHub will produce an artifact named:
Flip-Rush-7-v1.0-Release

Inside will be:
Flip-Rush-7-v1.0.apk
Flip-Rush-7-v1.0.sha256.txt
