

# Update pass:
rppass --> rppass001

# Update host:

RP_DB_HOST: postgres
-->
RP_DB_HOST: reportportal-db3.c22xzvbrghrn.eu-west-1.rds.amazonaws.com


POSTGRES_HOST: "postgres"
-->
POSTGRES_HOST  : reportportal-db3.c22xzvbrghrn.eu-west-1.rds.amazonaws.com

----

From:
    POSTGRES_HOST
    POSTGRES_PASSWORD
To:
    POSTGRES_HOST: "reportportal-db3.c22xzvbrghrn.eu-west-1.rds.amazonaws.com"
    POSTGRES_PASSWORD: "rppass001"
