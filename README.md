-name: intro to ansible-palybook
  hosta: all
  tasks:
    -name: print hello
      ansible.builtin.debug
      msg: hello
    -name: print fruit
      debug
      msg: apple