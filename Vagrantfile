Vagrant::Config.run do |config|
  config.vm.box = "python"
  config.vm.box_url = "http://dl.dropbox.com/u/29645873/vagrants/pandas.box"

  # config.vm.boot_mode = :gui
  config.ssh.forward_x11 = true

  config.vm.forward_port 8888, 8888
end
