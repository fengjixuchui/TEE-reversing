# TEE basics 

- Introduction to Trusted Execution Environment: ARM's TrustZone
	- https://blog.quarkslab.com/introduction-to-trusted-execution-environment-arms-trustzone.html
	
- Introduction to TEE (original title: TEEを中心とするCPUセキュリティ機能の動向 )
	- https://seminar-materials.iijlab.net/iijlab-seminar/iijlab-seminar-20181120.pdf

- Attacking the ARM's TrustZone
	- https://blog.quarkslab.com/attacking-the-arms-trustzone.html

- Secure initialization of TEEs: when secure boot falls short (EuskalHack 2017)
	- https://www.riscure.com/uploads/2017/08/euskalhack_2017_-_secure_initialization_of_tees_when_secure_boot_falls_short.pdf

- Amlogic S905 SoC: bypassing the (not so) Secure Boot to dump the BootROM
	- https://fredericb.info/2016/10/amlogic-s905-soc-bypassing-not-so.html#amlogic-s905-soc-bypassing-not-so
	
- Boomerang: Exploiting the Semantic Gap in Trusted Execution Environments (A.Machiry) 2017
	- https://pdfs.semanticscholar.org/f62b/db9f1950329f59dc467238737d2de1a1bac4.pdf (slides)
	- http://sites.cs.ucsb.edu/~cspensky/pdfs/ndss17-final227.pdf (paper)
	


### Motorola

- Unlocking the Motorola Bootloader (10/02/2016)
	- http://bits-please.blogspot.com/2016/02/unlocking-motorola-bootloader.html

### Huawei

- Exploiting Trustzone on Android (BH-US 2015) by Di Shen(@returnsme) 
	- https://www.blackhat.com/docs/us-15/materials/us-15-Shen-Attacking-Your-Trusted-Core-Exploiting-Trustzone-On-Android-wp.pdf
	
