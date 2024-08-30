# Developer Update Index

Copyright is held by VRChat Inc.

This is to find the developer update article for a specific topic.

I found it's a little challenging to find developer update for specific topic so I collected all Developer Updates

Before 2022, there are few Community Updates in dev updates category but they are not listed here.

Any text element prefixed with Note: is writer (anatawa12)'s note or opinion.

## Guideline for writing summary

- Put some words to make it easier to search
  - For example, put version number, feature name, etc.
- Put released feature name with Note if changed since dev update
  - This make easier to find when feature is released

## 2022

### [2022/07/28](https://ask.vrchat.com/t/developer-update-28-july-2022/)

Note: images are on gfycat so they cannot be loaded

- Horizon Adjust
- Microphone Sensitivity / Noise Gate
- Noise Cancellation
- Visual Settings
  - Color blindness filters
  - Adjust Bloom
  - Gamma / Brightness / Contrast
- Slider Snapping in Menus
  - for Exactly on 100% volume
- Solo Audio Button
- Local Voice Falloff Settings
- Conversation Dome
  - Now implemented as Earmuff
- Stream Audio spatializer
- Avatar Distance Hiding
  - Note: Now available as Hide Avatar by Distance
- Text to Speech / Speech to Text / Speech to Text to Speech
  - T2S for other user's voice
  - S2T for others
  - S2T2S for voice anonymization
- Invite+ Fix
  - Broken due to secure instance
- Home instance type
- Particle Limiter on UI Config
  - Previously hidden in a config file
- Paste Button on in-VR Keyboard
- Better Portal Placement
  - Portal Placement with Holoport interface
- Haptics on touch Avatar Dynamics
- Increase Favorites
  - New UI can handle more items than 100!
- Personal Mirror and Calibration mirror
- FBT Calibration Visualization
  - Show tracker and closest calibration point for each tracker
- Camera Changes
  - Remove (Too / unnecessary) Lag
  - Portrait Mode
    - Note: Portrait is rotate image based on camera orientation
  - Increase Screenshot Resolution
    - 8K is possible, more is challenging
- User Notes
- Hide Avatar by ID (Now known as "Hide Avatar Globally")
- Security and Safety
  - No detailed info
- Main Menu Location / Moving
  - already in new MM, backporting to ild MM

### [2022/07/29](https://ask.vrchat.com/t/developer-update-29-july-2022/)

- Live Beta
  - Horizon Adjust
  - Moveable Main Menu
  - Personal Mirror
  - Calibration Mirror
  - Portal Prompt
  - improvement look to move with lying down
  - Gesture Indicator
  - Home Instance Type
  - Particle Limiter toggle on Menu
    - Custom settings can be configured with config json
  - Reduced Screenshot lag
  - User Notes (web only)
    - Note: This is included in Main Menu 2.0 so we can access in game now
  - Auto Disabling Avatar Cloning on World entry
- In-development features
  - Paste Button on Keyboard
  - NearClip Override
  - Text to Speech
  - Speech Bubble
    - Note: Now available as Chat Box
  - Additional Favorites
    - Note: I think same as current limit
      - Non-VRC+
        - Friends: 3*150
        - Worlds: 4*100
        - Avatars: 1*50
      - VRC+
        - Avatarss: 6*50
  - AMD FSR
    - Bad result in internal testing but assigned
  - Hide Avatar by Distance

### [2022/08/02](https://ask.vrchat.com/t/developer-update-2-august-2022/)

- Live Beta feedback responses
- Movable Main Menu
  - Bug fixes
- Horizon adjust
  - Bug fixes
- Personal Mirror
  - Face Mirror addition
- Hide Avatars by Distance
  - Always show friends avatars
  - Allow Override with Show Avatar
- Text to Speech
  - Text to Text: No Problems
  - Text to Speech: no effort beyond exploration
  - Speech to Text: If feedback is come
    - We may input to TTT with OS-level TTS
- Camera Near-Clip Adjustment
  - depth buffer size issue on quest
  - continue development
- Noise Gating and Background Noise Removal
  - In-review
- Portal Placement
- Auto Disable Cloning
- User Notes
  - In-game supportChanged to higher-level override => auto toggle off
- AMD FSR
  - FSR 2.0 or XeSS?
    - Motion Vector problem
- CPU Affinity for Ryzen Processors
- FPS Drop after EAC?
  - Not on average
- Community Labs Graduation bug fix

### [2022/08/03](https://ask.vrchat.com/t/developer-update-3-august-2022/)

- 2022.2.2p2 Live Beta Update
- Increased Favorites
  - In QA
- Visual Settings
- Copy/Paste Button
- Personal Mirror UI Changes
- Near Clip
  - Problems with with larger FarClip
  - Off/Dynamic/Forced
- Portrait Mode
  - Note: Portrait is to rotate image based on camera orientation
- Increased Screenshot Resolution
- Save Image Directly to Gallery
- Desktop Camera
- Hide avatar by distance
- Conversation Dome vs. Local Player Voice Falloff Slider
  - Local Player Voice Falloff Slider is win
  - Note: This is known as Earmuff
- Speech Bubbles
- Text to Speech
- CPU Core Affinity and Process Priority
  - Impossible for now due to EAC.

### [2022/08/04](https://ask.vrchat.com/t/developer-update-4-august-2022/)

- Server downtime
- noise gate & supression
- Personal Mirror UI changes
- Earmuffs (previously known as Conversation Dome)
- Hide by Distance
  - Problems with WD on
- More favorites is in UI 1.0
- Camera Resolution Selector
- Text Chatbox / Chat Bubble

### [2022/08/05](https://ask.vrchat.com/t/developer-update-5-august-2022/)

- 2022.2.2p2 Release
  - Personal Mirror, Movable Main Menu, Horizon Adjust are now live
  - New Features details here (again)
- 2022.2.2p3 now in Live Beta
  - Earmuffs
  - Noise Gate + Suppression
  - near clip adjustment
  - hide avatar by distance
  - persoal mirror UI changes
- In development
  - Face Mirror
  - Chatbox
  - Gesture Indicators
  - Earmuffs indicator on nameplate

### [2022/08/08](https://ask.vrchat.com/t/developer-update-8-august-2022/)

- Quick Recap
  - 2022.2.2p2 Released
  - 2022.2.2p2b Released
  - 2022.2.2p3 is in Live Beta!
- Features in Progress
  - Earmuffs
    - indicators on nameplate
  - gesture indicator
  - more favorites
  - more personal mirror tweaks
    - immersive mode
    - resize
    - face mirror
  - camera sutff
    - resolution selector up to 8K (PC)/ 4K (Quest)
    - Camera Smart Rotation (previously known as Portrait Mode)
    - Other Requests
      - keyframed camera tracks in worlds
      - better scaling / grabbing
      - desktop camera
      - and many
      - Not featres are implemented but some may be addressed in differ ways
  - Text Chatbox
    - In progress
  - Near clip Bugs
    - If reference camera is not defined was bug
  - Unmute sound
    - Ask user for unmute
    - straightforward!
    - Note: There is no feature yet?

### [2022/08/09](https://ask.vrchat.com/t/developer-update-9-august-2022/)

- Developer Update Schedule Change
  - reduced to twice a week since next week
- Feature Work
  - Full-Body Tracking Calibration Visualization
    - Optional
  - Gesture Icons
    - Note: Previously known as Gesture Indicator
  - Personal Mirror
    - Added laser to immersive
  - More favorites
  - VRChat Home Website update
  - Earmuffs on VRCat
  - Other Updates
  - Text Chatbox
    - In progress

### [2022/08/10](https://ask.vrchat.com/t/developer-update-10-august-2022/)

- Developer Update Schedule Change (Again)
- Release Plan
  - 2022.2.2p3 Live soon
  - 2022.2.2p4 Live Beta right after 2022.2.2p3
- Feature work
  - Desktop Camera (and flying camera)
  - Earmuffs
    - affect avatar audio
  - CPU Affinity
  - Hide Avatar Globally
  - Chatbox (+ OSC)
