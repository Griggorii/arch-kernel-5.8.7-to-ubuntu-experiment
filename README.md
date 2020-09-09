# arch-kernel-5.8.7-to-ubuntu-experiment
 arch kernel 5.8.7 to ubuntu kernel , experiment
                                                          Griggorii@gmail.com

                                           arch kernel 5.8.7 to ubuntu experiment

Download https://git.archlinux.org/linux.git/commit/?h=v5.8.7-arch1&id=13c2d5cc731142ffd8f22aec0e644dcd99b78940 inpack 	linux-13c2d5cc731142ffd8f22aec0e644dcd99b78940.tar.gz rename folder to 5.8.7-arch1

view hidden file all file copy kernel 5.8.7-arch1-1 .config .config.old debian makifile version to folder kernel 5.8.7-arch1


sudo apt update && sudo apt --reinstall install libelf-dev flex bison build-essential libc-dev libc6-dev gcc g++ dpkg-dev bc fakeroot libncurses5-dev libssl-dev git make -y

Command terminal command in folder 5.8.7-arch1 paste enter:

dpkg-buildpackage -rfakeroot -b

____________________________________________________________________________________________________

alternative clang command: 

make ARCH=x86_64 CC=clang LLVM_IAS=1 LLVM=1 -j16 bindeb-pkg


