FROM windowsservercore

# Executed as cmd /S /C echo default
RUN echo default

# Executed as cmd /S /C powershell -command Write-Host default
RUN powershell -command Write-Host default

# Executed as powershell -command Write-Host hello
SHELL ["powershell", "-command"]
RUN Write-Host hello

# Executed as cmd /S /C echo hello
SHELL ["cmd", "/S"", "/C"]
RUN echo hello

############################

#RUN ["powershell", "-command", "Execute-MyCmdlet", "-param1 \"c:\\foo.txt\""]

############################

# # escape=`

# FROM windowsservercore
# SHELL ["powershell","-command"]
# RUN New-Item -ItemType Directory C:\Example
# ADD Execute-MyCmdlet.ps1 c:\example\
# RUN c:\example\Execute-MyCmdlet -sample 'hello world'

