# Elasticsearch Index Templates

## kvs
ESではデフォルトで全文検索がONになっているので、それをあえてデフォルトOFFにしてKey Valueストアのように使うためのテンプレート。メモリやディスクの使用量を削減するために役立つ。

Field名の末尾を_textなどにすれば全文検索できるようになるので、必要に応じて設定する。
