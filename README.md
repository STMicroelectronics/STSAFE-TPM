# STSAFE&trade;-TPM

ST33KTPM is the latest addition to the STSAFE-TPM family, a widely used and standardized Trusted Platform Module that serves as a cornerstone of security for PCs and servers.
TPMs are required by Microsoft Windows and natively supported by Linux operating systems.
ST33KTPM offers improved performance, enhanced security, and increased memory capacity to effectively address current and future security challenges.
The independent security certifications by Common Criteria, TCG and FIPS provide a high level of confidence and can be leveraged to meet regulatory requirements.

## Product portfolio
The ST33KTPM family offers three products with different interfaces and lifetimes to support all ecosystem requirements.


![Summary table of ST33KTPM products](https://github.com/collarto73/STSAFE-TPM/blob/main/pictures/Portfolio.png)
- [ST33KTPM2XSPI](https://www.st.com/en/secure-mcus/st33ktpm2xspi.html)
- [ST33KTPM2X](https://www.st.com/en/secure-mcus/st33ktpm2x.html)
- [ST33KTPM2I](https://www.st.com/en/secure-mcus/st33ktpm2i.html)

## Key Benefits
- Proven and standardized security solution
- High assurance based on Common Criteria, TCG and FIPS 140 certifications
- Easy integration with Windows, Linux OS and TCG TPM Software Stack
- Cryptographic services with improved performance
- Firmware upgradable to new standardized features and cryptography

## Key Features
- TCG TPM 2.0 latest specifications compliant (Rev. 1.59)
- Extended cryptography support  (up to RSA 4096, ECC NIST P256 & P384, EC BN256, SHA1, SHA2-256 & 384, SHA3-256 & 384, AES 128-192-256)
- TCG compliant SPI or I²C interface selectable dynamically
- Non-volatile memory (200 kB)
- TPM firmware upgrade through fault tolerant loading process
- TPM firmware & critical data self-recovery (NIST SP800-193)
- Consumer and Industrial JESD-47 qualifications
- Available in thin UFQFPN32 standard package and small footprint package WLCSP24
- Extended operating temperature range (-40°C to 105°C)

## Application notes
- [Integrating the STSAFE-TPM trusted platform modules with Linux®](https://www.st.com/resource/en/application_note/an5714-integrating-the-stsafetpm-trusted-platform-modules-with-linux-stmicroelectronics.pdf)

## STM32MP1x-DK platform intergration
To integrate STSAFE-TPM products on
- [STM32MP157F-DK2](https://www.st.com/en/evaluation-tools/stm32mp157f-dk2.html) board.
- [STM32MP135F-DK](https://www.st.com/en/evaluation-tools/stm32mp135f-dk.html) board.
  
please go to dedicated github : [X-LINUX-TPM](https://github.com/STMicroelectronics/meta-st-x-linux-tpm)

The X-LINUX-TPM expansion package is available on [X-LINUX-TPM wiki article](https://wiki.st.com/stm32mpu/wiki/X-LINUX-TPM_expansion_package).

## STMicroelectronics Open Source Projects
- [I²C driver](https://github.com/STMicroelectronics/TCG-TPM-I2C-DRV) for Linux kernel versions before 6.1




