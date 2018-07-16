## How to run
`git clone https://github.com/ricsam/testVI.git cd && cd testVI/ios && open testVI.xcworkspace/`

## How this project was created

1. `react-native init testVI`
2. `cd testVI`
3. `yarn add react-native-voximplant`
4. Add Gemfile, see [Gemfile](https://github.com/ricsam/testVI/blob/master/ios/Gemfile)
5. Add Podfile, see [Podfile](https://github.com/ricsam/testVI/blob/master/ios/Podfile)
6. Run `bundler install` in the ios folder
7. On line 4 in the Podfile change `plugin 'cocoapods-fix-react-native'` to `#plugin 'cocoapods-fix-react-native'` (commented)
8. run `bundler exec pod install` in the ios folder
9. On line 4 in the Podfile change `#plugin 'cocoapods-fix-react-native'` to `plugin 'cocoapods-fix-react-native'` (uncommented)
10. run `bundler exec pod install` in the ios folder
11. run `open testVI.xcworkspace/`
12. Run the application


## Errors

### Run errors
<img src="https://snag.gy/Dbrcms.jpg" width="50%" />
<img src="https://snag.gy/3bMDYo.jpg" width="50%" />

## Build log
<img src="https://snag.gy/Hmbyzi.jpg" />

## Project
<img src="https://snag.gy/Nl6wCL.jpg" />
