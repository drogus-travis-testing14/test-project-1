require 'rake'

task :test do
  puts "Using RUBY_VERSION: #{RUBY_VERSION}"

#  ENV.keys.sort.each do |key|
#    puts "#{key}: #{ENV[key]}"
#  end

  1.upto(1) do
    sleep(1)
    putc '.'
    $stdout.flush
  end
end

task :default => :test
