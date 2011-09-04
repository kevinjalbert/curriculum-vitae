require 'rake/clean'
CLEAN.include('./src/*.aux')
CLEAN.include('./src/*.log')
CLEAN.include('./src/*.out')
CLEAN.include('./src/*.pdf')
CLEAN.include('./src/*.dvi')

task :default => :list

task :list do
  system 'rake -T'
end

desc "Compiles the CV using latex"
task :dvi do
  system 'latex --output-directory ./src ./src/*.tex'
end

desc "Compiles the CV using pdflatex"
task :pdf do
  system 'pdflatex --output-directory ./src ./src/*.tex'
end

desc "Compiles the CV using latex and pdflatex"
task :all do
  system 'pdflatex --output-directory ./src ./src/*.tex'
  system 'latex --output-directory ./src ./src/*.tex'
end
