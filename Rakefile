IMAGE_TAG = ENV['IMAGE_TAGE'] || 'aventinesolutions/docker-archlinux-rvm'

task default: :build

desc 'build Aventine Ruby RVM docker'
task :build do
  fail 'Docker build failed' unless system "docker build --tag #{IMAGE_TAG} ."
end


