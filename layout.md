# ios-
///
import UIKit

class ViewController: UIViewController {

    @IBOutlet weak var imageview: UIImageView!
    
    @IBOutlet weak var tilabel: UILabel!
    
    
    @IBOutlet weak var userimage: UIImageView!
    
    @IBOutlet weak var username: UILabel!
    
    @IBOutlet weak var prlabel: UILabel!
    
    @IBOutlet weak var deplabel: UILabel!
    
    @IBOutlet weak var widlabel: UILabel!
    
    @IBOutlet weak var helabel: UILabel!
    
    override func viewDidLoad() {
        super.viewDidLoad()
        // Do any additional setup after loading the view.
    }

    override func viewWillAppear(_ animated: Bool) {
        
        tilabel.text = "HATTEFJÄLL"
        username.text="방선우"
        prlabel.text = "10,000"
        deplabel.text = "68cm"
        widlabel.text = "68cm"
        helabel.text = "110cm"
    }
        override func didReceiveMemoryWarning() {
            super.didReceiveMemoryWarning()
        }
}
///
