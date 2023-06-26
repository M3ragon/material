# vlmcsd
## Microsoft KMS Activation
### Usage

Start a Command Prompt as an Administrator.
#### Windows

slmgr.vbs -ipk W269N-WFGWX-YVC9B-4J6C9-T83GX
slmgr.vbs -skms kms.srv.crsoo.com
slmgr.vbs -ato

#### Office

`cd C:\Program Files\Microsoft Office\Office15`
`cscript ospp.vbs /inpkey:YC7DK-G2NP3-2QQC3-J6H88-GVGXT`
`cscript ospp.vbs /sethst:kms.srv.crsoo.com`
`cscript ospp.vbs /act`

GVLKs

Authoritative source on Microsoft’s TechNet and Windows Server Activation Guide.

##### Windows 10

| Betriebssystem Edition                   | KMS Client Setup Key                          |
|-----------------------------------------|-----------------------------------------------|
| Windows 10 Core                         | TX9XD-98N7V-6WMQ6-BX7FG-H8Q99                |
| Windows 10 Core N                       | 3KHY7-WNT83-DGQKR-F7HPR-844BM                |
| Windows 10 Core Country Specific        | PVMJN-6DFY6-9CCP6-7BKTT-D3WVR                |
| Windows 10 Core Single Language         | 7HNRX-D7KGG-3K4RQ-4WPJ4-YTDFH                |
| Windows 10 Professional                  | W269N-WFGWX-YVC9B-4J6C9-T83GX                |
| Windows 10 Professional N                | MH37W-N47XK-V7XM9-C7227-GCQG9                |
| Windows 10 Enterprise                    | NPPR9-FWDCX-D2C8J-H872K-2YT43                |
| Windows 10 Enterprise N                  | DPH2V-TTNVB-4X9Q3-TJR4H-KHJW4                |
| Windows 10 Education                     | NW6C2-QMPVW-D7KKK-3GKT6-VCFB2                |
| Windows 10 Education N                   | 2WH4N-8QGBV-H22JP-CT43Q-MDWWJ                |
| Windows 10 Enterprise 2015 LTSB          | WNMTR-4C88C-JK8YV-HQ7T2-76DF9                |
| Windows 10 Enterprise 2015 LTSB N        | 2F77B-TNFGY-69QQF-B8YKP-D69TJ                |
| Windows 10 Enterprise 2016 LTSB          | DCPHK-NFMTC-H88MJ-PFHPY-QJ4BJ                |
| Windows 10 Enterprise 2016 LTSB N        | QFFDN-GRT3P-VKWWX-X7T3R-8B639                |

##### Windows 8 / 8.1

| Betriebssystem Edition                            | KMS Client Setup Key                          |
|--------------------------------------------------|-----------------------------------------------|
| Windows 8 Professional                            | NG4HW-VH26C-733KW-K6F98-J8CK4                |
| Windows 8 Professional N                          | XCVCF-2NXM9-723PB-MHCB7-2RYQQ                |
| Windows 8 Enterprise                              | 32JNW-9KQ84-P47T8-D8GGY-CWCK7                |
| Windows 8 Enterprise N                            | JMNMF-RHW7P-DMY6X-RF3DR-X2BQT                |
| Windows Embedded 8 Industry Professional          | RYXVT-BNQG7-VD29F-DBMRY-HT73M                |
| Windows Embedded 8 Industry Enterprise            | NKB3R-R2F8T-3XCDP-7Q2KW-XWYQ2                |
| Windows 8.1 Professional                          | GCRJD-8NW9H-F2CDX-CCM8D-9D6T9                |
| Windows 8.1 Professional N                        | HMCNV-VVBFX-7HMBH-CTY9B-B4FXY                |
| Windows 8.1 Enterprise                            | MHF9N-XY6XB-WVXMC-BTDCT-MKKG7                |
| Windows 8.1 Enterprise N                          | TT4HM-HN7YT-62K67-RGRQJ-JFFXW                |
| Windows Embedded 8.1 Industry Pro                 | NMMPB-38DD4-R2823-62W8D-VXKJB                |
| Windows Embedded 8.1 Industry Enterprise           | FNFKF-PWTVT-9RC8H-32HB2-JB34X                |

##### Windows 7

