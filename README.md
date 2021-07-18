# Hashcat Benchmark GPU's
Benchmark in Hashcat for diferents GPU's

# How to collaborate
```
hashcat -b --benchmark-all > benchmark.txt
```

# Archived
Migrated to https://gitlab.com/vay3t/hashcatbenchmark

### Note
Please, do not use the GPU while doing this process

# WPA Benchmark
Hashmode: 2500 - WPA-EAPOL-PBKDF2
294.8
| GPU | Hashes/s |
|---|---|
| [RTX 3090](Nvidia/rtx_3090.txt) | 1065.9 k |
| [RTX 2080 ti](https://github.com/analsec/hashcatbenchmark/blob/master/Nvidia/rtx_2080ti.txt) | 744.9 k |
| [RTX 2080](https://github.com/analsec/hashcatbenchmark/blob/master/Nvidia/rtx_2080.txt) | 571.4 k |
| [RTX 2060](https://github.com/analsec/hashcatbenchmark/blob/master/Nvidia/rtx_2060.txt) | 370.7 k |
| [GTX 1070 (L)](https://github.com/analsec/hashcatbenchmark/blob/master/Nvidia/gtx_1070_L.txt) | 334.2 k |
| [GTX 1660 SUPER](https://github.com/analsec/hashcatbenchmark/blob/master/Nvidia/gtx_1660_super) | 294.8 k |
| [GTX 1060](https://github.com/analsec/hashcatbenchmark/blob/master/Nvidia/gtx_1060_half.txt) | 223.2 k |
| [RX 580](https://github.com/analsec/hashcatbenchmark/blob/master/AMD/rx_580.txt) | 202.1 k |
| [RX 570](https://github.com/analsec/hashcatbenchmark/blob/master/AMD/rx_570.txt) | 189.3 k |
| [GTX 970](https://github.com/analsec/hashcatbenchmark/blob/master/Nvidia/gtx_970.txt) | 183.6 k |
| [GTX 1060 (L)](https://github.com/analsec/hashcatbenchmark/blob/master/Nvidia/gtx_1060_half_L.txt) | 177.1 k |
| [GTX 1650 (L)](https://github.com/analsec/hashcatbenchmark/blob/master/Nvidia/gtx_1650_L.txt) | 153.4 k |
| [GTX 1050 (L)](https://github.com/analsec/hashcatbenchmark/blob/master/Nvidia/gtx_1050_L.txt) | 100.8 k |
| [GTX 960m (L)](https://github.com/analsec/hashcatbenchmark/blob/master/Nvidia/gtx_960m_L.txt) | 62786 |
| [GeForce 940m (L)](https://github.com/analsec/hashcatbenchmark/blob/master/Nvidia/940m_L.txt) | 36270 |
| [Jetson TX2](https://github.com/analsec/hashcatbenchmark/blob/master/Nvidia/jetson_tx2.txt) | 27084 |
| [Jetson nano](https://github.com/analsec/hashcatbenchmark/blob/master/Nvidia/jetson_nano.txt) | 9661 |

* L = Laptop
* e = eGPU (external GPU)
