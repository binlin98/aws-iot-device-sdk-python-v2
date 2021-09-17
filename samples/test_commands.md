## Test Command for ThingTest
python aws-iot-device-sdk-python-v2/samples/pubsub.py --endpoint a2lq4mfqqgidoc-ats.iot.us-east-2.amazonaws.com --root-ca root-CA.crt --cert ThingTest.cert.pem --key ThingTest.private.key
## Test Command for ThingOne
python aws-iot-device-sdk-python-v2/samples/pubsub.py --endpoint a2lq4mfqqgidoc-ats.iot.us-east-2.amazonaws.com --root-ca root-CA.crt --cert ThingOne_certificate.pem.crt --key ThingOne_private.pem.key
## Shadow Test Command for ThingTest
python aws-iot-device-sdk-python-v2/samples/shadow.py --endpoint a2lq4mfqqgidoc-ats.iot.us-east-2.amazonaws.com --root-ca root-CA.crt --cert ThingTest.cert.pem --key ThingTest.private.key --thing-name "ThingTest"
## Shadow Test Command for ThingOne
python aws-iot-device-sdk-python-v2/samples/shadow.py --endpoint a2lq4mfqqgidoc-ats.iot.us-east-2.amazonaws.com --root-ca root-CA.crt --cert ThingOne_certificate.pem.crt --key ThingOne_private.pem.key --thing-name "ThingOne"