| Betriebssystem Edition  | KMS Client Setup Key                          |
|------------------------|-----------------------------------------------|
| Windows 7 Professional | FJ82H-XT6CR-J8D7P-XQJJ2-GPDD4                |
| Windows 7 Professional N | MRPKT-YTG23-K7D7T-X2JMM-QY7MG                |
| Windows 7 Professional E | W82YF-2Q76Y-63HXB-FGJG9-GF7QX                |
| Windows 7 Enterprise   | 33PXH-7Y6KF-2VJC9-XBBR8-HVTHH                |
| Windows 7 Enterprise N | YDRBP-3D83W-TY26F-D46B2-XCKRJ                |
| Windows 7 Enterprise E | C29WB-22CC8-VJ326-GHFJW-H9DH4                |

##### Windows Server 2022

| Betriebssystem Edition           | KMS Client Setup Key                          |
|----------------------------------|-----------------------------------------------|
| Windows Server 2022 Datacenter   | WX4NM-KYWYW-QJJR4-XV3QB-6VM33                 |
| Windows Server 2022 Standard     | VDYBN-27WPP-V4HQT-9VMD4-VMK7H                 |

##### Windows Server 2019

| Betriebssystem Edition           | KMS Client Setup Key                          |
|----------------------------------|-----------------------------------------------|
| Windows Server 2019 Datacenter   | WMDGN-G9PQG-XVVXX-R3X43-63DFG                 |
| Windows Server 2019 Standard     | N69G4-B89J2-4G8F4-WWYCC-J464C                 |
| Windows Server 2019 Essentials   | WVDHN-86M7X-466P6-VHXV7-YY726                 |

##### Windows Server 2016

| Betriebssystem Edition           | KMS Client Setup Key                          |
|----------------------------------|-----------------------------------------------|
| Windows Server 2016 Datacenter   | CB7KF-BWN84-R7R2Y-793K2-8XDDG                 |
| Windows Server 2016 Standard     | WC2BQ-8NRM3-FDDYY-2BFGV-KHKQY                 |
| Windows Server 2016 Essentials   | JCKRF-N37P4-C2D82-9YXRT-4M63B                 |

##### Windows Server 2012

| Betriebssystem Edition                    | KMS Client Setup Key                          |
|-------------------------------------------|-----------------------------------------------|
| Windows Server 2012                       | BN3D2-R7TKB-3YPBD-8DRP2-27GG4                 |
| Windows Server 2012 N                     | 8N2M2-HWPGY-7PGT9-HGDD8-GVGGY                 |
| Windows Server 2012 Single Language       | 2WN2H-YGCQR-KFX6K-CD6TF-84YXQ                 |
| Windows Server 2012 Country Specific      | 4K36P-JN4VD-GDC6V-KDT89-DYFKP                 |
| Windows Server 2012 Server Standard       | XC9B7-NBPP2-83J2H-RHMBY-92BT4                 |
| Windows Server 2012 MultiPoint Standard   | HM7DN-YVMH3-46JC3-XYTG7-CYQJJ                 |
| Windows Server 2012 MultiPoint Premium    | XNH6W-2V9GX-RGJ4K-Y8X6F-QGJ2G                 |
| Windows Server 2012 Datacenter            | 48HP8-DN98B-MYWDG-T2DCC-8W83P                 |
| Windows Server 2012 R2 Server Standard    | D2N9P-3P6X9-2R39C-7RTCD-MDVJX                 |
| Windows Server 2012 R2 Datacenter         | W3GGN-FT8W3-Y4M27-J84CP-Q3VJ9                 |
| Windows Server 2012 R2 Essentials         | KNC87-3J2TX-XB4WP-VCPJV-M4FWM                 |

##### Windows Server 2008

