Optimus 2x(LG-SU660) kernel project
based on LG official SU660 kernel V20D/V20H

## Kernel Sources ##
  * LG SU660 V20D - http://www.lg.com/global/support/opensource/opensource-detail.jsp?detailCustomerModelCode=LGSU660
  * lge-kernel-star by rmcc - https://github.com/CyanogenMod/lge-kernel-star
  * NVIDIA Tegra - http://nv-tegra.nvidia.com/gitweb/?p=linux-2.6.git;a=tree;h=refs/heads/android-tegra-2.6.32;hb=android-tegra-2.6.32

---

  * merged up to 2.6.32.51
  * almost all patch sets applied from the lge-kernel-star(by rmcc) except p990 specific / LG USB revert patches.
  * revert some LG specific patches
    * revert lowmemkiller
  * additional backport some v2.6.35 features.
    * fixed compaction patch to compile correctly.
    * show memory map.

---

git repo will be released soon.
## Kernel 3.0.8 ##
**Experimental**
  * forward ported kernel 3.0.8 based on Nvidia's ODM/NVRM based tegra kernel 2.6.32.9.
  * SU660 (based on Open2x kernel 2.6.32) and P99x (for P990/P999 based on lge-kernel-star 2.6.32)
  * Alpha stage. but almost all working nicely.

Please see also
> http://forum.xda-developers.com/showthread.php?t=1556682
## Kernel 3.0 source ##
https://github.com/wkpark/tegra-linux-3.0.y

---

옵티머스 2x(LG-SU660) 커널 프로젝트

LG 정식 SU660 커널 버전 V20D/V20H를 기반으로 하는 커널 프로젝트입니다.

## 커널 3.0 ##
  * Nvidia의 ODM/NVRM 기반 테그라커널 2.6.32.9를 포워드 포팅했습니다.
  * SU660 (Open2x커널의 변경을 토대로) 및 P99x (P990/P999는 lge-kernel-star 2.6.32 변경점을 사용하고 이를 바탕으로 수정)

Please see also
> http://forum.xda-developers.com/showthread.php?t=1556682
## 커널 3.0 소스 ##
https://github.com/wkpark/tegra-linux-3.0.y