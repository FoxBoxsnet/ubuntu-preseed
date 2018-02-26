# ubuntu-preseed


- BOOT SEQUENCE CONFIGURATIONS START
  - layoutcode: `jp`
  - modelcode: `jp106`


- Network settings
  - Static IP

- Select a mirror to download the Installer package
  - Mirror Server: `jp.archive.ubuntu.com`

- Clock and time zone setup
  - TImeZone: `Asia/Tokyo`
  - NTP Server: `ntp.nict.jp`


- Account setup
  - Root account setup
    - username: `root`
    - password: `password`

  - To create a normal user account
    - username: `user`
    - password: `password`

- This first command is run as early as possible, just after
  - Packeage
    - This first command is run as early as possible, just after
      - openssh-server
    - bash-completion
    - curl
    - wget
    - psmisc
    - sshpass
    - tree
    - unzip
    - vim
    - zip
