we can use chose scripts to manager boards in openlab

configure file: 
boardlab.cfg: some config info for openlab.
boards.cfg: config info for boards.
serial.cfg: include serial info 
power.cfg: power config info for boards with bmc.
user.cfg: user info and which the boards be used.
ser2net.conf: the configure file for ser2net service.

manager scripts:
board_check: check configure info.
board_connect: connect the board's serial.
board_reboot: reset power on boards.
intall.sh: install service and script to localhost.
ap7921-control: control script on power for pdu.
gencfg.sh: generate default grub.cfg.
inituser: set init environment for new user.
newuser: add new user base on user.cfg
board_list: show the boards be used by current account 
cp_rootfs.sh: cp and extract rootfs 
board_op: function used by board_reboot
