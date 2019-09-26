# ProgessHud using SwiftPackage

## How to use
**Open xCode Project**

    xCode Menu > File > Swift Packages > Add Package Dependency 
    > https://github.com/AtifNaveed/HudSwiftPackage.git 
    > Enter > Next > Finish

![alt image is missing](https://res.cloudinary.com/atifcloud/image/upload/c_scale,h_285/v1569500900/2_ocwgue.png)


## Usage
    var hud = SwiftyProgressHud()
    hud.show(view: self.view)

## Example

    import UIKit
    import SwiftyProgressHud

    class ViewController: UIViewController {
        var hud: SwiftyProgressHud!
    
        override func viewDidLoad() {
            super.viewDidLoad()
            hud = SwiftyProgressHud()
        }
    
        func showHud() {
            hud.text = "Loading"
            hud.show(view: self.view)
        }
    
        func hideHud() {
            hud.hide()
        }
    }

![alt image is missing](https://res.cloudinary.com/atifcloud/image/upload/c_scale,h_656/v1569500898/1_ddtx3s.png)


## Author

AtifNaveed, atif.gcucs@gmail.com



