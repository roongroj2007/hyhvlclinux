# hyhvlclinux
# stream 6 cctv camera through VLC
1) config ch1 to ch6 input stream input (url, ip address, usr/password, port) in file mosaichyhnet.vlm
2) Config linux server
    - Install vlu in linux server: sudo apt install vlc
3) Stream CCTV mosaic on VLC Linux server
    - startVLC default interface: /usr/bin/vlc --vlm-conf /home/admin/hyhvlc/mosaichyhnet.vlm
    - startVLC without interface: /usr/bin/cvlc --vlm-conf /home/admin/hyhvlc/mosaichyhnet.vlm
4) To stop VLC streaming on linux server
    - stop VLC: killall vlc

# running VLC cctv mosaic stream on PC clients
5) Install vlc on PC clients (windows or linux)
6) Open VLC app on the PC clients and run streaming
    - http://<VLC cctv stream server ip>:8090/hyhipcam


# trouble shooting
7) if some channel ipput could not stream out 
    - check ip cctv camera port
