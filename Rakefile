# Rakefile

require "./lib/collector"

task :collect_all do
  collector = Collector::Client.new

  collector.collect_all
  collector.send_data
end
