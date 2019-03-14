creating a flask directory:
make a directory
initialize git
make git ignore file
create setup.py (can copy from flaskr tut)
change name in setup.py
can create a dictionary called extras_require and make list of dependencies for testing 
create a virtual enviornment python3 -m venv (name of enviornment)
dont need virt env in git
activate env by source virtenvname/bin/activate
check virt env by using which
pip install -e . - in editable mode and looks for setup.py - runs flask package
flask is in setup.py requirements and is needed for this project according to setup.py
pip install -e '.[test]' installs tests needed dependencies
setup flask environment variables export FLASK_APP=flask_boilerplate 
export FLASK_ENV=development
create init directory
make a: create app function, index function and return app
