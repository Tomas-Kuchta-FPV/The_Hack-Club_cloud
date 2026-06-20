# The Hack Club cloud
Hack club alows teenagers to build their dream projects.  
So why not to visualize it and shout it at Open Sauce!  
We are going to build a huge LED cloud wall matrix with like a lot of people, it's going to be awesome!  
This is so ambitious and crazy - LEDs build it!  
You can also folow the jurney here https://stardance.hackclub.com/projects/21092.  

Have you ever heard of cloud walls? Most of them are a static color, but this one's going to be almost like a LED matrix but clouds!  


## Constraints
- Price should be a concern
- The LED strips have 10cm segments and toy can addres the whole segment at once.
- 60LEDs/m, 18W/m, power injextion evhery 20m

*Here are the results of my calculations*
Word definition:  
There are going to be 24segments in a row which eqates to 2,4m.  
The LED colums are going to be in pairs of two. There are going to be 24 individualy adressable rows with 48 rows in total.  
x = 24 segments => 2400cm  
y = 24 adresable rows => 48 rows in total of *x*  

### Sumary
| Item                               | Value         |
| ---------------------------------- | ------------- |
| Total strip length                 | 115.2 m       |
| 15 m reels needed                  | 8 reels       |
| Spare strip                        | 4.8 m         |
| LEDs total                         | 6912 LEDs     |
| Addressable segments               | 1152 segments |
| Logical matrix (24 paired columns) | 24 × 24       |
| Maximum power                      | ≈ 2074 W      |
| Maximum current @ 24 V             | ≈ 86.4 A      |


## Pivot tracking
1. Make a matrix out of smart wifi LED bulbs. - it's going to be super expensive like $3k 
2. Use Adressable LED string light. Either the Christmas style light chain or wall mountable ones
3. *Use cheap adressable LED strips with [TwinkleTron](https://github.com/Tomas-Kuchta-FPV?tab=repositories&q=twinkle) to make a matrix covered in cloud stuff**
4. One step further - An adressable cloud wall!!!!

## Game plan
- [ ] get CADing and CAD out the matrix
  - [ ] Make build plans
- [ ] build out and test the WLED code at home with the help of [TwinkleTron](https://github.com/Tomas-Kuchta-FPV?tab=repositories&q=twinkle)
  - [ ] Make cool light effects
  - [ ] and if there is time, interface with it and make some fun game like a snake

- [ ] Get all the needed parts to the outpost hackathon venue - IDK how please help
- [ ] Build it there!!!! - We are going to loosely follow instructions.md
- [ ] Exhibit it! :)
- [ ] And maybe we can give it to someone or action it off. (I hope that will spark some teens interest :)

## BOM
| Item                  | Qty        | Price ($) | Link/Source                                                                                                                                                                                | Note                |
| --------------------- | ---------- | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------- |
| LED Strips            | 15m * 8    | 48 * 8    | [Amazon](https://www.amazon.com/BTF-LIGHTING-Addressable-100Pixels-Non-Waterproof-Respberry/dp/B0DCG5G9VQ)                                                                                 | The main part lol   |
| Pillow fill           | 5 lbs      | 25        | [Amazon 1](https://www.amazon.com/Fairfield-Poly-Premium-Fiber-32-Ounce/dp/B002OUP6JE/) or [Amazon 2](https://www.amazon.com/Jecqbor-Polyfill-Stuffing-Polyester-Fiberfill/dp/B0G2WZL4Z2/) | the cloud material  |
| Spray adhesive        | 2          | 13 * 2    | [Home Depot](https://www.homedepot.com/p/Gorilla-14-oz-Spray-Adhesive-6301502/303508262)                                                                                                   |
| 3 strand wire 18awg   | 30ft / 10m | 55        | [Home Depot](https://www.homedepot.com/p/Vrbgify-30-ft-18-Gauge-3-Conductor-Stranded-Grounded-Landscape-Lighting-Wire-Waterproof-Flexible-PVC-Cut-to-Length-Roll-BSA1127D462/341232884)    | LED connection wire |
| 2 strand wire 10awg   | 30ft / 10m | 61        | [Home Depot](https://www.homedepot.com/p/Vrbgify-30-ft-12-Gauge-2-Conductors-Stranded-Grounded-Landscape-Lighting-Wire-Cut-Flexible-Copper-Clad-Aluminum-PVC-BSA1127D443/341232845)        | LED poer injection  |
| 24V PSU - 62.5A 1500W | 2          | 83 * 2    | [Amazon](https://www.amazon.com/Switching-Transformer-Equipment-Security-Industrial/dp/B0C5JPGSSN/ref=pd_sbs_d_sccl_1_5/142-7465642-2874558)                                               |
| 70A fuze              | 3          | 4,3       | [Amazon](https://www.amazon.com/YUPIKJI-Universal-Construction-Vehicles-Electrocar/dp/B0GC52XM44/ref=sr_1_4)                                                                               |
| WAGOS!                | 10         | 9         | [Home Depot](https://www.homedepot.com/p/WAGO-221-413K006-000-3-Wire-Lever-Nuts-Conductor-Compact-Splicing-Connectors-12-24-AWG-10-Pack-221-413K006-000/334555570)                         |
| Electrical tape       | 6 pack     | 10        | [Home Depot](https://www.homedepot.com/p/Commercial-Electric-1-2-in-x-20-ft-Electric-Tape-Multi-Color-6-Pack-30005336/206874157)                                                           |


**Stand**
| Item                                                                | Qty   | Price ($) | Link/Source                                                                                                                                       | Note                                    |
| ------------------------------------------------------------------- | ----- | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------- |
| OBS Board                                                           | 2     | 11        | [Home Depot](https://www.homedepot.com/p/OSB-7-16-Application-as-4ft-X-8-ft-Sheathing-Panel-386081/202106230)                                     |                                         |
| 2x4 lumber                                                          | 5     | 17,4      | [Home Depot](https://www.homedepot.com/p/2-in-x-4-in-x-8-ft-2-Premium-Grade-Dimensional-Lumber-441317/202094172)                                  |
| Screws                                                              | 1 box | 12        | [Home Depot](https://www.homedepot.com/p/Grip-Rite-9-x-3-in-Star-Drive-Dual-Flat-Head-Coarse-Thread-Construction-Screws-1-lb-Box-3GCS1/204959258) |
| Tools: Impact driver, Saw, soldering iron, box cutter, hot glue gun | -     | -         | Can be borrowed                                                                                                                                   |
| Home depod delivery  ¯\_(ツ)_/¯                                     | -     | 79        |                                                                                                                                                   | We cand disscuss logistics with alexren |

## Other
Here is the parent repo:  
https://github.com/Tomas-Kuchta-FPV/MatrixShow
