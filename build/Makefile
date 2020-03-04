all:
	mkdir -p b
	sudo docker build -t altertech/pytpl-builder .
	sudo docker run -v `pwd`/b:/b -i -t altertech/pytpl-builder cp /build.tar /b/
	mv -f ./b/build.tar ../run/
