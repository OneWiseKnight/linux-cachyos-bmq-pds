# This REPO is for my personal use, this is a personal project for personal use.

# linux-cachyos-pds
Cachy Kernel with the PDS Scheduler by default however BMQ Scheduler is available if selected for Linux Kernel 7.0.6 via the PKGBUILD.

> [!Caution]
> Currently there is no PDS version of Cachyos Kernel for Linux 7, so this is a temporary solution. All the patches used are for my personal use so if you have any issues just understand this is a personal project and has nothing to do with Cachyos, or anything related outside this repository. If you would like to compile the BMQ Cachy PKGBUILD version make sure to set CONFIG_SCHED_POC_SELECTOR=n in the config file.

## Currently only Kernel versions supported is 7.0.6

> [!NOTE]
> Lots of code was removed from the Cachy patches to accommodate other patches for my personal preference.

## How to Make the Kernel
1) Download the repo
2) Open terminal in the folder containing the PKGBUILD file
3) Edit the PKGBUILD file if your interested in the PDS scheduler, default is BMQ.
3) Type the command
```
makepkg
```

## Thanks
- Thanks to the Cachyos team for always keeping things up to date with the Kernel, and PKGBUILD's. If this repo causes any issues with the Cachyos Repo, this repo will easily be taken down.

- Thanks to Xanmod for a lot of the patches!

- Thanks to Alfred Chen for pushing forward with the BMQ/PDS Project!
