task :default => :deploy
 
desc 'Deploy'
task :deploy do
  sh 'rsync -rtzh --progress --delete public/ blue:/home/kale/public_html/waybackletter.com/public/'
end

desc 'Sync Archive'
task :archive do
  sh 'rsync -rtzh --progress ~/dev/wayback/bin/archive/ ~/websites/waybackletter.com/public/archive/'
end
