Intel® Core™ i9-10900 CPU @ 2.80GHz × 20 
31.3 GiB

yc@yc-B460-AORUS-PRO-AC:~/_workspace/ycyang1229/libsrtp/build$ ./srtp_driver -t
# SSRC:          any outbound
# rtp cipher:    null cipher
# rtp auth:      hmac sha-1 authentication function
# rtp services:  authentication
# rtcp cipher:   null cipher
# rtcp auth:     hmac sha-1 authentication function
# rtcp services: authentication
# window size:   128
# tx rtx allowed:false
# Encrypted extension headers: none
# testing srtp throughput:
# mesg length (octets)	throughput (megabits per second)
16			88.008801
32			171.120707
64			271.769421
128			439.535912
256			640.142032
512			821.200444
1024			941.970826
2048			1033.814127


# SSRC:          any outbound
# rtp cipher:    AES-128 integer counter mode
# rtp auth:      null authentication function
# rtp services:  confidentiality
# rtcp cipher:   AES-128 integer counter mode
# rtcp auth:     null authentication function
# rtcp services: confidentiality
# window size:   128
# tx rtx allowed:false
# Encrypted extension headers: none
# testing srtp throughput:
# mesg length (octets)	throughput (megabits per second)
16			671.457798
32			852.026892
64			988.951557
128			1069.585744
256			1128.362222
512			1134.626039
1024			1174.106593
2048			1157.789854


# SSRC:          any outbound
# rtp cipher:    AES-128 integer counter mode
# rtp auth:      hmac sha-1 authentication function
# rtp services:  confidentiality and authentication
# rtcp cipher:   AES-128 integer counter mode
# rtcp auth:     hmac sha-1 authentication function
# rtcp services: confidentiality and authentication
# window size:   128
# tx rtx allowed:false
# Encrypted extension headers: none
# testing srtp throughput:
# mesg length (octets)	throughput (megabits per second)
16			79.083619
32			149.855705
64			222.011196
128			321.983215
256			411.986224
512			474.218425
1024			517.430759
2048			544.017287


# SSRC:          any outbound
# rtp cipher:    null cipher
# rtp auth:      null authentication function
# rtp services:  none
# rtcp cipher:   null cipher
# rtcp auth:     null authentication function
# rtcp services: none
# window size:   128
# tx rtx allowed:false
# Encrypted extension headers: none
# testing srtp throughput:
# mesg length (octets)	throughput (megabits per second)
16			2298.850575
32			4555.160142
64			8969.866854
128			18723.715487
256			34547.908232
512			73352.435530
1024			147523.860976
2048			295420.122611


# SSRC:          any outbound
# rtp cipher:    AES-256 integer counter mode
# rtp auth:      hmac sha-1 authentication function
# rtp services:  confidentiality and authentication
# rtcp cipher:   AES-256 integer counter mode
# rtcp auth:     hmac sha-1 authentication function
# rtcp services: confidentiality and authentication
# window size:   128
# tx rtx allowed:false
# Encrypted extension headers: none
# testing srtp throughput:
# mesg length (octets)	throughput (megabits per second)
16			79.026004
32			140.307031
64			199.489587
128			293.026876
256			367.613403
512			423.854217
1024			450.761513
2048			468.104924


# SSRC:          any outbound
# rtp cipher:    null cipher
# rtp auth:      hmac sha-1 authentication function
# rtp services:  authentication
# rtcp cipher:   null cipher
# rtcp auth:     hmac sha-1 authentication function
# rtcp services: authentication
# window size:   128
# tx rtx allowed:false
# Encrypted extension headers: none
# testing srtp throughput:
# mesg length (octets)	throughput (megabits per second)
16			90.184032
32			176.297612
64			275.905179
128			437.197665
256			633.883029
512			803.879661
1024			960.780634
2048			1032.486393

