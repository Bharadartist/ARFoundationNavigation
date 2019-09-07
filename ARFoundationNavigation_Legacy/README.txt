Unity Version - 2019.0.2.1.f1
ARFoundation - 2.2.0 preview .3
ARCore XR Plugin - 2.2.0 preview .2

Issue

1 - Command Invocation Failure

Links
https://issuetracker.unity3d.com/issues/cannot-build-android-player-if-the-colour-space-is-set-to-linear
https://forum.unity.com/threads/cannot-build-android-player-with-linear-color-space-due-to-sdk-api-issue.643639/

Resolution
Uninstall java 10 and install java 8 from java updater

2 - Black Screen after deployment

Links
https://forum.unity.com/threads/ar-foundation-android-black-screen-on-first-launch-bug-il2cpp.671467/
https://github.com/Unity-Technologies/arfoundation-samples/issues/2

Resolution
LWRP has issues, go with legacy 3D for development

3 - Failed to build due to error in arcoreimg

Links
https://github.com/Unity-Technologies/arfoundation-samples/issues/165

Resolution
Check the Unity logs. See if there are enough feature points for the images in the image library
