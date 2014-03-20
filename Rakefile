require 'bundler'
Bundler.require(:default)

require 'active_record'


task "assets:precompile" do
  ActiveRecord::Base.establish_connection
  ActiveRecord::Base.connection.execute("")
end

task "assets:clean" do
end
