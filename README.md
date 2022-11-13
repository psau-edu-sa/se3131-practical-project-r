# Traffic Light system 🚦 
This how we created a traffic light system by using **formal specification's** model; Petri net.

## Description
We have a traffic intersection that organizes four different streets, It can be green at a specific time and the rest of the traffic lights are red.
>The traffic lights should work orderly; according to the description below:

- The two traffic lights in lanes 1 can be green at the same time, and the rest of the traffic lights are red.
- The two traffic lights in lanes 2 can be green at the same time, and the rest of the traffic lights are red.
- The traffic light in lane 3 can be green, and the rest of the traffic lights are red.
- The traffic light in lane 4 can be green, and the rest of the traffic lights are red.
- Traffic lights should work in the order above.
-  The traffic lights in lanes 5 can be green allow cars to U-turn when it does not interfere with another traffic light.

#
The above system
![](https://lh3.googleusercontent.com/qshfqFhkQDcgsb8QWq5aGbXnoVYb_p3ttSS2rIkZGirRMWiyDqZzlwlsvnV0Ykp9JOdyGcik1LHfAAMVzoel9lE05Mg2wmMTjWbEUoV3hE-J8t7Xj396cED8rYLblH8IPU0JhoccOQldYXgzHm9jAzygaBh-1vDn2juyMNNG7cP2uuCxDZxl1qlH0wsDuncsIHdzOgEaAL1Qm-Wt0bWmZTs1KAWlTuk9w_27DJ3wXjai4r1v-ASaglhYn2NQIUfOPBLynsUn31kRSX_IXB0ZF4hOY1_icsVvPJHA08GIj9lyCSrs-j6826HcnNjUnsVU40bjQYd6M3psdH2ny1Q4uU351sET9O26RWCm7BfXc57JVtw38AtS_OT1_vYsl16zIB7SHRLwL5t0PIs6Xvwi05D59fGuS1WlRkY7m52hEvv9hkgQwvpAx6UrcvlRabSB7XZjrCwTO3zuQGtt-n4afmFsQ5oaOwAynSex-pUgBmlrvRqqTCCzTY_aLSNFpezjuQIgfcaq_X0QdkYOtznUX5NsAr9g8tsUbDrtxm-ixL-uFJ-lcQ1flKUHRS1lRRVgzSQvD3rbgUeDYduSH18dYcqJjidJIYYfReEeJtYC1Ci-fZ5Dvyvk69oqhKhgSk6fNzHUkd3j_7f9_d5bJ713clXy5xKyNSSp04EN-q3pw0QN0UFSmfZskzS2E5d8OIR5A2J892t-gMPB0BGWilqMiBIo94QOgDvR3-mFddm_cD2X1Xl-QE0QUrMkrYMmaqL5KYi4Vz2X-Aoh823rtU6fSpVzUt2jtX1TZccOuxiWmoVZYPrNW5XV6PBBsl-Onh8NSX2xImjuyagmziE8jhmgU9XxDIEQCC6mHM-6Lb3XIpE7V3_UcOyt4UNJ8c6q2wcaFfXva9nGsaQvRBEK9NtOk69UVVV0ezVpKLkygEZGsVkOqxCWAn7qZQMRYGctDbCrdD5Ik47avTsonfEHNv7d3qNqaqJuunz9d4EsaGdK8MwH6G0kxDP8No8=w1596-h1622-no?authuser=0)
## Terms
- rg1: action from red to green of traffic 1.
- gr1: action from green to red of traffic 1.
- rg2: action from red to green of traffic 2.
- gr2: action from green to red of traffic 2.
- rg3: action from red to green of traffic 3.
- gr3: action from green to red of traffic 3.
- rg4: action from red to green of traffic 4.
- gr4: action from green to red of traffic 4.
- G1L: traffic 1 Left side will be green.
- G1R: traffic 1 Right side will be green.
- R1L: traffic 1 Left side will be red.
- R1R: traffic 1 Right side will be red.
- G2L: traffic 2 Left side will be green.
- G2R: traffic 2 Right side will be green.
- R2L: traffic 2 Left side will be red.
- R2R: traffic 2 Right side will be red.
- G3: traffic 3 will be green.
- R3: traffic 3 will be red.
- G4: traffic 4 will be green.
- R4: traffic 4 will be red.
- G51L: 5 of traffic 1 Left side will be green.
- R51L: 5 of traffic 1 Left side will be red.
- G51R: 5 of traffic 1 Right side will be green.
- R51R: 5 of traffic 1 Right side will be red.
- G54: 5 of traffic 4 will be green.
- R54: 5 of traffic 4 will be red.
- G53: 5 of traffic 3 will be green.
- R53: 5 of traffic 3 will be red
- safe1: after the traffic 1 turned red traffic 2 will be green.
- safe2: after the traffic 2 turned red traffic 3 will be green.
- safe3: after the traffic 3 turned red traffic 4 will be green.
- safe4: after the traffic 4 turned red traffic 1 will be green again.

## The system
[The Petri net file](https://drive.google.com/file/d/1jbKLsbZkcMoJ6ALvR2yi0MTGnCZjlCxF/view?usp=share_link)

Here's the system after the implementation
![](https://lh3.googleusercontent.com/R8l-ThaHxzzM2oTmogzz38H8ufa00cW2zzsttz8rYVF2BejfLKndHZNnzcEXtpdoU3U5Jq8nPmxhqZoQ_f_mkSW8cpPjdDxMhm9DG8VDN5BGEWz3cb9tcYSG72t4zrs_yRNRySx1UnqOdZliFpZG9bu-cpZIYyfL4e2L7mjLZPrv7H21QWwa8GQirKax1j5BzMUF7tetms3k5Jmc3w3Drm6wprbTbnl2_R17slAVUSnkdoUvf5K6bimXCglKzeCOL0ZoUPPBXbZfhk4RLnWwWrEBPLPQ0k_VwuCxUQ0mqOifUf7HcT069U8Xwh7hqsK3NJDi8BeMg0w5og1sVuVQSjbmB2VFEhf3TqXPFKw4NCG4JdbI7JddoKoFrRYpGprQNFO-TZDgIkMJ9rDSotZrI-chqgQ3zyc7gJR-uywzMEhoT6zLEEWxSiVxjuWbqZRKtGZEinY_286TgZXETU9xBCPLyNcDPXjIwjZ4MHg21fW6ungy70reKKpUQF_UaUtA5vzB7xXxFZy9bvslpp-DwJeCCx45BlgoDLKcALywqHy5twSHxek6OYHzwKVDd-HBa-JL45rlakjHS1CL-Rgyyu0g2gxGkkKCKKx8d_JtxPo-HanCK7soVn2KBVJpoCmbfzU3rScLkSta6r-tn-DbeNnBldgO_kW0S8PHu2tMlN8Q_4u-Q_-WMC4H3nkWKhqfn4MbuGYHewobs0eO0AsHt6bv_GIgBYaaJut1ZPTzaEsW6rHDNRBqnNq95sqcbM7ycVRD_LUoNxzOcdjR17xJy78_0R3W3IaYkHB7bnMcb26ul35YwTOtY8S8gEClAUHZh1GTWPLx5nab5OjLCfFfaiwqTKG88XKdLOLV2p4jWCZM2CTS3sYhN8HqApdK_PzYHK5jeQcPNuPr3Cbtau2sY1wpJTGweHfpavPn5aoCI3CfvNOhWnUiuYbrS1HP7QVmbYO5yY_Mv2tyXvEZkcf2kqGJlGL2NNOGctuB6MU6oUOmfxofns3YlBw=w1280-h739-no?authuser=0)
## Tools
[APO](https://apo.adrian-jagusch.de/) is a web interface for APT, a powerful software for Petri net analysis and synthesis developed at the Carl von Ossietzky University in Oldenburg, Germany. APO is developed by Adrian Jagusch and was part of his bachelor thesis.
## Developers 
**Mohammed Aldosri**

**Saleh Alzayed**

**Bassam Aloush**

**Rayan Alhamdan**
## 
This a homework we have taken it in Formal specification course with **dr.Mohammed Assiri** in 2022.