- EL3 Tour : Get the Ultimate Privilege of Android Phone (Infiltrate19)
	- https://speakerdeck.com/hhj4ck/el3-tour-get-the-ultimate-privilege-of-android-phone
	- Paper : [infiltrate.pdf](https://github.com/enovella/TEE-reversing/blob/master/Papers/infiltrate.pdf)
	
- Nailgun: Break the privilege isolation in ARM devices (PoC #2 only)
	- https://github.com/ningzhenyu/nailgun

### QSEE

- Reflections on Trusting TrustZone (2014)
	- https://www.blackhat.com/docs/us-14/materials/us-14-Rosenberg-Reflections-on-Trusting-TrustZone.pdf

- Getting arbitrary code execution in TrustZone's kernel from any context (28/03/2015)
	- http://bits-please.blogspot.com/2015/03/getting-arbitrary-code-execution-in.html

- Exploring Qualcomm's TrustZone implementation (04/08/2015)
	- http://bits-please.blogspot.com/2015/08/exploring-qualcomms-trustzone.html

- Full TrustZone exploit for MSM8974 (10/08/2015)
	- http://bits-please.blogspot.com/2015/08/full-trustzone-exploit-for-msm8974.html

- TrustZone Kernel Privilege Escalation (CVE-2016-2431)
	- http://bits-please.blogspot.com/2016/06/trustzone-kernel-privilege-escalation.html

- War of the Worlds - Hijacking the Linux Kernel from QSEE
	- http://bits-please.blogspot.com/2016/05/war-of-worlds-hijacking-linux-kernel.html

- QSEE privilege escalation vulnerability and exploit (CVE-2015-6639)
	- http://bits-please.blogspot.com/2016/05/qsee-privilege-escalation-vulnerability.html

- Exploring Qualcomm's Secure Execution Environment (26/04/2016)
	- http://bits-please.blogspot.com/2016/04/exploring-qualcomms-secure-execution.html

- Android privilege escalation to mediaserver from zero permissions (CVE-2014-7920 + CVE-2014-7921)
	- http://bits-please.blogspot.com/2016/01/android-privilege-escalation-to.html

- Trust Issues: Exploiting TrustZone TEEs (24 July 2017)
	- https://googleprojectzero.blogspot.com/2017/07/trust-issues-exploiting-trustzone-tees.html

- Breaking Bad. Reviewing Qualcomm ARM64 TZ and HW-enabled Secure Boot on Android (4-9.x)
	- https://github.com/bkerler/slides_and_papers/blob/master/QualcommCrypto.pdf

- Technical Advisory: Private Key Extraction from Qualcomm Hardware-backed Keystores CVE-2018-11976 (NCC)
	- https://www.nccgroup.trust/us/our-research/private-key-extraction-qualcomm-keystore/

- Qualcomm TrustZone Integer Signedness bug (12/2014)
	- https://fredericb.info/2014/12/qpsiir-80-qualcomm-trustzone-integer.html
	
- The road to Qualcomm TrustZone apps fuzzing (RECON Montreal 2019)
	- https://cfp.recon.cx/media/tz_apps_fuzz.pdf


### Samsung 

#### Kinibi & MobiCore

- Unbox Your Phone: Parts I, II & III
	- https://medium.com/taszksec/unbox-your-phone-part-i-331bbf44c30c
	- https://medium.com/taszksec/unbox-your-phone-part-ii-ae66e779b1d6
	- https://medium.com/taszksec/unbox-your-phone-part-iii-7436ffaff7c7
	- https://github.com/puppykitten/tbase
	- https://github.com/puppykitten/tbase/blob/master/unboxyourphone_ekoparty.pdf

- KINIBI TEE: Trusted Application Exploitation (2018-12-10)
	- https://www.synacktiv.com/posts/exploit/kinibi-tee-trusted-application-exploitation.html

- Reverse Engineering Samsung S6 SBOOT - Part I & II
	- https://blog.quarkslab.com/reverse-engineering-samsung-s6-sboot-part-i.html
	- https://blog.quarkslab.com/reverse-engineering-samsung-s6-sboot-part-ii.html

- TEE Exploitation on Samsung Exynos devices by Eloi Sanfelix: Parts I, II, III, IV
	- https://labs.bluefrostsecurity.de/blog/2019/05/27/tee-exploitation-on-samsung-exynos-devices-introduction/
	- https://labs.bluefrostsecurity.de/files/TEE.pdf
	
- Breaking Samsung's ARM TrustZone (BlackHat USA 2019)
	- https://i.blackhat.com/USA-19/Thursday/us-19-Peterlin-Breaking-Samsungs-ARM-TrustZone.pdf
	
#### TEEGRIS

- Reverse-engineering Samsung Exynos 9820 bootloader and TZ by @astarasikov
	- http://allsoftwaresucks.blogspot.com/2019/05/reverse-engineering-samsung-exynos-9820.html
	
## TEE Videos

- Ekoparty-13 (2017) Daniel Komaromy - Unbox Your Phone - Exploring and Breaking Samsung's TrustZone SandBoxes
	- video: https://www.youtube.com/watch?v=L2Mo8WcmmZo
	- slides: https://github.com/puppykitten/tbase/blob/master/unboxyourphone_ekoparty.pdf

- Daniel Komaromy - Enter The Snapdragon (2014-10-11)
	- https://www.youtube.com/watch?v=2wJRnewVE-g

- BSides DC 2018 & DerbiCon VIII - On the nose: Bypassing Huaweis Fingerprint Authentication by Exploiting the TrustZone by Nick Stephens
	- https://www.youtube.com/watch?v=QFFhdqP7Dxg
	- https://www.youtube.com/watch?v=MdoGCXGHGnY
	
- BH US 2015 - Fingerprints On Mobile Devices: Abusing And Leaking
	- https://www.youtube.com/watch?v=7NkojB9gLXM

- No ConName 2015 - (Un)Trusted Execution Environments by Pau Oliva
	- video: *audio Spanish only* https://vimeo.com/150787883
	- slides: https://t.co/vFATxEa7sy

## Tools

### Emulate

- QEMU Support for Exynos9820 S-Boot
	- https://github.com/astarasikov/qemu

- Emulating Exynos 4210 BootROM in QEMU
	- https://fredericb.info/2018/03/emulating-exynos-4210-bootrom-in-qemu.html#emulating-exynos-4210-bootrom-in-qemu

### Reverse

- TZAR unpacker
	- https://gist.github.com/astarasikov/f47cb7f46b5193872f376fa0ea842e4b#file-unpack_startup_tzar-py

- IDA MCLF Loader
	- https://github.com/ghassani/mclf-ida-loader

