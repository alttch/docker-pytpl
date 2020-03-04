all:
	mkdir -p b
	docker build -t altertech/pytpl-builder .
	docker run -v `pwd`/b:/b -i -t altertech/pytpl-builder cp /build.tar /b/
	mv -f ./b/build.tar ../run/
