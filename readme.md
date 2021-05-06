# The Source of smileservices.github.io

Using Pelican to render static pages and handle the blog

## Install
Run these commands in order. Note: make sure you have pip/python3 installed
* Clone the project
`git clone --recurse-submodules smileservices/smileservices.github.io.project.git`
* Install dependencies
`pip install -r requirements.txt`

## Run
* Render the static pages
`make html`
* Start the server on http://127.0.0.1:8000/
`pelican content --listen`