#2. openssl
yc@yc-B460-AORUS-PRO-AC:~/_workspace/ycyang1229/libsrtp/build$ ./srtp_driver -t
# SSRC:          any outbound
# rtp cipher:    null cipher
# rtp auth:      hmac sha-1 authentication function
# rtp services:  authentication
# rtcp cipher:   null cipher
# rtcp auth:     hmac sha-1 authentication function
# rtcp services: authentication
# window size:   128
# tx rtx allowed:false
# Encrypted extension headers: none
# testing srtp throughput:
# mesg length (octets)	throughput (megabits per second)
16			433.369447
32			894.510640
64			1462.898940
128			2661.814401
256			4272.274026
512			6122.937096
1024			7950.156247
2048			9427.090226


# SSRC:          any outbound
# rtp cipher:    AES-128 counter mode using openssl
# rtp auth:      null authentication function
# rtp services:  confidentiality
# rtcp cipher:   AES-128 counter mode using openssl
# rtcp auth:     null authentication function
# rtcp services: confidentiality
# window size:   128
# tx rtx allowed:false
# Encrypted extension headers: none
# testing srtp throughput:
# mesg length (octets)	throughput (megabits per second)
16			1128.349788
32			2170.227196
64			4473.960154
128			8490.878939
256			14714.757868
512			24182.311961
1024			33870.834367
2048			44931.987714


# SSRC:          any outbound
# rtp cipher:    AES-128 counter mode using openssl
# rtp auth:      hmac sha-1 authentication function
# rtp services:  confidentiality and authentication
# rtcp cipher:   AES-128 counter mode using openssl
# rtcp auth:     hmac sha-1 authentication function
# rtcp services: confidentiality and authentication
# window size:   128
# tx rtx allowed:false
# Encrypted extension headers: none
# testing srtp throughput:
# mesg length (octets)	throughput (megabits per second)
16			362.729540
32			712.754406
64			1247.593752
128			2139.305561
256			3579.043025
512			5168.128194
1024			6779.436592
2048			7978.845152


# SSRC:          any outbound
# rtp cipher:    AES-128 GCM using openssl
# rtp auth:      null authentication function
# rtp services:  confidentiality and authentication
# rtcp cipher:   AES-128 GCM using openssl
# rtcp auth:     null authentication function
# rtcp services: confidentiality and authentication
# window size:   128
# tx rtx allowed:false
# Encrypted extension headers: none
# testing srtp throughput:
# mesg length (octets)	throughput (megabits per second)
16			737.582114
32			1421.590404
64			2898.550725
128			5214.645822
256			9755.632830
512			16270.109235
1024			25785.332074
2048			36140.644991


# SSRC:          any outbound
# rtp cipher:    AES-128 GCM using openssl
# rtp auth:      null authentication function
# rtp services:  confidentiality and authentication
# rtcp cipher:   AES-128 GCM using openssl
# rtcp auth:     null authentication function
# rtcp services: authentication
# window size:   128
# tx rtx allowed:false
# Encrypted extension headers: none
# testing srtp throughput:
# mesg length (octets)	throughput (megabits per second)
16			763.951059
32			1446.164275
64			2791.712105
128			5440.153004
256			9681.384135
512			16226.923382
1024			25348.887582
2048			36170.964324


# SSRC:          any outbound
# rtp cipher:    AES-256 GCM using openssl
# rtp auth:      null authentication function
# rtp services:  confidentiality and authentication
# rtcp cipher:   AES-256 GCM using openssl
# rtcp auth:     null authentication function
# rtcp services: confidentiality and authentication
# window size:   128
# tx rtx allowed:false
# Encrypted extension headers: none
# testing srtp throughput:
# mesg length (octets)	throughput (megabits per second)
16			739.884393
32			1410.002203
64			2646.678728
128			5148.056910
256			8905.509414
512			14282.227414
1024			22418.653020
2048			29588.961930


# SSRC:          any outbound
# rtp cipher:    AES-256 GCM using openssl
# rtp auth:      null authentication function
# rtp services:  confidentiality and authentication
# rtcp cipher:   AES-256 GCM using openssl
# rtcp auth:     null authentication function
# rtcp services: authentication
# window size:   128
# tx rtx allowed:false
# Encrypted extension headers: none
# testing srtp throughput:
# mesg length (octets)	throughput (megabits per second)
16			741.642042
32			1388.361625
64			2765.624156
128			5184.285136
256			9124.933167
512			14774.202857
1024			22360.519707
2048			29295.331414


