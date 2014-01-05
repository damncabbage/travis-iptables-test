task :default do
  [
    'iptables -L',
    'sudo iptables -L',
  ].each do |cmd|
    puts "\n** Executing `#{cmd}`..."
    puts `#{cmd}`
    puts "Exit code: #{$?.to_i}"
  end
end
