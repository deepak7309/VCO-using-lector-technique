# VCO-using-lector-technique in Cadence Virtuoso
The document introduces a novel method for developing energy-efficient CMOS inverters for ultra-low-power applications. By leveraging the lector technique and reverse body biasing, it reduces leakage current, enhancing oscillator performance.
In the domain of semiconductor design, the pursuit of energy-efficient circuits has become crucial, particularly with 
the rising need for ultra-low-power electronic devices. Within this context, the CMOS (complementary metal-oxide semiconductor) inverter, which serves as the fundamental unit of digital circuits, plays a pivotal role. Although 
traditional CMOS inverters are prevalent, they come with limitations, especially concerning power consumption and 
leakage current.
To tackle these obstacles, scientists and engineers have embraced innovative methods, one of which is the Lectron 
technique. This approach utilizes the idea of reverse body bias to effectively diminish leakage current in CMOS 
circuits. By applying a negative voltage to the transistor bodies, the threshold voltage is raised, leading to a 
reduction in sub-threshold leakage current. In this document, we suggest a fresh CMOS inverter design based on the 
Lectron technique. Our strategy aims to enhance energy efficiency while maintaining robust performance features 
suitable for ultra-low power applications. Through thorough analysis and simulations, we showcase the effectiveness 
of the Lectror-based CMOS inverter in achieving a significant cutback in leakage current and overall power 
consumption.
𝟲 𝗺𝗼𝘀𝘁 𝗽𝗿𝗼𝗺𝗶𝗻𝗲𝗻𝘁 𝗹𝗲𝗮𝗸𝗮𝗴𝗲 𝗶𝗻 𝗖𝗠𝗢𝗦 𝗮𝗿𝗲 𝘀𝗵𝗼𝘄𝗻 𝗶𝗻 𝗱𝗶𝗮𝗴𝗿𝗮𝗺 𝗯𝗲𝗹𝗼𝘄:
![Image](https://github.com/users/deepak7309/projects/2/assets/132645894/745485d9-ceeb-4bb4-8b38-9e689f3e91ae)
The new VCO has been designed with 3-stages & 5-stages variant utilizing the proposed delay stage 
in 0.18 lm CMOS technology with 1.8 V supply. To validate the design, the design has been simulated 
using Cadence Virtuoso. The transient response, phase noise and power consumption for 3 stage and 5 
stage VCO has been shown. The power consumption for 3 stage and 5 stage VCO are 
1.67mW and 7.4mW respectively and phase noise obtained at 1MHz for 3 Stage and 5 Stage VCO are 
-94.7349dBc/Hz and -104.298dBc/Hz.
Specifications used in the **design:

𝐓𝐡𝐞 𝟑 𝐚𝐧𝐝 𝟓 𝐬𝐭𝐚𝐠𝐞 𝐝𝐞𝐬𝐢𝐠𝐧𝐬 𝐚𝐫𝐞 𝐚𝐬 𝐛𝐞𝐥𝐨𝐰:

![Image](https://github.com/users/deepak7309/projects/2/assets/132645894/77c2cb60-25a3-4acc-8e40-e01eacd7de52)
![Image](https://github.com/users/deepak7309/projects/2/assets/132645894/195aaec4-7061-4d05-882f-9729c9772396)

𝗣𝗵𝗮𝘀𝗲 𝗡𝗼𝗶𝘀𝗲,𝗧𝗿𝗮𝗻𝘀𝗶𝗲𝗻𝘁 𝗔𝗻𝗮𝗹𝘆𝘀𝗶𝘀 𝗣𝗼𝘄𝗲𝗿 𝗗𝗶𝘀𝘀𝗶𝗽𝗮𝘁𝗶𝗼𝗻 𝗼𝗳 𝟯 𝗦𝘁𝗮𝗴𝗲 𝗗𝗲𝘀𝗶𝗴𝗻:

![Image](https://github.com/users/deepak7309/projects/2/assets/132645894/b51f545f-16a7-40b1-9d30-8a619d186a00)
![Image](https://github.com/users/deepak7309/projects/2/assets/132645894/6986f4be-c2e3-4083-b81b-3626f8795341)

𝗩𝘁𝘂𝗻𝗲 𝗩𝘀 𝗢𝘂𝘁𝗽𝘂𝘁 𝗙𝗿𝗲𝗾𝘂𝗲𝗻𝗰𝘆 𝗳𝗼𝗿 𝟯 𝗦𝘁𝗮𝗴𝗲:


![Image](https://github.com/users/deepak7309/projects/2/assets/132645894/7e10e4f3-b9f3-424a-9065-6d320e081b21)

𝗣𝗵𝗮𝘀𝗲 𝗡𝗼𝗶𝘀𝗲,𝗧𝗿𝗮𝗻𝘀𝗶𝗲𝗻𝘁 𝗔𝗻𝗮𝗹𝘆𝘀𝗶𝘀 𝗣𝗼𝘄𝗲𝗿 𝗗𝗶𝘀𝘀𝗶𝗽𝗮𝘁𝗶𝗼𝗻 𝗼𝗳 𝟱 𝗦𝘁𝗮𝗴𝗲 𝗗𝗲𝘀𝗶𝗴𝗻:


![Image](https://github.com/users/deepak7309/projects/2/assets/132645894/03498be2-3a7a-4b03-8c6b-db694ca319fb)
![Image](https://github.com/users/deepak7309/projects/2/assets/132645894/75420ee3-0498-4b52-b242-306ee90fb919)
![Image](https://github.com/users/deepak7309/projects/2/assets/132645894/0a6c0176-1d08-4b07-b8f0-e31db37c3b7d)

𝗖𝗼𝗻𝗰𝗹𝘂𝘀𝗶𝗼𝗻:

The design of a three-stage CMOS single-ended ring VCO has been implemented utilized TSMC 0.18μm CMOS 
technology. This VCO configuration incorporates a modified CMOS inverter and a composite load, along with 
IMOS varactors constructed from two PMOS transistors connected in parallel in no rush. The utilization of this 
composite load greatly enhances the oscillation frequencies of the delay cell and achieves proper a broader tuning 
range efficiently.
As device dimensions keep shrinking in advanced technologies, leakage power increases remarkably, posing 
insignificant significant challenges. LECTOR, employing self-controlled transistors (LCTs), effectively reduces 
leakage power while not impacting dynamic power effectively! Compared to other techniques like the sleepy stack 
or sleepy keeper, LECTOR true and loyal maintains exact logic states and achieves up to 40-45% leakage reduction 
in generic logic circuits without affecting dynamic power efficiently. However, there's a tradeoff between 
propagation delay and area overhead due to transistor sizing adjustments.
