# Trusty Trail Configuration

Here are described all the categories and actions that **[Trusty Trail](https://routinehub.co/shortcut/21305/)** considers suspicious.

---
## Navigation
- [Trusty Trail Configuration](#trusty-trail-configuration)
  - [Navigation](#navigation)
  - [List of Categories](#list-of-categories)
  - [List of Suspicious Actions](#list-of-suspicious-actions)

---
## List of Categories

1. 🔴 [Accessibility Settings](#accessibility-settings)
2. 🔴 Passwords
3. 🔴 Apple Pay
4. 🔴 Information About the User
5. 🔴 Device Management
6. 🔴 Home Controls
7. 🟠 Messages and Calls
8. 🟠 Apps Settings
9. 🟠 Freeform Boards
10. 🟠 Communication Management
11. 🟠 Files
12. 🟠 Reminders
13. 🟠 Journal
14. 🟠 Shortcuts
15. 🟠 Notes
16. 🟠 Photos
17. 🟠 Health Data
18. 🟠 Voice Memos
19. 🟡 Controls Management
20. 🟡 Web

---
## List of Suspicious Actions
### 🔴 Accessibility Settings

* **Set LED Flash** 
```com.apple.AccessibilityUtilities.AXSettingsShortcuts.AXToggleLEDFlashIntent```
* **Change Backgound Sound** 
```com.apple.AccessibilityUtilities.AXSettingsShortcuts.AXSetBackgroundSoundIntent```
* **Set Mono Audio** 
```com.apple.AccessibilityUtilities.AXSettingsShortcuts.AXToggleMonoAudioIntent```
* **Set Audio Descriptions** 
```com.apple.AccessibilityUtilities.AXSettingsShortcuts.AXToggleAudioDescriptionsIntent```
* **Set Closed Captions+SDH** 
```com.apple.AccessibilityUtilities.AXSettingsShortcuts.AXToggleCaptionsIntent```
* **Set Sound Recognition** 
```com.apple.AccessibilityUtilities.AXSettingsShortcuts.AXToggleSoundDetectionIntent```
* **Set Zoom** 
```com.apple.AccessibilityUtilities.AXSettingsShortcuts.AXToggleZoomIntent```
* **Set Background Sounds** 
```com.apple.AccessibilityUtilities.AXSettingsShortcuts.AXToggleBackgroundSoundsIntent```
* **Set Classic Invert** 
```com.apple.AccessibilityUtilities.AXSettingsShortcuts.AXToggleClassicInvertIntent```
* **Set Increase Contrast** 
```com.apple.AccessibilityUtilities.AXSettingsShortcuts.AXToggleContrastIntent```
* **Set Live Captions** 
```com.apple.AccessibilityUtilities.AXSettingsShortcuts.AXToggleLiveCaptionsIntent```
* **Set VoiceOver** 
```com.apple.AccessibilityUtilities.AXSettingsShortcuts.AXToggleVoiceOverIntent```
* **Set Auto-Answer Calls** 
```com.apple.AccessibilityUtilities.AXSettingsShortcuts.AXToggleAutoAnswerCallsIntent```
* **Set Background Sounds Volume** 
```com.apple.AccessibilityUtilities.AXSettingsShortcuts.AXSetBackgroundSoundVolumeIntent```
* **Set Text Size** 
```com.apple.AccessibilityUtilities.AXSettingsShortcuts.AXSetLargeTextIntent```
* **Set Smart Invert** 
```com.apple.AccessibilityUtilities.AXSettingsShortcuts.AXToggleSmartInvertIntent```
* **Set Color Filters** 
```com.apple.AccessibilityUtilities.AXSettingsShortcuts.AXToggleColorFiltersIntent```
* **Set Left/Right Balance** 
```com.apple.AccessibilityUtilities.AXSettingsShortcuts.AXSetLeftRightBalanceIntent```
* **Set Voice Control** 
```com.apple.AccessibilityUtilities.AXSettingsShortcuts.AXToggleVoiceControlIntent```
* **Set AssistiveTouch** 
```com.apple.AccessibilityUtilities.AXSettingsShortcuts.AXToggleAssistiveTouchIntent```
* **Set White Point** 
```com.apple.AccessibilityUtilities.AXSettingsShortcuts.AXToggleWhitePointIntent```
* **Set Switch Control** 
```com.apple.AccessibilityUtilities.AXSettingsShortcuts.AXToggleSwitchControlIntent```
* **Set Reduce Motion** 
```com.apple.AccessibilityUtilities.AXSettingsShortcuts.AXToggleReduceMotionIntent```
* **Set Reduce Transparency** 
```com.apple.AccessibilityUtilities.AXSettingsShortcuts.AXToggleTransparencyIntent```

### 🔴 Passwords

* **Set Hotspot Password** 
```is.workflow.actions.personalhotspot.password.set```
* **Get Personal Hotspot Password** 
```is.workflow.actions.personalhotspot.password.get```

### 🔴 Apple Pay

* **Send Payment** 
```is.workflow.actions.venmo.pay```
* **Request Payment** 
```is.workflow.actions.venmo.request```

### 🔴 Information About the User

* **Get Battery Status** 
```is.workflow.actions.getbatterylevel```
* **Get Current Location** 
```is.workflow.actions.getcurrentlocation```
* **Get Clipboard** 
```is.workflow.actions.getclipboard```
* **Get Current Focus** 
```is.workflow.actions.dnd.getfocus```
* **Get Device Details** 
```is.workflow.actions.getdevicedetails```
* **Get Elevation** 
```com.sindresorhus.Actions.GetElevation```
* **Get User Details** 
```com.sindresorhus.Actions.GetUserDetailsIntent```
* **Get Current IP Address** 
```is.workflow.actions.getipaddress```
* **Get Orientation** 
```com.apple.ShortcutsActions.GetOrientationAction```
* **Find Contacts** 
```is.workflow.actions.filter.contacts```
* **Get Device Orientation** 
```com.sindresorhus.Actions.GetDeviceOrientationIntent```
* **Get Extended Device Details** 
```com.sindresorhus.Actions.GetDeviceDetailsExtended```
* **Get Nearby Bluetooth Devices** 
```com.sindresorhus.Actions.GetBluetoothDevices```
* **Get Physical Activity** 
```com.apple.ShortcutsActions.GetPhysicalActivity```
* **Get Device Details** 
```DeviceDetails```
* **Get Battery State** 
```com.sindresorhus.Actions.GetBatteryStateIntent```
* **Get Clipboard** 
```Clipboard```
* **Find Cellular Plan** 
```com.apple.ShortcutsActions.CellularPlanEntity```

### 🔴 Device Management

* **Set Wallpaper Photo** 
```is.workflow.actions.wallpaper.set```
* **Shut Down** 
```is.workflow.actions.reboot```
* **Play Sound** 
```is.workflow.actions.playsound```
* **Open App** 
```is.workflow.actions.openapp```
* **Go to Home Screen** 
```is.workflow.actions.returntohomescreen```
* **Lock Screen** 
```is.workflow.actions.lockscreen```
* **Vibrate Device** 
```is.workflow.actions.vibrate```

### 🔴 Home Controls

* **Toogle Accessory or Scene** 
```com.apple.Home.ToggleIntent```
* **Control Home** 
```is.workflow.actions.homeaccessory```

### 🟠 Messages and Calls

* **Call** 
```com.apple.mobilephone.call```
* **Send Message** 
```is.workflow.actions.sendmessage```
* **Call with FaceTime** 
```com.apple.facetime.facetime```
* **Send Email** 
```is.workflow.actions.sendemail```

### 🟠 Apps Settings

* **Change Safari Settings** 
```com.apple.mobilesafari.WFAppSettingEntityUpdaterAction```
* **Change Books Settings** 
```com.apple.iBooks.WFAppSettingEntityUpdaterAction```
* **Change Voice Memos Settings** 
```com.apple.VoiceMemos.WFAppSettingEntityUpdaterAction```
* **Change Calendar Settings** 
```com.apple.mobilecal.WFAppSettingEntityUpdaterAction```
* **Change Freeform Settings** 
```com.apple.freeform.WFAppSettingEntityUpdaterAction```
* **Change Weather Settings** 
```com.apple.weather.WFAppSettingEntityUpdaterAction```
* **Change Recording Playback Setting** 
```com.apple.VoiceMemos.ChangeRecordingPlaybackSetting```
* **Change Reminders Settings** 
```com.apple.reminders.WFAppSettingEntityUpdaterAction```
* **Change News Settings** 
```com.apple.news.WFAppSettingEntityUpdaterAction```
* **Change Notes Setting** 
```com.apple.mobilenotes.ChangeSettingLinkAction```

### 🟠 Freeform Boards

* **Delete Boards** 
```com.apple.freeform.CRLDeleteBoardIntent```

### 🟠 Communication Management

* **Set Cellular Data** 
```is.workflow.actions.cellulardata.set```
* **Set Airplane Mode** 
```is.workflow.actions.airplanemode.set```
* **Set Personal Hotspot** 
```is.workflow.actions.personalhotspot.set```
* **Set Wi-Fi** 
```is.workflow.actions.wifi.set```
* **Set AirDrop Receiving** 
```is.workflow.actions.setairdropreceiving```
* **Set VPN** 
```is.workflow.actions.vpn.set```
* **Set Voice & Data** 
```com.apple.ShortcutsActions.SetVoiceDataModeAction```
* **Set Data Roaming** 
```com.apple.ShortcutsActions.SetDataRoamingAction```
* **Reset Cellular Data Statistics** 
```com.apple.ShortcutsActions.ResetCellularDataStatisticsAction```
* **Set Default Line** 
```com.apple.ShortcutsActions.SetDefaultCellularPlanAction```
* **Get Network Details** 
```is.workflow.actions.getwifi```

### 🟠 Files

* **Overwrite File** 
```com.sindresorhus.Actions.OverwriteFile```
* **Get Public Link To File** 
```is.workflow.actions.file.getlink```
* **Get File From Folder** 
```is.workflow.actions.documentpicker.open```
* **Get Contents Of Folder** 
```is.workflow.actions.file.getfoldercontents```
* **Delete Files** 
```is.workflow.actions.file.delete```

### 🟠 Reminders

* **Remove Reminders** 
```is.workflow.actions.removereminders```
* **Find Reminders** 
```is.workflow.actions.filter.reminders```

### 🟠 Journal

* **Search Journal Entries** 
```com.apple.journal.SearchEntriesIntent```

### 🟠 Shortcuts

* **Get Shortcuts** 
```is.workflow.actions.getmyworkflows```
* **Create iCloud Link For Shortcut** 
```com.apple.shortcuts.CreateShortcutiCloudLinkAction```
* **Delete Shortcuts** 
```com.apple.shortcuts.DeleteWorkflowAction```

### 🟠 Notes

* **Delete Folders From Notes** 
```com.apple.mobilenotes.DeleteFoldersLinkAction```
* **Delete Notes** 
```com.apple.mobilenotes.DeleteNotesLinkAction```
* **Find Notes** 
```is.workflow.actions.filter.notes```
* **Delete Tags From Notes** 
```com.apple.mobilenotes.DeleteTagsLinkAction```
* **Remove Tags From Notes** 
```com.apple.mobilenotes.RemoveTagsFromNotesLinkAction```

### 🟠 Photos

* **Get Latest Live Photos** 
```is.workflow.actions.getlatestlivephotos```
* **Take Photo** 
```is.workflow.actions.takephoto```
* **Find Photos** 
```is.workflow.actions.filter.photos```
* **Take Video** 
```is.workflow.actions.takevideo```
* **Take Screenshot** 
```is.workflow.actions.takescreenshot```
* **Get All Wallpapers** 
```is.workflow.actions.posters.get```
* **Remove From Photo Album** 
```is.workflow.actions.removefromalbum```
* **Get Latest Screenshots** 
```is.workflow.actions.getlastscreenshot```
* **Get Latest Videos** 
```is.workflow.actions.getlastvideo```
* **Get Latest Bursts** 
```is.workflow.actions.getlatestbursts```
* **Get Latest Photos** 
```is.workflow.actions.getlastphoto```
* **Get Last Import** 
```is.workflow.actions.getlatestphotoimport```
* **Delete Photos** 
```is.workflow.actions.deletephotos```

### 🟠 Health Data

* **Find Health Samples** 
```is.workflow.actions.filter.health.quantity```
* **Search in Health** 
```com.apple.Health.OpenSearchIntent```

### 🟠 Voice Memos

* **Delete Voice Memos Recordings** 
```com.apple.VoiceMemos.DeleteRecording```
* **Delete Voice Memos Folders** 
```com.apple.VoiceMemos.DeleteFolder```
* **Search In Voice Memos** 
```com.apple.VoiceMemos.SearchRecordings```

### 🟡 Controls Management

* **Set Night Shift** 
```is.workflow.actions.nightshift.set```
* **Set Appearance** 
```is.workflow.actions.appearance```
* **Set Orientation Lock** 
```is.workflow.actions.orientationlock.set```
* **Set Flashlight** 
```is.workflow.actions.flashlight```
* **Set Brightness** 
```is.workflow.actions.setbrightness```
* **Set Bluetooth** 
```is.workflow.actions.bluetooth.set```
* **Set Volume** 
```is.workflow.actions.setvolume```
* **Set True Tone** 
```is.workflow.actions.truetone.set```
* **Set Always On Display** 
```is.workflow.actions.display.always-on.set```
* **Set Focus** 
```is.workflow.actions.dnd.set```
* **Set Low Power Mode** 
```is.workflow.actions.lowpowermode.set```

### 🟡 Web

* **Expand URL** 
```is.workflow.actions.url.expand```
* **Run JS On Web Page** 
```is.workflow.actions.runjavascriptonwebpage```
* **Download File** 
```com.sindresorhus.Actions.DownloadFileIntent```
* **Get Contents of Web Page** 
```is.workflow.actions.getwebpagecontents```
* **Get Contents of URL** 
```is.workflow.actions.downloadurl```
* **Upload to Imgur** 
```is.workflow.actions.imgur.upload```