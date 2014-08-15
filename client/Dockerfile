FROM busybox
CMD while true ; do echo -n "Client on $HOSTNAME talking to $SERVER_1_PORT_1234_TCP at " ; date ; set | grep SERVER.*_TCP= | grep -v FIG ; sleep 5 ; done
