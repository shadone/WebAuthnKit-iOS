# Uncomment the next line to define a global platform for your project
platform :ios, '10.0'

target 'WebAuthnKitDemo' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  pod "PromiseKit", "~> 6.13"
  pod "EllipticCurveKeyPair", :git => "https://github.com/shadone/EllipticCurveKeyPair", :branch => "master"
  pod "KeychainAccess", "~> 4.1"
  pod "CryptoSwift", "~> 1.3.0"

  # Pods for WebAuthnKitDemo

  target 'WebAuthnKit' do
    inherit! :search_paths
    pod "PromiseKit", "~> 6.13"
    pod "EllipticCurveKeyPair", :git => "https://github.com/shadone/EllipticCurveKeyPair", :branch => "master"
    pod "KeychainAccess", "~> 4.1"
    pod "CryptoSwift", "~> 1.3.0"
  end

  target 'WebAuthnKitTests' do
    inherit! :search_paths
    # Pods for testing
  end

end
