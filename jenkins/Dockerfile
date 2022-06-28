#
#  Author: Sushma Pawar
#  Date: 2022-06-28 10:58:07 +0000 (Thu, 20 Jan 2022)
#
#  vim:ts=4:sts=4:sw=4:et
#
#  https://github.com/sushmapawar-mengade/jenkins/Dockerfiles
#
#  If you're using my code you're welcome to connect with me on LinkedIn and optionally send me feedback to help improve or steer this or other code I publish
#

# nosemgrep: dockerfile.audit.dockerfile-source-not-pinned.dockerfile-source-not-pinned
FROM jenkins/jenkins:lts

RUN /bin/jenkins-plugin-cli --plugins workflow-aggregator:2.6
