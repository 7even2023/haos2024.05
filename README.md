haos2024.05main 20.05.2024 13:27

# haos2024.05/tree/main - yaml main esphome files 
### note: source main (srv7@7wlan) 
<img src='git-pics/pcb-srv7wlan7haos_main.png' width='50%'/>

# haos2024.05/tree/dev - yaml backup esphome files 
### note: source dev (srv7@6wlan) 
<img src='git-pics/pcb-srv7wlan6haos_dev.png' width='50%'/>

# haos v1.2.3 dashboard home panel env.overview (srv1+srv2+srv7@7wlan) 
<img src='git-pics/pcb-srv7wlan7haos_srv127.png' width='70%'/>
 overview env location w.i.p. (location:ort)  az-esp32v4
<img src='git-pics/pcb-floorplan.png' width='50%'/>
  overview env connected w.i.p. (speed:verbindung) mesh-wifi
<img src='git-pics/pcb-env_nas1+2+3_6wlan.png' width='50%'/>

# env.0 az32a00 = home lab (guest_room)
<img src='git-pics/pcb-a00.jpg' width='70%'/>

pcb: button + relais(incl led) + bme280
note: value id temp + humi + press
### <a href="https://github.com/7even2023/yaml/blob/76fa6ba39aad9fe83afc449854af3aca2f6d9836/ch0-001_esphome-web-e911d0.yaml">az32a00.yaml</a>
<img src='git-pics/pcb-a00.jpg' width='50%'/>

# env.1 az32a01 = kueche (kitchen)
<img src='git-pics/pcb-a01.jpg' width='70%'/>

pcb: button + relais(incl led) + bme280
note: value id temp + humi + press
### <a href="https://github.com/7even2023/yaml/blob/76fa6ba39aad9fe83afc449854af3aca2f6d9836/ch0-001_esphome-web-e911d0.yaml">az32a01.yaml</a>
<img src='git-pics/pcb-a01.jpg' width='50%'/>

# env.2 az32a02 = bad (bath)
<img src='git-pics/pcb-a02.jpg' width='70%'/>

pcb: button + relais(incl led) + bme280
note: value id temp + humi + press
### <a href="https://github.com/7even2023/yaml/blob/76fa6ba39aad9fe83afc449854af3aca2f6d9836/ch0-001_esphome-web-e911d0.yaml">az32a02.yaml</a>
<img src='git-pics/pcb-a02.jpg' width='50%'/>

# env.3 az32a03 = schlafzimmer (sleeping_room)
<img src='ch0-603_haos11_sensors_az32003schlaf.png' width='70%'/>
### button + relais(incl led) + dht11 
### <a href="https://github.com/7even2023/yaml/blob/76fa6ba39aad9fe83afc449854af3aca2f6d9836/ch0-001_esphome-web-e911d0.yaml">ch1-003_esphome-az32003.yaml</a>
<img src='ch1-003a_az32003_schlafzimmer.jpg' width='50%'/>

# env.4 az32a04 = wohnzimmer (living_room)
<img src='ch0-604_haos11_sensors_az32004wohn.png' width='70%'/>
### relais(incl led) + dht11 
### <a href="https://github.com/7even2023/yaml/blob/76fa6ba39aad9fe83afc449854af3aca2f6d9836/ch0-001_esphome-web-e911d0.yaml">ch1-004_esphome-az32004.yaml</a>
<img src='ch1-004a_az32004_wohnzimmer.jpg' width='50%'/>

# env.5 az32a05 = flur (todo motion) wip motion(ir)
<img src='ch0-605_haos11_sensors_az32005flur.png' width='70%'/>
###  neopixel rgb light (relais(incl led) + fotosensor + thermistor) 
### <a href="https://github.com/7even2023/yaml/blob/76fa6ba39aad9fe83afc449854af3aca2f6d9836/ch0-001_esphome-web-e911d0.yaml">ch1-005_esphome-az32005rgb.yaml</a>
<img src='ch1-005a_az32005_flur.jpg' width='50%'/>
<img src='ch1-005b_az32005_flur_rgb.jpg' width='50%'/>

# env.6 az32a06 = balkon (outside/aussen)
<img src='ch0-606_haos11_sensors_cb32balkon.png' width='70%'/>
### relais(incl led) + dht11 
### <a href="https://github.com/7even2023/yaml/blob/76fa6ba39aad9fe83afc449854af3aca2f6d9836/ch0-001_esphome-web-e911d0.yaml">chx-00x_esphome-cb32.yaml</a>
<img src='ch1-006a_cb32_aussen.jpg' width='50%'/>

wip-changelog200524-1437: 
todo hyperlinks in readme to yaml file links 

wip-changelog200524-1438: 
added flur part unten b05 + wip rgb stripe 5m 
todo add all yaml-projects in git-source
