# oracle-opatch-19.7-from-19.3
oracle opatch 19.7 from 19.3 GI and Database
1. download  GI patchset p30899722
2. download latest OPatch p6880880
3. use gird and oracle replace $ORACLE_HOME/OPatch on every node
4. view p30899722 readme.html
5. fix bug 
    Set ORACLE_HOME environment to point to OID oracle home and then execute the following command:
    <ORACLE_HOME>/oui/bin/attachHome.sh
6. $ORACLE_HOME/OPatch/opatch lsinventory -detail -oh /u01/app/190/grid
