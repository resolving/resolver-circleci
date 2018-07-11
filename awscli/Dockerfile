# https://circleci.com/docs/2.0/circleci-images/#pre-installed-tools
# https://circleci.com/docs/2.0/circleci-images/#other-packages
# https://circleci.com/docs/2.0/circleci-images/#python
FROM circleci/python

# CONSIDER: `sudo` look harmfull, maybe pip virtual env is more appropriate
RUN sudo pip install awscli

ENTRYPOINT ["aws"]

CMD ["--version"]
