# RDS-Start-STOP-Script
Weekend Script for RDS- Start and Stop

Details to be added to RDS- Database which is to be stopped or started

KEY             VALUE

DEV-TEST	START
DEV-TEST1	STOP


This Script will run on Basis of Tags and no Database name will be mentioned. Eg: If you want to Use Start Script. Update teh Tag as "DEV-TEST"	"START" in Database and update the Env as KEY DEV-TEST and VALUE	START .

ENV VARIABLES

START Script:-------------

Key      Value

KEY	DEV-TEST
REGION	us-east-1
VALUE	START

START Script:------------

Key     Value

KEY	DEV-TEST1
REGION	us-east-1
VALUE	STOP
