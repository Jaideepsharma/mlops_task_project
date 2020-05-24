FROM centos

RUN yum install -y python36 

RUN pip3 install numpy

RUN pip3 install keras

RUN yum install -y python36-devel

RUN pip3 install tensorflow

RUN pip3 install pandas

CMD ["python3","mlops_task_project/cnn_code.py"]