# SSRC:          any outbound
# rtp cipher:    null cipher
# rtp auth:      null authentication function
# rtp services:  none
# rtcp cipher:   null cipher
# rtcp auth:     null authentication function
# rtcp services: none
# window size:   128
# tx rtx allowed:false
# Encrypted extension headers: none
# testing srtp throughput:
# mesg length (octets)	throughput (megabits per second)
16			2382.281779
32			4698.109745
64			9385.884510
128			17694.833247
256			37855.822551
512			73655.817299
1024			144786.143514
2048			306931.434994


# SSRC:          any outbound
# rtp cipher:    AES-256 counter mode using openssl
# rtp auth:      hmac sha-1 authentication function
# rtp services:  confidentiality and authentication
# rtcp cipher:   AES-256 counter mode using openssl
# rtcp auth:     hmac sha-1 authentication function
# rtcp services: confidentiality and authentication
# window size:   128
# tx rtx allowed:false
# Encrypted extension headers: none
# testing srtp throughput:
# mesg length (octets)	throughput (megabits per second)
16			358.543417
32			719.505340
64			1242.326450
128			2159.517483
256			3497.924815
512			5026.938796
1024			6472.563505
2048			7569.800267


# SSRC:          any outbound
# rtp cipher:    null cipher
# rtp auth:      hmac sha-1 authentication function
# rtp services:  authentication
# rtcp cipher:   null cipher
# rtcp auth:     hmac sha-1 authentication function
# rtcp services: authentication
# window size:   128
# tx rtx allowed:false
# Encrypted extension headers: none
# testing srtp throughput:
# mesg length (octets)	throughput (megabits per second)
16			452.408723
32			892.172580
64			1514.792899
128			2570.990986
256			4219.722257
512			6155.603312
1024			7905.046801
2048			9292.670338

#3. mbedtls

yc@yc-B460-AORUS-PRO-AC:~/_workspace/ycyang1229/libsrtp/build$ ./srtp_driver -t
# SSRC:          any outbound
# rtp cipher:    null cipher
# rtp auth:      hmac sha-1 authentication function using mbedtls
# rtp services:  authentication
# rtcp cipher:   null cipher
# rtcp auth:     hmac sha-1 authentication function using mbedtls
# rtcp services: authentication
# window size:   128
# tx rtx allowed:false
# Encrypted extension headers: none
# testing srtp throughput:
# mesg length (octets)	throughput (megabits per second)
16			143.205567
32			288.668629
64			483.073555
128			822.648543
256			1254.579091
512			1774.804364
1024			2229.431103
2048			2532.177698


# SSRC:          any outbound
# rtp cipher:    AES-128 counter mode using mbedtls
# rtp auth:      null authentication function
# rtp services:  confidentiality
# rtcp cipher:   AES-128 counter mode using mbedtls
# rtcp auth:     null authentication function
# rtcp services: confidentiality
# window size:   128
# tx rtx allowed:false
# Encrypted extension headers: none
# testing srtp throughput:
# mesg length (octets)	throughput (megabits per second)
16			1087.418231
32			1608.646475
64			2189.999572
128			2695.517123
256			3089.175818
512			3307.573665
1024			3411.314972
2048			3455.891193


# SSRC:          any outbound
# rtp cipher:    AES-128 counter mode using mbedtls
# rtp auth:      hmac sha-1 authentication function using mbedtls
# rtp services:  confidentiality and authentication
# rtcp cipher:   AES-128 counter mode using mbedtls
# rtcp auth:     hmac sha-1 authentication function using mbedtls
# rtcp services: confidentiality and authentication
# window size:   128
# tx rtx allowed:false
# Encrypted extension headers: none
# testing srtp throughput:
# mesg length (octets)	throughput (megabits per second)
16			130.678918
32			253.759305
64			403.782305
128			631.233741
256			902.842986
512			1155.645339
1024			1365.167238
2048			1476.541519


