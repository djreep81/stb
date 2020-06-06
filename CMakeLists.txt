CMAKE_MINIMUM_REQUIRED(VERSION 2.8)
PROJECT(stb)
install(FILES "stb_image.h"   DESTINATION include/stb)
install(FILES "stb_vorbis.c"   DESTINATION include/stb)

#sync with upstream
# git remote add upstream https://github.com/nothings/stb
# git remote -v
# git fetch upstream
# git checkout master                       #forks master branch
# git merge upstream/master
# git push origin master
