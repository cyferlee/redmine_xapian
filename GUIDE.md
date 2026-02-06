```
apt install xapian-omega
```
```
apt install xapian-omega libxapian-dev poppler-utils \
    antiword unzip catdoc pandoc libwpd-tools libwps-tools gzip unrtf catdvi \
    djview djview3 uuid uuid-dev xz-utils libemail-outlook-message-perl
```

В папке редмайна:
```
ruby plugins/redmine_xapian/extra/xapian_indexer.rb -f
```