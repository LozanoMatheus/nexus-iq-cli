# GO Example:

```bash
go mod init
go generate
java -jar /opt/nexus-iq-cli-1.64.0-02.jar -i my_app_id -a user:pass -r result.json -s https://my_iqs_server -t build go.sum
```

# Python Example:

```bash
pip install -U --no-cache-dir pipreqs ; pipreqs --force ./
java -jar /opt/nexus-iq-cli-1.64.0-02.jar -i my_app_id -a user:pass -r result.json -s https://my_iqs_server -t build requirements.txt
```
