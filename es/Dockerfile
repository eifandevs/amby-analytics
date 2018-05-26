FROM elasticsearch:5.6.9

# install x-pack
RUN elasticsearch-plugin  install --batch x-pack

# install kuromoji
RUN elasticsearch-plugin  install analysis-kuromoji