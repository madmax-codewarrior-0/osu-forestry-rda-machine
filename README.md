# osu-forestry-rda-machine
A collection of notes, configs, and setup steps for the Forestry RDA machine. Provisioned and installed by Max for the College of Forestry.

Contact Info:
Maximillian Schmidt (he, his, him)
Faculty Research Assistant - Computational Scientist
Center for Quantitative Life Sciences (CQLS) & OSU Open Source Lab (OSL)
Oregon State University
https://cqls.oregonstate.edu  ~  https://osuosl.org

Email: max@cqls.oregonstate.edu, schmidtm@osuosl.org

 Comments are denoted inside hash-parenthesis `#( Like this! )`

## 1. BIOS Settings

<details><summary><b> General </b></summary>

#### Boot Sequence: 

    Boot Sequence: ubuntu, Windows Boot Manager

    Boot List Option: UEFI

#### Advanced Boot Options:

- [X] Enable Legacy Option ROMs
- [ ] Enable Attempt Legacy Boot

#### UEFI Boot Path Security:

- [X] Always, Except Internal HDD
- [ ] Always
- [ ] Never

#### Date/Time - N/A
</details>
    
<details><summary><b> System Configuration </b></summary>

#### Integrated NIC:

- [X] Enable UEFI Network Stack

- [ ] Disabled 
- [X] Enabled 
- [ ] Enabled w/PXE

#### Serial Port - N/A

#### SATA Operation:

- [ ] Disabled 
- [ ] AHCI
- [X] RAID On

#### SATA Drives: All checked

#### PCIE Drives: All checked

#### Smart Reporting:

- [X] Enable SMART Reporting `#( Checks health of drives on POST before an OS boots, to warn users. )`

#### USB Configuration: All checked

#### Front USB Configuration: All checked

#### Rear USB Configuration: All checked

#### Internal USB Configuration: All checked

#### Thunderbolt Adapter Configuration:

- [] Enable Thunderbolt Technology Support

#### USB Powershare:

- [ ] Enable USB Powershare `#( Users shouldn't be attaching devices with their own batteries to charge. )`

#### Audio:

- [X] Enable Audio
  - [X] Enable Microphone
  - [X] Enable Internal Speaker

#### Memory Map IO above 4GB:

- [X] Memory Map IO above 4GB

#### HDD Fans - N/A

#### Miscellaneous Devices:

- [X] Enable PCI Slot
- [ ] Secure Digital (SD) Card Boot 
- [ ] Enable Secure Digital (SD) Card `#( Doubtful that any data is being processed from SD cards. Enable if different. )`
- [ ] Secure Digital (SD) Card Read-Only Mode

#### Intel VMD Technology:

- [X] PCIE0
- [X] PCIE1
- [X] Auto
- [ ] Disabled

</details>

<details><summary><b> Video </b></summary>

#### Primary Video Slot:
    
- [X] Auto
- [ ] Slot 1
- [ ] Slot 2
- [ ] Slot 3
- [ ] Slot 4 *
- [ ] Slot 5
- [ ] Slot 6

 `#( * 'NVIDIA HD Graphics' will be shown on the active slot. Recommended: Slot 4 (see below) )`
    
</details>

<details><summary><b> Security </b></summary>

#### Admin Password: Not Set
    
</details>
