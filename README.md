# ondoc-jitsi
кастомизированная версия jitsi	1) cd / && mkdir /tmp/repo
2) cd /ondoc-jitsi
3) npm install

# ios
https://github.com/jitsi/jitsi-meet/blob/master/ios/README.md
Building it yourself
1) cd ios
2) pod install
3) cd ../
4) xcodebuild -workspace ios/jitsi-meet.xcworkspace -scheme JitsiMeet -destination='generic/platform=iOS' -configuration Release archive

# android
https://github.com/jitsi/jitsi-meet/blob/master/android/README.md
Build and use your own SDK artifacts/binaries

# toolbar buttons
https://github.com/jitsi/jitsi-meet/blob/master/react/features/toolbox/components/native/Toolbox.js#L238