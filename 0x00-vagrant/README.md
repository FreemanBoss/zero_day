The command uname is liken to other shell commands which fall into *executable program* command. This kind of command is different to *shell built-in commands* in that they are writen program which are made accessible globally by configuring them in the `/usr/bin/` configuration directory.
     Using the command alone displays the *kernel name* i.e the kernel the system operating system works on. For instance, on an Ubuntu system it output `Linux`. To explore this command more, I will privide the `man --help` output here;

     -a, --all                print all information, in the following order,
                             except omit -p and -i if unknown:
  -s, --kernel-name        print the kernel name
  -n, --nodename           print the network node hostname
  -r, --kernel-release     print the kernel release
  -v, --kernel-version     print the kernel version
  -m, --machine            print the machine hardware name
  -p, --processor          print the processor type (non-portable)
  -i, --hardware-platform  print the hardware platform (non-portable)
  -o, --operating-system   print the operating system
      --help     display this help and exit
      --version  output version information and exit