# 2025-01-30-Docker


- `docker run --rm -p 8787:8787 rocker/rstudio:4.4.2` connect the port to rstudio
- open brower and type in`localhost:8787` to get to rstudio in the container.
- hit ctrl+c to quit
- we can also pass in `docker run --rm -e PASSWORD="<ANY PASSWORD>" -p 8787:8787 rocker/rstudio:4.4.2` to make the login 'password' to be the password stirng you specified.
