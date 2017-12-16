# packer-linux
packer scripts to create Linux AMI

Base-Linux folder consist of base-linux which has below requirments 

AMI Based on the Amazon Linux minimal AMI

1.Installation and configuration of SELINUX
2.Has the root account shell removed, so no root login available
3.Has all unnecessary services and ports removed. This includes, but is not limited to, sendmail and postfix
4.Applies all current Yum updates
