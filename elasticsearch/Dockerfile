ARG ELK_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/elasticsearch/elasticsearch:${ELK_VERSION}

# Add your elasticsearch plugins setup here
# Example: RUN elasticsearch-plugin install analysis-icu

# RUN echo y | elasticsearch-plugin install https://github.com/medcl/elasticsearch-analysis-ik/releases/download/v7.11.1/elasticsearch-analysis-ik-7.11.1.zip 
# RUN echo y | elasticsearch-plugin install https://github.com/medcl/elasticsearch-analysis-pinyin/releases/download/v7.11.1/elasticsearch-analysis-pinyin-7.11.1.zip
RUN echo y | elasticsearch-plugin install https://malljh.oss-cn-beijing.aliyuncs.com/soft/elasticsearch-analysis-ik-7.11.1.zip
RUN echo y | elasticsearch-plugin install https://malljh.oss-cn-beijing.aliyuncs.com/soft/elasticsearch-analysis-pinyin-7.11.1.zip
