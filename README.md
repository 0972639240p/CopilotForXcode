# <img align="center" height="70" src="./Docs/AppIcon.png"/> GitHub Copilot for Xcode

<img alt="Demo of GitHub Copilot for Xcode" src="./Docs/demo.gif" width="800" />

[GitHub Copilot](https://github.com/features/copilot) is an AI pair programmer
tool that helps you write code faster and smarter. Copilot for Xcode is an Xcode
extension that provides inline coding suggestions as you type.

## Beta Preview Policy

Use of the GitHub Copilot Xcode Extension is subject to [GitHub's Pre-Release Terms](https://docs.github.com/en/site-policy/github-terms/github-pre-release-license-terms). We want to remind you that:

> Beta Previews may not be supported or may change at any time. You may receive confidential information through those programs that must remain confidential while the program is private. We'd love your feedback to make our Beta Previews better.


## Requirements

- macOS 12+
- Xcode 8+
- A GitHub Copilot subscription. To learn more, visit [https://github.com/features/copilot](https://github.com/features/copilot).

## Getting Started

1. Install via [Homebrew](https://brew.sh/):

   ```sh
   brew install --cask github-copilot-for-xcode
   ```

   Or download the `dmg` from
   [the latest release](https://github.com/github/CopilotForXcode/releases/latest/download/GitHubCopilotForXcode.dmg).
   Drag `GitHub Copilot for Xcode` into the `Applications` folder:

   <p align="center">
     <img alt="Screenshot of opened dmg" src="./Docs/dmg-open.png" width="512" />
   </p>

   Updates can be downloaded and installed by the app.

1. A background item will be added to enable Copilot to start when Xcode is opened.
   <p align="center">
     <img alt="Screenshot of background item" src="./Docs/background-item.png" width="370" />
   </p>

1. Two permissions are required: `Accessibility` and `Xcode Source Editor
   Extension`. For more on why these permissions are required see
   [TROUBLESHOOTING.md](./TROUBLESHOOTING.md).

   The first time the application is run the `Accessibility` permission should be requested:

   <p align="center">
     <img alt="Screenshot of accessibility permission request" src="./Docs/accessibility-permission-request.png" width="529" />
   </p>

   The `Xcode Source Editor Extension` permission needs to be enabled manually. Click
   `Extension Permission` from the `Copilot for Xcode` settings to open the
   System Preferences to the `Extensions` panel. Select `Xcode Source Editor`
   and enable `GitHub Copilot`:

   <p align="center">
     <img alt="Screenshot of extension permission" src="./Docs/extension-permission.png" width="582" />
   </p>

1. After granting the extension permission, please restart Xcode to ensure the
   `Github Copilot` menu is available and not disabled under the Xcode `Editor`
   menu.
    <br>
    <p align="center">
      <img alt="Screenshot of Xcode Editor GitHub Copilot menu item" src="./Docs/xcode-menu.png" width="648" />
    </p>

    Keyboard shortcuts can be set for all menu items in the `Key Bindings`
    section of Xcode preferences.

1. To sign into GitHub Copilot, click the `Sign in` button in the settings application. This will open a browser window and copy a code to the clipboard. Paste the code into the GitHub login page and authorize the application.
    <p align="center">
      <img alt="Screenshot of sign-in popup" src="./Docs/device-code.png" width="372" />
    </p>

1. To install updates, click `Check for Updates` from the menu item or in the
   settings application.

   After installing a new version, Xcode must be restarted to use the new
   version correctly.

   New versions can also be installed from `dmg` files downloaded from the
   releases page. When installing a new version via `dmg`, the application must
   be run manually the first time to accept the downloaded from the internet
   warning.

1. To avoid confusion, we recommend disabling `Predictive code completion` under
   `Xcode` > `Preferences` > `Text Editing` > `Editing`.

1. Press `tab` to accept the first line of a suggestion, hold `option` to view
   the full suggestion, and press `option` + `tab` to accept the full suggestion.

   <p align="center">
     <img alt="Screenshot of welcome screen" src="./Docs/welcome.png" width="672" />
   </p>

## License

This project is licensed under the terms of the MIT open source license. Please
refer to [LICENSE.txt](./LICENSE.txt) for the full terms.

## Privacy

We follow responsible practices in accordance with our
[Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement).

To get the latest security fixes, please use the latest version of the GitHub
Copilot for Xcode.

## Support

We’d love to get your help in making GitHub Copilot better!  If you have
feedback or encounter any problems, please reach out on our [Feedback
forum](https://github.com/orgs/community/discussions/categories/copilot).

## Acknowledgements

Thank you to @intitni for creating the original project that this is based on.

Attributions can be found under About when running the app or in
[Credits.rtf](./Copilot%20for%20Xcode/Credits.rtf).
{"app_name":"ShareExtension","timestamp":"2025-02-03 13:12:57.00 +0700","app_version":"498.0.0","slice_uuid":"4c4c4481-5555-3144-a1bb-fb4e5be75e99","adam_id":"284882215","build_version":"691089697","bundleID":"com.facebook.Facebook.ShareExtension","platform":2,"share_with_app_devs":0,"is_first_party":0,"bug_type":"309","os_version":"iPhone OS 18.2 (22C152)","roots_installed":0,"incident_id":"50E6373D-CF36-4994-AB1C-811C5AFA23B6","name":"ShareExtension"}
{
  "uptime" : 11000,
  "procRole" : "unknown",
  "version" : 2,
  "userID" : 501,
  "deployVersion" : 210,
  "modelCode" : "iPhone13,2",
  "coalitionID" : 1122,
  "osVersion" : {
    "isEmbedded" : true,
    "train" : "iPhone OS 18.2",
    "releaseType" : "User",
    "build" : "22C152"
  },
  "captureTime" : "2025-02-03 13:12:55.7813 +0700",
  "codeSigningMonitor" : 1,
  "incident" : "50E6373D-CF36-4994-AB1C-811C5AFA23B6",
  "pid" : 2855,
  "translated" : false,
  "cpuType" : "ARM-64",
  "roots_installed" : 0,
  "bug_type" : "309",
  "procLaunch" : "2025-02-03 13:10:04.0923 +0700",
  "procStartAbsTime" : 280458011067,
  "procExitAbsTime" : 284578372396,
  "procName" : "ShareExtension",
  "procPath" : "\/private\/var\/containers\/Bundle\/Application\/1A820B31-7BD3-4AAC-A694-3CCCF1DBE682\/Facebook.app\/PlugIns\/ShareExtension.appex\/ShareExtension",
  "bundleInfo" : {"CFBundleShortVersionString":"498.0.0","CFBundleVersion":"691089697","CFBundleIdentifier":"com.facebook.Facebook.ShareExtension"},
  "storeInfo" : {"itemID":"284882215","storeCohortMetadata":"10|date=1738521000000&sf=143475&pgtp=Search&pgid=07045f35-5480-4663-9f6b-b4a5cb4d9040&prpg=SearchLanding_SearchLanding&ctxt=Search&issrch=1&imptyp=card&kind=iosSoftware&lngid=35","distributorID":"com.apple.AppStore","deviceIdentifierForVendor":"87C05593-07C5-46D0-BC74-4FF5787FD1C1","softwareVersionExternalIdentifier":"871780108","applicationVariant":"1:iPhone13,2:18","thirdParty":true},
  "parentProc" : "launchd",
  "parentPid" : 1,
  "coalitionName" : "com.facebook.Facebook.ShareExtension",
  "crashReporterKey" : "9a9cd7405db99d8db2627bde271aaa86866592e5",
  "lowPowerMode" : 1,
  "appleIntelligenceStatus" : {"state":"unavailable","reasons":["notOptedIn","deviceNotCapable","unableToFetchAvailability","selectedSiriLanguageIneligible","selectedLanguageIneligible","siriAssetIsNotReady","selectedLanguageDoesNotMatchSelectedSiriLanguage","assetIsNotReady"]},
  "wasUnlockedSinceBoot" : 1,
  "isLocked" : 0,
  "throttleTimeout" : 10,
  "codeSigningID" : "com.facebook.Facebook.ShareExtension",
  "codeSigningTeamID" : "V9WTTPBFK9",
  "codeSigningFlags" : 570450689,
  "codeSigningValidationCategory" : 4,
  "codeSigningTrustLevel" : 7,
  "instructionByteStream" : {"beforePC":"ARAA1MADX9aQBYCSARAA1MADX9awBYCSARAA1MADX9bQBYCSARAA1A==","atPC":"wANf1vAFgJIBEADUwANf1hAGgJIBEADUwANf1jAGgJIBEADUwANf1g=="},
  "bootSessionUUID" : "4256542F-B05E-4846-B71B-DF69B08CF117",
  "basebandVersion" : "5.20.03",
  "exception" : {"codes":"0x0000000000000000, 0x0000000000000000","rawCodes":[0,0],"type":"EXC_CRASH","signal":"SIGKILL"},
  "termination" : {"namespace":"RUNNINGBOARD","flags":6,"code":3735883980},
  "faultingThread" : 0,
  "threads" : [{"triggered":true,"id":181707,"threadState":{"x":[{"value":268451845},{"value":21592279046},{"value":8589934592},{"value":49490908151808},{"value":0},{"value":49490908151808},{"value":2},{"value":4294967295},{"value":18446744073709550527},{"value":2},{"value":0},{"value":0},{"value":0},{"value":11523},{"value":4608},{"value":0},{"value":18446744073709551569},{"value":6880656912,"symbolLocation":56,"symbol":"clock_gettime"},{"value":0},{"value":4294967295},{"value":2},{"value":49490908151808},{"value":0},{"value":49490908151808},{"value":6170813272},{"value":8589934592},{"value":21592279046},{"value":21592279046},{"value":4412409862,"symbolLocation":26062,"symbol":"FBFeedStoryGenAIOpenThreadView"}],"flavor":"ARM_THREAD_STATE64","lr":{"value":8114183832},"cpsr":{"value":4096},"fp":{"value":6170813120},"sp":{"value":6170813040},"esr":{"value":1442840704,"description":" Address size fault"},"pc":{"value":8114169736,"matchesCrashFrame":1},"far":{"value":0}},"queue":"com.apple.main-thread","frames":[{"imageOffset":6024,"symbol":"mach_msg2_trap","symbolLocation":8,"imageIndex":3},{"imageOffset":20120,"symbol":"mach_msg2_internal","symbolLocation":80,"imageIndex":3},{"imageOffset":19888,"symbol":"mach_msg_overwrite","symbolLocation":424,"imageIndex":3},{"imageOffset":19452,"symbol":"mach_msg","symbolLocation":24,"imageIndex":3},{"imageOffset":485364,"symbol":"__CFRunLoopServiceMachPort","symbolLocation":160,"imageIndex":4},{"imageOffset":482976,"symbol":"__CFRunLoopRun","symbolLocation":1212,"imageIndex":4},{"imageOffset":819828,"symbol":"CFRunLoopRunSpecific","symbolLocation":588,"imageIndex":4},{"imageOffset":5312,"symbol":"GSEventRunModal","symbolLocation":164,"imageIndex":5},{"imageOffset":4122492,"symbol":"-[UIApplication _run]","symbolLocation":816,"imageIndex":6},{"imageOffset":85604,"symbol":"UIApplicationMain","symbolLocation":340,"imageIndex":6},{"imageOffset":114580,"symbol":"_xpc_objc_uimain","symbolLocation":224,"imageIndex":7},{"imageOffset":114064,"symbol":"_xpc_objc_main","symbolLocation":108,"imageIndex":7},{"imageOffset":123872,"symbol":"_xpc_main","symbolLocation":64,"imageIndex":7},{"imageOffset":124352,"symbol":"xpc_main","symbolLocation":64,"imageIndex":7},{"imageOffset":2061368,"symbol":"-[NSXPCListener resume]","symbolLocation":308,"imageIndex":8},{"imageOffset":103500,"imageIndex":9},{"imageOffset":103128,"imageIndex":9},{"imageOffset":102292,"imageIndex":9},{"imageOffset":104360,"imageIndex":9},{"imageOffset":26404,"symbol":"EXExtensionMain","symbolLocation":288,"imageIndex":10},{"imageOffset":2875208,"symbol":"NSExtensionMain","symbolLocation":204,"imageIndex":8},{"imageOffset":196072,"symbol":"start","symbolLocation":2724,"imageIndex":11}]},{"id":181719,"name":"com.apple.uikit.eventfetch-thread","threadState":{"x":[{"value":268451845},{"value":21592279046},{"value":8589934592},{"value":73680163962880},{"value":0},{"value":73680163962880},{"value":2},{"value":4294967295},{"value":18446744073709550527},{"value":2},{"value":0},{"value":0},{"value":0},{"value":17155},{"value":0},{"value":0},{"value":18446744073709551569},{"value":6880656912,"symbolLocation":56,"symbol":"clock_gettime"},{"value":0},{"value":4294967295},{"value":2},{"value":73680163962880},{"value":0},{"value":73680163962880},{"value":6173662584},{"value":8589934592},{"value":21592279046},{"value":21592279046},{"value":4412409862,"symbolLocation":26062,"symbol":"FBFeedStoryGenAIOpenThreadView"}],"flavor":"ARM_THREAD_STATE64","lr":{"value":8114183832},"cpsr":{"value":4096},"fp":{"value":6173662432},"sp":{"value":6173662352},"esr":{"value":1442840704,"description":" Address size fault"},"pc":{"value":8114169736},"far":{"value":0}},"frames":[{"imageOffset":6024,"symbol":"mach_msg2_trap","symbolLocation":8,"imageIndex":3},{"imageOffset":20120,"symbol":"mach_msg2_internal","symbolLocation":80,"imageIndex":3},{"imageOffset":19888,"symbol":"mach_msg_overwrite","symbolLocation":424,"imageIndex":3},{"imageOffset":19452,"symbol":"mach_msg","symbolLocation":24,"imageIndex":3},{"imageOffset":485364,"symbol":"__CFRunLoopServiceMachPort","symbolLocation":160,"imageIndex":4},{"imageOffset":482976,"symbol":"__CFRunLoopRun","symbolLocation":1212,"imageIndex":4},{"imageOffset":819828,"symbol":"CFRunLoopRunSpecific","symbolLocation":588,"imageIndex":4},{"imageOffset":170824,"symbol":"-[NSRunLoop(NSRunLoop) runMode:beforeDate:]","symbolLocation":212,"imageIndex":8},{"imageOffset":1599220,"symbol":"-[NSRunLoop(NSRunLoop) runUntilDate:]","symbolLocation":64,"imageIndex":8},{"imageOffset":4725632,"symbol":"-[UIEventFetcher threadMain]","symbolLocation":420,"imageIndex":6},{"imageOffset":1137236,"symbol":"__NSThread__start__","symbolLocation":724,"imageIndex":8},{"imageOffset":6096,"symbol":"_pthread_start","symbolLocation":136,"imageIndex":14},{"imageOffset":5248,"symbol":"thread_start","symbolLocation":8,"imageIndex":14}]},{"id":181743,"name":"com.apple.NSURLConnectionLoader","threadState":{"x":[{"value":268451845},{"value":21592279046},{"value":8589934592},{"value":280422709723136},{"value":0},{"value":280422709723136},{"value":2},{"value":4294967295},{"value":18446744073709550527},{"value":2},{"value":0},{"value":0},{"value":0},{"value":65291},{"value":3072},{"value":0},{"value":18446744073709551569},{"value":6880656912,"symbolLocation":56,"symbol":"clock_gettime"},{"value":0},{"value":4294967295},{"value":2},{"value":280422709723136},{"value":0},{"value":280422709723136},{"value":6176529720},{"value":8589934592},{"value":21592279046},{"value":21592279046},{"value":4412409862,"symbolLocation":26062,"symbol":"FBFeedStoryGenAIOpenThreadView"}],"flavor":"ARM_THREAD_STATE64","lr":{"value":8114183832},"cpsr":{"value":4096},"fp":{"value":6176529568},"sp":{"value":6176529488},"esr":{"value":1442840704,"description":" Address size fault"},"pc":{"value":8114169736},"far":{"value":0}},"frames":[{"imageOffset":6024,"symbol":"mach_msg2_trap","symbolLocation":8,"imageIndex":3},{"imageOffset":20120,"symbol":"mach_msg2_internal","symbolLocation":80,"imageIndex":3},{"imageOffset":19888,"symbol":"mach_msg_overwrite","symbolLocation":424,"imageIndex":3},{"imageOffset":19452,"symbol":"mach_msg","symbolLocation":24,"imageIndex":3},{"imageOffset":485364,"symbol":"__CFRunLoopServiceMachPort","symbolLocation":160,"imageIndex":4},{"imageOffset":482976,"symbol":"__CFRunLoopRun","symbolLocation":1212,"imageIndex":4},{"imageOffset":819828,"symbol":"CFRunLoopRunSpecific","symbolLocation":588,"imageIndex":4},{"imageOffset":991264,"symbol":"+[__CFN_CoreSchedulingSetRunnable _run:]","symbolLocation":416,"imageIndex":15},{"imageOffset":1137236,"symbol":"__NSThread__start__","symbolLocation":724,"imageIndex":8},{"imageOffset":6096,"symbol":"_pthread_start","symbolLocation":136,"imageIndex":14},{"imageOffset":5248,"symbol":"thread_start","symbolLocation":8,"imageIndex":14}]},{"id":182925,"name":"LigerEvbThread","threadState":{"x":[{"value":4},{"value":0},{"value":0},{"value":4318978048},{"value":64},{"value":0},{"value":12915945952},{"value":1},{"value":4389729980,"symbolLocation":3000,"symbol":"MCAMailboxGetPrivacyContext"},{"value":1000000},{"value":6868860181418575887},{"value":1872142487303304720},{"value":24000000},{"value":2435720},{"value":4317885352},{"value":6172519256},{"value":363},{"value":12895588864},{"value":0},{"value":4385064192},{"value":4385320960},{"value":38},{"value":4318978048},{"value":1},{"value":4385321824},{"value":4385321856},{"value":0},{"value":0},{"value":1000000}],"flavor":"ARM_THREAD_STATE64","lr":{"value":4389730064},"cpsr":{"value":536875008},"fp":{"value":6172519040},"sp":{"value":6172518912},"esr":{"value":1442840704,"description":" Address size fault"},"pc":{"value":8114197708},"far":{"value":0}},"frames":[{"imageOffset":33996,"symbol":"kevent","symbolLocation":8,"imageIndex":3},{"imageOffset":2373392,"symbol":"MCAMailboxGetPrivacyContext","symbolLocation":3084,"imageIndex":1},{"imageOffset":2370940,"symbol":"MCAMailboxGetPrivacyContext","symbolLocation":632,"imageIndex":1},{"imageOffset":2364968,"symbol":"arfx::delivery::RemoteAsset::getType() const","symbolLocation":444,"imageIndex":1},{"imageOffset":2363064,"symbol":"folly::EventBase::loopForever()","symbolLocation":200,"imageIndex":1},{"imageOffset":2362920,"symbol":"folly::EventBase::loopForever()","symbolLocation":56,"imageIndex":1},{"imageOffset":2346176,"symbol":"FBQPLGetLoggingPolicySingleton","symbolLocation":272,"imageIndex":1},{"imageOffset":1137236,"symbol":"__NSThread__start__","symbolLocation":724,"imageIndex":8},{"imageOffset":6096,"symbol":"_pthread_start","symbolLocation":136,"imageIndex":14},{"imageOffset":5248,"symbol":"thread_start","symbolLocation":8,"imageIndex":14}]},{"id":183545,"frames":[{"imageOffset":5228,"symbol":"start_wqthread","symbolLocation":0,"imageIndex":14}],"threadState":{"x":[{"value":6171373568},{"value":53087},{"value":6170836992},{"value":0},{"value":409602},{"value":18446744073709551615},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0}],"flavor":"ARM_THREAD_STATE64","lr":{"value":0},"cpsr":{"value":4096},"fp":{"value":0},"sp":{"value":6171373568},"esr":{"value":1442840704,"description":" Address size fault"},"pc":{"value":9076659308},"far":{"value":0}}},{"id":183546,"frames":[{"imageOffset":5228,"symbol":"start_wqthread","symbolLocation":0,"imageIndex":14}],"threadState":{"x":[{"value":6171947008},{"value":58427},{"value":6171410432},{"value":6171945856},{"value":5193734},{"value":1},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0}],"flavor":"ARM_THREAD_STATE64","lr":{"value":0},"cpsr":{"value":4096},"fp":{"value":0},"sp":{"value":6171945840},"esr":{"value":1442840704,"description":" Address size fault"},"pc":{"value":9076659308},"far":{"value":0}}},{"id":183585,"frames":[{"imageOffset":5228,"symbol":"start_wqthread","symbolLocation":0,"imageIndex":14}],"threadState":{"x":[{"value":6175387648},{"value":71691},{"value":6174851072},{"value":6175386496},{"value":5193732},{"value":1},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0}],"flavor":"ARM_THREAD_STATE64","lr":{"value":0},"cpsr":{"value":4096},"fp":{"value":0},"sp":{"value":6175386480},"esr":{"value":1442840704,"description":" Address size fault"},"pc":{"value":9076659308},"far":{"value":0}}},{"id":183690,"frames":[{"imageOffset":5228,"symbol":"start_wqthread","symbolLocation":0,"imageIndex":14}],"threadState":{"x":[{"value":6174240768},{"value":53511},{"value":6173704192},{"value":0},{"value":409603},{"value":18446744073709551615},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0}],"flavor":"ARM_THREAD_STATE64","lr":{"value":0},"cpsr":{"value":4096},"fp":{"value":0},"sp":{"value":6174240768},"esr":{"value":1442840704,"description":" Address size fault"},"pc":{"value":9076659308},"far":{"value":0}}},{"id":183936,"frames":[{"imageOffset":5228,"symbol":"start_wqthread","symbolLocation":0,"imageIndex":14}],"threadState":{"x":[{"value":6173093888},{"value":88859},{"value":6172557312},{"value":6173092736},{"value":5193732},{"value":1},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0}],"flavor":"ARM_THREAD_STATE64","lr":{"value":0},"cpsr":{"value":4096},"fp":{"value":0},"sp":{"value":6173092720},"esr":{"value":1442840704,"description":" Address size fault"},"pc":{"value":9076659308},"far":{"value":0}}}],
  "usedImages" : [
  {
    "source" : "P",
    "arch" : "arm64",
    "base" : 4296065024,
    "size" : 704512,
    "uuid" : "4c4c4481-5555-3144-a1bb-fb4e5be75e99",
    "path" : "\/private\/var\/containers\/Bundle\/Application\/1A820B31-7BD3-4AAC-A694-3CCCF1DBE682\/Facebook.app\/PlugIns\/ShareExtension.appex\/ShareExtension",
    "name" : "ShareExtension"
  },
  {
    "source" : "P",
    "arch" : "arm64",
    "base" : 4387356672,
    "size" : 45531136,
    "uuid" : "4c4c4437-5555-3144-a1d4-b9fd041b4935",
    "path" : "\/private\/var\/containers\/Bundle\/Application\/1A820B31-7BD3-4AAC-A694-3CCCF1DBE682\/Facebook.app\/Frameworks\/FBSharedFramework.framework\/FBSharedFramework",
    "name" : "FBSharedFramework"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 4299702272,
    "size" : 49152,
    "uuid" : "be056522-26b1-3a50-8ad1-93ac99fcdc9c",
    "path" : "\/private\/preboot\/Cryptexes\/OS\/usr\/lib\/libobjc-trampolines.dylib",
    "name" : "libobjc-trampolines.dylib"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 8114163712,
    "size" : 237540,
    "uuid" : "e3965df1-a3a3-374a-94ea-f86739c5cc8e",
    "path" : "\/usr\/lib\/system\/libsystem_kernel.dylib",
    "name" : "libsystem_kernel.dylib"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 6748536832,
    "size" : 5521408,
    "uuid" : "6a60be13-e657-3bec-a9ac-ba239ae29862",
    "path" : "\/System\/Library\/Frameworks\/CoreFoundation.framework\/CoreFoundation",
    "name" : "CoreFoundation"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 8042741760,
    "size" : 36864,
    "uuid" : "f4e7a885-f491-3721-862d-c57403f4d821",
    "path" : "\/System\/Library\/PrivateFrameworks\/GraphicsServices.framework\/GraphicsServices",
    "name" : "GraphicsServices"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 6790610944,
    "size" : 32595968,
    "uuid" : "f80c6ee4-50ca-346f-90eb-bb3da9817503",
    "path" : "\/System\/Library\/PrivateFrameworks\/UIKitCore.framework\/UIKitCore",
    "name" : "UIKitCore"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 9076961280,
    "size" : 294912,
    "uuid" : "d7329e6b-e59d-39d9-aae1-eed096a3ec21",
    "path" : "\/usr\/lib\/system\/libxpc.dylib",
    "name" : "libxpc.dylib"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 6727585792,
    "size" : 13832192,
    "uuid" : "7274dde3-68d6-34a0-8e67-7726e1265e80",
    "path" : "\/System\/Library\/Frameworks\/Foundation.framework\/Foundation",
    "name" : "Foundation"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 7567605760,
    "size" : 237568,
    "uuid" : "767a7cce-0e9e-3bdd-bdcb-180c539075ed",
    "path" : "\/System\/Library\/PrivateFrameworks\/PlugInKit.framework\/PlugInKit",
    "name" : "PlugInKit"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 7003967488,
    "size" : 782336,
    "uuid" : "a5e09905-3e91-3d0b-9d06-4217245f69f8",
    "path" : "\/System\/Library\/Frameworks\/ExtensionFoundation.framework\/ExtensionFoundation",
    "name" : "ExtensionFoundation"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 7388614656,
    "size" : 536896,
    "uuid" : "4eb7459f-e237-38ce-8240-3f3e2e1ce5ab",
    "path" : "\/usr\/lib\/dyld",
    "name" : "dyld"
  },
  {
    "size" : 0,
    "source" : "A",
    "base" : 0,
    "uuid" : "00000000-0000-0000-0000-000000000000"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 6880616448,
    "size" : 524284,
    "uuid" : "8d425c72-57c9-3e54-a1e1-e243cbdfc446",
    "path" : "\/usr\/lib\/system\/libsystem_c.dylib",
    "name" : "libsystem_c.dylib"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 9076654080,
    "size" : 53236,
    "uuid" : "b2fe0dfa-67de-3d72-8267-6c42073e0e8d",
    "path" : "\/usr\/lib\/system\/libsystem_pthread.dylib",
    "name" : "libsystem_pthread.dylib"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 6770511872,
    "size" : 3952640,
    "uuid" : "99878792-4064-3260-b5b2-779a99b9f64e",
    "path" : "\/System\/Library\/Frameworks\/CFNetwork.framework\/CFNetwork",
    "name" : "CFNetwork"
  }
],
  "sharedCache" : {
  "base" : 6702858240,
  "size" : 4381753344,
  "uuid" : "d86e7e90-f409-3146-8958-f6d26a4e0fdc"
},
  "vmSummary" : "ReadOnly portion of Libraries: Total=1.7G resident=0K(0%) swapped_out_or_unallocated=1.7G(100%)\nWritable regions: Total=577.4M written=578K(0%) resident=578K(0%) swapped_out=0K(0%) unallocated=576.8M(100%)\n\n                                VIRTUAL   REGION \nREGION TYPE                        SIZE    COUNT (non-coalesced) \n===========                     =======  ======= \nActivity Tracing                   256K        1 \nAudio                               64K        1 \nCG raster data                    4032K       34 \nColorSync                          608K       29 \nCoreAnimation                     1152K       20 \nFoundation                         272K        2 \nImage IO                          3344K       66 \nKernel Alloc Once                   32K        1 \nMALLOC                           557.0M       21 \nMALLOC guard page                   32K        2 \nSQLite page cache                 1024K        8 \nSTACK GUARD                        144K        9 \nStack                             5360K        9 \nVM_ALLOCATE                        352K        5 \n__AUTH                            7871K      682 \n__AUTH_CONST                     104.1M     1289 \n__CTF                               824        1 \n__DATA                            54.7M     1227 \n__DATA_CONST                      37.6M     1300 \n__DATA_DIRTY                      10.7M     1159 \n__FONT_DATA                        2352        1 \n__INFO_FILTER                         8        1 \n__LINKEDIT                       208.0M        4 \n__LLVM_COV                          10K        1 \n__OBJC_RW                         2963K        1 \n__RODATA                          16.6M        2 \n__TEXT                             1.5G     1317 \n__TPRO_CONST                       272K        2 \nlibnetwork                        5760K       32 \nmapped file                      353.8M       73 \nowned unmapped memory             1184K        1 \npage table in kernel               578K        1 \nshared memory                       80K        4 \n===========                     =======  ======= \nTOTAL                              2.9G     7306 \n",
  "legacyInfo" : {
  "threadTriggered" : {
    "queue" : "com.apple.main-thread"
  }
},
  "logWritingSignature" : "924bd38e412bf22309e49a833c85400eb95b3af5",
  "trialInfo" : {
  "rollouts" : [
    {
      "rolloutId" : "645eb1d0417dab722a215927",
      "factorPackIds" : {
        "SIRI_VALUE_INFERENCE_SIRI_REMEMBERS" : "645eb2f7417dab722a215928"
      },
      "deploymentId" : 240000005
    },
    {
      "rolloutId" : "601074e4af9bef000c169ea8",
      "factorPackIds" : {
        "BIFROST_DEV_1" : "679d0af2a9fa7c6c84408846"
      },
      "deploymentId" : 240004340
    }
  ],
  "experiments" : [

  ]
}
}
