# docs
Nautilus Workshop samples documentation

## Get started

Clone the Github Repository

    git clone https://github.com/pravega/worshop-samples
    cd workshop-samples/docs

Create a Virtualenv

    virtualenv .venv
    source .venv/bin/activate
    pip install -r requirements.txt

Build the docs

    make html

Run autobuild

    sphinx-autobuild -H 0.0.0.0 -p 8080 . build/html
