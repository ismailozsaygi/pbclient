## CPITemplate
##### Version: 10
----
### Features
1. Now Jenkins build informations *(Item name, build number and passed build parameters)* will be available on **SROptions** debug panel Works on builds only 
2. **UIScaleUtility** added. *(In case "Canvas Scaler" doesn't work properly on differently shaped popups etc. this utility may be used to scale content responsive to the screen resolution)*
----
### Fixes
1. Fixed using statement of `UnityEditor.iOS.Xcode` in `AutoBuilder.cs`
2. Fixed the initial position of moving coin animators
3. Now emoji background animation/tween will not be freezed after a short period of time
	1. Animation/tween won't skip frames from now on
4. Default level text will no longer stuck at value 14
5. Now gauge bar will be only available if ads are available
	1. When ads are not available, coins won't multiply anymore
6. Claim reward/Reject buttons will not be available before fake leaderboard animations
7. Fixed the default position of CoinElement in GameOverPanel
----