# SSRC:          any outbound
# rtp cipher:    AES-128 GCM using mbedtls
# rtp auth:      null authentication function
# rtp services:  confidentiality and authentication
# rtcp cipher:   AES-128 GCM using mbedtls
# rtcp auth:     null authentication function
# rtcp services: confidentiality and authentication
# window size:   128
# tx rtx allowed:false
# Encrypted extension headers: none
# testing srtp throughput:
# mesg length (octets)	throughput (megabits per second)
16			267.301508
32			410.493233
64			583.143508
128			709.357422
256			827.976551
512			905.263391
1024			956.333433
2048			976.768948


# SSRC:          any outbound
# rtp cipher:    AES-128 GCM using mbedtls
# rtp auth:      null authentication function
# rtp services:  confidentiality and authentication
# rtcp cipher:   AES-128 GCM using mbedtls
# rtcp auth:     null authentication function
# rtcp services: authentication
# window size:   128
# tx rtx allowed:false
# Encrypted extension headers: none
# testing srtp throughput:
# mesg length (octets)	throughput (megabits per second)
16			268.755118
32			419.019560
64			582.182046
128			712.253685
256			838.128289
512			915.196825
1024			960.635295
2048			985.294551


# SSRC:          any outbound
# rtp cipher:    AES-256 GCM using mbedtls
# rtp auth:      null authentication function
# rtp services:  confidentiality and authentication
# rtcp cipher:   AES-256 GCM using mbedtls
# rtcp auth:     null authentication function
# rtcp services: confidentiality and authentication
# window size:   128
# tx rtx allowed:false
# Encrypted extension headers: none
# testing srtp throughput:
# mesg length (octets)	throughput (megabits per second)
16			261.999795
32			405.872467
64			572.009519
128			696.342840
256			811.558366
512			888.744237
1024			922.086401
2048			942.411328


# SSRC:          any outbound
# rtp cipher:    AES-256 GCM using mbedtls
# rtp auth:      null authentication function
# rtp services:  confidentiality and authentication
# rtcp cipher:   AES-256 GCM using mbedtls
# rtcp auth:     null authentication function
# rtcp services: authentication
# window size:   128
# tx rtx allowed:false
# Encrypted extension headers: none
# testing srtp throughput:
# mesg length (octets)	throughput (megabits per second)
16			260.602235
32			407.961626
64			576.492180
128			691.644208
256			808.980953
512			885.273255
1024			923.705240
2048			948.141564


# SSRC:          any outbound
# rtp cipher:    null cipher
# rtp auth:      null authentication function
# rtp services:  none
# rtcp cipher:   null cipher
# rtcp auth:     null authentication function
# rtcp services: none
# window size:   128
# tx rtx allowed:false
# Encrypted extension headers: none
# testing srtp throughput:
# mesg length (octets)	throughput (megabits per second)
16			2353.806547
32			4709.345107
64			9337.953675
128			18782.098313
256			37406.392694
512			75335.663049
1024			150643.618978
2048			301342.652198


# SSRC:          any outbound
# rtp cipher:    AES-256 counter mode using mbedtls
# rtp auth:      hmac sha-1 authentication function using mbedtls
# rtp services:  confidentiality and authentication
# rtcp cipher:   AES-256 counter mode using mbedtls
# rtcp auth:     hmac sha-1 authentication function using mbedtls
# rtcp services: confidentiality and authentication
# window size:   128
# tx rtx allowed:false
# Encrypted extension headers: none
# testing srtp throughput:
# mesg length (octets)	throughput (megabits per second)
16			129.428895
32			251.715797
64			400.625978
128			623.508208
256			900.093174
512			1148.059286
1024			1327.973026
2048			1440.460554


# SSRC:          any outbound
# rtp cipher:    null cipher
# rtp auth:      hmac sha-1 authentication function using mbedtls
# rtp services:  authentication
# rtcp cipher:   null cipher
# rtcp auth:     hmac sha-1 authentication function using mbedtls
# rtcp services: authentication
# window size:   128
# tx rtx allowed:false
# Encrypted extension headers: none
# testing srtp throughput:
# mesg length (octets)	throughput (megabits per second)
16			143.579849
32			288.518974
64			481.497155
128			815.403481
256			1241.769036
512			1778.843231
1024			2236.845698
2048			2525.293004
