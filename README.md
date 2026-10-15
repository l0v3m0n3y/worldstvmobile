# worldstvmobile
web api for worldstvmobile.com Browse 10528 free live TV channels from around the world by country and category.
# main
```swift
import Foundation
import worldstvmobile

let worldtv = worldsTvMobile()
let rain = try await worldtv.getStreamById(id: "TVRain.nl")
print(rain)
```

# Launch (your script)
```
swift run
```
