# CHIP Android Mobile SDK
Our Android Mobile SDK helps you integrate with CHIP payment into your Android application. It redirects the application to payment page.

## Prerequisite
You are required to set **Brand ID** and **Secret Key** from your Developer section by logging in to your account.

## Installation
1. Download [CHIP Android SDK](https://github.com/CHIPAsia/chip-android-sdk/releases).
2. Copy the SDK to your project.
3. Add `include ':sdk'` to `settings.gradle`
4. Add to `build.gradle`:
    ```
    dependencies {
    	...
    	implementation project(":sdk")
    }
    ```

## Others
- Facebook: [Merchants & DEV Community](https://www.facebook.com/groups/3210496372558088)
- Blog: [CHIP Blogs](https://blog.chip-in.asia/)
