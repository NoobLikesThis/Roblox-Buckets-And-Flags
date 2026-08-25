# FAST FLAGS
FFlags are a set of configuration flags that Roblox use to enable and disable features without needing to push a new update.

FFlags are currently restricted and only a few of them are allowed to be used without injection or a proxy.

Applications that let you use blacklisted FFlags:

[FLEASION (GITHUB)](https://github.com/fleasion/Fleasion/releases)

[FLEASION (ALTERNATIVE LINK)](https://fleasion.github.io/)

[FIDDLER EVERYWHERE (PAID)](https://www.telerik.com/download/fiddler/fiddler-everywhere-windows)

[FIDDLER EVERYWHERE (CRACKED VERSION)](https://github.com/NoobLikesThis/fiddler-everywhere-patch-automated/releases/download/frsss/Fiddler-Everywhere-V7.8.0-Patched.zip)

[XSDR INJECTOR (BUGGY)](https://github.com/creatornawaf/XSDR-Injector/releases)

There are two FFlag links which is [this link (NOT OWNED BY ROBLOX)](https://raw.githubusercontent.com/MaximumADHD/Roblox-Client-Tracker/refs/heads/roblox/FVariables.txt) and [this link (OWNED BY ROBLOX)](https://clientsettingscdn.roblox.com/v2/settings/application/PCDesktopClient)

The first link is an unofficial github repo which dumps every fflag into a txt for anyone to see.

The second link is the official roblox link that roblox uses for setting default FFlags on the bucket ```Production``` [Info here](#buckets)

# BUCKETS/CHANNELS
## buckets
For the second link in the ```FAST FLAGS``` section, if you are using a custom bucket such as ```ZAFlag``` and ```ZFlag``` for example, the link would be either [this](https://clientsettingscdn.roblox.com/v2/settings/application/PCDesktopClient/bucket/ZAFlag) for ```ZAFlag``` or [this](https://clientsettingscdn.roblox.com/v2/settings/application/PCDesktopClient/bucket/ZFlag) for ```ZFlag```

Using FFlags to use a custom FFlag such as [this](#bucketflag) will NOT change your default FFlags.

Roblox have these things called "buckets" which are similar to a normal roblox version which can bring new/testing features to your client.

If you want to use a bucket, use a tool like [fishstrap](https://fishstrap.app/) or [bloxstrap](https://bloxstraplabs.com/) to change your "channel" do something like ```ZAFlag``` or ```ZFlag```

Some buckets used to let you use an imgui ui onto roblox and use dev tools (such as ```Zcanary``` and ```Zintegration```

The Channel ```Production``` is the default channel that you get when you first download roblox which is the finalised version of the latest roblox version.

Production has an alternative version named ```Live``` which is identical to ```Production```


## bucketflag
```json
{
    "DFStringChannelName": "channelname",
    "FStringDebugShowFlagState": "DFStringChannelName"
}
```
