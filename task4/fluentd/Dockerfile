FROM fluent/fluentd:v1.16-1

USER root
# install the compatible version
RUN gem install fluent-plugin-elasticsearch -v 5.3.0 --no-document
RUN gem install fluent-plugin-concat --no-document

USER fluent
