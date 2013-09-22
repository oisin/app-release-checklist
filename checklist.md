## App Development Company Limited

*RELEASE AUTHORISATION FORM v1.0*

|  |  |
|:-------------------------------------|-------------------------------------:|
| App name                             |      *insert content*                |
| Version                              |      *insert content*                |
| Date of submission                   |      *insert content*           |

This form is to document the testing that has been done on each app
version before submitting to the App Store. For each item, indicate *Yes*
if the testing has been done, *Not Applicable* if the testing does not
apply (eg testing audio for an app that doesn’t play any), or *No* if the
testing has not been done for another reason.

--

###Internet Connectivity
Test all the data downloading sections of the app by trying them on the appropriate connection type. Consider graceful degradation and failure as well as success conditions.

| Connection | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| Wifi | | | |
| Edge | | | |
| GPRS | | | |
| No Network | | | |
| Break in Network - use Charles | | | |
| Server unreachable - timeout | | | |
| Resumed connect - streaming only | | | |

--

###Locale
Change device’s settings then load the app. Check that dates appear correctly, especially dates from external feeds or services.

| Locale | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| 12 and 24 hour clocks | | | |
| Regions: **fork and add regions for you** | | | |
| Languages: **fork and add languages for you** | | | |
| Timezones  | | | |
| Daylight Savings time | | | |

--

### Devices
Run the application through navigations using different devices with different iOS versions and display formats.

| Device | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| iPhone / iPod touch running iOS 5.0 | | | |
| iPhone / iPod touch running iOS 5.1.1 | | | |
| iPhone / iPod touch running iOS 6.0 | | | |
| iPhone / iPod touch running iOS 6.1.3 | | | |
| iPhone / iPod touch running iOS 7.0 | | | |
| Retina iPhone display | | | |
| Non-retuna iPhone display | | | |
| iPad 1 running iOS 5.0 | | | |
| iPad 1 running iOS 5.0 | | | |
| iPhone / iPod touch running iOS 5.1.1 | | | |
| iPad running iOS 6.0 | | | |
| iPad running iOS 6.1.3 | | | |
| iPad running iOS 7.0 | | | |
| Retina iPad display | | | |
| Non-retina iPad display | | | |
| iPad mini display | | | |

--

### Audio
If app plays audio, perform the following checks. For streaming audio, make sure the checks in the network section above have also been done.

| Audio | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| Headphones/speaker routing  | | | |
| Dock connector audio out routing   | | | |
| iPod touch audio routing (consider model without speaker) | | | |
| Mute switch functionality (officially it mutes non-user-requested sounds) | | | |
| Audio pause on received phone call | | | |
| Background audio (if supported): playback and multitasking bar controls | | | |
| Start playing audio when another app is already playing | | | |
| Headphone remote for audio control | | | |
| Multitasking screen audio control | | | |

--

###Video
Streaming video should have been checked in the network tests.

| Video | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| User cancels video before playback begins  | | | |
| User cancels video during playback  | | | |
| Video plays to the end  | | | |
| Video return from full screen  | | | |
| Dock connector video out  | | | |
| Video transition between inline and full screen  | | | |

--

###Location

| Location | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| True GPS | | | |
| Wifi location | | | |
| Cell tower location | | | |
| Unable to find location | | | |
| No results returned (eg too far from any searchable points of interest).  | | | |
| Location services turned off | | | |
| Location services disabled for this app | | | |

--

###Logging

| Logging | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| Logging events to live server | | | |
| Logging errors (interact with other tests?) | | | |

--

###User Interface
Test each major view in the app.

| Title | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| Double height status bar (eg in call) | | | |
| Orientation change | | | |
| Upside-down orientation | | | |
| Orientation lock | | | |
| VoiceOver turned on | | | |
| Usable by a new user with Screen Curtain turned on | | | |
| Works with Accessibility Zoom turned on | | | |

--

###Core Data

| Core Data | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| Validation error in user input | | | |
| Validation error in web server input | | | |
| Test migrations with valid and invalid data files | | | |
| Rollback | | | |

--

###Installation

| Installation | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| Fresh install | | | |
| Upgrade from previous live version | | | |
| Upgrade from older live version | | | |
| Rollback | | | |

--

###Text

| Title | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| Shake to Undo | | | |
| Text selection (including disabled when appropriate) | | | |
| Copy / Paste | | | |
| Editing when keyboard is hidden | | | |

--

###Third Party Services
All third party services should use production API key and the new app version should be registered in the respective dashboards
| Title | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| Production analytics/tracking API key | | | |
| New app version tracking data available tracking in dashboard | | | |
| Production crash reporting API key | | | |
| Upload dysm to crash reporting tool | | | |
| New app version available in crash reporting dashboard | | | |
| Push notification service API key | | | |
| New app version added to push service dashboard | | | |
| Production App ID for social services (Twitter, Facebook, Instagram, etc) | | | |

--

###Misc

| Misc | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| Motion | | | |
| Tested in Ad Hoc mode | | | |
| Version number upgraded | | | |
| Bundle identifier correct for release | | | |

--
<br><br>

Sign-off: __________________________________________  

<br><br><br>
Project role: _______________________________________  
