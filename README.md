# remastering-linux-caleumOS

## CaleumOS ISO

The 7.46 GB ISO is stored as four Git LFS parts because GitHub limits each LFS file to 2 GB on Free/Pro plans.

After cloning the repository with Git LFS installed, rebuild the ISO in Windows Command Prompt from this folder:

```cmd
copy /b CaleumOS.iso.part-00+CaleumOS.iso.part-01+CaleumOS.iso.part-02+CaleumOS.iso.part-03 CaleumOS.iso
```

Screenshots of the running system will be added here when available.
