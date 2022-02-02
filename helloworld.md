# ios-
///
import UIKit

class ViewController: UIViewController{
   
    @IBOutlet weak var dragoned: UILabel!
    
    @IBOutlet weak var protoss: UILabel!
    
    @IBOutlet weak var terran: UILabel!
    
    @IBOutlet weak var dragon: UIImageView!
    
    @IBOutlet weak var zeratul: UIImageView!
    
    @IBOutlet weak var ranor: UIImageView!
    
    override func viewDidLoad() {
        super.viewDidLoad()
        // Do any additional setup after loading the view.
        print("hello world")
    }
    override func viewWillAppear(_ animated: Bool) {
        print("viewwillappear")
        dragoned.text = "dragon"
        protoss.text = "zeratul"
        terran.text = "jim raynor"
        dragon.image = UIImage(named: "dragon")
        
        
        
        
    }
}
///
