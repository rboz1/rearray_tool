# rearray_tool

## Overview

A software tool that takes user text input of one to four 96 well microplate plate maps and rearrays them into a higher-throughput 384 well microplate plate map.

**Background** 

Transferring samples from 96 to 384 well plates requires plate maps for record keeping. At first glance generating these plate maps seems easy to quickly "automate" with Excel spreadsheets or loop. However to work with automation equipment, samples must be *stamped* from a 96 well plate into the 384 well plate a specific, standardized way. In the 384 well plate, 96 well plates 1 + 3 are stamped in every other well of every other column, alternating columns with 96 well plates 2 + 4. See figure below.

![plates_labelled](https://user-images.githubusercontent.com/63253421/148575308-cab7d87a-d171-4875-8b3a-2231f424de2f.png)


*Figure showing how samples in each well are rearrayed from three 96 well microplates to a 384 well microplate*

## How it works

The tool takes up to four exported 96 well microplate plate maps, the user pastes them into the text areas on the left (plate 1 goes in the first text area, plate 2 in the second, etc.). If less than four 96 well plates are used, the 384 well plate will include empty wells for the missing plate(s). The user then clicks the arrow button to trigger the on-click event which rearrays the 96 well plate maps into a 384 well plate map. This 384 well plate map is output into the text area on the right. The user can also clear the text area fields by clicking on the clear button which calls an on-click event.

## Tool Demo

https://user-images.githubusercontent.com/63253421/148574200-7f5c7e1f-6a62-4f1d-83fd-1f0cecc46d68.mov


## Benefits

This tool reduced human error and hands-on time that could have been caused by an Excel spreadsheet system. It also helps with record keeping accuracy!
