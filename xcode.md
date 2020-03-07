# Apple Xcode Installer Checksums


## What?

SHA1 checksums of Apple's installers for:

 * [Mac OSX InstallESD.dmg](readme.md)
 * [Xcode Installer DMGs](xcode.md)

## Why?

Strong cryptography makes us all safer.

## How do I verify SHA1 checksums?

OSX have `shasum`, Linux & others: `openssl sha1`:

````
shasum whatever.xip
openssl sha1 whatever.xip
````

<!-- For SHA256: `shasum -a 256 whatever.xip` -->

## How do I help?

Got access to old versions of Apple installers you know are legit? Submit some hashes in a pull request.

## See also:

* [Stack overflow: How to download Xcode DMG](https://stackoverflow.com/questions/10335747/how-to-download-xcode-dmg-or-xip-file/10335943#10335943)

### Xcode Installers

| Version                           | Hashes                            |
| --------------------------------- | --------------------------------- |
| Xcode 11.4 beta 3 (11N132i)<br>[Xcode_11.4_beta_3.xip][11.4 beta 3]<br>macOS 10.15.2+ | `MD5= 09310782f54df63954cf593e34b4355e`<br>`SHA1= 6fdfcf4e915fa54cfffba828fb5f314caeb37b13`<br>`SHA256= abe0dcfc743fb63acd15b52725ee4334c5281caa46dfb890dc36b3817a026abc`
| Xcode 11.4 beta 2 (11N123k)<br>[Xcode_11.4_beta_2.xip][11.4 beta 2]<br>macOS 10.15.2+ | `MD5= 839559f1f9c16c5f930cf58f5659b6a5`<br>`SHA1= a55e450133c2d49e1986f33026768fe8dbb223aa`<br>`SHA256= 0b466ce26b9982c61b1d1650b2ba5d59fc5eed82bb9ccf15c8ce45ab7146848d`
| Xcode 11.4 beta (11N111s)<br>[Xcode_11.4_beta.xip][11.4 beta]<br>macOS 10.15.2+ | `MD5= 32201e27103b28dca071aac990879d70`<br>`SHA1= 14e4e508734112a8f582d58651e1b0459bc575ec`<br>`SHA256= fa9a89b96f8dc489fc8fbb5d39123db8b7290b41f57de88137d5a9783a5f710d`

[11.4 beta 3]: https://download.developer.apple.com/Developer_Tools/Xcode_11.4_beta_3/Xcode_11.4_beta_3.xip
[11.4 beta 2]: https://download.developer.apple.com/Developer_Tools/Xcode_11.4_beta_2/Xcode_11.4_beta_2.xip
[11.4 beta]: https://download.developer.apple.com/Developer_Tools/Xcode_11.4_beta/Xcode_11.4_beta.xip
[11.3.1]: https://download.developer.apple.com/Developer_Tools/Xcode_11.3.1/Xcode_11.3.1.xip
[11.3]: https://download.developer.apple.com/Developer_Tools/Xcode_11.3/Xcode_11.3.xip
[11.3 beta]: https://download.developer.apple.com/Developer_Tools/Xcode_11.3_beta/Xcode_11.3_beta.xip
[11.2.1]: https://download.developer.apple.com/Developer_Tools/Xcode_11.2.1/Xcode_11.2.1.xip
[11.2.1 GM Seed]: https://download.developer.apple.com/Developer_Tools/Xcode_11.2.1_GM_Seed/Xcode_11.2.1_GM_Seed.xip
[11.2]: https://download.developer.apple.com/Developer_Tools/Xcode_11.2/Xcode_11.2.xip
[11.2 beta 2]: https://download.developer.apple.com/Developer_Tools/Xcode_11.2_beta_2/Xcode_11.2_beta_2.xip
[11.2 beta]: https://download.developer.apple.com/Developer_Tools/Xcode_11.2_beta/Xcode_11.2_beta.xip
[11.1]: https://download.developer.apple.com/Developer_Tools/Xcode_11.1/Xcode_11.1.xip
[11.1 GM Seed]: https://download.developer.apple.com/Developer_Tools/Xcode_11.1_GM_Seed/Xcode_11.1_GM_Seed.xip
[11]: https://download.developer.apple.com/Developer_Tools/Xcode_11/Xcode_11.xip
[11 GM]: https://download.developer.apple.com/Developer_Tools/Xcode_11_GM_Seed/Xcode_11_GM_Seed.xip
[11 Beta 7]: https://download.developer.apple.com/Developer_Tools/Xcode_11_Beta_7/Xcode_11_Beta_7.xip
[11 Beta 6]: https://download.developer.apple.com/Developer_Tools/Xcode_11_Beta_6/Xcode_11_Beta_6.xip
[11 Beta 5]: https://download.developer.apple.com/Developer_Tools/Xcode_11_Beta_5/Xcode_11_Beta_5.xip
[11 Beta 4]: https://download.developer.apple.com/Developer_Tools/Xcode_11_Beta_4/Xcode_11_Beta_4.xip
[11 Beta 3]: https://download.developer.apple.com/Developer_Tools/Xcode_11_Beta_3/Xcode_11_Beta_3.xip
[11 Beta 2]: https://download.developer.apple.com/Developer_Tools/Xcode_11_Beta_2/Xcode_11_Beta_2.xip
[11 Beta]: https://download.developer.apple.com/WWDC_2019/Xcode_11_Beta/Xcode_11_Beta.xip
[10.3]: https://download.developer.apple.com/Developer_Tools/Xcode_10.3/Xcode_10.3.xip
[10.2.1]: https://download.developer.apple.com/Developer_Tools/Xcode_10.2.1/Xcode_10.2.1.xip
[10.2]: https://download.developer.apple.com/Developer_Tools/Xcode_10.2/Xcode_10.2.xip
[10.1]: https://download.developer.apple.com/Developer_Tools/Xcode_10.1/Xcode_10.1.xip
[10]: https://download.developer.apple.com/Developer_Tools/Xcode_10/Xcode_10.xip
[10 GM]: https://download.developer.apple.com/Developer_Tools/Xcode_10_GM_seed/Xcode_10_GM_seed.xip
[10 Beta 6]: https://download.developer.apple.com/Developer_Tools/Xcode_10_Beta_6/Xcode_10_Beta_6.xip
[10 Beta 5]: https://download.developer.apple.com/Developer_Tools/Xcode_10_beta_5/Xcode_10_beta_5.xip
[10 Beta 4]: https://download.developer.apple.com/Developer_Tools/Xcode_10_beta_4/Xcode_10_beta_4.xip
[10 Beta 3]: https://download.developer.apple.com/Developer_Tools/Xcode_10_beta_3/Xcode_10_beta_3.xip
[10 Beta 2]: https://download.developer.apple.com/Developer_Tools/Xcode_10_Beta_2/Xcode_10_Beta_2.xip
[10 Beta]: https://download.developer.apple.com/Developer_Tools/Xcode_10_Beta/Xcode_10_Beta.xip
[9.4.1]: https://download.developer.apple.com/Developer_Tools/Xcode_9.4.1/Xcode_9.4.1.xip
[9.4]: https://download.developer.apple.com/Developer_Tools/Xcode_9.4/Xcode_9.4.xip
[9.3.1]: https://download.developer.apple.com/Developer_Tools/Xcode_9.3.1/Xcode_9.3.1.xip
[9.3]: https://download.developer.apple.com/Developer_Tools/Xcode_9.3/Xcode_9.3.xip
[9.2]: https://download.developer.apple.com/Developer_Tools/Xcode_9.2/Xcode_9.2.xip
[9.1]: https://download.developer.apple.com/Developer_Tools/Xcode_9.1/Xcode_9.1.xip
[9.1b1]: https://download.developer.apple.com/Developer_Tools/Xcode_9.1_beta/Xcode_9.1_beta.xip
[9.0.1]: https://download.developer.apple.com/Developer_Tools/Xcode_9.0.1/Xcode_9.0.1.xip
[9]: https://download.developer.apple.com/Developer_Tools/Xcode_9/Xcode_9.xip
[9b6]: https://download.developer.apple.com/Developer_Tools/Xcode_9_beta_6/Xcode_9_beta_6.xip
[9b5]: https://download.developer.apple.com/Developer_Tools/Xcode_9_beta_5/Xcode_9_beta_5.xip
[9b4]: http://adcdownload.apple.com/Developer_Tools/Xcode_9_beta_4/Xcode_9_beta_4.xip
[9b3]: http://adcdownload.apple.com/Developer_Tools/Xcode_9_beta_3/Xcode_9_beta_3.xip
[9b2]: http://adcdownload.apple.com/Developer_Tools/Xcode_9_beta_2/Xcode_9_beta_2.xip
[9b1]: http://adcdownload.apple.com/WWDC_2017/Xcode_9_beta/Xcode_9_beta.xip
[8.3.3]: http://adcdownload.apple.com/Developer_Tools/Xcode_8.3.3/Xcode8.3.3.xip
[8.3.2]: http://adcdownload.apple.com/Developer_Tools/Xcode_8.3.2/Xcode8.3.2.xip
[8.3.1]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/Xcode_8.3.1/Xcode_8.3.1.xip
[8.3]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/Xcode_8.3/Xcode_8.3.xip
[8.2.1]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/Xcode_8.2.1/Xcode_8.2.1.xip
[8.2]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/Xcode_8.2/Xcode_8.2.xip
[8.1]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/Xcode_8.1/Xcode_8.1.xip
[8]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/Xcode_8/Xcode_8.xip
[7.3.1]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/Xcode_7.3.1/Xcode_7.3.1.dmg
[7.3]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/Xcode_7.3/Xcode_7.3.dmg
[7.2.1]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/Xcode_7.2.1/Xcode_7.2.1.dmg
[7.2]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/Xcode_7.2/Xcode_7.2.dmg
[7.1.1]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/Xcode_7.1.1/Xcode_7.1.1.dmg
[7.1]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/Xcode_7.1/Xcode_7.1.dmg
[7.0.1]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/Xcode_7.0.1/Xcode_7.0.1.dmg
[7]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/Xcode_7/Xcode_7.dmg
[6.4]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/Xcode_6.4/Xcode_6.4.dmg
[6.3.2]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/Xcode_6.3.2/Xcode_6.3.2.dmg
[6.3.1]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/Xcode_6.3.1/Xcode_6.3.1.dmg
[6.3]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/Xcode_6.3/Xcode_6.3.dmg
[6.2]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/Xcode_6.2/Xcode_6.2.dmg
[6.1.1]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/xcode_6.1.1/xcode_6.1.1.dmg
[6.1]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/xcode_6.1/56841_xcode_6.1.dmg
[6.0.1]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/xcode_6.0.1/xcode_6.0.1.dmg
[5.1.1]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/xcode_5.1.1/xcode_5.1.1.dmg
[5.0.2]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/xcode_5.0.2/xcode_5.0.2.dmg
[4.6.3]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/xcode_4.6.3/xcode4630916281a.dmg
[4.6]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/xcode_4.6/xcode460417218a.dmg
[4.5.2]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/xcode_4.5.2/xcode4520418508a.dmg
[4.4.1]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/xcode_4.4.1/xcode_4.4.1_6938145.dmg
[4.3.2]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/xcode_4.3.2/xcode_432_lion.dmg
[4.2]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/xcode_4.2_for_lion_21264/installxcode_42_lion.dmg
[4.1]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/xcode_4.1_for_lion_21263/installxcode_41_lion.dmg
[4.0.2]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/xcode_4.0.2_and_ios_sdk_4.3/xcode_4.0.2_and_ios_sdk_4.3.dmg
[3.2.6]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/xcode_3.2.6_and_ios_sdk_4.3__final/xcode_3.2.6_and_ios_sdk_4.3.dmg
[3.1.4]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/xcode_3.1.4_developer_tools/xcode314_2809_developerdvd.dmg
[3.0]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/xcode_3.0/xcode_3.0.dmg
[2.5]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/xcode_2.5_developer_tools/xcode25_8m2558_developerdvd.dmg
[2.4.1]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/xcode_2.4.1/xcode_2.4.1_8m1910_6936315.dmg
[2.4]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/xcode_2.4/xcode_2.4_8k1079_6936199.dmg
[2.3]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/xcode_2.3/xcode_2.3_8m1780_oz693620813.dmg
[2.2.1]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/xcode_tools_2.2.1/xcode_2.2.1_8g1165_018213632.dmg
[1.5]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/xcode_v1.5/xcode_tools_1.5_cd.dmg.bin
[1.0]: https://developer.apple.com/devcenter/download.action?path=/Mac_OS_X/Mac_OS_X_10.3_Build_7B85/7B85_Xcode_CD.dmg

### Xcode Command Line Tools

| SHA1 | Version | Filename |
| ------- | ---- | -------- |
| `f1aeb8cc3cc0092e3fcd569f1bd9234d9c25d666` | [CLI Tools 9.3 beta (10.13)][cli-9.3b1-10.13] | Command_Line_Tools_macOS_10.13_for_Xcode_9.3_beta.dmg <!-- c0a24e883086bf47c8211f10e80803585f99cbb42074f378e602071ab39011c2 -->
| `5a6f9d1eb02bce4f522e6f93e22713a94daa600d` | [CLI Tools 6.1.1 (10.10)][cli-6.1.1-10.10] | commandlinetoolsosx10.10forxcode6.1.1.dmg
| `662746e2cf6788f9add7fab80aa28c2f5462d665` | [CLI Tools 6.1.1 (10.9)][cli-6.1.1-10.9] | commandlinetoolsosx10.9forxcode6.1.1.dmg

 [cli-6.1.1-10.9]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/command_line_tools_os_x_10.9_for_xcode__xcode_6.1.1/commandlinetoolsosx10.9forxcode6.1.1.dmg
 [cli-6.1.1-10.10]: https://developer.apple.com/devcenter/download.action?path=/Developer_Tools/command_line_tools_os_x_10.10_for_xcode__xcode_6.1.1/commandlinetoolsosx10.10forxcode6.1.1.dmg
 [cli-9.3b1-10.13]: https://download.developer.apple.com/Developer_Tools/Command_Line_Tools_macOS_10.13_for_Xcode_9.3/Command_Line_Tools_macOS_10.13_for_Xcode_9.3_beta.dmg
