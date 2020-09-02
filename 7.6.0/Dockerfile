FROM elasticsearch:7.6.0
RUN elasticsearch-plugin install --batch analysis-phonetic
ENV discovery.type single-node
ENV expack.security.enabled false