| Betriebssystem Edition                            | KMS Client Setup Key                          |
|---------------------------------------------------|-----------------------------------------------|
| Windows Server 2008 Web                           | WYR28-R7TFJ-3X2YQ-YCY4H-M249D                 |
| Windows Server 2008 Standard                      | TM24T-X9RMF-VWXK6-X8JC9-BFGM2                 |
| Windows Server 2008 Standard ohne Hyper-V         | W7VD6-7JFBR-RX26B-YKQ3Y-6FFFJ                 |
| Windows Server 2008 Enterprise                    | YQGMW-MPWTJ-34KDK-48M3W-X4Q6V                 |
| Windows Server 2008 Enterprise ohne Hyper-V       | 39BXF-X8Q23-P2WWT-38T2F-G3FPG                 |
| Windows Server 2008 HPC                           | RCTX3-KWVHP-BR6TB-RB6DM-6X7HP                 |
| Windows Server 2008 Datacenter                    | 7M67G-PC374-GR742-YH8V4-TCBY3                 |
| Windows Server 2008 Datacenter ohne Hyper-V       | 22XQ2-VRXRG-P8D42-K34TD-G3QQC                 |
| Windows Server 2008 für Itanium-basierte Systeme   | 4DWFP-JF3DJ-B7DTH-78FJB-PDRHK                 |
| Windows Server 2008 R2 Web                         | 6TPJF-RBVHG-WBW2R-86QPH-6RTM4                 |
| Windows Server 2008 R2 HPC Edition                 | TT8MH-CG224-D3D7Q-498W2-9QCTX                 |
| Windows Server 2008 R2 Standard                    | YC6KT-GKW9T-YTKYR-T4X34-R7VHC                 |
| Windows Server 2008 R2 Enterprise                  | 489J6-VHDMP-X63PK-3K798-CPX3Y                 |
| Windows Server 2008 R2 Datacenter                  | 74YFP-3QFB3-KQT8W-PMXWJ-7M648                 |
| Windows Server 2008 R2 für Itanium-basierte Systeme | GT63C-RJFQ3-4GMB6-BRFB9-CB83V                 |

##### Office LTSC 2021

| Product                           | GVLK                                      |
|-----------------------------------|-------------------------------------------|
| Office LTSC Professional Plus 2021 | FXYTK-NJJ8C-GB6DW-3DYQT-6F7TH             |
| Office LTSC Standard 2021         | KDX7X-BNVR8-TXXGX-4Q7Y8-78VT3             |
| Project Professional 2021         | FTNWT-C6WBT-8HMGF-K9PRX-QV9H8             |
| Project Standard 2021             | J2JDC-NJCYY-9RGQ4-YXWMH-T3D4T             |
| Visio LTSC Professional 2021      | KNH8D-FGHT4-T8RK3-CTDYJ-K2HT4             |
| Visio LTSC Standard 2021          | MJVNY-BYWPY-CWV6J-2RKRT-4M8QG             |
| Access LTSC 2021                  | WM8YG-YNGDD-4JHDC-PG3F4-FC4T4             |
| Excel LTSC 2021                   | NWG3X-87C9K-TC7YY-BC2G7-G6RVC             |
| Outlook LTSC 2021                 | C9FM6-3N72F-HFJXB-TM3V9-T86R9             |
| PowerPoint LTSC 2021              | TY7XF-NFRBR-KJ44C-G83KF-GX27K             |
| Publisher LTSC 2021               | 2MW9D-N4BXM-9VBPG-Q7W6M-KFBGQ             |
| Skype for Business LTSC 2021      | HWCXN-K3WBT-WJBKY-R8BD9-XK29P             |
| Word LTSC 2021                    | TN8H9-M34D3-Y64V9-TR72V-X79KV             |

##### Office 2019

| Product                        | GVLK                                      |
|--------------------------------|-------------------------------------------|
| Office Professional Plus 2019 | NMMKJ-6RK4F-KMJVX-8D9MJ-6MWKP             |
| Office Standard 2019          | 6NWWJ-YQWMR-QKGCB-6TMB3-9D9HK             |
| Project Professional 2019     | B4NPR-3FKK7-T2MBV-FRQ4W-PKD2B             |
| Project Standard 2019         | C4F7P-NCP8C-6CQPT-MQHV9-JXD2M             |
| Visio Professional 2019       | 9BGNQ-K37YR-RQHF2-38RQ3-7VCBB             |
| Visio Standard 2019           | 7TQNQ-K3YQQ-3PFH7-CCPPM-X4VQ2             |
| Access 2019                   | 9N9PT-27V4Y-VJ2PD-YXFMF-YTFQT             |
| Excel 2019                    | TMJWT-YYNMB-3BKTF-644FC-RVXBD             |
| Outlook 2019                  | 7HD7K-N4PVK-BHBCQ-YWQRW-XW4VK             |
| PowerPoint 2019               | RRNCX-C64HY-W2MM7-MCH9G-TJHMQ             |
| Publisher 2019                | G2KWX-3NW6P-PY93R-JXK2T-C9Y9V             |
| Skype for Business 2019       | NCJ33-JHBBY-HTK98-MYCV8-HMKHJ             |
| Word 2019                     | PBX3G-NWMT6-Q7XBW-PYJGG-WXD33             |
