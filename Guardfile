guard 'minitest' do

  # with Minitest::Spec
   watch(%r|^spec/(.*)_spec\.rb|)
   watch(%r|^lib/(.*)([^/]+)\.rb|)     { |m| "spec/#{m[1]}#{m[2]}_spec.rb" }
   watch(%r|^spec/spec_helper\.rb|)    { "spec" }

  # Rails 3.2
  # watch(%r|^app/controllers/(.*)\.rb|) { |m| "test/controllers/#{m[1]}_test.rb" }
  # watch(%r|^app/helpers/(.*)\.rb|)     { |m| "test/helpers/#{m[1]}_test.rb" }
  # watch(%r|^app/models/(.*)\.rb|)      { |m| "test/unit/#{m[1]}_test.rb" }  
  
  # Rails
  # watch(%r|^app/controllers/(.*)\.rb|) { |m| "test/functional/#{m[1]}_test.rb" }
  # watch(%r|^app/helpers/(.*)\.rb|)     { |m| "test/helpers/#{m[1]}_test.rb" }
  # watch(%r|^app/models/(.*)\.rb|)      { |m| "test/unit/#{m[1]}_test.rb" }  
end

guard 'coffeescript', :input => 'lib/frenzy_bunnies/web/public/js', :output => 'lib/frenzy_bunnies/web/public/js', :all_on_start => true
