## Version 2404 - Spring 2024 Update
Released: Mar 1, 2024
Servicing release

**[Version #2404.1] - 10 Mar 2024**
- Fixed the appearance of the year 1601 in the Timeline. Clicking on it caused the application to crash
- Optimized access to files in the gallery
- Slightly optimized RAM consumption when opening images

**[Version #2404.0] - 1 Mar 2024**
- Optimized and accelerated timeline loading
- Windows SDK version updated to 10.0.19041
- Minimum required Windows build for app installation has been updated to 10.0.19044 (Windows 10 version 21H2)

## Version 2403 - Long-Term Support Release
Released: Mar 1, 2024
Long-term support release for no longer supported device configurations.
This version will receive bug fixes and security updates until the end of 2025.

The application, starting from version 2404, no longer supports: 
-Windows 10 versions 1809, 1903, 1909, 2004, 20H2, 21H1
-x32 processors
-ARM32 (not ARM64!) processors
-Xbox
-Hololens

If you have received this version (2403), then most likely you are on one of these more unsupported device configurations.
More details on the What's New page (icon with a question on the main page)

**[Version #2403.0] - 1 Mar 2024**
- Optimized and accelerated timeline loading

## Version 2402 - February 2024 Update
Released: Feb 5, 2024
First release in 2024!

**[Version #2402.0] - 5 Feb 2024**
- [NEW!] The global music player in the app. The music now doesn't stop when you exit the music page
- [NEW!] Mini-player in the gallery, slideshow page and image viewer page
- [NEW!] Context menus when clicking on a file in the gallery
- [NEW!] Context menus when clicking on a folder in the gallery
- [NEW!] Dragging files from the application to the system
- [REMOVED] HEVC-videos extension from extensions list in Settings window due to its now unavailable in the Microsoft Store
- Some minor UI edits throughout the app
- Minor performance improvements
- Bugfixes

**[Version #2402.1] - 7 Feb 2024**
- [NEW!] Ease of use: tap on the background of the pop-up window to close it

**[Version #2402.2] - 11 Feb 2024**
- Bugfixes

**[Version #2402.3] - 13 Feb 2024**
- Fixed: app crash

**[Version #2402.4] - 14 Feb 2024**
- Fixed: Rate app dialog errors
- Folders list is now updated too when you click the gallery update button
- Some third-party libs updated

**[Version #2402.5] - 15 Feb 2024**
- [NEW!] When dragging files, the page blurs

**[Version #2402.6] - 16 Feb 2024**
- [NEW!] Now you can drag and drop a music file directly from the player page by pulling on the album image of the track
- Improved perfomance on opening image in picture page

**[Version #2402.7] - 18 Feb 2024**
- [NEW!] Gallery sorting! Click on Filter-icon button at the bottom of the gallery page
- [NEW!] Previously temporarily disabled file viewing function on a removable device has been returned
- Some under-the-hood changes

**[Version #2402.8] - 20 Feb 2024**
- Fixed: miniplayer click not working sometimes
- Fixed: the distances between the elements in the gallery
- Some UI changes

**[Version #2402.9] - 21 Feb 2024**
- Mini-player UI improvements
- Fixed: the distances between the elements in the gallery

**[Version #2402.10] - 23 Feb 2024**
- Mini-player fixes
- RAM usage optimizations

**[Version #2402.11] - 25 Feb 2024**
- Some UI edits

**[Version #2402.12] - 27 Feb 2024**
- [NEW!] Additional sorting options in Gallery page

**[Version #2402.13] - 29 Feb 2024**
- Fixed: crash of the application when trying to sort files in folders outside the gallery
- Option to sort videos and music by duration is temporarily disabled due to an error found
- Some RAM-usage optimizations

## Version 2312 - Winter 2023 Update
Released: Dec 3, 2023
Another service release aimed at improving the stability and performance of the application

**[Version #2312.0] - 3 Dec 2023**
- [NEW!] Chinese localization
- Significantly improved performance when switching folders in the gallery
- Improved the app launch speed
- Improved image editor performance
- Improved performance when working with the Timeline
- Numerous changes, improvements and optimizations "under the hood"
- When the application is launched, it now checks access to the library of images and videos
- The settings window now displays a list of changes to only the current version
- The changelogs of previous versions are now posted on GitHub (the link is available in the settings window)
- Integration with the Telegram application channel has been removed
- The donation page has been deleted
- For better performance, the carousel has been replaced with a standard collection control in the Timeline
- When starting a slideshow, the application now checks that there are enough images in the selected folder
- The settings window has been reduced
- The page switching animation in the settings window has been changed and accelerated
- Various interface edits throughout the application
- WinUI has been updated to version 2.8.6
- CommunityToolkit has been updated from version 7.1.3 to 8.0.0

**[Version #2312.1] - 4 Dec 2023**
- Fixed app title in Start Menu

**[Version #2312.2] - 15 Jan 2024**
- Updated CommunityToolkit.WinUI to 8.0.1
- Bugfixes

**[Version #2312.3] - 1 Feb 2024**
- Fixed: video-files previews not displayed

## Version 2311 - November 2023 Update

The release is mainly for fixes and optimizations. The gallery sorting function will be added later in one of the patches to version 2311.

**[version #2311.0] - 1 Nov 2023**
- Timeline-gallery loading is accelerated several times
- Changed the UI of video and music cards in the gallery
- Added animation of loading cards in the gallery
- Added animations in the music player
- Accelerated opening of music files
- The cards in the gallery are now centered and do not stretch to fit the size of the window
- Large internal permutations in the project and code refactoring
- Minor adjustments to background colors and fonts

## Version 2310 - Quality Update

Multiple fixes and usability improvements 
New localizations and opening files on removable devices

**[version #2310.0 (#3260)] - 2 Oct 2023**
- [NEW!] Scrolling through music files
- [NEW!] Ability to view files on removable devices
- [NEW!] Turkish localization
- [NEW!] Vietnamese localization
- [NEW!] German localization
- Perfomance improvements
- The launch of the application is slightly accelerated (it will be slightly noticeable on weak devices)
- Accelerated opening and scrolling of images. Now the low resolution image is displayed first and the original resolution image is loaded in the background
- Redesigned Tab-navigation. Improved usability with keyboard, gamepad or joystick
- Redesigned Welcome screen (yes, again)
- Added animation when pausing a music file
- At the end of a music track, a pop-up now appears with information about the next track
- When the video is paused, its name is now displayed
- Added a double-click to switch the video to full screen
- When you press the arrow keys, the music and video are now rewound for 10 seconds
- The gallery page now displays a button to open the What's New window
- By pressing Escape, you can now access the gallery from the Image, Music and Video pages
- UI edits in the Video and Music FileInfo pages
- UI edits in Filters Page
- UI edits in Slide-Show Page
- Bugfixes

**[version #2310.1 (#3261)] - 3 Oct 2023**
- Fixed: the clock is not displayed in the slideshow
- Fixed: visual bug of displaying information about a music/video file

**[version #2310.2 (#3264)] - 5 Oct 2023**
- Fixed: application crash when trying to move files in the gallery
- Fixed: the gallery was not updated automatically when adding/removing folders from libraries
- Fixed: incorrect gallery update after deleting/moving files

**[version #2310.3 (#3265)] - 6 Oct 2023**
- Fixed: some localization issues

**[version #2310.4 (#3271)] - 7 Oct 2023**
- Updated icons
- Updated items design in the music and video gallery
- Added an icon that is displayed when a music track does not have an album image
- Fixed: broken icons

**[version #2310.5 (#3272)] - 9 Oct 2023**
- Some localization fixes

**[version #2310.6 (#3284)] - 11 Oct 2023**
- Fixed: app crash when opening music

**[version #2310.7 (#3285)] - 11 Oct 2023**
- Fixed: app crash when opening FLAC-files

**[version #2310.8 (#3291)] - 11 Oct 2023**
- Redesigned layout of the image editor page
- Improved sliders for more convenient change through the keyboard or gamepad
- Fixed: some UI errors in image editor page

## Version 2309 - A New Era Release

The biggest update I've ever done is already here! New features, rebranding and numerous edits)
Since the application now has not only images, but also videos with music, 
it was decided to rename it to better reflect the essence of the application.
Since the update is quite large, some bugs and instability are possible. I will try to promptly correct errors as they are identified.

**[version #2309.0 (#3144)] - 8 Sep 2023**
- [NEW!] Timeline feature! Sort your images by year with a nice carousel
- [NEW!] Music Gallery feature! Add music folders to the gallery and view them
- [NEW!] File Info view for videos
- [NEW!] File Info view for music
- [NEW!] Completely redesigned slide show
- [NEW!] Option to display the clock in a slideshow
- [NEW!] Added more than 60 animations to the slideshow
- [NEW!] More detailed color correction! Check in the Filters Page. Edit the color correction as a Pro!)
- [NEW!] Extensions gallery! A list of extensions available for installation, for opening more rare or professional file formats and images or videos. Available in Settings
- [NEW!] New logo
- [NEW!] New app name: SimplePhotos! -> FlyGallery!
- [NEW!] Donate option changed from Boosty to Telegram Donate Bot
- [NEW!] A Telegram channel has been created for the news of the application, you can also support the development of the application there) Link in the Settings
- [NEW1] Clicking on a field in the File Info screen (music and video so far) copies this field to the clipboard
- [REMOVED!] Drawing feature
- Redesigned Welcome Screen
- Redesigned WhatsNew Screen
- Redesigned MusicPlayer Page
- Redesigned video gallery items
- Redesigned main gallery page
- Fully rewritten Settings screen for better perfomance and rendering
- Added acrylic background for pages on Windows 10 devices
- Added new animations when switching pages for additional smoothness of the application
- Changed the animation of opening/closing pop-ups
- WinUI updated to 2.8.5
- Win2d updated to 1.27.0
- Other third-party libraries updated
- Bugfixes

**[version #2309.1 (#3145)] - 10 Sep 2023**
- Fixed incorrect display of folders in the music gallery

**[version #2309.2 (#3146)] - 15 Sep 2023**
- Removed acrylic background in Picture Page on Windows 10
- Some colors corrections in UI
- Acrylic transparency in Music Page reduced

**[version #2309.3 (#3155)] - 17 Sep 2023**
- Fixed date-time formatting in File Info popups
- Fixed gallery button in Music Gallery
- Fixed folders layout in adding folders in Settings

## Version 2306 - Music Update

The ability to open music format files! So far, only the basic functionality is available - opening music files. 
The music gallery and other related functions, such as information about the music file, 
moving to the next track in the folder will be available later.

**[version #2306.0 (#2951)] - 15 Jun 2023**
- [NEW!] Music files support (mp3, wav, aac, flac, m4a) (now in beta)
- Added some animations when switching application pages
- Third-party packages update
- Removed anniversary decorations
- Some fixes with gif-files

**[version #2306.1 (#2952)] - 17 Jun 2023**
- Fixed bug with transparent popups
- Temporarily removed the animation of the transition between pages

## Version 2305 - Third Anniversary Update

The application is 3 years old! 
The update for the third anniversary is already here!

**[version #2305.0 (#2816)] - 20 May 2023**
- [NEW!] GIF-files support
- [NEW!] WEBP-files support
- Third-party packages updated
- Anniversary decorations
- Small UI adjustments
- Build number is now hidden for better readability of the app version
- Slight performance improvement
- Added the display of the full version of the application on the page with the list of changes

## Version 2304 - April 2023 Update

A small technical release is already here! 
Internal changes to bring back support for older versions of Windows 10, and a new option in the image editor!

**[build #2636] - 1 Apr 2023**
- [NEW!] Hue Rotation option in Image Editor
- [NEW!] Returned support for older versions of Windows 10 prior to version 1809
- Small adjustments to animations
- Fixed ability to start slideshow from empty folder
[build #2638] - 10 Apr 2023
- Bugfix: hue rotation effect not applying

## Version 2303 - Spring 2023 Update

Spring update is here! Video functionality improvements and multi-selection in gallery feature!
Further development of the multiple selection feature will be in the upcoming updates

**[build #2616] - 20 Mar 2023**
- [NEW!] Images and videos multi-selection in gallery
- [NEW!] One-click deletion selected images/videos
- [NEW!] One-click moving to folder selected images/videos
- Some UI improvements in video page and video-paused page
- The background of the video title in the gallery has been replaced to accent color due to performance drawdowns
- Some system changes
- Third-party libraries updated
- Redesigned app updating notification
- Removed gray splashscreen background color
- Removed app updating screen
- Bugfixes

## Version 2301 - Media Update

First update in 2023 is already here! 
Video files support and videogallery feature!

**[build #2401] - 3 Jan 2023**
- [NEW!] App icon and logo
- [NEW!] Ability to open video files (now in BETA)
- [NEW!] Function of viewing the video library as a gallery (now in BETA)
- [NEW!] Ability to add folders to videos library (in app settings)
- [NEW!] Opening folders to view video files (now in BETA)
- [NEW!] Redesigned settings page
- [NEW!] RateApp and Error dialogs
- [REMOVED!] Images carousel temporary removed due to serious performance issues
- [REMOVED!] Animation when scrolling through images using buttons in the UI or on the keyboard
- [SYSTEM] Completely redesigned the mechanism of the image collection 
when opening the application through a file. 
Performance in folders with a large number of images should increase several times
- Several animations changes
- Several UI changes
- Gallery processing has been accelerated
- New mechanism for storing app settings
- System libraries updated
- WinUI updated to version 2.8.2
- Added nice animation in FileInfo screen

## Version 2212 - New Year 2023 Update

Few fixes and improvements for the New Year

**[build #2216] - 9 Nov 2022**
- System libraries updated
- Slightly reduced the size of the application

**[build #2218] - 24 Dev 2022**
- Bugfix with welcoming screen

## Version 2211 - Fall 2022 Update

Swipes, folder management improvements and refreshed app design

**[build #2200] - 5 Nov 2022**
- [NEW!] When opening a folder, the top bar now displays the subfolders
- [NEW!] In the gallery window, it is now possible to go through the nested folders
- [NEW!] Refreshed design and new animations
- [NEW!] Swipes in picture page. Swipe up for deleting image, swipe down for back to gallery
- [NEW!] Reworked images scrolling swipes. Now the picture follows the finger when flipping
- Updated: donation page in Settings screen
- Updated: folders page in Settings screen
- Updated: about app page in Settings screen
- Optimized: image output in Filters screen. RAM consumption for heavy images is reduced by almost half
- Fixed: after adding a folder to the image library, the gallery was not automatically updated
- Fixed: some visual errors in Settings screen
- Big internal changes
- Third-party libraries updated

## Version 2208 - Filters Update

10 new filters is here! Many small features and changes!

**[build #2161] - 21 Jul 2022**
- [NEW!] 10 new image filters
- Updated filter preview images
- Stability improvements after the last release: fixed about 8 minor (and not very) bugs
- Major update of app UI library (WinUI)
- Updated splash-screen logo

**[build #2164] - 7 Aug 2022**
- [NEW!] When copying the file path, an icon with a check mark now appears
- Fixed zooming image on touch screen with double tap
- Since Patron is no longer available in my country, it was replaced on the donation page with another service - Boosty
- Updated system libraries
- Internal changes

**[build #2166] - 10 Aug 2022**
- [NEW!] Click or tap on picture to hide/show bottom panel
- [NEW!] Scroll through the pictures with the arrows from the keyboard! And also: "UP" - return to the gallery, "DOWN" - show/hide bottom panel
- Internal changes

**[build #2168] - 12 Aug 2022**
- [NEW!] Full-screen mode in picture page
- Setting and Drawing buttons swapped
- Internal changes

**[build #2171] - 21 Aug 2022**
- [NEW!] Whats New page button added to bottom of Gallery page
- Redesigned Whats New page
- Redesigned Welcome page (first app launch) 
- Some UI changes
- Big internal changes

**[build #2175] - 22 Aug 2022**
- Internal changes
- Some images output optimizations
- Some gallery loading optimizations
- Fullscreen mode button and the File Info button have swapped places
- Fixed an image scrolling bug when deleting a file

**[build #2176] - 24 Aug 2022**
- Fixed a crash when opening an image

**[build #2177] - 26 Aug 2022**
- Fixed UI bugs in Filters page
- Fixed unstable pictures carousel appearing
- Fixed bug with added folders in Settings page

**[build #2178] - 1 Sep 2022**
- Internal changes
- System libraries updates
- Redesigned image editing page

**[build #2179] - 11 Sep 2022**
- Bugfixes
- System libraries updated

**[build #2180] - 18 Sep 2022**
- Fixed some errors
- Added a tooltip to close the slideshow

## Version 2207 - Gallery Update

Another big update is here! 
Big gallery improvements, drawing feature, slide-show and some more!

**[build #2151] - 7 Jul 2022**
- [NEW!] Tabs with separate Pictures Library folders
- [NEW!] Open folder with images from disk
- [NEW!] SLide-show (beta)
- [NEW!] Drawing feature
- [NEW!] Images carousel in picture page (move pointer on top of picture page)
- [NEW!] Added animation when scrolling through images
- System libraries updates
- Code refactoring
- File Info screen corrections
- New image on Welcome screen
- Link to the installation of the SimpleNotepad! application has been removed from the Settings
- Tab with the third-party software used has been removed from the Settings
- Changed folder icons in Settings for Windows 11 style
- Minor changes to the appearance of the gallery
- Added animation in WhatsNew screen
- Minor UI corrections in WhatsNew screen
- All changes from the hotfixes of version #2206

## Version 2206 - Summer 2022 Update

Image compression feature is here!

**[build #1996] - 05 Jun 2022**
- [NEW!] Image compression
- [NEW!] New welcome screen when the app is first launched
- Redesigned file deletion
- Redesigned saving file changes
- Updated WinUI Library version to v2.8
- System libraries updated
- Bugfixes

**[build #2000] - 07 Jun 2022**
- System libraries updated
- App size reduced

**[build #2004] - 11 Jun 2022**
- Fixed image deletion bug

**[build #2016] - 16 Jun 2022**
- Fixed filters applying to png images with transparency
- UWP version updated

**[build #2020] - 19 Jun 2022**
- Fixed file info output for long strings

**[build #2031] - 25 Jun 2022**
- Fixed some Print image bugs

**[build #2034] - 27 Jun 2022**
- Fixed bug when images with file format in capital letters were not displayed in gallery

## Version 2204 - Usability Update

Multi-window and usability improvements!

**[build #1907] - 03 Apr 2022**
- [NEW!] Multi-window
- [NEW!] New aspect ratio options on the crop page
- Save Original and Save Copy buttons are separated in filters page to improve convenience
- Save Original and Save Copy buttons are separated in crop page to improve convenience
- Localization on tooltips has been fixed
- Added animation upon successful completion of a task, such as setting wallpaper or saving a filter
- Added animation when deleting a file
- Added animation when switching tabs in settings and filters
- Scrolling tabs in settings and filters is now possible by swipe
- Fixed: The gallery is now automatically updated when cropping, editing, deleting or moving an image
- Fixed: the arrows for flipping the image now do not appear when flipping is impossible
- System libraries updated

## Version 2202 - Editor Update

Big update is here!
The update includes a completely new image editor with new filters
and improved performance by about 500%! 
Also, in addition to the new editor, the function of moving the image
to the specified folder has been added. 
Thank you for staying with us!

**[build #1821] - 10 Feb 2022**
- [NEW!] New Image Editor with new awesome filters and adjustments
- [NEW!] "Move to.." image to selected folder
- Redesigned the logic of loading the gallery
- Redesigned the appearance of the image cropping screen
- UI correction in Gallery Page
- To improve the usability, Print button and File Info button are swapped
- Reduced the size of the application occupied on the device
- Reduced RAM consumption when scrolling through images
- New graphics library - Win2D
- Bugfixes
- System libraries updates
- Removed: Some system libraries
- Removed: Windows 10 Version 1903 and Version 1909 support

**[build #1822] - 11 Feb 2022**
- Fixed: app crashes when opening some images
- Fixed: english localization issues

## Version 2112 - New Year 2022 Update

Small fixes for the New Year! Thank you for using my app this year! Stay tuned!)

**[build #1730] - 22 Dec 2021**
- App crash fixes
- Bugfixes
- System libraries updates
- Small code optimizations

**[build #1734] - 01 Jan 2022**
- Fixed: scrolling through images

## Version 2111 - Systems Update

Major changes "under the hood"

**[build #1700] - 30 Nov 2021**
- [NEW!] New supported files format: .jfif
- [NEW!] Copy image path from File Info window
- Increased gallery loading speed
- Many internal changes (some new bugs are possible, which I will try to fix quickly)
- Logo changed (yes, again)
- UWP version updated
- Localization fixes

## Version 2110 - Fall 2021 Update

Edit images! New app design!

**[build #1000] - 9 Oct 2021**
- [NEW!] Apply filters to the image (beta)
- [NEW!] Apply Color Matrix to the image
- [NEW!] Reflect images
- [NEW!] New Settings page
- [NEW!] Windows light-theme support (finally!!)
- [NEW!] New right-click context menu on Image page
- [NEW!] New What's New screen that will be shown with each new major update
- New app updating screen
- New animations in the app to make its use smoother
- Some gallery output optimizations
- A separate Editor page has been deleted
- New app default font - Segoe UI Variable
- Image cropping is now available in the menu called by the pen button on the image page
- Some changes have been made to improve the smoothness of the interface
- Added a pop-up window with key update changes
- Changed the message dialog about the availability of an update
- WinUI updated to v2.7
- "Add folder" button has been moved to the bottom of the page
- "Add folder" button now leads to a new settings page
- "About app" button now leads to a new settings page
- Image rotation button is now located in the image editing menu (the button with a pen)
- "About app" window has been removed
- "Add folder to gallery" window has been removed
- Added donation button on Gallery page
- Gallery gradient animation has been removed
- System libraries updated
- Fixed image output when file is not supported
- Fixed translation of File Info title
- Fixed output of image size in FileInfo
- Fixed output of image camera model in FileInfo
- Fixed output of image title in FileInfo
- Fixed output of image folder in FileInfo
- Other small fixes

**[build #1005] - 22 Oct 2021**
- Fixed new fonts on devices with Windows 10
- Swapped places Settings button and Donation button in Gallery Page

**[build #1009] - 25 Oct 2021**
- Fixed app crash when folder deleted from Picture Library
- Fixed Error content dialog appearance

## Version 2107 - July 2021 Update

**[build #740] - 18 Sep 2021**
- Fixed app crash when the Pictures Library is empty
- Fixed an empty window when opening an unsupported file

**[build #730] - 6 Jul 2021**
- [NEW!] Italian localization
- Bugfixes
- System libraries updated

**[build #731] - 19 Aug 2021**
- TIF files bugfix
- System libraries updates

**[build #732] - 23 Aug 2021**
- Image output fix

**[build #733] - 8 Sep 2021**
- ICO files support
- Bugfixes

## Version 2105 - Anniversary Update

Anniversary update here! 
1 year!!!
Thanks for using it! Stay tuned!)

**[build #712] - 31 May 2021**
- [NEW!] Cropping images!
- [NEW!] Copy image
- [NEW!] Copy image as file
- [NEW!] Pinch-zoom for touch-devices
- [NEW!] Image Share feature!
- [NEW!] Print Image feature!
- [NEW!] Ctrl+Wheel zoom
- System changes
- Removed app splashscreen on powerful PC
- System libraries updated
- Redesigned gallery page
- Redesigned file info dialog
- Removed gallery wallpaper
- Removed blured background on picture page
- Added new animations
- New gradient backgrounds
- Increased app perfomance
- New app icon

**[build #714] - 7 Jun 2021**
- Image showing fixed
- Double-tap zoom reduced
- Animations edits
- Bugfixes

## Version 2012 - New Year 2021 Update

**[build #277] - 28 Dec 2020**
- System changes
- Fixed rendering of high-resolution images
(experimental)
- New default gallery wallpaper

## Version 2011 - November 2020 Update

**[build #266] - 30 Nov 2020**
- [NEW!] Incremental gallery loading
- New animations on image opened
- New default gallery image backgroung
- System libraries updates
- Internal changes
- Increased speed and improved performance 
- Improved rendering when scrolling through the gallery 
- Bugfixes

## Version 2007 - July 2020 Update

**[build #145] - 8 Jul 2020**
- [NEW!] Image rotation 
- [NEW!] File deletion 
- [NEW!] Auto-refresh the gallery when you change the file system 
- [NEW!] Displaying the parent folder in the file Information window" 
- Added animations to various parts of the app 
- New animation when launching the app 
- Added a banner informing about the update of the gallery 
- Redesigned the lower menu on the image viewing page 
- Redesigned the "About" window" 
- Added a changelog 
- Redesigned the function of adding a folder to the gallery 
- Increased speed and improved performance 
- Improved rendering when scrolling through the gallery 
- Changes to the file Information window-Updated the default gallery background 
- Added the app's French language 
- Added Spanish app language 
- Fixed various bugs

## Version 2006 - June 2020 Update

**[build #101] - 1 Jun 2020**
- [NEW!] add image folders to your gallery!
- [NEW!] added support for .tiff files
- Design correction
- Added gallery animation when resizing the window
- Added gallery animation when launching the app
- Added a window offering to send logs in case of errors
- New default gallery wallpaper
- Improved adaptability when changing the window size
- App target version changed to Windows 10 Version 2004

**[build #102] - 3 Jun 2020**
- Bugfixes

**[build #104] - 7 Jun 2020**
- Fix an issue with adding folder to the gallery
- Adding a banner about the availability of updates

## Version 2005 - Original Release

**[build #42] - 13 May 2020**
- First release in Microsoft Store

**[build #52] - 16 May 2020**
- Bugfixes