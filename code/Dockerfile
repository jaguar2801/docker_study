FROM continuumio/anaconda3
RUN conda install python=3.7
WORKDIR /workspace
CMD jupyter-lab --no-browser \
  --port=8888 --ip=0.0.0.0 --allow-root
RUN git clone https://github.com/rasbt/python-machine-learning-book-2nd-edition