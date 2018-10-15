# docker-tic(k)
docker tick-stack (telegraf, influxdb, chronograf, [kapacitor]) - ideal for a raspberry Pi based on hypriot


**prerequisites**

make sure docker runs on your Raspberry Pi

(For new raspberry Pi flash SD card and install hypriot on your raspberry pi first: `http://blog.hypriot.com/post/releasing-HypriotOS-1-8/`)


**installation**

1. copy the repo to your home dir 
2. cd to `docker-tick` folder
2. run `docker-compose up` (add `-d` for detached mode).


**use**

you can access chronograf under http://**DeviceIP**:8888
  
enjoy.
