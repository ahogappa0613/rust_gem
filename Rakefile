# frozen_string_literal: true

require "bundler/gem_tasks"
require "rb_sys/extensiontask"

task build: :compile

RbSys::ExtensionTask.new("rust_gem") do |ext|
  ext.lib_dir = "lib/rust_gem"
end

task default: :compile
