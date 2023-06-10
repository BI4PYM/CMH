# 通信方式层级结构 Communication Mode Hierarchy CMH
'CMH' 是用于描述各种通信方式之间关系的模型，类似于OSI模型，分为 '介质层' '信道层' '调制层' '接口层' '信息层' '封装层' '界面层' 共七层。每层元素可向下包含，高层元素利用低层元素。不同元素包含的下层元素可能不同。层间/层中关系并不是绝对严格，可根据需要灵活调整。
## 一、介质层 信号传输方式
介质层描述了信号的传输渠道，如机械波、有线电、无线电、光、物理介质的交通运输、引力波、物理粒子等，是通信方式最根本最基础的描述。
## 二、信道层 频谱利用方式
信道层描述了频谱的利用方式，可以分为2.0层、2.5层和特殊信道层。2.0层描述了区分同一用户不同信号的方式，包含FDM、OFDM、TDM、单路直通等。2.5层描述了区分信道中不同用户的方式，包含FDMA、TDMA、CDMA等。特殊信道层包含物理介质上的文字符号、颜色图画、磁记录、电记录、机械记录、生物记录、化学记录、行为记录等。
## 三、调制层 信号调制方式
调制层描述了信号的调制方式，可分为幅度调制、角度调制、混合调制和其他调制。幅度调制包含OOK/ASK、AM/DSB、SSB(USB/LSB)、VSB、ISB等。角度调制可分为频率调制和相位调制，频率调制包含FM、FSK、AFSK等，相位调制包含PM、PSK、QPSK、BPSK等。混合调制是组合使用的调制方式，如QAM、FM调制的AFSK、AM调制的AFSK、FM调制的QPSK、FM调制的QAM等。其他调制包含直通等。
## 四、接口层 信息与基带信号的变换
接口层描述了信息（欲表达的含义）与基带信号（如二进制数据、中频信号）的变换方式，包含AX.25、RTTY、Pactor、ASPP、TCP/IP、PD120、Robot36、PAL、NTSC、RDFT、ASCII、LoRa、IEEE 802.11、MFSK标准、信件、纸张、磁带、硬盘、软盘、光盘、相片、唱片、气味、打孔卡片、图画、语言等。
## 五、信息层 信息的类型
信息层描述了欲表达的不同含义类型，如音频、图像、视频、其他信息、组合信息（如电视）等。
## 六、封装层 模式封装和传输控制
封装层是对更低层的包装，以形成完整的协议和标准。如CW、ASP、SSTV、FAX、WLAN、WiFi、HTTP、FTP、TELNET、NTFS、FAT、NBTV、ATV、DATV、RTTY、APRS、DRM、IRC、SSH、VoIP、语言、文字、LoRaWAN、LoRaAPRS、AREDN、HAMDRM、MFSK等。
## 七、界面层 人机交互的直接渠道
界面层是最高层级，是人机交互的最直接渠道，信息通过界面层传达到更低层级。界面层包含MMSSTV、MMRTTY、MMVARI、Winlink2000、MutiPSK、Dream、WinDRM、DIGTRX、EasyPal、AGWTracker、SDRuno、TNC、无线电台、Chrome、Edge、Firefox、随身听、唱片机、计算机、眼睛、耳朵、鼻子等。