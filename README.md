golang-vim
==========

###golang tools for vim  
git clone https://github.com/ifels/golang-vim
cd golang-vim
git submodule update --init --recursive

cp -rf code.google.com $GOPATH/src/  
cp -rf github.com $GOPATH/src/  

go get github.com/jstemmer/gotags  
go get github.com/nsf/gocode  
go get code.google.com/p/go.tools/cmd/goimports  
