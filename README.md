golang-godep-env
================

golang 1.3.3

cd <SOURCE-DIR>
docker run --rm -v "$(pwd)":/go/<NAME> -w /go/<NAME> carlsaturnino/golang-godep-env make
