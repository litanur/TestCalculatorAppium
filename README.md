# TestCalculatorAppium
Materi hari 20 kelas SQA batch 9 Juara Coding

## Perintah - perintah yang sering digunakan
* untuk melihat package

`adb shell pm list packages`

* untuk melihat activity

`adb shell dumpsys activity activities | grep "mFocused"`

* untuk reboot device

`adb shell am broadcast -a android.intent.action.BOOT_COMPLETED`