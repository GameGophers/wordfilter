#word filter service
base on https://github.com/huichen/sego

# install
install gpm, gvp first        
$go get -u https://github.com/GameGophers/wordfilter/        
$cd wordfilter     
$source gvp        
$gpm       
$go install wordfilter         

#install with docker
$docker build -t wordfilter .     