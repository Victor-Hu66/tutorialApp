- push codes to github repo
- clone repo to pythonanywhere bash console
    - create env and active
    - install packages

- go to pythonanywhere / web section 
    - add a new app
    - select manuel config
    - select python package (3.9)

- go to bash console make ls and see manage.py (take path: pwd)
- source code and working directory : paste the directory

- paste env directory to virtualenv section

- right click wsgi open new section and keep django section delete others
    - uncomment codes
    - update path section with manage.py directory
    - update ... . settings (folder name)
    - save

- source code go to directory
    - .env add a new file
    - add secret_key etc.
    - save

- python manage.py migrate (in console)
- reload in web section and open the link