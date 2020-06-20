# aws-iot-rpi4-sensehat

Place script in the aws-iot-device-sdk-python-v2/samples directory.

Execute

```
python3.5 aws-iot-device-sdk-python-v2/samples/pubsub_sensehat.py --endpoint <endpoint>.iot.<region>.amazonaws.com --root-ca root-CA.crt --cert <mycert>.cert.pem --key <mycert>.private.key --client-id basicPubSub --topic sdk/test/Python --count 0
```