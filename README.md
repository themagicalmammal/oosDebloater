# Oxygen OS Debloater
This is a debloater for oxygen os. Though it doesn't come with many bloats there are few bloats that could be removed to increase performance and battery life.

##### Though the performance was almost the same to me battery life increased by, 30 - 80%. As before this, I was getting approximately 4 hours 30 min s.o.t and Now I am getting about 7 hours 30 min s.o.t.

# XDA
The xda page is [here](https://forum.xda-developers.com/oneplus-7/how-to/debloat-oxygen-os-debloater-t4009133)

## Requirments
1. Windows/MAC/Linux PC
2. ADB [Working!]
3. OP7/OP7 Pro

## Instructions:-
1. Connect the phone using ADB.
2. Open command prompt or PowerShell or shell or the terminal with admin permissions
3. Give adb permissions to pc. Using -
```shell
adb devices
```
4. Type
```shell
adb shell
```
5. Then use anyone of [this](https://github.com/DevilDipan/adbdebloater_op7/releases)
6. If you don't want some apps to be removed remove respective lines.
7. Done Enjoy!!!

### What if I want any app back?
#### Answer - Easy just install it from Play store or Install its Apk file.

## Testing -
1. I tested it on my OP7 on android pie beta and android 10 beta as well.
2. My friend, Nicole tested it her OP7 Pro on android 10 stable.
3. On OP7 android 10 stable by haris_94

I am using this debloater for months now and it didn't give me any issues.

Also if you want to be updated please post it or write it to me.

## Versions -

**v1**
1. Basic User and System Bloatware Removal
2. Deep Sleep Script

**v2**
1. Chrome Removed from the script
2. Oneplus Gallery Removed from the script
3. Oneplus Account Removed from the script

**v3**
1. Amazon bloatware
2. Oneplus Icons Packs
3. One plus community apps

**v3 with enabling method** *Use this if you know how to work enabling it back*
*I prefer the above one*
1. Same things as above one but has the option to unable
2. To enable use -
Code:
pm enable <package_to_enable>

**v4 both methods**
1. Removed the failures commands as posted by haris_94

**v5 changes with optional scripts**
Added a few more optional scripts

**OPTIONAL SCRIPTS**
```shell
Camera:           pm uninstall --user 0 com.oneplus.camera
Calculator:       pm uninstall --user 0 com.oneplus.calculator
Chrome:           pm uninstall --user 0 com.android.chrome
Oneplus Clock:    pm uninstall --user 0 com.oneplus.deskclock
Oneplus Gallery:  pm uninstall --user 0 com.oneplus.gallery
```

**Note**: - If you use it on any other device or make any other threads copying the code from this thread mention me and ask me before doing it. Also if you want any other devices to be on it contact me.

## Thanks for Suggestions :-<br>
[haris_94](https://forum.xda-developers.com/member.php?u=9931329)<br>
[Kinto](https://forum.xda-developers.com/member.php?u=1755710)
