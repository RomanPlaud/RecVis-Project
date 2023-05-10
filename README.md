# MVA Object Recognition project
Project realised for the MVA course "Object recognition and Computer Vision" supervised by Gul Varol and Mathis Petrovich. Project is based on [**"TEMOS: Generating diverse human motions from textual descriptions"**](http://arxiv.org/abs/2204.14109). 

## Report
Report with our contributions to find [here](https://github.com/RomanPlaud/RecVisProject/blob/master/report.pdf).

## Contributions
Our work focused on dealing with the "foot sliding" effect observed in several 3D motions generations. To address this issue we add a contact loss which supervises ground contacts of 4 joints of the feet. Results shows that quantitative state-of-the-art results are not deteriorated by the additional contact loss while the foot sliding effect is reduced.

## Code
Our modifications can be found [here](https://github.com/clemgris/transfer_VM) (which almost entirely rely on this [repo](https://github.com/Mathux/TEMOS)

### Grade 
19/20
