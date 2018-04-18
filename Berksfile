# -*- mode: ruby -*-
source "https://supermarket.getchef.com"

metadata

cookbook "python",
    github: "https://github.com/EduardFazliev/python"

cookbook "git"
cookbook "build-essential"
cookbook "runit"

group :integration do
  cookbook "apt"
  cookbook "yum"
  cookbook "minitest-handler"
  cookbook "diamond_test", path: "test/cookbooks/diamond_test"
end
