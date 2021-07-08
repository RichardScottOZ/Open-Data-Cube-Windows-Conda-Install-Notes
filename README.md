# Open-Data-Cube-Windows-Conda-Install-Notes
rough notes on process to get it to work

- conda create env -n cubeenv

- conda install datacube
- conda install jupyter matplotlib scipy

- initdb -D mylocal_db

- #pg_ctl -D mylocal_db -l logfile start
- pg_ctl: could not start server

- [get rid of the logfile]

- Examine the log output.


- pg_ctl -D mylocal_db  start

- make this config file manually
- C:\Users\rscott\AppData\Local\Continuum\anaconda3\envs\cubeenv

- https://stackoverflow.com/questions/55367160/how-to-configure-postgresql fix user etc

- https://gist.github.com/gwangjinkim/f13bf596fefa7db7d31c22efd1627c7a

- createdb --owner=mynonsuperuser myinner_db

