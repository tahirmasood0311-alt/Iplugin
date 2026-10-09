# Iplugin — mobile + cloud build starter

This is a starter Android project with a basic floating "I" bubble. It is **not a finished AI WhatsApp assistant** and it does not read WhatsApp messages or send messages automatically.

## Build an APK using only your phone
1. Download this ZIP and extract it on your phone.
2. Create a GitHub repository named `Iplugin` in your mobile browser.
3. Upload the extracted project files/folders to the repository, keeping their folder structure. Make sure `.github/workflows/android.yml` is included.
4. Open the repository's **Actions** tab and enable Actions if asked.
5. Select **Build Iplugin APK** → **Run workflow** (or push/upload a commit to `main`).
6. When the run succeeds, open that run, scroll to **Artifacts**, and download `Iplugin-debug-apk`.
7. Extract the artifact ZIP to get `app-debug.apk`, then install it on your Android phone. Android may ask you to allow installation from that browser/file manager.

## Permissions and use
Open Iplugin, allow **Display over other apps**, then tap **Start floating button**. The bubble should appear over other apps if the device permits overlays. To stop it, return to Iplugin and tap **Stop floating button**.

## Important
- This starter currently contains only the floating bubble and a basic home screen. AI reply, translation, and WhatsApp integration are not implemented yet.
- Do not place an AI API key in Android code, GitHub files, or the APK. Add AI through a secure HTTPS backend with the key stored server-side.
- The debug APK is for testing, not a signed production release.
- Android 13+ and phone manufacturers may require notification/background settings. Do not disable system security protections.
