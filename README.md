# springai-opensearch-vector-search-demo
# springai-opensearch-vector-search-demo

## to download certificate
```sh
openssl s_client -showcerts -connect localhost:9200 </dev/null | sed -n -e '/-.BEGIN/,/-.END/ p' > certifs.cer


```

 ## to import certificate

```sh

keytool -import -alias opensearchcert -file "C:\temp\certifs.cer" -keystore "C:\Program Files\Java\jdk-22\lib\security\cacerts"
```