- Other Stuff
  - Terms of Use and Privacy Policy Update
    - Related to EAC
    - Note: EAC is released few week ago
  - Feedback
    - Avatar Scaling
    - Avatar Search

### [2022/08/11](https://ask.vrchat.com/t/developer-update-11-august-2022/)

- Schedule Change (Again)
- Web Login Issues (fixed)
- 2022.2.2p2c Release (bugfixes)
- 2022.2.2p3 Live Beta Updates
  - Hold release because bugs
  - Chatbox
    - Friends only by default
    - Cooldown system (5msg / 5sec, exceeding will wait 30 sec)
  - Personal Mirror Updates
    - Transparency changes
    - VRC Mirror Reflection component
    - Note: https://creators.vrchat.com/worlds/components/vrc_mirrorreflection/
  - Mirror Resolution Changer
    - 1/4, 1/2, full, unlimited
  - More Favorites
    - available
  - Camera Resolution Changes
  - Camera Smart Rotation
  - Slider Snapping and audio percentage slider
  - Hide Avatar Globally
  - Keyboard Paste
    - World creator can disable
    - Note: TODO: which component?
  - Calibration Confirmation Dialog
  - Quick Menu Information Headers improvements
  - Gesture Indicator Icons
  - NearClip Fixes (worlds without reference camera)
- Up Next
  - Hide Avatar by Distance
  - Visual Adjustments
    - Color Blindness Filters
  - Avatar Haptics
    - Haptics feedback on touch avatar mesh
  - Desktop Camera and Flying / Drone Camera
- Other Stuff
  - Avatar Scaling
    - no ETA yet

### [2022/08/12](https://ask.vrchat.com/t/developer-update-12-august-2022/)

No new info

- Schedule Change (Again)
- 2022.2.2p2c Release
- 2022.2.2p3 Live Beta Update
  - Chatbox
    - Friends only by default
    - Cooldown system
    - UTF-8 through OSC in future
  - Desktop Camera
  - Personam Mirror
  - Mirror Resolution Changer
  - More Favorites
  - Camera Resolution Options
  - Slider Snapping
  - Hide Avatar Globally
  - Keyboard Paste
  - Earmuffs for Avatar Audio
  - Calibration Confirmation Dialog
  - Quick Menu Information Headers
  - BugFixes

### [2022/08/16](https://ask.vrchat.com/t/developer-update-16-august-2022/)

- Upcoming Releases (2022.2.2p3)
  - 2022.3.1 is next
- Feature Work
  - Main Menu 2.0
  - Visual Adjustments
    - Refer to previous updates
  - Quick Menu UI Improvements
    - Scroll & Section Collapse improve
  - Portal Placement
  - More Personal Mirror Iteration
    - Face Mirror Scaling
  - Unlimited Mirror Resolution
    - Save-able
  - Hide Avatar by Distance bug fixes
    - Blocked user proxies
    - PhysBone poses
    - Keep Animator running
  - Avatar Haptics
  - Chatbox
    - Chatbox is an alternative to voice chat without voice
      - Not for general text chatroom
    - Keyboard redo
    - Chatbox Sound
    - Chatbox Options
        - Chatbox Sound - on/off
          - Display Duration - 2s to 60s
          - Chatbox Opacity - 10-100%
          - Keyboard Opacity - 10-100%
          - Chatbox Size Slider
          - Keyboard Size Slider
    - Action Menu and Bindings 
      - Requests for T key for open
      - VR Binding?
    - Chatbox Position
      - Over head vs middle
      - middle option will be added
    - Visibility Range
      - same as voice
    - Everyone or Friends by default
    - Visibility in Mirror
    - Filters (profanity filter)
    - Chatbox Iteration
      - High
        - Fix bugs
        - QM Settings and new options
        - Indication should disappear in 5s
        - if player is muted or has voice blocked via safety, hide indicator
        - typing indicator should inherit settings from chatbox
      - Mid
        - Inherit voice falloff
        - Add sound on message send
        - ADd binding for keyboard (T?)
        - Make keyboard bindable in VR
        - Implement middle chat placement
- Other Stuff
  - Beta Feedback Board Changes
    - Categories and Build Number field added
  - Continued Development

### [2022/08/19](https://ask.vrchat.com/t/developer-update-19-august-2022/)

- Release Plans
  - In Short: delay due to bugs in 2022.2.2p3
    - 2022.2.2p3 Live Beta
    - 2022.3.1 Main Menu Beta
- Feature Work
  - Chatbox Safety Design (not final)
    - Back to Safety system
  - Chatbox Emojis (fixed)
  - Personal Mirror Iteration
    - Clamped so not fall off
    - Head tracked Personal Mirror
  - Avatar Haptics
  - Earmuffs Improvements
    - Small Snap step (0.25 instead of 0.5)
    - Shortcut with double-click audio
    - Avatar Parameter `Earmuffs`
  - Portal Placement
    - on the way
  - Additional Emoji
    - planned
- Creator Updates
  - ClientSim Updates (bugfixes)
  - UdonGraph Changes
  - Creator Companion 0.3.6
    - It will be RC

### [2022/08/23](https://ask.vrchat.com/t/developer-update-23-august-2022/)

- Release Plans
  - 2022.2.2p3 Live Beta
    - Release to live this week
  - Main Menu Beta 
    - delayed
- Features and updates
  - Main Menu Preview
    - Many changes including skins
  - Avatar Haptics
    - This feature adheres to the interaction permission
  - Portal Placement
    - in development
  - VRChat Creator Companion (VCC) 1.0.0
    - At this time, optional

### [2022/08/26](https://ask.vrchat.com/t/developer-update-26-august-2022/)

- Schedule Update
  - weekly since 2022/09/08
- Release Schedule
  - 2022.2.2p3 Release
  - Main Menu Live Beta
    - In progress
- Feature Updates
  - Camera Improvements
    - Camera Flying Camera Drone for VR
    - Visual Shutter Effect
    - Camera Menu Changes and General Fixes
      - Take Photo is moved to begining
      - Exit is moved to camera itself
  - AMD FSA and nVidia Variable Rate Shading
    - Implementing AMD FSR Natively
      - cannot be implemented into VRChat natively
      - hard to implement with BRP (Built-in Render Pipeline) natively
      - Short version: Implementing FSR as documented and recommended by AMD isn’t possible in VRChat right now.
    - What about the OpenVR FSR DLL?
      - It's man in the middle so VRChat doesn't like
      - Too late in the render pipeline
        - FSR should be implemented before noise like bloom (post-processing)
        - This make bad view
      - Short version: Not Comfortable with VRChat
    - nVidia Variable Rate Shading
      - Good result in prototype
      - Short Version: significant benefit with acceptable impact. Prototyping
- Community Highlights
  - Summer VKet 2022
  - Slyfest: Azuria

### [2022/08/30](https://ask.vrchat.com/t/developer-update-30-august-2022/)

- Schedule Update announcement again
- Releases and Betas
  - 2022.2.2p3 release
  - VRChat Creator Companion (VCC) Released!
  - Main Menu Beta
    - In progress
- Features in Development
  - Camera Updates is in QA
  - Portal Placement design update
  - Other Features in progress


### [2022/09/02](https://ask.vrchat.com/t/developer-update-2-september-2022/)

- Schedule Change announcement again
- Releases and Betas
  - Main Menu Live Beta
    - Delayed to next week
