IMAGE_NAME     = "nullstyle/rbenv"

task :build do
  system("docker build -t #{IMAGE_NAME} .")
end

task :run do
  exec("docker run -i -t --rm #{IMAGE_NAME}")
end

task :bash do
  exec("docker run -i -t --rm #{IMAGE_NAME} /bin/bash")
end