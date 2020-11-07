## Moving from Android to iOS

These are my notes from my experience transitioning from a long time Android user over to iOS in Fall 2020. Each item is my own personal experience of what I really observed - it's not a commentary on technical specs, or which vendor *should* do one thing or another, etc.

I moved from Android 11 on Pixel 2XL to iOS 14 on iPhone 12 Pro. Prior to the move, I took notes on the things that were upsetting me about Android, and the things I thought that I would miss or enjoy when I switched to iOS


### Week Negative N (time leading up to the switch)


#### Android annoyances
1. Android Auto
    1. Android auto requires cable
    1. Android auto won't let me use maps on the phone at the same time as car is connected
    1. Android auto UI has a ridiculously huge bottom bar that wastes screen real estate.
2. URL Handling
    1. URL handlers for apps trampoline through Webviews before arriving at the app, and sometimes seem to get "stuck" in the Webview
    1. Opening a link in the "Google Discover" feed page opens a Webview within Google Discover. Unlike with other apps, this Webview is immediately lost if you leave the Google Discover app.
    1. Sometimes apps will open a handled URL but then the app is hung
    1. Sometimes apps will open in response to handled URL but simply open to their splash screen or home screen, and not the URL
    1. Sometimes app URLs will open the Play Store page for an app you already have.
3. Back button out of apps sometimes seems wrong
    1. I think the main issue is how you arrived at the app. The back button may take you back to a different app that linked you here, or it may simply go back within the app you are now in.
4. No adblock in the browser
5. Fitbit Bluetooth sync slow sometimes, or requires a few refreshes
6. Switching audio device from Bluetooth to Phone and vice versa works, but requires 3 clicks
    1. But sometimes, for no reason, I'm not presented with alternate audio devices, even while bluetooth is connected

#### Android Pro's, which I anticipate to be unique to Android / Pixel

1. Always-on-screen
1. USB-C charging anywhere
1. Voice assistant has my Google Account
1. App logins with Google Account

#### iOS Unique Pro's (I hope)
1. Adblock in the browser
1. PAC/Data-PAC/MTE
    1. OK, I know this isn't part of my user experience, but I'm vaguely aware of it in the back of my head, so maybe it is for me. We got PAC and some data-PAC, but not MTE.
 
#### iOS Annoyances (TBD)
1. Self-congratulating BS keynotes with shit like "We replaced full-screen incoming calls with a notification and it changed the world"
    1. Seriously, watching the announcment for iPhone 12 made me feel like a tool. Am I just getting scammed by this marketing drivel?

### Week One

After one week, I've spent a few days on setup and transition and a few days fully "moved in" with the phone as my daily driver. I've mostly adjusted to the "learnable" UI functions, and in general I won't be commenting on things I feel are just a preference to adapt to.

In a very short summary:
1. There are indeed Android-only features that I miss
1. The iOS experience seems less buggy (indeed, many of my Android complaints were arguably just bugs, and my iOS experience has been almost entirely bug-free so far)
1. There are 
1. There are a ton of things that are virtually identical.

#### The Good
1. High quality built-in apps like Apple News, Apple Stocks, Compass. I haven't had an Android device include a built-in compass in a long while, and the Android compass always seems to be wildly out of calibration. The iPhone compass seems precise and accurate with no fiddling.
1. I use "Sign in with Google" for several apps, and it works just fine on iOS. I was worried about this.
1. The screen has good color at wide angles.
1. Ceramic shield, if it is as promised, is a nice surprise. I always go caseless. This phone feels tough. My Pixel 2 XL was tough enough to survive a few drops, but it didn't eventually accumulate some damage near the end of its life.
1. Things generally seem pretty fast.
    1. Yes, I was upgrading from a 3-year old device.
    1. Bluetooth syncs are fast. Fitbit doesn't require a bunch of refreshes to get it to sync. It just happens about 1-2 seconds after you open the app.

