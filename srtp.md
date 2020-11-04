# internal
$ ./srtp_driver -t
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
16			90.773060
32			177.217819
64			282.297416
128			458.906780
256			669.672782
512			860.247573
1024			1011.923953
2048			1101.298045


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
16			656.578610
32			743.041245
64			906.499531
128			995.411774
256			1084.470050
512			1120.834496
1024			1151.142219
2048			1164.324373


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
16			81.619119
32			151.393291
64			223.549548
128			322.407985
256			419.591308
512			495.706139
1024			539.154517
2048			571.140133


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
16			2345.611142
32			4718.894009
64			7902.454082
128			18775.210854
256			33800.957254
512			41727.791361
1024			146678.603402
2048			299853.587116


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
16			80.871389
32			143.586292
64			208.481788
128			296.951032
256			374.427754
512			432.860632
1024			470.194426
2048			489.431547


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
16			91.215518
32			176.513987
64			285.111288
128			461.435859
256			669.084256
512			864.300952
1024			1011.580323
2048			1107.777771

#openssl
$ ./srtp_driver -t
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
16			434.457946
32			700.065631
64			1342.035595
128			2383.557180
256			3896.869946
512			5796.035037
1024			7548.630244
2048			9101.160420


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
16			1109.570042
32			2147.831194
64			3172.636014
128			8519.843581
256			11102.076218
512			24216.625281
1024			29581.482685
2048			40615.781254


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
16			314.025662
32			638.085743
64			1127.529785
128			1954.720727
256			3311.183328
512			4882.467935
1024			6437.215150
2048			7569.730319


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
16			727.479398
32			1141.023355
64			2712.295386
128			4351.336421
256			7862.709717
512			13647.874184
1024			22311.191001
2048			31975.019516


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
16			716.524854
32			1184.253134
64			2269.704761
128			4591.516456
256			8555.792288
512			13663.353126
1024			20360.888801
2048			31937.621832


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
16			590.160911
32			1119.566168
64			2662.506500
128			4177.375270
256			7453.235316
512			12476.773584
1024			19863.246205
2048			26749.824487


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
16			698.042210
32			1126.810159
64			2569.765107
128			4332.557648
256			7405.800246
512			12636.515086
1024			19462.130571
2048			26850.213045


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
16			2201.582387
32			4376.816550
64			8500.747136
128			17444.633731
256			33756.387012
512			43658.068642
1024			140514.579760
2048			280212.074568


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
16			320.569010
32			640.977491
64			1121.454386
128			1990.513957
256			3212.145927
512			4688.000733
1024			6150.842813
2048			7304.665730


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
16			442.921900
32			757.396450
64			1268.582755
128			2389.508564
256			3927.133269
512			5778.128879
1024			7546.683126
2048			9073.841263

