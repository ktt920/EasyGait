# EasyGait

EasyGait is a user-friendly software platform that simplifies data collection process for mouse neuromuscular behavior (gait analysis). Building ontop of contrast-enhanced video recordings, EasyGait extracts gait metrics through manual paw-coordinate plotting on digital video. This approach replaces tedious ink-paw tracking, overcomes the tracking issues of fully or semi-fully automated detection systems, and eliminates the need for expensive commercial gait analysis equipment.

## Setup

1. **Install Required Python Libraries** : Open a terminal and install the required Python packages:
```
pip install opencv-python numpy pandas
```
>_Note: Creating a separate Conda environment for EasyGait is optional. The program only requires common Python libraries and should run in most standard Python / Python Libraries versions_ 


2. **Clone the EasyGait Repository** : If Git is installed, clone the repository in Terminal with: 
```
git clone https://github.com/ktt920/EasyGait.git
```
> _Note: You may also clone the EasyGait Repository through GitHub Desktop (Easier). 1. Open GitHub Desktop 2. Navigate to Current Repository -> Add -> Clone Repository 3. Select the URL Tab 4. Enter the URL (https://github.com/ktt920/EasyGait.git)._


3.  **Run EasyGait**
Run the python program by specifying the full file path.
```
(base) PS C:\Users\name> python "C:\Path\To\EasyGait\EasyGait.py"
```
> _Note: Replace the file path with the actual file path on your local computer. Locate EasyGait.py in File Explorer. Right click the file. Select "Copy as path." Paste the path into the terminal after "python." (python (Path))_ 
