FROM mysql:8.0
ENV MYSQL_ROOT_PASSWORD=ExpenseApp@1
COPY scripts/*.sql  /docker-entrypoint-initdb.d

# What ever the .sql extension files we keep in the abovementioned directory container will take care of creating DB/Schemas with table creation