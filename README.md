# Example Package

remember to set a ~/.pypirc file (or newer equivalent) with the Nexus login details
e.g.

[distutils]
index-servers =
    nexus

[nexus]
repository = http://localhost:8081/repository/localpypi/
username = <user>
password = <pass>

