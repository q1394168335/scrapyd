FROM python:3.6
COPY scrapyd.conf /etc/scrapyd/scrapyd.conf
RUN pip install scrapyd -i https://pypi.tuna.tsinghua.edu.cn/simple/
CMD scrapyd
