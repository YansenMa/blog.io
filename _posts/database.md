
---
layout: post
title:  "My Git Notes"
tags: git 
mathjax: on
---


## Database

```console

select room_id,
       room_number,
       room_network_network_id,
       conv(room_edi_termostat_location, 16, 10) as location # convert hex string to decimal
from cms_hotel_room
where room_network_network_id = 3261
order by location + 0; # how to order by number value, not str value

```
