# Selective_Repeat_for_CN
Programs for Selective Repeat Protocol
# SELECTIVE REPEAT PROTOCOL


## DESCRIPTION
This is an implementation of Selective Repeat reliable transport layer protocol.


## RUNNING SERVER
python ServerApp.py -a [sender_ip] -b [sender_port] -x [receiver_ip] -y [receiver_port] -m [sequence_number_bits] -w [window_size]

e.g. python ServerApp.py -a "127.0.0.1" -b 8081 -x "127.0.0.1" -y 8080 -m 2 -w 2


## RUNNING CLIENT
python ClientApp.py -f [filename] -a [sender_ip] -b [sender_port] -x [receiver_ip] -y [receiver_port] -m [sequence_number_bits] -w [window_size] -s [max_segment_size] -n [total_packets] -t [timeout]

e.g. python ClientApp.py -f "index.html" -a "127.0.0.1" -b 8081 -x "127.0.0.1" -y 8080 -m 2 -w 2 -s 1500 -n "ALL" -t 10


## Maintainer
 - Name:        Venkataraghavan & Anantharaman
