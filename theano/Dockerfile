# Start with Ubuntu base image
FROM amazonlinux
  
RUN yum install -y gcc gcc-c++ make openssl-devel \
  gcc-gfortran \
  git \
  wget \
  atlas atlas-devel lapack-devel \
  blas-devel \
  python27-devel \
  python27-pip \
  python27-nose \
  python27-numpy \
  python27-scipy \
  && pip-2.7 install --upgrade pip \
  && python --version \
  && pip --version \
  && pip install --upgrade six \
  && pip install --upgrade --no-deps git+git://github.com/Theano/Theano.git
