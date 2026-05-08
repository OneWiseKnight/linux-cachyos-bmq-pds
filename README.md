# This REPO is for my personal use, this is a personal project for personal use.

# linux-cachyos-bmq or linux-cachyos-pds
Cachy Kernel with the BMQ Scheduler by default however PDS Scheduler is available if selected for Linux Kernel 7.0.5

> [!Caution]
> Currently there is no BMQ or PDS version of Cachyos Kernel for Linux 7, so this is a temporary solution. All the patches used are for my personal use so if you have any issues just understand this is a personal project and has nothing to do with Cachyos, or anything related outside this repository.

## Currently only Kernel versions supported is 7.0.5

> [!NOTE]
> For BMQ/PDS to work, **lots of code from patches needed to be removed** in terms of POC selector, Sched Fair, and anything that touched the scheduler so that BMQ/PDS could compile. So make sure you only use this PKGBUILD for BMQ and PDS only.

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
