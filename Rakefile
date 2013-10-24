
PROJECT_NAME = "RakeExample"

desc "Config #{PROJECT_NAME}"
task :config do
    puts "\nConfiguring #{PROJECT_NAME}"
end

desc "Clean #{PROJECT_NAME}"
task :clean do
    puts "\nCleaning #{PROJECT_NAME}"

    #rakefiles = FileList[""]
    #rakefiles.exclude("something")
    #rakefiles.each do |rakefile|
    #    FileUtils.rm_rf("#{rakefile}")
    #end
end

desc "Clean intermediate files in #{PROJECT_NAME}"
task :distclean do
    puts "\nCleaning intermediate files in #{PROJECT_NAME}"
end

desc "Build #{PROJECT_NAME}"
task :build do
    puts "\nBuilding #{PROJECT_NAME}"
end

desc "nDistribute #{PROJECT_NAME}"
task :dist do
    puts "\nDistributing #{PROJECT_NAME}"
end

task :default do
    sh('rake -T')
end
