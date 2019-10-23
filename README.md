```bash
sudo ln -sf $(pwd)/Xamarin.Sdk.iOS /usr/local/share/dotnet/sdk/3.0.100/Sdks/Xamarin.Sdk.iOS

cd App
MD_MTOUCH_SDK_ROOT=/usr/local/share/dotnet/sdk/3.0.100/Sdks/Xamarin.Sdk.iOS/XI dotnet build

## or alternatively ##
MD_MTOUCH_SDK_ROOT=/usr/local/share/dotnet/sdk/3.0.100/Sdks/Xamarin.Sdk.iOS/XI dotnet run
```

_Note:_ Xamarin.Sdk.iOS/XI is an unmodified copy of Xamarin.iOS 13.4.0.2 with WatchOS/TVOS and other parts deleted to make it smaller.
