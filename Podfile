platform :ios, '13.0'

target 'StudyPal SwiftUI' do
  
  use_frameworks!

  # Pods for StudyPal SwiftUI
  
  pod 'FirebaseAnalytics'
  pod 'FirebaseAuth'
  pod 'FirebaseFirestoreSwift'
  pod 'FirebaseStorage'
  
  post_install do |installer|
   installer.pods_project.targets.each do |target|
    target.build_configurations.each do |config|
     config.build_settings['BUILD_LIBRARY_FOR_DISTRIBUTION'] = 'YES'
    end
   end
  end
end
