# python-template
python web server template

Only Support Python 3.X

## Usage

### 1. Create Project

~~~ Shell
git clone git@github.com:xp880906/python-template.git [project name]
cd [project name]
git remote remove origin
git remote add origin [your git repository address]
~~~

### 2. Make Virtual Environment

~~~ Shell
python3 -m venv venv
source venv/bin/activate
~~~

### 3. Write Dependencies

Write Packages To requirements.in
Then:

~~~ Shell
make compile-deps
~~~

requirements.txt & requirements-dev.txt will be generated.

requirements.txt for online mode, like docker container.

requirements-dev.txt for dev mode.

### Other

lint:
~~~ Shell
make lint
~~~
