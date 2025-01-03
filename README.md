YOu might already have all the libs installed, but if u dont:

# Install dependencies (windows/powershell):
* Create a fresh [virtual python enviroment](https://www.freecodecamp.org/news/how-to-setup-virtual-environments-in-python/) at the project root dir, or use whatever python you have installed (it will be polluted with new libs)
* run script ``./venv.ps1`` to activate the env, if you made one
* run script ``./install.ps1`` to install only the needed libs for this project

Then in your jupyter notebook select this venv or your python kernel and use the notebook.

The powershell scripts are simple af, u can easily rewrite their analogues to ur OS.