```bash
sudo ln -sf $(pwd)/Xamarin.Sdk.iOS /usr/local/share/dotnet/sdk/3.0.100/Sdks/Xamarin.Sdk.iOS

cd App
MD_MTOUCH_SDK_ROOT=/usr/local/share/dotnet/sdk/3.0.100/Sdks/Xamarin.Sdk.iOS/XI dotnet build
```
