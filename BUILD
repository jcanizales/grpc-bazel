
objc_binary(
    name = "BazelSample",
    srcs = [
        "src/main.m",
        "src/AppDelegate.m",
        "src/ViewController.m",
    ],
    hdrs = glob(["src/*.h"]),
    asset_catalogs = ["src/Images.xcassets/AppIcon.appiconset/Contents.json"],
    infoplist = "src/Info.plist",
    storyboards = ["src/Base.lproj/Main.storyboard"],
    deps = [
        "third_party/grpc/src/objective-c/RxLibrary",
    ];
)
