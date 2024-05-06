npm install --legacy-peer-deps

npm  start

npm run build

#清理构建文件,删除build目录中所有的map文件
git终端mingw64>find . -name "*.map" -type f -delete
cmd>for /r build %i in (*.map) do del /f "%i"





#cmd例子:
#显示test目录中所有的map文件
#for /r test %i in (*.map) do @echo %i
#显示test目录中所有的txt,jpg和map文件
#for /r test %i in (*.txt,*.jpg,*.js) do @echo %i