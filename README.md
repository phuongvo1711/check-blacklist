# check-blacklist
automation check blacklist mail zimbra

Edit the following parameters :

LISTIP=" 

DARI="from:report@imanudin.net";

TUJUAN="to:admin@imanudin.net";

SALINAN="cc:admin@imanudin.net";

Save and Check.

Create Crontab : 

1 * * * * /opt/cekrbl.sh > /dev/null 2>&1
