source 'https://github.com/CocoaPods/Specs.git'

platform :ios, '8.0'

inhibit_all_warnings!

pod 'AFNetworking', '~> 2.5'
pod 'Mantle', '~> 2.0'
pod 'BlocksKit', '~> 2.2'
pod 'MBProgressHUD', '~> 0.9'
pod 'ISO8601DateFormatter', '~> 0.7'
pod 'DCIntrospect-ARC', '~> 0.0'

target "nu-bill-unit-tests" do
    pod 'OHHTTPStubs', '~> 4.0'
    pod 'OCMock', '~> 3.1'
end

target 'nu-bill-acceptance-tests', :exclusive => true do
  pod 'KIF', '~> 3.0', :configurations => ['Debug']
  pod 'FBSnapshotTestCase/Core'
end