# https://circleci.com/docs/2.0/circleci-images/#pre-installed-tools
# https://circleci.com/docs/2.0/circleci-images/#other-packages
# https://circleci.com/docs/2.0/circleci-images/#python
FROM circleci/python

ENV AWSCLI_VERSION 1.11.13-1

RUN sudo apt-get -y -qq install awscli=$AWSCLI_VERSION

ENTRYPOINT ["aws"]

CMD ["--version"]
