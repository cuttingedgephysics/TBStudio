TBStudio
===

For more information visit [tight-binding.com](https://tight-binding.com)

TBStudio is a technical software package to construct Tight-Binding model for nano-scale materials. It is a powerful and easy to use software package to construct Tight-Binding (TB) model for nano-scale materials. Starting from the simplified linear combination of atomic orbitals method in combination with first-principles calculations (such as OpenMX or Vasp packages), one can construct a TB model in the two-center approximation. Using Slater and Koster approach we calculate the TB Hamiltonian of the system and use a nonlinear fitting algorithm to find the best entries for both Hamiltonian and overlap matrices to reproduce the first-principles data. We obtain expressions for the Hamiltonian and overlap matrix elements between different orbitals (s, p and d orbitals with or without spin-orbit coupling) for the different atoms and present the SK coefficients in an orthogonal or nonorthogonal basis set. Furthermore, by using TBStudio one can generate code in a preferred programming language such as C++, C, Fortran, Mathematica, Matlab, and Python. TBStudio is a cross-platform application with a graphical user interface design that is user-friendly and easy to work with. This application is written in c++. This software is written by wxWidgets including OpenGL and LAPACK library.

<img src="https://tight-binding.com/wp-content/uploads/2019/09/TBStudio1-1024x550.png" width="400"/> <img src="https://tight-binding.com/wp-content/uploads/2019/09/TBStudio2-1024x550.png" width="400"/>

Getting Started
===

### Installation
1. Downoad from here [tight-binding.com/download](https://tight-binding.com/download). Check also [Github Releases](https://github.com/mohammadnakhaee/tbstudio/releases).
2. TBStudio is provided as a pre-compiled package. So there is no need to compile TBStudio.
3. You can also compile it. Just follow the steps in [github workflow](https://github.com/mohammadnakhaee/tbstudio/tree/master/.github/workflows).

#### Windows
TBStudio for windows is a portable version and there is no need to install it.
So just extract it anywhere and run it.

#### Debian based linux
You need to install it using the following command
sudo dpkg -i tbstudio-1.5.0-amd64.deb

#### RPM based linux
tbstudio-1.5.3.fc30.x86_64.rpm (Compatible with Fedora 30 Workstation)

#### MacOS
1. Double click on TBStudio-macos-11-1.5.3-64bit.app.tar.gz to extract the app
2. Drag and drop the TBStudio app into Applications folder located in the left toolbar.
(TBStudio.app has not been signed and you may need to solve it for your computer by yourself)

#### Other platforms
For more information visit [tight-binding.com/download](https://tight-binding.com/download).
Check also [Github Releases](https://github.com/mohammadnakhaee/tbstudio/releases)

### Example for Graphene
1. Launch TBStudio
2. Assumed you already downloaded the examples from [tight-binding.com/examples](https://tight-binding.com/examples)
3. Go to Graphene folder and open the file model.tbm
4. Press the Start button from Main-Ribbon > Analyze > Fitting.
5. The SK parameters tab will be shown. In terminal one can monitor the regression analysis.
6. Now the time for magic! What program language have you written your own Green’s Function calculation? Which language do you prefer to start your code? C++, C, Fortran, Mathematica, Matlab, and Python? It does not matter. We generate for you the Hamiltonian in your preferred programming language. Go to Main-Ribbon > Wizard > Code Generator and generate your own code as C++, C, Fortran, Mathematica, Matlab, and Python.
Hope you enjoy TBStudio

### Release summary
#### New in Version 1.5.0
The tight-binding model can be exported in format of PyBinding package
Sheet table added to arrange on-site and SK parameters
SK Table can be exported as a text file
Band-structure can be exported in TEX format

#### New in Version 1.4.0
Save Band-structure as an image in EPS, PNG, JPEG, TGA
Save Structure image as BMP, PNG or JPEG formats
Bug fixed for Band-structure visualization in a virtual machine
Bug fixed for mouse wheel zooming in windows 7

#### New in Version 1.3.0
Spin-Orbit Coupling (SOC) was added to the calculation
Code generator supports also SOC, non-orthogonal TB-Model or a system including both of them.
We added many examples with their references.

#### New in Version 1.2.0
In this version, one can also load both Unit-cell and Band structure from Vasp XML.
CIF output was added.
Weight function was added in the setup panel. One can paint on band structure to increase or decrease the weight function for input data.
Code generator supports now non-orthogonal TB-Model.

#### New in Version 1.1.0
Code Generator Tool for generating the code for the final band-structure.
