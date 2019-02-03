platform :ios, '10.0'

target 'TrustKeystore' do
  use_frameworks!

  pod 'BigInt', inhibit_warnings: true
  pod 'CryptoSwift', '~> 0.10.0'
  pod 'TrezorCrypto', inhibit_warnings: true
  pod 'TrustCore', :git=>'https://github.com/liweiz/trust-core-moac', :branch=>'commit_f987ee1', inhibit_warnings: true
  pod 'SwiftLint', '0.23.0'

  target 'KeystoreBenchmark'
  target 'TrustKeystoreTests'
end
