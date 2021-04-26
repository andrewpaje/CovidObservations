# CovidObservations
Covid Observation Technical Exam for DW Morgan

Web service that uses Python Django to render simple JSON output from PostgreSQL DB query.

1. Start Virtual Environment for Python Django to run on using the following command (dependent on current OS):

| PLATFORM | SHELL| COMMAND |
-----------|------|---------|
| POSIX    | bash/zsh       | $ source \<venv\>/bin/activate        |
|          | fish           | $ source \<venv\>/bin/activate.fish   |
|          | csh/tcsh       | $ source \<venv\>/bin/activate.csh    |
|          | PowerShell Core| $ \<venv\>/bin/Activate.ps1           |
| WINDOWS  | cmd.exe        | C:\> \<venv\>\Scripts\activate.bat    |
|          | PowerShell     | PS C:\\> \<venv\>\Scripts\Activate.ps1 |

where \<venv\> is folder "venv" on project directory.
  
2. Once Virtual Environment is up and running, run the following command in project directory to start Web Server:
   $ (venv) python manage.py runserver
   
3. You may now access Web Application by going to your browser and typing the following url:
   http://localhost:8000/CovidObservations
