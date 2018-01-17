#  Mirror of www.stanford.edu/news 

Mirror: https://wgetsnaps.github.io/stanford-edu-news/news/

Original: https://www.stanford.edu/news/

```sh
wget --page-requisites \
     --no-parent \
     --timestamping \
     --convert-links \
     --no-host-directories \
     --adjust-extension \
     --output-file /dev/stdout \
     https://www.stanford.edu/news/ \
     | tee ./wget.log
```