#### The Bad
1. No global camera shortcut
    1. I didn't see this coming. On Pixel 2, you can double-tap the power button and launch the camera from any context.
    1. On iOS, you have to do one of the following:
        1. Launch the camera app, but first unlocking the phone or swiping to the home screen, depending on what you're doing at the moment.
        1. Tap the camera button in the command center, only if the phone is already unlocked.
        1. Long-press the camera button on the lock screen (!). I don't want to wait for the phone to register a *long press*. Even worse: if you continue to hold the button, the camera app doesn't open until you let go. But if you let go too soon, you have to start over with a new long press. So the pressure to get the camera open as quickly as possible is all on you.
    1. YOu can al
        1. Swipe from right while on the lock screen, only if the screen is on. If you've recently used the lock button to turn the screen off, you will need to use the button to turn it back on. If you've simply pulled the phone from your pocket, you can swipe immediately, including while the screen is still dark. But if you press the lock button while the screen is about to come on, you will turn the screen back off, and need to turn it back on again before you can swipe. If you've pressed the lock button and then put your phone in your pocket, you will need to remember how recently you did this in order to know how to launch the camera. 
    1. All of the above has turned out to be big deal to me so far. When I want to get off a quick shot, my eyes are on my subject, not the screen, and my mind is on the subject and not trying to figure out what state my phone is probably in.
1. Google Maps scrolling is stuttery. It't not smooth like Google Maps on Android, or Apple Maps on iOS. Maybe this is Google's fault, but regardless, I use Google Maps and it's not smooth here.
1. No universal back button. This may be a design language choice by Apple. I've thought hard about this, and I think it's a bad choice.
    1. Maybe not all apps need a back button, but a lot of them do. When you have a device with primarily full-screen tasks, those tasks are going to be arranged in a stack, and you're going to be navigating backward in that stack a lot.
    1. I considered that perhaps Apple had invented some big-brain UI techniques that eliminated the *need* for a back button, and I could just adjust to the new paradigm. But in practice, tasks are still arranged in a stack, and most things *do* have some kind of way to go back. It just isn't consistent:
        1. Sometimes back is an arrow in the upper left.
            1. And this is the hardest possible place to reach on the screen for right-handers.
        1. Sometimes back is a word like "Done" in the upper left *or the upper right*
        1. Sometimes back is an arrow in the bottom left.
        1. Sometimes back is just a tap on a blank part of the screen
        1. Sometimes back is a swipe up
        1. Sometimes back is a swipe down
        1. Sometimes there's a tiny *extra back button* with the name of an app: the last app you were in.
            1. I actually like this one. If you've just entered an app, sometimes you want to go back to the last app, and sometimes you want to go back *within* the now-current app. Typically the former, I would guess.
        1. The incosistency comes with an additional cost: as a user, if you attempt a back gesture and nothing happens, you don't know if you've reached the bottom of the stack or done the gesture wrongly.
        Safari back button different too.
        \Some apps put it top left, some put it top right. This isn't a design language. Sometimes you tap a blank area of the screen. Sometimes it’s a tiny arrow under the clock.
Ok, but when there is a back button annotated for the app you’re going back to, this is a leg up on android. It’s useful to have “back within this app” and “back to the app that linked me here just this time”.  Upper left is still a dumb location for it though. 



#### The Medium
1. Siri is pretty responsive and sounds good. By gut feel, Siri's answers seem closer to the mark than Google Assistant's, but on par with Alexa's. I asked Siri “how many days are in October?” and Siri answered “It’s two days away”. Alexa is fine with this.
1. Keyboard has no comma and period.
    1. 
1. Face ID is neat, and it has been nice the two times already that I have had gloves on. But:
    1. It feels slower than Touch ID or fingerprint login on Android, possibly because it then requires an extra swipe to unlock after you authenticate. And I *want* the extra swipe - I don't want my phone unlocking without my explicit intent to do so - but it's nice on Touch ID that expressing that intent is the same action as providing the biometric.
    1. It does very well in the dark
    1. It does seem to improve over time - it was very fiddly about allowing me to have my head in my hands, or a pillow partly blocking my face, but it has improved, presumably as it better learns my face.

I have to reenter my iCloud password every time I install an app You can’t see any notifications because of the notchDoesn’t autocomplete my email address in text boxes for some reason No command center toggle for VPN Slippery flat edge is impractical for one handed useSometimes I don't know whether the screen is going to come on when I pick it upm or notNo wake lock for stopwatchAuto brightness is weak or laggy or broken Can’t filter gchat messages by favorites

The strange—-Google Authenticator barcodes are not compatible between android and iOS, and haven’t been for years. Something about seed length, or having == in the base64, or white space. 
Things I got used to----Swiping to home
