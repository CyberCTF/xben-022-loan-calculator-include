# Upstream's Dockerfile (XBEN-022-24/mysql/Dockerfile) with one change: mysql:5.7.15 is now mysql:5.7.44
# (the last 5.7 release), as Docker can no longer pull the 5.7.15 image (an old schema 1 manifest).
FROM mysql:5.7.44

ENV MYSQL_ROOT_PASSWORD=ssti_include_loan_calculator
ENV MYSQL_DATABASE=database

EXPOSE 3306
