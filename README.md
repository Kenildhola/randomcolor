# randomcolor
***************** viewdidload *********************************

viewMain.backgroundColor = .random

********************** randomcolor ********************************

extension UIColor {
    static var random: UIColor {
        return .init(hue: .random(in: 0...1), saturation: 1, brightness: 1, alpha: 1)
    }
}
