# 26.6.1 (23G82) .vs 26.6.1 (23G83)

## Inputs

- `iPhone18,1_26.6.1_23G82_Restore.ipsw`
- `iPhone18,1_26.6.1_23G83_Restore.ipsw`

## Kernel

### Version

| iOS | Version | Build | Date |
| :-- | :------ | :---- | :--- |
| 26.6.1 *(23G82)* | 25.6.0 | 12377.162.14~4 | Thu, 30Jul2026 12:43:49 PDT |
| 26.6.1 *(23G83)* | 25.6.0 | 12377.162.14~4 | Thu, 30Jul2026 12:43:49 PDT |

_Kernelcache functionally unchanged; KEXT diff skipped._

## MachO

### filesystem

#### ⬆️ Updated (1)

- [/private/var/staged_system_apps/MobileSafari.app/PlugIns/SafariWidgetExtension.appex/SafariWidgetExtension](MACHOS/filesystem/private/var/staged_system_apps/MobileSafari.app/PlugIns/SafariWidgetExtension.appex/SafariWidgetExtension.md)

### SystemOS

#### ⬆️ Updated (1)

- [/System/Library/PrivateFrameworks/SafariShared.framework/XPCServices/com.apple.Safari.SearchHelper.xpc/com.apple.Safari.SearchHelper](MACHOS/SystemOS/System/Library/PrivateFrameworks/SafariShared.framework/XPCServices/com.apple.Safari.SearchHelper.xpc/com.apple.Safari.SearchHelper.md)

### AppOS

#### ⬆️ Updated (2)

- [/usr/libexec/AuthenticationServicesAgent](MACHOS/AppOS/usr/libexec/AuthenticationServicesAgent.md)
- [/usr/libexec/browserkitd](MACHOS/AppOS/usr/libexec/browserkitd.md)

### 🔑 Entitlements

- [Entitlements DIFF](Entitlements.md)

### iBoot

| iOS | Version |
| :-- | :------ |
| 26.6.1 *(23G82)* | mBoot-18000.162.10 |
| 26.6.1 *(23G83)* | mBoot-18000.162.10 |

## DSC

### WebKit

| iOS | Version |
| :-- | :------ |
| 26.6.1 *(23G82)* | 624.5.1.10.1 |
| 26.6.1 *(23G83)* | 624.5.1.10.3 |

### Dylibs

#### ⬆️ Updated (3)

- [/System/Library/Frameworks/WebKit.framework/WebKit](DYLIBS/System/Library/Frameworks/WebKit.framework/WebKit.md)
- [/System/Library/PrivateFrameworks/AuthenticationServicesCore.framework/AuthenticationServicesCore](DYLIBS/System/Library/PrivateFrameworks/AuthenticationServicesCore.framework/AuthenticationServicesCore.md)
- [/System/Library/PrivateFrameworks/SafariShared.framework/SafariShared](DYLIBS/System/Library/PrivateFrameworks/SafariShared.framework/SafariShared.md)

## EOF
