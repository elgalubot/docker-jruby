# Changelog

Note sha256 digests are generated after pushing the image to the registry therefore the last version of this docker-selenium will always have digest TBD (to be determined) but will be updated manually at [releases][]

Note image ids also change after scm-source.json has being updated which triggers a cyclic problem so value TBD will be set here and updated in the [releases][] page by navigating into any release tag.

###### To get container versions
    docker exec jruby versions

## TBD_DOCKER_TAG
 + Date: TBD_DATE
 + TBD_COMMIT_MSG
 + Image tag details:
  + Timezone: TBD_TIME_ZONE
  + FROM ubuntu:UBUNTU_FLAVOR-UBUNTU_DATE
  + JRuby: TBD_JRUBY_VERSION
  + Tested on kernel dev host: 4.4.0-23-generic x86_64
  + Tested on kernel CI  host: TBD_HOST_UNAME
  + Built at dev host with: Docker version 1.11.2, build b9f10c9
  + Built at CI  host with: Docker version TBD_DOCKER_VERS, build TBD_DOCKER_BUILD
  + Image size: TBD_IMAGE_SIZE
  + Digest: TBD_DIGEST
  + Image ID: TBD_IMAGE_ID

[releases]: https://github.com/elgalu/docker-jruby/releases/