- Feature Work
  - Even More Camera Updates
    - Flying Camera like Desktop Camera
    - Camera mode submenu
    - Camera exit button on camera itself
    - Moved warning for large resolution
    - Renamed Photo Name to VRChat_{date}_{resolution}.png
    - QM Camera Tab Reorganized
    - World mode camera will be reattached when entering world
    - Camera Shutter Effect
  - Visual Adjustments
    - See previous updates
    - going to come with Main Menu beta
  - Calibration Visualization
    - See previous updates
    - going to come with Main Menu beta
  - Portal Placement
    - returned from QA with bugs
    - go another round soon
  - OSCQuery
    - Will release library
    - Note: [released](https://github.com/vrchat-community/vrc-oscquery-lib)
  - Nameplates and Chatboxes in Mirrors
    - Nameplates and Chatboxes will face local camera in mirrors
    - text texture has been regenerated with more padding
    - fixed action menu blurry on tiny avatars
    - minor fixes to nameplate shaders
      - we fixed a case where weird outlining could appear around the voice “aura” in mirrors.
- Future Development
  - nVidia VRS and OSC-driven eye tracking
    - prototype / experiment

### [2022/09/08](https://ask.vrchat.com/t/developer-update-8-september-2022/)

- Schedule Update announcement again
- Release Schedule
  - Main Menu Live Beta (2022.3.1) is released
- Feature Updates
  - Live-beta Features
    - VR Camera Flight Mode
    - Visual Adjustments
    - Avatar Texture VRAM usage estimation
    - FBT Calibration Visualization
    - Avatar Haptics
    - CPU Thread Affinity
    - And other improvements
  - Favorite Worlds Website Update
  - Portal Placement is in the Open Beta
    - Will be on by default on live

### [2022/09/15](https://ask.vrchat.com/t/developer-update-15-september-2022/)

- Live Beta Updates
  - fixed various bugs
- Development Updates
  - Dang 58.00B bug
  - Main Menu Updates, Iteration, and Bugs
    - Microphone Settings in MM to replicate Quick Menu
      - Sensitivity
      - Noise Cancellation
    - Discovery Issues of new worlds
    - "Current World" button in the Worlds Tab
      - will back
    - A lot of bugfixes
  - Chatbox improvements
    - distance check fix
    - adjust width wo fit text
    - improve chatbox in mirror
    - sount effects on send and effect
    - add OSC endpoint for MessageComplete
    - Keybind for desktop. "Y" is used for now
    - adjusted nameplate and chatbox scaling to avoid clipping with avatar
    - new chatbox position options
  - Travel Error Improvements
    - More descriptive error messages

### [2022/09/22](https://ask.vrchat.com/t/developer-update-22-september-2022/)

- Spookality 2022
  - Yearly Jam
- Database Cleanup
  - Removed friends requests older than one year
- Live Beta Updates
  - build 1240 and 1241. see those changelog
- Ongoing Development
  - Move Bunch of options out of Quick Menu
    - Many features waiting Main Menu 2.0 are put to Quick Menu
    - move / copy to to Main Menu
      - MOVED:
        - Fallback Icon
        - Tooltips
        - UI Haptics
        - Avatar Touch Haptics
        - Slider Snapping
        - Gesture Icons
        - Home Instance Type
        - Auto Disable Cloning
        - Portal Prompt
        - Portal Mode
        - Clipping plane distance
        - Particle Limiter
        - Mirror Resolution
          - Clear Local Profile Data
      - DUPLICATED:
        - Responsive Menu
        - Chatbox settings
        - Display & Visual Adjustments
  - Avatar Haptics
    - Not supported on Quest
  - Improved Tracker Modesl
    - Note: This is part of FBT Calibration Visualization
    - Too spiky and not confortable so Sphere, System, Box, and Axis are implemented
  - World Discovery
    - Explore Worlds
    - Trending and Heat
      - Changed algorithm
  - Chatbox Improvements
    - sound on message send
    - VR Controller Binding
    - OSCQuery
      - Automatic OSC Configuration

### [2022/09/29](https://ask.vrchat.com/t/developer-update-29-september-2022/)

- Recent Downtime
  - Upstream Provider maintenance down-scaled servers for VRChat
  - To reduce impact, shutdown some endpoints 
  - next day, boiled up some complication results from previous day
  - Some countermeasures
    - changing infracture to make it unlikely to be affected by upstream provider issues
    - shifting infrastructure to more durable against domino effects
    - making changes to client to reduce load when come back from downtime
- Spookality 2022
  - Skipped. see developer update
- Live Beta Updates
  - build 1243
- Ongoing Development
  - Downtime mitigation client changes
    - See above
  - Show and Hide Avatar will be saved locally instead of server
    - Block Avatar Globally / Hide Avatar Globally is not affected by this change
  - Even more IK Improvements
    - Added some launch option-only features
    - added tracking & IK section on main menu in convert and safety
      - Legacy Calibration
      - Disable Shoulder Tracking
      - Freeze Tracking on Disconnect
      - IK Debug Logging
      - Uesr Real Height in metric
      - Auto mesureing height with HMD
  - Managing Favorites on the Website
  - Main Menu UI Polish
  - Avatar Menu Preview in Main Menu with big / small avatar
  - Hide Avatar by Distance Performance Improvement
  - Smooth First Person Camera Improvements
    - Smooth First Person Camera is useful feature for streaming
    - Not good with fast moving station, fixed
  - Toxicity and Toxic Behavior in VRChat
    - Groups can be used for surface are a of toxicity?
    - Ask for thought on Dev Update


### [2022/10/06](https://ask.vrchat.com/t/developer-update-6-october-2022/)

- Spookality Launch
- Live Beta Updates
  - Build 1244
  - Build 1245
- Show / Hide Avatar Player Moderation Storage
  - saved to `{APPDATA_LOCALLOW}\VRChat\VRChat\Settings\`
- New Development
  - VRCat's Variety Box for exploring worlds
  - VRChat Groups
    - Note: Fan Fact: [Requested by tupper on canny a bit before worked at VRChat and updated by tupper](https://feedback.vrchat.com/feature-requests/p/player-groups-guilds-or-circles)
    - Group Instances

### [2022/10/13](https://ask.vrchat.com/t/developer-update-13-october-2022/)

- UI 2.0 is Live
  - UI 2.0.1 is also LIVE (2022.3.1p1)
- Spookality
- Ongoing Development
  - Show/Hide Avatar Moderation storage changes are postponed
  - Account Security: Email Verification
    - Recommended to use 2-factor authentication
    - See [blog post](https://hello.vrchat.com/blog/email-verification)
  - Avatar Preview fixes
    - No more sleeping animations when closed / re-opened
    - Particles are removed
    - Scale better inside preview
    - 2D avatars should no longer be huge
    - direction of you open menu no longer affect size of preview havatar
    - more consistent avatar height calculation
    - blue diamond loading avatar and error avatar will not have their height calculated
    - Avatars should no longer pop out of the UI and appear in world space if their animations are mis configured
  - Personal Mirror Snapping
  - Udon Node Graph Upgrades
  - Knowledgeable / Helpdesk (help.vrchat.com) Upgrades
  - Avatar Upcoming Features are in next or few after updates

### [2022/10/20](https://ask.vrchat.com/t/developer-update-20-october-2022/)

- Spookality
- VRChat 2022.3.1p2
- VRChat Creator Companion announcement
  - see [blog post](https://hello.vrchat.com/blog/creator-toolbox-update)
  - Will be required in 2023!
    - Will remove unitypackage SDKs
- Ongoing Development
  - Hide Personal Mirror in Camera
  - New HUD Indicator for Push-to-Talk mode
  - Action Menu Tools Section
    - Toggle Personal Mirror
    - Toggle Face Mirror
    - Quick Access to Chatbox
    - Quick Access to Camera
  - Creator Companion New UI
    - Note: released as Creator Companion 2.0

### [2022/10/27](https://ask.vrchat.com/t/developer-update-27-october-2022/)

- VRChat Creator Companion
  - Will be required since January 2023
  - SDK@ will no longer offered for download since January 2023
  - Huge bug reports due to out-of-date SDK or wrong version of Unity and maintenance issues should be resolved with VCC
  - In the future, new space to help creators find all the docs, examples, news, and info that's relevant to them
- VRChat 2022.4.1 Open Beta
  - Live incompatible
  - Quest Hand Tracking (Quest 2 / Quest Pro)
  - Networking Updates
    - Network IDs are now baked to scene and can be managed by creators
    - Reduced Serialization cost on join
    - Those changes are heavily tested with closed beta.
  - VRCGraphics Functions
    - lile Graphics.Blit
  - Show / Hide Avatar Moderation Storage
    - staring with this build, Show / Hide Avatar Player Moderation are stored locally
  - And more: see patchnote
- Ongoing Development
  - Improved VRChat Support Features
    - Output Log Improvements
      - Flag Issue button on Quick Menu
    - Improved Knowledgeable Appearance
  - VRChat API will no longer provide username
    - Use user id as primary user key, instead of username
      - Note user id is usr_UUID
  - UI Improvements
    - Move Main Menu in Z axis (far/near)
    - Mute toggle on the volume sliders in Quick Menu
    - issues with displaying Japaneese Characters
  - Unmuted VRChat
    - VRChat had their mute since last Quick Menu update last year.
    - random saying are back~

### [2022/11/03](https://ask.vrchat.com/t/developer-update-3-november-2022/)

- VRChat 2022.4.1 Finger Tracking are live
- What About the rest of 2022?
  - holiday season
  - after 12/6~6, no major updates
- Spookality updates
- Creator Companion Reminder
  - Linux and MacOS Content Development
    - VPM CLI can be used
    - Note: At the time, it's not enough feature so author (anatawa12) created [vrc-get](https://github.com/vrc-get/vrc-get) as a alternative VPM
- New Years 2023 Plans
  - We celebrate New Years 2023 for EVERY timezones
  - Video Submission
  - Posters and Booths
- Ongoing Development
  - Groups!
    - aiming to be released before end of the year
  - More Full Body Tracking Settings
    - should be in next release
    - Adjust wist and knee angle to fine-tune preference
    - Calibration range and Arm vs Height Ratio settings are on Main Menu
  - Desktop Camera Gesture Icon Improvements and Fixes
    - Gesture are now fixed for Desktop Users when camera is open
  - Renaming Avatar Lists
  - Graphics.Blit Example
  - New Icons for User Profiles
    - GitHub
    - GitLab
    - Soundclioud
    - Bandcamp
    - Kofi
    - Linktree
    - Gumroad
    - Ticktock
    - Astrastion
    - Furaffinity
    - Pixiv
    - Sketchfab
  - Updated VRChat Home World Art
    - Updated to UI 2.0
  - Performance Work
    - reduced world load time
  - Usernames are dead
    - Removed from API
    - But rolled backed due to VRChat Client itself is using username
  - Continued Toxicity
    - See the article fore more details

### [2022/11/10](https://ask.vrchat.com/t/developer-update-10-november-2022/)

- Spookality
- Creator Companion Reminder
  - SDK2 Deprecation Reminder
- VRChat 2023 New Years Plans
  - NYE World Posters
  - Food Trucks
  - Storefronts
  - Entertainment Network (26h of video stream)
- 2022.4.1p2
  - fixes and small features
- Ongoing Development
  - Groups
    - No news but in progress
  - Even More Graphics Udon Hooks
    - Add temporary RenderTextures, 
    - Constructors for RenderTexture, Texture2D, Texture3D, and Sprite
  - Udon-controlled Vido Recording and Screenshots
  - Creator Companion UX Update Progress

### [2022/11/17](https://ask.vrchat.com/t/developer-update-17-november-2022/)

- Creator Companion Reminder
  - SDK2 Deprecation Reminder
- VRChat 2023 New Years Plans
  - Same as last week
- Ongoing Development
  - Groups
  - OSC Trackers
    - OSC-driven full body tracking is comming soon
    - This is hardware agnostic; we can use on Quest

### [2022/12/01](https://ask.vrchat.com/t/developer-update-1-december-2022/)

Skipped last week because it was holiday.

- About Open Beta
  - Groups are in Live Beta
    - first Stage of feature, not completed
    - See [blog post](https://hello.vrchat.com/blog/vrchat-groups)
  - OSC Trackers
    - Many Trackers
    - Sony Mocopi
  - p3 will be released, and groups (2022.4.2 or 2022.5.1?) will be later
  - Unity upgrade to 2019.4.40f1
- Creator Companion Reminder
  - SDK2 Deprecation Reminder
- New Years 2023 Plans
  - Same as last week
- Ongoing Development
  - Curated Community Packages
  - Creator Companion UI / UX Rework
    - VCC Community Package Listing
  - Improved VRChat Search UI Flow
  - Improved Settings Page
    - Settings Page Headers are updated to be more consistent with rest of Main Menu
  - Toxity and Safety
    - There was VRChat on ToxMod customers, but VRChat currently decided to not use it
  - Safety in VRChat

### [2022/12/08](https://ask.vrchat.com/t/developer-update-8-december-2022/)

- Groups is Live
- Creator Companion Reminder
  - SDK2 Deprecation Reminder
- New Years 2023
- Ongoing Development
  - VCC New Community Curated Package: Gesture Manager
  - VCC Updates
    - Improved ui of migration
  - Sneak Peak: Remote Image Loading for Udon

### [2022/12/15](https://ask.vrchat.com/t/developer-update-15-december-2022/)

- New Years 2023
  - Schedule
- Creator Companion Reminder
  - SDK2 Deprecation Reminder
- Ongoing Development
  - SDK Feature Sneak Peak
    - Remote String Loader
    - Video Recording
    - Image Saving
  - What's Planned for SDK in 2023?
    - Increasing Communication with Creators
    - Udon 2
      - Udon on WASM
    - Custom Graph Nodes
      - Note: Search Term: Custom Udon Graph Node, Custom Udon Node
    - Migration Process
      - Phase 1: (Current) using GraphCompiler
      - Phase 2: Migrate GraphCompiler to GraphSharp compiler
      - Phase 3: Migrate GraphSharp to Udon 2

Last Dev Update of 2022.

## 2023

### [2023/01/19](https://ask.vrchat.com/t/developer-update-19-january-2023/)

Happy New Year!

- Welcome back
- New Yesrs 2023
- VRCat Early Support Badge Distribution ending
- Creator Companion Reminder
  - SDK2 Deprecation Reminder
- Ongoing Dvelopment
  - Legend (Steel N Gold) returns
  - Remote String Loading
  - Fixed Camera Menu Scrolling
  - HUD Adjustments
    - For Desktop: notifications will now automatically get out of the way of menus
    - Gesture indicators should no longer bonk into the rest of HUD with left/right notification anchors
  - A Few Other Fixes

### [2023/01/26](https://ask.vrchat.com/t/developer-update-26-january-2023/)

- VRCat Early Support Badge Distribution ending
- Creator Companion Reminder
  - SDK2 Deprecation Reminder
- Ongoing Development
  - New Quick Menu Avatar Details
  - Audio Slider Fixes
    - Resetting audio settings
  - Avatar Sync Bug Fix
    - Race condition around loading avatar and syncing
  - Search Fine-Tuning and QoL
    - Candidate words
    - Clean search term on closing main menu
  - Quest Finger Tracking Updats
    - Pickup options for Fist / Pinch / Both
    - Gesture Lock
    - Jump Toggle
    - Cancel Gesture
  - A few more fixes

### [2023/02/02](https://ask.vrchat.com/t/developer-update-2-february-2023/)

- VRChat 2023.1.1 Release
  - Ton of quality of life features, imprvements, and some nice bugfixes
- Creator Companion Reminder
- Unity Version Upload Blocking
  - Blocking Unity versions older than 2018 (exclusive) will be blocked
  - Soon blocking 2018 as well.
  - SDK2 worlds / avatars will no longer be permitted for uploads soon
- Ongoing Development
  - Extra-Cozy Earmuffs
    - Earmuff cone shape
  - Indicator for Earmuffs on nameplate
  - Multi-layer camera mode
  - Grab to Adjust Full Body Tracking Calibration
  - Udon MIDI Playback
  - Cameras in Station Bugfix
    - Jittery camera ui in station
  - Portal UI Refresh

### [2023/02/09](https://ask.vrchat.com/t/developer-update-9-february-2023/)

- Creator Companion Reminder
- New Updates - Unity Version Upload Blocking
  - Blocking Unity versions older than 2018 (inclusive) will be blocked
  - SDK2 will no longer be permitted for uploads soon
- VRChat 2023.1.1 patches
  - 2023.1.1p1
    - Audio Volume Slider Fix
    - Few Fixes
      - Favorite avatar groups
      - index controller fixes
- Current Development
  - Udon Networking Tweaks
  - Json in Udon
  - Localized Tooltips
  - Camera Rule of Thirds Grid

### [2023/02/16](https://ask.vrchat.com/t/developer-update-16-february-2023/)

- Creator Companion Reminder
- Unity Version Upload Blocking
  - Older than 2019 is blocked
  - SDK2 will no longer be permitted for uploads soon
- VRChat 2023.1.1 patches (2023.1.1p2)
- Player Moderation Missing
  - Some player moderation (blocks mutes and etc) are lost during maintenance
- Ongoing Development
  - Avatar Performance Stat Changes
    - VRAM usage will now affect Performance Rank
      - PC Avatars
        - Excellent: <40MB
        - Good: <75MB
        - Medium: <110MB
        - Poor: <150MB
      - Quest Avatars
        - Excellent: <10MB
        - Good: <18MB
        - Medium: <25MB
        - Poor: <40MB
      - How do those values come?
        - PC
          - 8GB of VRAM is median
          - Instance size of 20 people
          - For VR Compositor and OS, 2GB is reserved, rest: 6GB
          - 1GB for world: 5GB
          - 5GB / 20 = 250MB
          - Note: I think there is 100MB for mesh and 150MB for texture
        - Quest Values
          - Quest has 6GB of Shared RAM between CPU and GPU.
          - VRChat have access 4GB of that
          - approximate scale-down by dividing OC values by 4.
      - How many avatars will become Very Poor?
        - 0.8% of avatars that were not already Very Poor will be ranked Very Poor after this change
        - Note: FYI: My (anatawa12's) avatar is affected by this change, I reduced texture size to 1/4 and it's now back to Good
    - Avatar Constraints
      - Not affext Avatar Performance Rank, but recommended max of 15
      - Only 15?
        - Many (and VRChat) thought cheap-like free, but sudden cost 30% more if "cliff" passed.
      - How'd you arrive at 15 being your recommended value?
        - Like VRAM. Take target and split by average instance but keep some room for heavier instances
      - How bad are constraints, really?
        - 0-682 enable constraints, each cost about 3.2µs.
          - This sounds tiny but 300 constraints costs 0.96ms, ~9% of 90FPS frame time
        - What's the "cliff"?
          - you hit 683 constraints, suddenly constraints now cost 30% more, 4.2µs per frame per constraint
          - In addition, **per-component** cost increases with each additional constraint you add
          - This appears to be a Unity bug.
        - What about disabled constraints?
          - IsActive on GameObject and Enabled on Behaviour will reduce cost so lo that constraint basically doesn't exists
          - However, IsActive on the component increases cost
      - Can't can't you count enable constraints?
        - You can animate them on
        - We have to scan every frame and it's not cheap so impossible
      - Does apply to all types of Constraints?
        - VRChat tests with Parent constraint each with one source.
      - Solutions?
        - Few solutions are looked at but none can be talked
        - contacting Unity regarding this buggy behavior
        - Remember: constraints are pretty new in 2019.4
          - Note: Constraints are added in 2018
  - Udon UI in the Quick Menu
    - in dvelopment
    - this is all subject to change
    - Note: not released
  - SDK 3.1.11 nearly ready for release!
    - remote image and string downloads, midi playback are in 3.1.11
  - VCC Web Updates
    - Note: Previously announced as Creator Companion New UI in [2022/12/08](#20221208)
    - Release Soon!
  - Groups Web interface
  - You can Pet the Cat
    - Pet the VRCat badge on VRChat.com/home

### [2023/02/23](https://ask.vrchat.com/t/developer-update-23-february-2023/)

- Creator Companion Reminder
  - Recently released SDK 3.1.11
    - Note: this includes features but minor part is not bumped :(
  - New VPM-compatible UnityPackages are available for non-VCC-compatible platforms or other limitations
    - Don't use those SDK for migrating projects
  - SDK2 are no longer available
- Unity Version Upload Blocking
  - Older than 2019 is blocked
- Ongoing Development
  - VRChat SDK 3.11.1 Release
    - Note: This must be typo of 3.1.11.
    - Use VCC to upgrade
    - Features:
      - Image Loader
      - String Downloader
      - Playback MIDI Data
      - Simulation time of Players
      - GameObjects with Networking Comonents
      - OnDeserialization with DeserializationResult
      - Improved UI for VRCUrlInputField
    - ImageLoader Example
  - Avatar Download Prioritization
  - Group Unblocking


### [2023/03/02](https://ask.vrchat.com/t/developer-update-2-march-2023/)

- Creator Companion Reminder
- Unity Version Upload Blocking
- VRChat 2023.1.2 Open Beta
- Ongoing Develpment
  - Native EyeTracking
    - The data is synced at IK Rate
      - Note: faster than expression
    - Few New Options in the Tracking & IK Menu
      - Debug View shows your look target
      - Force Eye tracking Raycast
    - OSC Support with several endpoints
      - `/tracking/eye/EyesClosedAmount`
      - `/tracking/eye/CenterPitchYaw`
      - `/tracking/eye/CenterPitchYawDist`
      - `/tracking/eye/CenterVec`
      - `/tracking/eye/CenterVecFull`
      - `/tracking/eye/LeftRightPitchYraw`
      - `/tracking/eye/LeftRightVec`
  - Avatar Download Prioritization Part II
  - Event Execution Order Documentation

### [2023/03/09](https://ask.vrchat.com/t/developer-update-9-march-2023/)

- We're Hiring!
- Creator Companion 2.0 Released!
- VRChat 2023.1.2 Update
- Ongoing Development
  - Upcoming Avatar Jam
  - AsyncGPUCallback
  - Udon Ownership Bugs
  - Google Drive removed from URL Whitelists

### [2023/03/16](https://ask.vrchat.com/t/developer-update-16-march-2023/)

- We're Hiring!
- SDK Email Authentication
  - Email Authentication is not supported in older SDKs.
    - Please Upgrade
    - or enable 2FA
- Avatars for Everyone Jam
  - Jam for Default Avatars
- Patches!
  - 2023.1.2p1
  - 2023.1.2p2
  - 2023.1.2p3
- Ongoing Development
  - SDK Warning Improvements
    - on Quest, default texture compression ETC to ASTC
      - Meta has suggested using ASTC since Oculus days
      - RGB Texture will see 11% VRAM Size reduction from this change
      - RGBA Texture will see 56% VRAM Size reduction from this change
      - ASTC doesn't support Crunch
      - ~~suggesting **against** using crunched textures~~
        - Reverted this suggestion
      - Crunched textures are good at one particular thin: reduce on-disk (Note: and download) size by lossy compression
      - On GPU, size is not changed
  - Avatar Pedestal Changes
    - Internal objects of avatar pedestals will be added to Udon access blocklist
    - Some creators were uing avatar pedestals for dynamic images but please switch to ImageLoader
  - Update on Data containers / Udon JSON
    - Getting close
  - Update on Udon UI
    - Implementing Unity Editor

### [2023/03/23](https://ask.vrchat.com/t/developer-update-23-march-2023/)

- We're Hiring!
- SDK Email Authentication
  - Upgrade SDK or enable 2FA
- Avatars for Everyone Jam
- 2023.1.2p4
- Ongoing Development
  - Creator Companion User Repositories
    - Note: A.K.A. Community Repositories
  - Udon UI Progress
    - Udon UI is very close to ready for internal testing
  - VRChat Quick Launcher Update
    - Ability to modify VRChat install a file path

### [2023/03/30](https://ask.vrchat.com/t/developer-update-30-march-2023/)

- SDK Email Authentication
  - Upgrade SDK or enable 2FA
- Old Unused Account Cleaning
  - old unverified, complete unused accounts from the database.
- Avatars For Everyone Jam Closing Soon
- Ongoing Development
  - VRChat on Android Mobile
    - Contents: Quest contents are available on Android
    - Launch Plans
      - First, available to VRChat Plus users
        - During this time, not freely avaiable on Play Store, you need unique URL with beta access
      - Full public release follows
    - iOS When?
      - working
    - Futher Info
      - There's RAM limit
  - VRChat on Unity 2021.3
  - Remote Player Collider Changes
    - Collider for remote players was sphere at player's feet
      - Different from local player's collider
      - This may cause unexpected behavior
    - Will be changed to local player's collider
- We're Hiring!

### [2023/04/06](https://hello.vrchat.com/blog/april-dev-update)

TODO: This is originally video: https://www.youtube.com/watch?v=5K4mMn_JLpk

- Group Updates
  - Group+ Instances
  - Group Public Instances
  - Group Queue
- World Capacity Changes
  - Soft cap and Hard will be changed to Recommend and Maximum
- Localization
  - German
  - French
  - Italian
  - Japanese
  - Korean
  - Spanish
- Imposters

### [2023/04/13](https://ask.vrchat.com/t/developer-update-13-april-2023/)

- Old Unused Account Cleaning
- Avatars For Everyone Jam
- 2023.2.1
- Quest 1 Deprecation
  - Due to Meta's depreciation of Quest 1 SDK.
- Ongoing Development
  - Server-Side Avatar Analysis
    - Avatar Stats will be delivered to you from servers instead of calculating locally in upcoming updates
  - This will result in better performance when using minimum allowed Performance Rank System

### [2023/04/20](https://ask.vrchat.com/t/developer-update-20-april-2023/)

- Old Unused Account Cleaning
- VCC 2.1.0 and Community Repositories
- VRChat 2023.2.1 patches
  - 2023.2.1p1
  - 2023.2.1p2
- Server-Side Instance Changes
  - If you try t join a full instance, you'll receive error before you start traveling
  - Users will be dened entry into instances that aren't network compatible and are told why
  - We fixed variety of issues related to how Group instances were displayed on the web
- Ongoing Development
  - Group Locations
  - Group Bans
    - Ban user from Group instances
  - More group stuff on the web

### [2023/04/28](https://ask.vrchat.com/t/developer-update-28-april-2023/)

One-day delay

- 2023.2.2 Opne Beta
- SDK EMail Authentication Changes
  - Many confused so switched to 2FA-based email authentication
  - If your SDK doesn't support 2FA yet, it's 4 years out of date. Please upgrade.
- Creator Companion
  - Community Packages
- Ongoing Development
  - Squishy Bones
   - Open Beta with 2023.2.2
    - Allow bones to stretch and squish
    - New Stretch Motion will allow motion to affect length of bone
    - New Max Squish for how much bones can squish
      - Colliders and grab can squish bones
      - `_Squish` is added
    - PhysBone Versioning
      - 1.1 changed a lot
  - Guided Mode
    - Open Beta with 2023.2.2
    - Simplified UI
  - New SDK Features
    - DataContainers and VRCJSon
    - VRCAsyncGPUReadback
    - Udon UI Updates
  - Group Filter Members by Role

### [2023/05/04](https://ask.vrchat.com/t/developer-update-4-may-2023/)

- Dev Updates - Now Bi-Weekly
  - Staring with this Dev Update
- Important Info / Announcements
  - Quest 1 Deprecation Date
    - After June 30th 2023, we will no longer provide support
- Updates
  - VRChat Clinet 2023.2.2
  - Creator Companion 2.1.1
  - VRChat SDK 3.2.0
- Ongoing development
  - Group Member Filtering and Sorting
  - More Udon UI Previews

### [2023/05/18](https://ask.vrchat.com/t/developer-update-18-may-2023/)

- Important Info / Announcements
  - Video Update - Creator Economy
    - Video: https://www.youtube.com/watch?v=e93QzjnVf9g
    - Blog post: https://hello.vrchat.com/blog/creator-economy
- Dev Updates are now biweekly!
- Quest 1 Deprecation Date Reminder

### [2023/06/01](https://ask.vrchat.com/t/developer-update-1-june-2023/)

- Dev Updates are now biweekly!
- Important Info / Announcements
  - VRChat 2023.2.3 Open Beta
    - Group Instance Types
    - Group+ Instances
    - Group Public Instances
    - Group Ban Improvements
      - Role for Manage Group Ban is added
    - As a part of Instance moderator action, "Ban from Group" is added in Quick Menu
    - Group Locations View and Group Search
  - ClientSim 1.2.5 Released
  - Twitch isn't working in VRChat video players?
    - Twitch just Reverted changes. Read article for more details
- Ongoing Development
  - More Group Thins on the Way
    - Udon UI UpdatesGroup Member cap will be raiced from 10,000 to 100,000
  - Performance Improvements
    - mirrors and shadows improvements
  - Settings Search
  - Login Flow Localization
  - Fixes for some REALLY annoying bugs
    - in 2023.2.3 open beta
    - Smooth behavior of camera in station
    - mouse horizontal sensitive is super low
    - Quick Menu and Main Menu cursor jump around in moving station
    - Shaking hand while sitting in fullbody creates body jitters
    - Video Players do not work if yt-dlp user config is present
    - The camera is unusable at high speeds
    - Votekick Notifications

### [2023/06/15](https://ask.vrchat.com/t/developer-update-15-june-2023/)

- Important Info / Announcements
  - 2023.2.3 Released!
  - VRChat Creators Documentation is now Live~
    - https://docs.vrchat.com/ is to learn about playing
    - https://creators.vrchat.com/ is to learn about creating
  - yt-dlp Updates are now live
  - Lyuma's Av3Emulator now in VCC (curated)
- Ongoing Development
  - Custom Emoji
    - Up to 5 emoji
    - 27 animation we can choose from
  - Quick Menu Settings Revamp
    - Updated Quick Menu Settings to match with Main Menu
  - Updated SDK Build Panel
    - Upload without entering play mode
    - Change thumbnails without full re-uploads
    - Better performance
    - Many small changes to help newer creators find their way around SDK
    - You can new upload your selected avatar even if other avatars in the scene have incorrect settings
  - Localization Update!
    - Release some languages near future
  - UI QOL Fixes
    - Expandable World Description
    - Improved VRChat+ UI
  - Unity Upgrade Update
    - Upgrade to 2022.3 instead of 2021.3
  - VRCPhysBones, VRCPhysBoneCollider and VRCContact Hard Limits
    - each have 256 component count limit
      - Not 256 bones, but 256 components

### [2023/06/29](https://ask.vrchat.com/t/developer-update-29-june-2023/)

- Important Info / Announcements
  - 2023.2.3p2 Released!
  - 2023.2.4 Open Beta and Delay
    - Avatar Scaling
  - ClientSim 1.2.6
  - VCC 2.1.2
    -  Fixes
- Ongoing Development
  - Standard Lite Improvements
    - Reflection Probes are in!
    - Proper occlusion support
    - Detail map support
    - different uv set support
  - IK Updates and Improvements
    - Better Behavior with Lock Both Spine
  - Avatar World Filter

next Dev Update will be on July 20th

### [2023/07/20](https://ask.vrchat.com/t/developer-update-20-july-2023/)

- Important Info / Announcements
  - 2023.2.3 Patches
  - Jummer!
  - VRChat Home Site Tweaks
    - VRChat External Service Form
    - Change and Favorite Avatars on the Site
- Ongoing Development
  - Avatar Scaling (still) in Open Beta
  - Recommended Searchers

### [2023/08/03](https://ask.vrchat.com/t/developer-update-3-august-2023/)

- Important Info / Announcements
  - 2023.2.4 Released!
    - 2023.2.4p1 Too!
  - 2023.3.1 Open Beta
    - OSCQuery
  - VRChat IK Beta
    - Tracker Rework - Adjust Motion Prediction
    - Tracker Reqork - Losing Tracking
    - Spine Improvements
  - VRChat Community Guidelines Update
- Ongoing Dvelopment
  - New VRChat+ Feature: UI Color Customization and Color Picker
  - Development Deep Dive - Avatar Scaling and Custom Scalers
    - The Problem
      - broken with Animating root transform
      - transform.localScale in Unity comes with a cost
    - The Solution
      - VRChat is using use PlayableGraph API
        - As like Av3Emulator does
      - Unity supports custom scripted nodes, which will be evaluated together with any animations
    - Almost There
      - Unity 2019 has bug if we changed scale with playable graph with root motion disabled
      - solution is simply add `void OnAnimatorMove(){/*do nothing*/}`
    - fixing bug feels to simple might be complexer than we'd think!

### [2023/08/17](https://ask.vrchat.com/t/developer-update-17-august-2023/)

- Important Info / Announcements
  - VRChat Android Alpha is now Live
    - VRChat Android alpha is avaiable for all VRChat Plus subscribers
  - Wuest Pro Eye Tracking Build Turned Off
    - Due to ~20% reduction in framerate and issues in development / build process
  - World Category Changes
- Ongoing Development
  - World Preloading
    - View Instance button on invite notification for preloading

### [2023/08/31](https://ask.vrchat.com/t/developer-update-31-august-2023/)

- Important Info / Announcements
  - VRChat 2023.3.2 Released!
  - Unity 2022 Open Beta
    - No reupload required
  - Test your content NOW
  - Don't upgrade projects
  - NEw SDK UI Now in Beta
    - 3.3.0 beta
  - Important note for Tool Developer
    - Upload process changed. Please migrate to API
- Ongoing Development
  - Groups Timeline
    - To see older group notifications
  - Multi sampled UI Shader for better text rendering
  - Android Trailer production
    - Detailed information on how to create android trailer video

### [2023/09/14](https://ask.vrchat.com/t/developer-update-14-september-2023/)

- Important Info / Announcements
  - Recent Unity News
    - Note: this is Unity license changes
    - VRChat isn't going anywhere
  - Unity 2022 Open Beta
    - No reupload required
    - Do not upgrade your projects
  - VRCSDK 3.3.0 has been released~
  - Spookality and New years eve info
- Ongoing Development
  - Merging ClientSim and UdonSharp into the Worlds Package 
  - We will keep UdonSharp and ClientSim source repositories synchronized as closely as we can,
    and will still accept issues and PRs from them for now.
    - Note: In my (anatawa12's) experience, no PRs are accepted from UdonSharp and ClientSim repositories long before this announcement
    - What will I need to Do?
      - Almost nothing
        - Creator Companion 2.1.3 will handle this
      - If you create Unity Editors for Worlds SDK, you can assume VRCSDK 3.4.0+ will have UdonSharp and ClientSim available
      - If you ise a Version Define, those will no longer exist!
        - You should use the worlds package instead
        - VRChat checked over 100 popilar community packages and found only one which did this, so it's unlikely you'll be affected
          - Note: I (anatawa12) have the package affected by this change and issue is opened from VRChat member. I was surprised that the package is known by VRChat.
  - Letter from VRChat Security Team
    - talk about avatar ripping
  - Imposters
  - New VRChat Home Profile View

### [2023/09/28](https://ask.vrchat.com/t/developer-update-28-september-2023/)

- Important Info / Announcements
  - Spookality 2023
  - VRChat 2023.3.3 Open Beta
    - Unity 2022 Open Beta
      - No reupload required
      - Do not upgrade your projects
  - New Web Profiles
    - See previous update
- Ongoing Development
  - New Search Algorithm

### [2023/10/12](https://ask.vrchat.com/t/developer-update-12-october-2023/)

- Important Info / Announcements
  - VRChat 2923.3.3 Rollback and Open Beta PART TWO
  - Unity 2022 Open Beta
    - No reupload required
    - Do not upgrade your projects
  - Spookality 2023
  - New Uears 2024!
  - SDK Semantic Versioning
    - VRChat declared to use semantic versioning however, not following semantic versioning
    - Feedback post regarding increment of SDK to 4.0,0 in 2022 versions which reflects community-based point of view as to what VRChat have been doing.
    - Anatawa12 suggested `Branding.Major.Minor.Patch` but use laternative name: Branding.Breaking.Bumps
      - Branding: major shifts between an incompatible system
      - Breaking: incompatible API changes
      - Bumps: backwards-compatible feature additions
- Ongoing Development
  - Mobile Native UI
  - Content Gating: Reporting Missing Warnings
  - ScreenSpace Canvas Changes for Mobile Development

### [2023/10/26](https://ask.vrchat.com/t/developer-update-26-october-2023/)

- Important Info / Announcements
  - VRChat 2023.4.1 and Unity 2022 is OUT!
  - Spookality 2023
  - Note from Release team: What happened with 2023.3.3?
    - Read article for more details
- Ongoing Development
  - None - 2022 is the one

### [2023/11/09](https://ask.vrchat.com/t/developer-update-9-november-2023/)

- Important Info / Announcements
  - We're going to Anime NYC!
  - VRChat is now on Pico Store!
  - Submissions for VRCNYE2024 are open!
  - Spookality 2023 ending soon
- Ongoing Development
  - Imposters coming soon!
  - SDK for Unity 2022 progress
  - New Udon Mobile Feature: OnScreenUpdate

### [2023/11/22](https://ask.vrchat.com/t/developer-update-22-november-2023/20878)

- Important Info / Announcements
  - Creator Economy Open Beta is LIVE!
  - Terms of Service and Privacy Policy Updates
    - For Creator Economy
  - 2023.4.2 Open Beta
    - Content Gating
    - Imposters
    - Updated search UI
    - Improved shaders features 
      - better Shader Fallback System
      - better standard lite
      - supersampled ui
    - Improved Interaction
    - Quick Menu here page no longer starts out scroll o the bottom
  - VRChat New Years Eve 2024
- Ongoing Development
  - UI Focus View (for mobile)
    - Features under consideration
      - Present world-space canvas in simulated screen space
      - ensure interaction use as usual
      - enable pan and zoom
      - enter focus view by pressing on a ui element
      - exit focus view via screen-space icon
      - opt-out feature via website (similar to Avatar Scaling)
    - Other possible features
      - Enable on Desltop on VR
      - Catalog all canvases, allow selection via new menu
      - enable creators to set default view parameters
      - enable creators to opt-out per-canvas

### [2023/12/07](https://ask.vrchat.com/t/developer-update-7-december-2023/)

- Important Info / Announcements
  - VRChat Mobile no longer requires VRC+!
  - VRChat 2023.4.2p1 and 2023.4.2p2 released
  - New Years 2024 SOON!
  - Content Gating Changes
    - age based filtering is disabled temporarily
    - Extreme Horror, Excessive Gore, Extreme Violence were removed from age-based forced gating
      - Many too careful to tag those
- Ongoing Development
  - What's Security Checks Failed
    - Checks for reducing crashers
    - Not sharing limits but very high
    - if false positive, please contact VRChat Support
  - Head-Chopping, Reverts, and more
    - VRCHeadChop
    - nVidia Variable Rate Shading

### [2024/01/04](https://ask.vrchat.com/t/developer-update-4-january-2024/)

- Important Info / Announcements
  - Upgrade Your Projects to 2022
  - New Year's Eve Celebrations
    - What was that Outage during NYE?
  - What else on the Horizon
    - Sanrio Fest

### [2024/01/18](https://ask.vrchat.com/t/developer-update-18-january-2024/)

- Creator Economy January 18 update
  - video: https://www.youtube.com/watch?v=6B23zpIqgA8
- Communication with creators
  - apologize for 2022 update lack of communication
- What's next for Creator Economy
  - When Can I start celling?
    - Soon!
- Requests: Oe=time and automatic subscriptions
- Transparency and Look Behind Curtain
  - Planning for this year

### [2024/02/01](https://ask.vrchat.com/t/developer-update-1-february-2024/)

- Important Info / Announcements
  - Next Video Update: February 22
    - Talk abut Creator Economy
- Ongoing Development
  - Small Update on Custom Head Chops
  - Group Location on Web
  - Notifications Updated on Web
    - Closely with VRChat client
  - Close non-Public Instance
  - Group Role Changes for Everyone
    - Role named Eveyone is added
  - Quality of Life Fixes
    - Click Menu Header to scroll to top
    - Keyboard Text Field has Clear button
    - Button on Main Menu User Details to view avatar details
    - Go Home Yes button problem fix
  - Camera Changes better transparency handling in worlds iwth post processing
  - Avatar Contact Changes
    - Avatar contact receivers and senders that overlap by default will now initialize correctly

### [2024/02/15](https://ask.vrchat.com/t/developer-update-15-february-2024/)

- Important Info / Announcements
  - Submit your Application to join VRChat's Creator Economy
  - Creator Economy SDK Update (3.5.1)
- Ongoing Development
  - Standard Lite Improvements for Worlds   
  - Localization for VRChat Continues
  - New: AnimatorPlayAudio State Behavior
  - VRChat on We Update (Honse)

### [2024/02/29](https://ask.vrchat.com/t/developer-update-29-february-2024/)

- Creator Economy Updates
  - Opened up for new celler
- Udon 2
  - Going to closed beta
- Persistence
  - Save infomation to users
  - Player objects
    - might not be persistent
- User Research
  - suevey for users
- VRChat Plus Improvements
  - extra features soon

### [2024/03/14](https://ask.vrchat.com/t/developer-update-14-march-2024/)

- Important Info / Announcements
  - Join the Creator Economy
  - Come and join the Space Jam
  - Venice Fil Festival Submissions ar eOpen~
- Ongoing Development
  - Group Ownership Transfer
  - Upcoming Changes to Standard Lite & More
  - Udon2 Sneek Peak
    - There is performance improvements
  - Runtime URL Construction for Udon
  - New Udon Event for Detecting Input Type
  - View Fallback Shaders for your Local Avatars
  - Avatar File and Memory Limit Changes
    - When are these limits coming to use?
      - July 16 (2024/07/16)
    - 1200MB => 500MB in uncompressed size
    - 500MB => 200MB in compressed size

### [2024/03/28](https://ask.vrchat.com/t/developer-update-28-march-2024/)

- Important Info / Announcements
  - Space Jam Submissions Close April 5th
- Ongoing Development
  - Web Updates
  - Group Ownership Transfer is Live
  - Everyone Role
  - Updates to our Canny!
    - We can see feedback without login

### [2024/04/11](https://ask.vrchat.com/t/developer-update-11-april-2024/)

- Important Info / Announcements
  - Space Jam Winners SOON
  - 2024.2.1 Open Beta
- Ongoing Development
  - Imposters Update!
  - User Profile Language Improvements
    - Many languages are added
  - Group Changes
    - Remove user from group no longer send notification
    - Warn / Kick in Group Instances will show in Audit Log
    - Group bans will soon allow an optional reason
  - Website Updates
    - Change Status on Web
    - Cancel / Refund buyers subscription
    - Group post image scale properly
    - resetting password problem fixed
  - Worlds SDK Improvements
    - new inspector
    - help links
  - ClientSim Tools for Persistence
    - Save/Load PlayerData from JSON File
    - Show Current Keys and values for local / remote players
    - a button to clear data
    - refresh button if you edit manually
    - button to open folde
  - Player object tools
  - Copy/Paste improvements in the graph
  - Creator Documentation Updats
    - From server pull requests or VRChat team
      - Added a new page for the Animator Play Audio state behavior on avatars.
      - Added a new page for the VRC Head Chop component on avatars.
      - Added a new page for byte and bit operations in Udon.
      - Added a new page about the Udon VM and Udon Assembly. (Thanks @20kdc !)
      - Added release notes for the latest SDK release.
      - Added the OnInputMethodChanged event and its arguments for Udon.
      - Added an example on how to use String Loading in Udon.
      - Restructured the first steps of Create Your First Avatar.
      - Published the Creator Economy documentation.
      - If you’d like to apply as a seller, please send us an application 3.
      - Added a section on animator parameter mismatching. (Thanks @anatawa12 !)
      - Added more details on to use VRC Station properly. (Thanks @jellejurre !)
      - Added an introduction and performance tips to VRC Mirror reflection.
      - … and more!
  - Home world improvements

### [2024/05/02](https://ask.vrchat.com/t/developer-update-2-may-2024/)

- Important Info / Announcements
  - Golden Week in Japan features
- Ongoing Development
  - The Input Update
  - Cross-Platform Hand tracking
  - SteamVR Input 2.0
  - Localization to OpenBeta
  - SDK May 2024 Roadmap
  - Content-refresh websocket event fixed
  - iOS conversion for avatars
  - VRChat Constraints
  - Web Team Updates
    - Added tools for uploading custom animated emoji
    - Reduced code loaded to view given page on the website 
    - launch page provide locked / unlocked information
    - fixed issue breaking password reset from
    - fixed issue casing explore worlds page
    - fixed VRChat credits symbol appear as square
    - Marketplace page
  - Change sto Instance APIs and Auto Creation
    - Changing ID to UUID-based
    - Instance Create API
  - New Home World Update

### [2024/05/16](https://ask.vrchat.com/t/developer-update-16-may-2024/)

- Important Info / Announcements
  - Signups for iOS Closed Beta
  - Website Changes
    - Signup form for iOS
    - Forget Email Address button
    - Some Changes
  - Reminder: New Homeworld coming soon
- A bit of tease
  - download size reduction with worlds?

### [2024/05/30](https://ask.vrchat.com/t/developer-update-30-may-2024/)

- Important Info / Announcements
  - VRChat GEAR
- Ongoing Development
  - Localization Update: Hebrew
    - RtL support
  - Boop!
  - VRChat Constraints Revisited
  - Avatar Download / Uncompress Size Limit Reminder
- Next Upcoming VRCChat Ham
  - Summar Music Fest

missing 2024/06/13

### [2024/07/11](https://ask.vrchat.com/t/developer-update-11-july-2024/)

- Announcements
  - Summer Music Jam is Ongoing!
  - Pico Users - Update Your OS!
  - Final Reminder for Uncompressed and Download Size Limits
  - Dynamic Bone Conversion is Going Away (soon)
- Ongoing Development
  - Website Updates
  - Mipmapping Experiments
    - Better algorithm for mipmapping
  - Constraints Update
  - Age Verification

### [2024/07/25](https://ask.vrchat.com/t/developer-update-25-july-2024/)

- Announcements
  - Summer Music Jam is Still Open!
  - About last "Security Update"
    - combat avatar ripping
  - Talk about last dev upd
    - update roadmap in august
  - Heads up creator docs contributors
- Ongoing Development
  - Unity AI Navigation
  - VRChat Constraints Update
  - SteamVR Skeletal Hand Tracking
  - SteamVR Input 2.0
  - More Web Updates
  - Portals Visuals

### [2024/08/08](https://ask.vrchat.com/t/developer-update-8-aug-2024/26017)

- Announcements
  - A Moment of Remembrance
  - iOS Closed Beta Launch is Imminent
    - A Note about iOS Content
      - Everyone can upload for iOS
      - Hand-converted popular avatar from Android to iOS
      - Fallback system for worlds
      - Fallback system for avatars are still evaluating
  - Security Update - Update
    - You have to use avatars from "Public" or your own ones with local tests.
  - SDK Roadmap is in next update
- Ongoing Development
  - Favorite Friends is now on the website
  - Invite Offline Users
    - Active on Web OR mobile
  - New Status Icons
  - Camera Updates
    - Portrait Orientation
  - Show Focus
  - Ukrainian Laughing

### [2024/08/22](https://ask.vrchat.com/t/developer-update-22-aug-2024/)

- Announcements
  - Summer Music Jam Winners
  - Creator Roadmap is Updated
  - Avatar Limit Enforcement
  - 2023.3.1 Release
  - New Getting Started Guide
  - VRChat Wiki is Live
  - Avatar Self-Destriction Changes
- Work in Progress
  - New Features in Udon
    - Array.Sort
    - System.Random
    - StringBuilder
    - Regular Expressions
    - Type
      - IsSubclassOf
      - IsInstanceOfType
      - IsSubclassOf
      - BaseType
  - Automatic Avatar Optimizer

### [2024/09/05](https://ask.vrchat.com/t/developer-update-5-sept-2024/)

TODO
