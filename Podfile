platform :ios, '11.0'
inhibit_all_warnings!

target 'Swift-Base' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for Swift-Base
  # pod 'FSHelpers+Swift', :git => 'https://github.com/fs/FSHelper.git'

  # Analytics
  pod 'Fabric'
  pod 'Crashlytics'
  
  # Libraries
  pod 'Alamofire'
  pod 'SwiftLint'
  pod 'Moya'
  pod 'PromiseKit'

  target 'Swift-BaseTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'Swift-BaseUITests' do
    inherit! :search_paths
    # Pods for testing
  end
end
